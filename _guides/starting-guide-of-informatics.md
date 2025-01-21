---
title: "Starting guide of informatics"
authors: ismaelc
date: 2024-02-21
categories: [start,informatics]
description: "Learn all the basics of informatics, both software and hardware."
---

## Computing and informatics

**Computing** means the area of knowledge about devices that do computations, that's, math calculations and logical calculations. **Informatics** means the area of knowledge about information. Both words are used as synonym but are, then, different. Computers do both things at the same time, which are different tasks and have different purposes and utilities.

## Open source software

**Open source** is a concept created by **Richard Stallman** that means software whose code is freely available for everyone. Open source software is always free to download and use. When you have various options of software to use, if you don't want to spend money buying private software, you can always look for open source alternatives, which are free. Also, it's common that open source software is better than commercial software in lots of software categories, so they tend to be the better choices available.

## History of informatics

The first computer, which is the first **turing machine**, has been created by **Alan Turing**. The first important operating system, **UNIX**, has been created by **Dennis Ritchie** and **Ken Thompson**. The first important programming language, **C**, has been created also by Dennis Ritchie. Previous to C, the programming languages were **COBOL**, **Lisp**, **Fortran**, among others.

The second computers, after the UNIX systems, have been created by **Apple** and **Microsoft** in similar years.

## Units of information

A **bit** is a unit of information that can be one of only two different values, a 1 and a 0. A **byte** is composed of 8 bits. Each byte can store 256 different values, and only one of those values at the same time. Bytes operate in **binary**, because each bit can only be a 1 or a 0, and it can't be any other value. Although it's possible to create computers that work with units of information different than bytes, that's, units of information with more or less than 8 bits, that is not in use nowadays, and all computers operate in bytes of 8 bits.

The prefixes for bytes are in the order of 1024 instead of in the order of 1000, in difference with meters, forces, and a lot of other **SI units**. The SI units are the **International System of Units** and include all the standardized units, as meter, forces, pressures, volumes, etc.

A **kilobyte**, abbreviated **KB**, has a total of 1024 bytes. A **megabyte (MB)** a total of 1024 KB. A **gigabyte (GB)** a total of 1024 MB. A **terabyte (TB)** a total of 1024 GB.

## Files and directories

Both **files** and **directories** are stored inside hard disks. They are stored inside a hard disk through a system named **filesystem**. A file is an entity of a filesystem that containts information that can be read, saved, updated and removed. The information can be read directly, as is the case of a **plain file**, or it can be **archived** with some software, as tar files. There're also **binary files**, which contains instructions to be executed directly by a processor.

The most popular filesystems today are **NTFS** and **ext4**. NTFS is the filesystem used by Windows and ext4 is the generic filesystem created for open operating systems, like Linux distributions.

## Codification of characters

To **codify** means to assign a code to something. This code is used, in informatics and in other disciplines, as replacement of the information the code is of, it's like a synonym and it's equivalent in all purposes to the real information the code represents.

Inside informatics, all the characters of the keyboard, and ll the characters that aren't appearing as key directly in the keyboard, are codified. The codification systems most used are **UTF8**, **UTF16** and **UTF32**.

UTF8 characters size **1 byte**. Then, when writing, 12 UTF8 characters size in total 12 bytes.

UTF32 characters size **4 bytes**. Then, 12 UTF32 characters size in total 48 bytes.

UTF16 characters are characters that can be UTF8 characters or UTF32 characters. Then, they size 1 byte per each UTF8 character plus 4 bytes per each UTF32 character. When writing, if there are 10 UTF8 characters and 2 UTF32 characters, the size of the 10 UTF8 characters will be 10 bytes, and the size of the 2 UTF32 characters will be 8 bytes, making in total 18 bytes for those 12 UTF16 characters.

All UTF codification schemes are managed by the informatics organization called **Unicode**. In their website, all Unicode codification schemes can be seen, there're a big amount of different Unicode alphabets. The alphabets available are all the alphabets that exist, including chinese, russian, japanese, arab, persian, thai, and even ancient egypt (that's, jeroglyphs).

