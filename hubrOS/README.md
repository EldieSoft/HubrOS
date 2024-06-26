This is the README for my new project, Hubris Operating System (HubrOS).

Now, I know what you may be asking, why did I decide to do this. The answer will surprise you, also it will surprise me, because I have no idea why I decided to torture myself by doing this. 

Essentially, I just want to see if I can do it. The answer is probably no, but it is something I want to try. x86_64 Assembly has always facinated me, and I really want to do somethingwith it, even if it is just writing a pretty basic BIOS and bootloader. Also, I'm always ready to learn some more C, which is my favorite language. I haven't even started writing any code yet. Like, this is the first file in the directory. I haven't even christened this project with a "Hello, world!" yet.  This is all a part of the hubris that the OS depends on.

How to run: (NOTE: hubrOS is being made in Linux using qemu VM. Compilation instructions refer to qemu)

While in hubrOS dir, type this command in the handy, dandy terminal:

make && qemu-system-i386 -fda build/main_floppy.img

this command runs the makefile, then runs qemu emulator.

 
