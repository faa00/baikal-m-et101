# baikal-m-et101
Ядро и файлы конфигурации для материнской платы ET101-1.1 от "Элпитех".
Ядро собрано нативно, gcc 10.3.0 из состава дистрибутива Mageia-8.

    $ cat /etc/release 
    Mageia release 8 (Official) for aarch64
    $
    $ gcc -v
    Используются внутренние спецификации.
    COLLECT_GCC=gcc
    COLLECT_LTO_WRAPPER=/usr/lib/gcc/aarch64-mageia-linux-gnu/10/lto-wrapper
    Целевая архитектура: aarch64-mageia-linux-gnu
    Параметры конфигурации: ../configure --prefix=/usr --libexecdir=/usr/lib --with-slibdir=/lib64 --with-pkgversion='Mageia 10.3.0-2.mga8' --with-bugurl=https://bugs.mageia.org/ --mandir=/usr/share/man --infodir=/usr/share/info --enable-checking=release --enable-languages=c,c++,ada,fortran,objc,obj-c++,d --enable-linker-build-id --build=aarch64-mageia-linux-gnu --host=aarch64-mageia-linux-gnu --with-system-zlib --enable-threads=posix --with-linker-hash-style=gnu --enable-shared --enable-long-long --enable-__cxa_atexit --disable-libunwind-exceptions --enable-clocale=gnu --enable-ssp --disable-libssp --disable-quadmath --disable-libffi --disable-werror --with-isl --with-python-dir=/lib/python3.8/site-packages --enable-lto --with-gcc-major-version-only
    Модель многопоточности: posix
    Supported LTO compression algorithms: zlib zstd
    gcc версия 10.3.0 (Mageia 10.3.0-2.mga8)
    $


