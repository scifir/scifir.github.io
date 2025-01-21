---
title: "How to learn Linux"
authors: ismaelc
date: 2023-09-05
categories: [start,informatics]
description: "Learn how to learn all the topics related to Linux."
---

Welcome! In this guide you'll learn how to learn all about Linux, from the start to the more deep topics, in order that you can become an expert on Linux if you want.

## History of Linux

**Linux** is a kernel for operating systems, created by **Linus Torvalds** the 17 of september of 1991. Based on the Linux kernel, there are several Linux distributions, each having different preinstalled packages. The Linux kernel is developed by the **Linux Foundation**, founded by Linus Torvalds.

The most important Linux distribution is usually considered **Debian**, started in **1993**. The other very important is **Fedora**, started in **2003**. The most used is **Ubuntu**, which is strongly based on Debian, and has started in **2004**.

**GNU/Linux** is another name given to Linux given the fact that the software of GNU for operating systems is essential in Linux. Then, the names Linux and GNU/Linux can be used interchangeably.

**UNIX** is in a wide amount of senses the predecessor of Linux, it has been created by **Dennies Ritchie** and **Ken Thompson** in 1969 at **Bell Labs**.

The symbol of Linux is **Tux**, a penguin.

## The open source community

All the software of Linux, and, also, the distribution and the kernel, are **open source**, which means that their code is available through internet, and can be changed freely by programmers to make the software meet their needs.

The **open source community** is wide, it includes people from all nationalities and cultures. You can just browse through the web, search websites of open source software and, if you know programming, participate there. There are also IRC networks to chat and talk about informatics and open source in general.

The central websites to know currently about open source software are **github**, **gitlab** and **sourceforge**, they store the open source projects, which can be downloaded, and you can participate in if you want.

## Basic concepts of operating systems

Operating systems are always, strictly speaking, a program that controls the processes the computer executes and, also, which hardware devices can those program access, and under which rules and/or permissions (if there are on the operating system, which usually is the case).

## Common file types

Common file types used inside all operating systems, like Linux distributions, Windows and MacOS, are presented here. All should be completely known by Linux users, without exception.

Image file types are the following:

- **png:** It stores the pixel information one color after another. **PNG24** stores colors without transparency, and **PNG32** stores colors with transparency.
- **svg:** Vectorial image format. It's the better related to size.
- **jpg:** Image format that, using an algorithm, compresses the image. It also has sometimes the extension **jpeg**.
- **gif:** Simple image format that allows animations.

Video file types are the following:

- **mp4:** Video format very light.
- **mkv:** Video format with high quality.
- **avi:** Older video format, more heavy than mp4.
- **srt:** Format for subtitles that can be added to any video.

Audio file types are the following:

- **mp3:** Common audio format.
- **wav:** Common audio format.

Document file types are the following:

- **odt:** Format for documents, of OpenDocument.
- **ods:** Format for calculus sheets, of OpenDocument.
- **odp:** Format for presentations, of OpenDocument.

Windows has the following file formats that are used mainly in that operating system, more than in Linux distributions. They are the following:

- **exe:** Executable files.
- **dll:** Dynamic library files.
- **pdf:** Format for visualizing and printing documents.
- **txt:** Windows format similar to plain text files.
- **doc:** Format for document files of Microsoft Word.
- **docx:** New format for document files of Microsoft Word.
- **xls:** Format for files of Microsoft Excel.
- **xlsx:** Format for files of Microsoft Excel.
- **ppt:** Format for files of Microsoft PowerPoint.
- **pptx:** Format for files of Microsoft PowerPoint.
- **bmp:** Format for images, heavier than png.
- **iso:** Format for storing optical discs, and burning new ones with those files.
- **rar:** Format for compressing various files.
- **zip:** Format for compressing files, as rar.

## The Linux kernel and Linux distros

- **kmod:** Installs and uninstalls kernel modules.
- **kmon:** Allows to see all installed kernel modules and a description of them.
- **dmesg:** Kernel ring buffer, it contains messages of the kernel.

The Linux distributions more used are the following:

- **Debian:** Maybe the most important, it's one of the first. Its name comes from the names of the founder of the project, Ian Murdock, and his wife, Debra Lynn.
- **Ubuntu:**
- **Fedora:** Another very important Linux distribution.
- **KDE Neon:** A variant of fedora, which uses KDE Plasma Desktop by default.
- **Linux Mint:**
- **Xubuntu:**
- **Lubuntu:**
- **Arch Linux:**
- **Manjaro:**
- **OpenSUSE:**
- **Gentoo:**

## Installing Linux

### BIOS

You need to know how to use the BIOS in order to install and configure a Linux distribution, then it's explained here.

A **firmware** is a software preinstalled inside a hardware that allows to control it. The **BIOS**, acronym of **Basic Input/Output System**, is a firmware, usually of the motherboard (it can strictly be part of other hardware components for some electronic chips), that allows to control the initialization of the hardware during the **booting** process (the booting is the start of the computer) and to control runtime services. In 2023, all desktop computers have their BIOS inside the motherboard, or UEFI, is successor. **IBM** created the BIOS.

To start the BIOS you have to type F11, DEL, or another key, just after clicking on the power button. On the first screen that appears there's a message that says which key to type to access the BIOS.

Apart from the BIOS, recently it has been invented **UEFI**, acronym of **Unified Extensible Firmware Interface**. UEFI has been created by the **UEFI Forum**, a consortium, contrary to the BIOS which is proprietary software. The advantages of UEFI over BIOS is that it supports hardware with more capability, among other features.

For Linux, the Linux community has developed **coreboot**, previously called **LinuxBIOS**, a replacement for the BIOS and UEFI that is lightweight and performs the minimum number of tasks necessary to load and run an operating system of 32-bit or 64-bit. One of the variants of coreboot is **Libreboot**, which is free of proprietary blobs. A **proprietary blob**, called blob or binary blob, is a proprietary software that is only available as a binary executable.

