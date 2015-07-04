Vx32 is a user-mode library that can be linked into arbitrary applications that wish to create secure, isolated execution environments in which to run untrusted extensions or plug-ins implemented as native x86 code. Vx32 is similar in purpose to the Java or .NET virtual machines, but it runs native x86 code, so plug-ins can be written in ANY language, not just Java or C#.

Vx32 runs on unmodified x86 FreeBSD, Linux, and Mac OS X systems without special permissions, privileges, or kernel modules. It also runs on x86-64 Linux systems. Ports to x86-64 FreeBSD and Mac OS X should not be difficult. A port to Windows XP should also be possible.

Documentation
The USENIX 2008 paper “[Vx32: Lightweight, User-level Sandboxing on the x86](http://pdos.csail.mit.edu/papers/vx32:usenix08-abs.html)” explains how vx32 works and gives performance results for running various programs under vx32. Some programs even execute faster under vx32 than they do natively!