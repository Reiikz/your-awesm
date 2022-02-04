---
name: Bug Report
about: Create a report to help us improve
title: Concise bug description, Ex; "Can't find steam on Manjaro Linux"
labels: ''
assignees: Reiikz

---

Rules for reporting issues;
Replace every line with the answer to what is asked on that line weather you think it's relevant or not.
Extra information is appreciated.
Not following the rules may or may not result in your issue being dismissed.

OS and OS version
Shell the script is running on
Shell version

Installation source of steamcmd (tar.gz from valve, Debian repo package, etc) (if it's not being used specify it as such)
Did you use force_install_dir? (yes, no)
Internet connection speed (steamcmd is known to fail on slow ones, contracted speed is not valid please mesure it with speedtest.net)
Starbound installation location.
Specify weather you're using the starbound dedicated server or the starbound official client
If the script setup with systemd please provide the unit file, if not please specify it as a standalone install.
If the script has been setup with a different service manager specify so, if not remove this line.

Steps to reproduce the behavior, ex:
1. run star-server update <modpack url> --cp

**Expected behavior; ex:**
It downloads the mods and copies them to the mods folder

**Actual behaviour; ex:**
It downloads the mods but instead of coping them as files it creates symbolic links

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Additional context**
Add any other context about the problem here.
