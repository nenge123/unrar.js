# unrar.js
unrar.js is a port of GNA UnRAR by compiling the C code with Emscripten.

See [demo](http://seikichi.github.io/unrar.js/).

```
        unrar = new Unrar(Uint8ArrayBuf);
        unrar.list.forEach(
          v=>{
            let fileBuf = unrar.decompress(v.name);
          }
          );

```
