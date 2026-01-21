# Pix's Necronomicon of Software and Tools

This is inspired by the [awesome](https://github.com/sindresorhus/awesome) repos that have lead me to cool tools, so this is just my take on that, a list of awesome software I've found while passing through cyberspace

This list will likely have a cyber security lean just cause of my line of work, but will include anything I've found that I think is cool or useful.

Please send me cool tools to try! I'm always looking for more new awesome stuff to try!

## Indexing

  *A list of everything!*

- [Colourschemes](#colourschemes)
- [Window Managers && Desktop Environments](#window-managers--desktop-environments)
- [GUI Programs](#gui-programs)
- [Fonts](#fonts)
- [Shells](#shells)
- [Package Managers](#package-managers)
- [Markdown Tools](#markdown-tools)
- [Editors](#editors)
- [Terminal Emulators](#terminal-emulators)
- [File Swiss Army Knives](#file-swiss-army-knives)
- [Debugging Tools](#debugging-tools)
- [Version Control](#version-control)
- [AI Backed Tooling](#ai-backed-tooling)
- [Database Tooling](#database-tooling)
- [Programming Languages](#programming-languages)
- [Cool Development Libraries](#cool-development-libraries)
- [Build Systems](#build-systems)
- [Generic Productivity Tools](#generic-productivity-tools)
- [Command Line Tools](#command-line-tools)
  - [ls replacements](#ls-replacements)
  - [cd replacements](#cd-replacements)
  - [Linux Ng Tools - Replacements for common linux coreutils](#linux-ng-tools---replacements-for-common-linux-coreutils)
  - [CLI Network Tools](#cli-network-tools)
  - [Compression Tools](#compression-tools)
  - [Terminal File Managers](#terminal-file-managers)
  - [CLI Data Manipulation](#cli-data-manipulation)
    - [Colours and Styling](#colours-and-styling)
  - [Other CLI Tools](#other-cli-tools) - The List of Everything not in the above categories
- [Javascript Ecosystem](#javascript-ecosystem)
- [Cloud Tooling](#cloud-tooling)
- [IRC](#irc)
- [Logging](#logging)
- [Backup Tooling](#backend-tooling)

## Colorschemes

  *Because its important for things to look pretty if you have to stare at them for awhile*

- [Umbral](https://github.com/pix-xip/umbral.nvim) - Pix's colourscheme for Neovim and more!
- [catppuccin](https://github.com/catppuccin/catppuccin) - A beautiful pastel theme for your terminal
- [tokyonight](https://github.com/folke/tokyonight.nvim) - A beautiful theme for Neovim
- [Shadotheme](https://github.com/Shadorain/shadotheme) - A fantastic pink and purple theme!

## Window Managers && Desktop Environments

  *Unless you wanna interact with a black screen and a basic terminal, this should get you going..*

- [Aerospace](https://github.com/nikitabobko/AeroSpace) - An i3-like tiling winodw manager for macOS
- [Hyprland](https://github.com/hyprwm/Hyprland) - An independent, highly customizable dynamic tiling Wayland compositor
- [Niri](https://github.com/YaLTeR/niri) - A scrolling, tiled Wayland compositor
- [Sway](https://github.com/swaywm/sway) - An i3 compatible Wayland compositor
- [Yabai](https://github.com/koekeishiya/yabai) - A tiling window manager for macOS that uses the accessibility API

## Fonts

  *The fonts I've used and enjoyed*

- [Maple Mono](https://github.com/subframe7536/maple-font) - A monospaced font with rounded corners and ligatures.
- [Fira Code](https://github.com/tonsky/FiraCode) - A free monospaced font with programming ligatures
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) - A monospaced font with programming ligatures found near everywhere

## GUI Programs

  *A collection of GUI programs I found useful, that don't really fit into the other categories*

- [alfred](https://www.alfredapp.com/) - macOS Replacement for Spotlight with more productivity features
- [bitwarden](https://bitwarden.com/) - Cross-platform password manager
- [flameshot](https://github.com/flameshot-org/flameshot) - Powerful yet simple to use screenshot software
- [grim](https://github.com/emersion/grim) - Image Grabber for Wayland compositors
- [grimblast](https://github.com/hyprwm/contrib/tree/main/grimblast) - Hyprland version of Grimshot
- [hammerspoon](https://github.com/Hammerspoon/hammerspoon) - macOS desktop automation with Lua
- [hyprpicker](https://github.com/hyprwm/hyprpicker) - A simple and lightweight image picker for Hyprland
- [hyprpaper](https://github.com/hyprwm/hyprpaper) - Wayland wallpaper utility with IPC controls
- [obsidian](https://obsidian.md/) - A powerful knowledge base on top of a local folder of plain text Markdown files
- [raycast](https://www.raycast.com/) - macOS replacement for Spotlight with more productivity features
- [rectangle](https://github.com/rxhanson/Rectangle) - Move and resize windows on macOS with keyboard shortcuts and snap areas
- [rofi](https://github.com/davatorium/rofi) - A window switcher, application launcher and dmenu replacement
- [sddm](https://github.com/sddm/sddm) - Simple Desktop Display Manager for X11 && Wayland
- [shotcut](https://www.shotcut.org/) - Free and open source cross-platform video editor
- [sketchybar](https://github.com/FelixKratz/SketchyBar) - A highly customizable status bar for macOS
- [skhd](https://github.com/koekeishiya/skhd) - Simple hotkey daemon for macOS
- [sway-bg](https://github.com/swaywm/sway-bg) - Wallpaper manager for Wayland compositors
- [swaylock](https://github.com/swaywm/swaylock) - Screen locker for Wayland compositors
- [waybar](https://github.com/Alexays/Waybar) - Super duper customizable Wayland bar for Sway/Wlroots based compositors
- [waybar-hyprland](https://github.com/r-clifford/Waybar-Hyprland) - Hyprland fork of Waybar
- [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Command line copy/paste utilities for Wayland
- [wl-clipboard-history](https://github.com/janza/wl-clipboard-history) - Wayland clipboard history manager

## Shells

  *The various shells I've tried and useful extensions/plugins*

- [fish](https://fishshell.com/) - A modern shell with features like syntax highlighting and autosuggestions out of the box
  - [fisher](https://github.com/jorgebucaran/fisher) - The Package Manager for Fish
  - [umbral](https://github.com/pix-xip/umbral.nvim/tree/main/extras/fish) - Pix's umbral theme for fish
  - [autopair.fish](https://github.com/jorgebucaran/autopair.fish) - Auto [] {} () etc.
  - [catppuccin](https://github.com/catppuccin/fish) - Pastel theme for your terminal
  - [fish-colored-man](https://github.com/decors/fish-colored-man) - Coloured man pages
  - [fish-ssh-agent](https://github.com/danhper/fish-ssh-agent) - SSH agent using fish.
  - [fzf.fish](https://github.com/PatrickF1/fzf.fish) - Fzf plugins/hotkeys for fish
  - [rose-pine](https://github.com/rose-pine/fish) - SOHO vibes for commandline
  - [sponge](https://github.com/meaningful-ooo/sponge) - Cleans up typos and or commands that do not return 0
  - [tide](https://github.com/ilancosman/tide) - Async modern shell prompt.

- [nushell](https://github.com/nushell/nushell) - A complicated shell with a focus on piping and handling data inline
- [zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH) - The more modern bash shell!
  - [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) - A community-driven framework for managing your zsh configuration
- [bash](https://github.com/bminor/bash) - The default shell almost everywhere
- [ash](#) - Stripped back alpine shell
- [dash](#) - Lightweight POSIX compliant shell that tends to be what is actually `/usr/bin/sh`

## Package Managers

  *Package managers I use on the regular for each of the different systems I run*

- [yay](https://github.com/Jguer/yay) - Yet another yogurt package manager (Arch Linux)
- [eget](https://github.com/zyedidia/eget) - Installer for pre-build binaries from Github
- [paru](https://github.com/Morganamilo/paru) - A AUR wrapper for Arch Linux
- [brew](https://brew.sh/) - The missing package manager for macOS written in Ruby
- [bbrew](https://github.com/Valkyrie00/bold-brew) - A Homebrew TUI manager for package management
- [nix](https://nixos.org/) - A purely functional package manager for Linux and other Unix systems
  - [home-manager](https://github.com/nix-community/home-manager) - A tool for managing your home-configuration, powered by Nix

## Markdown Tools

  *Helpful tools for rendering Markdown in the termial*

- [dawn](https://github.com/andrewmd5/dawn) - An in terminal lighweight document drafter that renders markdown directly
- [glow](https://github.com/charmbracelet/glow) - Render markdown on the CLI, with pizzazz
- [mdcat](https://github.com/lunaryorn/mdcat) - cat for Markdown
- [mdtt](https://github.com/szktkfm/mdtt) - Markdown table editor TUI

## Editors

  *The various editors I've tried and thought were useful*

- [neovim](https://github.com/neovim/neovim) - A fork of vim that you can extend to the moon and back
- [neovide](https://github.com/neovide/neovide) - A GPU-accelerated version of neovim
- [Sublime Text](https://www.sublimetext.com/) - A decent cross platform text editor with plugins, extremely good at rendering large files
- [Zed](https://zed.dev/) - A modern editor with a focus on speed and simplicity

## Terminal Emulators

  *Terminal Emulators I've used and some quick thoughts on them*

- [ghostty](https://github.com/ghostty-org/ghostty) - An extremely fast, Linux/macOS feature-rich terminal emulator written in Zig, my current daily driver and all around good vibes for my terminal experience
- [kitty](https://github.com/kovidgoyal/kitty) - A fast, feature-rich, GPU based terminal emulator, has a focus on feeling snappy and contains plenty of features but had some strange defaults.
- [wezterm](https://github.com/wez/wezterm) - A GPU accelerated cross-platform terminal emulator, highly extensible and customizable with `lua` however it does feel like its fallen a little behind things like `kitty` and `ghostty`, however given you can extend it so far with lua it makes for a very personalised environment if you enjoy configuring.
- [alacritty](https://github.com/alacritty/alacritty) - Minimalist, fast emulator, it can dump text to screen fast.
- [foot](https://github.com/charmbracelet/foot) - Fast, lightweight and minimalist Wayland terminal emulator. Extremely good performance on Hyprland and Sway.
- [st](https://github.com/Shourai/st) - A simple terminal emulator you compile the config for. Extremely minimalist
- [iterm2](https://iterm2.com/) - The default terminal app on macOS, it's a bit of a mess but it works

## File Swiss Army Knives

  *Do you need to manipulate audio, video, images or text/docs? Here are is what you reach for first*

- [pandoc](https://github.com/jgm/pandoc) - Universal markup converter, Swiss Army Knife for converting documents
- [ffmpeg](https://ffmpeg.org/) - A collection of libraries and tools to process multimedia content such as audio, video, subtitles and related metadata, this runs basically every video processing you've ever heard of. The Swiss Army Knife of Audio
- [sox](https://github.com/chirlu/sox) - Swiss Army Knife of sound processing

## Debugging Tools

  *Debugging tools for when its all gone to shit Kupo! I need to find more of these*

- [cgdb](https://github.com/cgdb/cgdb) - Console front-end for `gdb`
- [dlv](https://github.com/go-delve/delve) - Delve is a debugger for the Go programming language
- [gdb](https://sourceware.org/gdb/) - The tried and true debugger for languages ranging from Ada and C to Rust and Go
- [heretek](https://github.com/wcampbell0x2a/heretek) - GDB TUI inspired by `gef` written in Rust and works with gdbserver remotely
- [lldb](https://lldb.llvm.org/) - The LLVM debugger, Swift, C#, and other things built atop the LLVM infrastructure
- [ste](https://github.com/fabiensanglard/st) - Command space-time explorer, a tool to explore how command line programs work, memory usage and more
- [valgrind](https://valgrind.org/) - A suite of tools for debugging and profiling memory

## Version Control

  *Do you like saving your work? Reverting your changes? Keeping a history?!*

- [dotstate](https://github.com/serkanyersen/dotstate) - A modern, secure and user-friendly dotfile manager
- [gh](https://cli.github.com/) - Github CLI, makes dealing with git repos on github braindead
- [git kraken](https://www.gitkraken.com/) - An alternative for `sublime merge` that works well on Windows
- [git-delta](https://github.com/dandavison/delta) - A syntax-highlighting pager for `git`
- [gitui](https://github.com/gitui-org/gitui) - Fast terminal-ui for git written in Rust, a less pretty `lazygit`
- [icdiff](https://github.com/jeffkaufman/icdiff) - An improved coloured version of `diff` written in Python
- [jujutsu](https://github.com/jj-vcs/jj) - A git compatible VCS written in Rust with a new way of handling version control
- [lazygit](https://github.com/jesseduffield/lazygit) - A fantastic TUI for git written in Go
- [sublime merge](https://www.sublimemerge.com/) - A fantastic, easy to parse git GUI for Sublime Text
- [svn](https://subversion.apache.org/) - Mercurial based VCS

## AI Backed Tooling

  *AI powered tools I've found and tried*

- [gemini-cli](https://github.com/google-gemini/gemini-cli) - Open source AI agent direct in your terminal, with access to everything..
- [goji](https://github.com/muandane/goji) - Commitizen-like emoji commit tool written in Go with AI commit message generator
- [smartcat](https://github.com/efugier/smartcat) - 'Putting the brain behind `cat`' integrates an LLM with cat
- [tgpt](https://github.com/aandrew-me/tgpt) - AI chatbots without needing API keys
- [warp](https://www.warp.dev/) - This used to be a temrinal, nowadays its like some llm agent dev env

## Database Tooling

  *Basic database tools and databases, honestly I suck at db's*

- [gobang](https://github.com/TaKO8Ki/gobang) - A cross-platform TUI database management tool written in Rust
- [lazysql](https://github.com/jorgerojas26/lazysql) - A cross-platform TUI database management tool written in Go
- [manticore](https://github.com/manticoresearch/manticore) - A fast, in-memory, vector search engine with SQL-like query syntax
- [sqlit](https://github.com/Maxteabag/sqlit) - TUI for SQL databases written in Python
- [sqlite](https://www.sqlite.org/index.html) - Everyone's favourite flat file database works with everything
- [surealdb](https://github.com/surrealdb/surrealdb) - Scalable, distributed, collaborative document-graph database

## Programming Languages

  *Various programming languages to work in*

- [bash](#) - Default shell scripting language almost everywhere
- [c#](https://dotnet.microsoft.com/en-us/languages/csharp) - The Microsoft programming language
- [c++](#) - Overengineered C
- [c](#) - Do I really need to explain C?
- [fish](https://fishshell.com/) - Fish scripting language, not POSIX compliant but feels sane
- [go](https://golang.org/) - The simple and powerful programming language from Google
- [haskell](https://www.haskell.org/) - Because everyone needs to try functional programming at least once
- [lua](https://www.lua.org/) - A powerful, fast, lightweight, embeddable scripting language
- [odin](https://github.com/odin-lang/Odin) - The C alternative for the joy of programming
- [perl](https://www.perl.org/) - Golf the heck out of your code
- [python](https://www.python.org/) - A general purpose scripting language
- [ruby](https://www.ruby-lang.org/) - The language of the internet (Rails)
- [swift](https://www.swift.org/) - The Apple programming language
- [zig](https://github.com/ziglang/zig) - General purpose systems programming language

## Cool Development Libraries

  *Mostly focused around C or Zig, cool libraries to work with and extend your code*

- [coreutils](https://github.com/coreutils/coreutils) - The GNU core utilities
- [hiredis](https://github.com/redis/hiredis) - A minimalistic C client for Redis
- [jemalloc](https://github.com/jemalloc/jemalloc) - A general purpose malloc implementation
- [libconfig](https://github.com/hyperrealm/libconfig) - A cross-platform library for parsing structured configuration files
- [libevent](https://github.com/libevent/libevent) - A cross-platform event notification library
- [libuv](https://github.com/libuv/libuv) - A cross-platform asynchronous I/O library
- [quickshell](https://quickshell.org/) - Flexible toolkit for making desktop shells using QtQuick.
- [mimalloc](https://github.com/microsoft/mimalloc) - A compact general purpose allocator with excellent performance
- [pix.h](#) - My very own header only library that brings along all sorts of useful things!
- [stb](https://github.com/nothings/stb) - A collection of header only libraries
- [xxhash](https://github.com/Cyan4973/xxHash) - A blazingly fast non-cryptographic hash algorithm

## Build Systems

  *Do you like to compile your code? But you don't want the hassle of typing out long compile commands every time?*

- [cmake](https://cmake.org/) - A cross-platform build system generator
- [make](https://www.gnu.org/software/make/) - Precusor to cmake! Still in use today cause it works!
- [meson](https://mesonbuild.com/) - A build system using ninja as a backend with a python like syntax
- [ninja](https://ninja-build.org/) - Build system with a focus on speed and parallelism
- [remake](https://github.com/pix-xip/remake) - I make my own build system, written in `C`, configured via `lua`
- [zig](https://ziglang.org/) - Due to its inbuilt C compiler etc, its a shocking good build system

## Generic Productivity Tools

 *Tooling to hopefully make you a more productive person*

- [pomo](https://github.com/Bahaaio/pomo) - Customisable TUI pomodoro timer with fun ascii art and notifications
- [taskwarrior](https://taskwarrior.org/) - A command line todo list manager

## Command Line Tools

  *The giant unsorted collection of CLI tools I keep, always adding more, at some point I'll split these into proper categories..*

### ls replacements

  *Advanced, modern and or simple replacements for everyone's favourite idle command to run*

- [erdtree](https://github.com/solidiquis/erdtree) - Cross-platform, multi-threaded and general purpose filesystem and disk usage utility with .gitignore awareness
- [eza](https://github.com/eza-community/eza) - A modern alternative to `ls` with lots of features!
- [lla](https://github.com/chaqchase/lla) - Blazingly fast `ls` replacement with 'superpowers'
- [lsd](https://github.com/lsd-rs/lsd) - Another rust rewrite of `ls`
- [natls](https://github.com/willdoescode/nat) - `ls` alternative with useful info and a splash of colour
- [pls](https://github.com/pls-rs/pls) - A prettier and powerful `ls` replacement

### cd replacements

  *Because sometimes you just need to jump around instead of typing full paths*

- [fasd](https://github.com/clvv/fasd) - An autojumper for jumping to files and directories
- [pazi](https://github.com/euank/pazi) - An autojump 'zap to directory' helper
- [z](https://github.com/rupa/z) - Z to jump around with regex
- [zoxide](https://github.com/ajeetdsouza/zoxide) - A smarter `cd` command

### Linux Ng Tools - Replacements for common linux coreutils

  *Modern replacements for the tried and true*

- [atop](https://github.com/Atoptool/atop) - System and process monitoring for Linux, alternative to `top`
- [bat](https://github.com/sharkdp/bat) - A `cat` clone with wings
- [bottom](https://github.com/ClementTsang/bottom) - A cross-platform graphical process/system monitor in Rust
- [btop](https://github.com/aristocratos/btop) - A pretty monitor of resources, alternative to `top`
- [choose](https://github.com/theryangeary/choose) - A human-friendly and fast alternative to `cut` and some `awk` commands
- [cyme](https://github.com/tuna-f1sh/cyme) - Cross-platform replacement for `lsusb`
- [dua](https://github.com/Byron/dua-cli) - A more intuitive version of `du`
- [duf](https://github.com/muesli/duf) - An intuitive visual replacement for `df`
- [dust](https://github.com/bootandy/dust) - A more intuitive version of `du` with a nice visual output
- [fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to `find`
- [glances](https://github.com/nicolargo/glances) - A `top`/`htop` alternative written in Python
- [hevi](https://github.com/Arnau478/hevi) - A hex viewer and alternative to `xxd`
- [hexyl](https://github.com/sharkdp/hexyl) - A coloured hex viewer and `xxd` alternative
- [htop](https://github.com/htop-dev/htop) - An interactive process viewer, alternative to `top`
- [hwatch](https://github.com/blacknon/hwatch) - Alternative to `watch`, records the differences in execution results and can check differences after
- [procs](https://github.com/dalance/procs) - A modern replacement for `ps`
- [rip](https://github.com/nivekuil/rip) - A safer and ergonomic alternative to `rm`, includes a trash!
- [ripgrep](https://github.com/BurntSushi/ripgrep) - A search tool like `grep` but faster
- [rsync](https://github.com/RsyncProject/rsync) - An open source utility for fast incremental file transfer, potential replacement for `cp` and `scp`
- [sd](https://github.com/chmln/sd) - Intuitive find & replace CLI, replacement for `sed`

### CLI Network Tools

  *Networking command line tools for debugging and more!*

- [axel](https://github.com/axel-download-accelerator/axel) - Lightweight CLI download accelerator
- [bandwich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool
- [bmon](https://github.com/tgraf/bmon) - Bandwidth monitor and rate estimator for your terminal
- [cidr](https://github.com/bschaatsbergen/cidr) - Network tool for subnet calculation and CIDR explanation
- [curlie](https://github.com/rs/curlie) - The power of curl, the ease of `httpie`
- [dog](https://github.com/ogham/dog) - A command-line DNS client
- [doggo](https://github.com/mr-karan/doggo) - A modern DNS client like `dig` written in Go
- [got](https://github.com/melbahja/got) - Go tool to download large files faster then `curl` and `wget`
- [havn](https://github.com/mrjackwills/havn) - A configurable port scanner with decent default options
- [httpie](https://github.com/httpie/cli) - user-friendly, command-line HTTP client for the API era, JSON support, colours, sessions, downloads, plugins and move
- [iproute2mac](https://github.com/brona/iproute2mac) - CLI wrapper for basic network utilities on MacOS
- [impala](https://github.com/pythops/impala) - TUI for managing WiFi on Linux
- [netcat](https://netcat.sourceforge.net/) - The network swiss army knife
- [oryx](https://github.com/pythops/oryx) - TUI for sniffing network traffic via eBPF
- [rustscan](https://github.com/bee-san/RustScan) - A 'modern' port scanner replacement for `nmap`
- [sntop](https://sntop.sourceforge.net/) - A simple network top
- [socat](https://www.dest-unreach.org/socat/) - Another swiss army knife for networking!
- [ssh-para](https://github.com/joknarf/ssh-para) - Parallel ssh jobs manager with interactive CLI
- [stu](https://github.com/lusingander/stu) - A TUI explorer for Amazon S3 buckets
- [tcpdump](https://www.tcpdump.org/) - A way to dump network traffic straight off the interface
- [tcpterm](https://github.com/sachaos/tcpterm) - A TCPDump visualiser
- [trippy](https://github.com/fujiapple852/trippy) - Network diagnostic tool with TUI output
- [tufw](https://github.com/peltho/tufw) - A TUI for `ufw`
- [unbound](https://github.com/NLnetLabs/unbound) - A validating, recursive, caching DNS resolver
- [updog](https://github.com/Owloops/updo) - Uptime monitoring CLI tool
- [wg](https://git.zx2c4.com/wireguard-tools/) - A toolkit for managing WireGuard
- [zerotier-one](https://www.zerotier.com/) - A mesh networking protocol that lets you connect devices together without the hassle of setting up a VPN, it has a free tier and a self hosted!

### Compression Tools

  *Making things smol, hopefully at acceptably fast speeds*

- [7zip](https://7-zip.org/) - A file archiver with a focus on speed
- [gzip](https://www.gnu.org/software/gzip/) - A fast compression tool
- [lz4](https://github.com/lz4/lz4) - An extremely fast compression algorithm
- [ouch](https://github.com/ouch-org/ouch) Painless compression and decompression in your terminal
- [pixz](https://github.com/vasi/pixz) - Parallel, indexed xz compressor
- [xz](https://github.com/tukaani-project/xz) - A high-compression file format and tool
- [zstd](https://github.com/facebook/zstd) - A fast lossless compression algorithm

### Terminal File Managers

  *Because who needs a GUI*

- [nnn](https://github.com/jarun/nnn) - The unorthodox terminal file manager designed to be fast with zero config
- [superfile](https://github.com/yorukot/superfile) - Pretty fancy and modern terminal file manager
- [yazi](https://github.com/sxyazi/yazi) - Blazingly fast terminal file manager written in Rust, based on async I/O

### CLI Data Manipulation

  *Easily manipulate common data formats with these tools*

- [dasel](https://github.com/TomWright/dasel) - Select, Put, Delete data from JSON, TOML, YAML, XML and CSV files with a single tool
- [fastmod](https://github.com/facebookincubator/fastmod) - A fast batch file editor find and replace
- [jless](https://github.com/PaulJuliusMartinez/jless) - JSON viewer designed for reading, exploring and searching through JSON data
- [jnv](https://github.com/ynqa/jnv) - Interactive JSON filter using `jq`
- [jq](https://github.com/jqlang/jq) - Command line JSON processor in C
- [jqp](https://github.com/noahgorstein/jqp) - A TUI playground to experiment with `jq`
- [jqp](https://github.com/noahgorstein/jqp) - TUI playground to use with `jq`
- [miller](https://github.com/johnkerl/miller) - Miller is like `awk`, `sed`, `cut`, `join` and `sort` for name-indexed data such as CSV, TSV, and tabular JSON
- [sad](https://github.com/ms-jpq/sad) - CLI batch search and replace
- [sttr](https://github.com/abhimanyu003/sttr) - Cross-platform tool to perform various operations on strings
- [yq](https://github.com/mikefarah/yq) - Portable command-line YAML and more properties processor

### Colours and Styling

*Making your terminal look gorgeous*

- [chalk-cli](https://github.com/chalk/chalk-cli) - A terminal string styling library in JavaScript
- [gum](https://github.com/charmbracelet/gum) - A tool for glamorous shell scripts, includes plenty of quality of life features for scripting
- [pastel](https://github.com/sharkdp/pastel) - A command-line tool to generate, analyze, convert and manipulate colors

### Other CLI Tools

  *All the other CLI tools I cannot categorise easily or don't have many competitors, yet*

- [atuin](https://github.com/atuinsh/atuin) - Magical Shell History, syncs across multiple machines if you want
- [ast-grep](https://github.com/ast-grep/ast-grep) - A CLI tool for code structured search, lint and rewrite
- [await](https://github.com/slavaGanzin/await) - Single binary that runs list of commands in parallel and waits for their termination
- [bear](https://github.com/rizsotto/Bear) - A tool for generating compilation database for clang tooling
- [bitwise](https://github.com/mellowcandle/bitwise) - Terminal based bit manipulator in `ncurses`
- [bp](https://github.com/printfn/bp) - Cross-platform clipboard tool
- [broot](https://github.com/Canop/broot) - A file manager with a focus on speed and simplicity
- [bt](https://github.com/LeperGnome/bt) - An interactive tree-line terminal file manager written in Go
- [cheat.sh](https://github.com/chubin/cheat.sh) - Endless quick cheat sheets for various topics!
- [circumflex](https://github.com/bensadeh/circumflex) - Hacker News in your terminal
- [clipboard](https://github.com/Slackadays/Clipboard) - Ridonkuliciously smart clipboard manager
- [cod](https://github.com/dim-an/cod) - Auto-Completion daemon for `bash`/`fish`/`zsh`
- [cotp](https://github.com/replydev/cotp) - Terminal tool for managing OTP's
- [chalk-cli](https://github.com/chalk/chalk-cli) - A terminal string styling library in JavaScript
- [croc](https://github.com/schollz/croc) - Easily and securely send things from one computer to another
- [ctop](https://github.com/bcicen/ctop) - `top`-like interface for container metrics
- [dblab](https://github.com/danvergara/dblab) - The database client every command line junkie deserves
- [diskonaut](https://github.com/imsnif/diskonaut) - Terminal disk space navigator
- [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image
- [dos2unix](https://github.com/TizenTeam/dos2unix) - Remove the extras from dos files to be compatible with unix
- [dua-cli](https://github.com/Byron/dua-cli) - View disk space usage and delete unwanted data fast
- [dyff](https://github.com/homeport/dyff) - Diff tool for YAML files, and sometimes JSON
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) - The up to date system info tool, written with performance in mind like `neofetch`
- [fjira](https://github.com/mk-5/fjira) - The golang fuzzy-find cli jira interface
- [flex](https://github.com/westes/flex) - Fast Lexical Analyser, scanner generator for lexing in C && C++
- [fzy](https://github.com/jhawthorn/fzy) - Simple, fast fuzzy finder for the terminal
- [gdu](https://github.com/dundee/gdu) - Pretty fast disk usage analyser with TUI written in Go
- [ghq](https://github.com/x-motemen/ghq) - Remote repository management made easy
- [gperf](https://github.com/yakaz/gperf) - A perfect hash function generator
- [hostctl](https://github.com/guumaster/hostctl) - Your dev tool to manage `/etc/hosts` like a pro
- [hunspell](https://github.com/hunspell/hunspell) - The most popular spellchecking library
- [hyperfine](https://github.com/sharkdp/hyperfine) - A command-line benchmarking tool
- [just](https://github.com/casey/just) - A command runner written in rust, to be an improvement on make
- [k9s](https://github.com/derailed/k9s) - Kubernetes CLI to Manage your clusters in style
- [keyb](https://github.com/kencx/keyb) - Create and view custom hotkey cheatsheets in the terminal
- [lemmeknow](https://github.com/swanandx/lemmeknow) - The fastest way to identify anything looking at strings
- [mprocs](https://github.com/pvolok/mprocs) - Run multiple commands in parallel
- [mutt](https://github.com/muttmua/mutt) - An email client for your terminal
- [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line
- [nemu](https://github.com/nemuTUI/nemu) - NCurses based UI for QEMU
- [neofetch](https://github.com/dylanaraps/neofetch) - A command line system information tool written in bash
- [nomino](https://github.com/yaa110/nomino) - Batch rename utility for developers
- [noti](https://github.com/variadico/noti) - Monitor a process and trigger a notification!
- [nvrs](https://github.com/adamperkowski/nvrs) - New version checker for software releases
- [onefetch](https://github.com/o2sh/onefetch) - Git repository summary on your terminal, similar to `neofetch`/`fastfetch` but for `git`
- [oom](https://github.com/dhth/omm) - Keyboard-driven task manager/todo list for command-line
- [pdu](https://github.com/KSXGitHub/parallel-disk-usage) - Highly parallelised fast directory tree analyser
- [pgtree](https://github.com/joknarf/pgtree) - Unix process hierachy tree for specific processes
- [pillager](https://github.com/brittonhayes/pillager) - Pillage filesystems for sensitive information with Go
- [pingme](https://github.com/kha7iq/pingme) - CLI utility which provides the ability to send messages or alerts to multiple messaging platforms & email
- [pueue](https://github.com/Nukesor/pueue) - Manage shell commands in the background and execute them whenever
- [pssh](https://github.com/pix-xip/pssh) - TUI wrapper for `ssh` with a searchable menu for your SSH Config
- [ran](https://github.com/m3ng9i/ran) - Simple static web server written in Go
- [rclone](https://github.com/rclone/rclone) - `rsync` for cloud storage
- [](https://github.com/phiresky/ripgrep-all) - `ripgrep` for everything, PDF's, E-Books, Office Docs, Zips, etc
- [rust-stakeholder](https://github.com/giacomo-b/rust-stakeholder) - Generate impressive looking terminal output to look busy when the stakeholders are walking around for inspection
- [scc](https://github.com/boyter/scc) - Count your lines of code accurately and quickly
- [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts
- [sig](https://github.com/ynqa/sig) - Interactive grep for streamed data
- [skim](https://github.com/skim-rs/skim) - Fuzzy Finder written in Rust
- [sshs](https://github.com/quantumsheep/sshs) - TUI interface for SSH and SSH Config Connections
- [task](https://github.com/go-task/task) - A task runner / build tool written in Go, aims to be simpler then `make`
- [tealdeer](https://github.com/tealdeer-rs/tealdeer) - A rust implementation of `tldr`
- [tldr](https://github.com/tldr-pages/tldr) - Collaborative cheatsheets for console commands
- [tokei](https://github.com/XAMPPRocky/tokei) - Count your lines of code, quickly
- [tran](https://github.com/abdfnx/tran) - Securely transfer and send anything between computers with a TUI
- [typocia](https://github.com/bloznelis/typioca) - Cozy typing speed tester for terminals
- [ugm](https://github.com/ariasmn/ugm) - Terminal based UNIX user and group browser
- [xh](https://github.com/ducaale/xh) - Friendly and fast tool for sending HTTP requests
- [you-get](https://github.com/soimort/you-get) - Dumb downloader that scrapes the web
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - Feature rich command line audio/video downloader
- [zeit](https://github.com/mrusme/zeit) - Zeit, Erfassen, A command line tool for tracking time spent on activities

## Javascript Ecosystem

  *Javascript go brrrrr*

- [bun](https://github.com/oven-sh/bun) - A fast all-in-one JavaScript/TypeScript runtime written in Zig
- [deno](https://github.com/denoland/deno) - A runtime for JavaScript/TypeScript written in Rust
- [node](https://github.com/nodejs/node) - The Node.js JavaScript runtime
- [npm](https://github.com/npm) - The classic package manager for JavaScript
- [pnpm](https://github.com/pnpm/pnpm) - Fast, disk space efficient package manager
- [yarn](https://github.com/yarnpkg) - Fast ,reliable, and secure dependency management for JavaScript

## Cloud Tooling

 *When you think about it, its just someone else's computer, waaaaay over there..*

- [claws](https://github.com/clawscli/claws) - A TUI for AWS resource management feat vim-style navigation

## IRC

 *A simpler time then chat was just.. chat*

- [zuse](https://github.com/babycommando/zuse) - Clean IRC TUI written using bubbletea in Go

## Logging

 *Good logging is something of lifesaver, visualisation and parsing makes it even better*

- [angle-grinder](https://github.com/rcoh/angle-grinder) - Slice and dice logs on the command line
- [hl](https://github.com/pamburus/hl) - Fast and powerful log viewer, capable of processing JSON and logfmt logs
- [lazyjournal](https://github.com/Lifailon/lazyjournal) - A TUI for reading journald, auditd, file system and more logs with coloured output, filtering and timestamping
- [lnav](https://github.com/tstack/lnav) - Logfile navigator in C++
- [tailspin](https://github.com/bensadeh/tailspin) - Log file highlighter

## Backup Tooling

 *Slightly more effective then my_file_working_real_3_actual_working_fr.txt.doc*

- [restic](https://github.com/restic/restic) - Fast, secure, efficient backup program, making backups easy
