---
title: Lösung von Installationsproblemen
sidebar_position: 5
---

:::note

This article covers AdGuard for Mac, a multifunctional ad blocker that protects your device at the system level. To see how it works, [download the AdGuard app](https://adguard.com/download.html?auto=true)

:::

## Fehler „Installation fehlgeschlagen“ in macOS Catalina

Während der Installation kann ein Fehler wie dieser auftreten:

![Installationsfehlerbildschirm](https://cdn.adtidy.org/content/kb/ad_blocker/mac/macerrorscreenEN.jpg)

Folgen Sie dieser Anleitung, um das Problem zu lösen:

1. Restart your Mac
2. As your Mac restarts, press and hold down the *Command(⌘) + R* keys immediately upon hearing the startup chime. Halten Sie die Tasten gedrückt, bis das Apple-Logo erscheint, um den Computer in den Wiederherstellungsmodus zu versetzen.
3. From the top bar select *Utilities* → *Terminal*, and execute this command: `csrutil disable`
4. Restart the Mac and log into Administrator's profile
5. Open the Finder window and select from the top bar *Go* → *Go to Folder* and type `~/private/`
6. Create a folder named *tmp* and type in your password
7. Launch AdGuard installation

Wenn die Installation abgeschlossen ist, starten Sie Ihren Mac im Wiederherstellungsmodus mithilfe der obigen Anweisungen neu und führen Sie den Befehl `csrutil enable` im Terminal aus, um den Systemschutz zu aktivieren.