### GNU GRUB

**GNU GRUB**, acronym of **GNU** **GR**and **U**nified **B**ootloader, is an application that allows to select the operating system to load when there's more than one operating system installed on the same computer.

GRUB can be configured to start all the operating systems installed on the computer. It detects them automatically, but they can be added manually to the configuration file. The configuration file is **/boot/grub/grub.cfg**.

The background image, among other options of GRUB, can be changed too.

### Configuring the hard-drive

### Syslinux

**Syslinux** is a software suite that allows to start a Linux distribution from every place, without necessarily installing it.

## UNIX

UNIX is the predecessor of Linux operating systems. It has been created by Dennis Ritchie, Ken Thompson, among others inside Bell Labs in **1969** and announced outside Bell Labs in **1973**. Most of the basic functionalities of UNIX have been the base for Linux distributions. UNIX has proprietary and free versions. Currently, UNIX operating systems are measured as compliant or not through the **Single UNIX Specification**.

Although currently UNIX is not used anymore in proportion to Linux distributions, it's important to know how it's in order to understand Linux deeply, because it's the base from which Linux has been developed, and most of the functionalities of UNIX are still functionalities inside Linux.

### Unix directory structure

The directory structure of Unix operating systems is the following:

- **/bin:** bin is the abbreviation of **binaries**, and contains all fundamental binaries.
- **/boot:** Contains all the files that are required for successful booting process.
- **/dev:** dev is the abbreviation of **devices**. Contains file representations of peripheral devices and pseudo-devices.
- **/etc:** Contains configuration files and system databases.
- **/home:** Contains the home directories for the users.
- **/lib:** Contains system libraries, and some critical files such as kernel modules or device drivers.
- **/media:** Default mount point for removable devices, such as USB sticks, media players, etc.
- **/mnt:** Stands for “mount”. Contains filesystem mount points. These are used, for example, if the system uses multiple hard disks or hard disk partitions. It is also often used for remote (network) filesystems, CD-ROM/DVD drives, and so on.
- **/proc:** procfs virtual filesystem showing information about processes as files.
- **/root:** The home directory for the superuser “root” – that is, the system administrator. This account’s home directory is usually on the initial filesystem, and hence not in /home (which may be a mount point for another filesystem) in case specific maintenance needs to be performed, during which other filesystems are not available. Such a case could occur, for example, if a hard disk drive suffers physical failures and cannot be properly mounted.
- **/tmp:** A place for temporary files. Many systems clear this directory upon startup; it might have tmpfs mounted atop it, in which case its contents do not survive a reboot, or it might be explicitly cleared by a startup script at boot time.
- **/usr:** Originally the directory holding user home directories,its use has changed. It now holds executables, libraries, and shared resources that are not system critical.
- **/usr/bin:** This directory stores all binary programs distributed with the operating system not residing in /bin, /sbin or (rarely) /etc.
- **/usr/include:** Stores the development headers used throughout the system. Header files are mostly used by the #include directive in C/C++ programming language.
- **/usr/lib:** Stores the required libraries and data files for programs stored within /usr or elsewhere.
- **/var:** A short for “variable.” A place for files that may change often – especially in size, for example e-mail sent to users on the system, or process-ID lock files.
- **/var/log:** Contains system log files.
- **/var/mail:** The place where all the incoming mails are stored. Users (other than root) can access their own mail only. Often, this directory is a symbolic link to /var/spool/mail.
- **/var/spool:** Spool directory. Contains print jobs, mail spools and other queued tasks.
- **/var/tmp:** A place for temporary files which should be preserved between system reboots.

### Unix 1

The first version of UNIX, released on november 3 of 1971 was including the following commands:

- **ar:** The first archiver, of file extensions **.a**, **.lib** and **.ar**.
- **as:** The first assembler. Currently GNU as has added feature that originally were not present in the version of 1971.
- **bas:** Dialect of **basic**, a common programming language during that period.
- **bcd:** Binary code to decimal conversion.
- **boot:** Reboots the system. It's placed inside /etc to avoid accidental invocation.
- **cat:** Concatenates and print a file. It can be used to concatenate files if various are specified.
- **chdir:** Previous version of cd. It changes the current directory of the shell.
- **check:** Checks file system consistency.
- **chmod:** Change mode of a file.
- **chown:** Change owner of a file.
- **cmp:** Compares two files.
- **cp:** Copy a file.
- **date:** Print the date.
- **db:** Debugs.
- **dbppt:** Dump binary to paper tape.
- **dc:** Desk calculator.
- **df:** Prints the free space in the disks.
- **dsw:** Delete interactively.
- **dtf:** DECtape format.
- **du:** Summarizes disk usage.
- **ed:** Text editor inside the command-line.
- **find:** Finds a file.
- **for:** Fortran compiler.
- **form:** Form letter generator.
- **hup:** Hang up typewritter.
- **lbppt:** Load binary paper tapes.
- **ld:** Linker. It's essential during the building of a C or C++ program.
- **ln:** Creates a link of a file.
- **ls:** Lists the contents of a directory.
- **mail:** Send mail to another user.
- **mesg:** Permits or denies messages from other users.
- **mkdir:** Makes a directory.
- **mkfs:** Makes a file system.
- **mount:** Mount a file system.
- **mv:** Move or rename a file.
- **nm:** Prints the symbol table of an output file.
- **od:** Dumps a file in octal.
- **pr:** Prints a file.
- **rew:** Rewinds DECtape drives.
- **rkd:** Dump RK disk to tape.
- **rkf:** Format RKO3 disk pack.
- **rkl:** Reload RK disk from tape.
- **rm:** Remove (unlink) files.
- **rmdir:** Remove a directory.
- **roff:** Format text.
- **sdate:** Set date and time.
- **sh:** The **Thompshon shell**, written by Ken Thompson. From version 1 it was having > and < to redirect input and output. From version 4 it was having | and ^ for pipes. In Unix 7 it has been replaced by the **Bourne shell**, and it has been used from Unix 1 to Unix 6. It's abbreviated **tsh** to distinguish it from other shells using sh as name.
- **sort:**
- **stat:** Get file status.
- **strip:** Remove symbols and relocation bits on the output of the assembler.
- **su:** Become privileged user.
- **sum:** Sums the contents of a file.
- **tap:** Manipulate DECtape.
- **tm:** Provide time information.
- **tty:** Prints the filename of the terminal in use.
- **type:** Produces output in an IBM 2741 terminal.
- **umount:** Dismount file system.
- **un:** Prints a list of undefined symbols inside an output file of assembler.
- **wc:** Counts the words in english.
- **who:** Prints which users are on the system.
- **write:** Writes to another user.

