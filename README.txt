HELP.R4X
========

HELP.R4X ist die Terminal-Hilfe fuer interne Befehle und installierte
Terminal-Software.

Projektstruktur seit 0.51.18:
- `build.zig` baut die App als eigenes SDK-Projekt.
- `build.zig.zon` bindet `r4os_sdk` als Paket.
- `module.R4MF` beschreibt Artefakt, Zielpfad und Contract.

Build:

    cd Code\System\Software\Help
    ..\..\..\DevTools\Zig\zig.exe build

Ergebnis:

    Code\System\Software\Help\zig-out\HELP.R4X

Contract:
- R4XStart-Entry: `help_main`
- App-Klasse: `console`
- Zielpfad im Image: `C:\R4OS\SOFTWARE\TERMINAL\HELP.R4X`

