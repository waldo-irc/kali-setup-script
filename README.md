# kali-setup-script
This script is intended to get new VMs of Kali up and running for Pentesting and CTFS in no time.

Just download script and run!

-e argument for express install otherwise just ./kali-setup.sh to run basic install.  Requires an IRC client and multiplexer selection (possible selections include terminator/tmux for multiplexers and hexchat/irssi for IRC clients).  Add -d to the end for all defaults.
     EX: ./kali-setup.sh -e tmux irssi
     EX: ./kali-setup.sh -e tmux irssi -d (for all defaults)

-ex argument for express install without doing apt-get update/upgrade.  Requires an IRC client and multiplexer selection (possible selections include terminator/tmux for multiplexers and hexchat/irssi for IRC clients).  Add -d to the end for all defaults.
     EX: ./kali-setup.sh -ex terminator hexchat
     EX: ./kali-setup.sh -ex terminator hexchat -d (for all defaults)

The script must be run as root in order to create the proper directories and install the programs without issues.

DEFAULTS:
If defaults are used you will find the following settings to becomes defaults.

SLEEP:DISABLED

FTP USER:FTP
FTP PASSWORD: FTP

USER PASSWORD REMAINS UNCHANGED (KALI DEFAULT IS TOOR)
