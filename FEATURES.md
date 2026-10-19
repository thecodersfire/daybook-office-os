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
