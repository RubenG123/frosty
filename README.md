# GameBoy Emulator written in Rust

Still a work in progress but 32KB roms should mostly work (e.g. Tetris) and MBC1 cartridges that dont have ram dimms in it

![image](https://user-images.githubusercontent.com/16002713/117520192-ebc23900-af9e-11eb-94b0-c4e67b1e6ac6.png)

## Tests
All Blargg cpu_instrs tests passing, as well as the dmg-acid2 ppu test!

![image](https://user-images.githubusercontent.com/16002713/117557463-0235c680-b06b-11eb-969c-40ea69976beb.png)
![image](https://user-images.githubusercontent.com/16002713/117734032-83679780-b1ea-11eb-868f-7b937e2e6cd8.png)


## TODO:
- Implement Sound? Not sure how hard it is
- Implement all cartridge types
- [Bonus] Pass all mooneye tests? A lot already pass
- [Bonus] Implement FIFO pipeline for the ppu so mid scanline stuff works?

## References Used
- https://github.com/AntonioND/giibiiadvance/blob/master/docs/TCAGBD.pdf
- https://gb-archive.github.io/salvage/decoding_gbz80_opcodes/Decoding%20Gamboy%20Z80%20Opcodes.html
- https://izik1.github.io/gbops/
- http://marc.rawer.de/Gameboy/Docs/GBCPUman.pdf
- http://imrannazar.com/GameBoy-Emulation-in-JavaScript:-The-CPU
- https://gbdev.io/pandocs/
- https://robertovaccari.com/blog/2020_09_26_gameboy/
- http://www.devrs.com/gb/files/faqs.html
- The kind people of the EmuDev discord
