## History of AwlsomeLinux
Welcome to AwlsomeLinux, a small embedded Linux Distribution that you can "Mostly" build yourself. This project started with my interest on how the Linux Kernel works, and how Tiny Core Linux worked, so I decided "Why not just build it?" Well, this was last year, and the [Minimal Linux Live Project](https://github.com/ivandavidov/minimal), the project AwlsomeLinux is forked on, was barely off its feet and my goal of a Linux Distribution was further than ever. However recently Ivandavidov put alot of work to the project, and I decided to fork it. AwlsomeLinux wasn't the first thing I had in mind however, the main reason I forked it was due to the project becoming too complex, so I merely simplified it. However I then got the idea "Why not add to it as well." I then implemented Nano and Ncurses, not too difficult, but wasn't 'entirely' accepted. Due to this, I then decided that I would start my own project, thus AwlsomeLinux (AwlsomeAlex Linux). Once this decision was made, I then simplified the scripts even more, to the point where the whole project was three scripts, one folder and one makefile, and after weeks of rewritting, I finally considered myself my own Linux Distribution. For here on out my main goals will be to add more packages, make AwlsomeLinux installable, make AwlsomeLinux self-hosted, and make AwlsomeLinux a GUI/TUI Interface.

## What is AwlsomeLinux?
Right now, AwlsomeLinux is a minimal, almost installable, and text-based Linux Environment which has the following features:
* The Latest Linux Kernel (4.9.x)
* The Latest Stable BusyBox (1.26.2 Stable)
* The Latest Glibc (2.25)
* OverlayFS Support (Read-Only for ISO / Read-Write for USB)

## Dependencies:
* build-essential, wget, make, gawk, gcc, bc, syslinux, genisoimage, texinfo (Ubuntu-Based Distributions)
* (More Distribution Support Coming Soon!)

## How to Build:
* 'make all' - Completely Compiles AwlsomeLinux, simple as that!
