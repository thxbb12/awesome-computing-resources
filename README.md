# Awesome Computing Resources

A curated list of awesome computing/programming resources.

## Contents
* [Artificial intelligence](#artificial-intelligence)
* [Bioinformatics](#bioinformatics)
* [Blogs](#blogs)
* [Books](#books)
* [Bootloaders](#bootloaders)
* [C](#c)
* [Ceph](#ceph)
* [Compilation](#compilation)
* [Computer Graphics](#computer-graphics)
* [Conferences](#conferences)
* [Containers](#containers)
* [Courses](#courses)
* [Distributed Computing](#distributed-computing)
* [Editors](#editors)
* [Education](#education)
* [Embedded Systems](#embedded-systems)
* [Emulation](#emulation)
* [Encoding](#Encoding)
* [Funny](#funny)
* [Games](#games)
* [Golang](#golang)
* [Graphs/charts/diagrams](#graphs-charts-diagrams)
* [Hacks](#hacks)
* [Hardware](#hardware)
* [Languages](#languages)
* [Linux](#linux)
* [Networking](#networking)
* [Operating Systems](#operating-systems)
* [People](#people)
* [Programming](#programming)
* [Repositories](#repositories)
* [Research papers](#research-papers)
* [Rust](#rust)
* [Security](#security)
* [Search Engines](#search-engines)
* [Shell](#shell)
* [Storage](#storage)
* [Systems](#systems)
* [Text editors/processing](#text-editors)
* [Tools](#tools)
* [Virtualization](#virtualization)

## Artificial intelligence
* [scikit-learn][31] - Simple and efficient machine learning tools in Python
* [huggingface][211] - The platform where the machine learning community collaborates on models, datasets, and applications. 
* [llm.c][223] - LLM training in simple, raw C/CUDA

## Bioinformatics
* [openms][46] - OpenMS is an open-source C++ library for LC-MS data management and analysis (github [here](https://github.com/OpenMS)).

## Blogs
* [Julia Evans][44] - Julia Evans' blog (mostly systems topcis)
* [Christine Dodrill][47] - Christine Dodrill's blog (web and backend services devops)
* [Mathieu Ropert][57] - A blog about C++ with a bit of a French touch
* [The Overflow][58] - The Stackoverflow Blog
* [Drew DeVault][240] - Drew DeVault is the creator of the Hare language, founder of SourceHut, author of the Wayland book, etc.
* [confessions of a code addict][254] - Passionate software engineer with a knack for turning complex ideas into simple solutions; insights and experiences from over a decade in the tech industry.

## Books
* [SystemsApproach book][138] - Computer Networks: A Systems Approach

## Bootloaders
* [POSIX-UEFI][142] - Dependency-free POSIX compatibility layer and build environment for UEFI
* [The rEFInd Boot Manager][15] - A boot manager for computers based on EFI and Unified EFI (UEFI).
* [bootboot][86] - BOOTBOOT has the opposite philosophy than GRUB: a set of simple and small loaders which provide the same boot environment for your kernel on different 64-bits platforms.
* [easyboot][234] - Easyboot is an all-in-one boot manager and bootable disk image creator that can load various OS kernels and Multiboot2 compliant kernels in various binary formats.
* [simpleboot][235] - Easyboot's little brother, simpler, which loads a single kernel only.
* [limine][236] - Modern, advanced, portable, multiprotocol bootloader and boot manager.
* [Managing EFI Boot Loaders for Linux][16] - Resources on EFI boot, secure boot, boot loaders and managers.
* [UEFI boot][69] - UEFI boot: how does that actually work, then?
* [Plop Boot Manager][17] - The Plop Boot Manager is a small program to boot different operating systems.
* [The Syslinux Project][18] - The SYSLINUX Project is a suite of lightweight MBR boot loaders for starting up PCs with the Linux kernel.
* [Linux on UEFI][74] - Linux on UEFI: A Quick Installation Guide
* [GOP][141] - Programming EFI Graphics Output Protocol (GOP) services
* [GNU-EFI][143] - GNU-EFI is a very lightweight developing environment to create UEFI applications using a system's native GCC.
* [GRUB rescue on UEFI][158] - GRUB rescue on UEFI based systems

## C
* [awesome-c][8] - A curated list of awesome C frameworks, libraries, resources and other shiny things.
* [Collections-C][1] - Library of generic data structures.
* [PIC, PIE and Sanitizers][56] - PIC, PIE and Sanitizers
* [libmill][78] - Libmill is a library that introduces Go-style concurrency to C.
* [coroutines C][79] - Coroutines in C.
* [SectorC][173] - SectorC: A C Compiler in 512 bytes.
* [matrix oo][249] - Sample matrix implementation illustrating object-oriented techniques in C99.

## Ceph
* [qemu ceph rbd perf][255] - Performance tuning of QEMU on Ceph rbd storage
* [ceph rbd snapshots][256] - Ceph rbd snapshots
* [ceph cheatsheet][257] - Ceph Cheatsheet

## Compilation
* [Godbolt][32] - Compile some code and watch the generated assembly for different programming languages.
* [llvm backend cpu0][144] - Creating an LLVM Backend for the Cpu0 Architecture
* [emscripten][165] - Emscripten is a complete compiler toolchain to WebAssembly, using LLVM
* [disasm.pro][171] - Online dissassembler for many architectures
* [llvm backend][229] - Writing an LLVM Backend
* [qbe][242] - QBE is a compiler backend that aims to provide 70% of the performance of industrial optimizing compilers in 10% of the code.

## Computer Graphics
* [scratchapixel][7] - Mathematics and Physics for Computer Graphics
* [simple2d][26] - Small, open-source graphics engine providing essential 2D drawing, media, and input capabilities (C)
* [orx][27] - Open source, portable, lightweight, plugin-based, data-driven and extremely easy to use 2D-oriented game engine (C)
* [csfml][30] - Simple and Fast Multimedia Library to ease the development of games and multimedia applications (C)
* [thebookofshaders][130] - This is a gentle step-by-step guide through the abstract and complex universe of Fragment Shaders
* [GPU arch explained][183] - GPU architecture types explained (Immediate-Mode vs Tile-Based rendering)
* [raylib][206] - raylib is a simple and easy-to-use library to enjoy videogames programming.
* [lodes computer gfx tutorial][216] - Lode's Computer Graphics Tutorial
* [automatic1111][218] - Stable Diffusion AI is a latent diffusion model for generating AI images
* [iopaint][220] - Image inpainting tool powered by SOTA AI Model. Remove any unwanted object, defect, people, etc. from your pictures.

## Courses
* [Awesome CS Courses][111] - Awesome Computer Science Courses

## Conferences
* [fosdem][87] - FOSDEM talks archives. Free and Open source Software Developers' European Meeting (FOSDEM) is a non-commercial, volunteer-organized European event centered on free and open-source software development.

## Containers
* [Docker internals][55] - Docker Internals, a deep dive into Docker for engineers interested in the gritty details
* [Under the hood of Docker][76] - Under the hood of Docker
* [Containers 500LOC][110] - Linux containers in 500 lines of code
* [rootless docker][159] - Run the Docker daemon as a non-root user
* [containers from scratch][169] - Containers from scratch
* [containerd][184] -  An open and reliable container runtime 
* [runc][185] - CLI tool for spawning and running containers
* [x11docker][208] - Run GUI applications and desktops in docker and podman containers.

## Distributed Computing
* [openfaas][214] - Serverless Functions Made Simple
* [raft][258] - The Raft Consensus Algorithm
* [raft go][259] - Golang implementation of the Raft consensus algorithm

## Editors
* [zettlr][103] - Zettlr: A Markdown editor for the 21st century

## Education
* [AMC][248] - Create and manage multiple choice questionnaires (MCQ), with automated marking.

## Embedded Systems
* [TinyGo][101] - A Go compiler for microcontrollers
* [MicroPython][88] - Implementation of Python 3 for microcontrollers which includes a small subset of the Python standard library
* [elinux][63] - Embedded Linux Wiki 
* [FreeRTOS][64] - FreeRTOS is a real-time operating system for microcontrollers
* [uC-OS3][65] - µC/OS-III is a highly portable, ROMable, scalable, preemptive, real-time, deterministic, multitasking kernel for CPU, MPU and DSP.
* [embedded][66] - The resource for everything embedded systems designers and developers need to do their jobs
* [build an embedded Linux system][72] - So you want to build an embedded Linux system?
* [synthos][73] - Synthesize your own optimized, custom real time operating system (RTOS)
* [BBC microbit][112] - The BBC micro:bit is a pocket-sized computer that introduces you to how software and hardware work together
* [BBC microbit hardware][113] - Detailed description of the BBC micro:bit's hardware
* [linux emb yocto][167] - Linux embarqué avec Yocto Project
* [Linux Yocto Cooker Imbriqué][179] - Imbriquer des systèmes Linux avec Yocto Cooker
* [U-Boot programming][180] - U-Boot programming tutorial 
* [rauc][217] - Safe and secure software updates for embedded Linux
* [Linux userspace examples][231] - Repository providing Linux application examples for common communication protocols: SPI, I2C, UART
* [Zephyr project][232] - Zephyr is a small RTOS for connected, resource-constrained and embedded devices supporting multiple architectures.
* [NuttX][233] - Apache NuttX is a highly scalable RTOS featuring small footprint and standards compliance (UNIX, POSIX, ANSI).

## Emulation
* [advanced qemu][221] - Advanced configuration for QEMU
* [DOSBox-X][225] - Open-source DOS/Win3.x/Win9x emulator for running DOS/windows applications and games. It is much more flexible and provides more features than DOSBox.
* [dosbox-x options][226] - DOSBox-X's Command-Line Options

## Encoding
* [unicode][187] - The Absolute Minimum Every Software Developer Must Know About Unicode in 2023.

## Funny
* [scigen][41] - An Automatic Computer Science Paper Generator

## Games
* [bevy][89] - A refreshingly simple data-driven game engine built in Rust
* [godot][145] - Godot is a cross-platform, free and open-source game engine
* [armory][146] - Armory is an open-source 3D game engine with full Blender integration
* [ogre][147] - OGRE is a scene-oriented, flexible, open-source 3D engine
* [o3de][148] - O3DE is an open-source, multi-platform 3D engine
* [panda3d][149] - Panda3D is an open-source, completely free-to-use engine for realtime 3D games
* [phaser][150] - Phaser is a free and fast 2D game framework for making HTML5 games

## Golang
* [awesome-go][115] - A curated list of awesome Go frameworks, libraries and software
* [go-101][116] - Go 101 is a series of books on Go programming
* [echo][117] - Echo is a high performance, extensible, minimalist Go web framework
* [chi][189] - A lightweight, idiomatic and composable router for building Go HTTP services
* [gin][190] - The fastest full-featured web framework for Go
* [webrpc][191] - webrpc is a schema-driven approach to writing backend services for modern Web apps and networks
* [go documentation][118] - Official Go documentation
* [Effective Go][121] - Effective Go short book
* [Go by Example][122] - Go by Example is a hands-on introduction to Go using annotated example programs
* [Resty][126] - Simple HTTP and REST client library for Go
* [Req][127] -  Simple Go HTTP client with Black Magic
* [Fyne][128] - Cross platform GUI in Go inspired by Material Design
* [gotk3][129] - Go bindings for GTK3
* [golang tutorials][131] - Golang tutorial series
* [go for C dev][132] - Go for C programmers
* [Organizing Go code][133] - Organizing Go code
* [Golang Goroutine Scheduler][192] - Understanding the Golang Goroutine Scheduler GPM Model
* [tview][193] - Terminal UI library with rich, interactive widgets (even "graphics")
* [reflection go][219] - Reflection in Go: Use cases and tutorial
* [common go mistakes][250] - 100 Common Go Mistakes
* [slice gotchas][251] - Why appending to slice in Golang is dangerous? Common Slice Gotchas

## Graphs charts diagrams
* [asciiflow][66] - ASCIIFlow is a client-side only web based application for drawing ASCII diagrams. Git repository [here](https://github.com/lewish/asciiflow).

## Hacks
* [destreamer][49] - destreamer, save Microsoft Stream videos for offline enjoyment
* [pihole][91] - Block ads for all devices inside your network with a Raspberry Pi
* [pihole setup][92] - How To Set Up Pi-hole
* [yt-dlp][262] - A feature-rich command-line audio/video downloader

## Hardware
* [piper][90] - The Piper Computer Kit is the ultimate DIY computer-building experience. Build a REAL computer from start to finish.
* [how dram works][154] - How does Computer Memory Work?
* [tiny tapeout][246] - Tiny Tapeout is an educational project that makes it easier and cheaper than ever to get your designs manufactured on a real chip!

## Languages
* [Language benchmarks][172] Programming language and compiler benchmarks.
* [Hare language][241] - Hare is statically-typed systems programming language designed to be simple, stable, and robust.
* [Zig language][230] - Zig is a general-purpose programming language and toolchain for maintaining robust, optimal and reusable software.
* [V language][243] - V is a statically typed compiled programming language designed for building maintainable software.

## Linux
* [Linux Kernel Monkey Log][19] - Greg Kroah-Hartman's blog (Linux kernel maintainer)
* [Linux Kernel in a Nutshell][20] - The "Linux kernel in a nutshell" free book from O'Reilly
* [Greg K-H's Linux Stuff][21] - Greg K-H's Linux Stuff (slides, talks, udev, hotplug, usb, etc.)
* [NixOS][36] - NixOS is a GNU/Linux distribution that aims to improve the state of the art in system configuration management (reliable and atomic upgrades, rollbacks, etc.)
* [Guix][37] - Guix is a GNU/Linux distribution that supports transactional upgrades, rollbacks, unprivileged package management, etc.
* [vramfs][170] - VRAM based file system for Linux
* [Linux kernel teaching][176] - Collection of lectures and labs on the Linux kernel
* [Grml Live Linux][181] - Debian based Linux Live system
* [Slax][199] - Slax is a compact, fast, modern and customizable Linux distro that can be generated into an ISO image.
* [cubic][202] - Cubic is a GUI wizard to create a customized Live ISO image for Ubuntu and Debian based distributions.
* [monogon][203] - Monogon OS is open-source, secure, API-driven, minimal, based on Linux and Kubernetes, with a clean userland rebuilt entirely from scratch in pure Go and eliminates decades worth of legacy code and unnecessary complexity.
* [mkusb][204] - mkusb is a simple, safe tool to create a bootable drive from an iso image or a compressed image file.
* [ubuntu-autoinstall-generator-tools][205] - A script to generate a fully-automated ISO image for installing Ubuntu onto a machine without human interaction.
* [binfmt_misc][245] - Kernel feature that allows you to invoke almost every program by simply typing its name in the shell (e.g. compiled Java or Python programs).

## Networking
* [IPFS][61] - A peer-to-peer hypermedia protocol designed to make the web faster, safer, and more open
* [sshuttle][125] - Transparent proxy server that works as a poor man's VPN. Forwards over ssh.

## Operating systems
* [Genode][105] - The Genode OS Framework is a tool kit for building highly secure special-purpose operating systems
* [Plan9][97] - Plan 9 from Bell Labs is a distributed OS designed to make a network of heterogeneous and geographically separated computers function as a single system
* [Inferno][98] - Inferno was created to bring ideas of Plan to a wider range of devices and networks
* [Inferno doc][224] - Inferno documentation
* [HelenOS][99] - HelenOS is a portable microkernel-based multiserver operating system designed and implemented from scratch
* [Serenity OS][51] - SerenityOS is a love letter to '90s user interfaces with a custom Unix-like core
* [x86-bare-metal-examples][52] - Dozens of minimal operating systems to learn x86 system programming
* [Rust RISC-V OS][109] - The Adventures of OS: Making a RISC-V Operating System using Rust
* [OS in Rust][114] - Writing an OS in Rust
* [managarm][139] - Pragmatic microkernel-based OS with fully asynchronous I/O
* [tilck][140] -  A Tiny educational Linux-Compatible kernel
* [AxleOS][174] - Axle OS is a hobby microkernel and userspace
* [egos-2000][175] - With only 2k lines of code, egos-2000 implements every component of an OS for education; it supports RISC-V boards and QEMU.
* [Debian Live][164] - The Debian Live project produces the framework used to build live systems based on Debian
* [gopher-os][212] - A proof of concept OS kernel written in Go
* [Multicians][213] - Presents the story of the Multics OS for people interested in the system's history
* [Little book OSdev][237] - The little book about OS development is a practical guide to writing your own x86 operating system.
* [Bredan mult-tasking][238] - Tutorial describing how to implement software multi-tasking and task switching for x86.
* [Unix clone in a month][239] - Writing a Unix clone in about a month.
* [osdev-notes][260] - A book that explore how to write an Operating System from scratch.

## People
* [Fabrice Bellard][247] - Fabrice Bellard, the author of QEMU, ffmpeg

## Programming
* [programming books][45] - Programming books (huge number of resources on many programming languages)
* [LeetCode][62] - LeetCode is the best platform to help you enhance your skills, expand your knowledge and prepare for technical interviews.
* [meson build][120] - Meson is an open source build system meant to be both extremely fast, and as user friendly as possible
* [ttt-bench][123] - Benchmark comparing the speed of many languages on a Tic-Tac-Toe solver
* [Benchmarks Game][124] Compare the performance of many languages across many tests
* [ncurses howto][215] - NCURSES Programming HOWTO
* [wizard zines][253] - Programming zines by Julia Evans

## Repositories
* [sourcehut][244] - SourceHut is a 100% open source, not owned by company, git forge.

## Research papers
* [google research][227] - Papers published by Google Research in a wide range of fields.

## Rust
* [The Rust Programming Language][24] - Book "The Rust Programming Language book"
* [awesome-embedded-rust][23] - Curated list of resources for Embedded and Low-level development in Rust
* [The Embedded Rust Book][25] - The Rust Programming Language (book)
* [awesome-rust][9] - A curated list of awesome Rust frameworks, libraries, resources and other shiny things.
* [cheats.rs][2] - Rust Language Cheat Sheet.
* [24daysofrust][3] - The "24 days of Rust" article series.
* [Learning Rust With Entirely Too Many Linked Lists][10] - Good / bad implementations of lists to learn Rust.
* [Actix][59] - Rust's powerful actor system and most fun web framework
* [Rocket][60] - Web framework that makes it simple to write fast, secure web applications
* [Polymorphism in Rust][95] - Polymorphism in Rust

## Search engines
* [google search op][82] - Google Search Operators: The Complete List.
* [Google Hacking DB][83] - Google Hacking Database.

## Security
* [urandom myths][96] - Myths about /dev/urandom
* [revers engineering][136] - Security research blog
* [apparmor guide][153] - The Comprehensive Guide To AppArmor
* [openssh priv key][161] - Public key cryptography: OpenSSH private keys
* [ssh tunneling][162] - SSH Tunneling Explained
* [keycloak][186] - Open Source Identity and Access Management For Modern Applications and Services (Single Sign-On)

## Shell
* [fzf][4] - A command-line fuzzy finder.
* [oh-my-zsh][5] - Manage ZSH configuration with plugins.
* [z][6] - Jump in directories based on 'frecency'.
* [explainshell.com][12] - Write down a command-line to see the help text that matches each argument.
* [tldr][14] - Simplified man pages with examples.
* [bat][40] - Syntax highlighting cat
* [shellsheck][41] - finds bugs in your shell scripts.
* [shfmt][42] - A shell parser, formatter, and interpreter (sh/bash/mksh)

## Storage
* [ext4 explained][156] - Ext4 filesystem explained: data blocks, super blocks, inode structure
* [ntfs cluster alloc][157] - Disk Cluster Allocation Behavior in Windows and NTFS
* [seaweedfs][207] - SeaweedFS is a fast distributed storage system for blobs, objects, files, and data lake, for billions of files!
* [btrfs][209] - BTRFS official documentation
* [timeshift][210] - System restore tool for Linux. Creates filesystem snapshots using rsync+hardlinks, or BTRFS snapshots. 

## Systems
* [gocrazy][100] - Replace Linux' core system layer by a pure and safe Go implementation
* [The TTY demystified][22] - The TTY demystified
* [collectd][33] - The system statistics collection daemon.
* [graphite][34] - Store numeric time-series data and render graphs of this data on demand.
* [grafana][35] - The open platform for beautiful analytics and monitoring.
* [sysstat][151] - Performance monitoring tools for Linux 
* [fosdem19][38] - FOSDEM (Free and Open source Software Developers' European Meeting) 2019 talks and papers
* [supervisord][48] - Supervisor: A Process Control System
* [pic shared libs][50] - Position Independent Code (PIC) in shared libraries 
* [ELF 101][54] - The 101 of ELF files on Linux: Understanding and Analysis
* [Evolution of the x86 context switch in Linux][68] - Evolution of the x86 context switch in Linux
* [Context Switching on x86][94] - Context Switching on x86
* [Beginners Guide to Udev][70] - Beginners Guide to Udev in Linux
* [Introduction to asynchronous IO][71] - A tiny introduction to asynchronous IO
* [systemd historical and technical retrospective][85] - systemd, 10 years later: a historical and technical retrospective
* [The hidden early history of Unix ][93] - The hidden early history of Unix
* [Systemd essentials][104] - Systemd Essentials: Working with Services, Units, and the Journal
* [AppImageKit][119] - AppImageKit is a concrete implementation of the AppImage format
* [FAI][137] - FAI is a tool for unattended mass deployment of Linux
* [bios keys][152] - Liste des touches accès au BIOS ou Boot menu par constructeur
* [hello world][155] - Hello World under the microscope
* [Cubic][163] - Custom Ubuntu ISO Creator
* [OSTree][182] - OSTree is an upgrade system for Linux-based operating systems that performs atomic upgrades of complete filesystem trees
* [modern-unix][188] - A collection of modern/faster/saner alternatives to common unix commands
* [kerrisk talks][222] - Michael Kerrisk Linux/kernel conferences' talks
* [zsync2][228] - zsync is designed for file distribution where only the new parts of the file are downloaded.

## Text editors
* [Textidote][263] - Correction tool for LaTeX: spelling, grammar, etc.
* [Basic Markdown Syntax][84] - Basic Markdown Syntax
* [Typst][194] - Typst is a new open-source typesetting system that is powerful and easy to learn, inspired by LaTeX
* [Polylux][197] - Polylux: package for Typst to create presentation slides
* [Touying][196] - Touying is a powerful and efficient package for creating presentation slides in Typst
* [Quarto][195] - An open-source scientific and technical publishing system
* [presenterm][261] - Create presentations in markdown format and run them from your terminal

## Tools
* [osboxes.org][11] - OS images ready to use with VirtualBox or VMware.
* [gitignore.io][13] - Create useful .gitignore files for your project.
* [Cool, but obscure unix tools][39] - A little collection of cool unix terminal/console/curses tools
* [ImHex][252] - A Hex Editor for Reverse Engineers, Programmers and people who value their retinas when working at 3 AM

## Virtualization
* [ARM virtualization][106] - An in-depth look into the ARM virtualization extensions
* [QuickEmu][102] - Quickly create and run highly optimised desktop virtual machines with just two commands
* [Firecracker][53] - Secure and fast microVMs for serverless computing
* [NOVA][107] - Research project aimed at constructing a secure virtualization environment with a small trusted computing base
* [NOVA microhypervisor][108] - Source code of the NOVA microhypervisor
* [NoVM][75] - novm is a legacy-free, type 2 hypervisor written in Go. Its goal is to provide an alternate, high-performance Linux hypervisor for cloud workloads.
* [xen guide][80] - Xen Project Beginners Guide
* [xen modes][81] - Xen Modes: What Color Is Your Xen?
* [Ravada][77] - Free, easy-to-use & deploy VDI solution. Ravada is an open-source project that allows users to connect to a virtual desktop.
* [MMU virt via Intel EPT][134] - MMU Virtualization via Intel EPT: Implementation
* [hypervisor-from-scratch][135] - Series of tutorials about implementing an hypervisor
* [vmm from scratch][168] - Hypervisor from scratch using Intel VT-x
* [embvm-core][160] - Embedded Virtual Machine Core Project
* [virtio driver][166] - Virtio driver implementation example
* [hypervisor][177] - A very simple hypervisor using the KVM API (Patrick Dumais)
* [KVM hypercall][178] - A Deep Dive in KVM Hypercall
* [Nanos][198] - Nanos is a new kernel designed to run one and only one application in a virtualized environment
* [spice-gtk-tutorial][200] - Tutorial for creating a VM Viewer with Spice-GTK 
* [go-spice][201] - Pure Go implementation of the Spice protocol 
* [Hypervisor-From-Scratch][264] - Mmulti-part series of tutorials "Hypervisor From Scratch"
* [vbox][265] - VirtualBox source code (mirror)

[1]: https://github.com/srdja/Collections-C
[2]: https://cheats.rs/
[3]: http://zsiciarz.github.io/24daysofrust/
[4]: https://github.com/junegunn/fzf
[5]: https://github.com/robbyrussell/oh-my-zsh
[6]: https://github.com/rupa/z
[7]: http://www.scratchapixel.com/
[8]: https://github.com/kozross/awesome-c
[9]: https://github.com/rust-unofficial/awesome-rust
[10]: http://cglab.ca/~abeinges/blah/too-many-lists/book/
[11]: https://www.osboxes.org/
[12]: https://explainshell.com/
[13]: https://www.gitignore.io/
[14]: https://github.com/tldr-pages/tldr
[15]: http://www.rodsbooks.com/refind/
[16]: http://www.rodsbooks.com/efi-bootloaders/index.html
[17]: https://www.plop.at/en/bootmanager/full.html
[18]: https://www.syslinux.org
[19]: http://www.kroah.com/log/
[20]: http://www.kroah.com/lkn/
[21]: http://www.kroah.com/linux/
[22]: https://www.linusakesson.net/programming/tty/
[23]: https://github.com/rust-embedded/awesome-embedded-rust
[24]: https://doc.rust-lang.org/book/index.html
[25]: https://doc.rust-lang.org/nightly/embedded-book/index.html
[26]: https://github.com/simple2d/simple2d
[27]: http://orx-project.org/
[30]: https://www.sfml-dev.org/download/csfml/
[31]: https://scikit-learn.org/stable/
[32]: https://www.godbolt.org/
[33]: https://collectd.org/
[34]: https://graphiteapp.org/
[35]: https://grafana.com/grafana
[36]: https://nixos.org/
[37]: https://guix.gnu.org/
[38]: https://www.fosdem.org/2019/schedule/
[39]: https://kkovacs.eu/cool-but-obscure-unix-tools
[40]: https://github.com/sharkdp/bat
[41]: https://pdos.csail.mit.edu/archive/scigen/
[42]: https://www.shellcheck.net/
[43]: https://github.com/mvdan/sh
[44]: https://jvns.ca/
[45]: https://github.com/smdocs/my-book-notes/blob/master/programming-books.md
[46]: https://www.openms.de/
[47]: https://christine.website/
[48]: http://supervisord.org/
[49]: https://github.com/snobu/destreamer
[50]: https://eli.thegreenplace.net/2011/11/03/position-independent-code-pic-in-shared-libraries/
[51]: https://serenityos.org/
[52]: https://github.com/cirosantilli/x86-bare-metal-examples
[53]: https://firecracker-microvm.github.io/
[54]: https://linux-audit.com/elf-binaries-on-linux-understanding-and-analysis/
[55]: http://docker-saigon.github.io/post/Docker-Internals/
[56]: https://mropert.github.io/2018/02/02/pic_pie_sanitizers/
[57]: https://mropert.github.io/
[58]: https://stackoverflow.blog/
[59]: https://actix.rs/
[60]: https://rocket.rs/
[61]: https://ipfs.io
[62]: https://leetcode.com/
[63]: https://www.elinux.org/Main_Page
[64]: https://www.freertos.org/
[65]: https://github.com/SiliconLabs/uC-OS3
[66]: https://www.embedded.com/
[67]: https://asciiflow.com/
[68]: https://www.maizure.org/projects/evolution_x86_context_switch_linux/
[69]: https://www.happyassassin.net/posts/2014/01/25/uefi-boot-how-does-that-actually-work-then/
[70]: https://www.thegeekdiary.com/beginners-guide-to-udev-in-linux/
[71]: http://www.wangafu.net/~nickm/libevent-book/01_intro.html
[72]: https://jaycarlson.net/embedded-linux/
[73]: http://zeidman.biz/SynthOS.htm
[74]: http://www.rodsbooks.com/linux-uefi/
[75]: https://github.com/google/novm
[76]: https://debugged.it/blog/under-the-hood-of-docker/
[77]: https://ravada.upc.edu/#get-started
[78]: https://github.com/sustrik/libmill
[79]: https://www.chiark.greenend.org.uk/~sgtatham/coroutines.html
[80]: https://wiki.xenproject.org/wiki/Xen_Project_Beginners_Guide
[81]: http://www.brendangregg.com/blog/2014-05-07/what-color-is-your-xen.html
[82]: https://ahrefs.com/blog/google-advanced-search-operators/
[83]: https://www.exploit-db.com/google-hacking-database
[84]: https://www.markdownguide.org/basic-syntax
[85]: https://blog.darknedgy.net/technology/2020/05/02/0/
[86]: https://gitlab.com/bztsrc/bootboot
[87]: https://fosdem.org/archives/
[88]: https://micropython.org/
[89]: https://bevyengine.org/
[90]: https://www.playpiper.com/
[91]: https://pi-hole.net/
[92]: https://medium.com/swlh/how-to-set-up-pi-hole-2293246dc8ed
[93]: https://papers.freebsd.org/2020/fosdem/losh-hidden_early_history_of_unix/
[94]: https://samwho.dev/blog/context-switching-on-x86/
[95]: https://oswalt.dev/2021/06/polymorphism-in-rust/
[96]: https://www.2uo.de/myths-about-urandom/
[97]: http://9p.io/plan9/
[98]: https://github.com/inferno-os/inferno-os
[99]: http://www.helenos.org/
[100]: https://gokrazy.org/
[101]: https://tinygo.org/
[102]: https://github.com/quickemu-project/quickemu
[103]: https://www.zettlr.com/
[104]: https://www.digitalocean.com/community/tutorials/systemd-essentials-working-with-services-units-and-the-journal
[105]: https://genode.org/index
[106]: https://genode.org/documentation/articles/arm_virtualization
[107]: http://hypervisor.org/
[108]: https://github.com/udosteinberg/NOVA
[109]: https://osblog.stephenmarz.com/
[110]: https://blog.lizzie.io/linux-containers-in-500-loc.html
[111]: https://github.com/prakhar1989/awesome-courses
[112]: https://microbit.org/
[113]: https://tech.microbit.org/hardware/
[114]: https://os.phil-opp.com/
[115]: https://github.com/avelino/awesome-go
[116]: https://github.com/go101/
[117]: https://echo.labstack.com/
[118]: https://go.dev/doc/
[119]: https://github.com/AppImage/AppImageKit
[120]: https://mesonbuild.com/
[121]: https://go.dev/doc/effective_go
[122]: https://gobyexample.com/
[123]: https://github.com/BartMassey/ttt-bench
[124]: https://benchmarksgame-team.pages.debian.net/benchmarksgame/index.html
[125]: https://github.com/sshuttle/sshuttle
[126]: https://github.com/go-resty/resty
[127]: https://github.com/imroc/req
[128]: https://github.com/fyne-io/fyne
[129]: https://github.com/gotk3/gotk3
[130]: https://thebookofshaders.com/
[131]: https://golangbot.com/learn-golang-series/
[132]: https://talks.golang.org/2012/goforc.slide
[133]: https://talks.golang.org/2014/organizeio.slide
[134]: https://revers.engineering/mmu-virtualization-impl-p1/
[135]: https://github.com/SinaKarvandi/Hypervisor-From-Scratch/
[136]: https://revers.engineering/
[137]: https://fai-project.org/
[138]: https://github.com/SystemsApproach/book
[139]: https://github.com/managarm/managarm
[140]: https://github.com/vvaltchev/tilck
[141]: https://wiki.osdev.org/GOP
[142]: https://gitlab.com/bztsrc/posix-uefi
[143]: https://wiki.osdev.org/GNU-EFI
[144]: https://jonathan2251.github.io/lbd/llvmstructure.html
[145]: https://godotengine.org/
[146]: https://armory3d.org/
[147]: https://www.ogre3d.org/
[148]: https://www.o3de.org/
[149]: https://www.panda3d.org/
[150]: https://phaser.io/
[151]: https://github.com/florentgluck/awesome-computing-resources
[152]: https://www.malekal.com/liste-touches-acces-bios-boot-menu-constructeur/#Touche_raccourcis_acces_au_BIOS_ou_boot_menu
[153]: https://medium.com/information-and-technology/so-what-is-apparmor-64d7ae211ed
[154]: https://www.youtube.com/watch?v=7J7X7aZvMXQ
[155]: https://gynvael.coldwind.pl/?id=754
[156]: https://adil.medium.com/ext4-filesystem-data-blocks-super-blocks-inode-structure-1afb95c8e4ab
[157]: https://link.springer.com/article/10.1007/s11036-019-01441-1
[158]: https://medium.com/@Arnab_Sat/grub-rescue-on-uefi-based-systems-7bf520e414aa
[159]: https://docs.docker.com/engine/security/rootless/
[160]: https://github.com/embvm/embvm-core/
[161]: https://www.thedigitalcatonline.com/blog/2021/06/03/public-key-cryptography-openssh-private-keys/
[162]: https://goteleport.com/blog/ssh-tunneling-explained/
[163]: https://github.com/PJ-Singh-001/Cubic
[164]: https://wiki.debian.org/DebianLive/
[165]: https://emscripten.org/
[166]: http://www.dumais.io/index.php?article=aca38a9a2b065b24dfa1dee728062a12
[167]: https://www.blaess.fr/christophe/yocto-lab/index.html
[168]: http://www.dumais.io/index.php?article=ac3267239dd3e34c061de6413203fb98
[169]: http://www.dumais.io/index.php?article=541cd30aa440e24f6a6f67eea9ce7caf
[170]: https://github.com/Overv/vramfs
[171]: https://disasm.pro/
[172]: https://programming-language-benchmarks.vercel.app/
[173]: https://xorvoid.com/sectorc.html
[174]: https://axleos.com/
[175]: https://github.com/yhzhang0128/egos-2000
[176]: https://linux-kernel-labs.github.io
[177]: https://github.com/pdumais/hypervisor
[178]: https://tianrenz2.github.io/KvmHypercall
[179]: https://www.blaess.fr/christophe/2022/02/03/5973/
[180]: http://www.xillybus.com/tutorials/uboot-hacking-howto-1
[181]: https://grml.org/
[182]: https://ostreedev.github.io/ostree/introduction/
[183]: https://www.rastergrid.com/blog/gpu-tech/2021/07/gpu-architecture-types-explained/
[184]: https://github.com/containerd/containerd
[185]: https://github.com/opencontainers/runc
[186]: https://www.keycloak.org/
[187]: https://tonsky.me/blog/unicode/
[188]: https://github.com/ibraheemdev/modern-unix
[189]: https://go-chi.io/#/
[190]: https://gin-gonic.com/
[191]: https://github.com/webrpc/webrpc
[192]: https://dev.to/aceld/understanding-the-golang-goroutine-scheduler-gpm-model-4l1g
[193]: https://github.com/rivo/tview
[194]: https://typst.app/
[195]: https://quarto.org/
[196]: https://typst.app/universe/template/touying
[197]: https://polylux.dev/book/polylux.html
[198]: https://github.com/nanovms/nanos
[199]: https://www.slax.org/
[200]: https://github.com/Rylern/SpiceGTK-tutorial
[201]: https://github.com/Shells-com/spice
[202]: https://github.com/PJ-Singh-001/Cubic
[203]: https://monogon.tech/monogon_os.html
[204]: https://help.ubuntu.com/community/mkusb
[205]: https://github.com/lefeck/ubuntu-autoinstall-generator-tools?tab=readme-ov-file
[206]: https://www.raylib.com/
[207]: https://github.com/seaweedfs/seaweedfs
[208]: https://github.com/mviereck/x11docker
[209]: https://btrfs.readthedocs.io/en/latest/Introduction.html
[210]: https://github.com/linuxmint/timeshift
[211]: https://huggingface.co/
[212]: https://github.com/gopher-os/gopher-os
[213]: https://www.multicians.org/
[214]: https://github.com/openfaas/faas
[215]: https://tldp.org/HOWTO/NCURSES-Programming-HOWTO/
[216]: https://lodev.org/cgtutor/
[217]: https://github.com/rauc/rauc
[218]: https://stable-diffusion-art.com/automatic1111/
[219]: https://blog.logrocket.com/reflection-go-use-cases-tutorial/
[220]: https://github.com/Sanster/IOPaint
[221]: https://docs.blissos.org/installation/install-in-a-virtual-machine/advanced-qemu-config/
[222]: https://www.youtube.com/playlist?list=PLPEqSODQbwFjVfdvqOz_ZOOto0SnjtPYx
[223]: https://github.com/karpathy/llm.c
[224]: https://www.inferno-os.org/inferno/
[225]: https://dosbox-x.com/
[226]: https://github.com/joncampbell123/dosbox-x/wiki/DOSBox%E2%80%90X%E2%80%99s-Command%E2%80%90Line-Options
[227]: https://research.google/
[228]: https://github.com/AppImageCommunity/zsync2
[229]: https://llvm.org/docs/WritingAnLLVMBackend.html
[230]: https://ziglang.org/
[231]: https://github.com/Digilent/linux-userspace-examples
[232]: https://www.zephyrproject.org/
[233]: https://nuttx.apache.org/
[234]: https://gitlab.com/bztsrc/easyboot
[235]: https://gitlab.com/bztsrc/simpleboot
[236]: https://github.com/limine-bootloader/limine
[237]: https://littleosbook.github.io/
[238]: https://wiki.osdev.org/Brendan%27s_Multi-tasking_Tutorial
[239]: https://drewdevault.com/2024/05/24/2024-05-24-Bunnix.html
[240]: https://drewdevault.com/
[241]: https://harelang.org/
[242]: https://c9x.me/compile/
[243]: https://vlang.io/
[244]: https://sourcehut.org/
[245]: https://www.kernel.org/doc/html/latest/admin-guide/binfmt-misc.html
[246]: https://tinytapeout.com/
[247]: https://bellard.org/
[248]: https://www.auto-multiple-choice.net/
[249]: https://github.com/sysprog21/matrix_oo
[250]: https://100go.co/
[251]: https://codefibershq.com/blog/golang-why-appending-to-slice-is-dangerous-common-slice-gotchas
[252]: https://github.com/WerWolv/ImHex
[253]: https://wizardzines.com/comics/
[254]: https://blog.codingconfessions.com/
[255]: https://ceph.io/en/news/blog/2022/qemu-kvm-tuning/
[256]: https://docs.ceph.com/en/quincy/rbd/rbd-snapshot/
[257]: https://github.com/TheJJ/ceph-cheatsheet
[258]: https://raft.github.io/
[259]: https://github.com/hashicorp/raft
[260]: https://github.com/dreamportdev/Osdev-Notes
[261]: https://mfontanini.github.io/presenterm/
[262]: https://github.com/yt-dlp/yt-dlp
[263]: https://sylvainhalle.github.io/textidote/
[264]: https://github.com/SinaKarvandi/Hypervisor-From-Scratch
[265]: https://github.com/mirror/vbox