# Built-in features for daybook-office-os

Purpose: everyday office work

1. **prepare study and research files** — run daybook-office-os-workspace. It creates ~/Documents/daybook-office-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run daybook-office-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/daybook-office-os-session-plans/.
3. **check study and source readiness** — run daybook-office-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/daybook-office-os-workspace features/daybook-office-os-plan features/daybook-office-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for everyday office work:

1. **KeePassXC** — org.keepassxc.KeePassXC
2. **VSCodium** — com.vscodium.codium
3. **GIMP** — org.gimp.GIMP

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for everyday office work:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
3. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
4. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
5. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
8. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
9. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
