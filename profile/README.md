<p align="center">
  <img 
    src="https://wsrv.nl/?url=avatars.githubusercontent.com/u/87477585?v=5&w=300&h=300&mask=circle&fit=cover" 
    width="200"
  />
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Ubuntu&size=23&duration=3000&pause=1000&color=8cb8e4&center=true&vCenter=true&width=600&height=100&lines=GNU+bash%2C+version+5.2+anto426-ecosystem;Starting+Ecosystem+Hub...;Loading+Repositories...+done;%3Elogin+anto426-org;%5B+OK+%5D+Ecosystem+Online;root%40anto426-org%23echo+%22Welcome+to+the+Arch+Ecosystem%22" alt="Typing SVG" /></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/divider.gif" width="440" height="40" />
</p>

# <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/icon.gif" width="60px" /> About the Ecosystem;

```sh
root@anto426: ~/organization (main⚡)$ neofetch

⡿⣡⣿⣿⡟⡼⡁⠁⣰⠂⡾⠉⢨⣿⠃⣿⡿⠍⣾⣟⢤⣿⢇⣿⢇⣿⣿⢿            root@anto426-org
⣱⣿⣿⡟⡐⣰⣧⡷⣿⣴⣧⣤⣼⣯⢸⡿⠁⣰⠟⢀⣼⠏⣲⠏⢸⣿⡟⣿            --------------------
⣿⣿⡟⠁⠄⠟⣁⠄⢡⣿⣿⣿⣿⣿⣿⣦⣼⢟⢀⡼⠃⡹⠃⡀⢸⡿⢸⣿            Ecosystem: Wayland / Hyprland
⣿⣿⠃⠄⢀⣾⠋⠓⢰⣿⣿⣿⣿⣿⣿⠿⣿⣿⣾⣅⢔⣕⡇⡇⡼⢁⣿⣿            Target OS: Arch Linux
⣿⡟⠄⠄⣾⣇⠷⣢⣿⣿⣿⣿⣿⣿⣿⣭⣀⡈⠙⢿⣿⣿⡇⡧⢁⣾⣿⣿            Color Engine: Dynamic Wallpaper Palette
⣿⡇⠄⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⢻⠇⠄⠄⢿⣿⡇⢡⣾⣿⣿⣿            Primary Theme: Orchis Fork (Riva custom)
⣿⣷⢰⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⢰⣧⣀⡄⢀⠘⡿⣰⣿⣿⣿⣿⣿            Core Shell: Zsh + Oh My Posh
⢹⣿⢸⣿⣿⠟⠻⢿⣿⣿⣿⣿⣿⣿⣿⣶⣭⣉⣤⣿⢈⣼⣿⣿⣿⣿⣿⣿            Bootstrap Tool: GNU Stow + custom Installer
⢸⠇⡜⣿⡟⠄⠄⠄⠈⠙⣿⣿⣿⣿⣿⣿⣿⣿⠟⣱⣻⣿⣿⣿⣿⣿⠟⠁            VSCode Theme: Anto426 Rofi Dynamic
⠄⣰⡗⠹⣿⣄⠄⠄⠄⢀⣿⣿⣿⣿⣿⣿⠟⣅⣥⣿⣿⣿⣿⠿⠋⠄⠄⣾            Bootloader: Customized GRUB2
⠜⠋⢠⣷⢻⣿⣿⣶⣾⣿⣿⣿⣿⠿⣛⣥⣾⣿⠿⠟⠛⠉⠄⠄ . .
```

<p align="center">
  <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/divider.gif" width="440" height="40" />
</p>

# <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/icon2.gif" width="70px" /> Core Repositories;

```sh
root@anto426: ~/organization (main⚡)$ btop --preset repos

+- core.installer                    -+     +- ecosystem.components              -+
| [Arch-Hyprland](https://github.com/Anto426/Arch-Hyprland) |     | 1. [dotfiles](https://github.com/Anto426/dotfiles)       (Configs & Theming) |
| Beautiful automatic Wayland deploy  |     | 2. [rofi](https://github.com/Anto426/rofi)           (Wayland Slider Fork) |
|                                     |     | 3. [grub2-themes](https://github.com/Anto426/grub2-themes)   (Dynamic Bootloader)  |
| [auto-setup-LT](https://github.com/Anto426/auto-setup-LT) |     | 4. [Anto426-theme](https://github.com/Anto426/Anto426-theme)  (GTK stable base)     |
| Minimal Shell / Terminal bootstrap   |     | 5. [vscodetheme](https://github.com/Anto426/vscodetheme)    (VSCode Sync Theme)   |
|                                     |     | 6. [Wallpaper-Collection](https://github.com/Anto426/Wallpaper-Collection) (Assets)    |
+-------------------------------------+     +-------------------------------------+
```

<p align="center">
  <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/divider.gif" width="440" height="40" />
</p>

# <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/icon3.gif" width="70px" /> Architecture Flow;

```mermaid
graph TD
    A[Wallpaper Collection] -->|Sourced by| B(dotfiles: wallpaper_select.sh)
    B -->|Generates Color Palette| C[Dynamic Palette Engine]
    C -->|Applies CSS & Layout| D[Waybar & Ghostty]
    C -->|Rewrites JSON| E[VS Code: Anto426 Rofi Dynamic]
    C -->|Compiles Assets| F[GRUB2 Boot Theme]
    C -->|Propagates variables| G[SwayNC & custom Rofi]
    
    H[Arch-Hyprland Installer] -->|Clones and Installs| A
    H -->|Clones and Stows| B
    H -->|Clones and Integrates| F
    H -->|Builds from Source| G
    H -->|Compiles| E
    H -->|Installs Fallback| I[Anto426-theme GTK Base]
```

<p align="center">
  <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/divider.gif" width="440" height="40" />
</p>

# <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/icon4.gif" width="70px" /> Visitors;

<p align="center">
  <img src="https://count.getloli.com/@anto426-org?name=anto426-org&theme=booru-lisu&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Anto426/Anto426/main/asset/divider.gif" width="440" height="40" />
</p>

<div align="center">
  <i>Maintained by the anto426 ecosystem</i>
</div>
