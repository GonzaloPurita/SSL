El compilador usado es gcc.exe (Rev6, Built by MSYS2 project) 13.2.0

Los argumentos del tasks.json son:

"-fdiagnostics-color=always",
                "-g",
                "-Wall",
                "-std=c2x",
                "-pedantic-errors",
                "${file}",
                "-o",
                "${fileDirname}\${fileBasenameNoExtension}.exe"
