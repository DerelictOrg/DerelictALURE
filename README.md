DerelictALURE
===========

A dynamic binding to version 1.2 of the [ALURE][1] (AL Utilities REtooled) library for the D Programming Language.

Please see the [Derelict documentation][2], for information on how to build DerelictGLFW3 and load GLFW3 at run time. In the meantime, here's some sample code.

```D
import derelict.alure.alure;

void main() {
    // Load the ALURE library.
    DerelictALURE.load();

    // Now ALURE functions can be called.
    ...
}
```

[1]: http://kcat.strangesoft.net/alure.html
[2]: https://derelictorg.github.io/