The system call of UNIX 1 are the following:

- **break:** Set program break.
- **cemt:** Catch emt traps.
- **chdir:** Change working directory.
- **chmod:** Change mode of a file.
- **chown:** Change owner of a file.
- **close:** Close a file.
- **creat:** Create a new file.
- **exec:** Execute a new file.
- **exit:** Terminate process.
- **fork:** Spawn a new process.
- **fstat:** Get status of open file.
- **getuid:** Get user identification.
- **gtty:** Get typewriter status.
- **ilgins:** Catch illegal instruction trap.
- **intr:** Set interrupt handling.
- **link:** Link to a file.
- **mkdir:** Make a directory.
- **mount:** Mount a file system.
- **open:** Open a file for reading or writing.
- **quit:** Turn off quit signal.
- **read:** Read from file.
- **rele:** Release processor.
- **seek:** Move read/write pointer.
- **setuid:** Set process ID.
- **smdate:** Set modified date on file.
- **stat:** Get file status.
- **stime:** Set time.
- **stty:** Set mode of typewriter.
- **tell:** Get file pointer.
- **time:** Get time of year.
- **umount:** Dismount file system.
- **unlink:** Remove directory entry.
- **wait:** Wait for process to die.
- **write:** Write on file.

The library routines of Unix 1 are the following:

- **atof:** ASCII to floating.
- **atoi:** ASCII to integer.
- **ctime:** Convert date and time to ASCII.
- **exp:** Exponential function.
- **fptrap:** Floating point simulator.
- **ftoa:** Floating to ASCII conversion.
- **fopen:** Open a file.
- **getc:** Returns the next byte from the file.
- **getw:** Returns the next word from the file.
- **itoa:** Integer to ASCII conversion.
- **log:** Logarithm base e.
- **mesg:** Write message on typewriter.
- **ptime:** Print date and time.
- **putc:** Writes a byte in the file.
- **putw:** Writes a word in the file.
- **fcreat:** Creates the given file.
- **flush:** Forces the contents of the buffer to be written.
- **sin:** Sine.
- **cos:** Cosine.
- **switch:** Switch on value.

The special files of Unix 1 are the following:

- **mem:** Core memory.
- **ppt:** Punched paper tape.
- **rf0:** RF11-RS11 fixed-head disk file.
- **rk0:** RK03 (or RK05) disk.
- **tap0 ... tap7:** Those are the DECtape drives 0 to 7.
- **tty:** Console typewriter.
- **tty0 ... tty5:** Communications interfaces.

The file formats of Unix 1 are the following:

- **a.out:** Assembler and link editor output.
- **archive:** It combines all files, it doesn't add any empty area.
- **binary punched paper tape format:** Binary paper tape, used to store information on paper tape.
- **format of core image:** Core image of an executing program.
- **format of directories:** Format for directories.
- **format of file system:** Every file system has a common format.
- **passwd:** Passwords file.
- **uids:** Maps user names to user IDs.
- **utmp:** User information.

The user-maintained software is the following:

- **basic:** The standard BASIC.
- **bj:** The game of black jack.
- **cal:** Print calendar.
- **chess:** The game of chess.
- **das:** Disassembler.
- **dli:** Load DEC binary paper tapes.
- **dpt:** Read DEC ASCII paper tape.
- **moo:** A game.
- **sort:** Sort a file.
- **ttt:** Tic-tac-toe game.

### Unix 2 to Unix 6

The following changes have happened with the next editions of Unix, the version 6 in total was including the following changes compared to Unix 1:

#### Commands

- **bc**: Arbitrary precision interactive language.
- **cc:** First C compiler. Added in Unix v2.
- **cdb:** C debugger.
- **comm:** Print lines common to two files.
- **cref:** Make cross reference listing.
- **dd:** Convert and copy a file.
- **diff:** Differential file comparator.
- **echo:** Echo arguments.
- **eqn:** Typeset mathematics.
- **exit:** Terminate command file.
- **fc:** Fortran compiler.
- **file:** Determinate file type.
- **goto:** Command transfer.
- **grep:** Search a file for a pattern.
- **if:** Conditional command.
- **kill:** Terminate a process.
- **login:** Sign onto Unix.
- **man:** Run manual of a program.
- **neqn:** Typeset mathematics on terminal.
- **newgrp:** Log into a new group.
- **nice:** Run a command at low priority.
- **nohup:** Run a command immune to hangups.
- **nroff:** Format text.
- **opr:** Off line print.
- **passwd:** Change login password.
- **pfe:** Print floating exception.
- **prof:** Display profile data.
- **ps:** Process status.
- **pwd:** Print working directory name.
- **rc:** Ratford compiler.
- **rev:** Reverse lines of a file.
- **shift:** Adjust shell arguments.
- **size:** Size of an object file.
- **sleep:** Suspend execution for an interval.
- **usort:** Sort files.
- **spell:** Find spelling errors.
- **split:** Split a file into pieces.
- **stty:** Set typewriter options.
- **tee:** It allows to read from standard input and write to standard outputs.
- **time:** Time a command.
- **tp:** Manipulate DECtape and magtape.
- **tr:** Transliterate.
- **troff:** Format text.
- **typo:** Find possible typos.
- **uniq:** Report repeated lines in a file.
- **wait:** Await completion of process.
- **yacc:** Parser generator.

