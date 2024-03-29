# Installation
Um das Tool nutzen zu können muss im Browser das AddOn Tampermonkey installiert werden. Für die Desktop Version sollte unter https://www.tampermonkey.net das entsprechende AddOn zu finden sein. Für Smartphones gibt es  [hier](https://chrunos.com/tampermonkey-scripts-for-mobile/) eine Anleitung zur Installation
**! zur Zeit funktioniert das Tool unter iOS noch nicht, ich arbeite aber daran !**

Um das Tool selber zu installieren [hier](https://github.com/BenniBaerenstark/DG-Tool/raw/main/main.user.js) klicken. Weiter dann auf "Installieren" oder "Update" klicken.
[![](https://cdn.discordapp.com/attachments/768588157780230184/1168268077377540199/image.png?ex=6551256f&is=653eb06f&hm=ad0c06ca7c61e50f4705e96851b7d365c89b0c7d0b2d59f5c5c06b2f96cc15bb&)](https://cdn.discordapp.com/attachments/768588157780230184/1168268077377540199/image.png?ex=6551256f&is=653eb06f&hm=ad0c06ca7c61e50f4705e96851b7d365c89b0c7d0b2d59f5c5c06b2f96cc15bb&)
# Funktionen
## Einstellungen
Über das XWars Menü kann die Seite "Tool" geöffnet werden. Darüber können folgende Einstellungen gemacht werden:
- Die Standartkoordinate für Savehandel kann festgelegt werden. Wir das nicht gemacht wählt das Tool automatisch einen Planeten in deinem Besitz aus.
- Funktionen des Tool können ein-/ausgeschalten werden.
- Koordinaten können mit Kommentaren eingetragen werden. Die sind beim Handelstellen unter den eigenen Koordinaten auswählbar.
<picture>
  <img src="https://cdn.discordapp.com/attachments/768588157780230184/1168265401763901470/image.png?ex=655122f1&is=653eadf1&hm=a03f7c3baaf342d191e1e62afe950ae25e2583b7982a37b7089a5b1322c63143&">
</picture>

## Handel
### Handelsangebot stellen
- Savehandel können mit einem Klick ausgefüllt werden => die Savehandel mit „#SAVE#“ markiert, werden auf dem gestellten Planet nicht mehr angezeigt.
- Mit dem Gebäude-Formular können Kosten für Gebäude nachgeschaut werden und dann gesaved oder gefordert werden. „Fordern + „ ergänzt noch die Kosten für den Handel, so dass nach dem Handel die Ress auch gesaved werden können.
- Mit dem Schiffe-Formular können die Kosten für Schiffe direkt in den Handel eingetragen werden. Das Angebot der  Schiffe werden nach Bedarf von Admins ergänzt/aktuallisiert
- unter den Tool Einstellungen können eigene Koordinaten eingetragen werden 
<picture>
  <img src="https://cdn.discordapp.com/attachments/1129020455924269116/1129031948887670894/image.png">
</picture>

### Transaktionen
 - Es wird eine Übersicht über alle Savehandel angezeigt. Gezählt werden alle Handel die mit „#SAVE#“ markiert sind. Weiter werden alle markierten Savehandel  auf dem gestellten Planeten nicht angzeigt.
 - Eingehende Handel werden als Summe dargestellt. Dabei wird die Ressource orange markiert, wenn die Lagerkapazität 90% erreicht hat. Wir die Lagerkapaztät überschritten wird der Hintergrund rot. Die Rohstoffe auf dem Planeten selber werden dabei nicht berücksichtigt

<picture>
  <img src="https://cdn.discordapp.com/attachments/642751065766232065/1154739499847389214/image.png?ex=654e1276&is=653b9d76&hm=de90e043f4dc18cf1af494ee98fb8c58dd18f2ea8f2816a719510d97a80673ec&">
</picture>

### Handel kategorisieren
Handel werden nach Typ farblich markiert. Weiter werden alle unnötigen Informationen ausgeblendet und ein Countdown ergänzt.
- Laufende Handel sind dunkelgrau markiert
- Spenden/Schiffkäufe werden blau markiert (ausgehende dunkelblau/eingehende hellblau)
- Forderungen werden violett markiert (ausgehende dunkelviolett/eingehende hellviolett)
- Savehandel mit über 2h Laufzeit werden grün markiert, unter 2h orange und unter 30min rot.

<picture>
  <img src="https://cdn.discordapp.com/attachments/1129020455924269116/1143630012646428772/image.png?ex=654a91f2&is=65381cf2&hm=e5c6293dc67d63d936692ab44448a35ee223491cab2e64b5c0c6d1df45d0d05a&">
</picture>

### Handel Loggen
**NUR** für die Pushaccounts gibt es die Möglichkeit alle Handel zu tracken und in eine Datenbank einzutragen. 
##Flotten
### Flotten kategorisieren
Fliegende Flotten werden nach Mission farblich markiert:

|Farbe   | Mission |
| ------------ | ------------ |
|  rot | Angriff |
| grün | Verteidiung |
| schwarz | Transport  |
| blau | Überstellen |
| grau | Rückkehr |

### Einbindung Observerlink
Wenn ein Observer beim Angreiffer/Angegriffenen vorhanden ist, wird der Direktlink im Flottenmenu angezeit. Damit das Tool die Informationen bekomment muss zuvor die Observerseite besucht werden.
<picture>
  <img src="https://cdn.discordapp.com/attachments/1129020455924269116/1131981916313231380/image.png?ex=654e5650&is=653be150&hm=0e63da4afbf26c5170d0f55dbed777ab77112eea0977847739e557975bda9740&">
</picture>

### Raumdock
- Im Raumdock gibt es einen neuen Button "alle Schiffe", der die maximale Anzahl aller verfügbarer Schiffe einträgt ( ACHUTUNG noch nicht mit Träger geteset!) Weiter kann auf die Nummer der maximal verfügbaren Schffe pro Klasse geklickt werden um die Maximalzahl der Schiffe dieser Klasse einzutragen.
<picture>
  <img src="https://cdn.discordapp.com/attachments/1129020455924269116/1132119300791074896/image.png?ex=654ed643&is=653c6143&hm=f63f78b8ccd54df19678cb8f30f5d862a9c77568ac16b3c65213c950a0a7bed9&">
</picture>

## Bank
- Standardmäßig ist der Übertragungstyp auf "Resourcen übermitteln" eingestellt.
- Die maximale Lagermenge abzüglich aktuellem Zins wird in Klammer neben der Max. Lagerkapazität angezeigt.
- Ist der Übertragungstyp auf übermitteln eingestellt, wird mit dem Klick auf den Ressourcennamen die maximale Anzahl an Rohstoffen übermittelt, bis die Bank die maximale Lagerkapazität erreicht hat (das beinhaltet auch schon laufende Einzahlungen).
- Ist der Übertragungstyp auf abbuchen eingestellt, kann ebenfalls mit dem Klick auf die Ressourcennamen so viel Rohstoffe abgebucht werden, damit die maximale Kontostand abzüglich Zins wieder erreicht ist.
## Sprachen
Das Tool ist ins englische und französiche übersetzt und übernimmt die Spracheinstellungen im Browsers

