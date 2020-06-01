# About

This repository is for building a dockerized version of Irssi IRC Client with Blowfish cipher support to encrypt private and public messages in ECB and CBC modes. It also includes and Diffie-Hellman key exchange for private chat.

Blowfish support is integrated using the work of https://github.com/falsovsky/FiSH-irssi

# Install

`docker pull foretix/irssi-blowfish-docker:latest`

# Run

Is ran via Unraid, rightclick via webui to get into console and execute bash cmd as seen in dockerfile at the end.

Note: `/load fish` command is executed immediately on start, so there is no need to load fish extension manually.

# IRC commands for Blowfish

See readme at https://github.com/falsovsky/FiSH-irssi
