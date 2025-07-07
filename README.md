# Pix's Necronomicon of Software

This is inspired by the [awesome](https://github.com/sindresorhus/awesome) repos that have lead me to cool tools, so this is just my take on that, a list of awesome software I've found while passing through cyberspace

This list will likely have a cyber security lean just cause of my line of work, but will include anything I've found that I think is cool or useful.

Please send me cool tools to try! I'm always looking for more new awesome stuff to try!

## Indexing

- [Colorschemes](#my-favourite-colour-schemes)
- [Window Managers](#window-managers)
- [GUI](#gui-stuff)
- [Fonts](#fonts)

### My favourite Colour schemes

- [Umbral ( My own theme!)](https://github.com/pix-xip/umbral.nvim)
- [Catppuccin](https://catppuccin.com/)
- [Tokyonight](https://github.com/folke/tokyonight.nvim)
- [Shadotheme](https://github.com/Shadorain/shadotheme)
  
### Window Managers

#### Hyprland

My primary window manager, a hybrid tiling/floating compositor for Wayland.

#### Niri - experimental

Experimental window manager for me, this is a infinitely scaling horizontal
window manager for Wayland built in rust, I have found it to be good when
you only have a single small screen.

#### Aerospace

My primary window manager on Darwin systems, a hybrid filing/floating window
manager that doesn't require you to disable SIP like Yabai to get the same
window management goodness.

### GUI Stuff

`waybar`

- Utility Bar to fill with whatever on `wayland`.

`rofi`

- Launcher for programs and files

`wl-clipboard-history`

- Clipboard History on GUI

`swaybg`

- Backgrounds!

`swaylock`

- Lock your PC

`grim`

- Screenshots

`grimblast`

- Screenshot Utility specifically for Hyprland.

`sddm`

- Simple Desktop Display Manager - use for login etc.

`hyprpicker`

- Pick out colours easily!

`waybar-hyprland` `(-git)`

- Specific Waybar implementation for Hyprland.

`hyprpaper`

- Wallpapers on Hyprland!

`wl-clipboard`

- Clipboard manager for wayland!

`shotcut`

- Free video editing software similar to after effects.

`Alfred`

- Replacement for spotlight on crack for Mac.

`Raycast`

- Replacement for spotlight, commercially developed not community based

`ganttproject`

- An old school gantt project manager that still works well today.

`docker`

- Docker Desktop, for when you cbf writing docker run .....

`orbstack`

- Faster DockerDesktop, hooks docker as well as provides a way to launch
  vm's via `orb`

`rectangle`

- On top window manager that lets you snap to sides, corners, etc.

`obsidian`

- Markdown editor and renderer - decent for notes.

`bitwarden`

- Modern secure password vault / manager.

`keepassx`

- Older password vault

`tiger-vnc`

- Decent VNC client for when you need GUI remote access.

`skhd`

- Simple Hotkey Daemon, map any key to anything.

`sketchybar`

- Informational Bar configurable with `bash` or `lua`.

`cleanshot x` | `flameshot`

- Improved Screenshotting capabilities

`Hammerspoon`

- Configure and automate parts of your system with `lua`

-----------------

PIXTODO: Updoot this layout

### Fonts

  ttf-fira-code
  ttf-nerd-fonts-symbols-common
  otf-firamono-nerd
  inter-font
  otf-sora
  noto-fonts
  noto-fonts-emoji
  ttf-jetbrains-mono-nerd
  adobe-source-code-pro-fonts"

-----------------

### Shells

`fish` *

- `tide` prompt configuration
- `fisher` package manager

My personal choices:

```bash
jorgebucaran/fisher        # The Package Manager
patrickF1/fzf.fish         # FZF with hotkeys for fish.
decors/fish-colored-man    # Coloured man pages
danhper/fish-ssh-agent     # SSH agent using fish.
jorgebucaran/autopair.fish # Auto [] {} () etc.
ilancosman/tide@v6         # Async modern shell prompt.
meaningful-ooo/sponge      # Cleans up typos from history
pink-n-purple-pix          # My colourscheme

## Outdated / Not in use
catppuccin/fish            # Pastel theme (mocha)
rose-pine/fish             # SOHO vibes for commandline
```

`nushell`

- Overly complicated shell with impressive builtins for data handling

`zsh`

- Just improved bash :>

`bash`

- Your basic bitch find everywhere linux shell.

`ash`

- Stripped back alpine shell.

`dash`
The faster debian improved 'sh' usually what sh links to on machines.

-----------------

### Package Managers

`yay` (Arch)

- Pacman standin for AUR written in Go.

`paru` (Arch)

- Pacman standin for AUR with features, written in Rust

`brew` (All)

- General purpose but slower package manager written in Ruby

`nix` (All)

- Prebuilt, precached, declarative consistent packages.

`home-manager` (All)

- Manages your home directory and nix packages via config files.

-----------------

### Markdown

`glow` *

- Specific markdown viewer ( has a neovim plugin )

`gum format | pager`

- Using the shell beautifier that is gum to format markdown

-----------------

### Editors

`neovim`

```bash
# My Setup:
### Distribution Boostrap:
  `LazyVim` - Folkes Neovim Distribution. I run a customised version of this
### Pkg Manager:
  `lazy.nvim`
### Noteable Changes from LazyVim:
  `pix_plugins` - Just extra stuff I built and use
  `ftplugins` - Added a few extra for languages I use regularly.
  `nvim.lua/style` - Allow for a custom style setting at project roots
  `keybinds` - I use Colemak, changes are made to adjust for taht.
  `formatters` - Custom ones for C and Swift
  `LLM` - Experimental LM Studio Plugin for local AI Codegen
  `fish` - Added to make editing my shell easier
  
  ## Disabled:
  - neotree
  - mini.pairs
  - spectre
  - flit
  - LuaSnip
```

`neovide`

- A frontend GUI for neovim/vim. Has cute little animations and stuff.

`Sublime Text`

- Running a custom theme I made on MacOS.

`Zed`

- Interesting editor written in Rust, comes with built in LSP support.

-----------------

### Terminals

`ghostty` *

- Crossplatform - simple configuraition very fast Zig terminal

`wezterm` *

- Crossplatform - configurable with lua, GPU accelerated.

`foot` *

- Wayland specific terminal, quite fast!

`st`

- Compiled C terminal. Very Minimal

`alacritty`

- GPU accelerated like `wezterm`, text to screen go brr

`iterm2`

- Your classic basic mac terminal upgrade.

-----------------

### File Conversion

#### Swiss army knives

-----------------

`pandoc`

- For docs

`ffmpeg`

- For video

`sox`

- For audio

`blink` || `blink-emulator` && `blinkenlights`

- Smol virtual machine for running linux posix binaries.

-----------------

### Command Line Tools

{{

`eza` (`exa` is deprecated) *

- A replacement for `ls` with more options available.

`lla`

- A replacement for ls with more options, newish?

`erd` || `erdtree`

- Another `ls` replacement written in Rust.

`omm`

- TUI task manager, vim bindings, can be used to visualise changing priorities.

`zoxide` *

- A replacement for `cd`, faster, more options.

`atuin` *

- Fancy sync-able shell history, querieable with human language.

`z`

- Written in shell similar to `zoxide`

`pazi`

- More complex algo's then `zoxide` at the cost of performance.

`fasd`

- Another jumper! Making life easier.

`bat` *

- `cat` but with color and stuff

`fd` *

- Better `find`, easier syntax, generally faster.

`ripgrep` *

- `grep` but faster and better on large datasets

`jq` *

- Json terminal formatter, very very useful

`jqp`

- A TUI playground for `jq` lets you visualise and explore JSON objects.

`cyme`

- `lsusb` replacement, written in Rust

`rsync` *

- `cp` / `scp` replacement, often faster when copying repeatedly

`rclone`

- Sync files and folders with various cloud providers

`dd` *

- Disk management, `cp` replacement, disk utility Warning: Dangerous.

`gd`

- Bunch of cli tools for graphic manipulation.

`sd`

- Better `sed`, easier syntax

`sad` *

- Space Aged seD - kind of like `sd`, easier syntax, similar to `fastmod`

`fastmod` *

- For making large codebase changes across multiple files at once.

`croc` *

- Easily and securely send any file from computer to computer.

`rip` && `rm-improved` *

- A safer, more error friendly `rm`, allows for a graveyard.

`tokei` *

- Keeps track of the lines of code written in a project

`scc`

- Same as `tokei` fast code line counter, comments, blank lines etc.

`dust` *

- `du` with visual display

`duf` *

- `df` with visual display

`hunspell`

- Check the spelling of a file given an encoding.

`tealdeer || tldr` *

- `man` but a quick and dirty version

`task` || `go-task`

- A helpful CI tool for creating pipelines and auto builds.

`gaze`

- Similar to task, watches a directory for changes and runs commands

`curl cheat.sh/<thing>`

- A helpful cheatsheet about a topic, usually web tool related.

`procs` *

- A better, coloured and more easily searched `ps`

`gum` *

- General purpose library to improve your scripting with various
  functions (log, timer, loading..)

`mutt` || ``NeoMutt``

- Email! But in your terminal!

`navi`

- Quick Cheatsheets that let you autofill commands and run them.

`neofetch` *

- Show information about your computer, inactive.

`fastfetch`

- Shows information about your computer, active.

`onefetch`

- Like `neofetch` or `fastfetch` except for git repositories

`npm, pnpm, yarn, bun, etc..`

- The Javascript ecosystem...

`choose`

- Replacement for `cut`

`flex`

- Program for generating scanners for lexical pattern matching faster.

`dasel`

- `jq` like parser for JSON, YAML, TOML, etc

`bitwise`

- bit calculator with interactive setup

`fjira` *

- Command line Jira

`k9s`

- Kubernetes cluster management

`pingme` *

- Allows you to reach out to various services with a message

`await`

- Await things to be finished in the terminal

`glances`

- Kind of like a way more advance `top`

`htop` || `btop` *

- Better versions of top that keep its general concepts + extra

`gperf`

- Generates 'perfect' hash functions.

`nettle`

- Hashing CLI tool.

`mcfly`

- Rust powered, neural network enhanced shell history search

`botan`

- Cryptographic CLI tool for generating all sorts of fun.

`grex`

- Generates regex based on a user test case, hit and miss imo.

`hyperfine`

- benchmarks stuff based on conditions you pick and generate.

`iproute2mac` *

- `ip` commands on your mac, not all, but enough to make it comfy.

`shellcheck` *

- Make sure your scripts are written efficiently and without obvious pitfalls

`xxhash`

- hehe, hash go brrrr

`brotli`

- Compression and Decompression package. (Think tar kinda)

`pixz` *

- parallised `xz` so its faster.

`xz`
C Heavy compression tool, usually results in very small output

`7zip`

- Easy zip of files for people who dunno how to use tar.

`zstd`

- Competes with `xz` for compression, but always has faster Decompression

`gzip`

- Faster compression tool, but will not result in as small of a output.

`bear` *

- Generates compile_commands.json files for Clangd and some other LSPs

`bp` *

- 'better paste' - optimal for chaining with pipes

`clipboard`

- Would you like a copy paste buffer on crack?

`dos2unix`

- Remove pesky `\r\n` from files coming from windows to unix

`curlie`

- Easy to use curl based off `httpie`

`httpie`

- An easy way to test your API with requests from command line

`lnav` *

- Extremely fast log viewer in C++. Tutorial at `ssh tutorial1@gdemo.lnav.org`

`angle-grinder` *

- Logfile analysis tool with builtin manipulations, could replace `cat grep` etc.

`ran`

- Simple file server in Go, good for local lan passing things

`yq`

- `jq` but for YAML

`pueue`

- Long running task manager with concurrency

`rga`

- `ripgrep` extended to include PDF, tar, sqlite and other documents when searching

`noti`

- Get yourself some notifications when things are done

`ctop`

- `top` for running containers from something like `docker`

`fzy`

- A potentially faster then `fzf` fuzzy finder

`hexyl` *

- A modern newer hex viewer

`hevi`

- Yet another `xxd` clone

`skim`

- `fzf` in rust

`you-get`

- Download videos from youtube

`map`

- Map commands out of stdin

`natls`

- Another `ls` replacement written in `rust`

`wfh`

- Synchronise folders between machines with `rsync` and dir watching

`got` *

- A fast downploader for the commandline in GO

`axel` *

- Download anything at the speed of threads

`ugm`

- A TUI for viewing information about UNIX users and groups.

`tailspin` || `tspin` *

- A log file highlighter in Rust, can be used as a drop in for `less` and `tail`

`keyb`

- A selfmade cheatsheet for keybindings with fuzzy lookup

`sttr`

- A tool for performing string manipulation from the command line

`superfile` || `spf`

- A file manager in your terminal

`yazi` *

- A *blazingly* fast TUI file manager with plugins!

`hwatch`

- Alternative of the `watch` command, keeps track of command execution
  and changes etc.

`dblab`

- Cmdline database interactive TUI, supports 5 different db's

`mdtt`

- Markdown table editor with `vim` like keybinds, good if you use alot
  of `markdown` tables.

`jnv`

- Interative JSON viewer that executes `jq` queries to filter.

`lemmeknow`

- Identifies strings through signature detection.

`mprocs`

- Run multiple proccesses in parallel, seems like it could be good for
  hot reload ++ server listening

`typocia`

- Cozy little terminal typer, lets you practice so you to can be Blazingly Fast!~

`sig`

- Interactive grep, good over streamed data, such as websocket outputs.

`diskonaut`

- Treemap style viewer of your filesystem.

`pastel`

- Generate, convert and manipulate colours and colourcodes!

`ghq`

- A go tool for managing git repositories.

`gdu`

- Go Disk Usage, little TUI for seeing where your disk has been filled up.

`ouch`

- Obvious Unified Compression Helper! A tool for doing all sorts of compression
  and detection.

`atop`

- TUI for linux performance monitoring.

`jless`

- JSON viewer written in rust.

`jqp`

- Playground for interacting with `jq` and seeing what commands do in realtime.

`sshs`

- TUI for SSH sessions, using your ssh config, useful for those one
  off ones you forget, or if you need to figure out an ip quickly.

`yt-dlp`

- Youtube downloader with extended features and other uses.

`zeit`

- Time tracker for your terminal :>

`clx` || `circumflex`

- Hacker news browser in your terminal.

`dua` || `dua-cli`

- Interactive TUI for seeing space used by files on system.

`dive`

- Tool for going through `docker` containers.

`nemu`

- Basic TUI for managing `qemu` vm's

`cotp`

- Terminal tool for managing OTP's

`tran`

- Send files to other computers with a nice TUI.

`portal`

- Another way to send files via a relay system, similar to `croc`

`goji`

- Format commit messages using emojis and such.

`miller`

- A multi-purpose parser for TOML, YAML, JSON, CSV etc.

`nomino`

- Batch renamer from the command line with some extra formatting.

`lazyjournal`

- Inspired by `lazydocker` and `jazygit` except for systemd/journald output.

`nvrs`

- Fast version checker for software new releases

`dyff`

- Diff tool for YAML and JSON files

`pgtree`

- Process hierachy tree for specific running processes.

`logmerger`

- Written in python, allows viewing of multiple logs at the
  same time, in time series order.

`hostctl`

- Tool for managing hostfile configuration, designed for devs who swap between
  alot of host confs, allowing for profiles etc of '/etc/hosts'

`pillager`

- Filesystem scanner for sensitive info, based off gitleaks and others

`pdu`

- Like `dust` and `du`, lets you see disk usage.

`xh`

- Drop in replacement for `curl` written in Rust, with some fancy colours, json work,
  and general manipulation of HTTP requests.

`cod` *

- Generate autocompletes based off running `--help` for your shell.

`rust-stakeholder`

- Fill your screen with all sorts of jargon and nonsense to impress the shareholders!

}}

-----------------

### CLI Network Utilities

{{

`netcat` *

- The network swiss army knife

`rcat`

- Netcat but in rust

`ssh-para`

- Parallel SSH job runner with interactive CLI, good output.

`tcpdump` *

- best way to view your network data in command line

`impala`

- TUI Wifi network manaagement for Linux

`trippy` *

- A network diagnostics tool

`sntop`

- uses fping to determine connectivity of hosts based on a config file.

`bmon`

- A network monitoring tool!

`cidr`

- Classless Inter-Domain Routindg tool for performing various actions on,
  around and about them.

`bandwhich` *

- Watch what proccesses are using bandwidth, how many connections etc.

`zerotier-one` *

- Build your own network anywhere, connect to anything.

`dog` *

- A more friendly version of `dig`

`hping3` *

- Would you like to DOS something? Wanna do it again?

`unbound`

- recursive, validating and caching dns resolver (daemon version)

`rustscan`

- `nmap` written in `rust` run from `docker` usually

`doggo`

- DNS client similar to `dog` or `dig`

`stu`

- CLI AWS S3 interactive tool

`updo`

- Monitor the uptime of the various websites with alerts and metrics

`havn`

- Port scanner similar to `nmap` with some decent defaults.

`eget`

- Kind of like a package manager for github, allows installing of simple
  already compiled binaries. ( Use at your own risk for obvious reasons. )

`tufw`

- TUI for `ufw` firewall, allows visualisation of your rules while making changes
`wg-cmd`

- Wireguard TUI for managing connections.

`pvw`

- Port viewer TUI written in Go.

`tcpterm`

- TUI for `tcpdump`

}}

-----------------

### Debugging

`gdb` *

- The tried and true debugger most commonly associated with C

`dlv` *

- Debugger specifically for `go`, has knowledge of the runtime, allows for
  great in depth inspection

`heretek`

- Another wrapper for GDB without the python dependency, a TUI.

`cgdb` *

- GDB featuring a split view that shows source code among other things.

### Version Control

`lazygit` *

- TUI style git client.

`jujutsu` || `jj` *

- Combines the features of git, mercurial and extras into one system.

`gitui`

- TUI style git client - faster then lazygit according to benchmarks with less crashes

`svn`

- Mercurial based version control system

`gh`

- Interact specifically with github, makes pr and stuff much quicker then by hand.

`gh-dash`

- Dashboard for `gh` written in Go  

`git-flow`

- Way overengineered form of git management with branches out the wazoo.

`git-leaks` *

- Looks through repos for obvious leaks like passwords or creds or api-keys

`delta`

- Smarter `diff` with colour, dual layouts and closer to Sublime Merge style

`icdiff`

- Smarter `diff` with colour and dual layouts, easier to read.

#### Version Management (GUI)

`Sublime Merge` *

- Fantastic git manager, makes merges very simple

`git-kraken`

- Alternative to the above, preference thing.

-----------------

### Build Systems

`meson` *

- Easier Cmake using ninja as a backend.

`cmake`

- The better version of make, though its a pain

`ninja`

- Cmake replacement build system.

`make`

- The precursor to cmake.

`pixbuild` || `remake` *

- Pix's very own build system, written in C, configured via lua.

`zig` *

- Turns out zig builds compiler is actually pretty fancy

### Development Libraries

`libevent`

- Heard you wanted massive async socket connections.

`libconfig`

- Standardised C config reader

`hiredis`

- Redis in your C what joy

`coreutils`

- Standard C building blocks, you should know / use these.

`xxhash`

- hehe, hash go brrrr

`mimalloc`

- Microsofts better implementatino of the standard library malloc.

`jemalloc`

- emphasis on no framgmentation and concurrency support

`stb`

- I like to make use of the header only libraries

`pix.h`

- My own STB style header that has a bunch of my ever growing stuff

-----------------

### Languages

`C`

- Need I say more.

`go`

- C with training wheels, meaning you can just go really fast all the time.

`Odin`

- C with QoL out of the box and less ambiguous behaviour

`zig`

- Systems level language competitive with C and C++

`lua`

- Configuration for `neovim` and `wezterm`, small scripting language with `C` integration.

`Swift`

- Apples dynamic everything GPL. Cross compat with C.

`C++`

- You know, C with extra bloat. x(

`Python`

- For when you really need 500 ways to do the same thing badly

`bash`

- Yes its a language, bite me. Get good at it.

`fish`

- Like bash, but if you use that shell, handy to know. (not posix compliant)

`C#`

- Microsoft flavour Java, good for distributed systems in my experience

`perl` || `raku`

- If you really just need to golf something..

`haskell`

- Cause everyone needs to try functional programming at least once.

-----------------

### Databases && Tools

This is honestly a massive weak point for me, so here is just some basic
stuff I've used and enjoy

-----------------

`sqlite`

- Everyone's favourite flat-file works with anything database

`surealdb`

- A multi model database using what I think is a document system?

`manticore`

- C++ Elastic Search esque document data base.

`gobang`

- TUI for interacting with various databases.

-----------------

### AI Backed Tooling

Tools that in some way rely on or integrate AI specifically.

`smartcat`

- Its `cat` but integrates with ollama etc, does a buncha stuff.

``Warp``

- Mac only, proprietary... integrated AI. Am Sus of it tbqh

`tgpt`

- Terminal chat gpt without api keys?
