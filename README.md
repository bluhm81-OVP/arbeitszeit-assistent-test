Arbeitszeit-Assistent v0.13.0

- Texterkennung neu: Datum (gestern, 1. Oktober, am 01.10., Wochentag), Zeiten (sieben bis halb fünf), Ort (bekannte Orte aus früheren Einträgen + "in Ort") und Tätigkeit werden getrennt erkannt.
- Datum springt nicht mehr auf heute; Diktat überschreibt nie den zuletzt bearbeiteten Tag.
- Doppelte Einträge pro Datum werden abgefangen.
- Update-Problem behoben: Service Worker lädt neue Versionen jetzt zuerst aus dem Netz.

Alle Daten bleiben lokal im Browser. Regelmäßig JSON-Sicherung exportieren.