#### System calls

- **brk:** Change core allocation.
- **sbrk:** Change core allocation.
- **csw:** Read console switches.
- **dup:** Duplicate an open file descriptor.
- **execl:** Executes a file.
- **execv:** Executes a file.
- **getgid:** Get group identifications.
- **getpid:** Get process identification.
- **indir:** Indirect system call.
- **kill:** Send signal to a process.
- **mknod:** Make a directory or a special file.
- **nice:** Set program priority.
- **pipe:** Create an interprocess channel.
- **profil:** Execution time profile.
- **ptrace:** Process trace.
- **setgid:** Set process group id.
- **signal:** Catch or ignore signals.
- **sleep:** Stop execution for interval.
- **sync:** Update super-block.
- **times:** Get process times.

#### Subroutines

- **abort:** Generate an IOT fault.
- **abs:** Absolute value.
- **fabs:** Absolute value.
- **alloc:** Core allocator.
- **free:** Core allocator.
- **atan:** Arc tangent function.
- **atan2:** Arc tangent function.
- **crypt:** Password encoding.
- **localtime:** Convert date and time to ASCII.
- **gmtime:** Convert date and time to ASCII.
- **ecvt:** Output conversion.
- **fcvt:** Output conversion.
- **end:** Last locations in program.
- **etext:** Last locations in program.
- **edata:** Last locations in program.
- **floor:** Floor function.
- **ceil:** Ceil function.
- **fmod:** Floating modulo function.
- **gamma:** Log gamma function.
- **getarg:** Get command arguments from Fortran.
- **iargc:** Get command arguments from Fortran.
- **getchar:** Read character.
- **getpw:** Get name from UID.
- **hmul:** High-order product.
- **ierror:** Catch Fortran errors.
- **ldiv:** Long division.
- **lrem:** Long division.
- **locv:** Long output conversion.
- **monitor:** Prepare execution profile.
- **nargs:** Argument count.
- **perror:** System error messages.
- **nlist:** Get entries from name list.
- **syserrlist:** System error messages.
- **sysnerr:** System error messages.
- **errno:** System error messages.
- **pow:** Floating exponentiation.
- **printf:** Formatted print.
- **fflush:** Buffered output.
- **putchar:** Write character.
- **qsort:** Quicker sort.
- **rand:** Random number generator.
- **srand:** Random number generator.
- **reset:** Execute non-local goto.
- **setexit:** Execute non-local goto.
- **setfil:** Specify Fortran file name.
- **sqrt:** Square root function.
- **ttyn:** Return name of current typewriter.

#### Special files

- **cat:** phototypesetter interface.
- **dc:** DC-11 communications interface.
- **dh:** DH-11 communications multiplexer.
- **dn:** DN-11 ACU interface.
- **dp:** DP-11 201 data-phone interface.
- **hp:** RH-11/RP04 moving-head disk.
- **hs:** RH11/RS03-RS04 fixed-head disk file.
- **ht:** RH-11/TU-16 magtape interface.
- **kl:** KL-11 or DL-11 asynchronous interface.
- **lp:** line printer.
- **kmem:** core memory.
- **pc:** PC-11 paper tape reader/punch.
- **rf:** RF11/RS11 fixed-head disk file.
- **rk:** RK-11/RK03 (or RK05) disk.
- **rp:** RP-11/RP03 moving head disk.
- **tc:** TC-11/TU56 DECtape.
- **tm:** TM-11/TU-10 magtape interface.
- **tty:** general typewriter interface.

#### File formats and conventions

- **ar:** New name for archive files.
- **ascii:** Map of ASCII character set.
- **dump:** Incremental dump tape format.
- **greek:** Graphics for extended TTY-37 type-box.
- **group:** Group file.
- **mtab:** Mounted file system table.
- **tabs:** Set tab stops.
- **tp:** DEC/mag tape formats.
- **ttys:** Typewriter initialization data.
- **wtmp:** User login history.

#### User maintained programs

- **azel:** Satellite predictions.
- **col:** Filter reverse line feeds.
- **cubic:** Three dimensional tic-tac-toe.
- **factor:** Discover prime factors of a number.
- **fed:** Edit form letter memory.
- **form:** Form letter generator.
- **graph:** Draw a graph.
- **gsi:** Interpret extended character set on GSI terminal.
- **m6:** General purpose macroprocessor.
- **plot: tek, gsip, vt0** Graphics filters.
- **primes:** Print all primes larger than somewhat.
- **quiz:** Test your knowledge.
- **sky:** Obtain ephemerides.
- **sno:** Snobol interpreter.
- **speak:** Word to voice translator.
- **spline:** Interpolate smooth curve.
- **tbl:** Format tables for nroff or troff.
- **tmg:** Compiler-compiler.
- **units:** Conversion program.
- **wump:** The game of hunt-the-wumpus.

#### User maintained subroutines

- **crfork, crexit, crread, crwrite, crexch, crprior:** Coroutine scheme.
- **ms:** Macros for formatting manuscripts.
- **plot: openpl et al.** Graphics interface.
- **salloc:** String allocation and manipulation.

#### System maintenance

- **ac:** Login accounting.
- **boot procedures:** UNIX startup.
- **chgrp:** Change group.
- **clri:** Clear i-node.
- **crash:** What to do when the system crashes.
- **cron:** Clock daemon.
- **dcheck:** File system directory consistency check.
- **dpd:** Data phone daemon.
- **dump:** Incremental file system dump.
- **getty:** Set typewriter mode.
- **glob:** Generate command arguments.
- **icheck:** File system storage consistency check.
- **init:** Process control initialization.
- **lpd:** Line printer daemon.
- **mknod:** Build special file.
- **ncheck:** Generate names from i-numbers.
- **restor:** Incremental file system restore.
- **sa:** Shell accounting.
- **sync:** Update the super block.
- **update:** Periodically update the super block.
- **wall:** Write to all users.

