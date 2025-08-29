# hrmpf - Void Linux Rescue System

```
     _                    __ 
    | |_  _ _ _ __  _ __ / _|
    | ' \| '_| '  \| '_ \  _|
    |_||_|_| |_|_|_| .__/_|
                   |_|      
```

**hrmpf** is a powerful rescue and maintenance system based on Void Linux. It provides an extensive collection of tools for system rescue, maintenance, diagnostics, networking, security, and ad-hoc setups.

## Overview

hrmpf is a live system that can be burned to CD or written directly to a USB stick. It loads the entire system into memory, allowing it to run quickly even from slow USB sticks or CD-ROMs. The system can also be loaded via netboot.xyz.

## Features

### Tools and Applications

#### Diagnostic Tools
- `acpi` - Display battery and temperature information
- `atop` - System and process activities in terminal
- `blktrace` - Block layer I/O tracer
- `bonnie++` - File system and disk benchmark
- `diskscan` - Scans disks for bad blocks
- `dmidecode` - Display DMI/SMBIOS information
- `dstat` - Multi-purpose statistics tool
- `extrace` - Tracks program and library execution
- `f3` - Tests flash memory capacity and reliability
- `fatrace` - Traces file system accesses
- `fio` - Flexible I/O tester
- `hddtemp` - Displays hard disk temperature
- `htop` - Interactive process viewer
- `hwinfo` - Hardware information tool
- `i2c-tools` - Various I2C tools
- `idle3-tools` - Idle3 timer tools for Western Digital hard drives
- `interbench` - Benchmark for latency and bandwidth
- `ioping` - Simple latency measurement tool
- `ioprof` - I/O profiler
- `iotop-c` - Shows I/O usage by processes
- `ipmitool` - Command-line tool for IPMI
- `lm_sensors` - Hardware sensor query
- `lshw` - Hardware lister
- `lsof` - List open files
- `lsscsi` - List SCSI devices
- `ltrace` - Library call tracer
- `memtester` - Memory tester
- `nethogs` - Net top tool grouped by processes
- `pciutils` - PCI bus tools
- `powertop` - Power consumption analysis tool
- `read-edid` - EDID reading tool
- `smartmontools` - SMART hard disk tools
- `strace` - System call tracer
- `stress` - Tool to generate CPU/MEM/IO load
- `stress-ng` - Stress tests for CPUs, memory, I/O
- `sysstat` - System performance tools
- `tiptop` - Process performance monitor
- `tpm-tools` - TPM tools
- `unixbench` - Unix benchmark suite
- `usbutils` - USB tools
- `virt-what` - Detects virtualization environment

