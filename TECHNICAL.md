# AXIOMA – Technische Spezifikation (Kurzfassung)

## 1. Compute-Chronometer
Jede Sonde führt identische, deterministische Aufgaben aus:
- Hash-Ketten
- einfache Primtests
- feste Integer-Matrixoperationen
- speichergebundene Kopieroperationen

Ziel ist nicht Rechenleistung,
sondern Vergleichbarkeit der Prozessrate.

## 2. Messdaten
Zusätzlich erfasst jede Sonde:
- Temperatur
- Strahlung
- Energieverfügbarkeit
- Magnetische / elektrische Felder (optional)

Diese Daten dienen zur Normalisierung der Rechenergebnisse.

## 3. Output
Jede Sonde sendet:
- Task-ID
- Epoch-ID
- Ergebnis-Hash
- Metriken (z. B. Stabilität, Entropie)
- Signatur

## 4. Konsens
Mehrere Sonden bearbeiten dieselbe Aufgabe.
Ein Ergebnis gilt als stabil, wenn eine definierte Mehrheit übereinstimmt.

## 5. Aggregation
Ergebnisse werden zu Ortsvektoren zusammengeführt
und in einer Ereignisdichte-Karte abgelegt.