### UNIX 7

#### Basic software

- **stty:** Set up options for optimal control of a terminal.
- **lpr:** Spools arbitrary files to the line printer.
- **dd:** Physical file format translator.
- **cd:** Change working directory.
- **test:** Tests for use in Shell conditionals.
- **expr:** String computations for calculating command arguments.
- **read:** Read a line from terminal, for interactive Shell procedure.
- **cron:** Schedule regular actions at specified times.
- **at:** Schedule a one-shot action for an arbitrary time.
- **quot:** Print summary of file space usage by user id.
- **iostat:** Print statistics about system I/O activity.
- **tar:** Manage file archives on magnetic tape or DECtape.
- **dump:** Dump the file system stored on a specified device, selectively by date, or indiscriminately.
- **restor:** Restore a dumped file system, or selectively retrieve parts thereof.
- **dcheck, lcheck, ncheck:** Check consistency of file system.
- **clri:** Peremptorily expunge a file and its space from a file system. Used to repair damaged file systems.
- **sync:** For all outstanding I/O on the system to completion. Used to shut down gracefully.
- **ac:** Publish cumulative connect time report.
- **sa:** Publish Shell accounting report. Gives usage information on each command executed.
- **calendar:** Automatic reminder service for events of today and tomorrow.
- **cu:** Call up another time-sharing system.
- **uucp:** Unix to Unix copy.
- **library:** The basic run-time library.
- **adb:** Interactive debugger.
- **od:** Dump any file.
- **lorder:** Places object file names in proper order for loading, so that files depending on others come after them.
- **make:** Controls creation of large programs.
- **learn:** A program for interpreting CAI scripts, plus scripts for learning about Unix by using it.
- **lint:** Verifier for C programs.
- **cb:** A beautifier for C programs.
- **f77:** A full compiler for ANSI Standard Fortran 77.
- **ratfor:** Ratfor adds rational control structure a la C to Fortran.
- **struct:** Converts ordinary ugly Fortran into structured Fortran.
- **m4:** A general purpose macroprocessor.
- **lex:** Generator of lexical analyzers.

#### Text processing

- **ptx:** Make a permuted (key word in context) index.
- **look:** Search for words in a dictionary that begin with specified prefix.
- **crypt:** Encrypt and decrypt files for security.
- **tbl:** A preprocessor for nroff/troff that translates simple descriptions of table layouts and contents into detailed typesetting instructions.
- **refer:** Fills in bibliographic citations in a document from a data base.
- **tc:** Simulates graphic systems typesetter on Tektronix 4014 scope.
- **greek:** Fancy printing on Diable-mechanism terminals like DASI-300 and DASI-450, and on Tektronix 4014.
- **col:** Canonicalize files with reverse line feeds for one-pass printing.
- **deroff:** Remove all troff commands from input.
- **checkeq:** Check document for possible errors in eqn usage.

#### Information handling

- **tsort:** Topological sort - converts a partial order into a total order.
- **join:** Combine two files by joining records that have identical keys.
- **look:** Binary search in sorted file for lines with specified prefix.
- **sed:** Stream-oriented version of ED. Can perform a sequence of editing operations on each line of an input stream of unbounded length.
- **awk:** Pattern scanning and processing language. Searches input for patterns, and performs actions on each line of input that satisfies the pattern.

#### Graphics

- **graph:** Prepares a graph of a set of input nunmbers.
- **spline:** Provides a smooth curve through a set of points intended for graph.
- **plot:** A set of filters for printing graphs produced by graph and other programs on various terminals.

#### Novelties, games and things that didn't fit anywhere else

- **backgammon:** A player of modest accomplishment.
- **checkers:** Ditto, for checkers.
- **bcd:** Converts ascii to card-image form.
- **ppt:** Converts ascii to paper tape form.
- **cubic:** An accomplished player of 4x4x4 tic-tac-toe.
- **maze:** Constructs random mazes for you to solve.
- **banner:** Print output in huge letters.
- **ching:** The I Ching. Place your own interpretation on the output.
- **fortune:** Presents a random fortune cookie on each invocation.
- **units:** Converts amounts between different scales of measurement.
- **arithmetic:** Speed and accuracy test for number facts.
- **factor:** Factor large integers.
- **quiz:** Test your knowledge of Shakespeare, Presidents, capitals, etc.
- **wump:** Hunt the wumpus, thrilling search in a dangerous cave.
- **reversi:** A two person board game, isomorphic to Othello.
- **hangman:** Word-guessing game. Uses the dictionary supplied with spell.
- **fish:** Children's card-guessing game.

### UNIX 8 to UNIX 10