#### Network Tools
- `6tunnel` - IPv4/IPv6 tunnel for network services
- `arp-scan` - ARP packet scanner
- `arpwatch` - Ethernet ARP table monitor
- `autossh` - Automatically restarting SSH sessions
- `bind-utils` - BIND DNS tools
- `bmon` - Bandwidth monitor and rate estimator
- `bridge-utils` - Bridge configuration tools
- `bwm-ng` - Bandwidth monitor (Next Generation)
- `chrony` - NTP client and server
- `create_ap` - Creates a WiFi access point
- `ddclient` - Updates dynamic DNS entries
- `dhclient` - DHCP client
- `dhcpcd` - DHCP/IPv4LL/IPv6RS/DHCPv6 client
- `dracut-network` - Dracut network modules
- `ethstatus` - Console-based Ethernet statistics monitor
- `ethtool` - Tool to display or change Ethernet device settings
- `ferm` - Firewall configuration manager
- `fping` - Ping tool to send ICMP ECHO_REQUEST packets to network hosts
- `grepcidr` - Filters IP addresses by CIDR networks
- `horst` - Horst's OLSR/802.11 sniffer/analyzer
- `hostapd` - IEEE 802.11 Access Point and IEEE 802.1X/WPA/WPA2 Authenticator
- `httptunnel` - Creates tunnels for arbitrary TCP and UDP data streams
- `ifenslave` - Configure kernel network interfaces for ifenslave
- `ifstatus` - Displays the status of network interfaces
- `iftop` - Displays bandwidth usage on interfaces
- `inadyn` - Dynamic DNS client
- `inetutils-hostname` - Hostname tools
- `inetutils-talk` - Talk client for user messages
- `iodine` - Tunnels IPv4 data through a DNS server
- `ipcalc` - Simple IP network calculator
- `iperf` - TCP/UDP bandwidth measurement tool
- `iperf3` - Improved TCP/UDP bandwidth measurement
- `iprange` - IP address range management
- `iproute2` - Advanced IP routing tools
- `ipset` - IP set management for netfilter
- `iptables` - Administration tool for IPv4 packet filter rules
- `iptraf-ng` - Interactive color IP LAN monitor
- `iputils` - Network maintenance and test tools
- `iw` - Tool to configure wireless devices
- `jnettop` - Network traffic monitor
- `ldns` - Library to manipulate DNS packets
- `lft` - Layer Four Traceroute
- `liboping` - C library to generate and process ping
- `libressl-netcat` - Network read/write tool
- `lldpd` - LLDP protocol implementation
- `miniupnpc` - UPnP IGD client
- `miruo` - TCP/IP packet analyzer
- `mosh` - Mobile shell
- `msmtp` - SMTP client
- `mtr` - Network diagnostic tool
- `ndisc6` - IPv6 network discovery tools
- `nemesis` - Command-line based network packet generator
- `net-snmp` - SNMP tools
- `net-tools` - NET-3 tools
- `nfs-utils` - NFS tools
- `nftables` - Framework for packet classification and filtering
- `ngrep` - Network grep
- `nload` - Real-time network and system statistics monitor
- `nmon` - Nigel's performance Monitor for CPU/Memory/Disk statistics
- `ntp` - Network Time Protocol
- `openbsd-netcat` - OpenBSD netcat
- `openssh` - OpenSSH client and server
- `openssh-sk-helper` - OpenSSH Security Key Helper
- `pchar` - Tool to measure network characteristics
- `polysh` - Launches commands in multiple remote shells simultaneously
- `ppp` - Point-to-Point Protocol
- `pptpclient` - PPTP client
- `radvd` - Router Advertisement Daemon
- `redsocks` - Transparent TCP-to-proxy bridge
- `rpcbind` - RPC program binding
- `s6` - Small suite of tools for system administration
- `s6-linux-utils` - Linux system tools for s6
- `s6-dns` - DNS client library and tools for s6
- `s6-networking` - Network maintenance tools for s6
- `shorewall` - Shorewall firewall
- `shorewall6` - Shorewall6 firewall
- `sipcalc` - IP subnet calculator
- `slurm` - Network load monitor
- `socat` - Multipurpose relay (SOcket CAT)
- `sshpass` - Non-interactive SSH password provider
- `sshuttle` - Transparent proxy server
- `swaks` - Swiss Army Knife SMTP
- `tailscale` - Tailscale VPN client
- `tcpdump` - Network packet sniffer
- `tcpflow` - TCP/IP packet demultiplexer
- `tcping` - Measures TCP connection times
- `tcptrack` - TCP connection monitor
- `tinyssh` - Small SSH server
- `tor` - Anonymization network
- `traceroute` - Trace IP packet routes
- `vde2` - Virtual Distributed Ethernet
- `vpnc` - Cisco-compatible VPN client
- `wavemon` - WLAN monitor
- `whois` - WHOIS client
- `wireless_tools` - Wireless tools
- `wol` - Wake-On-LAN client
- `wpa_supplicant` - WPA/WPA2/WPA3 supplicant for WiFi
- `wrk` - Modern HTTP benchmarking tool
- `wvdial` - PPP dialer tool