## File formats

A **file format** is a format for storing data inside a file. A file follows a file format if it doesn't breaks it, that's, if it follows the rules of the file format. If the file format is correct, then a program that opens that file format can read the file and use it for the any purpose the program allows.

File formats common to all operating systems:

- **png:** Most common file format of images. It stores the image pixel by pixel.
- **jpeg:** Also called **jpg**. It stores a photo with an algorithm that reduces its size in expense of reducing also its quality.
- **gif:** File format of images that stores an animation.
- **bmp:** Old file format of images which size more than png for the same image.
- **mp4:** Common file format of videos.
- **mkv:** File format of videos of high quality and also high consumption of resources and higher size than mp4.
- **avi:** Old file format of videos of more size than mp4.
- **mp3:** File format of audio.
- **docx:** File format of enriched text used by **Microsoft Word**. Strictly, file formats of Microsoft Office can be used inside Linux, iOS, and any other operating system, not only Windows.
- **calcx:** File format of calculus sheets used by **Microsoft Excel**.

File formats used by Windows operating systems:

- **exe:** File format used by Windows for executable files, that's, files that run a program.
- **msi:** File format used by Windows for installers of programs. It's an acronym of **m**icro**s**oft **i**nstaller.
- **dll:** File format for dynamic libraries. It's used by Windows.
- **txt:** File format of plain text files used only inside **Windows**.

File formats used majoritarily by Linux distributions, although also in all other operating systems:

- **elf:** File format for executable files used by GNU operating systems.
- **deb:** File format of software packages for Debian operating systems.
- **rpm:** File format of software packages for Red Hat operating systems.
- **conf:** File format for configuration files. Used by open source software.
- **cfg:** File format for configuration files, competition of conf. Used by open source software.
- **xml:** Schema for creating file formats, all following the xml style. Invented by the **W3C**.
- **yml:** Schema for creating file formats, competition of xml.

## Hardware characteristics

- **Processing power or CPU power:** Speed for processing computer instructions. It's measured in **GHz** and sometimes in **FLOPS**, both measures aren't convertible because the reasoning for each one is different.
- **RAM**: Amount of random memory the computer has available. Every process of a computer consumes RAM. Inside a program, each instantiation of a variable consumes memory.
- **Graphics power or GPU power:** Speed for processing graphics. It's measured in **GHz** or **VHz**. Also, **FLOPS** can also be used as measure.
- **VRAM:** Visual RAM. RAM used for displaying graphics, it's contained inside the graphics cards. The more triangles are drawn for a 3D images, the more VRAM is needed for that.
- **Storage capacity:** Amount of information that the computer can store. It's measured in **GB** or **TB**.

## Hardware components

- **Motherboard:** Electronic component where all the other components are inserted. It contains a software called **BIOS** which allows to configure how the motherboard behaves related to each component it has connected.
- **Processor or CPU:** Electronic component that computes every program in binary form, that's, written in **assembler language**. It's inserted inside the **socket** of the motherboard.
- **Cooler:** Electronic component that dissipates the heat of the processor. It's added on the top of the processor adding a **thermal paste** to the processor first.
- **RAM memory:** Card that is inserted into the motherboard and provides RAM to the computer.
- **Hard disk:** Electronic component that can store information permanently. The difference it has to the RAM memory is that the information that it contains is not deleted when the computer is shutdown.
- **Graphics card or GPU:** Electronic component that contains a **graphics processor**, called **GPU**, and memory dedicated exclusively for **graphics purposes**, called **VRAM**. It's the sum of the CPU and the RAM memory.
- **Power supply:** Electronic component that provides the electricity to the motherboard.
- **Chassis:** It contains the motherboard with all his components attached. The common size for it is **ATX**, which is the size that commonly desktop computers have, the other sizes are **Mini-ITX**, **MicroATX** and **EATX**.

Inside a motherboard there are included the following components, impossible to separate from it:

