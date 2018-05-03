# arm-mac-linux-uclibcgnueabihf
**GCC Version**: 6.3.0  
**GDB Version**: 7.12.1
**libc**: uClibc 0.9.33.2  
**Build**: MacBook Pro late 2016 with macOS 10.13.4  
**Host**: macOS 10.13+  
**Target**: arm926ej-s(arm9/arm11)  
**Language**: c/c++ 

## GCC Configure
`/Volumes/buildcc/.build/src/gcc-6.3.0/configure --build=x86_64-build_apple-darwin17.5.0 --host=x86_64-build_apple-darwin17.5.0 --target=arm-mac-linux-uclibcgnueabi --prefix=/Volumes/buildcc/x-tools/arm-mac-linux-uclibcgnueabi --with-sysroot=/Volumes/buildcc/x-tools/arm-mac-linux-uclibcgnueabi/arm-mac-linux-uclibcgnueabi/sysroot --enable-languages=c,c++ --with-cpu=arm926ej-s --with-float=soft --with-pkgversion='crosstool-NG crosstool-ng-1.23.0' --enable-__cxa_atexit --disable-libmudflap --disable-libgomp --disable-libssp --disable-libquadmath --disable-libquadmath-support --disable-libsanitizer --disable-libmpx --with-gmp=/Volumes/buildcc/.build/arm-mac-linux-uclibcgnueabi/buildtools --with-mpfr=/Volumes/buildcc/.build/arm-mac-linux-uclibcgnueabi/buildtools --with-mpc=/Volumes/buildcc/.build/arm-mac-linux-uclibcgnueabi/buildtools --with-isl=/Volumes/buildcc/.build/arm-mac-linux-uclibcgnueabi/buildtools --enable-lto --enable-threads=posix --enable-target-optspace --enable-plugin --enable-gold --with-libintl-prefix=/Volumes/buildcc/.build/arm-mac-linux-uclibcgnueabi/buildtools --disable-multilib --with-local-prefix=/Volumes/buildcc/x-tools/arm-mac-linux-uclibcgnueabi/arm-mac-linux-uclibcgnueabi/sysroot --enable-long-long`