#### General System Tools
- `aha` - ANSI HTML adapter
- `alsa-lib` - ALSA library
- `alsa-utils` - ALSA tools
- `ascii` - Displays ASCII table
- `at` - Delayed command execution
- `attr` - Tools to manipulate filesystem attributes
- `bbe` - Sed-like editing tool for binary files
- `bc` - GNU bc calculator
- `beep` - Beep command for PC speaker
- `buffer` - Buffering for shell commands
- `busybox` - Miniaturized Unix tools
- `byobu` - Text-based window manager
- `cdrtools` - CD/DVD/BluRay tools
- `cmark` - CommonMark-compliant markdown parser
- `colordiff` - Colorized diff
- `convmv` - Converts filenames from one charset to another
- `cpulimit` - Limits CPU usage of processes
- `cpupower` - CPU power management
- `cronie` - Cron daemon
- `curl` - Command-line tool to transfer data with URL syntax
- `daemonize` - Runs a command as a daemon
- `dateutils` - Date and time tools
- `db` - Berkeley DB library
- `dbus` - Simple interprocess messaging system
- `debootstrap` - Bootstrap a basic Debian system
- `detox` - Recursive filename cleaner
- `di` - Enhanced df-like disk information display
- `dialog` - Script tool for terminal color dialogs
- `diffutils` - File difference tools
- `dos2unix` - Converts text files between DOS, Mac and Unix formats
- `dtach` - Emulates the detach function of screen
- `duff` - Fast duplicate file finder
- `dvtm` - Terminal multiplexer
- `earlyoom` - Early OOM killer
- `entr` - Runs an arbitrary command when files change
- `etckeeper` - Version control for /etc
- `execline` - Small, powerful scripting language
- `fail` - Runs a command with a certain probability to fail
- `faketime` - Manipulates system time for programs
- `fbgrab` - Creates screenshots of the framebuffer
- `fbset` - Framebuffer device settings
- `fdupes` - Identifies and deletes duplicate files
- `file` - Identifies file types
- `findutils` - File search tools
- `firejail` - Security sandbox
- `fwupd` - Firmware update daemon
- `fzy` - Fast, simple fuzzy finder
- `gawk` - GNU awk
- `gcal` - Calendar program
- `gpm` - Generic mouse support for consoles
- `grep` - Searches text patterns
- `hostmux` - Host multiplexer
- `icdiff` - Improved diff
- `inotify-tools` - Inotify tools
- `ipgrep` - Extracts IP addresses from text
- `irqbalance` - Distributes interrupts over multiple CPUs
- `jf` - jq-like JSON queries
- `jo` - JSON generator
- `jq` - Lightweight and flexible JSON processor
- `kbd` - Keyboard tools
- `kexec-tools` - Fast system reboot
- `less` - Text file viewer
- `linux-firmware` - Firmware for Linux kernel drivers
- `logrotate` - Rotates, compresses and mails log files
- `lr` - Lists files recursively
- `lrzsz` - File transfer tools
- `lxc` - Linux containers
- `mawk` - AWK implementation
- `mbuffer` - Buffering for shell commands
- `mc` - Midnight Commander
- `metalog` - Modern system message collection
- `minised` - Small sed implementation
- `ministat` - Simple statistical analysis
- `mlog` - Multilog-like tool
- `mmv` - Moves/copies/renames multiple files
- `mtm` - Terminal multiplexer
- `multitail` - Shows multiple log files simultaneously
- `multitime` - Measures resource consumption of commands
- `ncdu` - NCurses disk usage
- `necho` - Echo with newline
- `nocache` - Prevents file I/O caching
- `nq` - Task queue
- `nsjail` - Process isolation tool
- `numactl` - NUMA control
- `odo` - Shows file differences
- `opendoas` - OpenBSD doas command
- `outils` - Outils standard tools
- `par` - Paragraph formatter
- `parallel` - Runs commands in parallel
- `pax-utils` - Security-related tools for files
- `perl` - Perl interpreter
- `pfetch` - Simple system information collector
- `picocom` - Minimal dumb-terminal emulator
- `pmr` - Parallel make-like execution
- `progress` - Shows progress of core processes
- `psmisc` - Tools to display process information
- `pv` - Shows progress of data through a pipe
- `python3` - Python interpreter
- `qrencode` - QR code generator
- `quota` - Quota management
- `ranger` - Console-based file manager
- `rdd` - Raw disk duplicator
- `rdfind` - Finds duplicate files
- `reap` - Removes child processes
- `reptyr` - Moves running programs to a new terminal
- `ripgrep` - Fast text searcher
- `rlwrap` - Readline wrapper
- `rset` - Remote setup
- `rw` - Rewrap
- `rwc` - Rewrap (C version)
- `s6` - Small suite of tools for system administration
- `sample` - Samples data streams
- `schedtool` - Tool to control process scheduling
- `screen` - Terminal multiplexer
- `shmux` - Shell multiplexer
- `sispmctl` - Controls Gembird SIS-PM power outlet strips
- `snooze` - Delays command execution
- `socklog-void` - Socklog system services
- `su-exec` - chroot, su, exec - all in one
- `sudo` - Runs a command as another user
- `tab` - Tabulator
- `the_silver_searcher` - Code search tool
- `time` - Measures program runtime
- `tio` - Terminal I/O tool
- `tmux` - Terminal multiplexer
- `tree` - Displays directory structure
- `ttyrec` - Terminal recording
- `ugrep` - Ultra-fast grep with interactive TUI
- `util-linux` - Various system tools
- `vimpager` - Vim-based pager
- `void-docs-browse` - Browses Void documentation
- `watchdog` - Software watchdog
- `wgetpaste` - Command-line tool to upload data to pastebin services
- `which` - Shows full path to commands
- `xe` - Xargs replacement
- `xjobs` - Runs commands in parallel
- `xmlstarlet` - XML tools
- `xtools` - xbps tools
- `xmirror` - XBPS mirror selection tool

