# Customise ton terminal sous linux

![center](https://yt3.ggpht.com/ikEnzTf7Z7VDwidr1qoUiGVASFordTjPJi3WaPYR-aA4aC2m12yWakI8nIlROAKBk9ovtle-=w2560-fcrop64=1,00005a57ffffa5a8-k-c0xffffffff-no-nd-rj "Blacktr@ce")

> :fr: **Bonjour tout le monde,voici differents tuto pour customiser votre terminal sous linux , amusez vous** :wink: :fr:

## 1. Comment customiser l'en-tête de votre terminal avec `figlet`:

![center](https://i.ytimg.com/vi/yz6n8TJgvLk/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLD1Sc_i5v9XhlNKxmNMSJ7BpNVoyw "Comment customiser l'en-tête de votre terminal")

:movie_camera: [TUTO YOUTUBE](https://www.youtube.com/watch?v=yz6n8TJgvLk&t=54s) :movie_camera: 
 
**:one: Installe *figlet*:**
```
sudo apt-get install figlet
```
**:two: choisit une *police d'écriture*:**
```
showfigfonts "text"
```

**:three: Ouvre et entre cette commande dans *.bashrc*:**
```
code bashrc
```
- (in .bashrc)
```
figlet -f "your font" "text"
```
- (save .bashrc)

**:four: Ferme et ouvre un nouveau terminal**
* Ctrl+alt+t

> :arrow_right: [Donovan RINGOT](https://github.com/DRINGOT) :arrow_left:

## 2. Comment customiser l'ouverture de votre terminal avec `yakuake`:   

![center](https://i.ytimg.com/vi/NDeWaaZMj3s/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLCgDg3H_NWyXI0tOfMOFex-33b6gQ "Comment customiser l'ouverture de votre terminal")

:movie_camera: [TUTO YOUTUBE](https://www.youtube.com/watch?v=NDeWaaZMj3s) :movie_camera: 
 
**:one: Installe *yakuake*:**
```
sudo apt-get install yakuake
```

**:two: Ouvre l'application:**
:point_right: Albert :point_right: yakuake
     
**:three: *Customise*:**
:point_right: check settings     

**:four: Démarrage automatique de l'application**

1. Open Startup applications
2. Click on Add
3. Name: Yakuake
4. Command: yakuake
5. Comment: A drop-down terminal emulator 

> :arrow_right: [Donovan RINGOT](https://github.com/DRINGOT) :arrow_left:

## 3. Comment afficher la matrice dans votre terminal avec `cmatrix`:

![center](https://i.ytimg.com/vi/O0-0j1BD2qE/hqdefault.jpg?sqp=-oaymwEjCPYBEIoBSFryq4qpAxUIARUAAAAAGAElAADIQj0AgKJDeAE=&rs=AOn4CLAio-xObSQ959EF8ipBHM-I5Cw3gg "Comment afficher la matrice dans votre terminal")

:movie_camera: [TUTO YOUTUBE](https://youtu.be/O0-0j1BD2qE) :movie_camera: 

**:one: Installe *cmatrix*:**
```
sudo apt-get install cmatrix
```

**:two: Installe *cmatrix-font*:**
```
sudo apt-get install cmatrix-font
```
  
**:three: Utilise *cmatrix*:**
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
