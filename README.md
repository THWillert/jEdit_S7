# jEdit_S7


## Übersicht

Siemens Step 7 Edit-Mode-AWL und passende Erweiterung für die Plugins Xinsert und Ctags.

![jEdit_S7](/images/jEdit_S7.png)


## Voraussetzungen

**Folgende jEdit-Plugins:**
- XInsert
- SideKick
- CtagsSideKick

**Und zusätzlich:**
- [Universal-Ctags](https://github.com/universal-ctags) (empfohlen)
- oder [Ctags](http://ctags.sourceforge.net/) (nicht mehr weiterentwickelt - letzte Version von 2009)

##  Installation (Windows)

### Edit-Mode

(ToDo)

### Ctags

Das Programm selbst in installieren:

`%ProgramFiles%\ctags\`

Die ctags.cnf evtl. mit schon vorhander Datei kombinieren:
```
--langdef=S7
--langmap=S7:.s7.S7.AWL.awl
--regex-S7=/^[ \t]*TITLE[ \t]+=(.*?)/\1/Title/i
```
oder nach kopieren:

`%ProgramFiles%\jEdit\ctags.cnf`

Im jEdit-Plugin "CtagsSideKick" den Pfad zu Ctags einstellen - Angabe inklusive *.exe!

![jEdit_S7](/images/CtagsSideKick.png)


## ToDo

- [ ] Readme kompletieren
- [ ] Englische Übersetzung


## Author
Thorsten Willert

[Homepage](http://www.thorsten-willert.de/)

## Lizenz
Das ganze steht unter der [Apache 2.0](https://github.com/THWillert/HomeMatic_CSS/blob/master/LICENSE) Lizenz.
.