#### Filesystems & Storage
- `bcache-tools` - Bcache tools
- `bcachefs-tools` - Bcachefs tools
- `btrfs-progs` - Btrfs tools
- `cryptsetup` - Manages encrypted devices
- `dmg2img` - Converts Apple DMG files
- `dmraid` - Device-mapper RAID interface
- `dosfstools` - Tools to manipulate FAT filesystems
- `dumpet` - Extracts and analyzes El Torito boot catalogs
- `e2fsprogs` - Ext2/3/4 tools
- `exfat-utils` - Tools to manipulate exFAT filesystems
- `ext4magic` - Recovery tool for ext3/ext4
- `fuse` - FUSE (Userspace FS)
- `fuse-exfat` - exFAT filesystem for FUSE
- `fuse-sshfs` - SSH filesystem for FUSE
- `geteltorito` - Extracts El Torito boot images
- `gptfdisk` - GPT partition table tools
- `hdparm` - Displays/manipulates SATA/IDE device parameters
- `hfsprogs` - HFS+ tools
- `hfsutils` - HFS tools
- `jfsutils` - JFS tools
- `kpartx` - Creates device mappings for partitions
- `lvm2` - LVM2 tools
- `mdadm` - RAID management
- `mergerfs` - Function-like union filesystem for FUSE
- `mhddfs` - Multi-Hard Disk Drive File System for FUSE
- `mtools` - Tools to manipulate MS-DOS files
- `nbd` - Network Block Device client and server
- `ntfs-3g` - NTFS driver support
- `nvme-cli` - NVMe tools
- `nwipe` - Securely wipes disks
- `open-iscsi` - Open-iSCSI initiator
- `partclone` - Filesystem-based partition clone tools
- `parted` - Partition table editor
- `s3cmd` - Tool to manage Amazon S3 and CloudFront
- `s3fs-fuse` - FUSE-based filesystem for Amazon S3
- `sdparm` - Displays/manipulates SCSI device parameters
- `sg3_utils` - SCSI device tools
- `simple-mtpfs` - Simple MTP filesystem for FUSE
- `squashfs-tools` - Squashfs tools
- `sysfsutils` - Sysfs tools
- `tc-play` - TrueCrypt implementation
- `tgt` - Userspace SCSI target
- `u9fs` - Plan 9 filesystem for Unix
- `udftools` - UDF tools
- `xfsdump` - XFS filesystem backup
- `xfsprogs` - XFS tools
- `zerofree` - Zeros unused filesystem blocks
- `zfs` - OpenZFS

