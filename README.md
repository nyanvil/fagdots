# fagdots

**Aiming 4 Perfection**

---

slightly opinionated, however it should be painless for anyone

#### NOTE: *gtk theming is kinda fucked* at least for me, maybe it works on arch or other rolling distroes?

tested only on debian trixie

should work, *and maybe will work better* on other distroes

current problems: gtk theme (at least on debian trixie) & no brightness osd shows up but i kinda dgaf abt it & occassionally on theme/wallpaper change, gtk accidentally goes light instead of dark (might be a noctalia isssue? idfk)

# dependencies:

```
gayland
sway
noctalia
polkit-kde-authentication-agent
```

& optional, but are also modded by these dots

```
kitty
discord (patched with equicord)
vscodium
telegram-desktop (doesnt apply for me? maybe bc my client is too old (debian stable moment)
& prolly more cuz i selected alot in templates but didnt check everything
```

# now onto the keybinds

in the sway config **the default mod key is super**
however if u wanna replace it, **just change the set**
u can also change your **prefered terminal** this way

control center - mod+a
kill focused window - mod+q
toggle tabbed/split - mod+shift+w
fullscreen - mod+f
change focused window - mod+arrows or hover over it with mouse
cycle workspaces - mod+(1 through 9)
cycle tabbed windows - mod+(left/right arrow)
move focused window to another workspace - mod+shift+(left/right arrow)
noctalia settings - mod+comma
open terminal (kitty by default) - mod+enter
reload sway config - mod+shift+c

