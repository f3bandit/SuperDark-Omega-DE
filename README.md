###### FORKED FROM https://github.com/ez-flash/omega-de-kernel

# SuperDark-DE for Ez-Flash Omega Definitive Edition

<img src="https://gbatemp.net/attachments/splash-jpg.447361" width="128"/>

# A fork of Simple-DE by Sterophonick
<img src="https://gbatemp.net/attachments/cart_boot_option-png.447362" width="128"/><img src="https://gbatemp.net/attachments/cheat_list-png.447363" width="128"/><img src="https://gbatemp.net/attachments/cheats_icon-png.447364" width="128"/>
<img src="https://gbatemp.net/attachments/game_list_title_image_off-png.447365" width="128"/><img src="https://gbatemp.net/attachments/game_list_title_image_on-png.447366" width="128"/><img src="https://gbatemp.net/attachments/gb_icon-png.447367" width="128"/>
<img src="https://gbatemp.net/attachments/gba_icon-png.447368" width="128"/><img src="https://gbatemp.net/attachments/gbc_icon-png.447369" width="128"/><img src="https://gbatemp.net/attachments/image_icon-png.447370" width="128"/>
<img src="https://gbatemp.net/attachments/nes_icon-png.447371" width="128"/><img src="https://gbatemp.net/attachments/nor-flash-png.447372" width="128"/><img src="https://gbatemp.net/attachments/plugin_icon-png.447373" width="128"/>
<img src="https://gbatemp.net/attachments/recent_list-png.447374" width="128"/><img src="https://gbatemp.net/attachments/save_icon_esv-png.447375" width="128"/><img src="https://gbatemp.net/attachments/save_icon_rts-png.447376" width="128"/>
<img src="https://gbatemp.net/attachments/settings_a-png.447377" width="128"/>
<img src="https://gbatemp.net/attachments/settings_b-png.447378" width="128"/>

If you are looking for Simple-Light for the Ez-Flash Omega and the Omega Definitive Edition
Official forum thread for Simple-Light and Simple-DE:
https://gbatemp.net/threads/new-theme-for-ez-flash-omega.520665/

<img src="https://gbatemp.net/attachments/457315-1-png.459658" width="128"/>


Sterophonick Github

Omega 
https://github.com/Sterophonick/SimpleLight

Omega-DE
https://github.com/Sterophonick/omega-de-kernel

<img src="https://gbatemp.net/attachments/14646-1-png.459659" width="128"/>

Ez-Flash official downloads

https://www.ezflash.cn/download/

Ez-Flash Github

Omega
https://github.com/ez-flash/omega-kernel

Omega-DE
https://github.com/ez-flash/omega-de-kernel




## Installation instructions:


_**YOU MUST USE THE OFFICIAL KERNEL TO UPDATE THE FIRMWARE :(**_

1. Copy the SYSTEM and BACKUP folder to the root of the SD Card.
2. Move your IMGS, SAVER, RTS, and PATCH folders to SYSTEM.
3. If you want the light theme, copy ezkernel-light.bin to the root of the SD Card. If you want the dark thing, do the same with ezkernel-dark.bin
4. Rename the new kernel file to ezkernel.bin
5. You're done!

## Registered file types:
### Game ROMs
    .gba - GBA ROM
    .bin - GBA ROM
    .mb - GBA Multiboot ROM
    .agb - GBA ROM
    .col - ColecoVision ROM (Requires Cologne) *
    .gb - Game Boy ROM (Jaga's Goomba Color)
    .gbc - Game Boy Color ROM (Jaga's Goomba Color)
    .gg - Game Gear ROM (SMSAdvance)
    .rom - MSX Cartridge ROM (MSXAdvance) **
    .ngp - Neo Geo Pocket ROM (NGPAdvance)
    .ngc - Neo Geo Pocket ROM (NGPAdvance)
    .ngpc - Neo Geo Pocket Color ROM (NGPAdvance)
    .nes  - NES ROM File (PocketNES)
    .pce - PC-Engine ROM File (PCEAdvance)
    .sms - Sega Master System ROM File (SMSAdvance)
    .sg - Sega SG-1000 ROM File (SMSAdvance)
    .sv - Watara Supervision ROM File (Wasabi)
    .ws - WonderSwan ROM File (SwanAdvance)
    .wsc - WonderSwan Color ROM File (SwanAdvance)
    .z80 - 48k ZX-Spectrum Z80 ROM (ZXAdvance)
    .c8 - Chip-8 ROM (Chip8Adv (My First Emulator! :D))
    .arc - 4kb Emerson Arcadia 2001 ROM File

### Media
    .jpg - JPEG Image
    .jpeg - JPEG Image
    .mod - ProTracker Module file
    .bmp - Bitmap Image
    .pcx - ZSoft Paintbrush PCX image
    .mid - MIDI sequence
    .nsf - NES Music file (Nintendo Sound File)
    .vgm - SMS/GG music file
    .vga - aPlib Compressed SMS/GG music file
    .vgl - LZ77 Compressed SMS/GG music file
    .txt - Text Document
    .wav - Wave Sound (formatted in GSM 6.10)
    .k3m - Krawall Advance Sound
    .sb - MaxMod sound bank
    .lz - LZ77 Compressed Image
    .raw - Uncompressed Mode 3 Bitmap
    .ap - aPlib compressed Mode 3 Bitmap
    .bgf - BoyScout module
    .mda - Sharp X68000 Music
    .cwz - CWZ Music (IDK what exactly it is, but it was included with PogoShell 1.2)

*\* For Cologne, you have to make the ROM yourself.*\
*\*\* MSXAdvance uses the C-BIOS, so I can redistribute the emulator.*

##### Cologne Emulator Guide:
1. Download the latest version of Cologne.
2. Open the EXE file.
3. Take a blank file, and also add the Official Colecovision BIOS.
4. Create col.gba in the PLUG folder.

### This ZIP file contains some tech demos/games:
* XBill (SG-1000)
* Sega Tween (SMS)
* WinGG (Game Gear)
* HuZERO (PC-Engine)
* 1968 (ZX-Spectrum)
* Adventures Of Gus and Rob (Neo Geo Pocket)
* Kaboom! (Homebrew) (ColecoVision)
* Motkonque (MSX)
* SwanDriving (WonderSwan)
* F8Z (Chip-8)

### How to build 
1. Install [devkitPro](https://devkitpro.org/)
2. Set the following environment variables to their correct directories: `DEVKITPRO, DEVKITARM, LIBGBA`
3. Comment or uncomment the `#define DARK` line in `draw.h`. If uncommented, a dark theme is generated.
4. Run the command `make`. If done successfully, this should give you an `ezkernel.bin` file.
5. Follow the installation instructions above.
4. Update your flashcart and enjoy! :)

### Special Greetz & Contributors:
Sasq\
Moonlight\
Kuwanger\
veikkos\
DarkFader\
CoolHJ\
Let's Emu!\
Izder456\
NuVanDibe\
SLKun\
Mintmoon\
hitsgamer\
Rocky5

### Credits
[EZ-FLASH](https://www.ezflash.cn/) - The original firmware & hardware creators\
Kuwanger - PogoShell plugin integration\
Sterophonick - SIMPLE theme for EZO & EZODE\
fluBBa - SMSAdvance, MSXAdvance, Cologne for GBA, Goomba for GBA (Original), PCEAdvance, PocketNES, SNESAdvance, Wasabi, NGPAdvance, SwanAdvance\
[Jaga](https://github.com/EvilJagaGenius) - [Jaga's Goomba Color fork](https://github.com/EvilJagaGenius/jagoombacolor)\
...and others!
