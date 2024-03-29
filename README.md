# This repository has been moved to https://git.reiikz.net/reiikz/your-awesm

## What is it?

YOUR-AWESM is a BASH written and tested (may run on other POSIX compliant shells, feel free to request compatibility).

YOUR-AWESM takes care of launching/stopping a starbound server within a screen, with the added bonus of being able to install modpacks directly from a steam workshop link and also through individually specified steam workshop content id's, and through the combination of YOUR-AWESM with cron and systemd you can set up an auto update enabled server that starts up with the OS.

Target system: Debian Stable, feel free to ask for compatibility updates.

### how to use it?

try to read the manual instead, it's updated more often than the wiki and has virtually the same content ;) or... 
[check the wiki](https://github.com/Reiikz/your-awesm/wiki)

### What works:
* starting and stopping starbound through the script and systemd
* updating mods from a modpack URL
* updating mdos from the command line through content ids
* Multi server support; the ability to manage multiple server profiles at once each with their own unique modpack
* Auto generates unit files to set it up as a system service
* logs to a file when doing certain tasks like updating
* Standar manual page for star-server

### What is planned:
* Client support for all profiling features
* Profiling support; the ability to have multiple modpacks/map combinations for one server
* API that spits out the player list a json format
* Automatic starbound log backup
* Log processing for error detection and playercount reporting

### What's been deprecated:
* the script will no longer support foreign users to manage other user's servers, stopping and starting will still be accessible through systemd, but support for other operations through sudo overrides will be dropped, in the future you'll have to explicitely specify to run the script as that particular user through the use of an external command like sudo.
