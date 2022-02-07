## What is it?

YOUR-AWESM is a BASH written and tested (may run on other POSIX compliant shells, feel free to request compatibility).

YOUR-AWESM takes care of launching/stopping a starbound server within a screen, with the added bonus of being able to install modpacks directly from a steam workshop link and also through individually specified steam workshop content id's, and through the combination of YOUR-AWESM with cron and systemd you can set up an auto update enabled server that starts up with the OS.

Target system: Debian Stable, feel free to ask for compatibility updates.

### how to use it?

[check the wiki](https://github.com/Reiikz/your-awesm/wiki)

### What works:
* starting and stopping starbound through the script and systemd
* updating mods from a modpack URL
* updating mdos from the command line through content ids

### What is currently being worked on:
* Multi server support; the ability to manage multiple server profiles at once each with their own unique modpack

### What is planned:
* Profiling support; the ability to have multiple modpacks/map combinations for one server
* Standar manual page for star-server

### What's been deprecated:
* the script will no longer support foreign users to manage other user's servers, stopping and starting will still be accessible through systemd, but support for other operations through sudo overrides will be dropped, in the future you'll have to explicitely specify to run the script as that particular user through the use of an external command like sudo.
