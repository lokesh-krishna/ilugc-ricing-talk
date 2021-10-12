---

author: Lokesh Krishna
styles:
    author:
        fg: "#85dc85"
    date:
        fg: "#9e9e9e"
    hrule:
        style:
            fg: "#f09479"
    link:
        fg: "#74b2ff,underline"
    slides:
        fg: "#e3c78a"
    headings:
        default:
            fg: "#80a0ff,bold"
        "1":
            fg: "#80a0ff,bold"
        "2":
            fg: "#79dac8,bold"
        "3":
            fg: "#ae81ff,bold"

---

# Desktop Customisation a.k.a Ricing
An introduction to customising your desktop, the components involved and resources for doing the same

---

## What is your desktop?
- Desktop environments
- Window managers and associated paraphernalia

---

## Desktop Environments
The big players
* GNOME
* KDE Plasma
* Xfce
* LXQt
* Cinnamon
* Budgie
* Pantheon

---

## Window Managers

X vs Wayland

X gives you a lot of options: cwm, Openbox, Xfwm, Bspwm, Herbstluftwm, i3, awesome, dwm, Qtile, xmonad

Your only real choice when it comes to Wayland: sway

There are others but they're not quite there yet: hikari, river

---

## Wallpapers

The first impression, on you and others

Make or break

Good resources: wallhaven, simple desktops, unsplash

Edit your wallpapers (gimp)

---

## Theming

Swapping resources out for a different set of resources

You can change your -

- stylesheet (GTK/Qt)
- icons
- cursor
- fonts

---

# Getting themes and the rest

- [Gnome Look](https://www.gnome-look.org/)
- [KDE Store](https://store.kde.org/)

---

## Installing themes and resources

Your distro's repositories but what if you like something and it's not there?

Themes are installed by moving the folder containing the theme into either 

- ~/.themes
- ~/.local/share/themes

Icon packs and cursors are installed by moving the folder into

- ~/.icons

You can then apply them from settings in some DEs or DE specific tools like Gnome Tweak Tool, etc in others

---

## Building your own desktop

What all do you need to have a functioning desktop?

- window manager
- status bar
- notification daemon
- screen lockers
- program launcher
- widgets
- display manger

The no-bar setup

---

# Compositors

Compositors and what they enable

Picom

Wayland and compositors

---

### Bars

Bars with modules
- Polybar
- Waybar

Making your own bar
- lemonbar

You can ultimately get what you want but some bars make it easier to

---

### Notification daemons

- Two approaches

- Dunst and Mako

- Tiramisu

---

### Launchers

- DE offerings

- Rofi is all you need (and wofi)

- dmenu, bemenu and other lightweight options

---

### Widgets

Why is Awesome awesome?

EWW can replace most of what we're talking about singlehandedly

---

### Screen lockers

- i3lock
- swaylock

--- 

## Color schemes

- Crafted (Nord, Dracula, Mountain)
- Generated
    - Random (terminal.sexy)
    - Wallpaper-based (pywal)

How to go about picking one?

---

## Fonts

- Why you need fonts
- How many fonts do you need?
- Where to get fonts?
- Comparing fonts ([104 Programming Fonts](https://www.programmingfonts.org/))

---

## Some special programs

- Terminal (traditional and modern options)
- Text editor (pick whatever you want as long as it's neovim)

---

## Terminal customisation

- Color scheme and font
    - Nerd fonts
- Prompt (pure, starship or make your own)

---

## Dotfiles

- Share yours
- Study others

Ask for dotfiles, you help yourself and the person you're asking

---

## Share

- Where can you share?
- Get inspired 
  - Standing on the shoulders of giants
  - Cherrypicking
- Excellent collections
    - [adi1090x](https://github.com/adi1090x)

---

## How far can you go?

- fork and add what you need
    - how deep does the rabbit hole go?
- roll your own everything

---

## A note on riced distros

So, that's a thing

Here are two worth checking out to get a taste: Garuda Linux and ArchCraft

---

# Thank you :)
