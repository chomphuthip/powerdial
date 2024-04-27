# PowerDial
Powershell reverse shell over RTP

Powered by [Tremont](https://github.com/chomphuthip/tremont).

If you didn't want a [full C2](https://github.com/chomphuthip/bleeddial), PowerDial simply drops you into a Powershell session.

## Building
To compile, include `tremont.h` and put `tremont.cpp` in the same directory. Statically linked implant is ~44kb.

If using Visual Studio, set to `Release` to stop the implant from opening up windows.
