## Building

1. Install [Docker](https://hub.docker.com/search/?type=edition&offering=community) and [Python 3.7](https://www.python.org/downloads/). ([WSL](https://nickjanetakis.com/blog/setting-up-docker-for-windows-and-wsl-to-work-flawlessly) or Linux VM needed for Windows)

2. Clone this repo and all submodules recursively.

       git clone https://github.com/designgears/nx-sd.git --recurse-submodules

3. Run `python3 build.py`.

### Building optional components

The name of each componenet corresponds with its filename in `/nxsd/components`. A successful build will output to the `/build` directory under the same name.

       python3 build.py -c noexes

## Components

### Core components

| Component                                                 | Description |
| --------------------------------------------------------- | ----------- |
| [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere) | Custom firmware for the Nintendo Switch |
| [Hekate](https://github.com/CTCaer/hekate)                | Nintendo Switch Bootloader - CTCaer mod |
| [Incognito_RCM](https://github.com/jimzrt/Incognito_RCM)  | Wipes personal infor from Switch via RCM payload |
| [Lockpick_RCM](https://github.com/shchmue/Lockpick_RCM)   | Encryption key derivation bare metal RCM payload |
| [nx-hbloader](https://github.com/switchbrew/nx-hbloader)  | Host process for loading homebrew NROs |
| [nx-hbmenu](https://github.com/switchbrew/nx-hbmenu)      | The Nintendo Switch homebrew menu |
| [Toolbox](https://github.com/designgears/Kosmos-Toolbox)  | A toolbox for the Kosmos CFW package |

### Addons

| Component                                                 | Description |
| --------------------------------------------------------- | ----------- |
| [EdiZon](https://github.com/WerWolv/EdiZon)               | Save manager, editing tool, and memory trainer |
| [ldn_mitm](https://github.com/spacemeowx2/ldn_mitm)       | Play local wireless supported games online |
| [NX-Shell](https://github.com/joel16/NX-Shell)            | 3DShell port for the Switch |
| [nxdumptool](https://github.com/DarkMatterCore/nxdumptool)| Generates dumps from Switch gamecards and installed SD/eMMC titles |
| [sys-CLK](https://github.com/retronx-team/sys-clk)        | Overclocking/underclocking system module |
| [sys-clk-Editor](https://github.com/SunTheCourier/sys-clk-Editor) | Editor for your sys-clk configuration |
| [sys-ftpd](https://github.com/designgears/sys-ftpd)       | Ftpd as a Switch sysmodule |

### Optional

| Component                                                 | Description |
| --------------------------------------------------------- | ----------- |
| [AmiiSwap](https://github.com/FuryBaguette/AmiiSwap)      | Switch GUI Amiibo Manager homebrew for emulation with Emuiibo |
| [Checkpoint](https://github.com/FlagBrew/Checkpoint)      | Fast and simple homebrew save manager for 3DS and Switch |
| [emuiibo](https://github.com/XorTroll/emuiibo)            | MitM'ing NFP services for Amiibo emulation! |
| [Goldleaf](https://github.com/XorTroll/Goldleaf)          | Switch multipurpose homebrew tool |
| [incognito](https://github.com/blawar/incognito)          | Wipes personal information from your Nintendo Switch |
| [Noexes](https://github.com/KranKRival/Noexes)            | graphical remote debugger for the Switch |
