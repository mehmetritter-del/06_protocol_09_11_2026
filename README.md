# Protokoll – 09.11.2026
### Protokolschreiber: Mehmet
## Thema des Tages
Wir haben While-Schleifen (while loops) kennengelernt, in Gruppenarbeit geübt und unsere Ergebnisse präsentiert. Danach haben wir eine Einführung in Functions bekommen, am Nachmittag die Theorie zu Functions in Gruppen bearbeitet und zum Schluss Functions besprochen.

## Tagesablauf
| Uhrzeit | Was haben wir gemacht? |
|---------|------------------------|
| 09:00 – 09:30 | Rückblick auf Freitag und Besprechung des Protokolls vom 06.11.2026 |
| 09:30 – 10:30 | While-Schleifen bearbeitet und kennengelernt |
| 10:30 – 10:45 | Pause |
| 10:45 – 12:00 | While-Schleifen-Übung in zwei Gruppen |
| 12:00 – 12:15 | Ergebnisse präsentiert |
| 12:15 – 13:00 | Einführung in Functions |
| 13:00 – 13:30 | Mittagspause |
| 13:30 – 16:30 | Theorie über Functions in Gruppen bearbeitet |
| 16:30 – 17:00 | Besprechung und Q&A über Functions |

## Was wir gemacht haben
- Wir haben Freitag wiederholt und das Protokoll vom 06.11.2026 gemeinsam besprochen
- Wir haben das Konzept der while-Schleife kennengelernt
- Wir haben in zwei Gruppen eine Übung zu while-Schleifen bearbeitet
- Wir haben unsere Ergebnisse aus der Gruppenübung präsentiert
- Wir haben eine Einführung in Functions bekommen (Introduction, Definition, Function definieren und aufrufen)
- Wir haben am Nachmittag die Theorie über Functions in Gruppen bearbeitet
- Wir haben zum Abschluss Functions besprochen und offene Fragen im Q&A geklärt

## Wichtige Befehle / Code

```python
number = 0
while number < 5:
   number += 1
   print(number)
```

**Ausgabe:**
```
1
2
3
4
5
```

**Die wichtigsten Befehle aus dem Beispiel:**

| Befehl | Was macht er? | Wofür ist er gut? |
|--------|---------------|-------------------|
| `number = 0` | Legt eine Variable mit dem Startwert 0 an | Die Schleife braucht einen Wert, den sie prüfen und verändern kann |
| `while number < 5:` | Wiederholt den eingerückten Code, solange die Bedingung wahr ist | Wenn man etwas mehrfach ausführen will, ohne den Code zu kopieren |
| `number += 1` | Erhöht `number` um 1 (Kurzform für `number = number + 1`) | Damit sich die Bedingung irgendwann ändert und die Schleife endet |
| `print(number)` | Gibt den aktuellen Wert auf dem Bildschirm aus | Um zu sehen, was in der Schleife passiert |
| Einrückung (3 Leerzeichen) | Zeigt, welcher Code zur Schleife gehört | Python erkennt den Schleifenkörper nur an der Einrückung |

## Was wir gelernt haben

**While-Schleifen:**
Eine while-Schleife wiederholt Code so lange, wie eine Bedingung wahr ist. Wir setzen sie ein, wenn wir vorher nicht wissen, wie oft etwas wiederholt werden muss, zum Beispiel bei einer Eingabe, die so lange abgefragt wird, bis sie stimmt. Wichtig: Die Variable in der Bedingung muss sich in der Schleife verändern (bei uns `number += 1`), sonst läuft die Schleife endlos.

**Functions:**
- **Introduction:** Eine Function ist ein benannter Codeblock, den wir einmal schreiben und danach beliebig oft verwenden können. Das spart Wiederholungen und macht den Code übersichtlicher.
- **Definition:** Wir legen eine Function mit `def` und einem Namen an. Dabei steht nur fest, was die Function tun soll, ausgeführt wird der Code dabei noch nicht.
- **Aufrufen (Calling):** Erst wenn wir die Function mit ihrem Namen aufrufen, läuft der Code in ihr ab. Aufrufen können wir sie so oft, wie wir wollen.

## Offene Fragen
- (Was war in der Gruppenübung noch unklar?)
- (Was war bei Functions noch unklar?)
