# gdx-compression
LibGDX compression classes extract into a standalone library (i.e. no OpenGL, LWJGL, etc. required)

Mechanism
----------------------

The gradle build will checkout a specific version of libgdx, copy the compression source files into src/main/java, package renamed from _com.badlogic.gdx.utils.compression_ to _org.mini2Dx.gdx.compression_ and compile the standalone jar.

Usage
----------------------

```gradle
compile "org.mini2Dx:gdx-compression:1.9.13"
```

This project's only dependency is [gdx-collections](https://github.com/mini2Dx/gdx-collections).

Included Classes
----------------------

The entire _com.badlogic.gdx.utils.compression_ package is included along with _Base64Coder_