- **Network card:** It manages the network connections of the computer. It contain the **ethernet port** to connect the computer to the local area network. The cable that's connected to the network card is called **ethernet cable**. There're network cards that have **wifi connections** rather than ethernet connections. More than one network card can be added to a motherboard, and the computer can have then ethernet and wifi connections at the same time.
- **Sound card:** It manages the sound of a computer.
- **BIOS:** Firmware that's stored inside the motherboard and allows to configure how it behaves related to the componets it has connected. A firmware is a software designed specifically to work inside an electronic device, like for example a motherboard.
- **Integrated graphics card:** Graphics card integrated in the motherboard, that usually doesn't has as much processing power as an external graphics card.

## Hardware peripherals

- **Keyboard:** Input device that allows to enter characters with the majority of his keys, among other instructions with the rest of the keys. There are different distributions of keys for a keyboard, the most common is the **QWERTY** distribution.
- **Mouse:** Input device that allows to enter input in the form of pairs of coordinates (x,y).
- **Monitor:** Output device that displays a graphical output.
- **Speakers:** Output devices that give an output of sound.
- **Webcam:** Input device that streams a video.

**Plug and play**, abbreviated **PnP**, means that a peripheral can be connected to a computer and used instantly, without needing to configure it or to restart the computer.

## Hardware accessories

- **Mousepad:** Pad that allows to move the mouse easy.

## Hardware ports

The **internal ports** are the following:

- **ATX-24 connector:** It connects the motherboard to the power supply.
- **Socket:** It connects the processor to the motherboard.
- **DDR5:** It connects the RAM memory to the motherboard. The previous versions where **DDR4**, **DDR3**, **DDR2** and **DDR**. DDR5 slots are compatible with previous RAM memories, and so a DDR4 RAM memory can be used in a DDR5 slot.
- **SATA:** It connects the hard disk to the motherboard.

The **peripheral ports** are the following:

- **PS/2:** It connects mouses or keyboards to the motherboard, one at a time.
- **AC:** It connects the power supply to the electricity network.
- **PCI express:** It allows to connect a hardware component to the motherboard. It has a generic purpose, and it allows to extend the motherboard with any kind of device.
- **HDMI:** It connects the monitor to the motherboard.
- **Ethernet port:** It connects the computer to the local area network.
- **USB:** It allows to transfer data and energy between the motherboard and the device connected through it. Majoritarily used for storage devices (pendrives), mouses and keyboards, but it's a generic port.

## Hardware brands

- **Intel:** They created the intel processors.
- **AMD:** Also called **Advanced Micro Devices**. They created the amd processors and currently they also manage the radeon graphics cards.
- **Asus:** Brand of motherboards. For computers dedicated to run videogames they have the brand **Republic of Gamers (RoG)**.
- **MSI:** Brand of motherboards.
- **Gigabyte:** Brand of motherboards. The name gigabyte is the same as the gigabyte unit, but is a different concept the unit and the brand.
- **Nvidia:** Brand of the nvidia graphics cards.
- **Corsair:** One of the better brands of RAM memory cards, power supplies and coolers.
- **Thermaltake:** Another important brand of power supplies, chassis, fans, RAM memory, among other computer products.
- **Western digital:** Brand of hard disks.

## How to mount a computer

The first action to do is to attach the motherboard to the chassis, use the screws that come with the motherboard to attach it to the chassis.

The next set of actions to do is to connect all the hardware components to the motherboard. First add the processor to the socket. After that, add the thermal paste in top of the processor and then add the cooler in top of the processor, the thermal paste then should be between the processor and the cooler. Add the RAM memory to the RAM sockets. Add the graphics card to the PCI express. Add all the hard disks to the SATA ports. Connect then the power supply, by connecting first to the central electricity of the motherboard. Then, add the power supply connectors to the hard disk and to the graphics cards.

Now that all the hardware components are connected, close the chassis and attach the hardware peripherals. Attach the mouse, the keyboard, connect the ethernet cable, connect the monitor and the speakers.

