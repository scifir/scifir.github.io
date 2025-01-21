---
title: "Complete guide of C++"
authors: ismaelc
date: 2023-09-05
categories: [start,informatics]
description: "Learn all the different important technologies related to C++."
---

## History of C++

C++ has been created by **Bjarne Stroustrup** in **1981**. It's based on C, and for that reason his first name was **"C with classes"**. A class was then, and continues being, a data structure with functions that allow to customize how that data behaves. The first compiler is **cfront**, the currently being most used are **g++** and **clang++**.

C++ has evolved over time and, then, has different versions available. The versions of C++ are **C++98**, **C++03**, **C++11**, **C++14**, **C++17** and **C++20**.

Currently, C++ has an ISO, called **International Standard ISO/IEC 14882:2020(E) – Programming Language C++**, which is essentially the sintaxis of the programming language, not the compilers.

## Bibliography

The most important book of C++ is **"The C++ programming language"**, from Bjarne Stroustrup.

## Websites

- **isocpp.org:** The official website of the standard of C++.

## Compiling system

- **cpp:** The C preprocessor. It processes the **header .h files**.
- **g++:** The compiler of C++. It creates the **object .o files** from the **.cpp files**.
- **ld:** The linker of C++, it creates the **executable file** based on the **.o files**.
- **make:** The build tool that executes cpp, g++ and ld.
- **cmake:** The most used build tool at the present. It uses a **CMakeLists.txt file**.
- **autoconf:** Part of the previous build tool, the autotools. It uses a **configure.ac file**.
- **automake:** Part of the previous build tool, the autotools. It uses a **makefile.am file**.
- **libtool:** Part of the previous build tool, the autotools. It links libraries statically and dynamically.

## GNU binutils

The **GNU binutils** are tools used to analize the files compiled and created with the build system. They allow to detect errors in the compiled files, and also they allow to study in detail **assembler**, the final programmin language in whih all C++ files are converted to by the compiling process.

- **objdump:** It allows to see the instructions of an object file.
- **readelf:** It allows to read an elf file.

## C++ IDEs

- **KDevelop:** Better C++ IDE, it includes even a C++ linter.
- **CodeBlocks:** Light C++ IDE with all the usually important features.

## Installing C++ tools

### Linux

Install the packages, through **apt** or the package manager of your Linux distribution if it's another. The packages you must install are the ones containing **gcc**, **clang**, **make**, **cmake**, **autotools**. Additoinally, you should add **gtk**, **wxwidgets** and **qt**.

### Windows

Inside Windows use **MinGW** to install C++. There you can install the packages you need, like **gcc**, **clang**, **make**, **cmake**, **autotools**, **gtk**, **wxwidgets** and **qt**.

## Build tools

### make

- **make:** It compiles all the project. It's better to use **-j** to specify the number of jobs to use.
- **make -j n:** It compiles in the specified number of different jobs all the project.
- **make docs:** It creates the documentation of the project, if there's documentation.
- **make install:** It copies the builded files inside the install folder.

### cmake

- **cmake -G system:** It compiles the project generated for the specified system.
- **cmake -Dvariable:** It defines a variable for the build, which allows to change configurations if the variable is specified inside the build for the project.

To build using cmake type the following commands, in order:

```cpp
cmake .
make
make install
```

When using cmake, you also have available **ctest** and **cpack**, explained bellow.

### autotools

- **./configure:** Command that executes the autotools.
- **./configure --help:** It displays all the configuration options available for the build.

To build using autotools type the following commands, in order:

```cpp
./configure
make
make install
```

### ninja

The ninja build system uses a file called **build.ninja**. To build under ninja, just run **ninja**.

### qmake

The qmake build system uses a file with **.pro** extension. To build under qmake use the following command, the example is for a file called hello.pro:

```cpp
qmake -o Makefile hello.pro
```

An example of a qmake file is the following:

```cpp
CONFIG += debug
HEADERS += hello.h
SOURCES += hello.cpp
SOURCES += main.cpp
win32 {
    SOURCES += hellowin.cpp
}
unix {
    SOURCES += hellounix.cpp
}
```

