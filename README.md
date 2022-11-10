# ScratchTools

ScratchTools - a set of simple [Scratch](https://en.wikipedia.org/wiki/Scratch_(programming_language)) related, but mostly unrelated to each other tools.

Many tools from this respository are availible through github-pages.

---

## Description

#### [Img2list](https://xeltalliv.github.io/ScratchTools/Img2list/)

A tool for converting images to lists of numbers in a variaty of ways.


#### [List2img](https://xeltalliv.github.io/ScratchTools/List2img/)

A tool for converting lists of numbers to images.


#### [ProjectJsonMinimizer](https://xeltalliv.github.io/ScratchTools/ProjectJsonMinimizer/)

Scratch project file format `.sb3` is actually a zip archive with all of the assets and 1 json file.
That json file has a limit of 5 MiB, and scratch by default wastes a lot of space in it.
This program reduces the size of this json file in a way that can't cause any issues and that remains
persistent even after being loaded and resaved in scratch.


#### [STT-Visualizer](https://xeltalliv.github.io/ScratchTools/STT_Visualizer/)

A tool that allows to convert cloud log of [this](https://scratch.mit.edu/projects/555383076/) project to a human readable format.


#### [SimilarSB3Storage](https://github.com/Xeltalliv/ScratchTools/tree/main/SimilarSB3Storage)

2 simple scripts written in bash that allow storing many versions of the same scratch project in a
space efficient way without storing the same assets multiple times.

```
./compress
```
to disassemble all `.sb3` files in the folder to this space efficient representation.

``` 
./decompress <project name without file extension>
```
to reassemble project back into `.sb3`. File creation dates are preserved.


#### [WadToScratchImporter](https://xeltalliv.github.io/ScratchTools/WadToScratchImporter/)

A tool for automatically importing `.wad` files of [idTech1](https://en.wikipedia.org/wiki/Doom_engine) based games to Vadik1's recreation of this engine in scratch.


#### [Vadik's scratch programming language](https://xeltalliv.github.io/ScratchTools/ProgLang/)

A compiler for a custom programming language `.vspl` that compiles into scratch 3 projects.
It contains some very useful zero cost abstractions that make creation of advanced projects easier.

---

## License

All files in the repository with the exception of `/vendor` folder are licensed under GNU General Public License v3.0.

Files inside `/vendor` folder have their own license files included along with them.

## Credits

Also thanks to [GarboMuffin](https://github.com/GarboMuffin) for providing [trampoling.turbowarp.org](https://trampoling.turbowarp.org/) proxy used in some of the tools.