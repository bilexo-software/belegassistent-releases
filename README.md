# Belegassistent

Ordnet Ihre Kontoauszüge automatisch den passenden Rechnungen aus dem
Gmail-Postfach zu — für Windows.

**[→ Neueste Version herunterladen](https://github.com/bilexo-software/belegassistent-releases/releases/latest)**

## Was das Programm macht

1. **Kontoauszug einlesen** — CSV-Export aus dem Online-Banking hochladen.
   Zeichensatz, Trennzeichen und Spalten werden erkannt; doppelt importierte
   Zeiträume erkennt das Programm und überspringt sie.
2. **Rechnung suchen** — zu jeder Abbuchung wird das Gmail-Postfach nach der
   passenden Rechnung durchsucht, einzeln oder als Sammellauf über alle offenen
   Buchungen. Betrag, Rechnungsdatum und Rechnungsnummer werden aus den
   PDF-Anhängen ausgelesen.
3. **Prüfen und übernehmen** — jeder Vorschlag zeigt, warum er vorgeschlagen
   wird. Erst ein Klick legt die Rechnung ab, nach Jahr sortiert.
4. **Weitergeben** — bestätigte Belege landen zusätzlich in einem
   Übergabeordner für **DATEV Unternehmen online** (Belegtransfer wird direkt
   unterstützt). Eine CSV-Liste aller Zuordnungen gibt es auf Knopfdruck.

Die Zuordnung ist immer ein **Vorschlag, keine Prüfung** — ohne Ihren Klick
wird nichts abgelegt.

## Ihre Daten bleiben bei Ihnen

Das Programm arbeitet **lokal auf Ihrem Rechner**. Belege, Zugangsdaten und die
Datenbank verlassen ihn nicht; es gibt kein Nutzerkonto beim Hersteller.

Der Gmail-Zugriff ist auf **Lesen beschränkt** (`gmail.readonly`) — das
Programm kann Ihre E-Mails weder ändern noch verschicken. Die Verbindung
richten Sie selbst über Ihr eigenes Google-Konto ein; die Anleitung dazu steht
im Programm unter *Einstellungen*.

Beim Start wird höchstens einmal täglich bei GitHub nachgefragt, ob eine neuere
Fassung vorliegt. Dabei werden **keine** Daten über Sie oder Ihre Buchungen
übertragen. Abschaltbar unter *Einstellungen → Programmfassung*.

## Testen und kaufen

Nach der Installation läuft das Programm **7 Tage lang mit vollem
Funktionsumfang**. Die Testphase beginnt, sobald Sie sich zum ersten Mal mit
Gmail verbinden.

Danach ist das Suchen und Zuordnen gesperrt, bis ein Lizenzschlüssel eingetragen
ist. Bereits abgelegte Rechnungen und importierte Buchungen bleiben
selbstverständlich erhalten und einsehbar.

Den Schlüssel tragen Sie im Programm unter *Lizenz* ein.

## Installation

1. `Belegassistent-Setup-x.y.z.exe` von der
   [Release-Seite](https://github.com/bilexo-software/belegassistent-releases/releases/latest)
   herunterladen und ausführen.
2. Administratorrechte sind nicht erforderlich.

> **Hinweis zur Windows-Warnung:** Das Programm ist noch nicht mit einem
> kostenpflichtigen Zertifikat signiert. Windows zeigt deshalb beim ersten Start
> „Der Computer wurde durch Windows geschützt". Über *Weitere Informationen →
> Trotzdem ausführen* lässt sich die Installation fortsetzen.

## Updates

Das Programm meldet sich, wenn hier eine neuere Fassung erscheint, und verlinkt
den Download. **Eingespielt wird von Hand** über den Installer: einfach die
neue Fassung über die vorhandene installieren. Ihre Daten bleiben dabei
erhalten.

## Was das Programm nicht kann

- **Rechnungen ohne PDF-Anhang** werden nicht gefunden. Manche Anbieter
  verschicken nur einen Link ins Kundenportal — solche Buchungen müssen Sie von
  Hand ablegen.
- **Gescannte Rechnungen ohne Textebene** liefern keinen Betrag.
- **Sammelbuchungen** (eine Abbuchung für mehrere Rechnungen) bekommen nur eine
  Rechnung zugeordnet.

## Systemvoraussetzungen

Windows 10 oder 11 (64 Bit), rund 300 MB freier Speicherplatz, ein
Gmail-Postfach.

## Support

Fragen zur Lizenz oder zur Anwendung: bitte an den Hersteller wenden.

---

*Dieses Repository enthält nur die Installationsdateien und den Update-Kanal.
Der Quelltext ist nicht öffentlich.*
