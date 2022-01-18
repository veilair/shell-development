# Shell Development
> Welcome to the world of Shell Development. An ongoing curated list of frameworks, books, articles, talks, screencasts, recordings, libraries, learning tutorials and resources about Shell Development. Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.

## Table of Contents

- [Shells](#shells)
- [Command-Line Productivity](#command-line-productivity)
  - [Directory Navigation](#directory-navigation)
- [Customization](#customization)
- [For Developers](#for-developers)
- [System Utilities](#system-utilities)
- [Downloading and Serving](#downloading-and-serving)
- [Multimedia and File Formats](#multimedia-and-file-formats)
- [Applications](#applications)
- [Games](#games)
- [Shell Package Management](#shell-package-management)
- [Shell Script Development](#shell-script-development)
- [Guides](#guides)
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [Other Awesome Lists](#other-awesome-lists)
- [Web Links](#web-links)

## `Shells`

*Choose your base shell.*

* [bash](https://www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
* [elvish](https://elv.sh/) - Friendly, expressive shell features like anonymous functions and data structures
* [es](https://wryun.github.io/es-shell/) - The extensible shell, based on Plan 9's [rc](https://github.com/rakitzis/rc) shell
* [fish](https://fishshell.com) - Smart and user-friendly command line shell
* [ion](https://github.com/redox-os/ion) - A modern system shell that features a simple, yet powerful, syntax. It is written entirely in Rust.
* [ksh93](https://github.com/att/ast) - Korn Shell
* [mksh](https://github.com/MirBSD/mksh) - MirBSD Korn Shell
* [ngs](https://github.com/ngs-lang/ngs) - Fully featured scripting language created specifically for Ops. REPL is being developed.
* [nushell](https://github.com/nushell/nushell) - A modern shell written in Rust
* [oksh](https://github.com/ibara/oksh) - Portable OpenBSD ksh
* [osh](https://www.oilshell.org) - Bash compatible, with new/modern Unix shell language called Oil
* [pdksh](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public domain Korn shell
* [powershell](https://docs.microsoft.com/en-us/powershell/scripting/overview) a cross-platform task automation and configuration management framework, consisting of a command-line shell and scripting language
* [shell++](https://github.com/alexst07/shell-plus-plus) - Friendly and modern functional and object oriented shell script language
* [shenv](https://github.com/shenv/shenv) - Simple shell version management
* [tcsh](https://www.tcsh.org/) - C shell with file name completion and command line editing
* [xonsh](https://xon.sh) - Python-ish, BASHwards-looking shell language and command prompt
* [yash](https://yash.osdn.jp/) - A POSIX-compliant command line shell with built-in support for completion and prediction based on command history
* [zsh](https://www.zsh.org) - Powerful shell with scripting language

## `Command-Line Productivity`

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* [AdvancedNewFile](https://github.com/tanrax/terminal-AdvancedNewFile) - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin.
* [ag](https://github.com/ggreer/the_silver_searcher) - Super fast string search through a directory hierarchy
* [aliases](https://github.com/sebglazebrook/aliases) - Contextual, dynamic, organized aliases for bash
* [autoenv](https://github.com/inishchith/autoenv) - Directory-based environments
* [bashhub](https://github.com/rcaloras/bashhub-client) - :cloud: Bash history in the cloud. Indexed and searchable.
* [boilr](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates.
* [boom](https://github.com/holman/boom) - Store links and snippets in the command line
* [borg](https://github.com/ok-borg/borg) - A terminal based search engine for bash commands
* [browsh](https://github.com/browsh-org/browsh) - The modern text-based browser
* [Buku](https://github.com/jarun/Buku) - Powerful command-line bookmark manager
* [byobu](https://www.byobu.org) - Text-based window manager and terminal multiplexer
* [cod](https://github.com/dim-an/cod) — A completion daemon for shell that learns when you invoke `--help` commands
* [CloudClip](https://github.com/skywind3000/CloudClip) - Your own clipboard in the cloud, copy and paste text with gist between different systems
* [ddgr](https://github.com/jarun/ddgr) - DuckDuckGo from the terminal
* [desk](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell
* [direnv](https://github.com/direnv/direnv) - An environment switcher for the shell, compare with autoenv
* [dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync and web interface
* [eureka](https://github.com/simeg/eureka/) - :bulb: CLI tool to input and store your ideas without leaving the terminal
* [fasd](https://github.com/clvv/fasd) - Command-line productivity booster, offers quick access to files and directories
* [fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to find.
* [foxy](https://github.com/s-p-k/foxy) - Plain text bookmarks for Firefox and surf browsers.
* [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries.
* [funky](https://github.com/bbugyi200/funky) - Extends functionality of shell functions making them more powerful and flexible.
* [fz](https://github.com/changyuheng/fz) - Seamless fuzzy tab completion for z
* [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder
* [gitmux](https://github.com/arl/gitmux) - Show Git status in Tmux status bar
* [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal
* [googlr](https://github.com/Astranno/googlr) - Command line tool that lets you search Google from your terminal.
* [has](https://github.com/kdabir/has) - `has` helps you check presence of various command line tools and their versions on path
* [how2](https://github.com/santinic/how2) - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language.
* [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) - Colorize words in a command output
* [hr](https://github.com/LuRsT/hr) - `<hr />` for your terminal
* [hss](https://github.com/six-ddc/hss) - An interactive parallel ssh client featuring autocomplete and asynchronous execution
* [hstr](https://github.com/dvorka/hstr) - Bash History Suggest Box
* [k](https://github.com/supercrabtree/k) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates
* [k alias](https://github.com/lingtalfi/k) - get kool aliases (and more) working with a simple one-liner
* [lf.sh](https://github.com/suewonjp/lf.sh) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc)
* [Lmod](https://lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
* [loop](https://github.com/Miserlou/Loop) - Write and control complex loops with as one-liners
* [marker](https://github.com/pindexis/marker) - Bookmark your shell commands
* [mackup](https://github.com/lra/mackup/) - Keep your application settings in sync (OS X/Linux)
* [mcfly](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scot!
* [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
* [nnn](https://github.com/jarun/nnn) - File browser and disk usage analyzer with excellent desktop integration
* [parallel](https://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* [pass](https://www.passwordstore.org/) - Manage passwords from the command line with GPG encryption and optional git integration.
* [pathpicker](https://github.com/facebook/PathPicker) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command.
* [pdd](https://github.com/jarun/pdd) - Tiny date, time diff calculator with timers
* [percol](https://github.com/mooz/percol) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell
* [q](https://github.com/cal2195/q) - Vim like macro registers for your Bash and Zsh Shell
* [qfc](https://github.com/pindexis/qfc) - File-completion widget for Bash and Zsh
* [resh](https://github.com/curusarn/resh) - Contextual shell history for Zsh and Bash
* [rg](https://github.com/BurntSushi/ripgrep) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep
* [screen](https://www.gnu.org/software/screen/) - GNU terminal multiplexer
* [shell-history](https://github.com/pawamoy/shell-history) - Visualize your shell usage with Highcharts
* [SHML](https://github.com/odb/shml) - Style framework for the terminal (Shell Markup Language)
* [slugify](https://github.com/benlinton/slugify) - Command that converts filenames and directories to a web friendly format
* [sman](https://github.com/tokozedg/sman) - :bug: A command-line snippet manager
* [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ in your shell
* [spark.fish](https://github.com/jorgebucaran/spark.fish) - ▁▂▃▅ Sparkline Generator
* [sheet](https://github.com/oscardelben/sheet) -  Text snippets for the command line
* [spot](https://github.com/rauchg/spot) - Tiny file search utility
- [snips](https://github.com/srijanshetty/snips) - Command line tool to manage snippets of code.
* [sqlline](https://github.com/julianhyde/sqlline) - Shell for issuing SQL to relational databases via JDBC (multiline, completion, highlighting, dialect support)
* [sshfs](https://github.com/osxfuse/sshfs) - A tool for mounting remote file systems over SSH
* [sudocabulary](https://github.com/badarsh2/Sudocabulary) - Learn English Vocabulary from your terminal
* [surfraw](https://gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
* [task-manager](https://github.com/lingtalfi/task-manager) - Execute all your scripts with just two or three keystrokes.
* [td-cli](https://github.com/darrikonn/td-cli) - A todo command line manager to organize and manage your todos across multiple projects.
* [thefuck](https://github.com/nvbn/thefuck) - Fix common shell mistakes by using an easy to remember command
* [tldr](https://github.com/raylee/tldr-sh-client) - A fully-functional bash client for tldr, simplified and community-driven man pages
* [tmux](https://tmux.github.io/) - Amazing terminal multiplexer
* [undollar](https://github.com/xtyrrell/undollar) - undollar bites the dollar sign off the tip of the command you just pasted into your terminal
* [usql](https://github.com/xo/usql) - Universal command-line interface for SQL databases.
* [v](https://github.com/rupa/v) - z for vim.
* [wemux](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy
* [xiki](https://xiki.org) - Makes the shell console more friendly and powerful
* [xplr](https://github.com/sayanarijit/xplr) -  A hackable, minimal, fast TUI file explorer
* [xsv](https://github.com/BurntSushi/xsv) - a fast CSV command line toolkit written in Rust
* [xxh](https://github.com/xxh/xxh) - Bring your favorite shell wherever you go through the SSH.

### `Directory Navigation`

* [aliasme](https://github.com/Jintin/aliasme) - alias helper to change directory quickly
* [autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line
* [bashmarks](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell
* [bd](https://github.com/vigneshwaranr/bd) - Quickly go back to a parent directory
* [commacd](https://github.com/shyiko/commacd) - A faster way to move around in Bash
* [enhancd](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with an interactive filter
* [goto](https://github.com/iridakos/goto) - A shell utility for navigation to aliased directories supporting auto-completion
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate your file system faster by learning your habits.
* [lazy-cd](https://github.com/pedramamini/lazy-cd) - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion.
* [up](https://github.com/shannonmoeller/up) - Ascend directories by name or count; for bash, zsh, and fish.
* [z](https://github.com/rupa/z) - z is the new j, yo
* [z.lua](https://github.com/skywind3000/z.lua) - A new cd command that helps you navigate faster by learning your habits
* [zoxide](https://github.com/ajeetdsouza/zoxide) - A faster way to navigate your filesystem, written in Rust
* [zpyi](https://github.com/sakshamsharma/zpyi) - Python in Zsh - Easy python scripting in shell

## `Customization`

*Custom prompts, color themes, etc.*

* [base16-builder](https://github.com/base16-builder/base16-builder) - Base16-Builder
* [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) - Powerful prompt with screen, tmux, git support and many more
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy Bash prompt for Git users
* [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script
* [bashstrap](https://github.com/barryclark/bashstrap) - A quick way to spruce up OSX terminal
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train.zsh) - :bullettrain_side: An oh-my-zsh shell theme based on the Powerline Vim plugin
* [emojify](https://github.com/mrowa44/emojify) Emoji on the command line :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* [git-prompt](https://github.com/lvv/git-prompt) - Bash prompt with Git, SVN and HG modules
* [gittify](https://github.com/momeni/gittify) - A colorful Bash prompt + customized Git aliases
* [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) -  Colorization for mysql comand-line client
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated git prompt for bash and zsh
* [polyglot](https://github.com/agkozak/polyglot) - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, dash, and busybox sh
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - Super flexible awesome powerline ZSH theme
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, Git statuses, and Git branches
* [starship](https://starship.rs/) - Fast, customisable, cross-shell prompt written in rust
* [synth-shell](https://github.com/andresgongora/synth-shell) - Greeter with a customizable status report and a fancy bash prompt

## `For Developers`

*Command-line development, version control, and deployment.*

* [ack](https://beyondgrep.com/) - A grep-like search tool optimized for source code.
* [add-gitignore](https://github.com/TejasQ/add-gitignore) - Interactive CLI that generates a .gitignore for your project based on your needs.
* [bcal](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations
* [bitwise](https://github.com/mellowcandle/bitwise) - Terminal based interactive bit manipulator in curses.
* [bocker](https://github.com/p8952/bocker) - Docker implemented in 100 lines of bash
* [cloc](https://github.com/AlDanial/cloc) - Count Lines of Code
* [doclt](https://github.com/omgimanerd/doclt) - A command line interface to Digital Ocean
* [dokku](https://github.com/dokku/dokku) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.
* [getopts.fish](https://github.com/jorgebucaran/getopts.fish) - CLI parser for fish
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` taking advantage of fuzzy finder fzf.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more.
* [git-extras](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more
* [git-open](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser
* [git-quick-stats](https://github.com/arzzen/git-quick-stats) - Git quick statistics is a simple and efficient way to access various statistics in git repository.
* [git-semver](https://github.com/markchalloner/git-semver) - Git plugin for easing semantic versioning and changelog validation
* [git-sh](https://github.com/rtomayko/git-sh) - A customized Bash environment suitable for Git work
* [gita](https://github.com/nosarthur/gita) - A command-line tool to manage multiple git repos.
* [hub](https://github.com/github/hub) - hub helps you win at git.
* [just](https://github.com/casey/just) - Task runner for saving and running project-specific commands.
* [licins](https://github.com/dogoncouch/licins) - Insert commented software licenses into source code.
* [mkdkr](https://github.com/rosineygp/mkdkr) - Makefile + Docker = CI Pipeline
* [mr](https://myrepos.branchable.com) - Multiple Repository management tool
* [overcommit](https://github.com/sds/overcommit) - A fully configurable and extendable Git hook manager
* [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* [rebound](https://github.com/shobrook/rebound) - Instantly browse Stack Overflow results in your terminal when you get a compiler error
* [repren](https://github.com/jlevy/repren) - Command-line search-and-replace and file-renaming swiss army knife
* [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor that runs on Node.js
* [shipit](https://github.com/sapegin/shipit) - Minimalistic SSH deployment
* [starring](https://github.com/ritz078/starring) - Automatically star the npm-packages that you are using on GitHub.
* [tag](https://github.com/aykamko/tag) - Instantly jump to your ag matches.
* [wipe-modules](https://github.com/bntzio/wipe-modules) - A little agent that removes the node_modules folder of non-active projects

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* [bat](https://github.com/sharkdp/bat) - A `cat` clone with wings
* [bmon](https://github.com/tgraf/bmon) - Real-time network bandwidth monitor and rate estimator with human-friendly visual output
* [bpytop](https://github.com/aristocratos/bpytop) - Linux/OSX/FreeBSD resource monitor
* [catcli](https://github.com/deadc0de6/catcli) -  The command line catalog tool for your offline data
* [ccat](https://github.com/owenthereal/ccat) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting.
* [exa](https://github.com/ogham/exa) - A modern version of `ls`.
* [progress](https://github.com/Xfennec/progress) - Linux tool to show progress for `cp`, `rm`, `dd`, and more...
* [stronghold](https://github.com/alichtman/stronghold) - Easily configure MacOS security settings from the terminal.
* [glances](https://github.com/nicolargo/glances) - Glances an Eye on your system
* [goaccess](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems.
* [hblock](https://github.com/hectorm/hblock) - Hosts-file based adblocker
* [histstat](https://github.com/vesche/histstat) - History for netstat
* [htop](https://github.com/hishamhm/htop) - A ncurses based interactive process viewer which aims to be a better `top`
* [lnav](https://lnav.org) - An advanced log file viewer for the small-scale
* [logdissect](https://github.com/dogoncouch/logdissect) - CLI utility and Python API for analyzing log files and other data.
* [ls++](https://github.com/trapd00r/ls--) - Colorized ls on steroids
* [lsp](https://github.com/dborzov/lsp) - An improved `ls`, with file descriptions in plain language and intelligent file grouping
* [maza](https://github.com/tanrax/maza-ad-blocking) - Local ad blocker. Like Pi-hole but local and using your operating system.
* [mtr](https://github.com/traviscross/mtr) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage
* [nmtui](https://github.com/NetworkManager/NetworkManager) - Text User Interface for controlling NetworkManager
* [powertop](https://github.com/fenrus75/powertop) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options.
* [prettyping](https://github.com/denilsonsa/prettyping) - Making the output of `ping` prettier, more colorful, more compact, and easier to read.
* [procdog](https://github.com/jlevy/procdog) - Lightweight command-line control of long-lived processes like servers
* [quick-secure](https://github.com/marshyski/quick-secure) - Quickly secure and harden UNIX/Linux systems
* [rng](https://github.com/nickolasburr/rng) - Copy range of lines from file or stdin to stdout.
* [wifi-wand](https://github.com/keithrbennett/wifiwand) - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`)
* [xiringuito](https://github.com/ivanilves/xiringuito) - SSH-based "VPN for poors"

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* [aria2](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink
* [balls](https://github.com/jneen/balls) - Bash on Balls
* [bashttpd](https://github.com/avleen/bashttpd) - A web server written in Bash
* [bashhub-server](https://github.com/nicksherron/bashhub-server) - Private cloud shell history. Open source server for bashhub
* [bitpocket](https://github.com/sickill/bitpocket) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion"
* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox
* [httpie](https://github.com/httpie/httpie) - HTTPie is a command line HTTP client, a user-friendly cURL replacement
* [HTTPLab](https://github.com/gchaincl/httplab) - The interactive web server, let you inspect HTTP requests and forge responses.
* [ngincat](https://github.com/jaburns/ngincat) - Tiny Bash HTTP server using netcat
* [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines
* [shell2http](https://github.com/msoap/shell2http) - HTTP-server to execute shell commands. Designed for development, prototyping or remote control
* [vesper](https://github.com/chris-rock/vesper) - 🍸Vesper is a HTTP framework for Bash/Unix Shell
* [xh](https://github.com/ducaale/xh) - Friendly and fast tool for sending HTTP requests
* [youtube-dl](https://yt-dl.org/) - Small command-line program to download videos from YouTube.com and other video sites

## Multimedia and File Formats

*Tools for handling video and audio files.*

* [adb-export](https://github.com/sromku/adb-export) - Export Android content providers to CSV format
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux
* [Beets](https://github.com/beetbox/beets) - Music library manager and MusicBrainz tagger
* [cmus](https://github.com/cmus/cmus) - Cross-platform cli audio player.
* [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to [jq](https://github.com/stedolan/jq) / [yq](https://github.com/kislyuk/yq) but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* [fx](https://github.com/antonmedv/fx) - Command-line JSON processing tool by anononymus JavaScript functions
* [gifgen](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding
* [image-scraper](https://github.com/sananth12/ImageScraper) - A cool command line image scraper with a lot of features.
* [imgp](https://github.com/jarun/imgp) - Blazing fast batch image resizer and rotator
* [jo](https://github.com/jpmens/jo) - A small utility to create JSON objects from command-line arguments.
* [jq](https://github.com/stedolan/jq) - Sed for json data. You can use it to slice and filter and map and transform structured data
* [korkut](https://github.com/oguzhaninan/korkut) - Quick and simple image processing at the command line.
* [mpv](https://mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* [nehm](https://github.com/bogem/nehm) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way
* [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device
* [sejda](https://github.com/torakiki/sejda/) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc)
* [visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for exploring and arranging data (csv/json/xml/xls/yaml/etc)
* [xidel](https://github.com/benibela/xidel/) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery.
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.
* [yq](https://github.com/mikefarah/yq) - yq is a portable command-line YAML processor

## Applications

*Command line-based applications or command line access to existing services.*

* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols
* [awless](https://github.com/wallix/awless) - A powerful, innovative and small surface CLI to manage AWS.
* [bashblog](https://github.com/cfenollosa/bashblog) - A Bash script that handles blog posting
* [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - 🎨 Beautiful images of your code — from right inside your terminal.
* [choosealicense-cli](https://github.com/lord63/choosealicense-cli) - Choose an OSS license from the comfort of your terminal
* [cointop](https://github.com/miguelmota/cointop) - The fastest and most interactive terminal based UI application for tracking cryptocurrencies
* [dstask](https://github.com/naggie/dstask) - Single binary terminal-based TODO manager with git-based sync + markdown notes per task
* [editly](https://github.com/mifi/editly) - Command line video editor
* [facebook-cli](https://github.com/specious/facebook-cli) - Facebook command line tool
* [fanyi](https://github.com/afc163/fanyi) - Translate English to Chinese in terminal
* [gcalcli](https://github.com/insanum/gcalcli) - Google Calendar command line interface
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) - Command line evernote client
* [haxor-news](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor
* [hn-cli](https://github.com/rafaelrinaldi/hn-cli) - Browse Hacker News from the comfort of your Terminal
* [iponmap](https://github.com/nogizhopaboroda/iponmap) - Draw point on world map using ip address
* [isitup](https://github.com/lord63/isitup) - Check whether a website is up or down
* [jrnl](https://github.com/jrnl-org/jrnl) - A simple command line journal application that stores your journal in a plain text file
* [kanban.bash](https://github.com/coderofsalvation/kanban.bash) - commandline asciii kanban board for minimalist productivity bash hackers (csv-based)
* [ledger](https://github.com/ledger/ledger) - Command line accounting
* [licen](https://github.com/lord63/licen) - Generate your license. Yet another lice, but implement with Jinja2 and docopt
* [md2png](https://github.com/weaming/md2png) - Convert markdown to PNG image
* [moviemon](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line.
* [nomino](https://github.com/yaa110/nomino) - Batch rename utility using regex, sort and map file options.
* [pcalc](https://github.com/alt-romes/programmer-calculator) - Calculator made for programmers working with multiple number representations, sizes, and overall close to the bits.
* [pockyt](https://github.com/achembarpu/pockyt) - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection.
* [pushblast](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - Bash interface to the PushBullet API
* [ranger](https://github.com/ranger/ranger) - A console file manager with VI key bindings.
* [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal
* [SAWS](https://github.com/donnemartin/saws) - A Supercharged AWS CLI
* [taskbook](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat
* [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager
* [terjira](https://github.com/keepcosmos/terjira) - Command line power tool for Jira
* [ticker](https://github.com/achannarasappa/ticker) — Terminal stock ticker with live updates and position tracking
* [transfer.sh](https://transfer.sh/) — Quickly upload and share files from your shell
* [vl](https://github.com/ellisonleao/vl) - URL link checker on text documents
* [wego](https://github.com/schachmat/wego) - Weather app for the terminal
* [whales](https://github.com/Gueils/whales) - A tool to automatically dockerize your applications
* [whereami](https://github.com/rafaelrinaldi/whereami) - Get your geolocation information from the CLI
* [wttr.in](https://github.com/chubin/wttr.in) - :partly_sunny: The right way to check the weather (curl wttr.in)

## Games

*All work and no play is a cruddy way to spend your day.*

* [bash2048](https://github.com/mydzor/bash2048) - Bash implementation of 2048 game
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - Bash implementation of minesweeper
* [nudoku](https://github.com/jubalh/nudoku) - ncurses based sudoku game written in C
* [piu-piu](https://github.com/vaniacer/piu-piu-SH) - Horizontal scroller game in bash with multiplayer mode!
* [sedtris](https://github.com/uuner/sedtris) - Tetris in sed
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) - Arkanoid and Sokoban written using sed
* [SHTAP](https://notimetoplay.org/engines/shtap/) - Reusable text adventure engine for Bash 4
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) - Play solitaire in your terminal!

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* [bash-it](https://github.com/Bash-it/bash-it) - A community Bash framework
* [basher](https://github.com/basherpm/basher) - A package manager for shell scripts
* [bashing](https://github.com/xsc/bashing) - Smashing Bash into Pieces
* [bpkg](https://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere
* [dotfiler](https://github.com/svetlyak40wt/dotfiler) – Shell agnostic git based dotfiles package manager, written in Python.
* [fresh](https://github.com/freshshell/fresh) - Keep your dotfiles fresh
* [homeshick](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash
* [shallow-backup](https://github.com/alichtman/shallow-backup) - Easily create lightweight documentation of installed packages, dotfiles, and more
* [shundle](https://github.com/javier-lopez/shundle) - Plugin manager for shell scripts
* [vcsh](https://github.com/RichiH/vcsh) - Config manager based on Git
* [yadm](https://yadm.io/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* [ansi](https://github.com/fidian/ansi) - ANSI escape codes in pure bash - change text color, position the cursor, much more
* [assert.sh](https://github.com/lehmannro/assert.sh) - Bash unit testing framework
* [bashew](https://github.com/pforret/bashew) - bash script creator - from small stand-alone script to complex projects with CI/CD and testing
* [bashful](https://github.com/jmcantrell/bashful) - A collection of libraries to simplify writing Bash scripts
* [Bashlets](https://github.com/reale/bashlets) - A modular extensible toolbox for Bash
* [bashmanager](https://github.com/lingtalfi/bashmanager) - mini bash framework for creating command line tools
* [bashwithnails](https://github.com/mindaugasbarysas/bashwithnails) - a Bash framework written just for fun with testing, dependency management & packaging
* [bash-language-server](https://github.com/bash-lsp/bash-language-server) - [LSP](https://microsoft.github.io/language-server-protocol/)-based Bash language server
* [bash-modules](https://github.com/vlisivka/bash-modules) - functions for developing with [unofficial strict mode](http://redsymbol.net/articles/unofficial-bash-strict-mode/) enabled. 
* [bats](https://github.com/bats-core/bats-core) - Bash Automated Testing System
* [crash](https://github.com/molovo/crash) - Proper error handling, exceptions and try/catch for ZSH
* [critic.sh](https://github.com/Checksum/critic.sh) - Dead simple testing framework for Bash with coverage reporting
* [esh](https://github.com/jirutka/esh) - A simple templating engine based on shell, implemented in ~290 lines of POSIX shell and awk.
* [Fishtape](https://github.com/jorgebucaran/fishtape) - TAP producer and test harness for fish
* [composure](https://github.com/erichs/composure) - Compose, document, version and organize your shell functions
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - A command line argument parser in 50 lines of portable shell script.
* [getoptions](https://github.com/ko1nksm/getoptions) - An elegant option parser for shell scripts (sh, bash and all POSIX shells)
* [is.sh](https://github.com/qzb/is.sh) - An alternative for builtin test command, it will make your "if" statements pretty
* [lumberjack](https://github.com/molovo/lumberjack) - A logging interface for shell scripts
* [mo](https://github.com/tests-always-included/mo) - Mustache templates in pure bash
* [optparse](https://github.com/nk412/optparse) - A BASH wrapper for getopts, for simple command line arguments.
* [rerun](https://github.com/rerun/rerun) - A modular shell automation framework to organize your keeper scripts
* [revolver](https://github.com/molovo/revolver) - A reusable progress spinner for shell scripts
* [phases](https://github.com/sorokine/phases) - Minimally invasive bash preprocessor, select sections of your script to run
* [powscript](https://github.com/coderofsalvation/powscript) - bash transpiler written in bash (coffeescript for bash)
* [semver_bash](https://github.com/cloudflare/semver_bash) - Semantic Versioning in Bash
* [sh-semver](https://github.com/qzb/sh-semver) - Semver tool for bash - finds versions matching to specified rules
* [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts
* [shellfire](https://github.com/shellfire-dev/shellfire) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries
* [shellspec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, zsh and all POSIX shells
* [shfmt](https://github.com/mvdan/sh) - A shell parser, formatter, and interpreter with bash support; includes shfmt
* [shpec](https://github.com/rylnd/shpec) - A shell testing framework
* [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* [sub](https://github.com/basecamp/sub) - A delicious way to organize programs
* [ts](https://github.com/thinkerbot/ts) - A shell test script
* [urchin](https://github.com/tlevine/urchin) - An idiomatic shell testing framework that uses only shell commands
* [shunit2](https://github.com/kward/shunit2) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
* [rebash](https://github.com/jandob/rebash) - Scripting library/framework. Features: imports, exceptions, doc-tests ...
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH

# Guides

* [Bash Official Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
* [Bash Hackers Wiki](https://wiki.bash-hackers.org/)
* [Greg Wooledge's (aka "greycat") wiki](https://mywiki.wooledge.org).
  Specifically [Bash Guide](https://mywiki.wooledge.org/BashGuide), [Bash FAQ](https://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](https://mywiki.wooledge.org/BashPitfalls)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
* [The Linux Documentation Project: Bash Programming - Intro/How-to](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
* [The Linux Documentation Project: Advanced Bash Scripting Guide](https://tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics)
* [A guide to learn bash](https://github.com/Idnan/bash-guide)
* [Shell Field Guide](https://raimonster.com/scripting-field-guide/)

# Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome](https://github.com/emijrp/awesome-awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

### See also

* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps)
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy)

[awesome-badge]: https://raw.githubusercontent.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-fish]: https://github.com/jorgebucaran/awsm.fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins

## Web Links


A curated list of awesome Shell frameworks, libraries and software.

* [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) - 🙃   A delightful community-driven (with 2,000+ contributors) framework for managing your zsh configuration. Includes 300+ optional plugins (rails, git, macOS, hub, docker, homebrew, node, php, python, etc), 140+ themes to spice up your morning, and an auto-update tool so that makes it easy to keep up with the latest updates from the community.
* [nvm-sh/nvm](https://github.com/nvm-sh/nvm) - Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions
* [pi-hole/pi-hole](https://github.com/pi-hole/pi-hole) - A black hole for Internet advertisements
* [dylanaraps/pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible) - 📖 A collection of pure bash alternatives to external processes.
* [acmesh-official/acme.sh](https://github.com/acmesh-official/acme.sh) - A pure Unix shell script implementing ACME client protocol
* [zsh-users/zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - Fish-like autosuggestions for zsh
* [spaceship-prompt/spaceship-prompt](https://github.com/spaceship-prompt/spaceship-prompt) - :rocket::star: A Zsh prompt for Astronauts
* [Nyr/openvpn-install](https://github.com/Nyr/openvpn-install) - OpenVPN road warrior installer for Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS and Fedora
* [rbenv/rbenv](https://github.com/rbenv/rbenv) - Manage your app's Ruby environment
* [zsh-users/zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Fish shell like syntax highlighting for Zsh.
* [asdf-vm/asdf](https://github.com/asdf-vm/asdf) - Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more
* [Bash-it/bash-it](https://github.com/Bash-it/bash-it) - A community Bash framework.
* [kaldi-asr/kaldi](https://github.com/kaldi-asr/kaldi) - kaldi-asr/kaldi is the official location of the Kaldi project.
* [sindresorhus/pure](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt
* [RetroPie/RetroPie-Setup](https://github.com/RetroPie/RetroPie-Setup) - Shell script to set up a Raspberry Pi/Odroid/PC with RetroArch emulator and various cores
* [CISOfy/lynis](https://github.com/CISOfy/lynis) - Lynis - Security auditing tool for Linux, macOS, and UNIX-based systems. Assists with compliance testing (HIPAA/ISO27001/PCI DSS) and system hardening. Agentless, and installation optional.
* [babun/babun](https://github.com/babun/babun) - Babun - a Windows shell you will love!
* [thoughtbot/laptop](https://github.com/thoughtbot/laptop) - A shell script to set up a macOS laptop for web and mobile development.
* [oh-my-fish/oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) - The Fish Shell Framework
* [dnschneid/crouton](https://github.com/dnschneid/crouton) - Chromium OS Universal Chroot Environment
* [zsh-users/antigen](https://github.com/zsh-users/antigen) - The plugin manager for zsh.
* [Mayccoll/Gogh](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal and Pantheon Terminal
* [holman/dotfiles](https://github.com/holman/dotfiles) - @holman does dotfiles
* [oldratlee/useful-scripts](https://github.com/oldratlee/useful-scripts) - 🐌 useful scripts for making developer's everyday life easier and happier, involved java, shell etc.
* [holman/spark](https://github.com/holman/spark) -  ▁▂▃▅▂▇ in your shell.
* [dehydrated-io/dehydrated](https://github.com/dehydrated-io/dehydrated) - letsencrypt/acme client implemented as a shell-script – just add water
* [niieani/bash-oo-framework](https://github.com/niieani/bash-oo-framework) - Bash Infinity is a modern standard library / framework / boilerplate for Bash
* [arzzen/git-quick-stats](https://github.com/arzzen/git-quick-stats) - ▁▅▆▃▅ Git quick statistics is a simple and efficient way to access various statistics in git repository.
* [git-ftp/git-ftp](https://github.com/git-ftp/git-ftp) - Uses Git to upload only changed files to FTP servers.
* [spotify/docker-gc](https://github.com/spotify/docker-gc) - INACTIVE: Docker garbage collection of containers and images
* [petervanderdoes/gitflow-avh](https://github.com/petervanderdoes/gitflow-avh) - AVH Edition of the git extensions to provide high-level repository operations for Vincent Driessen's branching model
* [zsh-users/zsh-completions](https://github.com/zsh-users/zsh-completions) - Additional completion definitions for Zsh.
* [hyperupcall/autoenv](https://github.com/hyperupcall/autoenv) - Directory-based environments
* [todotxt/todo.txt-cli](https://github.com/todotxt/todo.txt-cli) - ☑️ A simple and extensible shell script for managing your todo.txt file.
* [mack-a/v2ray-agent](https://github.com/mack-a/v2ray-agent) - （VLESS+TCP+TLS/VLESS+TCP+XTLS/VLESS+gRPC+TLS/VLESS+WS+TLS/VMess+TCP+TLS/VMess+WS+TLS/Trojan+TCP+TLS/Trojan+gRPC+TLS/Trojan+TCP+XTLS）+伪装站点、八合一共存脚本，支持多内核安装
* [xwmx/nb](https://github.com/xwmx/nb) - CLI and local web plain text note‑taking, bookmarking, and archiving with linking, tagging, filtering, search, Git versioning & syncing, Pandoc conversion, + more, in a single portable script.
* [paulirish/dotfiles](https://github.com/paulirish/dotfiles) - paul's shell, git, etc config files. also homebrew, migration setup. good stuff.
* [teddysun/across](https://github.com/teddysun/across) - Across the Great Wall we can reach every corner in the world
* [KittyKatt/screenFetch](https://github.com/KittyKatt/screenFetch) - Fetches system/theme information in terminal for Linux desktop screenshots.
* [cknadler/vim-anywhere](https://github.com/cknadler/vim-anywhere) - Use Vim everywhere you've always wanted to
* [dylanaraps/pure-sh-bible](https://github.com/dylanaraps/pure-sh-bible) - 📖 A collection of pure POSIX sh alternatives to external processes.
* [GameServerManagers/LinuxGSM](https://github.com/GameServerManagers/LinuxGSM) - The command-line tool for quick, simple deployment and management of Linux dedicated game servers.
* [OpenVPN/easy-rsa](https://github.com/OpenVPN/easy-rsa) - easy-rsa - Simple shell based CA utility
* [jessfraz/dotfiles](https://github.com/jessfraz/dotfiles) - My dotfiles. Buyer beware ;)
* [MichaIng/DietPi](https://github.com/MichaIng/DietPi) - Lightweight justice for your single-board computer!
* [bats-core/bats-core](https://github.com/bats-core/bats-core) - Bash Automated Testing System
* [kewlbear/FFmpeg-iOS-build-script](https://github.com/kewlbear/FFmpeg-iOS-build-script) - Shell scripts to build FFmpeg for iOS and tvOS
* [ekalinin/github-markdown-toc](https://github.com/ekalinin/github-markdown-toc) - Easy TOC creation for GitHub README.md
* [fengyuhetao/shell](https://github.com/fengyuhetao/shell) - Linux命令行与shell脚本编程大全案例
* [paulirish/git-open](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser.
* [ohmybash/oh-my-bash](https://github.com/ohmybash/oh-my-bash) - A delightful community-driven framework for managing your bash configuration, and an auto-update tool so that makes it easy to keep up with the latest updates from the community.
* [laurent22/rsync-time-backup](https://github.com/laurent22/rsync-time-backup) - Time Machine style backup with rsync.
* [teddysun/lamp](https://github.com/teddysun/lamp) - Install LAMP(Linux + Apache + MySQL/MariaDB + PHP ) for CentOS/Debian/Ubuntu
* [jamesob/desk](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell
* [pystardust/ani-cli](https://github.com/pystardust/ani-cli) - A cli tool to browse and play anime
* [licess/lnmp](https://github.com/licess/lnmp) - LNMP一键安装包是一个用Linux Shell编写的可以为CentOS/RHEL/Fedora/Aliyun/Amazon、Debian/Ubuntu/Raspbian/Deepin/Mint Linux VPS或独立主机安装LNMP(Nginx/MySQL/PHP)、LNMPA(Nginx/MySQL/PHP/Apache)、LAMP(Apache/MySQL/PHP)生产环境的Shell程序。
* [b4b4r07/enhancd](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with your interactive filter
* [wslutilities/wslu](https://github.com/wslutilities/wslu) - A collection of utilities for Windows 10 Linux Subsystems
* [mathiasbynens/evil.sh](https://github.com/mathiasbynens/evil.sh) - :speak_no_evil: Subtle and not-so-subtle shell tweaks that will slowly drive people insane.
* [tmux-plugins/tmux-yank](https://github.com/tmux-plugins/tmux-yank) - Tmux plugin for copying to system clipboard. Works on OSX, Linux and Cygwin.
* [scop/bash-completion](https://github.com/scop/bash-completion) - Programmable completion functions for bash
* [silinternational/ecs-deploy](https://github.com/silinternational/ecs-deploy) - Simple shell script for initiating blue-green deployments on Amazon EC2 Container Service (ECS)
* [Winetricks/winetricks](https://github.com/Winetricks/winetricks) - Winetricks is an easy way to work around problems in Wine
* [hnarayanan/shpotify](https://github.com/hnarayanan/shpotify) - A command-line interface to Spotify.
* [dana-at-cp/backdoor-apk](https://github.com/dana-at-cp/backdoor-apk) - backdoor-apk is a shell script that simplifies the process of adding a backdoor to any Android APK file. Users of this shell script should have working knowledge of Linux, Bash, Metasploit, Apktool, the Android SDK, smali, etc. This shell script is provided as-is without warranty of any kind and is intended for educational purposes only.
* [billw2/rpi-clone](https://github.com/billw2/rpi-clone) - A shell script to clone a booted disk.
* [juewuy/ShellClash](https://github.com/juewuy/ShellClash) - One-click deployment and management of Clash services using Shell scripts in Linux environment
* [huyng/bashmarks](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell
* [nodenv/nodenv](https://github.com/nodenv/nodenv) - Manage multiple NodeJS versions.
* [simonwhitaker/gibo](https://github.com/simonwhitaker/gibo) - Easy access to gitignore boilerplates
* [postmodern/ruby-install](https://github.com/postmodern/ruby-install) - Installs Ruby, JRuby, Rubinius, TruffleRuby or MRuby
* [tony/tmux-config](https://github.com/tony/tmux-config) - :green_book: Example tmux configuration - screen + vim key-bindings, system stat, cpu load bar.
* [polybar/polybar-scripts](https://github.com/polybar/polybar-scripts) - This is a community project. We write and collect scripts for polybar!
* [bpkg/bpkg](https://github.com/bpkg/bpkg) - Lightweight bash package manager
* [esc0rtd3w/wifi-hacker](https://github.com/esc0rtd3w/wifi-hacker) - Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securities (WEP, WPS, WPA, WPA2)
* [megastep/makeself](https://github.com/megastep/makeself) - A self-extracting archiving tool for Unix systems, in 100% shell script.
* [trapd00r/LS_COLORS](https://github.com/trapd00r/LS_COLORS) - A collection of LS_COLORS definitions; needs your contribution!
* [WritingMinds/ffmpeg-android](https://github.com/WritingMinds/ffmpeg-android) - FFmpeg for Android compiled with x264, libass, fontconfig, freetype, fribidi and lame (Supports Android 4.1+)
* [mrworf/plexupdate](https://github.com/mrworf/plexupdate) - Plex Update script to simplify the life of Linux Plex Media Server users.
* [xero/dotfiles](https://github.com/xero/dotfiles) - ▒ rice ░░  custom linux config files
* [MvsCode/frps-onekey](https://github.com/MvsCode/frps-onekey) -  Frps 一键安装脚本&管理脚本 A tool to auto-compile & install frps on Linux
* [chriskempson/base16-shell](https://github.com/chriskempson/base16-shell) - Base16 for Shells
* [isaacs/nave](https://github.com/isaacs/nave) - Virtual Environments for Node
* [driesvints/dotfiles](https://github.com/driesvints/dotfiles) - Get started with your own dotfiles.
* [kerl/kerl](https://github.com/kerl/kerl) - Easy building and installing of Erlang/OTP instances
* [adtac/climate](https://github.com/adtac/climate) - The swiss-army knife of utility tools for Linux.
* [Bugswriter/notflix](https://github.com/Bugswriter/notflix) - Notflix is a shell script to search and stream torrent.
* [fsquillace/junest](https://github.com/fsquillace/junest) - The lightweight Arch Linux based distro that runs, without root privileges, upon any Linux distro
* [udhos/update-golang](https://github.com/udhos/update-golang) - update-golang is a script to easily fetch and install new Golang releases with minimum system intrusion
* [Nyr/wireguard-install](https://github.com/Nyr/wireguard-install) - WireGuard road warrior installer for Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS and Fedora
* [create-dmg/create-dmg](https://github.com/create-dmg/create-dmg) - A shell script to build fancy DMGs
* [aqzt/kjyw](https://github.com/aqzt/kjyw) - 快捷运维，代号kjyw，项目基于shell、python，运维脚本工具库，收集各类运维常用工具脚本，实现快速安装nginx、mysql、php、redis、nagios、运维经常使用的脚本等等...
* [Aloxaf/fzf-tab](https://github.com/Aloxaf/fzf-tab) - Replace zsh's default completion selection menu with fzf!
* [ZZROTDesign/docker-clean](https://github.com/ZZROTDesign/docker-clean) - A script that cleans docker containers, images, volumes, and networks.
* [cytopia/pwncat](https://github.com/cytopia/pwncat) - pwncat - netcat on steroids with Firewall, IDS/IPS evasion, bind and reverse shell, self-injecting shell and port forwarding magic - and its fully scriptable with Python (PSE)
* [kward/shunit2](https://github.com/kward/shunit2) - shUnit2 is a xUnit based unit test framework for Bourne based shell scripts.
* [dylanaraps/pfetch](https://github.com/dylanaraps/pfetch) - 🐧 A pretty system information tool written in POSIX sh.
* [alrra/dotfiles](https://github.com/alrra/dotfiles) - 💻 macOS / Ubuntu dotfiles
* [mchav/with](https://github.com/mchav/with) - Command prefixing for continuous workflow using a single tool.
* [pch/welder](https://github.com/pch/welder) - 👨‍🏭Set up your Linux server with plain shell scripts
* [shellfire-dev/shellfire](https://github.com/shellfire-dev/shellfire) - A repository of namespaced, composable shell (bash, sh and dash) function libraries. Takes aware the pain of shell scripting, making it robust and reusable. Includes secure curl usage, JSON, XML and Debian control file parsers, dependency documentation via attributes, and more. Batteries ARE included.
* [visionmedia/deploy](https://github.com/visionmedia/deploy) - Minimalistic deployment shell script
* [kuoruan/shell-scripts](https://github.com/kuoruan/shell-scripts) - Linux Shell Scripts
* [elasticdog/transcrypt](https://github.com/elasticdog/transcrypt) - transparently encrypt files within a git repository
* [denilsonsa/prettyping](https://github.com/denilsonsa/prettyping) - `prettyping` is a wrapper around the standard `ping` tool, making the output prettier, more colorful, more compact, and easier to read.
* [jayrambhia/Install-OpenCV](https://github.com/jayrambhia/Install-OpenCV) - shell scripts to install different version of OpenCV in different distributions of Linux
* [paxtonhare/demo-magic](https://github.com/paxtonhare/demo-magic) - A handy shell script that enables you to write repeatable demos in a bash environment.
* [wireghoul/graudit](https://github.com/wireghoul/graudit) - grep rough audit - source code auditing tool
* [dyne/Tomb](https://github.com/dyne/Tomb) - the Crypto Undertaker
* [jeffreytse/zsh-vi-mode](https://github.com/jeffreytse/zsh-vi-mode) - 💻 A better and friendly vi(vim) mode plugin for ZSH.
* [monfresh/laptop](https://github.com/monfresh/laptop) - A shell script which sets up a Ruby development environment on your macOS computer.
* [dsixda/Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization.  Uses shell scripts and works with Cygwin/OS X/Linux.
* [liquanzhou/ops_doc](https://github.com/liquanzhou/ops_doc) - 运维简洁实用手册
* [kitabisa/ssb](https://github.com/kitabisa/ssb) - Secure Shell Bruteforcer — A faster & simpler way to bruteforce SSH server
* [matchai/spacefish](https://github.com/matchai/spacefish) - 🚀🐟 The fish shell prompt for astronauts
* [hectorm/hblock](https://github.com/hectorm/hblock) - Improve your security and privacy by blocking ads, tracking and malware domains.
* [justinmayer/virtualfish](https://github.com/justinmayer/virtualfish) - Fish shell tool for managing Python virtual environments
* [goreliu/zshguide](https://github.com/goreliu/zshguide) - Zsh 开发指南
* [basherpm/basher](https://github.com/basherpm/basher) - A package manager for shell scripts.
* [envygeeks/jekyll-docker](https://github.com/envygeeks/jekyll-docker) - ⛴ Docker images, and CI builders for Jekyll.
* [stark/Color-Scripts](https://github.com/stark/Color-Scripts) - User contributed color scripts
* [bash-my-aws/bash-my-aws](https://github.com/bash-my-aws/bash-my-aws) - Bash-my-AWS provides simple but powerful CLI commands for managing AWS resources
* [konstruktoid/hardening](https://github.com/konstruktoid/hardening) - Hardening Ubuntu. Systemd edition.
* [EternalPain/ZJL](https://github.com/EternalPain/ZJL) - ZJL 免流防跳脚本
* [aurora/rmate](https://github.com/aurora/rmate) - Remote TextMate 2 implemented as shell script
* [riobard/bash-powerline](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script. See also https://github.com/riobard/zsh-powerline
* [cokebar/gfwlist2dnsmasq](https://github.com/cokebar/gfwlist2dnsmasq) - A shell script which convert gfwlist into dnsmasq rules. Python version: https://github.com/cokebar/gfwlist2dnsmasq_python
* [geometry-zsh/geometry](https://github.com/geometry-zsh/geometry) - geometry is a minimal, fully customizable and composable zsh prompt theme
* [rmarquis/pacaur](https://github.com/rmarquis/pacaur) - [unmaintained] An AUR helper that minimizes user interaction
* [icy/pacapt](https://github.com/icy/pacapt) - An ArchLinux's pacman-like shell wrapper for many package managers. 56KB and run anywhere.
* [philcook/brew-php-switcher](https://github.com/philcook/brew-php-switcher) - Brew PHP switcher is a simple shell script to switch your apache and CLI quickly between major versions of PHP. If you support multiple products/projects that are built using either brand new or old legacy PHP functionality. For users of Homebrew (or brew for short) currently only.
* [dunwu/linux-tutorial](https://github.com/dunwu/linux-tutorial) - :penguin: Linux教程，主要内容：Linux 命令、Linux 系统运维、软件运维、精选常用Shell脚本
* [complexorganizations/wireguard-manager](https://github.com/complexorganizations/wireguard-manager) - ✔️ wireguard-manager enables you to build and manage your own vpn under a minute.
* [webpro/dotfiles](https://github.com/webpro/dotfiles) - Dotfiles for macOS
* [carloscuesta/materialshell](https://github.com/carloscuesta/materialshell) - A material design theme for your terminal. ✨
* [wireghoul/htshells](https://github.com/wireghoul/htshells) - Self contained htaccess shells and attacks
* [cdown/clipmenu](https://github.com/cdown/clipmenu) - Clipboard management using dmenu
* [spencerwooo/dotfiles](https://github.com/spencerwooo/dotfiles) - Dotfiles for all :D
* [StarshipEngineer/OpenVPN-Setup](https://github.com/StarshipEngineer/OpenVPN-Setup) - Shell script to set up Raspberry Pi (TM) as an OpenVPN server
* [unixorn/git-extra-commands](https://github.com/unixorn/git-extra-commands) - A collection of git utilities and useful extra git scripts, packaged for ease of use with shell frameworks, though they aren't required.
* [ffffffff0x/f8x](https://github.com/ffffffff0x/f8x) - 红/蓝队环境自动化部署工具 | Red/Blue team environment automation deployment tool
* [cloudposse/geodesic](https://github.com/cloudposse/geodesic) - 🚀 Geodesic is a DevOps Linux Toolbox in Docker. We use it as an interactive cloud automation shell. It's the fastest way to get up and running with a rock solid Open Source toolchain.  ★ this repo! https://slack.cloudposse.com/
* [summerblue/laravel-ubuntu-init](https://github.com/summerblue/laravel-ubuntu-init) - A shell script for setting up Laravel Production environment on Ubuntu 14.04 & Ubuntu 16 & Ubuntu 18  system.
* [rehiy/dnspod-shell](https://github.com/rehiy/dnspod-shell) - 基于DNSPod用户API实现的纯Shell动态域名客户端
* [anti-ddos/Anti-DDOS](https://github.com/anti-ddos/Anti-DDOS) - 🔒 Anti DDOS | Bash Script Project 🔒
* [caarlos0/dotfiles](https://github.com/caarlos0/dotfiles) - Config files for ZSH, Java, Ruby, Go, Editors, Terminals and more.
* [bestswifter/macbootstrap](https://github.com/bestswifter/macbootstrap) - A bootstrap script for new Mac
* [getfatday/keytool-importkeypair](https://github.com/getfatday/keytool-importkeypair) - A shell script to import key/certificate pairs into an existing Java keystore
* [monlor/Monlor-Tools](https://github.com/monlor/Monlor-Tools) - 小米路由器Shell工具箱，本人自用，主要参考了小米的Misstar Tools制作，仅学习之用！Telegram群组：https://t.me/joinchat/FMraA0lwzH9fzEW1wXdCFA
* [clangcn/kcp-server](https://github.com/clangcn/kcp-server) - kcp-server one key install shell,build for https://github.com/kcptunsocks/kcptun/tree/router
* [jmcerrejon/PiKISS](https://github.com/jmcerrejon/PiKISS) - PiKISS for Raspberry Pi: A bunch of scripts with menu to make your life easier.
* [myxuchangbin/dnsmasq_sniproxy_install](https://github.com/myxuchangbin/dnsmasq_sniproxy_install) - One-click Install and Configure Dnsmasq and Sniproxy for CentOS/Debian/Ubuntu
* [neverpanic/google-font-download](https://github.com/neverpanic/google-font-download) - Locally host Google's web fonts
* [loyess/Shell](https://github.com/loyess/Shell) - Shadowsocks with plugins one-click installation. e.g. v2ray-plugin, kcptun, simple-obfs, goquiet, cloak, mos-tls-tunnel, rabbit-tcp, simple-tls, gost-plugin, xray-plugin, qtun, gun
* [modernish/modernish](https://github.com/modernish/modernish) - Modernish is a library for writing robust, portable, readable, and powerful programs for POSIX-based shells and utilities.
* [glenpike/npm-g_nosudo](https://github.com/glenpike/npm-g_nosudo) - A shell script which will fix the problem where you want to stop using sudo for npm -g on Ubuntu.
* [raylee/tldr-sh-client](https://github.com/raylee/tldr-sh-client) - Simplified and community-driven man pages
* [snwh/ubuntu-post-install](https://github.com/snwh/ubuntu-post-install) - A set of post-installation shell scripts for Ubuntu
* [swoodford/aws](https://github.com/swoodford/aws) - A collection of bash shell scripts for automating various tasks with Amazon Web Services using the AWS CLI and jq.
* [jgmdev/ddos-deflate](https://github.com/jgmdev/ddos-deflate) - Fork of DDoS Deflate with fixes, improvements and new features.
* [lemnos/theme.sh](https://github.com/lemnos/theme.sh) - A script which lets you set your $terminal theme.
* [bytesking/AutoPacking-iOS](https://github.com/bytesking/AutoPacking-iOS) - iOS自动打包脚本 多项选择 一行上传指定位置
* [x1mdev/ReconPi](https://github.com/x1mdev/ReconPi) - ReconPi - A lightweight recon tool that performs extensive scanning with the latest tools.
* [unofficial-unifi/unifi-pfsense](https://github.com/unofficial-unifi/unifi-pfsense) - A script that installs the UniFi Controller software on pfSense and other FreeBSD systems
* [mfaerevaag/wd](https://github.com/mfaerevaag/wd) - :rocket: Jump to custom directories in zsh
* [reobin/typewritten](https://github.com/reobin/typewritten) - A minimal, lightweight, informative zsh prompt theme
* [shellspec/shellspec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for bash, ksh, zsh, dash and all POSIX shells
* [mafredri/zsh-async](https://github.com/mafredri/zsh-async) - Because your terminal should be able to perform tasks asynchronously without external tools!
* [cloudsec/brootkit](https://github.com/cloudsec/brootkit) - Lightweight rootkit implemented by bash shell scripts v0.10
* [churchers/vm-bhyve](https://github.com/churchers/vm-bhyve) - Shell based, minimal dependency bhyve manager
* [mdo/config](https://github.com/mdo/config) - Personal checklist for setting up a new Mac's dev environment.
* [trick77/ipset-blacklist](https://github.com/trick77/ipset-blacklist) - A bash script to ban large numbers of IP addresses published in blacklists.
* [kvaps/kubectl-node-shell](https://github.com/kvaps/kubectl-node-shell) - Exec into node via kubectl
* [RaymiiOrg/bash-http-monitoring](https://github.com/RaymiiOrg/bash-http-monitoring) - HTTP(s) monitoring webpage via shell script
* [centminmod/centminmod](https://github.com/centminmod/centminmod) - CentOS Shell menu based Nginx LEMP web stack auto installer (GPLv3 licensed)
* [na--/ebook-tools](https://github.com/na--/ebook-tools) - Shell scripts for organizing and managing ebook collections
* [plyint/encpass.sh](https://github.com/plyint/encpass.sh) - Lightweight solution for using encrypted passwords in shell scripts
* [changs/slimzsh](https://github.com/changs/slimzsh) - Small, usable configuration for ZSH
* [evanlucas/fish-kubectl-completions](https://github.com/evanlucas/fish-kubectl-completions) - kubectl completions for fish shell
* [bluezio/ipwebcam-gst](https://github.com/bluezio/ipwebcam-gst) - Simple shell script for using IP Webcam as a V4L2 webcam / sound source
* [Nick233333/phper-linux-gitbook](https://github.com/Nick233333/phper-linux-gitbook) - 💡PHPer 必知必会的 Linux 命令
* [mig1984/bashible](https://github.com/mig1984/bashible) - Simple bash DSL framework for writing shell scripts safe and agile.
* [jcsalterego/historian](https://github.com/jcsalterego/historian) - Command-line utility for managing shell history in a SQLite database.
* [xwmx/bash-boilerplate](https://github.com/xwmx/bash-boilerplate) - A collection of Bash scripts for creating safe and useful command line programs.
* [alestic/lambdash](https://github.com/alestic/lambdash) - Lambda shell - Run sh commands inside AWS Lambda environment
* [screetsec/Vegile](https://github.com/screetsec/Vegile) - This tool will setting up your backdoor/rootkits when backdoor already setup it will be hidden your spesisifc process,unlimited your session in metasploit and transparent. Even when it killed, it will re-run again. There always be a procces which while run another process,So we can assume that this procces is unstopable like a Ghost in The Shell
* [clangcn/onekey-install-shell](https://github.com/clangcn/onekey-install-shell) - 一大坨一键安装脚本
* [freekmurze/dotfiles](https://github.com/freekmurze/dotfiles) - My personal dotfiles
* [srillia/devops](https://github.com/srillia/devops) - let devops for docker, dockerswarm ,k8s easy
* [Ventto/mons](https://github.com/Ventto/mons) - POSIX Shell script to quickly manage monitors on X
* [franciscolourenco/done](https://github.com/franciscolourenco/done) - A fish-shell package to automatically receive notifications when long processes finish.
* [servisys/ispconfig_setup](https://github.com/servisys/ispconfig_setup) - ISPConfig autoinstaller and setup
* [fteem/git-semantic-commits](https://github.com/fteem/git-semantic-commits) - Tiny semantic commit messages for Git.
* [pstadler/ticker.sh](https://github.com/pstadler/ticker.sh) - Real-time stock tickers from the command-line.
* [cykerway/complete-alias](https://github.com/cykerway/complete-alias) - automagical shell alias completion;
* [Har-Kuun/OneClickCDN](https://github.com/Har-Kuun/OneClickCDN) - A one-click shell script to set up a CDN node for your websites.
* [Spearfoot/disk-burnin-and-testing](https://github.com/Spearfoot/disk-burnin-and-testing) - Shell script for burn-in and testing of new or re-purposed drives
* [centos-bz/ezhttp](https://github.com/centos-bz/ezhttp) - The bash shell script stack for installation of Nginx OpenResty Tengine lua_nginx_module nginx_concat_module nginx_upload_module ngx_substitutions_filter_module　Apache-2.2 Apache-2.4　MySQL-5.1 MySQL-5.5 MySQL-5.6 MySQL-5.7 PHP-5.2 PHP-5.3 PHP-5.4 PHP-5.5 PHP-5.6 ZendOptimizer ZendGuardLoader Xcache Eaccelerator Imagemagick IonCube Memcache Memcached Redis Mongo Xdebug Mssql Memcached PureFtpd PhpMyAdmin Redis Mongodb PhpRedisAdmin MemAdmin RockMongo Jdk7 Jdk8 Tomcat7 Tomcat8
* [Checksum/critic.sh](https://github.com/Checksum/critic.sh) - Dead simple testing framework for Bash with coverage reporting
* [2moe/tmoe-linux](https://github.com/2moe/tmoe-linux) - Without any basic knowledge of linux shell, you can easily install and configure a GNU/Linux graphical desktop environment on 📱Android termux and 💻WSL .🍰You can also run VSCode on your android phone.
* [bach-sh/bach](https://github.com/bach-sh/bach) - Bach Testing Framework
* [EivindArvesen/prm](https://github.com/EivindArvesen/prm) - A minimal project manager for the terminal.
* [TermuxArch/TermuxArch](https://github.com/TermuxArch/TermuxArch) - Experience the pleasure of the Linux command prompt in Android, Chromebook, Fire OS and Windows on smartphone, smartTV, tablet and wearable https://termuxarch.github.io/TermuxArch/
* [marzocchi/zsh-notify](https://github.com/marzocchi/zsh-notify) - Desktop notifications for long-running commands in zsh.
* [sapegin/dotfiles](https://github.com/sapegin/dotfiles) - My macOS environment: zsh, Git, Visual Studio Code, etc.
* [iljaiwas/objc-run](https://github.com/iljaiwas/objc-run) - A shell script that makes it easy to use Objective-C files for shell script-like tasks.
* [mbucc/shmig](https://github.com/mbucc/shmig) - Database migration tool written in BASH.
* [docopt/docopts](https://github.com/docopt/docopts) - Shell interpreter for docopt, the command-line interface description language.
* [lework/kainstall](https://github.com/lework/kainstall) - Use shell scripts to install kubernetes(k8s) high availability clusters and addon components based on kubeadmin with one click.使用shell脚本基于kubeadmin一键安装kubernetes 高可用集群和addon组件。
* [odb/shml](https://github.com/odb/shml) - SHell Markup Language | Style Framework for The Terminal
* [bmizerany/roundup](https://github.com/bmizerany/roundup) - eliminate bugs and weeds from shell scripts
* [ericoc/zabbix-slack-alertscript](https://github.com/ericoc/zabbix-slack-alertscript) - Zabbix AlertScript for Slack.com chat
* [natelandau/shell-scripting-templates](https://github.com/natelandau/shell-scripting-templates) - Shell scripting utility functions and a bash script boilerplate template
* [kisslinux/kiss](https://github.com/kisslinux/kiss) - KISS Linux - Package Manager
* [oscm/shell](https://github.com/oscm/shell) - Infrastructure Management Shell - Linux
* [chris-marsh/pureline](https://github.com/chris-marsh/pureline) - A Pure Bash Powerline PS1 Command Prompt
* [whiteinge/ok.sh](https://github.com/whiteinge/ok.sh) - A Bourne shell GitHub API client library focused on interfacing with shell scripts
* [JElchison/format-udf](https://github.com/JElchison/format-udf) - Bash script to format a block device (hard drive or Flash drive) in UDF. The output is a drive that can be used for reading/writing across multiple operating system families: Windows, macOS, and Linux. This script should be capable of running in macOS or in Linux.
* [colbycheeze/dotfiles](https://github.com/colbycheeze/dotfiles) - Setup and install scripts for a new machine + dotfiles for various apps. Linux, Mac, and Mac (Amazon specific) branches are included.
* [FabioAntunes/fish-nvm](https://github.com/FabioAntunes/fish-nvm) - nvm wrapper for fish-shell
* [vmavromatis/gnome-layout-manager](https://github.com/vmavromatis/gnome-layout-manager) - A bash script that batch installs and tweaks GNOME extensions as well as GTK/Shell themes. There are currently three options available: Unity, Windows and macOS.
* [MinecraftServerControl/mscs](https://github.com/MinecraftServerControl/mscs) - Powerful command-line control for UNIX and Linux powered Minecraft servers
* [zoltan-dulac/css3FontConverter](https://github.com/zoltan-dulac/css3FontConverter) - A shell script that can use other command line tools to produce @font-face compatible fonts in all browsers.  Works under Windows (using Cygwin), Mac OS X and Linux
* [kdabir/has](https://github.com/kdabir/has) - ✅ checks presence of various command line tools and their versions on the path
* [cswl/tsu](https://github.com/cswl/tsu) - Gain root shell on Termux.
* [epety/100-shell-script-examples](https://github.com/epety/100-shell-script-examples) - Collection of shell scripts found on the internet
* [changyuheng/fz](https://github.com/changyuheng/fz) - Cli shell plugin, the missing fuzzy tab completion feature for the z jump around command.
* [geerlingguy/dotfiles](https://github.com/geerlingguy/dotfiles) - My configuration. Minimalist, but helps save a few thousand keystrokes a day.
* [bkuhlmann/mac_os](https://github.com/bkuhlmann/mac_os) - Shell scripts for automated macOS machine setup.
* [mstinaff/PMS_Updater](https://github.com/mstinaff/PMS_Updater) - Shell script for updating the Plex Media Server inside the FreeNAS Plex plugin
* [github-modules/ghwd](https://github.com/github-modules/ghwd) - Open the github URL that matches your shell's current branch and working directory
* [flplv/ssh-allow-friend](https://github.com/flplv/ssh-allow-friend) - A shell script to temporary allow ssh logins for friends
* [hamvocke/dotfiles](https://github.com/hamvocke/dotfiles) - A collection of my personal dotfiles
* [andresgongora/synth-shell](https://github.com/andresgongora/synth-shell) - Boost your terminal, script by script
* [szepeviktor/debian-server-tools](https://github.com/szepeviktor/debian-server-tools) - Tools and living docs 🧬 for Debian-based servers and Web Applications
* [iridakos/stup](https://github.com/iridakos/stup) - Daily notes in the terminal :penguin:
* [jszczerbinsky/ptSh](https://github.com/jszczerbinsky/ptSh) - Let your shell commands look prettier
* [marlonrichert/zsh-snap](https://github.com/marlonrichert/zsh-snap) - ⚡️ Znap! The fast & light-weight Zsh plugin manager that's easy to grok. Also functions as a generic Git repo manager.
* [rylnd/shpec](https://github.com/rylnd/shpec) - Test your shell scripts!
* [hertg/egpu-switcher](https://github.com/hertg/egpu-switcher) - 🖥🐧 Setup script for eGPUs in Linux (Xorg)
* [kasparsd/php-7-debian](https://github.com/kasparsd/php-7-debian) - Install PHP 7 on Debian/Ubuntu
* [nystudio107/craft-scripts](https://github.com/nystudio107/craft-scripts) - Shell scripts to manage database backups, asset backups, file permissions, asset syncing, cache clearing, and database syncing between Craft CMS environments
* [petrockblog/OwncloudPie](https://github.com/petrockblog/OwncloudPie) - Shell script for installing Owncloud on the Raspberry Pi
* [arcticicestudio/nord-gnome-terminal](https://github.com/arcticicestudio/nord-gnome-terminal) - An arctic, north-bluish clean and elegant GNOME Terminal color theme.
* [canha/golang-tools-install-script](https://github.com/canha/golang-tools-install-script) - Simple Bash script to automate Go language tools single user installation or even removal.
* [R0B1NL1N/OSCP-note](https://github.com/R0B1NL1N/OSCP-note) - list of useful commands, shells and notes related to OSCP
* [Installomator/Installomator](https://github.com/Installomator/Installomator) - Installation script to deploy standard software on Macs
* [chriscool/sharness](https://github.com/chriscool/sharness) - Shell library to test your Unix tools like Git does
* [budlabs/i3ass](https://github.com/budlabs/i3ass) - A collection of shell scripts to ease the use of i3wm
* [llitfkitfk/docker-tutorial-cn](https://github.com/llitfkitfk/docker-tutorial-cn) - docker 教程
* [ellipsis/ellipsis](https://github.com/ellipsis/ellipsis) - ◦◦◦ Ellipsis is a package manager for dotfiles.
* [ellerbrock/fish-shell-setup-osx](https://github.com/ellerbrock/fish-shell-setup-osx) - :blowfish: Tutorial: Fish, Fisher, Powerline Fonts + iTerm2
* [robotshell/magicRecon](https://github.com/robotshell/magicRecon) - MagicRecon is a powerful shell script to maximize the recon and data collection process of an objective and finding common vulnerabilities, all this saving the results obtained in an organized way in directories and with various formats.
* [chromedp/docker-headless-shell](https://github.com/chromedp/docker-headless-shell) - Minimal container for Chrome's headless shell, useful for automating / driving the web
* [clu3bot/owt](https://github.com/clu3bot/owt) - Update Version 3.1 added free SMS messaging.
* [Washington-University/HCPpipelines](https://github.com/Washington-University/HCPpipelines) - Processing pipelines for the HCP
* [ekalinin/envirius](https://github.com/ekalinin/envirius) - Universal Virtual Environments Manager
* [bkuhlmann/mac_os-config](https://github.com/bkuhlmann/mac_os-config) - Shell scripts for customized macOS machine setup and configuration.
* [Oreomeow/VIP](https://github.com/Oreomeow/VIP) - DONOT FORK!!!别 Fork 了！超过一定数量就跑路！🏃‍💨 Gone
* [18F/laptop](https://github.com/18F/laptop) - DEPRECATED: A shell script which turns your Mac into an awesome web development machine.
* [bntzio/wipe-modules](https://github.com/bntzio/wipe-modules) - 🗑️ Easily remove the node_modules folder of non-active projects
* [importpw/import](https://github.com/importpw/import) - `import` is a simple and fast module system for Bash and other Unix shells
* [codigofuerte/GeoNames-MySQL-DataImport](https://github.com/codigofuerte/GeoNames-MySQL-DataImport) - Shell Script to download and import geonames.org dumps into a mysql database.
* [gdubw/gdub](https://github.com/gdubw/gdub) - A gradlew / gradle wrapper.
* [danhper/fundle](https://github.com/danhper/fundle) - A minimalist package manager for fish shell
* [RayViljoen/Raspberry-PI-SD-Installer-OS-X](https://github.com/RayViljoen/Raspberry-PI-SD-Installer-OS-X) - Shell Script for creating Raspberry PI SD card on OS X.
* [petobens/trueline](https://github.com/petobens/trueline) - Fast and extensible bash powerline prompt with true color and fancy icon support
* [kaelzhang/shell-safe-rm](https://github.com/kaelzhang/shell-safe-rm) - 😎 Safe-rm: A drop-in and much safer replacement of bash rm with nearly full functionalities and options of the rm command! Safe-rm will act exactly the same as the original rm command.
* [freebsd/poudriere](https://github.com/freebsd/poudriere) - Port/Package build and test system
* [SafeBreach-Labs/pwndsh](https://github.com/SafeBreach-Labs/pwndsh) - Post-exploitation framework (and an interactive shell) developed in Bash shell scripting
* [minamarkham/yonce](https://github.com/minamarkham/yonce) - 👑 Queen Bey-inspired themes for all your favs.
* [ghaiklor/iterm-fish-fisher-osx](https://github.com/ghaiklor/iterm-fish-fisher-osx) - Semi-automatic installer for Command Line Tools + Homebrew + iTerm2 + Fish Shell + Fisher + Plugins/Themes
* [TermuxHackz/wifi-hacker](https://github.com/TermuxHackz/wifi-hacker) - Shell Script For Attacking Wireless Connections Using Built-In Kali Tools. Supports All Securities (WEP, WPS, WPA, WPA2)
* [sheharyarn/mongo-sync](https://github.com/sheharyarn/mongo-sync) - Sync Remote and Local MongoDB Databases :fire:
* [Baiyuetribe/baiyue_onekey](https://github.com/Baiyuetribe/baiyue_onekey) - 佰阅部落一键脚本合集工具箱，集合25+优质开源项目，一步到位，全程中文交互提示，不懂代码也可以轻松搭建很多程序
* [slashbeast/better-initramfs](https://github.com/slashbeast/better-initramfs) - Small and reliable initramfs solution supporting (remote) rescue shell, lvm, dmcrypt luks, software raid, tuxonice, uswsusp and more.
* [ovh/debian-cis](https://github.com/ovh/debian-cis) - PCI-DSS compliant Debian 9/10 hardening
* [pr1ntf/iohyve](https://github.com/pr1ntf/iohyve) - FreeBSD bhyve manager utilizing ZFS
* [karek314/macOS-home-call-drop](https://github.com/karek314/macOS-home-call-drop) - Simple shell script to fix macOS privacy issues and remove mostly useless macOS calls to cupertino
* [tanersener/ffmpeg-video-slideshow-scripts](https://github.com/tanersener/ffmpeg-video-slideshow-scripts) - Shell scripts to create video slideshows using images and videos
* [sund/auto-gitlab-backup](https://github.com/sund/auto-gitlab-backup) - A simple script to backup your Gitlab data. This script will copy the backup archives of your gitlab installation via rsync, or scp. Also, you can copy backups to Backblaze’s B2 Cloud Storage service.
* [pacstall/pacstall](https://github.com/pacstall/pacstall) - An AUR-inspired package manager for Ubuntu
* [redcode-labs/Revssl](https://github.com/redcode-labs/Revssl) - A script that automates generation of OpenSSL reverse shells
* [black7375/BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) - 🔮 Awesome, Customable Zsh Starter Kit 🌠🌠
* [tmux-plugins/tmux-cpu](https://github.com/tmux-plugins/tmux-cpu) - Plug and play cpu percentage and icon indicator for Tmux.
* [brujoand/sbp](https://github.com/brujoand/sbp) - Simple Bash Prompt (SBP) is a bash prompt, which strives to be simple. But it isn't. But it looks kind of nice. I think.
* [systematicat/hack-captive-portals](https://github.com/systematicat/hack-captive-portals) - Hack any Captive portal using MAC-spoofing technique
* [denny0223/scrabble](https://github.com/denny0223/scrabble) - Simple tool to recover .git folder from remote server
* [6gk/fet.sh](https://github.com/6gk/fet.sh) - 🐢 a fetch written in posix shell without any external commands  (sponsored by https://git.io/kiwmi)
* [adoyle-h/lobash](https://github.com/adoyle-h/lobash) - A modern, safe, powerful utility library for Bash script development.
* [andrep/git-svn-clone-externals](https://github.com/andrep/git-svn-clone-externals) - Simple shell script to import svn:externals into a local git-svn repository
* [xwp/wp-dev-lib](https://github.com/xwp/wp-dev-lib) - 🛠️ Common code used during development of WordPress plugins and themes
* [erichs/composure](https://github.com/erichs/composure) - Don't fear the Unix chainsaw
* [joestandring/dwm-bar](https://github.com/joestandring/dwm-bar) - A modular statusbar for dwm
* [A-BenMao/pure-bash-bible-zh_CN](https://github.com/A-BenMao/pure-bash-bible-zh_CN) - 📖 一个纯bash实现外部命令的脚本集合（中文版）【翻译自pure-bash-bible仓库】
* [matteocorti/check_ssl_cert](https://github.com/matteocorti/check_ssl_cert) - A shell script (that can be used as a Nagios/Icinga plugin) to check an SSL/TLS connection.
* [examplecode/unused-image](https://github.com/examplecode/unused-image) - This is shell script used to check and clean unused image resource , support Android and IOS project
* [chrismytton/shoreman](https://github.com/chrismytton/shoreman) - :shell: foreman in shell
* [techarkit/shell-scripting-tutorial](https://github.com/techarkit/shell-scripting-tutorial) - A complete begineers guide to learn shell scripting from scratch which includes Videos, Practice scenarios and project idea.
* [FICS/atcmd](https://github.com/FICS/atcmd) - Android AT command scripts and firmware extraction
* [jgigault/42FileChecker](https://github.com/jgigault/42FileChecker) - 42FileChecker is a tiny bash script developed at 42 school for testing and checking files according to the rules of the subjects
* [LukeSmithxyz/lb](https://github.com/LukeSmithxyz/lb) - Blog & RSS system in less than 100 lines of shell script
* [whihail/AutoArchive](https://github.com/whihail/AutoArchive) - 一个基于Jenkins的iOS/Android自动构建系统，它实现了最大程度的自动化，让你的iOS自动打包，Android自动打包流程变得更加高效。此项目包含了各种实现细节的讲解说明，你能够使用它解决大多数跟客户端构建/分发相关的问题，并将这种能力进行开放，提高研发效率。
* [vitorgalvao/tiny-scripts](https://github.com/vitorgalvao/tiny-scripts) - Collection of small scripts
* [rgomezcasas/dotfiles](https://github.com/rgomezcasas/dotfiles) - :penguin: Simple, fast, productivity-increaser dotfiles
* [miohtama/ztanesh](https://github.com/miohtama/ztanesh) - Improve your UNIX command line experience and productivity with ztanesh project: the tools will make your shell more powerful and easier to use.
* [w00fz/xdebug-osx](https://github.com/w00fz/xdebug-osx) - Simple bash script to toggle xdebug on/off in OSX
* [graysky2/pulseaudio-ctl](https://github.com/graysky2/pulseaudio-ctl) - Control pulseaudio volume from the shell or mapped to keyboard shortcuts. No need for alsa-utils.
* [jaywcjlove/shell-tutorial](https://github.com/jaywcjlove/shell-tutorial) - Shell入门教程（Shell tutorial book）
* [JoshuaMart/AutoRecon](https://github.com/JoshuaMart/AutoRecon) - Simple shell script for automated domain recognition with some tools
* [rjbaker/simple-magento-vagrant](https://github.com/rjbaker/simple-magento-vagrant) - A VERY simple Magento environment provisioner for Vagrant
* [puppylinux-woof-CE/woof-CE](https://github.com/puppylinux-woof-CE/woof-CE) - woof - the Puppy builder
* [kvz/cronlock](https://github.com/kvz/cronlock) - cronlock lets you deploy cronjobs cluster-wide without worrying about overlaps. It uses Redis to keep track of locks.
* [DFabric/DPlatform-Shell](https://github.com/DFabric/DPlatform-Shell) - Deploy self-hosted apps easily: simple, bloat-free, independent installation
* [foxundermoon/vs-shell-format](https://github.com/foxundermoon/vs-shell-format) - the shellscript、Dockerfile、properties ...... format extension
* [haskell/ghcup](https://github.com/haskell/ghcup) - DEPRECATED IN FAVOR OF haskell/ghcup-hs
* [archlinux/asp](https://github.com/archlinux/asp) - Arch Build Source Management Tool
* [ftrvxmtrx/split2flac](https://github.com/ftrvxmtrx/split2flac) - Split flac/ape/wv/wav + cue sheet into separate tracks
* [XIU2/Shell](https://github.com/XIU2/Shell) - 🐧 自用的一些乱七八糟 Linux 脚本~
* [Spearfoot/FreeNAS-scripts](https://github.com/Spearfoot/FreeNAS-scripts) - Handy shell scripts for use on FreeNAS servers
* [tokyoneon/Armor](https://github.com/tokyoneon/Armor) - Armor is a simple Bash script designed to create encrypted macOS payloads capable of evading antivirus scanners.
* [jgamblin/MacOS-Maid](https://github.com/jgamblin/MacOS-Maid) - Shell Script I Use To Automatically Clean Up My Mac.
* [breunigs/bravia-auth-and-remote](https://github.com/breunigs/bravia-auth-and-remote) - Shell snippets to auth and send remote control commands to Sony Bravia TVs
* [vlevit/notify-send.sh](https://github.com/vlevit/notify-send.sh) - drop-in replacement for notify-send with more features
* [simnalamburt/shellder](https://github.com/simnalamburt/shellder) - :shell: Featured zsh/fish shell theme
* [codecov/codecov-bash](https://github.com/codecov/codecov-bash) - Global coverage report uploader for Codecov
* [rocky/zshdb](https://github.com/rocky/zshdb) - gdb-like "trepan" debugger for zsh
* [rachpt/AutoSeed](https://github.com/rachpt/AutoSeed) - 全自动发种姬 [流程图 https://www.processon.com/view/link/5c088855e4b0ca4b40c93a49 ]
* [xonixx/makesure](https://github.com/xonixx/makesure) - Simple task/command runner with declarative goals and dependencies
* [jakewmeyer/Geo](https://github.com/jakewmeyer/Geo) - :earth_americas: A Bash utility for easy wan, lan, router, dns, mac address, and geolocation output, with clean stdout for piping
* [kward/shflags](https://github.com/kward/shflags) - shFlags is a port of the Google gflags library for Unix shell.
* [Mangeshrex/rxfetch](https://github.com/Mangeshrex/rxfetch) - A custom system info fetching tool
* [client9/shlib](https://github.com/client9/shlib) - portable functions for posix shell environments
* [mattly/bork](https://github.com/mattly/bork) - the Bash-Operated Reconciling Kludge
* [xuxiaodong/tmuxen](https://github.com/xuxiaodong/tmuxen) - tmux environment made easy.
* [denysdovhan/dotfiles](https://github.com/denysdovhan/dotfiles) - My lovely dots ~/.💖
* [laughedelic/pisces](https://github.com/laughedelic/pisces) - ♓️ Fish shell plugin that helps you to work with paired symbols in the command line
* [mitchweaver/bin](https://github.com/mitchweaver/bin) - 🗑️ helpful scripts and snippets
* [agkozak/agkozak-zsh-prompt](https://github.com/agkozak/agkozak-zsh-prompt) - A fast, asynchronous Zsh prompt with color ASCII indicators of Git, exit, SSH, virtual environment, and vi mode status. Framework-agnostic and customizable.
* [pretzelhands/jinx](https://github.com/pretzelhands/jinx) - ✨jinx - a magical nginx wrapper
* [oldmanpushcart/shell](https://github.com/oldmanpushcart/shell) - 我在unix/linux下积累的常用工具
* [ungleich/cdist](https://github.com/ungleich/cdist) - usable configuration management
* [atarallo/TECMINT_MONITOR](https://github.com/atarallo/TECMINT_MONITOR) - A Shell Script to Monitor Network, Disk Usage, Uptime, Load Average and RAM Usage in Linux. Originally published on http://www.tecmint.com
* [geekcomputers/Shell](https://github.com/geekcomputers/Shell) - Some of the handy shell scripts I have created/acquired
* [MikeMcQuaid/dotfiles](https://github.com/MikeMcQuaid/dotfiles) - :computer: My dot files shared between machines.
* [weibeld/k1s](https://github.com/weibeld/k1s) - The world's simplest Kubernetes dashboard (50 lines of Bash code)
* [codeship/scripts](https://github.com/codeship/scripts) - Scripts for use on Codeship Basic
* [rusty-bits/OC-tool](https://github.com/rusty-bits/OC-tool) - POSIX shell script that builds an OpenCore EFI folder from an OpenCore config.plist
* [IntergalacticPenguin/mobile-toolkit](https://github.com/IntergalacticPenguin/mobile-toolkit) - 📱 Command line tool for Android & iOS device management
* [Cyclenerd/gallery_shell](https://github.com/Cyclenerd/gallery_shell) - 📷 Bash Script to generate static responsive image web galleries.
* [ninrod/dotfiles](https://github.com/ninrod/dotfiles) - :octocat: Ninrod's sharpened dotfiles for emacs, vim, zsh, tmux. Since '15.
* [gaenserich/hostsblock](https://github.com/gaenserich/hostsblock) - an ad- and malware-blocking script for Linux
* [PeterMosmans/security-scripts](https://github.com/PeterMosmans/security-scripts) - A collection of security related Python and Bash shell scripts. Analyze hosts on generic security vulnerabilities. Wrapper around popular tools like nmap (portscanner), nikto (webscanner) and testssl.sh (SSL/TLS scanner)
* [h46incon/AliDDNSBash](https://github.com/h46incon/AliDDNSBash) - 阿里云域名解析动态更新（DDNS）的 Shell 脚本
* [brandonprry/wicked_cool_shell_scripts_2e](https://github.com/brandonprry/wicked_cool_shell_scripts_2e) - Full shell scripts for the second edition of Wicked Cool Shell Scripts
* [IzzySoft/Adebar](https://github.com/IzzySoft/Adebar) - Android DEvice Backup And Report, using Bash and ADB. Moved to https://codeberg.org/izzy/Adebar -- this is only a mirror now.
* [teracow/googliser](https://github.com/teracow/googliser) - a fast BASH multiple-image downloader
* [xiaoyunjie/Shell_Script](https://github.com/xiaoyunjie/Shell_Script) - Linux系统的安全，通过脚本对Linux系统进行一键检测和一键加固
* [tadly/hideIt.sh](https://github.com/tadly/hideIt.sh) - Automagically hide/show a window by its name when the cursor is within a defined region or you mouse over it.
* [justinmayer/tacklebox](https://github.com/justinmayer/tacklebox) - Framework for organizing and sharing fish shell functions
* [matthewmccullough/dotfiles](https://github.com/matthewmccullough/dotfiles) - My shell configuration
* [sheerun/dotfiles](https://github.com/sheerun/dotfiles) - My lovely dotfiles. Chocolate and unicorns.
* [bill-auger/git-branch-status](https://github.com/bill-auger/git-branch-status) - A shell script that prints out pretty git branch sync status reports
* [konstruktoid/Docker](https://github.com/konstruktoid/Docker) - Docker playground
* [grrnikos/pma](https://github.com/grrnikos/pma) - Simple shell script that installs phpMyAdmin on a Laravel Homestead box.
* [zxui/shell](https://github.com/zxui/shell) - :maple_leaf:  Centos运维常用工具
* [tlevine/urchin](https://github.com/tlevine/urchin) - Shell tests
* [bfontaine/rfc](https://github.com/bfontaine/rfc) - :page_facing_up: Read RFCs from the command-line
* [zpm-zsh/zpm](https://github.com/zpm-zsh/zpm) - Zpm— Zsh Plugin Manager
* [fabacab/git-archive-all.sh](https://github.com/fabacab/git-archive-all.sh) - A bash shell script wrapper for git-archive that archives a git superproject and its submodules, if it has any.
* [dotzero/vagrant-debian-jessie](https://github.com/dotzero/vagrant-debian-jessie) - Automatic Debian 8 Vagrant base box building on OSX, Linux and Windows
* [dylanaraps/shfm](https://github.com/dylanaraps/shfm) - file manager written in posix shell
* [njhartwell/pw3nage](https://github.com/njhartwell/pw3nage) - If you get pw3ned, might want to fix your shell
* [SixArm/sixarm_zsh_config](https://github.com/SixArm/sixarm_zsh_config) - SixArm.com → Z shell → zsh configuration
* [olets/zsh-abbr](https://github.com/olets/zsh-abbr) - The zsh manager for auto-expanding abbreviations, inspired by fish shell.
* [PhrozenByte/rmtrash](https://github.com/PhrozenByte/rmtrash) - Put files (and directories) in trash using the `trash-put` command in a way that is, otherwise as `trash-put` itself, compatible to GNUs `rm` and `rmdir`
* [IsaacSchemm/MultiCD](https://github.com/IsaacSchemm/MultiCD) - A shell script package for creating combination disks from Linux ISOs.
* [raphaelcohn/bish-bosh](https://github.com/raphaelcohn/bish-bosh) - MQTT shell script client, for bash, dash, BusyBox ash and others. Gives you MQTT on anything Unix like, from embedded routers to AIX servers with almost no dependenices.
* [jnwatts/pushover.sh](https://github.com/jnwatts/pushover.sh) - Shell script wrapper around curl for sending messages through PushOver
* [derekstavis/plugin-nvm](https://github.com/derekstavis/plugin-nvm) - Node version manager wrapper for Fish shell
* [kyle8998/Sudo-Productivity](https://github.com/kyle8998/Sudo-Productivity) - Boost your "productivity" to the max! A fun project made for slackers by slackers.
* [sickcodes/osx-optimizer](https://github.com/sickcodes/osx-optimizer) - OSX Optimizer: Optimize MacOS - Shell scripts to speed up your mac boot time, accelerate loading, and prevent unnecessary throttling.
* [risfeng/aliyun-ddns-shell](https://github.com/risfeng/aliyun-ddns-shell) - 阿里云域名解析动态更新IP Shell脚本
* [huijunchen9260/dmenufm](https://github.com/huijunchen9260/dmenufm) - A simple file manager using dmenu
* [Sepero/temp-throttle](https://github.com/Sepero/temp-throttle) - A shell script for throttling system CPU frequency based on a desired maximum temperature
* [Mr-xn/subdomain_shell](https://github.com/Mr-xn/subdomain_shell) - 一键调用subfinder+ksubdomain+httpx 强强联合 从域名发现-->域名验证-->获取域名标题、状态码以及响应大小 最后保存结果,简化重复操作命令
* [kalasutra/Clash_For_Magisk](https://github.com/kalasutra/Clash_For_Magisk) - 使用shell启动clash内核,以及创建iptables tproxy规则,以此在Android上达到透明代理的目的.
* [cryptojuice/gobrew](https://github.com/cryptojuice/gobrew) - Shell script to download and set GO environmental paths to allow multiple versions.
* [passcod/nvm-fish-wrapper](https://github.com/passcod/nvm-fish-wrapper) - NVM wrapper for the fish shell - NOT MAINTAINED
* [junbaor/shell_script](https://github.com/junbaor/shell_script) - 一键安装 shadowsocks，支持 chacha20-ietf-poly1305 加密方式
* [edouard-lopez/progress-bar.sh](https://github.com/edouard-lopez/progress-bar.sh) - Simple & sexy progress bar for `bash`, give it a duration and it will do the rest.
* [rafritts/bunit](https://github.com/rafritts/bunit) - A unit testing framework for Shell scripts - namely Bash.
* [chris-rock/vesper](https://github.com/chris-rock/vesper) - 🍸Vesper - HTTP Framework for Bash Shell
* [yutkat/dotfiles](https://github.com/yutkat/dotfiles) - The best and strongest dotfiles. Editor: Neovim(coc.nvim); Shell: zsh(zinit, powerlevel10k); Terminal: tmux, wezterm; Desktop: i3-gaps/sway, rofi, dunst; OS: ArchLinux, (Ubuntu/Fedora/CentOS)
* [chisui/zsh-nix-shell](https://github.com/chisui/zsh-nix-shell) - zsh plugin that lets you use zsh in nix-shell shells.
* [zhwj184/shell-work](https://github.com/zhwj184/shell-work) - shell常用分析命令和脚本
* [ivandavidov/minimal-linux-script](https://github.com/ivandavidov/minimal-linux-script) - One script which generates live Linux ISO image with minimal effort. Based on the first published version of Minimal Linux Live: http://github.com/ivandavidov/minimal
* [cyphunk/humanism.sh](https://github.com/cyphunk/humanism.sh) - subjective but sensible defaults for shell use. Ubuntu, OSX, FreeBSD tested.
* [wick3dr0se/sysfetch](https://github.com/wick3dr0se/sysfetch) - A super tiny system information fetch script written in BASH
* [duyuanch/shell](https://github.com/duyuanch/shell) - All useful linux shell scripts
* [davideolgiati/PartyLoud](https://github.com/davideolgiati/PartyLoud) - A simple tool to generate fake web browsing and mitigate tracking
* [barnybug-archive/docker-fish-completion](https://github.com/barnybug-archive/docker-fish-completion) - ARCHIVED: docker command completion for the fish shell
* [jreinke/modgit](https://github.com/jreinke/modgit) - Shell script for Git module deployment with include/exclude filters.
* [WazeHell/PE-Linux](https://github.com/WazeHell/PE-Linux) - Linux Privilege Escalation Tool By WazeHell
* [jiangxianli/SSHAutoLogin](https://github.com/jiangxianli/SSHAutoLogin) - 一个使用expect免输入密码自动登录ssh的shell脚本，方便好用,适用Mac、Linux
* [ko1nksm/getoptions](https://github.com/ko1nksm/getoptions) - An elegant option/argument parser for shell scripts (full support for bash and all POSIX shells)
* [sharkdp/trigger](https://github.com/sharkdp/trigger) - Run a user-defined command on file changes
* [exceedhl/toft](https://github.com/exceedhl/toft) - toft is a library currently supporting testing infrastructure code such as chef, shell scripts with cucumber and lxc on linux machine
* [dominiksalvet/asus-fan-control](https://github.com/dominiksalvet/asus-fan-control) - Fan control for ASUS devices running Linux
* [aqingsao/nana](https://github.com/aqingsao/nana) - A lightweight Nginx log analyzer written in shell(statistics of traffic/rate/response time/upstream servers/spiders/response codes)
* [SpiderLabs/jboss-autopwn](https://github.com/SpiderLabs/jboss-autopwn) - A JBoss script for obtaining remote shell access
* [LevisWings/Auto-PWE](https://github.com/LevisWings/Auto-PWE) - Script en Bash que te permite convertir una distribución de Linux en un entorno de trabajo profesional de manera automática.
* [dylanaraps/promptless](https://github.com/dylanaraps/promptless) - 🚀 A super fast and extremely minimal shell prompt.
* [anapsix/zabbix-haproxy](https://github.com/anapsix/zabbix-haproxy) - HAProxy Zabbix Discovery and Template
* [hachibu/note.sh](https://github.com/hachibu/note.sh) - A simple shell script for managing your notes.
* [oh-my-fish/packages-main](https://github.com/oh-my-fish/packages-main) - Primary Oh My Fish package repository.
* [loftuxab/alfresco-ubuntu-install](https://github.com/loftuxab/alfresco-ubuntu-install) - Alfresco script based install for Ubuntu
* [joukewitteveen/netctl](https://github.com/joukewitteveen/netctl) - Profile based systemd network management
* [arcticicestudio/nord-xfce-terminal](https://github.com/arcticicestudio/nord-xfce-terminal) - An arctic, north-bluish clean and elegant Xfce Terminal color theme.
* [OutsideIT/FireMotD](https://github.com/OutsideIT/FireMotD) - :fire: Fire Framework Linux MoTD Generator :fire:
* [paul-nelson-baker/git-openssl-shellscript](https://github.com/paul-nelson-baker/git-openssl-shellscript) - Shellscript to compile git with OpenSSL
* [Mr-Linus/login-shell](https://github.com/Mr-Linus/login-shell) - SSH登陆显示脚本
* [joelagnel/adeb](https://github.com/joelagnel/adeb) - A debian-based shell environment designed for Android and adb
* [Cyb0r9/winspy](https://github.com/Cyb0r9/winspy) - WinSpy a Windows reverse shell Backdoor creator with an Automatic IP Poisener
* [thecasualcoder/kube-fzf](https://github.com/thecasualcoder/kube-fzf) - Shell commands using kubectl and fzf for command-line fuzzy searching of Kubernetes Pods.
* [myplaceonline/posixcube](https://github.com/myplaceonline/posixcube) - posixcube.sh is a POSIX compliant, shell script-based server automation framework.
* [chenxiaolong/Unity-for-Arch](https://github.com/chenxiaolong/Unity-for-Arch) - Porting Ubuntu's Unity Shell to Arch Linux
* [M1Screw/Airport-toolkit](https://github.com/M1Screw/Airport-toolkit) - 各類方便機場主進行安裝維護的shell腳本
* [EugeneDae/Force-Paste](https://github.com/EugeneDae/Force-Paste) - Paste text even when not allowed (password dialogs etc) in macOS
* [qdaxb/wtool](https://github.com/qdaxb/wtool) - shell toolkit
* [aurasphere/mongodb-university-classes](https://github.com/aurasphere/mongodb-university-classes) - Courseware and solutions of problems from MongoDB University's classes that I've attended.
* [PacktPublishing/Linux-Shell-Scripting-Cookbook-Third-Edition](https://github.com/PacktPublishing/Linux-Shell-Scripting-Cookbook-Third-Edition) - Linux Shell Scripting Cookbook Third Edition, published by Packt
* [Akianonymus/gdrive-downloader](https://github.com/Akianonymus/gdrive-downloader) - Download a gdrive folder or file easily, shell ftw.
* [SimonBaeumer/shell-tricks](https://github.com/SimonBaeumer/shell-tricks) - Simple bash tricks which make your life easier.
* [KnpLabs/symfony2-autocomplete](https://github.com/KnpLabs/symfony2-autocomplete) - A very simple script to autocomplete Symfony2 commands in a bash shell.
* [solidsnack/arx](https://github.com/solidsnack/arx) - Bundles code and a job to run for local or remote execution.
* [LLNL/magpie](https://github.com/LLNL/magpie) - Magpie contains a number of scripts for running Big Data software in HPC environments, including Hadoop and Spark. There is support for Lustre, Slurm, Moab, Torque. LSF, and more.
* [shibli2700/Rekon](https://github.com/shibli2700/Rekon) - The project contains multiple shell scripts for automating the tasks during recon.
* [rupa/j](https://github.com/rupa/j) - semi clone of autojump (http://github.com/joelthelion/autojump) in shell/awk
* [rafaelstz/simplesh](https://github.com/rafaelstz/simplesh) - :penguin: Quick installation for Ubuntu terminal.
* [muhmud/qsh](https://github.com/muhmud/qsh) - shell-based query tool
* [vcheckzen/FamilyCloudSpeederInShell](https://github.com/vcheckzen/FamilyCloudSpeederInShell) - [ 天翼家庭云/天翼云盘提速 Shell 版 ] A Shell Implementation of FamilyCloudSpeeder, ESurfing
* [meefik/linuxdeploy-cli](https://github.com/meefik/linuxdeploy-cli) - Linux Deploy CLI
* [scponly/scponly](https://github.com/scponly/scponly) - The scponly pseudo-shell provides a file-transfer only shell for *Nix systems with optional support for using a chrooted environment.
* [katernet/darkmode](https://github.com/katernet/darkmode) - Set macOS dark mode and Alfred dark theme at sunset
* [homebysix/jss-filevault-reissue](https://github.com/homebysix/jss-filevault-reissue) - A framework for re-escrowing missing or invalid FileVault keys with Jamf Pro.
* [shubhampathak/autosetup](https://github.com/shubhampathak/autosetup) - Auto setup is a bash script compatible with Debian based distributions to install and setup necessary programs.
* [ludeeus/action-shellcheck](https://github.com/ludeeus/action-shellcheck) - GitHub action for ShellCheck.
* [sentora/sentora-installers](https://github.com/sentora/sentora-installers) - Provides a central place to store, version and distribute the Sentora installer and upgrade scripts from.
* [microsoft/shell-intune-samples](https://github.com/microsoft/shell-intune-samples) - Sample shell scripts for Intune admins.
* [jandamm/zgenom](https://github.com/jandamm/zgenom) - A lightweight and fast plugin manager for ZSH
* [NullArray/MIDA-Multitool](https://github.com/NullArray/MIDA-Multitool) - Bash script purposed for system enumeration, vulnerability identification and privilege escalation.
* [brunelli/gnome-shell-extension-installer](https://github.com/brunelli/gnome-shell-extension-installer) - A bash script to search and install extensions from extensions.gnome.org
* [MarioCatuogno/Clean-macOS](https://github.com/MarioCatuogno/Clean-macOS) - 💻 A simple script to setup a clean environment on macOS
* [Comcast/k8sh](https://github.com/Comcast/k8sh) - A simple, easily extensible shell for navigating your kubernetes clusters
* [spf-tools/spf-tools](https://github.com/spf-tools/spf-tools) - Shell scripts for taming the SPF (Sender Policy Framework) records in order to fight 10-maximum-DNS-look-ups limit.
* [rukshn/pomodoro](https://github.com/rukshn/pomodoro) - A simple pomodoro shell script
* [busterc/xcv](https://github.com/busterc/xcv) - :scissors: Cut, Copy and Paste files with Bash
* [zmalltalker/fish-nuggets](https://github.com/zmalltalker/fish-nuggets) - Completions, code snippets helping you to get even more out of the amazing Fish shell
* [zpm-zsh/autoenv](https://github.com/zpm-zsh/autoenv) - Autoenv for zsh
* [hagen1778/grafana-import-export](https://github.com/hagen1778/grafana-import-export) - shell scripts for importing and exporting Grafana's dashboards and datasources
* [Anvil/bash-argsparse](https://github.com/Anvil/bash-argsparse) - An high level argument parsing library for bash
* [gmarik/gist.sh](https://github.com/gmarik/gist.sh) - Bash shell script for getting/posting code snippets (gists) from/to https://gist.github.com
* [OliverLew/fontpreview-ueberzug](https://github.com/OliverLew/fontpreview-ueberzug) - A POSIX shell script to preview fonts in fzf
* [sundowndev/covermyass](https://github.com/sundowndev/covermyass) - Shell script to cover your tracks on UNIX systems. Designed for pen testing "covering tracks" phase, before exiting the infected server. Or, permanently disable system logs for post-exploitation.
* [jgamblin/quickinstall](https://github.com/jgamblin/quickinstall) - A Shell Script To Take Care Of Ubuntu Basics
* [gmacario/easy-build](https://github.com/gmacario/easy-build) - Collection of Dockerfiles for building embedded software distributions
* [wulabing/SSR-manyuser_glzjin_shell](https://github.com/wulabing/SSR-manyuser_glzjin_shell) - sspanel v3 魔改版 后端一键安装配置管理脚本
* [wschlich/bashinator](https://github.com/wschlich/bashinator) - Bashinator: Bash Shell Script Framework
* [qzb/is.sh](https://github.com/qzb/is.sh) - Human readable conditions for bash 👌
* [fenglh/IPABuildShell](https://github.com/fenglh/IPABuildShell) - IPABuildShell  一个强大的、轻量的 iOS 自动打包工具，无需手动指定授权文件和证书
* [silvio/docker-matrix](https://github.com/silvio/docker-matrix) - docker image for matrix.org
* [shannonmoeller/up](https://github.com/shannonmoeller/up) - Quickly navigate to a parent directory via tab-completion.
* [jirutka/esh](https://github.com/jirutka/esh) - Simple templating engine based on shell.
* [bkuhlmann/dotfiles](https://github.com/bkuhlmann/dotfiles) - Shell scripts for applying default settings to UNIX-based operating systems.
* [rudiratlos/hotspot](https://github.com/rudiratlos/hotspot) - shell script for setup and management of hotspot (hostapd) function on rpi plattform
* [phyver/GameShell](https://github.com/phyver/GameShell) - a game to learn (or teach) how to use standard commands in a Unix shell
* [justinmayer/tackle](https://github.com/justinmayer/tackle) - Collection of fish shell functions, modules, plugins, and themes
* [woefe/git-prompt.zsh](https://github.com/woefe/git-prompt.zsh) - A fast, customizable, pure-shell, asynchronous Git prompt for Zsh
* [trapd00r/zsh-syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - zsh syntax highlighting with dircolors in realtime
* [dysosmus/ansible-completion](https://github.com/dysosmus/ansible-completion) - Basic bash completion for Ansible
* [64kramsystem/zfs-installer](https://github.com/64kramsystem/zfs-installer) - Shell script program that prepares ZFS on a system, and installs Linux
* [rogalmic/vscode-bash-debug](https://github.com/rogalmic/vscode-bash-debug) - Bash shell debugger extension for VSCode (based on bashdb)
* [lilyball/nix-env.fish](https://github.com/lilyball/nix-env.fish) - Nix environment setup for the fish shell
* [jamielinux/bashmount](https://github.com/jamielinux/bashmount) - Tool to mount and unmount removable media from the command-line
* [goodboy23/shell-script-collection](https://github.com/goodboy23/shell-script-collection) - shell小框架，地址：http://www.linkops.cn/363.htm
* [sjl/z-fish](https://github.com/sjl/z-fish) - A fork of http://github.com/rupa/z to port it to the Fish shell.
* [pathikrit/mac-setup-script](https://github.com/pathikrit/mac-setup-script) - script to setup my mac
* [pschmitt/pia-tools](https://github.com/pschmitt/pia-tools) - Shell script to automate privateinternetaccess port forwarding and starting/stopping transmission when connected/disconnected and other stuff
* [nixcraft/domain-check-2](https://github.com/nixcraft/domain-check-2) - Domain Expiration Check Shell Script Forked and Maintained by nixCraft
* [bing0o/bash_scripting](https://github.com/bing0o/bash_scripting) - bash scripting thing !
* [vinhnx/Ciapre-Xcode-theme](https://github.com/vinhnx/Ciapre-Xcode-theme) - An easy on the eyes Xcode color scheme, ported from Ciapre Sublime Text.
* [raphaelcohn/swaddle](https://github.com/raphaelcohn/swaddle) - swaddle creates RPM, Deb and tarball packages using shell script. Everything you need to package is in Source Control in simple directories. No rpminfo cruft, no DEB makefile hell. No Python, Ruby, Perl or other unnecessary stuff required
* [kobe1941/shell](https://github.com/kobe1941/shell) - 一个根据linkMap文件计算Xcode里各个工程代码占安装包大小的工具
* [icy/bocker](https://github.com/icy/bocker) - Write Dockerfile completely in Bash/Bourne. Extensible and simple.
* [pstadler/metrics.sh](https://github.com/pstadler/metrics.sh) - Collect and forward metrics using portable shell scripts
* [nhoffman/argparse-bash](https://github.com/nhoffman/argparse-bash) - Use python's argparse module in shell scripts
* [luckylz2git/exfat-synology](https://github.com/luckylz2git/exfat-synology) - Perfect shell scripts to auto mount exfat disk partition on Synology DiskStation NAS (x86 platform), and more post-mount functions are coming soon! Use this at your own risks.
* [samoshkin/tmux-plugin-sysstat](https://github.com/samoshkin/tmux-plugin-sysstat) - Prints CPU usage, memory & swap, load average, net I/O metrics in Tmux status bar
* [rpranshu/EternalView](https://github.com/rpranshu/EternalView) - EternalView is an all in one basic information gathering and vulnerability assessment tool
* [qfish/xproj](https://github.com/qfish/xproj) - A shell script can batch adding compile flags like `-fno-objc-arc`or `-fobjc-arc` for all the files under the same dir by processing the project file.
* [alex7kom/nvm-fish](https://github.com/alex7kom/nvm-fish) - Node Version Manager for fish shell - **NO LONGER MAINTAINED, DO NOT USE** - Use https://github.com/edc/bass instead to wrap the original nvm.
* [StanAngeloff/vagrant-shell-scripts](https://github.com/StanAngeloff/vagrant-shell-scripts) - A collection of scripts to ease Vagrant box provisioning using the shell.
* [ramnes/context-color](https://github.com/ramnes/context-color) - :rainbow: To each context its own shell color
* [gavinlyonsrepo/cylon](https://github.com/gavinlyonsrepo/cylon) - A CLI TUI menu driven bash shell script supporting updates, maintenance, backups and system checks for an Arch based Linux distro
* [zma/usefulscripts](https://github.com/zma/usefulscripts) - Useful Shell scripts on Linux or macOS
* [tengla/sqlite3-to-mysql](https://github.com/tengla/sqlite3-to-mysql) - Make an Sqlite3 export MySQL readable.
* [excalibur1234/pacui](https://github.com/excalibur1234/pacui) - Bash script providing advanced Pacman and Yay/Pikaur/Aurman/Pakku/Trizen/Pacaur/Pamac-cli functionality in a simple UI
* [connermcd/gtd](https://github.com/connermcd/gtd) - A simple shell script for effective time management.
* [cfg2html/cfg2html](https://github.com/cfg2html/cfg2html) - cfg2html is a UNIX shell script similar to supportinfo, getsysinfo or get_config, except that it creates a HTML (and plain ASCII) system documentation for HP-UX, SCO-UNIX, AIX, Sun OS and Linux systems. Plug-ins for SAP, Oracle, Informix, Serviceguard, Fiber Channel/SAN, TIP/ix, OpenText (IXOS/LEA), SN Mass Storage like MAS, EMC, EVA, XPs, Network Node Manager and DataProtector etc. are included. The first versions of cfg2html were written for HP-UX. Meanwhile the cfg2html HP-UX stream was ported to all major *NIX platforms and small embedded systems.
* [ash-shell/ash](https://github.com/ash-shell/ash) - :shell: A Modular Bash Framework
* [rcmdnk/sentaku](https://github.com/rcmdnk/sentaku) - Utility to make sentaku (selection, 選択(sentaku)) window with shell command.
* [kkkgo/CloudXNS-DDNS-with-BashShell](https://github.com/kkkgo/CloudXNS-DDNS-with-BashShell) - The CloudXNS DDNS with BashShell
* [jalendport/switch-php](https://github.com/jalendport/switch-php) - Easily switch between PHP versions on your Mac. Requires Homebrew and works with Laravel Valet. 🔀
* [shellbound/jwalk](https://github.com/shellbound/jwalk) - Streaming JSON parser for Unix
* [cornerpirate/socat-shell](https://github.com/cornerpirate/socat-shell) - Socat can be used to establish a reverse shell with bash tab completion and full shell functionality
* [mm2270/JamfProScripts](https://github.com/mm2270/JamfProScripts) - A collection of shell scripts created for use in Jamf Pro and elsewhere
* [0rax/fish-bd](https://github.com/0rax/fish-bd) - Quickly go back to a parent directory up in your current working directory tree. Don't write 'cd ../../..' redundantly, use bd instead.
* [connermcd/notes](https://github.com/connermcd/notes) - Shell script for compiling pdf/html notes with pandoc.
* [Diolinux/Linux-Mint-19.x-PosInstall](https://github.com/Diolinux/Linux-Mint-19.x-PosInstall) - Shell Script de pós instalação do Linux Mint 19.x para utilização pessoal.
* [sloria/dotfiles](https://github.com/sloria/dotfiles) - sloria's dotfiles as Ansible roles
* [mritd/shell_scripts](https://github.com/mritd/shell_scripts) - 常用的一些 shell 脚本
* [haxpor/aseprite-macos-buildsh](https://github.com/haxpor/aseprite-macos-buildsh) - Automated script to create latest release app (either beta, or release whichever is newer) of Aseprite for macOS
* [chrismdp/p](https://github.com/chrismdp/p) - A simple yet powerful pomodoro tracker in pure Shell
* [benmarten/Monokai_Fish_OSX](https://github.com/benmarten/Monokai_Fish_OSX) - Monokai Theme for OS X Terminal & Fish Shell
* [OzzyCzech/dotfiles](https://github.com/OzzyCzech/dotfiles) - OzzyCzech dotfiles for macOS
* [IcaliaLabs/kaishi](https://github.com/IcaliaLabs/kaishi) - A shell script to convert any Mac OS X or Linux computer into a real development machine
* [Ethical-Hacking-Zone/shellphish](https://github.com/Ethical-Hacking-Zone/shellphish) - An Official Re-Upload Of The ShellPhish Tool In Github
* [xwmx/hosts](https://github.com/xwmx/hosts) - A command line hosts file editor in one portable script.
* [htr-tech/termux-shell](https://github.com/htr-tech/termux-shell) - Beautify your Termux App with this Shell 😍
* [brigand/fast-nvm-fish](https://github.com/brigand/fast-nvm-fish) - a wrapper around node version manager for fish shell with good performance
* [RenatGilmanov/shell-script-template](https://github.com/RenatGilmanov/shell-script-template) - Simple (and hopefully useful) shell script template
* [cytopia/thunar-custom-actions](https://github.com/cytopia/thunar-custom-actions) - Custom actions for Thunar (or Nautilus) File manager
* [alphapapa/bucket](https://github.com/alphapapa/bucket) - A bucket for your shell (like a set of registers, or a clipboard manager)
* [liungkejin/Bash-Games](https://github.com/liungkejin/Bash-Games) - LINUX终端下的贪吃蛇(Snake), 屏保(ClockSaver), 俄罗斯方块(Tetris)游戏(使用Bash shell编写)
* [csev/uninstall-python3](https://github.com/csev/uninstall-python3) - A Simple Shell Script to Uninstall Python 3 versions from Mac OS/X
* [chesty/overlayroot](https://github.com/chesty/overlayroot) - mounts an overlay file system over root
* [tony/.dot-config](https://github.com/tony/.dot-config) - :books: Example dot configs for tmux, tmuxp, vim, vcspull, i3 and awesome
* [miohtama/sublime-helper](https://github.com/miohtama/sublime-helper) - sublime-helper is a shell script collection to setup Sublime Text configuration files and command line aliases based on predefined templates.
* [lucascbeyeler/zmbackup](https://github.com/lucascbeyeler/zmbackup) - A reliable software written in Shell Script to help you in your daily task to backup and restore mails and accounts from Zimbra Open Source Email Platform. Project in deprecation process. Please help me with Waddles.
* [arzzen/calc.plugin.zsh](https://github.com/arzzen/calc.plugin.zsh) - zsh calculator - with support for basic math
* [wentmac/mysql_backup](https://github.com/wentmac/mysql_backup) - mysql数据库定时增量和全量备份的shell
* [hannob/tlshelpers](https://github.com/hannob/tlshelpers) - A collection of shell scripts that help handling X.509 certificate and TLS issues
* [snwh/fedora-post-install](https://github.com/snwh/fedora-post-install) - A set of post-installation shell scripts for Fedora
* [rsvp/speedtest-linux](https://github.com/rsvp/speedtest-linux) - Get download/upload speeds via speedtest.net or fast.com from command line using Bash script -- suitable for logs. POSIX OSX Linux
* [haideralipunjabi/polybar-kdeconnect](https://github.com/haideralipunjabi/polybar-kdeconnect) - KDEConnect module for Polybar
* [TristanBrotherton/netcheck](https://github.com/TristanBrotherton/netcheck) - A shell script to check and log when your internet connection goes down.
* [Fakerr/goto](https://github.com/Fakerr/goto) - Navigate long command lines using a minimalistic char-based decision tree.
* [sjhcockrell/gsd](https://github.com/sjhcockrell/gsd) - WasteNoTime not working? A shell script to keep you distraction-free while you work.
* [breinhart/Lua-In-Xcode](https://github.com/breinhart/Lua-In-Xcode) - A shell script and xclanspec to add Lua syntax support in Xcode
* [vercel/install-node](https://github.com/vercel/install-node) - Simple one-liner shell script that installs official Node.js binaries
* [trozler/whereAmI](https://github.com/trozler/whereAmI) - A short shell script that returns you your IPv4 address and its geolocation.
* [fmahnke/shell-semver](https://github.com/fmahnke/shell-semver) - Increment semantic versioning strings in Bash shell scripts.
* [seebi/rdf.sh](https://github.com/seebi/rdf.sh) - A multi-tool shell script for doing Semantic Web jobs on the command line.
* [rwxrob/dot](https://github.com/rwxrob/dot) - Personal and professional dotfiles to setup my personal workspace on any Debian/Ubuntu system. Also available as rwxrob/workspace container.
* [blueimp/shell-scripts](https://github.com/blueimp/shell-scripts) - A collection of (mostly POSIX compatible) shell scripts.
* [pythops/jetson-nano-image](https://github.com/pythops/jetson-nano-image) - Create a minimalist, Ubuntu based image for Nvidia jetson nano board
* [marlonrichert/zsh-launchpad](https://github.com/marlonrichert/zsh-launchpad) - 🚀 Simple, educational dotfiles template to get started with Zsh and learn about its features
* [hphde/yeelight-shell-scripts](https://github.com/hphde/yeelight-shell-scripts) - Control Xiaomi Mi Yeelight (RGB) with bash scripts
* [Rasukarusan/shellnium](https://github.com/Rasukarusan/shellnium) - :dizzy: Selenium Webdriver for Bash (or Zsh).
* [MoOx/setup](https://github.com/MoOx/setup) - My setup... dotfiles, aliases, functions, preferences, apps. Everything.
* [dmi3/bin](https://github.com/dmi3/bin) - Useful scripts and configs for Linux users
* [blacklabelops-legacy/jenkins](https://github.com/blacklabelops-legacy/jenkins) - Docker Jenkins Swarm-Ready with HTTPS
* [BrodieRobertson/scripts](https://github.com/BrodieRobertson/scripts) - Messing around with shell scripting because it seems like fun, maybe you'll find something useful
* [yousefvand/shellman](https://github.com/yousefvand/shellman) - vscode shell script snippet extension
* [jimeh/zsh-peco-history](https://github.com/jimeh/zsh-peco-history) - Search shell history with peco when pressing ctrl+r.
* [dalibo/pitrery](https://github.com/dalibo/pitrery) - DEPRECATED. PostgreSQL Point In Time Recovery made easy
* [coderofsalvation/powscript](https://github.com/coderofsalvation/powscript) - transpiler written in bash: painless shellscript, indentbased, coffee for the shell with hipster-sparkles v1 BETA LANDED 🎉🎉🎉🎉 thanks fcard!
* [Ljohn001/ljohn_ops](https://github.com/Ljohn001/ljohn_ops) - Linux运维工作中常用的shell脚本
* [qbit/ohmyksh](https://github.com/qbit/ohmyksh) - A framework for OpenBSD's ksh
* [kolbasa/git-repo-watcher](https://github.com/kolbasa/git-repo-watcher) - A simple bash script to watch a git repository and pull upstream changes if needed.
* [4bitfocus/asc-key-to-qr-code](https://github.com/4bitfocus/asc-key-to-qr-code) - Shell scripts to convert between ascii armor PGP keys and QR codes for paper backup
* [rsp/scripts](https://github.com/rsp/scripts) - Random shell scripts for different tasks
* [jlrodriguezf/WhatsPwn](https://github.com/jlrodriguezf/WhatsPwn) - Linux tool used to extract sensitive data, inject backdoor or drop remote shells on android devices.
* [ggustafsson/Tim](https://github.com/ggustafsson/Tim) - Terminal countdown timer with several modes written in Zsh shell script.
* [crclark96/ginh](https://github.com/crclark96/ginh) - ginh is not a histogram: visually evaluate your shell usage patterns
* [vijithassar/lit](https://github.com/vijithassar/lit) - a little preprocessor for literate programming
* [devploit/put2win](https://github.com/devploit/put2win) - Script to automate PUT HTTP method exploitation to get shell
* [b1izzard-34/Dynamic-gnome-wallpapers](https://github.com/b1izzard-34/Dynamic-gnome-wallpapers) - Day night wallpapers for gnome-shell
* [arcticicestudio/nord-termite](https://github.com/arcticicestudio/nord-termite) - An arctic, north-bluish clean and elegant Termite color theme.
* [rickfarmer/android-vm](https://github.com/rickfarmer/android-vm) - Automated provisioning and configuration of an Ubuntu VM containing the Android development environment, including Android ADT Bundle with SDK, Eclipse & the Android NDK using the Vagrant DevOps tool with Chef and shell-scripts.
* [grml/grml-live](https://github.com/grml/grml-live) - build system for creating a Grml (based) live system
* [SkypLabs/bsfl](https://github.com/SkypLabs/bsfl) - Bash Shell Function Library
* [ssh0/dot](https://github.com/ssh0/dot) - Simplest dotfiles manager written in shellscript :shell:
* [louwrentius/PPSS](https://github.com/louwrentius/PPSS) - Parallel Processing Shell Script
* [abemassry/wsend-gpg](https://github.com/abemassry/wsend-gpg) - Encrypted end to end file transfer
* [Roshan-R/termv](https://github.com/Roshan-R/termv) - A terminal iptv player written in bash
* [vcheckzen/XunleiKuainiaoInShell](https://github.com/vcheckzen/XunleiKuainiaoInShell) - [ 迅雷快鸟 Shell 版 ] A Shell Implementation of Kuainiao, Xunlei
* [Jintin/aliasme](https://github.com/Jintin/aliasme) - A shell script to memorize your command in command line.
* [neuronalmotion/qtrpi](https://github.com/neuronalmotion/qtrpi) - An easy-to-use environment to cross-compile Qt applications for Raspberry Pi from your desktop.
* [haslersn/any-nix-shell](https://github.com/haslersn/any-nix-shell) - fish and zsh support for the nix run and nix-shell environments of the Nix package manager
* [bookfere/KindleEar-Uploader](https://github.com/bookfere/KindleEar-Uploader) - 适用于 GAE 云端 Shell 的 KindleEar上传脚本。
* [aspiers/shell-env](https://github.com/aspiers/shell-env) - Adam's shell environment (bash/zsh) including a bunch of handy home-made utilities
* [arcticicestudio/nord-tilix](https://github.com/arcticicestudio/nord-tilix) - An arctic, north-bluish clean and elegant Tilix color scheme.
* [zerobyte-id-bak/Bashter](https://github.com/zerobyte-id-bak/Bashter) - Web Crawler, Scanner, and Analyzer Framework (Shell-Script based)
* [techwizrd/fishmarks](https://github.com/techwizrd/fishmarks) - Bookmark and jump to directories faster than a sailfish! Fishmarks is a clone of bashmarks for the Fish shell.
* [ddddavidmartin/Pre-commit-hooks](https://github.com/ddddavidmartin/Pre-commit-hooks) - A set of useful (and documented!) git pre-commit hooks.
* [Manas140/sh](https://github.com/Manas140/sh) - Collection Of My Sh Scripts.
* [tokyoneon/Arcane](https://github.com/tokyoneon/Arcane) - Arcane is a simple script designed to backdoor iOS packages (iphone-arm) and create the necessary resources for APT repositories.
* [tobiasBora/Scribd-downloader](https://github.com/tobiasBora/Scribd-downloader) - A little shell script to download a pdf file from a scribd document. This script isn't perfect, but it's enough for me.
* [jichu4n/fish-command-timer](https://github.com/jichu4n/fish-command-timer) - Fish shell extension for printing execution time for each command.
* [htr-tech/bash2mp4](https://github.com/htr-tech/bash2mp4) - Video Downloader for Termux .
* [primaryobjects/vpndemon](https://github.com/primaryobjects/vpndemon) - Monitor a VPN connection on Linux and kill a process upon disconnect
* [kward/log4sh](https://github.com/kward/log4sh) - log4sh is an advanced logging framework for Unix shell scripts.
* [jotyGill/ezsh](https://github.com/jotyGill/ezsh) - quickly install zsh, oh-my-zsh with power-level-9k zsh-completions zsh-autosuggestions zsh-syntax-highlighting history-substring-search
* [zsenliao/shellMonitor](https://github.com/zsenliao/shellMonitor) - 一个 Linux 下基于 Bash 的文件和数据库监控及备份工具，可发送微信报警通知
* [nyarly/simplekey](https://github.com/nyarly/simplekey) - Compatible shell scripts to make GnuPG more accessible and easier to use.
* [nicolinuxfr/macOS-post-installation](https://github.com/nicolinuxfr/macOS-post-installation) - Script d'installation et de configuration d'un Mac
* [luminousmen/Kgif](https://github.com/luminousmen/Kgif) -  :neckbeard: Tool for creating gif file from capturing active window.
* [kdeldycke/dotfiles](https://github.com/kdeldycke/dotfiles) - :wrench: macOS dotfiles for Python developers.
* [p-mng/proton-ge-custom-updater](https://github.com/p-mng/proton-ge-custom-updater) - Simple updater for custom Proton distributions
* [alebcay/pushblast](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits.
* [Jader/GreenBox](https://github.com/Jader/GreenBox) -  :game_die: 娱乐项目，使用 Crontab 定时提交 Commits。点亮绿格子；对就是绿
* [wilsonmar/git-utilities](https://github.com/wilsonmar/git-utilities) - :octocat: Shell scripts to work with git repos
* [tlrobinson/martin.sh](https://github.com/tlrobinson/martin.sh) - A simple web server and Sinatra-like microframework written in shell script. Why? WHY NOT?
* [six-ddc/v2ex-shell-client](https://github.com/six-ddc/v2ex-shell-client) - A v2ex command-line client for shell
* [qbit/snap](https://github.com/qbit/snap) - OpenBSD upgrade tool (OpenBSD,Shell)
* [nodesocket/cryptr](https://github.com/nodesocket/cryptr) - A simple shell utility for encrypting and decrypting files using OpenSSL.
* [kenzok8/Trojan](https://github.com/kenzok8/Trojan) - Trojan onekey install shell  Trojan && trojan.go一键脚本
* [janosgyerik/shellscripts](https://github.com/janosgyerik/shellscripts) - Convenient shell scripts for everyday use, written in Bash, Perl, awk, Python
* [gliyao/SketchToXcode](https://github.com/gliyao/SketchToXcode) - Exporting assets(App icon and icons) from sketch to your Xcode Images.xcassets via shell script.
* [brianreumere/gandi-automatic-dns](https://github.com/brianreumere/gandi-automatic-dns) - A Bourne shell script to update Gandi.net zonefiles
* [garrylachman/covid19-cli](https://github.com/garrylachman/covid19-cli) - Corona Virus (Covid 19) BASH Tracking CLI
* [fengzmg/clean-my-mac](https://github.com/fengzmg/clean-my-mac) - Shell Scripts to clean my mac
* [xHak9x/Hak9Tools](https://github.com/xHak9x/Hak9Tools) - All Hak9 Tools
* [toniblyx/alfresco-backup-and-recovery-tool](https://github.com/toniblyx/alfresco-backup-and-recovery-tool) - Alfresco BART is a tool written in shell script on top of Duplicity to do Alfresco backups and restore from a local file system, FTP, SCP or Amazon S3.
* [kevinSuttle/dotfiles](https://github.com/kevinSuttle/dotfiles) - My humble list of ~/.dotfiles: an opinionated attempt for a cross-shell setup.
* [dyne/JaroMail](https://github.com/dyne/JaroMail) - A commandline tool to easily and privately handle your e-mail
* [JeanMertz/chruby-fish](https://github.com/JeanMertz/chruby-fish) - Thin wrapper around chruby to make it work with the Fish shell
* [sakshamsharma/zpyi](https://github.com/sakshamsharma/zpyi) - The power of python in your Zsh - Unobtrusive and easy python scripting in shell
* [rcrowley/json.sh](https://github.com/rcrowley/json.sh) - Pure-shell JSON parser
* [ValeriyKr/sfb](https://github.com/ValeriyKr/sfb) - Flappy Bird clone, written in sed
* [spencertipping/cd](https://github.com/spencertipping/cd) - A better "cd" for bash
* [nickjj/notes](https://github.com/nickjj/notes) - A zero dependency shell script that makes it really simple to manage your text notes.
* [mediabots/Linux-to-Windows-with-QEMU](https://github.com/mediabots/Linux-to-Windows-with-QEMU) - One Script for Auto installation of Windows Server into a Linux Server.  Script would install Windows Server 2012 R2 evaluation copy (180 days free trial).  A power shell script to enable Remote Desktop + Firefox installer attached into the CD-ROM.
* [mattstauffer/syncCraft](https://github.com/mattstauffer/syncCraft) - Simple shell script to sync Craft DB & assets down locally
* [lonecloud/ssh-tools](https://github.com/lonecloud/ssh-tools) - :sob:没找到好用的shell工具:v:自己实现类似Xshell的部分功能
* [xtonousou/ship](https://github.com/xtonousou/ship) - A simple, handy network addressing multitool with plenty of features
* [shellscriptx/shellbot](https://github.com/shellscriptx/shellbot) - API em Shell Script para desenvolvimento de Bots na plataforma Telegram.
* [muhasturk/ukupgrade](https://github.com/muhasturk/ukupgrade) - Upgrade latest kernel automatically for Ubuntu and derivatives such as Linux Mint. :runner:
* [liuran001/GJZS](https://github.com/liuran001/GJZS) - 搞机助手·R（原「搞机助手重制版」）
* [kewlbear/fdk-aac-build-script-for-iOS](https://github.com/kewlbear/fdk-aac-build-script-for-iOS) - Shell script to build fdk-aac for use in iOS apps.
* [joewalnes/go-getter](https://github.com/joewalnes/go-getter) - Like 'go get' but with pinned package versions. A tiny shell script.
* [esemeniuc/ezpptp](https://github.com/esemeniuc/ezpptp) - Easy PPTP VPN setup script for Debian based VPS
* [bdamele/unix-privesc-check](https://github.com/bdamele/unix-privesc-check) - Shell script that runs on UNIX systems (tested on Solaris 9, HPUX 11, various Linux distributions, FreeBSD 6.2). It detects misconfigurations that could allow local unprivileged user to escalate to other users (e.g. root) or to access local apps (e.g. databases). This is a collaborative rework of version 1.0
* [mroth/evalcache](https://github.com/mroth/evalcache) - :hatching_chick: zsh plugin to cache eval loads to improve shell startup time
* [jnewland/kubernetes-pod-chaos-monkey](https://github.com/jnewland/kubernetes-pod-chaos-monkey) - Randomly delete pods in a given namespace
* [jaromaz/yosild](https://github.com/jaromaz/yosild) - Your simple Linux distro - Yosild is a single shell script that builds a full, minimal Linux distribution based on BusyBox.
* [holman/bandwidth-friends](https://github.com/holman/bandwidth-friends) - A shell script for macOS that makes sure you are being nice to your nice coffeeshop internet neighbors. 💖
* [g0r60n/InstaShell](https://github.com/g0r60n/InstaShell) - InstaShell
* [fehawen/dotfiles](https://github.com/fehawen/dotfiles) - A better $HOME.
* [duydo/evm](https://github.com/duydo/evm) - A Simple Elasticsearch Version Manager
* [cvmiller/v6brouter](https://github.com/cvmiller/v6brouter) - IPv6 bridge and IPv4 router (NAT) shell script for OpenWRT
* [geerlingguy/JJG-Ansible-Windows](https://github.com/geerlingguy/JJG-Ansible-Windows) - [DEPRECATED] Windows shell provisioning script to bootstrap Ansible from within a Vagrant VM.
* [daily-scripts/shell-scripts](https://github.com/daily-scripts/shell-scripts) - my-scripts
* [ShellShoccar-jpn/kotoriotoko](https://github.com/ShellShoccar-jpn/kotoriotoko) - KOTORIOTOKO (little bird man) -- Extremely Compatible and Sustainable Twitter Application Written in Shell Script
* [zeroQiaoba/ivector-xvector](https://github.com/zeroQiaoba/ivector-xvector) - Extract xvector and ivector under kaldi
* [vincetse/shellutils](https://github.com/vincetse/shellutils) - A collection of command line utilities
* [tobykurien/NSA_b_gone](https://github.com/tobykurien/NSA_b_gone) - A Linux shell script to improve your privacy online
* [kvz/ochtra](https://github.com/kvz/ochtra) - One Commit Hook To Rule All
* [gabrieldim/Shell-Scripts](https://github.com/gabrieldim/Shell-Scripts) - Shell scripts about some basic topics, current time, calculator, sorting, restaurant and more.
* [gheift/ght-acme.sh](https://github.com/gheift/ght-acme.sh) - a linux shell script to sign certifactes by the letsencrypt CA
* [fnando/dotfiles](https://github.com/fnando/dotfiles) - My dotfiles
* [wffls/waffles](https://github.com/wffls/waffles) - Bash Configuration Management
* [ryanpcmcquen/linuxTweaks](https://github.com/ryanpcmcquen/linuxTweaks) - :penguin: A whole host of Linux tricks I have picked up over the years, in plain text. Some of them are even useful.
* [roperzh/heroku-buildpack-hugo](https://github.com/roperzh/heroku-buildpack-hugo) - Heroku buildpack for Hugo, the static site generator - https://github.com/spf13/hugo
* [mkropat/sh-realpath](https://github.com/mkropat/sh-realpath) - A portable, pure shell implementation of realpath
* [caarlos0-graveyard/jvm](https://github.com/caarlos0-graveyard/jvm) - Never manually change your JAVA_HOME again
* [PeterDaveHello/ColorEchoForShell](https://github.com/PeterDaveHello/ColorEchoForShell) - Make 🐚(shell) 's 💬 (`echo`)  to be 🌈 easily ✨ Support ✅ sh ➕ bash ➕ zsh ➕ ksh ➕ 🐟
* [GArik/bash-completion](https://github.com/GArik/bash-completion) - programmable completion for the bash shell
* [vaamonde/ubuntu-1804](https://github.com/vaamonde/ubuntu-1804) - :large_blue_circle: Curso GRÁTIS Linux Ubuntu Server 18.04.x LTS - REPOSITÓRIO CONGELADO - Esse repositório não irá mais receber atualizações. Novo repositório: vaamonde/ubuntu-2004
* [tripflex/inodes](https://github.com/tripflex/inodes) - Bash/Shell script to count inode usage
* [torokmark/assert.sh](https://github.com/torokmark/assert.sh) - :exclamation: Assertion lib for shell script users
* [danishprakash/goodreadsh](https://github.com/danishprakash/goodreadsh) - Command line interface for Goodreads
* [bolknote/shellgames](https://github.com/bolknote/shellgames) - Some bash games
* [bevry/dorothy](https://github.com/bevry/dorothy) - 🧙🏻‍♀️ A better dotfile ecosystem with cross-platform automations. Supports fish, zsh, bash, mac and linux. Zero to hero in minutes on new and existing machines.
* [KHP-Informatics/ngseasy](https://github.com/KHP-Informatics/ngseasy) - Dockerised Next Generation Sequencing Pipeline (QC, Align, Calling, Annotation)
* [two-six/YT-Feeder](https://github.com/two-six/YT-Feeder) - Rofi-Based YouTube RSS Reader
* [tsk-tsk/tsk-tsk](https://github.com/tsk-tsk/tsk-tsk) - TSK - The Scripting Kit
* [sirjaren/redoflacs](https://github.com/sirjaren/redoflacs) - Parallel BASH commandline FLAC compressor, verifier, organizer, analyzer, and retagger
* [neurobin/JLIVECD](https://github.com/neurobin/JLIVECD) - Live cd/dvd customization tool
* [eyedol/tools](https://github.com/eyedol/tools) - Little codes here and there to automate some of my boring daily routines and configurations
* [decors/fish-ghq](https://github.com/decors/fish-ghq) - ghq completion and keybinding for fish shell
* [damphat/kv-bash](https://github.com/damphat/kv-bash) - key/value database written in bash script (permanent variables in shell)
* [AdnanHodzic/android-sdk-installer](https://github.com/AdnanHodzic/android-sdk-installer) - Linux utility which aims to automatically install and configures Android SDK, Eclipse ADT Plugin, adds hardware support for devices and enables full MTP support.
* [laughedelic/fish_logo](https://github.com/laughedelic/fish_logo) - 🐠 Fish shell colorful ASCII-art logo
* [flaupretre/sysfunc](https://github.com/flaupretre/sysfunc) - A sysadmin-oriented shell library
* [bittorf/kalua](https://github.com/bittorf/kalua) - hardware-independent openWRT-extension (using POSIX-shell as main-language) for setting up, monitor and manage many, large wifi-mesh-networks for different locations including billing, captive portal / splash screen / weblogin, accounting, data retention and layer7/8-QoS
* [Gisto/nwjs-shell-builder](https://github.com/Gisto/nwjs-shell-builder) - NW.js (node-webkit) shell script builder and packager scripts
* [yousefvand/shellman-ebook](https://github.com/yousefvand/shellman-ebook) - Guide on shell scripting with Shellman vscode snippet
* [theonemule/no-ip](https://github.com/theonemule/no-ip) - A shell script that works as Dynamic Update Client (DUC) for noip.com
* [sudar/wp-plugin-in-github](https://github.com/sudar/wp-plugin-in-github) - Collection of shell scripts that I am using to manage and deploy WordPress Plugins from github into svn
* [rcrowley/mustache.sh](https://github.com/rcrowley/mustache.sh) - Mustache in POSIX shell
* [Utappia/uCareSystem](https://github.com/Utappia/uCareSystem) - An all-in-one, one click system maintenance application for Ubuntu/Debian operating systems and derivatives
* [reegnz/jq-zsh-plugin](https://github.com/reegnz/jq-zsh-plugin) - jq zsh plugin
* [owent-utils/bash-shell](https://github.com/owent-utils/bash-shell) - OWenT's Utils -- Bash&Shell branch
* [dlang/installer](https://github.com/dlang/installer) - dmd installers for various systems
* [dawsbot/swim](https://github.com/dawsbot/swim) - 🏊‍♀️  Switch between multiple vimrc files
* [WuOtto/MacImagesetGenerator](https://github.com/WuOtto/MacImagesetGenerator) - 2个脚本文件，帮助你在Mac上，生成Xcode可使用的APP图标和启动图。
* [Bhupesh-V/dotman](https://github.com/Bhupesh-V/dotman) - dotman is a simple, elegant & easy to use dotfiles manager 🖖🏽
* [Ardakilic/backmeup](https://github.com/Ardakilic/backmeup) - BackMeUp: An automated MySQL / MariaDB databases and files backup solution on *nix Machines using Amazon S3, WebDAV (ownCloud / NextCloud etc.), Google Drive and Dropbox.
* [soraxas/shsh](https://github.com/soraxas/shsh) - A multi-threaded manager for shell scripts, functions, standalone binaries, tab-completions, and more.
* [robb/dotfiles](https://github.com/robb/dotfiles) - Dotfiles to make computing personal.
* [monitisexchange/Monitis-Linux-Scripts](https://github.com/monitisexchange/Monitis-Linux-Scripts) - Shell Script to Extend or Automate Monitis
* [miguelgfierro/scripts](https://github.com/miguelgfierro/scripts) - A collection of useful shell scripts for Linux, Windows & Mac
* [javier-lopez/shundle](https://github.com/javier-lopez/shundle) - shundle is a plugin manager for general purpose shells
* [helderburato/dotfiles](https://github.com/helderburato/dotfiles) - ⚙️ Setup a macOS environment quickly and easily!
* [flyqie/dd-shell](https://github.com/flyqie/dd-shell) - 该脚本可在DD系统时为您提供一个WebUI以帮助您了解到目前的DD状态.
* [rugk/borg-cron-helper](https://github.com/rugk/borg-cron-helper) - Helper shell scripts for BorgBackup to automate backups and make your life easier… 😉
* [pontikis/bash-cloud-backup](https://github.com/pontikis/bash-cloud-backup) - bash-cloud-backup is a set of bash scripts, which can be used to automate local and cloud backup in Linux/Unix machines.
* [jhubig/FritzBoxShell](https://github.com/jhubig/FritzBoxShell) - Some shell scripts for controlling and checking the Fritz!Box/Fritz!Repeater
* [ajmalsiddiqui/dotfiles](https://github.com/ajmalsiddiqui/dotfiles) - My Book of Arcane Magic. :')
* [Superbil/build-lame-for-iOS](https://github.com/Superbil/build-lame-for-iOS) - Build lame for iOS
* [shellgei/shellgei160](https://github.com/shellgei/shellgei160) - 書籍: シェル・ワンライナー160本ノックの情報ページ
* [fagiani/shellstack](https://github.com/fagiani/shellstack) - ShellStack is a collection of bash scripts to install apps on ubuntu linux
* [bggo/Zmbkpose](https://github.com/bggo/Zmbkpose) - The zmbkpose tool is a shell script that does hot backup and hot restore of ZCS Opensource accounts, GPL(OPENSOURCE). It can run from any host in the net, which means that it can be set on a backup server already existent.
* [Statemood/jenkins](https://github.com/Statemood/jenkins) - Jenkins Shell & Pipeline scripts for FreeStyle & Pipeline jobs
* [AdrianDC/advanced_development_shell_tools](https://github.com/AdrianDC/advanced_development_shell_tools) - Advanced Development Shell Tools - http://adriandc.github.io/advanced_development_shell_tools
* [yangwenmai/learning-kubernetes](https://github.com/yangwenmai/learning-kubernetes) - Learning Kubernetes ServiceMesh Istio
* [sbimochan/smart-commit](https://github.com/sbimochan/smart-commit) - Commit with current branch name.
* [ryanoasis/devicons-shell](https://github.com/ryanoasis/devicons-shell) - :symbols: adds font icons (glyphs ★♨☢) to filetypes via bash (faux ls with icons)
* [renemarc/dotfiles](https://github.com/renemarc/dotfiles) - ~/. Cross-platform, cross-shell configuration files. ⚙️💻
* [icyphox/repl](https://github.com/icyphox/repl) - :shell: an instant REPL for any command
* [filebot/plugins](https://github.com/filebot/plugins) - Plugins and shell scripts for integrating 3rd party tools with FileBot
* [digitoimistodude/dudestack](https://github.com/digitoimistodude/dudestack) - A toolkit for creating a new professional WordPress project with deployments. Originally based on Roots/bedrock.
* [abs0/wargames](https://github.com/abs0/wargames) - Shell script to simulate the W.O.P.R. computer from WarGames (wopr)
* [AndreBL/ip6neigh](https://github.com/AndreBL/ip6neigh) - Giving local DNS names to IPv6 SLAAC addresses [OpenWrt/LEDE shell script]
* [mxmnk/shell](https://github.com/mxmnk/shell) - shell
* [htr-tech/ubuntu](https://github.com/htr-tech/ubuntu) - Install ubuntu in Termux Without Rooted Device
* [faif/shell-utils](https://github.com/faif/shell-utils) - Useful functions for POSIX shells (bash, ksh, tcsh, etc.).
* [emarref/webicon](https://github.com/emarref/webicon) - Generate favicon and touch icons via a shell script
* [dagon666/napi](https://github.com/dagon666/napi) - Napi Projekt Client and Subotage subtitle format converter both written in bash
* [arcticicestudio/nord-konsole](https://github.com/arcticicestudio/nord-konsole) - An arctic, north-bluish clean and elegant Konsole color scheme.
* [adityashrm21/RaspberryPi-Packet-Sniffer](https://github.com/adityashrm21/RaspberryPi-Packet-Sniffer) - An HTTP and HTTPS sniffing tool created using a Raspberry Pi
* [mogensen/keychain](https://github.com/mogensen/keychain) - Bash script to access the osx keychain, for use in shell scripts.
* [jgamblin/MacOS-Config](https://github.com/jgamblin/MacOS-Config) - Simple Shell Scripts I Use To Tweak MacOS To My Liking.
* [samoshkin/docker-letsencrypt-certgen](https://github.com/samoshkin/docker-letsencrypt-certgen) - Docker image to generate, renew, revoke RSA and/or ECDSA SSL certificates from LetsEncrypt CA using certbot and acme.sh clients in automated fashion
* [outime/ipv6-dhclient-script](https://github.com/outime/ipv6-dhclient-script) - IPv6 w/ dhclient configuration script (Debian/RedHat-based distros)
* [narbehaj/bash-backup](https://github.com/narbehaj/bash-backup) - Simple backup script for GNU/Linux servers
* [logseq/git-auto](https://github.com/logseq/git-auto) - A Simple Shell Script To Do Git Commit And Push Automatically
* [bash-c/main_arena_offset](https://github.com/bash-c/main_arena_offset) - A simple shell script to get main_arena offset of a given libc
* [bAndie91/cloudflare-cli](https://github.com/bAndie91/cloudflare-cli) - CLI utility managing CloudFlare services using CloudFlare API
* [asb/sh-todo](https://github.com/asb/sh-todo) - A minimal todo-list manager written in POSIX shell
* [YunoHost/install_script](https://github.com/YunoHost/install_script) - YunoHost installation scripts
* [MadhavBahl/shebang-everything](https://github.com/MadhavBahl/shebang-everything) - Your unofficial guidebook to shell scripting, give this repo a ⭐ if  it helped you :)
* [zhenruyan/codefont](https://github.com/zhenruyan/codefont) - 60余种常用的等宽字体    愉快的code吧  欢迎issues我  收录更多字体  Happy code bar with more than 60 common fonts of equal width. Welcome issues. I include more fonts.
* [vincentbernat/zshrc](https://github.com/vincentbernat/zshrc) - My .zshrc
* [ryanuber/slide.sh](https://github.com/ryanuber/slide.sh) - Create simple, text-based slide decks in your shell
* [mikepqr/stowsh](https://github.com/mikepqr/stowsh) - A shell script to install and uninstall dotfiles using symlinks with almost no dependencies
* [mhauri/generate-modman](https://github.com/mhauri/generate-modman) - Shell script to generate modman files for Magento Extensions
* [jrodal98/watch-scripts](https://github.com/jrodal98/watch-scripts) - Execute shell commands on your Linux computer from your smartwatch!
* [codenameyau/sed-awk-cheatsheet](https://github.com/codenameyau/sed-awk-cheatsheet) - Things you can do with sed and awk
* [abemassry/wsend](https://github.com/abemassry/wsend) - wsend: The opposite of wget
* [Integralist/Shell-Scripts](https://github.com/Integralist/Shell-Scripts) - Collection of custom utility shell scripts
* [Autorevision/autorevision](https://github.com/Autorevision/autorevision) - A script for extracting version information useful in release/build scripting.
* [santoshbaggam/stacker](https://github.com/santoshbaggam/stacker) - Hassle-free server setup for Developers
* [opencultureconsulting/openrefine-batch](https://github.com/opencultureconsulting/openrefine-batch) - Shell script to run OpenRefine in batch mode (import, transform, export). It orchestrates OpenRefine (server) and a python client that communicates with the OpenRefine API.
* [meribold/muccadoro](https://github.com/meribold/muccadoro) - 🍅 Pomodoro timer using figlet, cowsay, and optionally lolcat 🐮
* [madcoda/dotenv-shell](https://github.com/madcoda/dotenv-shell) - Use Dotenv in everything
* [lgathy/google-cloud-sdk-fish-completion](https://github.com/lgathy/google-cloud-sdk-fish-completion) - Google Cloud Platform SDK command line utilities shell completion for fish
* [kickstarter/laptop](https://github.com/kickstarter/laptop) - A shell script which turns your OS X laptop into an awesome web development machine
* [hakerdefo/check-my-net](https://github.com/hakerdefo/check-my-net) - A stupidly simple shell script to check & diagnose internet connectivity issues.
* [clburlison/scripts](https://github.com/clburlison/scripts) - 💡 A collection of random scripts.
* [charlyie/resmushit-cli](https://github.com/charlyie/resmushit-cli) - CLI client for reSmush.it : the Free Image Optimization API. Image optimizer shell script.
* [Fleshgrinder/nginx-sysvinit-script](https://github.com/Fleshgrinder/nginx-sysvinit-script) - Linux Standard Base compliant SysVinit script for nginx.
* [F4dl0/keydroid](https://github.com/F4dl0/keydroid) - Android Keylogger + Reverse Shell
* [skissane/mkjail](https://github.com/skissane/mkjail) - Shell script to create a chroot jail on Mac OS X
* [narcello/findead](https://github.com/narcello/findead) - :mag: Dead react components finder
* [mempodippy/snodew](https://github.com/mempodippy/snodew) - PHP root (suid) reverse shell
* [luizm/action-sh-checker](https://github.com/luizm/action-sh-checker) - A GitHub action that performs static analysis for shell scripts using shellcheck, shfmt and checkbashisms.
* [brgmnn/fish-docker-compose](https://github.com/brgmnn/fish-docker-compose) - Fish shell completions for docker-compose
* [brandonweiss/pure.fish](https://github.com/brandonweiss/pure.fish) - A Pure-inspired prompt for fish shell.
* [bltavares/kickstart](https://github.com/bltavares/kickstart) - Agentless configuration manager in Bash
* [arzzen/pert](https://github.com/arzzen/pert) - A simple command line (bash/shell) utility to estimate tasks using PERT [Program Evaluation and Review Technique]
* [wombat94/EFIClone](https://github.com/wombat94/EFIClone) - macOS Shell Scripts to clone the EFI partition automatically from either Carbon Copy Cloner or SuperDuper! when run on a Hackintosh
* [reale/bashlets](https://github.com/reale/bashlets) - An experiment in extending the command-line interface.
* [pronoiac/tarsnap-cron](https://github.com/pronoiac/tarsnap-cron) - Cron scripts (bash/shell) for tarsnap backup, including scheduled deletion of old backups.
* [illiliti/tinyramfs](https://github.com/illiliti/tinyramfs) - Tiny initramfs written in POSIX shell
* [giswqs/manjaro-linux](https://github.com/giswqs/manjaro-linux) - Shell scripts for setting up Manjaro Linux for Python programming and deep learning
* [dokku/plugn](https://github.com/dokku/plugn) - Hook system that lets users extend your application with plugins
* [bilyboy785/seedbox-compose](https://github.com/bilyboy785/seedbox-compose) - A complete script to deploy Seedbox with Docker fully automated !
* [aluxian/fish-kube-prompt](https://github.com/aluxian/fish-kube-prompt) - ⎈ kubectl context/namespace in your fish shell prompt
* [Dieterbe/libui-sh](https://github.com/Dieterbe/libui-sh) - a shell library providing useful UI functions
* [rik2803/aws-sts-assumerole](https://github.com/rik2803/aws-sts-assumerole) - Bash script to easily set shell environment with temporary access tokens using a config file and the AWS credentials file
* [rafi/.config](https://github.com/rafi/.config) - Rafi's workstations (Archlinux, osx) ~/.config.
* [mjrafferty/apollo-zsh-theme](https://github.com/mjrafferty/apollo-zsh-theme) - Heavily customizable, compatible, and fast ZSH theme framework.
* [jonhoo/streamsh](https://github.com/jonhoo/streamsh) - Download online video streams using shell
* [illusori/bash-itunes](https://github.com/illusori/bash-itunes) - Shell script to control iTunes from the command-line.
* [emirozer/nixarmor](https://github.com/emirozer/nixarmor) - nixarmor is a linux hardening automation project
* [emerleite/mongo-migrate](https://github.com/emerleite/mongo-migrate) - MongoDB Migration using shell
* [doubaokun/dockers](https://github.com/doubaokun/dockers) - Docker hello world templates
* [yonchu/shell-color-pallet](https://github.com/yonchu/shell-color-pallet) - Show color pallet for zsh/bash on 16 and 256 color terminal
* [wklken/bash-utils](https://github.com/wklken/bash-utils) - utils for shell
* [sobolevn/wakatime-zsh-plugin](https://github.com/sobolevn/wakatime-zsh-plugin) - 🕒Track how much time you have spent in your terminal!
* [qbit/dotfiles](https://github.com/qbit/dotfiles) - Dotfile framework for make greater good of dotfiles (Shell)
* [n-ivkovic/tspreed](https://github.com/n-ivkovic/tspreed) - A terminal RSVP speed reader with Spritz-like functionality written in POSIX-compliant shell
* [jorgebucaran/pyenv](https://github.com/jorgebucaran/pyenv) - Pyenv support plugin for fish-shell
* [el1t/statusline](https://github.com/el1t/statusline) - Responsive powerline-esque zsh theme
* [dominiksalvet/gitpack](https://github.com/dominiksalvet/gitpack) - Simple Git-based package manager
* [bradleymackey/turbo-boost-disable](https://github.com/bradleymackey/turbo-boost-disable) - Shell wrappers and instructions for disabling Intel Turbo Boost on macOS
* [alexanderepstein/Sandman-Lite](https://github.com/alexanderepstein/Sandman-Lite) - A Lightweight Script Built With Late Night Developers In Mind
* [Machou/Cloudflare-Block](https://github.com/Machou/Cloudflare-Block) - Cloudflare Blocking
* [BeginMan/myshell](https://github.com/BeginMan/myshell) - 写的常用Shell小工具，运维小脚本等
* [htr-tech/Tbanner](https://github.com/htr-tech/Tbanner) - Give A Awesome Look to your Termux App
* [burrsutter/scripts-istio](https://github.com/burrsutter/scripts-istio) - My bash shell scripts for easy demo'ing of bit.ly/istio-tutorial
* [asciimoo/ali](https://github.com/asciimoo/ali) - Smart shell alias replacement
* [alicfeng/AShell](https://github.com/alicfeng/AShell) - 开发者常用脚本shell
* [PaulKinlan/chromium-android-installer](https://github.com/PaulKinlan/chromium-android-installer) - Install Chromium Test Shell on Android
* [PacktPublishing/Mastering-Linux-Shell-Scripting-Second-Edition](https://github.com/PacktPublishing/Mastering-Linux-Shell-Scripting-Second-Edition) - Mastering Linux Shell Scripting - Second Edition, published by Packt
* [xr09/cron-last-sunday](https://github.com/xr09/cron-last-sunday) - Run a cron task the first, nth or last weekday of the month
* [slim-bean/loki-shell](https://github.com/slim-bean/loki-shell) - How to use Loki to store and centralize your shell history from anywhere and search it using ctrl-r and fzf
* [ronalde/mpd-configure](https://github.com/ronalde/mpd-configure) - Bash scripts to assist users of mpd to configure it as an audiophile bit perfect music player.
* [pothi/backup-wordpress](https://github.com/pothi/backup-wordpress) - Shell scripts to take local and remote backups of WordPress (database and files) via server cron.
* [dryruner/imagecrawler](https://github.com/dryruner/imagecrawler) - An image crawler implemented in shell script
* [capitalone/bash_shell_mock](https://github.com/capitalone/bash_shell_mock) - A shell script mocking utility/framework for the BASH shell
* [al0ne/MacCheck](https://github.com/al0ne/MacCheck) - 一个Mac下信息搜集小脚本 主要用于信息搜集/应急响应/检测挖矿进程/异常进程/异常启动项
* [Xerbo/furaffinity-dl](https://github.com/Xerbo/furaffinity-dl) - FurAffinity Downloader, now with 100% more Python
* [FSMaxB/lfs-me](https://github.com/FSMaxB/lfs-me) - Linux From Scratch made ( more ) easy. A simple, fakeroot based, package manager for LFS heavily inspired by Archlinux' package management.
* [virtualmin/virtualmin-install](https://github.com/virtualmin/virtualmin-install) - Shell script to perform a Virtualmin GPL or Professional installation
* [soffes/dotfiles](https://github.com/soffes/dotfiles) - ~soffes
* [milianw/shell-helpers](https://github.com/milianw/shell-helpers) - a bunch of little programs I wrote to make my life on the command line easier and less type-intensitive
* [dnmfarrell/jp](https://github.com/dnmfarrell/jp) - Validate and transform JSON with Bash
* [betweenbrain/linux-stuff](https://github.com/betweenbrain/linux-stuff) - A collection of Linux tricks, tips, shell scripts, and general knowledge collected from around the web and from my own personal turmoil of breaking stuff and having to fix it.
* [aizk/shell](https://github.com/aizk/shell) - bash shell script.
* [Drapegnik/env](https://github.com/Drapegnik/env) - :wrench: Repo for storing my environment settings, dotfiles and etc.
* [shinriyo/breeze](https://github.com/shinriyo/breeze) - git tool for fish-shell
* [rutchkiwi/copyzshell](https://github.com/rutchkiwi/copyzshell) - A plugin for oh-my-zsh to copy your shell configuration to another machine over ssh.
* [reviewdog/action-shellcheck](https://github.com/reviewdog/action-shellcheck) - Run shellcheck with reviewdog
* [nichobi/sponsorblockcast](https://github.com/nichobi/sponsorblockcast) - A shell script that skips sponsored Youtube content on all local Chromecasts
* [l0b0/tilde](https://github.com/l0b0/tilde) - Linux home directory configuration and utilities
* [gawlk/art](https://github.com/gawlk/art) - :art: A smart theme generator
* [davidramiro/gpay-gms-patch](https://github.com/davidramiro/gpay-gms-patch) - 💳 Shell script to make Google Pay work on rooted Android devices
* [christianbaun/ossperf](https://github.com/christianbaun/ossperf) - A lightweight tool for analyzing the performance and data integrity of object-based storage services
* [bianjp/archlinux-installer](https://github.com/bianjp/archlinux-installer) - Shell scripts that help install and setup Arch Linux
* [adafruit/Adafruit-Pi-ExternalRoot-Helper](https://github.com/adafruit/Adafruit-Pi-ExternalRoot-Helper) - A shell script to configure a USB drive as root filesystem.
* [Gh005t/Android-BruteForce](https://github.com/Gh005t/Android-BruteForce) - Its is a simple shell script that brute force Android Lock screen (When USB DEBUGGING is enable) its uses ADB tools FOR BruteForce
* [treffynnon/Benchmark-PHP-HHVM-Zephir](https://github.com/treffynnon/Benchmark-PHP-HHVM-Zephir) - Benchmark PHP, HHVM and Zephir
* [sp1thas/dropboxignore](https://github.com/sp1thas/dropboxignore) - It's all about the missing .dropboxignore file.
* [runeasymail/easymail](https://github.com/runeasymail/easymail) - Easy way to install a mail server.
* [pmalves/ctools-installer](https://github.com/pmalves/ctools-installer) - Shell script that installs the CTools
* [mjambon/reasonable-shell-script](https://github.com/mjambon/reasonable-shell-script) - Because shell scripts don't have to be terrible
* [fengfu/jtoolkit](https://github.com/fengfu/jtoolkit) - JToolkit is a tool set for Java troubleshooting. It integrates various Linux commands, Shell scripts, Java commands, and various third-party useful tools to help us quickly locate problems through a fool-like interface and convenient operations. Currently, VjTop, Async-Profiler of Vipshop has been integrated /async-profiler).
* [ankitvad/goto](https://github.com/ankitvad/goto) - Linux Shell 'cd' replacement tool. cd on steroids, with fuzzy file finder and a directory bookmark saver.
* [LucasLarson/gunstage](https://github.com/LucasLarson/gunstage) - 🔫  `git unstage` as a service: a Git plugin for the shell that automagically remembers all the different commands there are to remove files from staging and when to use each
* [Bilalh/shellmarks](https://github.com/Bilalh/shellmarks) - Directory bookmarks for the shell
* [12moons/ec2-tags-env](https://github.com/12moons/ec2-tags-env) - :cloud: Import AWS EC2 tags as environment variables
* [martinburger/bash-common-helpers](https://github.com/martinburger/bash-common-helpers) - Helper functions commonly used when writing shell (for instance, Bash) scripts.
* [fabiomaia/fix-spotify-icon](https://github.com/fabiomaia/fix-spotify-icon) - :musical_note: Shell script to fix the Spotify icon in Ubuntu.
* [endofzero/Minecraft-Sheller](https://github.com/endofzero/Minecraft-Sheller) - Shell script designed to allow for automation of Minecraft Server Administration.
* [easonjim/centos-shell](https://github.com/easonjim/centos-shell) - CentOS常用Shell
* [dparoli/hrsync](https://github.com/dparoli/hrsync) - rsync backup with a bit of magic, decting moved and renamed files
* [crazyadmins/useful-scripts](https://github.com/crazyadmins/useful-scripts) - Useful shell scripts for Hadoop/Linux system administrator
* [0rax/fishline](https://github.com/0rax/fishline) - A powerline prompt framework for the fish-shell built in fish-shell.
* [ruyadorno/installme-osx](https://github.com/ruyadorno/installme-osx) - My personal script to setup a new OSX
* [mattiabasone/tuning-primer](https://github.com/mattiabasone/tuning-primer) - MySQL performance tuning primer script (with MariaDB patch)
* [dissipator/gd-utils-noport](https://github.com/dissipator/gd-utils-noport) - gd-utils noport no-ssl with shell
* [decors/fish-colored-man](https://github.com/decors/fish-colored-man) - Color-enabled man pages plugin for fish-shell
* [clhenrick/shell_scripts](https://github.com/clhenrick/shell_scripts) - Bash shell scripts for batch GeoProcessing using GDAL & OGR2OGR
* [amail/deploy.sh](https://github.com/amail/deploy.sh) - Deploy.sh is a universal deployment script that makes it easy for you to deploy your code, files, configurations etc. to multiple servers via ssh. Perfect for the cloud. Written as a shell script (standard bourne shell) and runs on every unix server. No need for remote install. Just run the deploy.sh script on the local machine.
* [ajxchapman/sshreverseshell](https://github.com/ajxchapman/sshreverseshell) - Full TTY reverse shell over SSH
* [JREAM/config-ubuntu](https://github.com/JREAM/config-ubuntu) - Quickly Setup Ubuntu Desktop or Server with all-in-one Bash Scripts.
* [Dbz/kube-aliases](https://github.com/Dbz/kube-aliases) - Kubernetes Aliases and Bash Functions
* [whats-this/owo.sh](https://github.com/whats-this/owo.sh) - Read-only mirror of https://owo.codes/whats-this/owo.sh
* [starrhorne/Fish-Shell-Scripts](https://github.com/starrhorne/Fish-Shell-Scripts) - My personal fish shell scripts
* [ramsayleung/dotfiles](https://github.com/ramsayleung/dotfiles) - A shell script to install awesome command for *nix platform and set them up
* [lasandell/RaspberryPi](https://github.com/lasandell/RaspberryPi) - Example shell scripts for interfacing electronics with the GPIO ports of the Raspberry Pi
* [krebs/array](https://github.com/krebs/array) - a POSIX-compliant implementation of arrays, once in 17 lines of shell. Archived
* [jqr/dotfiles](https://github.com/jqr/dotfiles) - Super bad-ass dotfiles for any Ruby/Rails/Git/OSX user.
* [joehillen/to-fish](https://github.com/joehillen/to-fish) - Bookmarks for Fish Shell
* [codeforester/base](https://github.com/codeforester/base) - A simple framework for sharing Bash profiles, reusable shell libraries, and commands across hosts and teams. Contains builtin libraries for common functions like logging, error handling, and assertions. Built with SRE / DevOps teams in mind.
* [agross/dotfiles](https://github.com/agross/dotfiles) - My dotfiles.
* [SySS-Research/clone-cert](https://github.com/SySS-Research/clone-cert) - Simple shell script to "clone" X.509 certificates
* [Madh93/conky-spotify](https://github.com/Madh93/conky-spotify) - :musical_note: Show current Spotify track in Conky (Cover, title...)
* [GideonWolfe/dots](https://github.com/GideonWolfe/dots) - 🌀 my linux configuration
* [zpm-zsh/ls](https://github.com/zpm-zsh/ls) - Zsh plugin for ls
* [zgr0629/RedisDesktopManager-Mac](https://github.com/zgr0629/RedisDesktopManager-Mac) - RedisDesktopManager compile shell, and compiled DMG file.
* [nwoolls/xgminer-osx](https://github.com/nwoolls/xgminer-osx) - Shell scripts for creating redistributable packages of CGMiner and BFGMiner for Mac OS X
* [noloader/Build-Scripts](https://github.com/noloader/Build-Scripts) - Collection of build scripts useful when testing on downlevel, abandonware and ransomware clients
* [mcsrainbow/shell-scripts](https://github.com/mcsrainbow/shell-scripts) - Shell scripts
* [linickx/rsdns](https://github.com/linickx/rsdns) - rackspace DNS tools
* [holman/eponine](https://github.com/holman/eponine) - A very simple web server interface to shell scripts. Designed for Slack integrations on a Raspberry Pi.
* [adsr/rw.rs](https://github.com/adsr/rw.rs) - Free shell account and web 1.0 hosting @ http://rw.rs/~you
* [Percona-QA/percona-qa](https://github.com/Percona-QA/percona-qa) - Percona QA is a suite of scripts and utilities that assists in building, continuous integration, automated testing & bug reporting for Percona Server, Percona XtraDB Cluster, Percona XtraBackup, Percona Server for MongoDB, as well as other flavors of MySQL (Oracle, Facebook MyQSL, WebScaleSQL, MariaDB) etc.
* [Charliedean/NetcatUP](https://github.com/Charliedean/NetcatUP) - Upgrade your netcat shell today!
* [travisg/toolchains](https://github.com/travisg/toolchains) - Shell script to build gcc for various architectures
* [thecasualcoder/lazy-connect](https://github.com/thecasualcoder/lazy-connect) - Shell function to fuzzy search an IPSec VPN by name and connect to it automatically.
* [stps/mpv-ios-scripts](https://github.com/stps/mpv-ios-scripts) - macOS shell script for cross-compiling libmpv for iOS
* [stablestud/adsorber](https://github.com/stablestud/adsorber) - Ad-blocker for Linux systems purely built on POSIX-compliant shell scripts.
* [duy13/VDVESTA](https://github.com/duy13/VDVESTA) - Welcome to VDVESTA, a shell script auto Custom & Install VESTACP for your CentOS Server Release 7 x86_64. Thanks you for using!
* [ahackett/Oracle-DBA-Scripts](https://github.com/ahackett/Oracle-DBA-Scripts) - This is a collection of useful Oracle SQL and shell scripts that I frequently use
* [SixArm/gpg-encrypt](https://github.com/SixArm/gpg-encrypt) - Use GPG to encrypt a file using our best settings
* [RicterZ/shell-blog](https://github.com/RicterZ/shell-blog) - My blog
* [s0wr0b1ndef/OSCP-note](https://github.com/s0wr0b1ndef/OSCP-note) - list of useful commands, shells and notes related to OSCP
* [KeepWannabe/Remot3d](https://github.com/KeepWannabe/Remot3d) - Remot3d: is a simple tool created for large pentesters as well as just for the pleasure of defacers to control server by backdoors
* [rosineygp/mkdkr](https://github.com/rosineygp/mkdkr) - Make + Docker + Shell = CI Pipeline
* [tonijarjour/autorice](https://github.com/tonijarjour/autorice) - Autorice 9001 ~ Simple and fast arch setup in minutes
* [lestrrat/kubesh](https://github.com/lestrrat/kubesh) - Spawn a shell for a particular kubectl context (cluster).
* [fish-shell/fish-shell](https://github.com/fish-shell/fish-shell) - The user-friendly command line shell.
* [meain/dotfiles](https://github.com/meain/dotfiles) - If there is a shell, there is a way!
* [br41-net/gandi-automatic-dns](https://github.com/br41-net/gandi-automatic-dns) - A Bourne shell script to update Gandi.net zonefiles
* [lebensterben/awesome-clear-linux](https://github.com/lebensterben/awesome-clear-linux) - Let's make Clear Linux distribution great
* [tests-always-included/tomdoc.sh](https://github.com/tests-always-included/tomdoc.sh) - Parse TomDoc'd shell scripts and generate pretty documentation from it
* [jm/shin](https://github.com/jm/shin) - A simple package manager for dotfiles and other shell scripts
* [grml/grml-debootstrap](https://github.com/grml/grml-debootstrap) - wrapper around debootstrap
* [bdossantos/nagios-plugins](https://github.com/bdossantos/nagios-plugins) - 🌡️ Various Sensu, Nagios, you name it, monitoring plugins.
* [aripollak/rbenv-bundler-ruby-version](https://github.com/aripollak/rbenv-bundler-ruby-version) - rbenv plugin to pick a ruby version from bundler's Gemfile
* [SixArm/sixarm_mac_setup](https://github.com/SixArm/sixarm_mac_setup) - SixArm.com » Mac » Setup notes for new Mac computer and macOS
* [Doriedson/mario-shellscript](https://github.com/Doriedson/mario-shellscript) - Game do Mario Bros em Shell Script
* [1egoman/biome](https://github.com/1egoman/biome) - :christmas_tree: A script to manage an isolated shell environment for a project.
* [heroku/heroku-buildpack-python](https://github.com/heroku/heroku-buildpack-python) - The official Heroku buildpack for Python apps.
* [brian2lvls/gandi-automatic-dns](https://github.com/brian2lvls/gandi-automatic-dns) - A Bourne shell script to update Gandi.net zonefiles
* [mengfeng/clean-my-mac](https://github.com/mengfeng/clean-my-mac) - Shell Scripts to clean my mac
* [robb/.dotfiles](https://github.com/robb/.dotfiles) - Dotfiles to make computing personal.
* [liunian1004/shell](https://github.com/liunian1004/shell) - bash shell script.
* [betweenbrain/ubuntu-web-server-build-script](https://github.com/betweenbrain/ubuntu-web-server-build-script) - A hand-rolled shell script to help you get up and running quickly with an Ubuntu web server. Specifically geared for Ubuntu 10.04 LTS 32-bit. Please note: This is not intended to be a complete and comprehensive solution, but a starting point for your custom server.
* [moeenz/vscode-updater](https://github.com/moeenz/vscode-updater) - A simple script to automate downloading, installing and restarting Visual Studio Code.
* [marcan/certbot-external](https://github.com/marcan/certbot-external) - Certbot plugin that uses an external shell script for domain validation
* [halinuya/imagesetGenerator](https://github.com/halinuya/imagesetGenerator) - a shell script for generator ImageSet which input need big picture.
* [alswl/.oOo.](https://github.com/alswl/.oOo.) - dot files configuration (macOS & Linux), surfingkeys / tmux / screen / ideavimrc / phoenix / etc.
* [MysterionRise/mavenized-jcuda](https://github.com/MysterionRise/mavenized-jcuda) - Mavenized JCuda
* [fastai/fastmac](https://github.com/fastai/fastmac) - Get a MacOS or Linux shell, for free, in around 2 minutes
* [shellhub/shell](https://github.com/shellhub/shell) - All useful linux shell scripts
* [noqqlint/cfetch](https://github.com/noqqlint/cfetch) - A simple system information tool for Linux.
* [brianhp2/gandi-automatic-dns](https://github.com/brianhp2/gandi-automatic-dns) - A Bourne shell script to update Gandi.net zonefiles
* [cemkeylan/mu-wizard](https://github.com/cemkeylan/mu-wizard) - Shell script to easily setup mu4e on Emacs
* [ronjouch/marathon](https://github.com/ronjouch/marathon) - minimal run-or-focus launcher for Linux/X
* [emrahcom/emrah-buster-templates](https://github.com/emrahcom/emrah-buster-templates) - The templates of the emrah-buster installer.
* [bosim/FedoraPrime](https://github.com/bosim/FedoraPrime) - This package provide similar functionality to nvidia-prime for Ubuntu, just for fedora, provide a shell script that will change to NVIDIA GPU and vice versa for Intel GPU
* [meetbill/shell_menu](https://github.com/meetbill/shell_menu) - 🛠 统一管理脚本框架(本框架中已含一些运维安全工具脚本)【CentOS】
* [ashqal/PNGCompressForMac](https://github.com/ashqal/PNGCompressForMac) - Simple shell script to compress png file. It will compress all png file include in given directory.
* [abathur/resholve](https://github.com/abathur/resholve) - a shell resolver? :)
* [jotyGill/quickz-sh](https://github.com/jotyGill/quickz-sh) - quickly install zsh, oh-my-zsh with power-level-9k zsh-completions zsh-autosuggestions zsh-syntax-highlighting history-substring-search
* [g763007297/GQResign](https://github.com/g763007297/GQResign) - ipa重签名(resign),只需一个证书的p12和一个mobileprovision文件就可以实现ipa的重签名
* [duksis/Lock](https://github.com/duksis/Lock) - 🔒 MacOS Application that does only one thing -> Locks your Mac
* [chadoe/luks-triple-unlock](https://github.com/chadoe/luks-triple-unlock) - Set of shell scripts to allow unlocking of full disk encrypted Ubuntu and Debian installs through console, USB-key or SSH.
* [augustohp/ship](https://github.com/augustohp/ship) - Aids you creating a `Dockerfile` by transforming its (interactive shell) history into `RUN` instructions
* [zerobyte-id/Bashter](https://github.com/zerobyte-id/Bashter) - Web Vulnerability Scanner using Shell Script
* [dxd132630/Shell](https://github.com/dxd132630/Shell) - Shell scripts/programs for use in Liunx Systems. (CentOS/Redhat variants)
* [NJUPT-ISL/login-shell](https://github.com/NJUPT-ISL/login-shell) - SSH登陆显示脚本
* [notclint/cfetch](https://github.com/notclint/cfetch) - A simple system information tool for Linux.
* [testrain/imagecrawler](https://github.com/testrain/imagecrawler) - An image crawler implemented in shell script
* [Tsuk1ko/nhentai-one-key-downloader](https://github.com/Tsuk1ko/nhentai-one-key-downloader) - 一个可以一键下载nhentai本子的纯shell脚本。A pure shell script that can easily download comics from nhentai.
* [thinkerbot/ts](https://github.com/thinkerbot/ts) - A shell test script
* [sevensins/Wallbase-Downloader](https://github.com/sevensins/Wallbase-Downloader) - Shell script to leech wallpapers from wallbase.cc
* [jsks/czhttpd](https://github.com/jsks/czhttpd) - zsh http server
* [Josef-Friedrich/Hue-shell](https://github.com/Josef-Friedrich/Hue-shell) - A collection of UNIX shell scripts to control the Hue LED lamps from Philips.
* [xilin/ios-build-script](https://github.com/xilin/ios-build-script) - Shell scripts to build ipa
* [saveriomiroddi/zfs-installer](https://github.com/saveriomiroddi/zfs-installer) - Shell script program that prepares ZFS on a system, and installs Linux
* [clieg/cfetch](https://github.com/clieg/cfetch) - A simple system information tool for Linux.
* [jamiewilson/predawn-shell](https://github.com/jamiewilson/predawn-shell) - Predawn themes for iTerm, Terminal, and a ZSH prompt
* [tomsquest/dotfiles](https://github.com/tomsquest/dotfiles) - :file_folder: Config files for zsh, vim and many more. Heavily commented
* [spack/sbang](https://github.com/spack/sbang) - Run scripts with very long shebang (#!) lines
* [rosshamilton1/cissec](https://github.com/rosshamilton1/cissec) - Kickstart profiles for CentOS 7 to help meet CIS benchmarks + shell script to audit
* [kud/my](https://github.com/kud/my) - dev environnement.
* [dotzero/iTerm-2-Peppermint](https://github.com/dotzero/iTerm-2-Peppermint) - iTerm 2 Peppermint color theme
* [Screetsec/Vegile](https://github.com/Screetsec/Vegile) - This tool will setting up your backdoor/rootkits when backdoor already setup it will be hidden your spesisifc process,unlimited your session in metasploit and transparent. Even when it killed, it will re-run again. There always be a procces which while run another process,So we can assume that this procces is unstopable like a Ghost in The Shell
* [natelandau/shell-scripts](https://github.com/natelandau/shell-scripts) - Shell scripting utility functions and a bash script boilerplate template
* [TheRealKizu/dotfiles](https://github.com/TheRealKizu/dotfiles) - My dotfiles / config files I use on my daily driver.
* [mhausenblas/kn](https://github.com/mhausenblas/kn) - A collection of shell functions for Kubernetes native dabbling
* [SixArm/sixarm_unix_shell_scripts](https://github.com/SixArm/sixarm_unix_shell_scripts) - SixArm.com » Unix » shell scripts for command line programs in sh, bash, etc.
* [gozoinks/unifi-pfsense](https://github.com/gozoinks/unifi-pfsense) - A script that installs the UniFi Controller software on pfSense and other FreeBSD systems
* [scriptingosx/Installomator](https://github.com/scriptingosx/Installomator) - Installation script to deploy standard software on Macs
* [JaderH/GreenBox](https://github.com/JaderH/GreenBox) -  :game_die: 娱乐项目，使用 Crontab 定时提交 Commits。点亮绿格子；对就是绿
* [thwidge/thoughts](https://github.com/thwidge/thoughts) - A portable pal for putting your thoughts on the internet
* [sixdimensionalarray/esxidown](https://github.com/sixdimensionalarray/esxidown) - A shell script to shutdown VMware ESXi host servers
* [quafzi/magento-anonymizer](https://github.com/quafzi/magento-anonymizer) - shell script to anonymize Magento database
* [arjun024/systemd-example-startup](https://github.com/arjun024/systemd-example-startup) - example file to tell systemd to start a shell script at boot
* [denysdovhan/spaceship-prompt](https://github.com/denysdovhan/spaceship-prompt) - :rocket::star: A Zsh prompt for Astronauts
* [dannysteenman/aws-toolbox](https://github.com/dannysteenman/aws-toolbox) - A collection of DevOps tools including shell & python scripts that automate the boring stuff in AWS.
* [ayoisaiah/dotfiles](https://github.com/ayoisaiah/dotfiles) -   Experimental, ongoing configuration files and scripts for Arch Linux, Fish shell, Git and Neovim.
* [dmitmel/dotfiles](https://github.com/dmitmel/dotfiles) - My dotfiles (configurations and settings) for shells, text editors and other terminal programs, plus a collection of scripts.
* [wd5gnr/mhs5200a](https://github.com/wd5gnr/mhs5200a) - Shell script and awk program (and spreadsheet) to allow custom wave settings for MHS-5200A signal generator
* [solodynamo/go-init](https://github.com/solodynamo/go-init) - The only Golang script you will ever need to get started .... 🏃
* [lavoiesl/bash-templater](https://github.com/lavoiesl/bash-templater) - Very simple templating system that replace {{VAR}} by $VAR environment value, supports defines
* [engineer-man/piston](https://github.com/engineer-man/piston) - A high performance general purpose code execution engine.
* [anrip/dnspod-shell](https://github.com/anrip/dnspod-shell) - 基于DNSPod用户API实现的纯Shell动态域名客户端
* [davidosomething/dotfiles](https://github.com/davidosomething/dotfiles) - mac OS, Arch Linux, and Debian/Ubuntu
* [egargo/cfetch](https://github.com/egargo/cfetch) - A simple system information tool for Linux.
* [brianpcurran/gandi-automatic-dns](https://github.com/brianpcurran/gandi-automatic-dns) - A Bourne shell script to update Gandi.net zonefiles
* [mzeis/MageSpawner](https://github.com/mzeis/MageSpawner) - Shell script for quickly creating Magento test installations.
* [aws-samples/copy-encrypted-ami](https://github.com/aws-samples/copy-encrypted-ami) - Shell script that automates the copy of encrypted AMI across accounts and regions.
* [tldr-pages/tldr](https://github.com/tldr-pages/tldr) - 📚 Collaborative cheatsheets for console commands
* [kluntze/cfetch](https://github.com/kluntze/cfetch) - A simple system information tool for Linux.
* [qindeli/WorksapceShell](https://github.com/qindeli/WorksapceShell) - 项目基于Workspace的打包签名脚本
* [solarkennedy/sensu-shell-helper](https://github.com/solarkennedy/sensu-shell-helper) - A shell script wrap your programs around to make them send their output to Sensu!
* [jacob33c/Send-a-Movie-Script](https://github.com/jacob33c/Send-a-Movie-Script) - Send an entire movie script line by line using this simple and short shell script.
* [eduosi/shell](https://github.com/eduosi/shell) - linux 常用脚本
* [FanhuaCloud/Shell-BBR](https://github.com/FanhuaCloud/Shell-BBR) - Centos7 BBR一键安装脚本
* [ideamonk/Rambola](https://github.com/ideamonk/Rambola) - Set of shell scripts to manage persistent ramdisks on os x
* [ahmedelgabri/dotfiles](https://github.com/ahmedelgabri/dotfiles) - ~ 🍭 ~
* [daenney/pyenv](https://github.com/daenney/pyenv) - Pyenv support plugin for fish-shell
* [juliantellez/up](https://github.com/juliantellez/up) - 🆙Configure your machine with one command 🆙
* [darrentu/convert-db-to-csv](https://github.com/darrentu/convert-db-to-csv) - convert-db-to-csv.sh is a shell script that uses SQLite3 to convert a .db file into .csv files. It converts each of the tables in the database into csv files.
* [connorworley/dotfiles](https://github.com/connorworley/dotfiles) - Dotfiles and shell scripts
* [metomi/rose](https://github.com/metomi/rose) - :rose: Rose is a toolkit for writing, editing and running application configurations.
* [logoscreative/new-wp-mamp-shell](https://github.com/logoscreative/new-wp-mamp-shell) - Roll a new WordPress installation for MAMP with this quick shell script (allows custom inputs for directory, database name, and WP version)
* [Ventto/lux](https://github.com/Ventto/lux) - POSIX Shell script to easily control brightness on backlight-controllers.
* [jorgebucaran/fisher](https://github.com/jorgebucaran/fisher) - A plugin manager for Fish—the friendly interactive shell.
* [jorgebucaran/spark.fish](https://github.com/jorgebucaran/spark.fish) - ▁▂▃▅▂▇ in your fish shell.
* [IlanCosman/tide](https://github.com/IlanCosman/tide) - 🌊 A modern prompt manager for the Fish shell.
* [Heckie75/eQ-3-radiator-thermostat](https://github.com/Heckie75/eQ-3-radiator-thermostat) - Full-Featured shell script in order to control the eQ-3 radiator thermostat via linux and Raspberry Pi
* [shixueqian/AutoPackageScript](https://github.com/shixueqian/AutoPackageScript) - 一个简单的ipa打包脚本，用shell脚本编写。可以方便地对iOS工程进行打包。
* [hhstore/awesome-script](https://github.com/hhstore/awesome-script) - 常用的 shell 脚本,包括 centos, Ubuntu, Mac osx, 以及 Docker, Python 等常用软件的安装, 配置, 开发环境搭建的脚本.
* [andrewharvey/srtm-stylesheets](https://github.com/andrewharvey/srtm-stylesheets) - Shell scripts for working with NASA SRTM DEM data; gdaldem stylesheets for shaded relief maps; Mapnik stylesheets for contours; TileStache configuration for sandwich
* [gitusrs/openssl-ios-build-shell-script](https://github.com/gitusrs/openssl-ios-build-shell-script) - Build openssl with shell script-only support to use on iOS, and bitcode is supported.
* [williamsmj/stowsh](https://github.com/williamsmj/stowsh) - A shell script to install and uninstall dotfiles using symlinks. stow written in bash, in other words.
* [excid3/dotfiles](https://github.com/excid3/dotfiles) - My personal dotfiles for macOS: zsh, MacVim, iterm, and more.
* [fishpkg/mono](https://github.com/fishpkg/mono) - No bells and whistles, true minimal prompt for the fish shell
* [tj/cipherhub.sh](https://github.com/tj/cipherhub.sh) - substack's cipherhub as a shell script
* [qindeli/NoWorkspaceShell](https://github.com/qindeli/NoWorkspaceShell) - 无WorkSpace的脚本
* [greymd/egzact](https://github.com/greymd/egzact) - Generate flexible patterns on the shell
* [davesque/s](https://github.com/davesque/s) - a simple shell script manager
* [superkojiman/rfishell](https://github.com/superkojiman/rfishell) - Provide a shell-like interface for exploiting Remote File Inclusion vulnerabilities.
* [ruipfcosta/carthage-workarounds](https://github.com/ruipfcosta/carthage-workarounds) - Shell scripts to make life a little easier when using Carthage.
* [gchaincl/dotenv.sh](https://github.com/gchaincl/dotenv.sh) -  Loads environment variables from `.env` in your shell
* [cowgill/spamhaus](https://github.com/cowgill/spamhaus) - A shell script that grabs the latest Spamhaus DROP List and adds it to iptables.
* [apfeltee/a2mp3](https://github.com/apfeltee/a2mp3) - convert (nearly) every type of (audio)file to mp3 in a quick, easy, batch-enabled way!
* [ivandavidov/minimal](https://github.com/ivandavidov/minimal) - Minimal Linux Live (MLL) is a tiny educational Linux distribution, which is designed to be built from scratch by using a collection of automated shell scripts. Minimal Linux Live offers a core environment with just the Linux kernel, GNU C library, and Busybox userland utilities.
* [realtho/PartyLoud](https://github.com/realtho/PartyLoud) - A simple tool to generate fake web browsing and mitigate tracking
* [Toxic-Cat/Airport-toolkit](https://github.com/Toxic-Cat/Airport-toolkit) - 各類方便機場主進行安裝維護的shell腳本
* [caarlos0/jvm](https://github.com/caarlos0/jvm) - Never manually change your JAVA_HOME again
* [webdna/serverpilot-scripts](https://github.com/webdna/serverpilot-scripts) - A collection of scripts for setting up various items / running tasks on serverpilot provisioned servers
* [ricardobeat/git-commands](https://github.com/ricardobeat/git-commands) - Custom power-user git commands.
* [ptrofimov/github-backup-sh](https://github.com/ptrofimov/github-backup-sh) - Simple shell script to backup all GitHub repos for specified user
* [mezga0153/offscreen-window-restore](https://github.com/mezga0153/offscreen-window-restore) - A simple shell script that moves off screen windows back
* [kerolloz/go-installer](https://github.com/kerolloz/go-installer) - 📜 A simple shell script to install the Go :blue_heart: programming language!
* [joarleymoraes/aws_lambda_deploy](https://github.com/joarleymoraes/aws_lambda_deploy) - Automated AWS Lambda Deployment (Python)
* [cybernova/DNSaxfr](https://github.com/cybernova/DNSaxfr) - Shell script for testing DNS zone transfer (AXFR query) on domains and subdomains recursively.
* [haikieu/shell-progressbar](https://github.com/haikieu/shell-progressbar) - Make a progress bar GUI on terminal platform (Shell script)
* [chr4/shellrc](https://github.com/chr4/shellrc) - Shell dotfiles, conf.d stype, for multiple shells (bash, zsh)
* [caarlos0-graveyard/shell-ci-build](https://github.com/caarlos0-graveyard/shell-ci-build) - A submodule to lint your shell projects with shellcheck in travis.ci builds
* [arunoda/fastai-shell](https://github.com/arunoda/fastai-shell) - A workflow to setup and use fastai on Google Cloud Platfrom
* [anudeepND/whitelist](https://github.com/anudeepND/whitelist) - A simple tool to add commonly white listed domains to your Pi-Hole setup.
* [Native-C/login-shell](https://github.com/Native-C/login-shell) - SSH登陆显示脚本
* [XIU2/SHELL](https://github.com/XIU2/SHELL) - 🤪 一些乱七八糟的脚本
* [levinit/itnotes](https://github.com/levinit/itnotes) - 个人笔记，IT相关。
* [ZephrFish/RandomScripts](https://github.com/ZephrFish/RandomScripts) - Random Shell Scripts and other ideas I have along the way
* [theshteves/commit-bot](https://github.com/theshteves/commit-bot) - Automatically generates GitHub activity
* [stevenkaras/bashfiles](https://github.com/stevenkaras/bashfiles) - My personal bashfiles - bash prompt, dotfiles, etc
* [RookieFeng/ipa_re_sign](https://github.com/RookieFeng/ipa_re_sign) - Re_sign an ipa using Apple Enterprise Certificate 使用企业证书 对 ipa 进行重签名.
* [RomainClaret/lfs-7.8](https://github.com/RomainClaret/lfs-7.8) - Shell script to automate Linux from Scratch, based on the book 7.8
* [raimue/ssl-cert-check](https://github.com/raimue/ssl-cert-check) - Check expiry dates of local and remote SSL certificates
* [posva/task-logger.sh](https://github.com/posva/task-logger.sh) - :art: shell library to log tasks with nice output. Supports zsh and bash
* [plushu/plushu](https://github.com/plushu/plushu) - Pluggable Shell User
* [loopbit/autoenv_fish](https://github.com/loopbit/autoenv_fish) - Directory-based environments for fish shell users
* [KimDarren/git-faker](https://github.com/KimDarren/git-faker) - :ghost: You can be the best GIT-COMMITTER in the planet.
* [jnaqsh/ffmpeg_installer](https://github.com/jnaqsh/ffmpeg_installer) - A Linux Shell Script for compiling, installing and uninstalling FFmpeg in CentOS
* [Jaggle/Gitfool](https://github.com/Jaggle/Gitfool) - Gitfool (or Gitfull) is a shell command for you to fulfill your git commit log.
* [guchongxi/gen-git-log](https://github.com/guchongxi/gen-git-log) - 自动生成git commit记录用以统计个人项目周报，全组项目周报，版本差异记录等
* [grantlucas/Logger-TXT](https://github.com/grantlucas/Logger-TXT) - Logger TXT is a small, shell based tool to log activities throughout the day to a simple, portable text file, along with the date/time. Options are available to log a specific entry under a type and project. All entries are stored in log.txt which is automatically created in the folder where logger.sh resides.
* [gilbertw1/roficlip](https://github.com/gilbertw1/roficlip) - A simple shell script that surfaces clipboard history from clipster in Rofi
* [frankjuniorr/github-create-release-action](https://github.com/frankjuniorr/github-create-release-action) - :octocat: Github Action that create Github Release automatically
* [ferd/erl_crashdump_analyzer](https://github.com/ferd/erl_crashdump_analyzer) - shell script to analyze Erlang crash dumps and find some (generally) useful information.
* [alixaxel/halBox](https://github.com/alixaxel/halBox) - Bash Script to Bootstrap Debian/Ubuntu Servers
* [abhijitvalluri/bash-powerline-shell](https://github.com/abhijitvalluri/bash-powerline-shell) - A beautiful, efficient and useful PS1 prompt for your bash shell
* [winder/svgToDxf](https://github.com/winder/svgToDxf) - Shell script that uses inkscape and pstoedit to convert svgToDxf
* [we-sh/42ShellTester](https://github.com/we-sh/42ShellTester) - Integration test suite for Shell implementation
* [sjz123321/goproxy-shell](https://github.com/sjz123321/goproxy-shell) - goproxy服务端部署脚本
* [rptec/vps-shell](https://github.com/rptec/vps-shell) - 收集一些自用的shell脚本，适用于懒人使用。
* [hibara/create-ios-all-icons-shellscript](https://github.com/hibara/create-ios-all-icons-shellscript) - Use Shell Script commands in only MacOSX for generating all icons that need to build iOS app.
* [er0/lolfish](https://github.com/er0/lolfish) - the most colorful fish shell prompt
* [daenney/rbenv](https://github.com/daenney/rbenv) - Rbenv support plugin for fish-shell
* [appleboy/dotfiles](https://github.com/appleboy/dotfiles) - Bootstrap for your terminal on Linux or FreeBSD
* [amiya-pattnaik/appium-setup-made-easy-OSX](https://github.com/amiya-pattnaik/appium-setup-made-easy-OSX) - Hassle free Appium setup on OSX using shell script. These shell script utility will help you set up iOS and Android on OSX.
* [Nefelim4ag/systemd-swap](https://github.com/Nefelim4ag/systemd-swap) - Script for creating hybrid swap space from zram swaps, swap files and swap partitions.
* [jorgebucaran/fishtape](https://github.com/jorgebucaran/fishtape) - TAP-based test runner for the fish shell.


# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/veilair/shell-development/blob/master/contributing.md) first.

## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Veilair](https://github.com/veilair/) has waived all copyright and related or neighboring rights to this work.

[Back to top](#table-of-contents)