## Keyboard keys

## Computer networks

- **LAN:** Acronym of **Local Area Network**. It consists of all the computers that are inside a house or another similar place.
- **WLAN:** Acronym of **Wireless Local Area Network**.
- **WAN:** Acronym of **Wide Area Network**. It consists of a wide area of computers that are connected to that same network, usually through different LANs.

## Network connections

The **Internet Service Provider (ISP)** is the organization, usually a company, that provides the internet connection through a subscription. A **network modem** manages the network connections of all computers of a LAN, like for example a house, and sends them to the Internet Service Provider. A **router** is another name used currently as synonym for modem.

- **Ethernet:** It consists of a cable that connects a computer to a computer network.
- **Wifi:** Technology that allows to be connected to a computer network wirelessly, that's, without cables.
- **Bluetooth:** Technology that allows to be connected to a computer network wirelessly, his connection speed is slower than wifi.

## Operating systems

### Windows

Operating system created by **Microsoft**. It has had various versions, which are **Windows 1**, **Windows 2**, **Windows 3**, **Windows 95**, **Windows 98**, **Windows 2000**, **Windows XP**, **Windows Vista**, **Windows 7**, **Windows 8**, **Windows 10** y **Windows 11**.

A **application**, in Windows, is every program that appears with a **graphical user interface**, that's, inside a window. A **service**, in Windows, in contrast to applications, is every program that's executed in the background, without showing a graphical user interface of it. A **process**, that's, a set of instructions executed by a processor, in Windows, can be different to an application and also different to a service and, so, strictly, all the processes that Windows executes aren't necessarily an application or a service. All the internal parts of the operating system of Windows are executed by processes, too.

The **desktop**, inside Windows, is where the direct accesses of the applications appear and can be started from there.

The **task manager** allows to stop programs and services. It also shows the consumption of CPU and RAM. It's executed by typing **Alt+Ctrl+Supr**.

### Android

Operating system for embedded systems managed by the **Open Handset Alliance**. It's an operating system of generic purpose that adds sensors and all important technologies utilities to embedded systems to allow it to do everything currently invented by informatic technologies. Android devices can then do calls, connect to internet, send voice messages by internet, measure the temperature, recognice voice, recognice faces, among a wide amount of features. Android is centrally used for smartphones, but it can also be used for any other electronic device, of any kind.

### UNIX

Operating system created by **Dennis Ritchie** and **Ken Thompson**. It's the first operating system created and it's the operating system with very high trascendence that has shaped the informatics. It has had the first shell, called in his first version the **thompson shell**, and the C compiler, called **cc**, the build program called **make**, among many other essential programs that together have created the start of the informatics era.

The filesystem of a UNIX operating system is composed of the following folders:

