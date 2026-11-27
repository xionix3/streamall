# Streamall

## Downloads

| Plattform | Aktuelle Version |
| --- | --- |
| Windows | [Installer (.msi)](https://github.com/xionix3/streamall/releases/latest/download/streamall-windows.msi) |
| Android und Android TV | [App (.apk)](https://github.com/xionix3/streamall/releases/latest/download/streamall-android.apk) |
| Enigma2 (SF8008) | [IPK-Installer (.ipk)](https://github.com/xionix3/streamall/releases/latest/download/streamall-enigma2-sf8008.ipk) |
| Linux | [Debian/Ubuntu (.deb)](https://github.com/xionix3/streamall/releases/latest/download/streamall-linux.deb) · [Fedora/openSUSE (.rpm)](https://github.com/xionix3/streamall/releases/latest/download/streamall-linux.rpm) |
| Optionale Portale | [Portalpakete und Installation](https://github.com/xionix3/streamall-addon#installation) |

[Alle Versionen und Prüfsummen](https://github.com/xionix3/streamall/releases)

## Bedienung

Die Ansicht lässt sich oben zwischen **Liste** und **Kacheln** wechseln. Vavoo bietet eine **Piconansicht** und zeigt verfügbare Senderlogos auch in der Liste. Die Auswahl bleibt für jedes Portal gespeichert. In den Einstellungen lässt sich die **Startansicht pro Portal** festlegen.

Im Windows- und Linux-Player schalten die Vollbildtaste, **F** und **F11** in den Vollbildmodus. **Esc** kehrt zum Fenster zurück. Auf Desktop und Android lassen sich unter **Einstellungen → Sprachfilter** Tonsprachen und Untertitel auswählen. Die Filter verwenden die Sprachangaben der jeweiligen Quellen.

## Installation und Updates

Installiere zuerst Streamall für dein Gerät. Die App prüft beim Start, ob es eine neuere Version gibt. Windows startet den Installer, Android und Android TV verwenden den Systemdialog. Falls ein alter Windows-Build beim Update `java/net/http/HttpClient` meldet, einmal den aktuellen MSI-Installer oben herunterladen und ausführen. Auf Enigma2 wird das Update über die App angeboten. Linux öffnet den Systeminstaller. Für die Wiedergabe unter Linux wird libmpv benötigt. Für das Linux-Portalpaket wird Python 3.11 bis 3.15 benötigt.

Das optionale Portalpaket hat einen eigenen Update-Kanal. Auf Enigma2 wird es als separates IPK installiert. In Android und Desktop findest du es oben beim **S → Portale verwalten**.

Unter **Einstellungen → Synchronisierung** kann ein eigener Streamall-Sync-Server über HTTPS verbunden werden. Synchronisiert werden Favoriten und Wiedergabepositionen. Auf Enigma2 findest du die Synchronisierung über **MENU** in den Streamall-Einstellungen.

Hier liegen die Beschreibung und die fertigen App-Pakete. Entwicklung und Builds laufen im internen Repository.
