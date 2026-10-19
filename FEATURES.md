# Built-in features for livebeam-os

Purpose: live streaming

1. **prepare racing and game notes** — run livebeam-os-workspace. It creates ~/Documents/livebeam-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run livebeam-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/livebeam-os-session-plans/.
3. **check game and controller readiness** — run livebeam-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/livebeam-os-workspace features/livebeam-os-plan features/livebeam-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for live streaming:

1. **Kdenlive** — org.kde.kdenlive
2. **Ardour** — org.ardour.Ardour
3. **Inkscape** — org.inkscape.Inkscape

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for live streaming:

1. **Blender** — create 3D assets and animations (org.blender.Blender)
2. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
3. **GIMP** — edit raster graphics and textures (org.gimp.GIMP)
4. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
5. **GNOME Sound Recorder** — capture voice and field notes (org.gnome.SoundRecorder)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
4. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
5. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
6. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
12. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
13. **Flatseal** (com.github.tchx84.Flatseal) — review Flatpak app permissions.
14. **GNOME Calendar** (org.gnome.Calendar) — schedule sessions, deadlines, and events.
15. **GNOME Papers** (org.gnome.Papers) — read project and reference PDFs.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