- **basename:** Gives the basename of a filename with all his path.
- **dirname:** Gives the path of a filename with all his path.
- **printf:** Print arguments.
- **printenv:** Print environment.
- **rc:** Command language.
- **wait:** Wait for process to change state.
- **whatis:** Outputs descriptions of one-line.
- **tr:** Translate or delete characters.
- **true:** Gives the value true.
- **false:** Gives the value false.
- **idiff:** Interactive file comparison.
- **where:** Machine name.
- **touch:** Set modification or access date of a file.
- **chdate:** Set modification or access date of a file.
- **worm::** Format of worm disks.
- **awk:** Pattern scanning and processing language.
- **cbt:** btree utilities.
- **col:** Column alignment.
- **mc:** Column alignment.
- **fold:** Column alignment.
- **expand:** Column alignment.
- **reccp:** 
- **encrypt:** Encode.
- **decrypt:** Decode.
- **cut:** Rearrange columns of data.
- **paste:** Rearrange columns of data.
- **dblbuf:** Convert and copy a file.
- **diff3:** Differential file comparison.
- **idiff:** Interactive file comparison.
- **join:** Relational database operator.
- **lc:** List contents of directory.
- **pack,unpack,pcat,compress,uncompress,zcat:** Compress and expand files.
- **random:** Sample lines from a file.
- **revpag:** Reverse pages.
- **fsplit:** Split a file into pieces.
- **strings:** Find printable strings in a file.
- **treesum:** Sum and count blocks in a file.
- **tail,readslow:** Deliver the last part of a file.
- **vis:** Show invisible characters.
- **xd:** Hex dump.
- **id:** Get user identity.
- **ex:** Text editor.
- **edit:** Text editor.
- **vi:** Text editor.
- **graphdraw:** Edit (combinatoric) graphs.
- **graphpic:** Convert to pic files.
- **icon:** Icon editor.
- **jf:** Font editor.
- **ped,tped:** Picture editor.
- **pico:** Graphics editor.
- **rebecca:** Graphics touch-up editor.
- **sam:** Screen editor with structural regular expresions.
- **lcc:** C compilers.
- **cin:** C interpreter.
- **cpp:** C language preprocessor.
- **cyntax:** C program verifier.
- **cem:** C program verifier.
- **mk:** Maintain (make) related files.
- **mkconv:** Maintain (make) related files.
- **membername:** Maintain (make) related files.
- **altran:** Programming language for the formal manipulation of rational functions of several variables.
- **cospan:** 
- **esterel:** Synchronous programming language for the development of complex reactive systems.
- **icon:** Very high-level programming language in which code returns "true" or "false".
- **lisp:** Programming language with a parenthesized prefix notation.
- **macsyma:** Programming language of algebra.
- **maple:** Programming language that allows to do mathematic calculations.
- **ops5:** Language for production system.
- **pascal:** Programming language.
- **ratfor:** Compiler to Fortran 77.
- **S:** **Important** statistical programming language. **R** is an implementation of S.
- **smp:** Computer algebra system.
- **sno:** Language.
- **spitbol:** Compiled implementation of the SNOBOL4 programming language.
- **struct:** Language.
- **twig:** Language.
- **f2c:** Convert Fortran 77 to C.
- **sml:** Standard ML compiler.
- **snocone:** Snogol with syntactic sugar.
- **eyacc:** Tool for yacc.
- **32ld:** Bootstrap loader for 5620.
- **ranlib:** Library maintainer.
- **libc:** Standard library functions.
- **stab:** Symbol table types.
- **bigcore:** Permit big core images.
- **coreid:** Identify source of image.
- **core:** Format of memory image file.
- **hang:** Start a process in stopped state.
- **lcomp:** Line-by-line profiler.
- **lprint:** Line-by-line profiler.
- **pi:** Process inspector.
- **3pi:** Process inspector.
- **time:** Time a command.
- **cip:** Draw pictures for typesetting.
- **dag:** Preprocessor for drawing directed graphs.
- **doctype:** Guess command line for formatting a document.
- **eqnchar:** Special character definitions for eqn.
- **font:** Typesetter fonts.
- **grap:** Pic preprocessor for drawing graphs.
- **ideal:** Troff preprocessor for drawing pictures.
- **mbits:** Macros to typeset bitmaps.
- **mcs:** Macros for formatting cover sheets.
- **movie:** Algorithm animation.
- **stills:** Algorithm animation.
- **mpictures:** Picture inclusion macros.
- **mpm:** Macros for page makeup.
- **ms:** Macros for formatting manuscripts.
- **ped,tped:** Picture editor.
- **pic,tpic:** Troff and tex preprocessors for drawing pictures.
- **prefer,pinvert,penter,plook,pconvert:** Mantain and use bibliographic references.
- **refer,lookbib,pubindex:** Mantain and use bibliographic references.
- **tbl:** Format tables for nroff or troff.
- **troff,nroff:** Text formatting and typesetting.
- **fmt:** Ultra-simple text formatter.
- **latex,bibtex:** Tex macro package and bibliographies.
- **monk,monksample:** Typeset documents and letters.
- **tex,initex,virtex,dvips,dvit:** Text formatting and typesetting.
- **deroff,demonk,detex,delatex:** Remove formatting requests.
- **docgen:** Generate a document from a script.
- **wwb,style,diction,punct:** Writer's workbench.
- **apsend:** Send troff output to phototypesetter.
- **docsubmit:** Send document to library.
- **proof:** Troff output interpreter for 5620.
- **psi:** Postscript interpreter.
- **reader:** Electronic retrieval of typeset documents.
- **sendcover:** Send cover sheet to the library.
- **bc:** Arbitrary-precision arithmetic language.
- **qfactor:** Factor a number.
- **hoc:** Interactive floating point language.
- **matlab:** Interactive matrix desk calculator.
- **seq:** Print sequences of numbers.

## systemd

**systemd** is the program that loads all services of a Linux operating system when it starts. It also allows to configure devices, login, network connections and event logging. It's the replacement of **SysV init**, the booter of UNIX. It's similar to sysv init in many aspects, but it has evolved to include more functionalities and to allow more control of the operating system.

The package systemd of Debian includes the following important programs:

- **systemctl:** The most important application. It controls the service that are executed, allows to stop them, and to configure which are executed at boot.
- **journalctl:** It keeps a log of the events of the operating system.
- **loginctl:** It keeps a log of the logins.
- **networkctl:** It allows to control the network connections.

## Base packages of Linux distributions

The base packages of Linux distributions mandatory to know are the commmands of **UNIX**, **GNU binutils** and **GNU coreutils**.

## Users, groups and permissions

Users are stored in the file **/etc/passwd**. The following commands are used to work with users:

- **whoami:** Prints the current user.
- **users:** Prints the current user specified by a file.
- **adduser:** Creates a new user, with the home directory.
- **useradd:** Creates a new user, without the home directory unless -m is used.
- **deluser:** Deletes a user.
- **userdel:** Deletes a user. With -r it deletes the home directory too.
- **passwd:** Allows to change the password.
- **usermod:** Allows to modify a user.

