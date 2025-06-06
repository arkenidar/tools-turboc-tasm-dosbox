# turboc-tasm-linux
TurboC++ and TASM ( Turbo Assembler ) for Ubuntu Linux (or other by DosBox)

- <https://github.com/arkenidar/tools-turboc-tasm-dosbox>
- <https://github.com/arkenidar/tools-turboc-tasm-dosbox/blob/master/TURBOC-TASM.zip> 

## for Debian and Ubuntu (other similar e.g. Windows)
```sh
sudo apt-get install dosbox
```
<https://github.com/arkenidar/tools-turboc-tasm-dosbox/blob/master/TURBOC-TASM.zip> Click on Download
```sh
# or download this way
wget https://github.com/arkenidar/tools-turboc-tasm-dosbox/blob/master/TURBOC-TASM.zip
# or also
git clone https://github.com/arkenidar/tools-turboc-tasm-dosbox
```

Open Terminal and Type
```sh
$ cd ~
$ cp ~/Downloads/TURBOC-TASM.zip ~
$ unzip TURBOC-TASM.zip
$ dosbox
```

```sh
dosbox > mount C ~
dosbox > C:
dosbox > cd setup
dosbox > install.exe
```

### Change Source Drive to 'C'
### Start Installation

```sh
dosbox> config -writeconf /home/your-pc-username/dosbox.conf
```

Quit

open dosbox.conf which is in your home directory and type this in under [autoexec]
```sh
mount c ~
C:
```

Now try to open dosbox, you will see C: prompt (C drive mounted) instead of Z:

To Run Turbo C++ type
```sh
dosbox > cd ..
dosbox > cd tc/bin/
dosbox > tc.exe
```


