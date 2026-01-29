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