#### Bootloaders
- `efibootmgr` - EFI Boot Manager
- `efitools` - EFI tools
- `efivar` - EFI variable tools
- `systemd-boot` - Bootloader for UEFI systems
- `ms-sys` - Tool to write Master Boot Records
- `sbctl` - Secure Boot key manager
- `sbsigntool` - Signs EFI binaries
- `vboot-utils` - Vboot tools

#### Archives
- `7zip` - 7-Zip compression tool
- `bsdtar` - BSD tar
- `bzip2` - Block-sorting file compressor
- `bzip3` - Improved bzip2 replacement
- `cabextract` - Microsoft Cabinet file extractor
- `cksfv` - SFV checksum tool
- `cpio` - Copies files in and out of archives
- `dpkg` - Debian package management
- `gzip` - GNU-ZIP compressor
- `lbzip2` - Parallel bzip2 compressor
- `lrzip` - Long Range compressor
- `lzip` - LZMA-based file compressor
- `lzop` - Real-time LZO compressor/decompressor
- `par2cmdline` - PAR 2.0 command-line tool
- `pax` - Portable Archive Exchange
- `pbzip2` - Parallel bzip2 compressor
- `pigz` - Parallel gzip
- `pixz` - Parallel, indexed xz
- `plzip` - Parallel lzip compressor
- `rpmextract` - Extracts RPM packages
- `sharutils` - Shell archive tools
- `tar` - Tar archive tool
- `unp` - Unpacks various archive formats
- `unzip` - De-compresses ZIP archives
- `xz` - XZ compressor
- `zip` - ZIP compressor
- `zstd` - Zstandard compressor
- `zutils` - Tools for transparent compression

#### Security Tools
- `age` - Simple, modern and secure file encryption
- `ccrypt` - Strong encryption for files and streams
- `chntpw` - Offline NT Password and Registry Editor
- `dnsmap` - DNS domain name brute forcer
- `easyrsa` - PKI management tool
- `ent` - Pseudo-random sequence test
- `ettercap` - Network analysis and manipulation
- `gnupg2` - GNU Privacy Guard 2
- `gnupg2-scdaemon` - Smartcard daemon for GnuPG
- `hashcat` - World's fastest password recovery program
- `haveged` - High entropy generator daemon
- `john` - John the Ripper - Password cracker
- `keyutils` - Linux Key Management tools
- `kismet` - Wireless network sniffer and IDS
- `masscan` - Very fast TCP port scanner
- `minisign` - Signs files and verifies signatures
- `nmap` - Network exploration tool and port scanner
- `opensc` - Smartcard API and drivers
- `opensc-pkcs11` - PKCS#11 API for smartcards
- `openssl` - OpenSSL cryptography
- `p0f` - Passive OS fingerprinting tool
- `paperkey` - Extracts OpenPGP keys for paper backup
- `pass` - Simple password manager
- `passwdqc` - Quality control for passwords
- `pdfcrack` - PDF password recovery
- `pgpdump` - Displays PGP packets in assembler style
- `pwgen` - Password generator
- `reaver` - Brute-force attack against WPS
- `reop` - Encryption without keys
- `rng-tools` - Hardware RNG tools
- `scrypt` - Tool for scrypt-like password-based KDF
- `testssl.sh` - Checks a server configuration for TLS/SSL weaknesses
- `yubikey-manager` - Configuration tool for YubiKey
- `zmap` - Fast single port scanner

#### Development
- `autoconf` - GNU autoconfiguration
- `automake` - GNU automation tool
- `binutils` - GNU binary tools
- `bison` - GNU parser generator
- `cpanminus` - CPAN module installer
- `cvs` - Concurrent Versions System
- `flex` - Fast Lexical Analyzer Generator
- `gcc` - GNU C compiler
- `gdb` - GNU debugger
- `gettext` - GNU internationalization tool
- `git` - Distributed version control system
- `glibc-devel` - GNU C library development headers
- `libtool` - Generic library support script
- `m4` - Macro processor
- `make` - GNU make
- `mercurial` - Distributed SCM
- `patch` - Applies diff files
- `pkg-config` - Returns meta information about installed libraries
- `rcs` - Revision Control System
- `redo` - Simple build system
- `smake` - Make program
- `texinfo` - Online documentation in Info format

