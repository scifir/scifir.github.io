---
title: "C++ Scifir coding standards"
authors: ismaelc
date: 2023-08-30
categories: [start,informatics]
description: "Learn how to program scientific software in C++, following the point of view of Scifir."
---

Here are the C++ coding standards used inside scifir, and that can be used partially or totally in any project that uses the C++ libraries of Scifir. You can follow all of them, or some of them, depending on your needs.

## Nomenclature

- Use always **snake-case**, never camelCase, for all C++ names.
- Use upper-case for all the values of enum classes.

## Build and environment

- Use CMake as build tool, and CATCH for test cases and benchmarks.
- All test cases are placed inside the tests/ folder, under the root directory.
- Avoid to use any dependency if there's a similar solution with the standard library, then the code becomes more robust related to updates and needs less maintenance.
- If the project is a library, create test cases for all member-functions of all classes, and for all other functions.
- Use ctest for test cases. Add the label tests to all test cases in order to use 'ctest -L tests' to execute all test cases.
- Use ctest for benchmarks. Add the label benchmarks to all benchmarks in a manner equivalent as with tests.
- If the project is a library, document all classes and all other functions.
- Use cpack to create the packages for the different OS.
- Use ctest inside the repository where the project is hosted to test the uploaded code after every push, being it hosted in GitHub, GitLab, etc.

## Code implementation and software architecture

- Avoid virtual as possible, in favor of an implementation easier to use, and with less memory consumption.
- Avoid to use the CRTP with static member-variables, prefer to directly return the values inside the functions instead.
- Never make a member-variable private unless it's required that variable to don't be accessed from the outside. Also, unless a member-variable is private, don't add getters and setters of member-variables.
- Every enum must have type int8_t, unless it needs to have more elements than the number that int8_t allows, which usually never happens.
- Avoid to use abbreviations in names of classes and functions, because they are sometimes confusing to programmers.
- Use ICU for strings when it's needed and when the std::string class is not being enough to solve the problem.
- Use value and std::move() as better solution for sink arguments (if you don't understand that, learn about sink arguments in C++ through the web).
- Use references when possible, and not values, in the receiving variables that get the value of a function that returns by reference, in order to improve performance.

## ISOs

- Always use a code instead of an id when there's an ISO available for it.
- Use the ISO of languages for language codes.
- Use the ISO of countries for country codes.
- Use the ISO of currency for currency codes.

## Desktop and CLI applications

- Use libconfig for configuration files.
- Use XML for all file types, unless for some reason another markup language is simpler than XML for an specific file type.
- Use wxWidgets, GTK+ or Qt for the GUI.

## Documentation

- README.md should contain all the basic behavior of the library, without requiring the user to see the reference for any common doubt about the code.
- HISTORY.md should contain the history of the project, with all relevant information about which are the authors, the year the project started, and the central objectives and challenges that have appeared when developing it.
- DISCARDED_FEATURES.md should contain the list of all discarded features, as well as a detailed explanation of why each discarded feature has been discarded.
- CHANGELOG.md should contain a brief list of all major changes the project has faced. Only major changes should be listed there.
- All authors should be documented inside README.md, with their completed name, their national identification number, and any other id the author is using for research (like, for example, ORCID).
