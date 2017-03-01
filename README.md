CascLib
=======

An open-source implementation of library for reading CASC storage from Blizzard games since 2014


###Commands for Emscripten compilation
```
emcmake cmake -DWITH_LIBTOMCRYPT=OFF
emmake make
emcc -s USE_ZLIB=1 -I. libcasc.so -o libcasc.js
```
