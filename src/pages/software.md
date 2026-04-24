---
layout: ../layouts/Layout.astro
title: Software
currentPage: software
---

<img src="/images/snow_trees.jpg" alt="Snow in the trees" style="max-width: 320px; margin-bottom: 1.5rem;" />

## GitHub

My personal GitHub account is [here](http://github.com/vancleve).

## SOCKS proxy via SSH Tunnel

A simple Python script that creates an SSH tunnel and uses "networksetup" on Mac OS X
to create a SOCKS proxy using the tunnel. Run the script in a terminal window with a
command line option for the network interface (e.g. "Wi-Fi", "Ethernet"). Quit with
Control+C to end the tunnel. The script also resets your network settings if the SSH
tunnel closes due to loss of connectivity.

For Mac OS 10.8+, run as root (e.g., `sudo setproxy.py --off`) to avoid multiple
admin password dialogs.

- [setproxy.py](http://github.com/vancleve/setproxy)

## BibDesk

- [Fork of Zot2Bib](http://github.com/vancleve/Zot2Bib) — When Zotero downloads a
  reference and PDF, Zot2Bib transfers only the reference to BibDesk. This fork also
  attaches the PDF to the BibTeX entry.
- Perl script to toggle between full journal titles and abbreviations, plus AppleScripts
  to do this in BibDesk (similar to JabRef):
  - [Perl script](http://haldane.uky.edu/wordpress/wp-content/software/abbreviateJournalTitles.perl) for journal title abbreviation
  - [AppleScript](http://haldane.uky.edu/wordpress/wp-content/software/Toggle%20Journal%20Abbreviation.scpt) for toggling between full title, ISO abbreviation, and Medline abbreviation
  - [AppleScript](http://haldane.uky.edu/wordpress/wp-content/software/Pre%20Auto%20File.scpt) that abbreviates journal titles before using them in linked PDF filenames
  - [Sample list of journal abbreviations](http://haldane.uky.edu/wordpress/wp-content/software/additional_journal_abbrv.txt)
