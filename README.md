# linuxforeducation

## Description

### Project Overview

#### What is the main goal of the project?
The main goal of the project is to create an Arch Linux customization for education via dotfiles. Firstly, the visual elements should not be distracting. Specifically, waybar should not contain unnecessary information for regular users, e.g., hardware metrics, weather forecast, and so on. Secondly, the color theme should avoid contrasting colors. Thirdly, notifications should be easily controlled by the user, e.g., disabling notifications except the pomodoro timer. Fourthly, optimized command aliases are effective for education. Finally, the keyboard interaction focus is to reduce distraction from mouse movement. To conclude, the goal of effective education Arch Linux customization contains unobtrusive visual elements, a non-contrasting color scheme, easily controlled notifications, effective aliases, and effective keyboard-styled interaction.

#### What should the project contain?
The project should (or may) contain the following:

- **Hyprland main configuration**
  - Monitors  
  - General settings  
  - Aesthetics  

- **Keybindings configuration**
  - Workspace navigation  
  - App launching  
  - Window management  

- **Window rules**
  - App-specific behavior  
  - Floating windows  
  - Workspace assignment  

- **Input configuration**
  - Keyboard layouts  
  - Mouse sensitivity  

- **Monitor/display setup**
  - Resolution  
  - Refresh rate  
  - Positioning  

- **Quickshell status bar implementation**
  - Workspace indicator module  
  - Clock/time display module  
  - Active window title module  
  - Notification indicator module  

- **Quickshell styling (QSS)**

- **Quickshell app-launcher implementation (or Rofi configuration)**
  - Application search and fuzzy matching  
  - Custom launcher modes (if Quickshell)  
  - Theme/styling for launcher  

- **Dunst configuration**
  - Rules  
  - Timeouts  
  - Appearance  
  - Notification filtering and prioritization  
  - Pomodoro timer notification handling  
  - Do Not Disturb toggle bindings  

- **Kitty main configuration (kitty.conf)**
  - Theme overrides (kitty.conf.nord, kitty.conf.catppuccin, kitty.conf.gruvbox)  
  - Transparency and font configuration  
  - Ligature and rendering settings  
  - Scrollback and tab bar configuration  

- **Shell configuration**
  - Bash initialization files (.bashrc, .bash_profile)  
  - Zsh initialization files (.zshrc, .zprofile)  
  - Shell aliases (navigation, git, system commands, education-focused)  
  - Shell functions (complex operations, custom workflows)  
  - Environment variable exports (XDG directories, PATH, theme variables)  
  - Shell completions (git, package managers, custom)  

- **Color scheme definitions**
  - Nord  
  - Catppuccin  
  - Gruvbox  

- **Color configuration**
  - Kitty color configuration (dynamic reloading)  
  - Quickshell/status bar color configuration  
  - Dunst notification colors  
  - Quickshell app-launcher colors  
  - GTK theme configuration  

- **Theme switcher script**
  - Kitty + Quickshell support  

- **Neovim configuration (init.lua, color scheme)**  
- **VS Code settings (optional)**  
  - Editor color scheme matching  

- **XDG Base Directory setup**
  - Config, data, cache, state directories  

- **GTK file manager configuration**  
- **Application desktop files (custom launchers)**  

- **Theme switcher script (Kitty, Quickshell, Dunst)**  

- **Automation and maintenance scripts**
  - Dotfiles backup/version control script  
  - Lock screen utility with custom styling  
  - Pomodoro timer integration script  
  - Installation automation script  
  - Dependency installation script  
  - Symbolic link creator script  
  - Setup verification script  
  - Kitty-specific theme reloading script  

- **Documentation**
  - README with project philosophy and quick start  
  - Installation guide (step-by-step)  
  - Configuration guide (customization instructions)  
  - Keybindings reference (complete list)  
  - Troubleshooting guide (common issues)  
  - Workflow examples (basic, development, note-taking)  
  - Per-component documentation (Quickshell, Kitty, Hyprland)  

- **CI/CD configuration**
  - Linting  
  - Validation  

- **Obsidian environment setup**
  - Wayland-specific configuration  

- **Git integration helpers**
  - Aliases for common workflows  

- **Pomodoro timer CLI tool configuration**  
- **Note-taking workflow helpers**

- **Keyboard layout setup**
  - Multiple layouts (US, Russian, etc.)  
  - Layout switching keybindings  
  - XKB options for language input  

- **UI consistency**
  - Unified color palette across all components  
  - Font consistency (terminal, status bar, launcher)  
  - Spacing and padding standards  
  - Opacity/transparency settings across UI elements  

#### Who is the target audience for this project?
The target audience for this project is computer science students or IT specialists who use Linux for education.

#### What learning objectives should users achieve?
Users of the linuxforeducation project should achieve mastery in creating and managing dotfiles for a distraction-free Arch Linux environment tailored to education. Users can achieve their best customization through flexible interaction with linuxforeducation dotfiles.

### Technical Details
 
