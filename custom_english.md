# Custom your terminal on ubuntu linux

![center](https://yt3.ggpht.com/ikEnzTf7Z7VDwidr1qoUiGVASFordTjPJi3WaPYR-aA4aC2m12yWakI8nIlROAKBk9ovtle-=w2560-fcrop64=1,00005a57ffffa5a8-k-c0xffffffff-no-nd-rj "Blacktr@ce")

> :uk: **Hello everyone, here is different tutorial to customize your terminal on linux, have fun** :wink: :uk:

## 1. How to custom Terminal Welcome using Figlet:

![center](https://i.ytimg.com/vi/yz6n8TJgvLk/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLD1Sc_i5v9XhlNKxmNMSJ7BpNVoyw "How to custom Terminal Welcome")

:movie_camera: [TUTO YOUTUBE](https://www.youtube.com/watch?v=yz6n8TJgvLk&t=54s) :movie_camera: 
 
**:one: Install *figlet*:**
```
sudo apt-get install figlet
```
**:two: choose a *font*:**
```
showfigfonts "text"
```

**:three: Open and add command in *.bashrc*:**
```
code bashrc
```
- (in .bashrc)
```
figlet -f "your font" "text"
```
- (save .bashrc)

**:four: Open new terminal**
* Ctrl+alt+t

> :arrow_right: [Donovan RINGOT](https://github.com/DRINGOT) :arrow_left:

## 2. How to custom Terminal Opening using Yakuake:   

![center](https://i.ytimg.com/vi/NDeWaaZMj3s/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLCgDg3H_NWyXI0tOfMOFex-33b6gQ "How to custom Terminal Opening")

:movie_camera: [TUTO YOUTUBE](https://www.youtube.com/watch?v=NDeWaaZMj3s) :movie_camera: 
 
**:one: Install *yakuake*:**
```
sudo apt-get install yakuake
```

**:two: Open:**
:point_right: Albert :point_right: yakuake
     
**:three: Enjoy *Custom*:**
:point_right: check settings     

**:four: Autostart**

1. Open Startup applications
2. Click on Add
3. Name: Yakuake
4. Command: yakuake
5. Comment: A drop-down terminal emulator 

> :arrow_right: [Donovan RINGOT](https://github.com/DRINGOT) :arrow_left:

## 3. How to display the Matrix in your terminal:

![center](https://i.ytimg.com/vi/O0-0j1BD2qE/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAio-xObSQ959EF8ipBHM-I5Cw3gg "How to display the Matrix in your terminal")

:movie_camera: [TUTO YOUTUBE](https://youtu.be/O0-0j1BD2qE) :movie_camera: 

**:one: Install *cmatrix*:**
```
sudo apt-get install cmatrix
```

**:two: Install *cmatrix-font*:**
```
sudo apt-get install cmatrix-font
```
  
**:three: Use cmatrix**
* Start: `cmatrix`
* Stop: Ctrl+c
      
**:four: Mode:**
```
 -a: Asynchronous scroll
 -b: Bold characters on
 -B: All bold characters (overrides -b)
 -f: Force the linux $TERM type to be on
 -l: Linux mode (uses matrix console font)
 -L: Lock mode (can be closed from another terminal)
 -o: Use old-style scrolling
 -h: Print usage and exit
 -n: No bold characters (overrides -b and -B, default)
 -s: "Screensaver" mode, exits on first keystroke
 -x: X window mode, use if your xterm is using mtx.pcf
 -V: Print version information and exit
 -u delay (0 - 10, default 4): Screen update delay
 -C [color]: Use this color for matrix (default green)
    choose: green/red/blue/white/yellow/cyan/magenta
 -r: rainbow mode
```

> :arrow_right: [Donovan RINGOT](https://github.com/DRINGOT) :arrow_left:
