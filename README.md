# Regelwerk

Zyklus-App fürs iPhone (läuft als Web-App auch auf jedem anderen Gerät). Daten bleiben auf dem Gerät.

- **Kalender & Vorhersagen:** Monatsansicht mit Periode, erwarteter Periode, fruchtbaren Tagen, geschätztem Eisprung
  und PMS-Phase. Oben eine Übersicht: Zyklustag, aktuelle Phase, nächste Periode, Eisprung und PMS-Beginn.
  Die Vorhersagen beruhen auf dem Durchschnitt der letzten 6 Zyklen; bis dahin gelten einstellbare Startwerte.
- **Tageseintrag:**
  - Blutung (keine, Schmierblutung, leicht, mittel, stark)
  - Symptome 0–10: Krämpfe, Kopf-, Rückenschmerzen, Brustspannen, Hautunreinheiten, Übelkeit, Durchfall, Blähungen, Heißhunger
  - Stimmung, Energie, Stress, Stimmungsschwankungen (0–10)
  - Zervixschleim, Sex (geschützt/ungeschützt), Schlaf (Dauer und Qualität), Sport (Minuten und Art), Gewicht,
    Medikamente und Notizen
- **Auswertung:** Zyklus- und Periodenlänge je Zyklus mit Durchschnitt und Regelmäßigkeit, Symptome nach Zyklustag als Heatmap.
- **Sicherung:** Export als `.json` (zum Wiederherstellen) und `.csv` (Excel/Numbers), Import mit Zusammenführen oder Ersetzen.

So wird gerechnet: Zyklustag 1 ist der erste Tag mit mindestens leichter Blutung (eine Schmierblutung davor zählt nicht
als Beginn). Eisprung ≈ nächste Periode − 14 Tage (Lutealphase, einstellbar), fruchtbar sind die 5 Tage davor bis
1 Tag danach, PMS die 5 Tage vor der Periode (einstellbar).

**Wichtig:** Alle Angaben sind Schätzungen – keine sichere Verhütung und kein Ersatz für ärztlichen Rat.

## Aufs iPhone

1. Settings → Pages → Branch `main`, Ordner `/ (root)` → Save. Die App ist dann unter
   https://maxwoess.github.io/Regelwerk/ erreichbar.
2. In Safari öffnen → **Teilen → Zum Home-Bildschirm**, ab dann immer über das Icon starten.

Regelmäßig unter **Sicherung** eine `.json`-Datei speichern (z. B. in iCloud Drive). Die App erinnert daran,
wenn die letzte Sicherung älter als 14 Tage ist.