The following commands are used to work with groups:

- **groups:** Lists the groups of the current user, or the specified user.
- **addgroup:** Creates a new group.
- **groupadd:** Creates a new group.
- **groupdel:** Deletes a group.
- **delgroup:** Deletes a group.
- **groupmod:** Allows to modify a group.
- **id:** Shows users and groups of the specified user, with their respective uid and gid.
- **getent:** Lists information about an entity of the administrative database.
- **getent group \<group\>**: List the users of a group.

Groups are stored in the file **/etc/group**, you can see all groups of the OS there.

The id of a user in Linux is abbreviated as **UID**, the id of a group is abbreviated as **GID**.

- **chmod:** Change the permissions of a file.
- **chown:** Change the owner and/or group of a file.
- **chgrp:** Change the group of a file.

## Processes and threads

## Desktop environments

It's called **desktop environment** the graphical display that allows the user to use an operating system, it's what appears on screen when the operating system is not executing a terminal. When there's no desktop environment but it's possible to type commands, the computer is then executing a terminal, from which, inside a Linux distribution, it's possible to execute a desktop environment.

Inside Linux there're different desktop environments, the most important ones are the following:

- **GNOME:** The most used desktop environment, it comes preinstalled by default inside Debian and Ubuntu.
- **KDE Plasma Desktop:** A very good desktop environment from KDE.
- **XFCE:** Lightweight desktop environment useful for computers with low computing power.
- **LXDE:** Desktop environment lightweight and fast, but with less features than GNOME and KDE Plasma Desktop.
- **LXQT:** Variant of LXDE with the Qt library (a GUI library, described later in this guide).
- **Cinnamon:** A desktop environment derived from GNOME 3 but being more conventional.

You can search images on Google of each desktop environment, and select the one you prefer.

There are more desktop environments, because inside Linux there are a wide amount of FOSS developers who develop new software available for everyone. Just search inside Google and install the desktop environment you prefer.

As part of the desktop environment there exist the display manager. The display manager handles the display of the monitor. There are different ones to choose:

- **lightdm:** The fastest display manager. Recommended.
- **gdm:** The display manager of GNOME. It comes with GNOME.
- **KDM:** Display manager of KDE.
- **LXDM:** Lightweight display manager for LXDE.
- Many others... (search over the web).

A display manager can be configured with one or another greeter. A greeter is the interface that prompts the user for credentials. For example, lightdm has a wide amount of greeters, one of them is **lightdm-gtk-greeter**.

## Linux directory structure

The main directories of Linux distributions are the following:

- **/bin:** binary or executable programs.
- **/etc:** system configuration files.
- **/home:** home directory. It is the default current directory.
- **/opt:** optional or third-party software.
- **/tmp:** temporary space, typically cleared on reboot.
- **/usr:** User related programs.
- **/var:** log files.

Other directories of Linux are the following:

- **/boot:** It contains all the boot-related information files and folders such as conf, grub, etc.
- **/dev:** It is the location of the device files such as dev/sda1, dev/sda2, etc.
- **/lib:** It contains kernel modules and a shared library.
- **/lost+found:** It is used to find recovered bits of corrupted files.
- **/media:** It contains subdirectories where removal media devices are inserted.
- **/mnt:** It contains temporary mount directories for mounting the file system.
- **/proc:** It is a virtual and pseudo-file system to contains info about the running processes with a specific process ID or PID.
- **/run:** It stores volatile runtime data.
- **/sbin:** binary executable programs for an administrator.
- **/srv:** It contains server-specific and server-related files.
- **/sys:** It is a virtual file system for modern Linux distributions to store and allows modification of the devices connected to the system.

## The Linux command-line

- **tsh:** The Thompson shell, the first command-line, created for Unix 1 by **Ken Thompson**.
- **bourne shell:** Successor of the Thompson shell.
- **bash:** Default terminal on Linux.
- **ksh:**
- **dash:** Terminal more lightweight than bash, POSIX-compliant.
- **zsh:**
- **mc:** Command-line with interface.
- **which:** Gives the location of a command.

### Environment variables

An environment variable is a variable that allows to configure some value of the operating system that can be read by all the processes that the operating system executes and that have the permission of the operating system to access that environment variable.

- **env:** List all environment variables.
- **export:** Sets and environment variable for the session.

### Using the filesystem

To use a command in Linux, just type it in the command line. All commands have arguments, and you have to write them after the name of the command. To use the filesystem inside a terminal of Linux the following commands are mandatory to know:

- **pwd:** Prints the location of the current directory.
- **cd:** Change directory.
- **mkdir:** Create a directory.
- **ls:** List directory contents.
- **cp:** Copy a file or directory.
- **mv:** Rename a file or move a directory.
- **rm:** Remove a file or directory.
- **cat:** List the content of a file.
- **touch:** Creates an empty file, or updates its date.
- **stat:** Displays information about a file.
- **file:** Displays the type of file.
- **find:** It search files with different options.
- **lsfd:** List file descriptors.
- **lsattr:** List attributes of the files in the current directory.
- **chattr:** Changes the attributes of a file.

### BASH

**BASH**, acronym of **B**ourne **A**gainst **SH**ell, is the default terminal in Linux. It allows to create chains of commands, where one command gives its output as input to the next command. To do that, the character **'|'** must be used. That's what's called a **pipe**.

Another important feature of bash is the use of **>** and **<** within commands. Those characters are used to add the output of a command to a file in order to create a new file with all the output. Also, it can be used to give the text of a file as input for a command.

### man and info

**man** is an application created by Dennis Ritchie to document software. It's executed from the command-line by typing **'man \<program\>'**. The data files from which the documentation is read is stored in the folder **/usr/share/man**.