#### Rescue & Forensics
- `aide` - Advanced Intrusion Detection Environment
- `antiword` - Displays MS Word documents
- `b3sum` - BLAKE3 checksum tool
- `bcal` - Byte CALculator
- `biew` - Binary editor and viewer
- `binfmt-support` - Kernel module for executable file formats
- `binwalk` - Firmware analysis tool
- `bvi` - Hex editor
- `chkrootkit` - Checks local installation for rootkits
- `dcraw` - Decodes RAW photos
- `ddrescue` - Data recovery tool
- `dhex` - Ncurses-based hex editor
- `docx2txt` - Converts .docx files to plain text files
- `e2tools` - Tools to manipulate ext2/ext3 filesystems
- `extundelete` - Recovery tool for ext3/ext4
- `fbv` - Framebuffer image viewer
- `flashrom` - Chip and programming tool for flash ROMs
- `foremost` - File recovery
- `hashdeep` - Recursive message digest/watermark generator
- `hexd` - Hex dump
- `ht` - Hex, disk and file editor
- `hyx` - Hyx file extractor
- `ired` - Interactive hex editor
- `jhead` - JPEG header information
- `lz4jsoncat` - Decompresses and displays LZ4-compressed JSON files
- `mtree` - File hierarchy comparison tool
- `pev` - PE binary analyzer
- `pixd` - Pixel dump
- `rhash` - Checksum tool
- `rkhunter` - Rootkit and trojan hunter
- `sleuthkit` - Forensics tools
- `ssdeep` - Contextual trigger points
- `testdisk` - Partition recovery
- `tweak` - Efficient hex editor
- `vbindiff` - Visual binary file comparer

#### Entertainment
- `cmus` - C* Music Player
- `cmus-flac` - FLAC support for C* Music Player
- `cmus-libao` - Libao support for C* Music Player
- `cmus-mpc` - MPC support for C* Music Player
- `cpat` - Patience-like card game
- `ddate` - Discordian date
- `libao-sndio` - Sndio audio output for libao
- `mpg123` - MP3 audio player
- `nudoku` - ncurses-based sudoku
- `rogue` - Dungeons of Doom game
- `sndio` - Audio/MIDI API and drivers
- `tmines` - Terminal minesweeper
- `vitetris` - Terminal tetris
- `vorbis-tools` - Ogg Vorbis tools

#### Backup
- `attic` - Deduplicating backup program
- `backupninja` - Metabackup system
- `borg` - Deduplicating backup program
- `btrbk` - Backup tool for btrfs subvolumes
- `csync2` - Cluster synchronization tool
- `dar` - Disk ARchive
- `duplicity` - Encrypted bandwidth-efficient backup software
- `dvdbackup` - DVD backup tool
- `fsarchiver` - Filesystem archiving
- `mt-st` - Magnetic tape control
- `rdiff-backup` - Reverse diff backup
- `rdumpfs` - Deduplicating filesystem backup
- `restic` - Fast, secure and efficient backup program
- `rsnapshot` - Filesystem snapshot tool
- `rsync` - Fast incremental file transfer
- `snapraid` - Backup program for disk arrays
- `snazzer` - Btrfs snapshot tool
- `zpaq` - Extensible, self-verifying archive format

#### Shells
- `dash` - POSIX-compliant shell
- `fish-shell` - Friendly interactive shell
- `mksh` - MirBSD Korn Shell
- `pdmenu` - Simple ncurses menu program
- `posh` - Policy-compliant ordinary shell
- `rc` - AT&T-Bell Labs shell
- `tcsh` - Extended C shell
- `yash` - POSIX-compliant shell

#### Text Editors
- `dte` - Dunkelheit's Text Editor
- `e3` - Lightweight text editor
- `ed` - Standard text editor
- `ex-vi` - Ex-vi text editor
- `jupp` - Joe's Own Editor
- `mg` - Micro-GNU-Emacs
- `nano` - Simple text editor
- `neatvi` - Neat vi-like editor
- `nvi` - 4.4BSD-vi text editor
- `qed` - QED text editor
- `vim` - Vi IMproved

