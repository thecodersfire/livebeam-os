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