#### What technology stack does the project use?
- **Window Manager/Compositor**: Hyprland
- **Status Bars**: Waybar, Quickshell (QML modules: workspace, clock, window title, notifications), AGS (Aylur's GTK Shell)
- **Terminal Emulators**: Kitty (Nord/Catppuccin/Gruvbox themes, transparency, fonts, ligatures), Alacritty, Foot
- **Notification Daemons**: Dunst (rules, timeouts, filtering, DND toggle, Pomodoro handling), Mako
- **App Launchers**: Rofi/Rofi-wayland (fuzzy search, theming), Wofi, Fuzzel, Tofi, Walker, Quickshell launcher
- **Shell**: Bash (.bashrc, .bash_profile), Zsh (.zshrc, .zprofile) with Oh My Zsh, Starship, Powerlevel10k
- **Shell Plugins**: zsh-autosuggestions, zsh-syntax-highlighting, zsh-history-substring-search, bash-completion
- **Text Editors**: Neovim (init.lua, color schemes), VS Code (matching themes)
- **File Managers**: Nautilus, Thunar, Ranger, lf
- **Color Schemes**: Nord, Catppuccin (Mocha/Latte/Frappe/Macchiato), Gruvbox (Dark/Light), Dracula, Tokyo Night, Rosé Pine, Solarized, Everforest, One Dark, Material
- **Dotfiles Management**: GNU Stow, Chezmoi, YADM, Bare Git Repository
- **Wallpaper Tools**: Hyprpaper, Swww (animated), Swaybg, Waypaper (GUI), feh
- **Lock Screen**: Swaylock/Swaylock-effects (blur, screenshots), Hyprlock, Gtklock
- **Idle Management**: Swayidle, Hypridle
- **Logout/Power Menu**: wlogout, Rofi power menu
- **Screenshot Tools**: Grim, Slurp (region selection), Grimblast, Swappy (annotation), Satty, Hyprshot
- **Screen Recording**: wf-recorder, wl-screenrec
- **Color Picker**: Hyprpicker
- **Clipboard Management**: wl-clipboard, Cliphist, Clipman, Clipvault, Clipse, CopyQ
- **System Monitoring**: btop++, htop, top, Glances, bottom (btm)
- **Audio**: PipeWire, PulseAudio, pipewire-pulse, WirePlumber, Pavucontrol, pamixer, wpctl
- **Brightness Control**: brightnessctl, light, xbacklight
- **Network Management**: NetworkManager (nmcli, nmtui, nm-applet), iwctl
- **Bluetooth**: bluetoothctl, blueman, blueberry
- **GTK Theming**: lxappearance, nwg-look, Oomox/Themix, Pywal (wallpaper colors), Gradience
- **Fonts**: Nerd Fonts, Hack Nerd Font, FiraCode, JetBrains Mono, Iosevka, Font Awesome
- **XDG Base Directories**: $XDG_CONFIG_HOME (~/.config), $XDG_DATA_HOME (~/.local/share), $XDG_CACHE_HOME (~/.cache), $XDG_STATE_HOME (~/.local/state), $XDG_RUNTIME_DIR
- **Pomodoro Timers**: pomo-cli, timer (Go), pomo (shell script)
- **CLI Utilities**: fzf (fuzzy finder), fd (find alternative), ripgrep/rg (grep alternative), bat (cat with highlighting), exa/eza (ls replacement), zoxide (smart cd), tldr, thefuck, delta (git pager), lazygit, ncdu, dust, duf, procs, sd
- **Package Management**: pacman, yay (AUR), paru (AUR), flatpak, paccache, reflector, pkgfile
- **Terminal Multiplexers**: tmux, zellij, screen
- **Image Viewers**: imv (Wayland), feh, sxiv
- **Document Tools**: pandoc, zathura, evince
- **Productivity Apps**: Obsidian (Wayland config), Zotero, MPV
- **Version Control**: Git, GitHub CLI, lazygit
- **Development Runtimes**: Docker/Podman, Node.js/npm, Python/pip, Rust/Cargo
- **Build Tools**: gcc/g++, make, cmake, meson, ninja
- **Configuration Formats**: JSON/JSONC (Waybar), TOML, YAML, INI, CSS/SCSS (styling), Lua (Neovim), QML (Quickshell), JavaScript/TypeScript (AGS)
- **Wayland Infrastructure**: wlroots, wayland-protocols, xdg-desktop-portal-hyprland, xdg-desktop-portal-wlr, wev (event viewer), wlr-randr
- **Authentication**: polkit, polkit-gnome, lxsession
- **Session Management**: systemd, D-Bus, XDG Autostart
- **Input Configuration**: libinput, XKB, Hyprland input config
- **Testing/Linting**: shellcheck, yamllint, pre-commit, GitHub Actions
- **System Information**: neofetch, fastfetch, inxi, screenfetch
- **Archive Tools**: tar, zip/unzip, 7zip/p7zip, atool
- **File Synchronization**: rsync, syncthing
- **Automation Scripts**: Theme switcher (Kitty/Quickshell/Dunst), dotfiles backup, installation automation, symbolic link creator, wallpaper rotation, Pomodoro integration
- **Hyprland-Specific**: hyprctl, hyprland-per-window-layout, Hyprland Plugin System, hyprland-plugins
- **Keyboard Layouts**: XKB options (US, Russian, multiple layouts), layout switching keybindings
- **Containerization** (testing): Docker, Podman, Distrobox

#### What are the system requirements?