#### Clients
- `alpine` - Alternative Pine-like e-mail reader
- `edbrowse` - Line-oriented editor, browser and e-mail client
- `elinks` - Advanced text mode web browser
- `ii` - Minimal IRC client
- `inetutils-ftp` - FTP client
- `inetutils-telnet` - Telnet client
- `irssi` - Modular text mode IRC client
- `ldapvi` - Direct LDAP entry editor
- `lftp` - Sophisticated file transfer program
- `links` - Text mode web browser
- `lynx` - Text-based web browser
- `mblaze` - Unix mail tools
- `mcabber` - Small Jabber (XMPP) client
- `mpop` - SMTP client
- `mutt` - Text-based mail client
- `ncftp` - FTP client
- `rtorrent` - Ncurses-based BitTorrent client
- `s-nail` - Mail processing system
- `sacc` - Simple gopher client
- `sic` - Simple IRC client
- `tin` - Newsreader
- `tnftp` - Enhanced FTP client
- `w3m` - Text-based web browser
- `weechat` - Fast, light and extensible chat client

#### Servers
- `dnsmasq` - Lightweight DHCP and caching DNS server
- `fastd` - Fast and Secure Tunneld Daemon
- `hitch` - Libev-based high performance SSL/TLS proxy
- `inetutils-inetd` - Internet services daemon
- `nginx` - Lightweight web server
- `nsd` - Authoritative DNS server
- `opensmtpd` - OpenSMTPD mail server
- `openvpn` - Virtual private network
- `polipo` - Local proxy
- `privoxy` - Web proxy with advanced filtering capabilities
- `rsyslog` - System logging daemon
- `stunnel` - Universal SSL tunnel
- `tftp-hpa` - HPA's TFTP server
- `tinyproxy` - Lightweight HTTP/HTTPS proxy daemon
- `unbound` - Validating, recursive and caching DNS resolver
- `wireguard-tools` - Tools for the WireGuard VPN
- `wstunnel` - Tunnels TCP over WebSocket
- `xinetd` - Extended internet services daemon

#### Office Applications
- `python3-xlrd` - Reading Excel files with Python
- `sc` - Spreadsheet Calculator
- `sc-im` - Spreadsheet Calculator Improvised
- `visidata` - Interactive multitool for tabular data
- `wcal` - Calendar tool
- `when` - Mini-calendar/workday calculator

#### Accessibility
- `brltty` - Access to the Linux console for blind users
- `espeakup` - eSpeak speech output daemon
- `void-live-audio` - Audio tools for live systems

### Additional Features
- Memtest86+ for memory testing
- ZFS support
- Easily installable additional software via XBPS
- Support for non-Linux extra images (only via ISOLINUX):
  - iPXE
  - FreeDOS
  - MHDD32 hard disk analysis
  - Bare GRUB 2
- Can be burned to CD or written directly to USB stick
- Option to load into RAM
- Bootable as MEMDISK or via netboot.xyz
- Clean Bash as default shell without annoying configuration

## Minimum Requirements

- x86_64 CPU
- 512 MB RAM

## Dependencies

- xbps
- GNU bash

## Usage

### Download Pre-built Images

Pre-built images can be downloaded at the following URL:
[https://github.com/leahneukirchen/hrmpf/releases](https://github.com/leahneukirchen/hrmpf/releases)

### Build Your Own Image

To build your own image, run the following command:

```bash
sudo ./mkhrmpf.sh
```

### Available Scripts

The project contains several scripts for creating different types of live images:

1. `mkhrmpf.sh` - Main script to create the hrmpf system
2. `mklive.sh` - Creates a basic live ISO image of Void Linux
3. `mkiso.sh` - Creates a more complete live ISO image
4. `mkrootfs.sh` - Creates a root filesystem archive
5. `mkimage.sh` - Creates a bootable image
6. `mknet.sh` - Creates a network boot image
7. `mkplatformfs.sh` - Creates a platform-specific filesystem

### Installation

The system includes an installation assistant (`void-installer`) that helps with installing Void Linux on a system.

## License

See COPYING file for complete license information.