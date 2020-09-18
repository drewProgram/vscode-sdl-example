## Reference
[Click here](<https://programmer.help/blogs/vscode-sdl2-configuration-tutorial.html>)

## Steps
### Installing MSYS2
- Download and install [MSYS2](/https://www.msys2.org/) and follow the wiki configuration steps
### Install Mingw64
- Install mingw 64 bit gcc compiler through msys with `pacman -S mingw64/mingw-w64-x86_64-gcc`
- Install mingw64 make `pacman -S mingw64/mingw-w64-x86_64-make`
- Go to the msys installation folder (usually C:/msys64) and go to mingw64/bin. Copy this folder address (Mine is C:\msys64\mingw64\bin) and put it as a System $PATH variable.
### Installing SDL
- Download [SDL 2 lib](/https://www.libsdl.org/download-2.0.php) (At the Development Libraries, the second Windows file)
- Follow the first link reference
