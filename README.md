# XCI Explorer

[Original Release](https://www.maxconsole.com/threads/exclusive-xci-explorer-released-for-switch-game-cartridge-backups.47046/)

View contents of XCI files and more!

## Features
* View metadata
* Explore partitions
* Check NCA hashes
* Extract NCA
* Modify cert

## Requirements
* Visual Studio 2017
* [Hactool](https://github.com/SciresM/hactool/releases) ([optional](https://github.com/StudentBlake/XCI-Explorer/releases/download/v1.0.0.0/hactool.zip))
* [Dumped keys](https://gbatemp.net/threads/how-to-get-switch-keys-for-hactool-xci-decrypting.506978/) ([optional](https://github.com/StudentBlake/XCI-Explorer/releases/download/v1.0.0.0/hactool.zip))

Main Tab Metadata/Cert/Trimming | Partitions Tab NCA Extract/Hash Check
:-------------------------:|:-------------------------:
![main](https://imgur.com/NdYOcgW.jpg) | ![partitions](https://imgur.com/ehPoPWB.jpg)

## Build Instructions
* Open `XCI Explorer.sln`
* Build -> Build Solution
* Add hactool.exe + dependencies + keys.txt to `XCI-Explorer/bin/Debug/` folder
* Run `XCI-Explorer.exe`

## Special Thanks
Addition of CARD2 and hash support provided by klks

## Disclaimer
This is not my original work. I just decompiled the rogue executable floating around and made minor changes. 

I am NOT a developer and this has NOT been extensively tested!