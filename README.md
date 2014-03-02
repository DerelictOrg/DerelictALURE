DerelictALURE
===========

A dynamic binding to version 1.2 of the [ALURE][1] (AL Utilities REtooled) library for the D Programming Language.

For information on how to build DerelictALURE and link it with your programs, please see the post [Building and Using Packages in DerelictOrg][2] at the Derelict forums.

For information on how to load the ODE library via DerelictDE see the page [DerelictUtil for Users][3] at the DerelictUtil Wiki. In the meantime, here's some sample code.

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
[2]: http://dblog.aldacron.net/forum/index.php?topic=841.0
[3]: https://github.com/DerelictOrg/DerelictUtil/wiki/DerelictUtil-for-Users