The different sections of man pages are **NAME**, **SYNOPSIS**, **DESCRIPTION**, **OPTIONS**, **FILES**, **ENVIRONMENT**, **DIAGNOSTICS**, **BUGS**, **AUTHOR**, **SEE ALSO**.

**Texinfo** is a software of GNU created by Richard Stallman and Robert Chassell that allows to generate documentation files on different formats like **HTML**, **DVI**, **PDF**, **Docbook**, **XML** and **Info**. **info** is an application that's similar to man and that can read info files generated by texinfo. It's used by GNU, and it's, as man, widely used inside Linux distributions. As man, it's used by typing **'info \<program\>'**. The data files of the documentation of programs is stored in the folder **/usr/share/info**.

### Important tools

Very important command-line utilities for Linux are the following:

- **less:** It allows to display text inside the command-line one page at a time. It's used with the name of the file or by piping the stream of text, example: apt search wx | less.
- **head:** Displays the start of a file.
- **tail:** Displays the end of a file.
- **nano:** Command line text editor.
- **vim:** Command line text editor.
- **vi:** Command line text editor, previous version of **vim**.
- **grep:** Search for patterns in files. It has variants egrep and fgrep.
- **sed:** Stream editor, it can edit the stream output and send a modified output of the output it receives.

## Knowing the hardware

The following tools give information about the hardware:

- **arch:** Architecture of the processor. **Very important** to know.
- **uname:** Displays information about the system.
- **hostname:** Name of the computer when acting as a **host**.
- **poweroff:** Shutdown the computer.
- **lsusb:** List usb connections.
- **lspci:** List connected pci devices.
- **lscpu:** Prints information about the cpu.

## Linux packages

A **Linux package** is a file containing all the files of a software or software suite, which includes binaries, libraries, configuration files, documentation files, documentation files of the authors, among any other required file.

The two widely used Linux packages are **deb files** and **rpm files**.

## Installing software

To install software in Debian, Ubuntu, and other Linux distributions, **apt** is used. Apt is an acronym of **Advanced package tool**. Apt is configured in the file **/etc/apt/apt.conf**. Inside fedora, among other distributions, instead of apt it's used **yum**. The application that installs packages varies with the Linux distribution, and so it's needed to read the documentation of the distribution in use to know how the packages are installed in it.

- **apt:** It installs and uninstalls deb packages in Debian, Ubuntu, among a wide amount of distributions.
- **apt-get:** Similar to apt, it installs and uninstalls packages.
- **apt-file:** Displays information about the specified package.
- **apt-cache:** It displays information about installed packages.
- **apt-config:** Displays information about the configuration of apt.
- **yum:** It installs and uninstalls rpm packages in Fedora, among other rpm-based distributions.
- **aptitude:** Program that lists, by categories, all packages installed and available to install.

The sources from which apt downloads the packages are specified in the file **/etc/apt/sources.list**. The packages for Debian distributions are downloaded mainly from [http://ftp.us.debian.org/debian](http://ftp.us.debian.org/debian).

Debian packages have the following applications available:

- **dpkg:** Installs and configures debian packages.
- **dpkg-query:** A tool that access the dpkg database. It can list all packages installed.

## Linux distributions

- **busybox:** It includes a lot of UNIX utilities, it comes preinstalled with some distributions.

## Linux organizations

- **Linux foundation:** The central Linux organization, it develops the Linux kernel.
- **GNOME:** It develops GNOME, which includes GTK+.
- **KDE:** It develops all KDE software, which includes KDE Plasma Desktop, and a wide amount of open source software.
- **freedesktop:** It develops desktop systems, like Wayland and the X library.

Apart from those organizations, and any open source software that you can find in, for example, GitHub, there exist the following important open source organizations, not related specifically to Linux, but mandatory to know:

- **GNU:** Founded by Richard Stallman, it develops the compilers, the GNU coreutils, among a wide amount of important software.
- **Apache Software Foundation:** It develops all the central technologies used by organizations, enterprises and non-profit, that allow to have an informatics system.

## Logs

## Core Linux libraries

The central libraries to develop software in Linux are, currently in 2023:

- **FreeType:** A library that creates glyph images of fonts.
- **HarfBuzz:** Another library of glyphs, competence of FreeType.
- **Pango:** A library that creates paragraphs and enriched text.
- **Cairo:** A library that allows to draw images.
- **D-Bus:** A library for inter-process communication between different programs.
- **Wayland:** A protocol and a library that communicates applications with a display server and get input from the user. It replaces X11.
- **xlib:** X window system that allows applications to interact with an X server. It has been replaced with Wayland.
- **Mesa3D:** Implementation of OpenGL, Direct3D, Vulkan, OpenCL, among other graphics specifications for Linux. It's used by 3D applications, like videogames.
- **GDK:** Basal library for creating the GUI library GTK+.
- **libconf:** It allows to parse .conf files.
- **libconfigurize:** It allows to parse cfg files. It competes with libconf.

The **Linux Standard Base** (**LSB**) has been created to have some compatibility between different Linux distributions.

## GUI libraries

The central libraries to create the GUI of desktop programs in Linux are:

- **GTK+:** The library created by **GNOME** to create the GUI, cross-platform (supports Linux, Windows and macOS). It uses **GDK** as its base.
- **wxWidgets:** Another library of GUI, cross-platform (supports Linux, Windows and macOS).
- **Qt:** Another library to create the GUI. It's used widely by **KDE**.

To create a GUI library

## Important Linux applications

### Archives

Archives are files containing more than one file inside.

- **ar:**
- **tar:**
- **zip:**
- **rar:**

## Programming tools

### Code editors

- **kdevelop:** **Very good** code editor of KDE.
- **codeblocks:** **Very good** code editor for C, C++, among other programming languages.
- **eclipse:** Important code editor.
- **intellij:** Java code editor of **Jetbrains**.
- **jed:** Editor for the command-line.

## Linux API and ABI

## Linux kernel modules

## Linux system calls
