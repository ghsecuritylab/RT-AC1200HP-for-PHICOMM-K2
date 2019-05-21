# RT-AC1200HP_3.0.0.4.380.8457-for-PHICOMM-K2

Set Up Environment (I used Deepin 15.10.1)
  1. Install packages
  
    sudo apt install cmake libncurses5 libncurses5-dev m4 bison gawk flex libstdc++6 g++ gengetopt git gitk zlib1g-dev autoconf autopoint libtool shtool autogen mtd-utils intltool sharutils docbook-xsl-* libstdc++5 texinfo dos2unix xsltproc u-boot-tools device-tree-compiler libc6-i386 lib32stdc++6 lib32z1

  2. setup development system
  
    	To install the tools:

	    	- copy the tools/brcm/ directory to /opt

		    - add /opt/brcm/hndtools-mipsel-linux/bin to your path

		    - add /opt/brcm/hndtools-mipsel-uclibc/bin to your path

	    	- copy tools/buildroot-gcc342 directory to /opt

		    - add /opt/buildroot-gcc342/bin to your path
		    
  3.  build firmware.
  
  	cd release/src-ra-mt7620

	make rt-ac1200hp
