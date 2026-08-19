# Awesome-anti-forensic with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 497,774 | 🐛 102 | 📅 2026-08-18
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/LICENSE-CC_BY_4.0-00a2ff?\&style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

Tools and packages that are used for countering forensic activities, including encryption, steganography, and anything that modify attributes. This all includes tools to work with anything in general that makes changes to a system for the purposes of hiding information.

## Tools

### System/Digital Image

* [Frida](https://github.com/frida/frida) ⭐ 21,674 | 🐛 1,958 | 🌐 Meson | 📅 2026-08-18 : Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.
  * [Fridump](https://github.com/Nightbringer21/fridump) ⭐ 857 | 🐛 26 | 🌐 Python | 📅 2024-08-07 : A universal memory dumper using Frida.
* [Dmg2img](https://github.com/Lekensteyn/dmg2img) ⭐ 271 | 🐛 15 | 🌐 C | 📅 2020-12-27 : A CLI tool to uncompress Apple's compressed DMG files to the HFS+ IMG format.
* [Bmap-tools](https://github.com/intel/bmap-tools) ⚠️ Archived : Tool for copying largely sparse files using information from a block map file.
* [Imagemounter](https://github.com/ralphje/imagemounter) ⭐ 127 | 🐛 6 | 🌐 Python | 📅 2023-02-09 : Command line utility and Python package to ease the (un)mounting of forensic disk images.
* [Afflib](https://github.com/sshock/AFFLIBv3) ⭐ 94 | 🐛 3 | 🌐 C++ | 📅 2026-05-15 : An extensible open format for the storage of disk images and related forensic.information.
* [Air-Imager](https://sourceforge.net/projects/air-imager/) : A GUI front-end to dd/dc3dd designed for easily creating forensic images.
* [dd]() : The dd command allows you to copy all or part of a disk.
  * [Dc3dd](https://doc.ubuntu-fr.org/dc3dd) : A patched version of dd that includes a number of features useful for computer forensics.
  * [Dcfldd](https://doc.ubuntu-fr.org/dcfldd) : DCFL (DoD Computer Forensics Lab), a dd replacement with hashing.
* [ddrescue](https://doc.ubuntu-fr.org/ddrescue) : GNU data recovery tool.

### Recovering tool / Memory Extraction

* [TestDisk & PhotoRec](https://github.com/cgsecurity/testdisk) ⭐ 2,532 | 🐛 90 | 🌐 C | 📅 2026-08-19 : TestDisk checks the partition and boot sectors of your disks. It is very useful in recovering lost partitions. PhotoRec is file data recovery software designed to recover lost pictures from digital camera memory or even hard disks. It has been extended to search also for non audio/video headers.
* [Mxtract](https://github.com/rek7/mXtract) ⭐ 587 | 🐛 0 | 🌐 C++ | 📅 2021-11-09 : Memory Extractor & Analyzer.
* [Foremost](https://github.com/korczis/foremost) ⭐ 374 | 🐛 6 | 🌐 C | 📅 2023-05-26 : A console program to recover files based on their headers, footers, and internal data structures.
* [Recoverjpeg](https://github.com/samueltardieu/recoverjpeg) ⭐ 80 | 🐛 1 | 🌐 C | 📅 2023-01-29 : Recover jpegs from damaged devices.
* [MemFetch](https://github.com/citypw/lcamtuf-memfetch) ⭐ 42 | 🐛 0 | 🌐 C | 📅 2018-02-08 : Simple utility that can be used to dump process memory of any userspace process running on the system without affecting its execution.
* [MemDump](https://github.com/kost/memdump) ⭐ 12 | 🐛 0 | 🌐 C | 📅 2018-03-13 : Dumps system memory to stdout, skipping over holes in memory maps.
* [Scrounge-Ntfs](https://github.com/lcorbasson/scrounge-ntfs) ⭐ 12 | 🐛 1 | 🌐 C | 📅 2017-02-16 : Data recovery program for NTFS file systems.
* [MagicRescue](https://github.com/jbj/magicrescue) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2021-09-12 : Find and recover deleted files on block devices.
* [Extundelete](http://extundelete.sourceforge.net/) : Utility for recovering deleted files from ext2, ext3 or ext4 partitions by parsing the journal.
* [SafeCopy](https://doc.ubuntu-fr.org/safecopy) : A disk data recovery tool to extract data from damaged media.

### Analysis / Gathering tool (Know your ennemies)

* [Volatility](https://github.com/volatilityfoundation/volatility) ⚠️ Archived : Advanced memory forensics framework.
* [Autopsy](https://github.com/sleuthkit/autopsy) ⭐ 3,289 | 🐛 398 | 🌐 Java | 📅 2026-06-20 : The forensic browser. A GUI for the Sleuth Kit.
* [Sleuthkit](https://github.com/sleuthkit/sleuthkit) ⭐ 3,130 | 🐛 475 | 🌐 C | 📅 2026-08-19 : A library and collection of command line digital forensics tools that allow you to investigate volume and file system data.
* [Emldump](https://github.com/DidierStevens/DidierStevensSuite/blob/master/emldump.py) ⭐ 2,520 | 🐛 13 | 🌐 Python | 📅 2026-07-30 : Analyze MIME files.
* [Pdfid](https://github.com/DidierStevens/DidierStevensSuite/blob/master/pdfid.py) ⭐ 2,520 | 🐛 13 | 🌐 Python | 📅 2026-07-30 : Scan a file to look for certain PDF keywords.
* [Rekall](https://github.com/google/rekall) ⚠️ Archived : Memory Forensic Framework.
* [PcapXray](https://github.com/Srinivas11789/PcapXray) ⭐ 1,876 | 🐛 15 | 🌐 Python | 📅 2026-05-01 : Network Forensics Tool - To visualize a Packet Capture offline as a Network Diagram including device identification, highlight important communication and file extraction
* [Peepdf](https://github.com/jesparza/peepdf) ⭐ 1,461 | 🐛 49 | 🌐 Python | 📅 2024-08-19 : A Python tool to explore PDF files in order to find out if the file can be harmful or not.
* [Bulk-extractor](https://github.com/simsong/bulk_extractor) ⭐ 1,409 | 🐛 67 | 🌐 C++ | 📅 2026-08-18 : Bulk Email and URL extraction tool.
* [captipper](https://github.com/omriher/CapTipper) ⭐ 725 | 🐛 15 | 🌐 Python | 📅 2023-03-16 : Malicious HTTP traffic explorer tool.
* [Recuperabit](https://github.com/Lazza/RecuperaBit) ⭐ 622 | 🐛 35 | 🌐 Python | 📅 2026-07-26 : A tool for forensic file system reconstruction.
* [Swap-digger](https://github.com/sevagas/swap_digger) ⭐ 536 | 🐛 1 | 🌐 Shell | 📅 2021-06-26 : A tool used to automate Linux swap analysis during post-exploitation or forensics.
* [Ntdsxtract](https://github.com/csababarta/ntdsxtract) ⭐ 335 | 🐛 20 | 🌐 Python | 📅 2022-03-24 \[windows]: Active Directory forensic framework.
* [Indxparse](https://github.com/williballenthin/INDXParse) ⭐ 227 | 🐛 14 | 🌐 Python | 📅 2023-11-01 : A Tool suite for inspecting NTFS artifacts.
* [Xplico](https://github.com/xplico/xplico) ⭐ 204 | 🐛 17 | 🌐 PHP | 📅 2020-08-28 : Internet Traffic Decoder. Network Forensic Analysis Tool (NFAT).
* [Volafox](https://github.com/n0fate/volafox) ⭐ 175 | 🐛 1 | 🌐 Python | 📅 2016-07-25 : macOS Memory Analysis Toolkit.
* [LiMEaide](https://github.com/kd8bny/LiMEaide) ⭐ 157 | 🐛 2 | 🌐 Python | 📅 2020-08-26 : Remotely dump RAM of a Linux client and create a volatility profile for later analysis on your local host.
* [Rifiuti2](https://github.com/abelcheung/rifiuti2) ⭐ 155 | 🐛 1 | 🌐 C | 📅 2025-11-11 : A rewrite of rifiuti, a great tool from Foundstone folks for analyzing Windows Recycle Bin INFO2 file.
* [Dumpzilla](https://github.com/Busindre/dumpzilla) ⭐ 148 | 🐛 10 | 🌐 Python | 📅 2025-12-09 : A forensic tool for firefox.
* [IPBA2](https://github.com/PicciMario/iPhone-Backup-Analyzer-2) ⭐ 107 | 🐛 9 | 🌐 Python | 📅 2014-05-05 : IOS Backup Analyzer.
* [PdfResurrect](https://github.com/enferex/pdfresurrect) ⭐ 103 | 🐛 1 | 🌐 C | 📅 2022-09-10 : A tool aimed at analyzing PDF documents.
* [Chromefreak](https://github.com/OsandaMalith/ChromeFreak) ⭐ 70 | 🐛 0 | 🌐 Python | 📅 2015-03-15 : A Cross-Platform Forensic Framework for Google Chrome.
* [SkypeFreak](https://github.com/OsandaMalith/SkypeFreak) ⭐ 65 | 🐛 5 | 🌐 Python | 📅 2017-05-21 : A Cross Platform Forensic Framework for Skype.
* [IOSforensic](https://github.com/Flo354/iOSForensic) ⚠️ Archived : iOS forensic tool.
* [ReplayProxy](https://github.com/sparrowt/replayproxy) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2022-01-19 : Forensic tool to replay web-based attacks (and also general HTTP traffic) that were captured in a pcap file.
* [Iphoneanalyzer](https://github.com/foreni-packages/iphoneanalyzer) ⭐ 6 | 🐛 0 | 📅 2015-10-03 : Allows you to forensically examine or recover date from in iOS device.
* [Pev](https://github.com/merces/pev) ⭐ 3 | 🐛 0 | 📅 2023-04-20 : Command line based tool for PE32/PE32+ file analysis.
* [Galleta](https://sourceforge.net/projects/odessa/files/Galleta/) : Examine the contents of the IE's cookie files for forensic purposes.
* [Guymager](https://guymager.sourceforge.io/) : A forensic imager for media acquisition.
* [MboxGrep](https://sourceforge.net/projects/mboxgrep/) : A small, non-interactive utility that scans mail folders for messages matching regular expressions. It does matching against basic and extended POSIX regular expressions, and reads and writes a variety of mailbox formats.
* [Mobiusft](https://www.nongnu.org/mobiusft/) : An open-source forensic framework written in Python/GTK that manages cases and case items, providing an abstract interface for developing extensions.
* [Naft](https://blog.didierstevens.com/programs/network-appliance-forensic-toolkit/) : Network Appliance Forensic Toolkit.\
  [Networkminer](https://www.netresec.com/?page=Networkminer) A Network Forensic Analysis Tool for advanced Network Traffic Analysis, sniffer and packet analyzer.
* [Nfex](https://github.com/deadbits/nfex) : A tool for extracting files from the network in real-time or post-capture from an offline tcpdump pcap savefile.
* [Pasco](http://b2b-download.mcafee.com/products/tools/foundstone/pasco.zip) : Examines the contents of Internet Explorer's cache files for forensic purposes.                                          |
* [Pdfbook-analyzer](https://sourceforge.net/projects/pdfbook/) : Utility for facebook memory forensics.
* [Rkhunter](http://rkhunter.sourceforge.net/) : Checks machines for the presence of rootkits and other unwanted tools.
* [Vinetto](https://sourceforge.net/projects/vinetto/) : A forensics tool to examine Thumbs.db files.

### Data tampering

* [Exiftool](https://github.com/qazbnm456/awesome-web-security) ⭐ 13,698 | 🐛 15 | 🌐 Python | 📅 2026-08-04 : Reader and rewriter of EXIF informations that supports raw files.
* [Exiv2](https://github.com/Exiv2/exiv2) ⭐ 1,156 | 🐛 201 | 🌐 C++ | 📅 2026-08-19 : Exif, Iptc and XMP metadata manipulation library and tools.
* [Scalpel](https://github.com/sleuthkit/scalpel) ⭐ 686 | 🐛 44 | 🌐 Shell | 📅 2024-03-27 : An open source data carving tool.
* [nTimetools](https://github.com/limbenjamin/nTimetools) ⭐ 53 | 🐛 1 | 🌐 C | 📅 2021-09-14 : Timestomper and Timestamp checker with nanosecond accuracy for NTFS volumes.
* [SetMace](https://github.com/jschicht/SetMace) ⭐ 53 | 🐛 4 | 🌐 AutoIt | 📅 2014-11-10 : Manipulate timestamps on NTFS.

### Hiding process

* [Saruman](https://github.com/elfmaster/saruman) ⭐ 140 | 🐛 1 | 🌐 C | 📅 2018-03-14 : ELF anti-forensics exec, for injecting full dynamic executables into process image (With thread injection).
* [Kaiser](https://github.com/ntraiseharderror/kaiser) ⭐ 92 | 🐛 0 | 🌐 C | 📅 2018-12-06 : File-less persistence, attacks and anti-forensic capabilities (Windows 7 32-bit).
* [Harness](https://github.com/droberson/harness) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2019-07-21 : Execute ELFs in memory.
* [Papa Shango](https://github.com/droberson/papa-shango) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2019-08-30 : Inject code into running processes with ptrace().
* [Unhide](http://www.unhide-forensics.info/?Linux:Download) : A forensic tool to find processes hidden by rootkits, LKMs or by other techniques.

### Cleaner / Data Destruction / Wiping / FileSystem

* [BleachBit](https://github.com/bleachbit/bleachbit) ⭐ 6,623 | 🐛 312 | 🌐 Python | 📅 2026-08-19 : System cleaner for Windows and Linux.
* [Meterpreter > clearev](https://github.com/rapid7/metasploit-payloads) ⭐ 2,048 | 🐛 82 | 🌐 C | 📅 2026-08-17 : The meterpreter clearev command will clear the Application, System, and Security logs on a Windows system.
* [NTFS-3G](https://github.com/tuxera/ntfs-3g) ⭐ 1,471 | 🐛 100 | 🌐 C | 📅 2026-07-15 : NTFS-3G Safe Read/Write NTFS Driver.
* [Forensia](https://github.com/PaulNorman01/Forensia) ⭐ 786 | 🐛 5 | 🌐 C++ | 📅 2023-06-23 : Anti Forensics Tool For Red Teamers, Used For Erasing Footprints In The Post Exploitation Phase.
* [Silk-guardian](https://github.com/NateBrune/silk-guardian) ⭐ 723 | 🐛 8 | 🌐 C | 📅 2024-02-05 : An anti-forensic kill-switch that waits for a change on your usb ports and then wipes your ram, deletes precious files, and turns off your computer.
* [delete-self-poc](https://github.com/LloydLabs/delete-self-poc) ⭐ 621 | 🐛 0 | 🌐 C | 📅 2025-11-05 : A way to delete a locked file, or current running executable, on disk.
* [Wipedicks](https://github.com/Drewsif/wipedicks) ⭐ 138 | 🐛 1 | 🌐 Python | 📅 2019-11-25 : Wipe files and drives securely with randoms ASCII dicks.
* [wiper](https://github.com/r3nt0n/wiper) ⭐ 78 | 🐛 2 | 🌐 Python | 📅 2023-01-16 : Toolkit to perform secure destruction of sensitive virtual data, temporary files and swap memories.
* [Nuke My LUKS](https://github.com/juliocesarfort/nukemyluks) ⭐ 53 | 🐛 0 | 🌐 Python | 📅 2016-08-31 : Network panic button designed to overwrite with random data the LUKS header of computers in a LAN.
* [Wipe](https://github.com/berke/wipe) ⭐ 51 | 🐛 8 | 🌐 C | 📅 2022-12-23 : A Unix tool for secure deletion.
* [Permanent-Eraser](https://github.com/edenwaith/Permanent-Eraser) ⭐ 23 | 🐛 3 | 🌐 C | 📅 2021-09-11 : Secure file erasing utility for macOS.
* [ChainSaw](https://github.com/Inffinite/ChainSaw) : ChainSaw automates the process of shredding log files and bash history from a system. It is a tool that cleans up the bloody mess you left behind when you went for a stroll behind enemy lines.
* [Clear-EventLog](https://learn.microsoft.com/powershell/module/microsoft.powershell.management/clear-eventlog?view=powershell-5.1) : Powershell Command. Clears all entries from specified event logs on the local or remote computers.
* [DBAN](https://sourceforge.net/projects/dban/) : Darik's Boot and Nuke ("DBAN") is a self-contained boot image that securely wipes the hard disks of most computers. DBAN is appropriate for bulk or emergency data destruction.
* [Hdparm](https://doc.ubuntu-fr.org/hdparm) : get/set hard disk parameters.
* [LogKiller](https://github.com/Rizer0/Log-killer) : Clear all your logs in linux/windows servers.
* [Shred](https://doc.ubuntu-fr.org/shred) : Overwrite a file to hide its contents, and optionally delete it.
* [Srm](https://sourceforge.net/projects/srm/) : Srm is a command-line compatible rm which overwrites file contents before unlinking.

### Password and Login

* [lazagne](https://github.com/AlessandroZ/LaZagne) ⭐ 10,953 | 🐛 17 | 🌐 Python | 📅 2025-09-18 : An open source application used to retrieve lots of passwords stored on a local computer.
* [Mimipenguin](https://github.com/huntergregal/mimipenguin) ⭐ 4,153 | 🐛 6 | 🌐 C | 📅 2025-09-05 : A tool to dump the login password from the current linux user.
* [chntpw](https://doc.ubuntu-fr.org/tutoriel/chntpw) : Offline NT Password Editor - reset passwords in a Windows NT SAM user database file.

### Encryption / Obfuscation

* [panic\_bcast](https://github.com/niklasfemerstrand/panic_bcast) ⭐ 225 | 🐛 3 | 🌐 Python | 📅 2021-11-10 : Decentralized opsec panic button operating over UDP broadcasts and HTTP. Provides automatic ejection of encrypted drives as a safe-measure against cold-boot attacks.
* [Midgetpack](https://github.com/arisada/midgetpack) ⭐ 210 | 🐛 6 | 🌐 C | 📅 2014-07-29 : Midgetpack is a multiplatform secure ELF packer.
* [ELFcrypt](https://github.com/droberson/ELFcrypt) ⭐ 130 | 🐛 1 | 🌐 C | 📅 2020-09-10 : ELF crypter.
* [Sherlocked](https://github.com/elfmaster/sherlocked) ⭐ 105 | 🐛 1 | 🌐 Objective-C | 📅 2014-10-30 : Universal script packer-- transforms any type of script into a protected ELF executable, encrypted with anti-debugging.
  * [suicideCrypt](https://github.com/MonolithInd/suicideCrypt) ⭐ 13 | 🐛 0 | 🌐 Perl | 📅 2017-12-03 : A toolset for creating cryptographically strong volumes that destroy themselves upon tampering (event) or via issued command.
* [BurnEye](https://github.com/packz/binary-encryption/tree/master/binary-encryption/burneye-stripped) ⭐ 71 | 🐛 0 | 🌐 C | 📅 2012-05-11 : ELF encryption program.
* [Tchunt-ng](https://github.com/antagon/TCHunt-ng) ⭐ 54 | 🐛 4 | 🌐 C | 📅 2018-11-09 : Reveal encrypted files stored on a filesystem.
* [TrueHunter](https://github.com/adoreste/truehunter) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2021-05-15 : Detect TrueCrypt containers using a fast and memory efficient approach.
* [cryptsetup](https://gitlab.com/cryptsetup/cryptsetup) : Utility used to conveniently set up disk encryption based
  on the DMCrypt kernel module.
  * [cryptsetup-nuke-password](https://salsa.debian.org/pkg-security-team/cryptsetup-nuke-password) : Configure a special "nuke password" that
    can be used to destroy the encryption keys required to unlock the encrypted partitions.
* [FreeOTFE](https://sourceforge.net/projects/freeotfe.mirror/) : A free "on-the-fly" transparent disk encryption program for PC & PDAs.

### Policies / Logging (Event) / Monitoring

* [python-evtx](https://github.com/williballenthin/python-evtx) ⭐ 777 | 🐛 24 | 🌐 Python | 📅 2026-03-19 : A tool to parse the Windows XML Event Log (EVTX) format.
* [Lfle](https://github.com/williballenthin/LfLe) ⭐ 26 | 🐛 1 | 🌐 Python | 📅 2015-10-09 : Recover event log entries from an image by heurisitically looking for record structures.
* [evtkit](https://github.com/yarox24/evtkit) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2016-03-29 : Fix acquired .evt - Windows Event Log files (Forensics) \[windows]
* [Grokevt](https://github.com/ecbftw/grokevt) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2024-07-12 : A collection of scripts built for reading Windows® NT/2K/XP/2K eventlog files. \[windows]
* [Auditpol](https://docs.microsoft.com/en-gb/windows-server/administration/windows-commands/auditpol) : Displays information about and performs functions to manipulate audit policies in Windows.
* [USBGuard](https://usbguard.github.io/) : Software framework for implementing USB device authorization policies (what kind of USB devices are authorized) as well as method of use policies (how a USB device may interact with the system).
* [wecutil](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/wecutil) : Enables you to create and manage subscriptions to events that are forwarded from remote computers. The remote computer must support the WS-Management protocol. \[windows]
* [Wevtutil](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/wevtutil) : Enables you to retrieve information about event logs and publishers. You can also use this command to install and uninstall event manifests, to run queries, and to export, archive, and clear logs (windows server).

### Steganography

* [StegCloak](https://github.com/KuroLabs/stegcloak) ⭐ 3,865 | 🐛 15 | 🌐 JavaScript | 📅 2024-10-01 : Hide secrets with invisible characters in plain text securely using passwords.
* [stego-toolkit](https://github.com/DominicBreuker/stego-toolkit) ⭐ 2,685 | 🐛 17 | 🌐 Shell | 📅 2022-11-27 : This project is a Docker image useful for solving Steganography challenges as those you can find at CTF platforms.
* [tweetable-polyglot-png](https://github.com/DavidBuchanan314/tweetable-polyglot-png) ⭐ 2,606 | 🐛 2 | 🌐 Python | 📅 2021-08-11 : Pack up to 3MB of data into a tweetable PNG polyglot file.
* [Cloakify](https://github.com/TryCatchHCF/Cloakify) ⭐ 1,680 | 🐛 8 | 🌐 Python | 📅 2020-11-24 : Transforms any filetype into a list of harmless-looking strings. This lets you hide the file in plain sight, and transfer the file without triggering alerts.
* [Stegify](https://github.com/DimitarPetrov/stegify) ⭐ 1,267 | 🐛 2 | 🌐 Go | 📅 2023-04-11 : Go tool for LSB steganography, capable of hiding any file within an image.
* [steganography](https://github.com/7thSamurai/steganography) ⭐ 1,083 | 🐛 1 | 🌐 C++ | 📅 2024-05-10 : Simple C++ Image Steganography tool to encrypt and hide files insde images using Least-Significant-Bit encoding.
* [StegaStamp](https://github.com/tancik/StegaStamp) ⭐ 876 | 🐛 36 | 🌐 Python | 📅 2023-12-08 : Invisible Hyperlinks in Physical Photographs.
* [Steganography](https://github.com/ragibson/Steganography) ⭐ 660 | 🐛 0 | 🌐 Python | 📅 2025-10-10 : Least Significant Bit Steganography for bitmap images (.bmp and .png), WAV sound files, and byte sequences.
* [PacketWhisper](https://github.com/TryCatchHCF/PacketWhisper) ⭐ 653 | 🐛 4 | 🌐 Python | 📅 2021-06-03 : Stealthily exfiltrate data and defeat attribution using DNS queries and text-based steganography.
* [Jsteg](https://github.com/lukechampine/jsteg) ⭐ 645 | 🐛 0 | 🌐 Go | 📅 2023-05-11 : jsteg is a package for hiding data inside jpeg files.
* [Stegdetect](https://github.com/abeluck/stegdetect) ⚠️ Archived : Automated tool for detecting steganographic content in images.
* [StegoVeritas](https://github.com/bannsec/stegoVeritas) ⭐ 411 | 🐛 7 | 🌐 Python | 📅 2026-04-10 : Yet another Stego Tool.
* [steg86](https://github.com/woodruffw/steg86) ⭐ 324 | 🐛 5 | 🌐 Rust | 📅 2026-08-10 : Format-agnostic steganographic tool for x86 and AMD64 binaries. You can use it to hide information in compiled programs, regardless of executable format (PE, ELF, Mach-O, raw, \&c).
* [AudioStego](https://github.com/danielcardeenas/AudioStego) ⭐ 299 | 🐛 5 | 🌐 C++ | 📅 2023-05-26 : Hides text or files inside audio files and retrieve them automatically.
* [Stego](https://github.com/ajmwagar/stego) ⭐ 274 | 🐛 11 | 🌐 Rust | 📅 2022-06-06 : stego is a steganographic swiss army knife.
  * [StegoGAN](https://github.com/DAI-Lab/SteganoGAN) ⭐ 392 | 🐛 35 | 🌐 Python | 📅 2023-03-23 : A tool for creating steganographic images using adversarial training.
* [ChessSteg](https://github.com/jes/chess-steg) ⭐ 93 | 🐛 2 | 🌐 JavaScript | 📅 2021-08-22 : Steganography in chess games.
* [StegFS](https://github.com/albinoloverats/stegfs) ⭐ 26 | 🐛 0 | 🌐 C | 📅 2026-03-02 : A FUSE based steganographic file system.
* [Mp3nema](https://github.com/enferex/mp3nema) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2013-07-01 : A tool aimed at analyzing and capturing data that is hidden between frames in an MP3 file or stream, otherwise noted as "out of band" data.
* [Steghide](http://steghide.sourceforge.net/) : Steganography program that is able to hide data in various kinds of image- and audio-files.

### Malware / AV

* [MalwareDetect](https://github.com/rfxn/linux-malware-detect) ⭐ 1,487 | 🐛 13 | 🌐 Shell | 📅 2026-05-24 : Submits a file's SHA1 sum to VirusTotal to determine whether it is a known piece of malware.
* [Malheur](https://github.com/rieck/malheur) ⭐ 375 | 🐛 1 | 🌐 C | 📅 2019-05-08 : A tool for the automatic analyze of malware behavior.

### OS/VM

* [HiddenVM](https://github.com/aforensics/HiddenVM) ⭐ 2,675 | 🐛 21 | 🌐 Shell | 📅 2024-07-18 : Use any desktop OS without leaving a trace.
* [Tails](https://tails.boum.org/index.en.html) : portable operating system that protects against surveillance and censorship.

### Hardware

* [USB Kill](https://github.com/hephaest0s/usbkill) ⭐ 4,621 | 🐛 34 | 🌐 Python | 📅 2024-03-01 : Anti-forensic kill-switch that waits for a change on your USB ports and then immediately shuts down your computer.
* [Day Tripper](https://github.com/dekuNukem/daytripper) ⭐ 4,038 | 🐛 6 | 🌐 C | 📅 2026-01-04 : Hide-My-Windows Laser Tripwire.
* [Silk Guardian](https://github.com/NateBrune/silk-guardian) ⭐ 723 | 🐛 8 | 🌐 C | 📅 2024-02-05 : Anti-forensic kill-switch that waits for a change on your usb ports and then wipes your ram, deletes precious files, and turns off your computer.
* [DoNotDisturb](https://github.com/objective-see/DoNotDisturb) ⭐ 329 | 🐛 30 | 🌐 Objective-C | 📅 2026-06-01 : Security tool for macOS that aims to detect unauthorized physical access to your laptop.
* [BusKill](https://github.com/BusKill/buskill-app) ⭐ 308 | 🐛 59 | 🌐 Python | 📅 2026-07-19 : BusKill is an hardware and software project that uses a hardware tripwire/dead-man-switch to trigger a computer to lock or shutdown if the user is physically separated from their machine.
* [USB Death](https://github.com/trpt/usbdeath) ⭐ 130 | 🐛 1 | 🌐 Shell | 📅 2017-06-12 : Anti-forensic tool that writes udev rules for known usb devices and do some things at unknown usb insertion or specific usb device removal.
* [xxUSBSentinel](https://github.com/thereisnotime/xxUSBSentinel) ⭐ 71 | 🐛 22 | 🌐 Rust | 📅 2026-08-03 : Windows anti-forensics USB monitoring tool.

### Android App

* [Lockup](https://github.com/levlesec/lockup) ⭐ 351 | 🐛 1 | 🌐 Java | 📅 2024-06-22 : A proof-of-concept Android application to detect and defeat some of the Cellebrite UFED forensic toolkit extraction techniques.
* [Ripple](https://github.com/guardianproject/ripple) ⭐ 292 | 🐛 17 | 🌐 Java | 📅 2026-04-17 : A "panic button" app for triggering a "ripple effect" across apps that are set up to respond to panic events.

## Contributing

Thanks for visiting ! If you have suggestions, then open an issue, or submit a PR. Contributions are welcome, and much appreciated !

## License

[![License](https://img.shields.io/badge/LICENSE-CC_BY_4.0-00a2ff)](https://creativecommons.org/licenses/by/4.0/)
Licensed under Creative Commons, CC BY 4.0, © [HUGUET Rémi @shadawck](https://github.com/shadawck) 2022

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
