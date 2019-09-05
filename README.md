# LKJ
Hey! This is a back-up for the first stage of the LKJ cross compiler. If your name is Jay, download, please please please make sure ownership is set properly, then get the chroot started and finish setup.

# For people who aren't me

Hiya! LKJ is a custom Linux distribution I run on my desktop. Built from the linux kernel (4.20) up, LKJ is tightly integrated with the plan9port userspace (rio window system included), so as to use the fantastic 9P IPC and userland utilities throughout the OS while still offering the ability to run classic UNIX applications. It's like "wearing the hairshirt" while still having the ability to fall back on modern browsers, etc.

At my residence hall, LKJ is being implemented to run floor-wide music servers, LED controllers, etc. due to its unique flexibility and prowess at cross-network communication. While it's primitive in some aspects(lkj-make is a simple shell script written from within the OS that literally just tries to pull from git unless you tell it otherwise), I continue to iterate and plan on releasing an ISO by the end of the year.

There isn't much to see here, because this effectively is a x86_64 specific pre-configuration for a blank-slate linux install. Stay tuned for the finished distro, and find the tar'd backup:
web.mit.edu/jaytlang/Public/lkj-tools.tar
