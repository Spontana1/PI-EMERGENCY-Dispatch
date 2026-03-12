# PI-EMERGENCY-Dispatch

🚑 X-Plane Emergency System

<img width="2300" height="1183" alt="Screenshot 2026-03-11 214817" src="https://github.com/user-attachments/assets/f4239c18-a336-4f9b-a67c-71dcd304daf1" />




Ein erweitertes Einsatz- und Rettungssystem für X-Plane, das eine realistische Simulation von:

🚑 Rettungsdienst

🚓 Polizei

📡 Leitstelle / Dispatch

🧑‍⚕️ Patienten

🖥 medizinischem Monitoring

ermöglicht.

Das Plugin wurde für XPPython3 entwickelt und erweitert X-Plane um ein komplettes Einsatz- und Notfallsystem.

✨ Funktionen
🚑 Einsatzleitstelle (Dispatch)

Die integrierte Leitstelle ermöglicht das Alarmieren und Verwalten von Einsatzfahrzeugen.

Funktionen:

Alarmierung von Einsatzfahrzeugen

automatische Fahrzeugauswahl

Einsatzstart

Rückkehr zur Wache

Fahrzeuge löschen

Stationsbasierte Fahrzeugpositionen

🚓 Einsatzfahrzeuge

Unterstützte Fahrzeugtypen:

Fahrzeug	Beschreibung
RTW	Rettungswagen
POL	Polizeifahrzeug

Fahrzeugfunktionen:

Spawn an Stationen

automatische Einsatzfahrt

Navigation zum Einsatzort

Rückfahrt zur Wache

Verwaltung über Dispatch-UI

🧑‍⚕️ Patienten-Simulation

Das Plugin enthält eine Patient-KI, die medizinische Werte simuliert.

Simulierte Vitalwerte
Wert	Beschreibung
HR	Herzfrequenz
BP	Blutdruck
SpO₂	Sauerstoffsättigung
Shock Index	Kreislaufzustand
Blood Loss	Blutverlust

Die Werte reagieren dynamisch auf:

Zeitverlauf

Medikamente

Blutverlust

Behandlungsmaßnahmen

🖥 Patientenmonitor

Der integrierte Monitor zeigt medizinische Daten ähnlich wie ein echter Patientenmonitor.

Angezeigte Werte:

Herzfrequenz

Blutdruck

Sauerstoffsättigung

Schockindex

Blutverlust

Medikamentenstatus

💉 Medikamentensystem

Medikamente bleiben für eine definierte Zeit sichtbar.

Medikament	Sichtbarkeit
O₂	20 Sekunden
Volumen	30 Sekunden
Analgesie	20 Sekunden
Sedierung	20 Sekunden
🖥 Dispatch Interface

Die Dispatch-UI wird direkt in X-Plane angezeigt.

Funktionen:

Patient auswählen

Einsatz starten

Fahrzeuge senden

Fahrzeuge zurück zur Wache schicken

Fahrzeuge löschen

UI-Layout:

[ PATIENT ]   [ START ]

[SEND]   [RETURN]   [DELETE]
📦 Plugin-Struktur
PythonPlugins/

PI_EMER_Dispatch_UI_Window_V12_8.py
PI_EMER_Dispatch_VAR_V12.py
PI_EMER_Patient_AI_V4.py
Dateien
Dispatch UI
PI_EMER_Dispatch_UI_Window_V12_8.py

Steuert:

UI Fenster

Mausinteraktionen

Dispatch Buttons

Anzeige

Dispatch Backend
PI_EMER_Dispatch_VAR_V12.py

Steuert:

Fahrzeugverwaltung

Dispatchlogik

Stationsdaten

Fahrzeugnavigation

Patienten KI
PI_EMER_Patient_AI_V4.py

Steuert:

Vitalwerte

Medikamente

Schockindex

Monitoranzeige

⚙ Voraussetzungen

Entwicklung.
