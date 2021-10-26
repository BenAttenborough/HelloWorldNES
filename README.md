# NES Test

## About

Mucking about with NES emulation. See the [Famicom Party book](https://famicom.party/book/)

## Requirements

Assembler, for Mac I use `brew install cc65`
Emulator, I use [Nintaco](https://nintaco.com/)
Graphics, [NES Lightbox](https://famicom.party/neslightbox/)
Sound, [FamiStudio](https://famistudio.org/)

## Compilation

1. Create object file with `ca65 helloworld.asm`
2. Turn it into a NES executable with `ld65 helloworld.o -t nes -o helloworld.nes`