### Eclipse internal builder

The IDE **Eclipse** has an internal builder for C++, which is possible to use in replacement of the other builders. That builder is configured in a window of the program for each project.

## Sintaxis

### Types

- **bool:** boolean. Sizes 1 byte.
- **char:** character. Sizes 1 byte.
- **short:** integer. Sizes 2 bytes.
- **int:** integer. Sizes 4 bytes.
- **long:** integer.
- **long long:** integer.
- **unsigned int:** unsigned integer. Sizes 4 bytes.
- **unsigned long:** unsigned integer.
- **unsigned long long:** unsigned integer.
- **float:** floating-point. Sizes 4 bytes.
- **double:** floating-point. Sizes 8 bytes.
- **long double:** floating-point. Sizes 16 bytes.

### Literals

- **bool:** true or false.
- **char:** character between ''.
- **string:** sequence of characters between "".
- **wstring:** sequence of characters between L"".
- **u32string:** sequence of characters between U"".
- **int:** 1.
- **double:** 1.0 or 1.0d.
- **float:** 1.0f.
- **array:** Use of {} with any sequence of valid literals.

## Testing

- **ctest:** Tool of cmake that allows to execute all tests registered inside CMakeLists.txt.
- **gcov:** Tool of GNU that allows to check the amount of coverage that the tests of a project are covering, and then the amount of lines of codes that aren't yet covered.

## Packaging

- **cpack:** Tool of cmake that allows to package the project inside **.deb files**, among other file formats for software packages. The package is specified inside CMakeLists.txt.

Apart from packages there exist, for Windows, the installers.

## Standard library

The most important headers of the standard library of C++ are the following:

- **string:** It contains the string class, wstring and u32string. Inside C++, an string contains **UTF8** characters, a wstring contains **UTF16** characters and a u32string contains **UTF32** characters.
- **iostream:** It contains cin and cout to allow to interact with the user through a command-line interface.
- **vector:** It contains the vector class, the stl container more used.
- **map:** It contains the map class, the equivalent inside C++ of associative arrays.

## Important libraries

Important libraries of C++ are the following:

- **ICU:** It means International Characters for Unicode, it allows to manager strings that can display any Unicode character.
- **boost:** Very big library that includes a big amount of libraries inside, covering similar use cases than the standard library.

For testing there exist the following libraries:

- **CATCH:** It allows unit testing and benchmarking. Very simple to use.

To use XML files inside C++ programs there are the following libraries:

- **rapidxml:** Library that parses XML very fast.
- **libxml2:** GNU library to parse XML.
- **tinyxml:** Simple library to parse XML.

To create GUI desktop programs the libraries are the following:

- **GTK:** Library of GNOME to create GUI interfaces.
- **wxWidgets::** Library to create GUI interfaces cross-platform.
- **Qt:** Library to create GUI interfaces cross-platform.

To work with fonts the following libraries are used:

- **freetype:** Library that allows to create glyphs from font files.
- **pango:** Library to create paragraphs, using freetype inside it, and to create enriched text.

To work with images the following libraries are important:

- **cairo:** Library that allows to draw new images, and to create then images with lines of code.
- **librsvg:** Library that allows to handle SVG images.
- **libpng:** Library that allows to handle PNG images.
- **libjpeg:** Library that allows to handle JPEG images.
- **libgif:** Library that allows to handle GIF images.

To work with 3D the following libraries are important:

- **mesa3d:** Implementation of OpenGL inside Linux. OpenGL has been created by **Khronos**.
- **direct3d:** 3D for Windows created by **Microsoft**.
- **glew:** Library to load extensions of OpenGL.
- **glfw:** Library to run OpenGL easy.

To work inside Linux the following libraries are used:

- **dbus:** To communicate between different programs.

The compression libraries to know about are the following:

- **zlib:** Most common compression library.
- **zstd:** Currently, the faster compression library.
- **zip:** The compression library of **winzip**.
- **tar:** The library that archives files, withuot necessarily compression.

The libraries through which compilers are made are the following:

- **gmp:**
- **mpfr:**
- **mpc:**
