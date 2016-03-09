# Secure Shell

Secure Shell oder SSH bezeichnet sowohl ein Netzwerkprotokoll als auch entsprechende Programme, mit deren Hilfe man auf eine sichere Art und Weise eine verschlüsselte Netzwerkverbindung mit einem entfernten Gerät herstellen kann. Häufig wird diese Methode verwendet, um lokal eine entfernte Kommandozeile verfügbar zu machen, das heißt, auf einer lokalen Konsole werden die Ausgaben der entfernten Konsole ausgegeben und die lokalen Tastatureingaben werden an den entfernten Rechner gesendet.
<br>[[Von Wikipedia](https://de.wikipedia.org/wiki/Secure_Shell)]

## Clients

### Linux

Mit dem Befehl `ssh` über das Terminal.

Genauer:

1. Das Programm _Terminal_ öffnen
2. Befehl für eine SSH-Verbindung: `ssh benutzer@host`
   <br>Für `host` die entsprechende IP einsetzen
3. Passwort eingeben

### Windows

- Software: [PuTTY](https://wiki.ubuntuusers.de/PuTTY/)
- Dokumentation: [Using SSH/SCP on Windows](http://ged.msu.edu/angus/tutorials/using-putty-on-windows.html)

## Dateitransfer

### Linux

Mit dem Befehl `scp` über das Terminal.

Genauer:

1. Das Programm _Terminal_ öffnen
2. Befehl:
   <br>Lokal -> Server: `scp quelldatei benutzer@host:zielverzeichnis`
   <br>Server -> Lokal: `scp benutzer@host:quelldatei zielverzeichnis`
3. Passwort eingeben

### Windows

- Software: [WinSCP](https://winscp.net/eng/index.php)
- Dokumentation: [Using SSH/SCP on Windows](http://ged.msu.edu/angus/tutorials/using-putty-on-windows.html)

## Siehe auch

- [Umgang mit der Kommandozeile](Linux_Komandozeile.md)
