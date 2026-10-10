<!-- markdownlint-disable MD013 -->
# Software-Alternativen: Open-Source & faire Software

Dies ist eine kuratierte Liste mit vorwiegend Open-Source-Software sowie ausgewählten, fairen Bezahlalternativen zu proprietärer und SaaS-Software.

> [!NOTE]
> Diese Liste erhebt keinen Anspruch auf Vollständigkeit, sondern enthält eine bewusst ausgewählte bzw. mir bekannte Sammlung empfehlenswerter Alternativen.

> [!IMPORTANT]
> Manche Beschreibungen enthalten meine persönliche Einschätzung. Diese dient zur Orientierung und stellt keine Wertung dar. Nutzt was ihr wollt, mögt oder kennt.

## Linux Distros

Es soll in dieser Übersicht zwar primär um Software-Alternativen zu proprietärer- und SaaS-Software gehen, aber genau da darf eigentlich eine Übersicht zu Alternativen zu MS Windows ebenfalls nicht fehlen.

* Umfangreiche Übersicht über [alle möglichen Linux Distributionen](https://distrowatch.com/dwres.php?resource=popularity) inkl. Beliebtheitsranking
* Interessantes [Projekt](https://www.linuxfromscratch.org/lfs/) für versierte Linux-Anwender

| Link | Beschreibung |
| :--- | :--- |
| [Fedora](https://fedoraproject.org/de/) | Stabil, aktueller Linux-Kernel, gute Software-Pakete |
| [openSUSE](https://www.opensuse.org/de/) | Tumbleweed gilt als stabilstes Rolling-Release, hervorragende KDE-Integration, standardmässig Systembackups |
| [Ubuntu](https://ubuntu.com/download) | Klassischer Allrounder mit grosser Community |
| [Linux Mint](https://linuxmint.com/) | Einsteigerfreundliche Linux Distribution |
| [ZorinOS](https://zorin.com/) | Speziell für Einsteiger und Umsteiger von Windows |
| [PikaOS](https://wiki.pika-os.com/de/home) | Gaming optimiert, Benutzerfreundlich und hohe Kompatibilität |
| [CachyOS](https://cachyos.org/) | Extrem auf Performance und Gaming optimiert (basiert auf Arch) |
| [Bazzite](https://bazzite.gg/) | Performance und Gaming-Optimiert, basiert auf Fedora, Immutable (isoliertes Kernsystem, daher fast unzerstörbar) |
| [Fedora SILVERBLUE](https://fedoraproject.org/atomic-desktops/silverblue/) | Atomic-System (ähnlich Bazzite) aber eher auf Workstation getrimmt |
| [Debian](https://www.debian.org/index.de.html) | Klassische, extrem robuste Basis für Server und erfahrene Anwender |
| [MX Linux](https://mxlinux.org/) | Auf Debian-Stable basierend, effiziente Desktops mit hoher Stabilität und solider Leistung |
| [Arch](https://archlinux.org/) | Minimalistische Rolling-Release-Distro - nur für erfahrene Benutzer! |
| [NixOS](https://nixos.org/) | Reproduzierbares, deklaratives und zuverlässiges Linux-System - nur für erfahrene Benutzer! |
| [Void](https://voidlinux.org/) | Void Linux hebt sich als komplett unabhängige Distribution durch seine radikale Minimalisierung ab, die mittels des blitzschnellen Paketmanagers XBPS und des systemd-Alternative init-Systems runit maximale Kontrolle und Performance garantiert ([Anleitung](https://www.youtube.com/watch?v=kkXXWAGegUo)). |
| [Alpine](https://www.alpinelinux.org/about/) | Sicherheitsorientierte, leichtgewichtige Linux-Distribution - eher für erfahrene Benutzer |
| [EndeavourOS](https://endeavouros.com/) | Leichtgewichtige, auf Arch basierende, terminalzentrierte Distro |
| [Manjaro](https://manjaro.org/) | Etwas umstrittene Distro auf Arch-Basis, komfortablere Einrichtung und Installation als Arch, mit exzellenter Gaming-Performance |
| [Pop!_OS](https://system76.com/pop) | Auf Basis von Ubuntu-LTS, vom Hardware-Hersteller System76, COSMIC-Desktop noch eher unausgereift |

### Spezielle Linux- bzw. Linux-ähnliche Betriebssysteme

| Link | Beschreibung |
| :--- | :--- |
| [ParrotOS](https://parrotsec.org/) | Spezielle Linux-Distro für Pentesting und Hacking |
| [Kali Linux](https://www.kali.org/) | Ebenfalls eine spezielle Linux-Distro für Pentesting und Hacking |
| [Solus](https://getsol.us/) | Anfängerfreundliches, unabhängiges, ausergewöhnlich stabiles und sehr schnelles Linux mit Budgie-Desktop |
| [Haiku](https://www.haiku-os.org/) | Von BeOS inspiriertes Open-Source-Betriebssystem, schnell, bedienerfreundlich und leistungsstark |
| [RedoxOS](https://www.redox-os.org/) | Unix-ähnliches, in Rust geschriebenes und auf Sicherheit und Zuverlässigkeit ausgelegtes OS (alternative zu Linux und BSD) |
| [FreeBSD](https://www.freebsd.org/) | Populärste BSD-Version, sehr gute Hardwareunterstützung (Funfact: OS von Sony Playstation basiert auf FreeBSD) |
| [OpenBSD](https://www.openbsd.org/) | Die Sicherheits-Festung! OpenBSD wurde speziell dafür geschaffen, das sicherste Betriebssystem zu sein |

## VMs

| Link | Beschreibung |
| :--- | :--- |
| [QEMU](https://www.qemu.org/) | Virtualisierung und Hardwareemulation |
| [Virt-Manager](https://virt-manager.org/) | Desktop UI für VMs |
| [Boxen](https://apps.gnome.org/de/Boxes/) | GNOME App zur Virtualisierung |
| [Oracle VirtualBox](https://www.virtualbox.org/) | Virtualisierungssoftware von Oracle |
| [UTM](https://mac.getutm.app/) | Virtualisierungssoftware speziell für MacOS |

### Containervirtualisierung

| Link | Beschreibung |
| :--- | :--- |
| [Docker](https://www.docker.com/) | Isolierung von Anwendungen durch Containervirtualisierung |
| [Podman](https://podman.io/) | Höhere Sicherheit und weniger Verbrauch von Systemressourcen im Vergleich zu Docker |

## IDEs (Editoren)

| Link | Beschreibung |
| :--- | :--- |
| [VS Code](https://code.visualstudio.com/) | MS Visual Studio Code |
| [VS Codium](https://vscodium.com/) | Visual Studio Code (ohne MS Telemetrie) |
| [Kate](https://kate-editor.org/de/) | KDE Editor Kate |
| [Zed](https://zed.dev/) | Zed Editor (schlanker, guter Editor mit Vim Modus) |
| [Rider](https://www.jetbrains.com/de-de/rider/) | .NET und Game Dev IDE |
| [nano](https://www.nano-editor.org/) | GNU nano Editor (bei den meisten Linux Distro's vorinstalliert) |
| [GNU Emacs](https://www.gnu.org/savannah-checkouts/gnu/emacs/emacs.html) | Erweiterbarer, Anpassbarer mächtiger Texteditor |
| [Neovim](https://neovim.io/) | Vim-basierter Texteditor |
| [Vim](https://www.vim.org/) | Gut konfigurierbarer Texteditor |

### Entwicklung

| Link | Beschreibung |
| :--- | :--- |
| [Git](https://git-scm.com/) | Von Linus Torvalds entwickeltes Versionskontrollsystem |

## Videobearbeitung

| Link | Beschreibung |
| :--- | :--- |
| [KDEnlive](https://kdenlive.org/de/) | Non-linearer Video Editor von KDE |
| [FilmCraft](https://github.com/storytold/filmcraft) | Rust Video Editor ähnlich wie Adobe Premiere |
| [Lightworks](https://lwks.com/) | Kostenpflichtiger Video Editor mit kostenloser Version |
| [DaVinci Resolve](https://www.blackmagicdesign.com/de/products/davinciresolve/studio) | Profesioneller Video Editor mit kostenloser Version |
| [HandBrake](https://handbrake.fr/) | Videokonverter zum Umwandeln von Videos in fast jedes Format |

### Videoaufnahmen und Live-Streaming

| Link | Beschreibung |
| :--- | :--- |
| [OBS](https://obsproject.com/de) | Bekannteste App für Live-Streaming und Desktopaufnahmen |

### Videowiedergabe

| Link | Beschreibung |
| :--- | :--- |
| [VLC](https://www.videolan.org/vlc/index.html) | Bekanntester Media-Player |
| [mpv](https://mpv.io/) | Alternative zu VLC (weniger Anwenderfreundlich aber top Bildqualität, schnell und mittels Skripts erweiterbar) |

## Videoeffekte und 3D Animation

| Link | Beschreibung |
| :--- | :--- |
| [Fusion](https://www.blackmagicdesign.com/de/products/fusion) | Vom Hersteller von DaVinci Resolve |
| [Natron](https://natrongithub.github.io/) | Open Source Visual Effect Editor |
| [Blender](https://www.blender.org/) | Blender eben |

## Audiobearbeitung

| Link | Beschreibung |
| :--- | :--- |
| [Audacity](https://www.audacityteam.org/) | Die wohl beliebteste Audiobearbeitungs- und Aufnahme-App |
| [Tenacity](https://tenacityaudio.org/) | Alternative (Klon) zu *Audacity* aber ohne die Telemetrie und Datensammlung von *Audacity* |
| [Ardour](https://ardour.org/) | Vollwertige Digital Audio Workstation (DAW) und sehr mächtig |
| [LMMS](https://lmms.io/) | Musik produzieren, Beats bauen oder mit Synthesizern arbeiten (ähnlich wie FL Studio aber zum Schneiden von Sprachaufnahmen eher ungeeignet) |
| [Mixxx](https://mixxx.org/) | Open-Source-Software speziell für DJs (Live-Mixe mit digitalen Musikdateien) |
| [FL-Studio](https://www.image-line.com/) | Nicht kostenlos, aber ohne Abo mit Einmalkauf oder Abzahlung |

## Kreativ-Suite

| Link | Beschreibung |
| :--- | :--- |
| [Affinity](https://www.affinity.studio/de_de) | Alternative zu Adobe CC |

## Desktop-Publishing (DTP)

| Link | Beschreibung |
| :--- | :--- |
| [Scribus](https://www.scribus.net/) | Open-Source-Software für DTP (vergleichbar mit Adobe InDesign) |

## Vektorgrafik

| Link | Beschreibung |
| :--- | :--- |
| [InkScape](https://inkscape.org/) | Vektorgrafiken erstellen und bearbeiten (vergleichbar mit Adobe Illustrator) |
| [Graphite](https://github.com/GraphiteEditor/Graphite) | Open Source Vektorgrafikprogramm |
| [Vectorpea](https://www.vectorpea.com/) | Online Vektorgrafiken bearbeiten |

## Fotografie-Workflow

| Link | Beschreibung |
| :--- | :--- |
| [Darktable](https://www.darktable.org/) | RAW Fotodateien bearbeiten und organisieren (vergleichbar mit Adobe Lightroom) |
| [RapidRAW](https://www.getrapidraw.com/) | RAW Fotodateien bearbeiten - [Beispiel](https://www.youtube.com/watch?v=fsmdNyxFcrM) (ebenfalls vergleichbar mit Adobe Lightroom) |
| [RAW Therapee](https://rawtherapee.com/) | RAW Bildverarbeitungsprogramm |
| [eagle](https://eagle.cool/) | Bilddateien organisieren |

## Bildbearbeitung, Zeichnen & malen

| Link | Beschreibung |
| :--- | :--- |
| [Gimp](https://www.gimp.org/) | **Der** Adobe Photoshop Ersatz |
| [Pinta](https://www.pinta-project.com/) | Open Source Zeichnen und Bildbearbeitung |
| [Krita](https://krita.org/de/) | Digital zeichnen und malen (ebenfalls Open Source) |
| [Photopea](https://www.photopea.com/) | Online Fotobearbeitungsprogramm (ähnlich wie Adobe Photoshop) |

## Dokumentenbetrachter (PDF, Comic, EPub)

| Link | Beschreibung |
| :--- | :--- |
| [Okular](https://okular.kde.org/de/) | Universeller Dokumentenbetrachter (vergleichbar mit Adobe Acrobat) |
| [Libre Office Draw](https://de.libreoffice.org/discover/draw/) | Texte und Grafiken in PDF's bearbeiten inkl. digitaler Signaturen |
| [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) | Open Source PDF's bearbeiten |

## 2D- und 3D-CAD

| Link | Beschreibung |
| :--- | :--- |
| [LibreCAD](https://librecad.org/) | Open Source 2D-CAD (Installation Fedora `sudo dnf install librecad`) |
| [QCAD](https://www.qcad.org/de/) | Open Source 2D-CAD |
| [FreeCAD](https://www.freecad.org/) | Parametrisch 3D-Modellieren (Installation Fedora `sudo dnf install freecad`) |
| [Onshape](https://www.onshape.com/de/) | Online-3D-CAD von PTC (**Achtung**: öffentliche Speicherung bei der kostenlosen Version) |

## Office-Anwendungen

| Link | Beschreibung |
| :--- | :--- |
| [LibreOffice](https://de.libreoffice.org/) | MS Office Ersatz |
| [OpenOffice](https://www.openoffice.org/de/) | Weiterer MS Office Ersatz (wird aber kaum noch gepflegt) |
| [kova.md](https://kova.md/) | Präsentationen mittels Markdown Dateien (alternative zu MS PowerPoint) |
| [Wire](https://wire.com/de/) | Sicherer Open Source Ersatz für MS Teams |
| [Nextcloud Talk](https://nextcloud.com/de/talk/) | Für kleine Teams kostenlos (Ersatz für MS Teams) |

## ToDo & Aufgabenplanung

| Link | Beschreibung |
| :--- | :--- |
| [Super Productivity](https://super-productivity.com/) | Aufgabenverwaltung (ToDo's) |
| [Vikunja](https://vikunja.io/) | Umfangreicher Aufgabenplaner |

## Email Clients

| Link | Beschreibung |
| :--- | :--- |
| [Thunderbird](https://www.thunderbird.net/de/) | Standard Email-Client (ähnlich wie MS Outlook) |
| [Geary](https://gitlab.gnome.org/GNOME/geary) | Open Source Email-Client |
| [Evolution](https://gitlab.gnome.org/GNOME/evolution) | Email-Client mit integriertem Kalender und Adressbuch |

## Notizen und Wissenssammlung

| Link | Beschreibung |
| :--- | :--- |
| [Obsidian](https://obsidian.md/) | Obsidian, mächtige Notizen-App mit vielen Plugins erweiterbar |
| [ZenNotes](https://zennotes.org/) | Ähnlich wie Obsidian |
| [HelixNotes](https://helixnotes.com/) | Ebenfalls mit Obsidian vergleichbar |
| [Notesnook](https://notesnook.com/) | Just Notes |
| [Logseq](https://github.com/logseq/logseq) | Wissensmanagement- und Kollaborationsplattform |
| [Joplin](https://joplinapp.org/de/) | Mit Notion vergleichbar aber Open Source |
| [Trilium](https://triliumnotes.org/) | Persönliche Wissensdatenbank |
| [Docmost](https://docmost.com/) | Lokales Wiki für Unternehmensteams |
| [Xournal++](https://xournalpp.github.io/) | Notizen-App für Handschriftliche Notizen |

### Forschungsassistent

| Link | Beschreibung |
| :--- | :--- |
| [Zotero](https://www.zotero.org/) | Spezielle Notizen-App - gut für Buchsammlungen und Recherchen für Studium und Beruf |

## E-Reader und Buchsammlung

| Link | Beschreibung |
| :--- | :--- |
| [Readest](https://readest.com/de) | Kostenloser, Quelloffener Reader für EPub und PDF's |
| [Calibre](https://calibre-ebook.com/) | Vermutlich der bekannteste EBook-Reader |

## Passwortmanager

| Link | Beschreibung |
| :--- | :--- |
| [ProtonPass](https://proton.me/de/pass) | Kostenloser Passwortmanager |
| [Bitwarden](https://bitwarden.com/) | Bekannter Passwortmaanger (kann mittels [Vaultwarden](https://github.com/dani-garcia/vaultwarden) privat selber gehosted werden) |
| [Passbolt](https://www.passbolt.com/) | Open Source Passwortmanager |
| [Psono](https://psono.com/de) | Selbstgehosteter Open Source Passwortmanager |
| [KeePassXC](https://keepassxc.org/) | Bekannter lokaler Passwortmanager |
| [Pass](https://www.passwordstore.org/) | Standard "Unix" Passwortmanager (TUI - [Anleitung](https://ryan.himmelwright.net/post/setting-up-pass/)) |

### Sicherheit & Privatsphäre

| Link | Beschreibung |
| :--- | :--- |
| [VeraCrypt](https://veracrypt.io/en/Home.html) | Vollständige Verschlüsselung von Festplatten, Partitionen oder USB-Sticks |
| [Kleopatra](https://apps.kde.org/de/kleopatra/) | Visuelles Kontrollzentrum für E-Mail- und Dateiverschlüsselung (OpenPGP) |
| [Signal](https://signal.org/de/) | Krypto-Messenger für Smartphones und PCs für sichere Kommunikation |

## Systemtools

| Link | Beschreibung |
| :--- | :--- |
| [GParted](https://gparted.org/) | Bekanntes Werkzeug zu Festplatten- und Partitionsverwaltung |

## Cloud & Filesharing

| Link | Beschreibung |
| :--- | :--- |
| [ProtonDrive](https://proton.me/de/drive) | 5 GB kostenloser Cloudspeicher |
| [Filen](https://filen.io/) | 10 GB kostenloser Cloudspeicher |
| [pCloud](https://www.pcloud.com/de) | Bis zu 10 GB kostenloser Cloudspeicher |
| [Nextcloud](https://nextcloud.com/de/) | Die Cloud-Lösung zum selber hosten |
| [qBittorrent](https://www.qbittorrent.org/) | Schlanker und werbefreier BitTorrent-Client |

## Fernzugriff und Support

| Link | Beschreibung |
| :--- | :--- |
| [RustDesk](https://rustdesk.com/de/) | Gute alternative zu TeamViewer |

## Dateien teilen

| Link | Beschreibung |
| :--- | :--- |
| [LocalSend](https://localsend.org/de) | Dateien schnell, sicher und einfach von jedem Gerät aus teilen |

## Beleuchtungssteuerung

| Link | Beschreibung |
| :--- | :--- |
| [OpenRGB](https://openrgb.org/) | Beleuchtung von PC, RAM, GraKa und Peripherie steuern und synchronisieren |

## Gruppenchat und Community

| Link | Beschreibung |
| :--- | :--- |
| [Fluxer](https://fluxer.app/) | Alternative zu Discord |
| [Stoat](https://stoat.chat/) | Ebenfall eine Community-Alternative zu Discord |
| [Nerimity](https://nerimity.com/) | Elegante und moderne Chat-App (ähnlich wie Discord) |
| [GameVox](https://gamevox.com/de/) | Noch eine alternative zu Discord |
| [matrix](https://matrix.org/) | Offenes Netzwerk für sichere, dezentrale Kommunikation |
| [Teamspeak 6](https://www.teamspeak.com/de/downloads/) | Aktuellste und stark überarbeitete Version von Teamspeak |

## Webbrowser

| Link | Beschreibung |
| :--- | :--- |
| [Mulvad](https://mullvad.net/en/browser) | Maximum an Sicherheit, Privatsphäre und Datenschutz |
| [LibreWolf](https://librewolf.net/) | Firefox Unterbau aber in sicher |
| [Helium](https://helium.computer/) | Bessere und saubere alternative zu Brave |
| [Zen-Browser](https://zen-browser.app/) | Visuell ansprechender Browser mit relativ gutem Datenschutz |
| [Firefox](https://www.firefox.com/de/) | Standardeinstellungen eher schlecht, nach Eingriffen ganz okay |
| [Chromium](https://github.com/ungoogled-software/ungoogled-chromium) | Ungoogled-Chromium Browser |
| [Brave](https://brave.com/de/) | Inzwischen zu viel Bloat (KI, Krypto, VPN-Werbung, Telemetrie) |
| [Vivaldi](https://vivaldi.com/de/) | Viel Bloat, nicht optimal für Anonymitätspuristen (Fingerprinting) |
| [Opera](https://www.opera.com/de/download) | Absolute Datenkrake - nicht empfehlenswert |
| [Google Chrome](https://www.google.com/intl/de/chrome/) | Google Datensammler |
