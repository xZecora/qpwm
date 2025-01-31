# qpwm - quite powerful window manager for X <img src="https://github.com/0xMrNight/0xMrNight/blob/main/assets/wave.gif?raw=true" width="28px">
### 👉 it's small floating window manager from not a programmer 👍
## some features 💪
- Floating only.
- Fullscreen toggle.
- Window centering.
- Mix of mouse and keyboard workflow.
- Focus with cursor.
## Dependencies 🧑‍💻
- only `xlib` (*usually `libX11`*).
## Installation 🕵️‍♂️
```fish
sudo make clean install
```
# How to configure? :tipping_hand_person:
```bash
make
```
### next, open config.h file in your text editor. And configure! :zap:

# :rocket: Running qpwm :rocket:
### add to `.xinitrc`
```bash
exec qpwm
```
If you use GDM, SDDM, LightDM оr anything other display manager 👤

Add it in /usr/share/xsessions/qpwm.desktop 
```
[Desktop Entry]
Name=qpwm
Comment=This session runs qpwm as window manager 
Exec=qpwm
Type=Application
```
## Default Keybindings :space_invader:
**Window Management**
| combo                      | action                 |
| -------------------------- | -----------------------|
| `Mouse`                    | focus under cursor     |
| `win` + `Left Mouse`       | move window            |
| `win` + `Right Mouse`      | resize window          |
| `win` + `f`                | maximize toggle        |
| `win` + `c`                | center window          |
| `win` + `q`                | kill window            |
| `win` + `1-6`              | desktop swap           |
| `win` + `Shift` +`1-6`     | send window to desktop |
| `win` + `return` (*enter*) | open terminal (st)     |
| `ALT` + `TAB`.             | focus cycle            |
# :fire: Screenshots of qpwm :fire:
![qpwm1](https://cdn.discordapp.com/attachments/955362477137362954/957063386154295346/2022-03-26_02-12.png?raw=true)
![qpwm2](https://cdn.discordapp.com/attachments/955362477137362954/957119114235764746/2022-03-26_06-20.png?raw=true)
![qpwm3](https://cdn.discordapp.com/attachments/955362477137362954/955533886132215878/2022-03-21_21-30.png?raw=true)
![qpwm4](https://cdn.discordapp.com/attachments/955362477137362954/955543502110990476/2022-03-21_22-08_1.png?raw=true)
![qpwm5](https://cdn.discordapp.com/attachments/955362477137362954/955544733470580776/2022-03-21_22-13.png?raw=true)
![qpwm6](https://media.discordapp.net/attachments/955362477137362954/955362504656187392/5CqwsnNUOos.jpg?raw=true)
## Thanks for code :speech_balloon:
- [tinywm](http://incise.org/tinywm.html)
- [dwm](https://dwm.suckless.org)
- [2bwm](https://github.com/venam/2bwm)
- [sowm](https://github.com/dylanaraps/sowm)
