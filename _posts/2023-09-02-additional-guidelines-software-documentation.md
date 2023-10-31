---
title:  "Additional guidelines for software documentation"
date:   2023-09-02
categories: informatics
authors: ismaelc
status: draft
---

Developing libraries I've arrived to new guidelines to document software, by detecting, through programming, falencies in the documentation of software. In this article I'll describe the new guidelines I've invented, which should be applied in lots of projects in order to have a better documentation for developers to know better how the code is.

## Developer's notes

Developer's notes is a section to explain any important feature or characteristic of the project that developers must know in order to work appropiately good on it.

## Internals - Philosophies and mechanisms

The **philosophies and mechanisms** can be described inside the "Internals" section of the documentation. The description of philosophies and mechanisms has to include all the important parts of the software, which usually inside common libraries and frameworks are just a few parts to describe. Those central parts can be important algorithms, important behaviors, and important needs of the objects that should not change. Usually, inside a library or framework, there are just some central parts to describe, because of those central parts is the rest of the project constructed. The majority of functions doesn't need any special explanation, because just by looking at the code it's understood what they do. Besides that, there are central philosophies and mechanisms that must be described in order for the developer to understand what is being done in the project, and it's precisely that what must be described in the section "philosophies and mechanisms".

Examples of central mechanisms very important to document is when an object should behave like a primitive type, and then it's forbidden to add new member-variables to it, because doing that increases its size. Possibly, but not always, it can be allowed to add an small variable, which increases its size a little, but to add a big variable is forbidden. Another is when an algorithm should always maintain some specific behavior or need which should never change and the idea is to maintain it.

When, for some purpose, it's needed to change a central mechanism, one possibility is to create a new class similar to the class that's needed to change, instead of changing it. Then, it's possible to have both ideas inside the code, covering the two cases that are needed.

## Class list

The **class list** should be added near the start of the documentation. If the documentation starts inside a README file, near the start of it. It just list the classes, and explains them briefly. By reading the class list, the developer can then know all the different parts the library or framework has quickly, without a lot of study.

## Layers architecture

The **layers architecture** is commonly not added inside the documentation, and that is a bad habit of developers. It should always be added. The way to add it can be an image which describes the different layers, or a list of the layers, written with text characters instead of inside an image.

## Overview

The **overview** section should be at the start of the documentation. It explains in a brief paragraph what the project does, explaining its central features.

## Example of README file with those guidelines
