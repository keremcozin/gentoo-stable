My local GitHub/Rsync repository to backup my important Gentoo GNU/Linux configuration files.

I'm on **amd64 stable** branch.
I use following overlays out of the main Gentoo sync tree;

* Miezhiko
* waffle-builds
* guru
* steam-overlay 

My motto is **"Keep it simple!"** :-)

My public Key ID to share with world: **84B2770AF478A795** (rsa4096)

![Screenshot of terminal](https://github.com/keremcozin/gentoo-stable/blob/main/screenshot.png)

If you intend to use the binary packages I've created by **quickpkg** these are my native host and compiler options here ${CFLAGS} && ${CXXFLAGS};

* -march=nehalem --param=l1-cache-line-size=64 --param=l1-cache-size=32 --param=l2-cache-size=8192
* -O2 -pipe -fomit-frame-pointer

* CPU_FLAGS_X86: mmx mmxext popcnt sse sse2 sse3 sse4_1 sse4_2 ssse3

For binary packages, **USE AT YOUR RISK** 