- **bin/**
- **boot/**
- **home/**
- **sbin/**
- **usr/**
- **var/**

The principle of UNIX says that each program should to one task good, a no more than one kind of task.

### Linux

**Linux** is a kernel that allows to create operating systems. A **kernel** is the central part of an operating system, it contains the process scheduler, which is the central part of the kernel and is the part that controls the execution of processes. The different parts of the Linux kernel are called **modules**. The process scheduler is one of the modules, the others manage for example the input and output that processes can do, the signals between processes, and the drivers of the hardware of the computer. The modules of the Linux kernel can be installed and updated by using the command line.

An operating system created using the Linux kernel is called a **Linux distribution**. Linux is open source software and then it can be used freely by anyone to create an operating system for any purpose. A Linux distribution implements over the Linux kernel a **desktop environment** that allows to use the operating system. The most important desktop environments for Linux are **GNOME**, **KDE plasma desktop** and **LXQT**.

The most common Linux distribution, which uses GNOME, is **Ubuntu**. The most important Linux distribution usually is considered **Debian**. **Fedora** and **KDE Neon** are other important Linux distributions. All Linux distributions are composed of **packages**, which are files that contains one or more software, with, usually, their respective documentation. The most common extensions of Linux packages are **deb** and **rpm**. All Linux distributions contains different packages by default. It's that difference in the packages they contain what makes each Linux distribution unique related to the other Linux distributions.

### iOS

### BSD

Family of operating systems that are a variant of Linux operating systems that allow to change everything of them. They are open source and in their open source license they allow any change. Then, BSD operating systems can be used for any purpose, and be customized for any need, of any electronic device. It has been used for videogame consoles, and for a wide amount of electronic gadgets, due to it enormous versatility.

## The web

The **web** is the set of all websites linked by urls between them. A **website** is an entity that contains any number of webpages. A **webpage** is a digital page that contains information in the form of enriched text, images, videos, among any other interaction.

The acronym **www** means **world wide web**.

The web is managed by the **W3C**, called **World Wide Web Consortium**.

- **Mozilla Firefox:** Web browser created by **Mozilla**.
- **Google Chrome:** Web browser created by **Google**.
- **Microsoft Edge:** Web browser created by **Microsoft**.
- **Safari:** Web browser created by **Apple** for their operating systems.

## Common programs

### Windows

The first collection of programs to know in Windows is **Microsoft Office**, which includes a good amount of programs to do different paper work and related tasks.

- **Microsoft word:** Part of Microsoft Office. It allows to write enriched text, and to separate it in different chapters.
- **Microsoft Excel:** Part of Microsoft Office. It allows to have calculation sheets.
- **Microsoft PowerPoint:** Part of Microsoft Office. It allows to create presentations.
- **Windows Media Player:** It plays videos of different file formats.
- **Microsoft Store:** Application which allows to purchase applications with a bank account and to download them directly, without needing to wait for a DVD of the software.

### Linux distributions

- **Libreoffice:** Free variant of Microsoft Office created by the open source community. It also works on Windows.
- **Inkscape:** Vectorial drawing application. It also works on Windows.
- **Krita:** Drawing application made by **KDE**. It also works on Windows.
- **VLC:** Video player. It also works on Windows.
- **Dragon Player:** Video player made by **KDE**.

## Important informatics

- **Alan Turing:** He created the computers by creating the **turing machine**, which is the base for the processors.
- **Dennis Ritchie:** He created the **C programming language** and the **UNIX operating system**, which are the base technologies for the current computers.
- **Ken Thompson:** He created the **UNIX operating system** with Dennis Ritchie. In it, among a lot of other technologies he created the **thompson shell**, **tsh**, which was the first shell.
- **Bjarne Stroustrup:** He created the **C++ programming language**.
- **Richard Stallman:** He created the **open source movement** and founded **GNU**. He programmed the compilers of **GCC**.
- **Linus Torvalds:** He created Linux, and leads the **Linux Foundation**.

## Important organizations and businesses of informatics

- **GNU:** Organization that provides all the technologies needed for programming and for handling operating systems. The most important are the **compilers of GCC**, the **GNU binutils** and the **GNU coreutils**.
- **Apache Software Foundation:** Foundation that provides the central technologies for development of technologies useful for organizations of any type, private or public, for profit and not for profit, the technologies can be related to internet or not.
- **Linux Foundation:** Foundation that manages the Linux Kernel and help in the development of a good amount of Linux-related technologies.
- **Mozilla:** Internet foundation that created Mozilla Firefox and Thunderbird. They promote the freedom of internet and the web.
- **Microsoft:** Business that created Windows, Microsoft Office, Xbox, and all Microsoft technologies for development, like SQL Server, C#, UTF16, among a good amount.
- **Apple:** Business that created the Mac computers, the iPhone, the iPad, iOS and Mac OS.
- **Debian Foundation:** Foundation that manages Debian, one of the most popular Linux distributions.
- **Google:** Internet organization that created a lot of internet-related technologies. The most important ones are the Google Searcher, Gmail, YouTube and the Android operating system.
- **Facebook:** Internet organization that created Facebook, among a good amount of web-related technologies.
