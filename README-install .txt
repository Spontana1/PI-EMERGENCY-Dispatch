X-Plane 11/12 simHeaven roads_graph Builder
====================================================================================
1) (plugins\PythonPlugins\python-3.14.3-amd64.exe)
2) (plugins\PythonPlugins\build_simheaven_roads_graph.bat)

In plugins einfügen 
-PluginAdmin
-PythonPlugins
-XPPython3

In Custom Scenery einfügen
-PI_EMER_Incident_Scenery 

====================================================================================
Inhalt
- build_simheaven_roads_graph.py
- build_simheaven_roads_graph.bat
- install_python_and_run.bat
- README.txt

So benutzt du es
1. ZIP entpacken.
2. DSFTool.exe in denselben Ordner legen.
3. build_simheaven_roads_graph.bat starten.

Was automatisch passiert
- sucht X-Plane 11 oder X-Plane 12
- installiert Python automatisch, falls es fehlt
- startet den roads_graph Builder
- schreibt +XX+YYYroads_graph.json nach:
  Resources\plugins\PythonPlugins
- legt eine builder_run.log fuer Fehleranalyse an

Hinweise
- Die Python-Installation versucht nacheinander:
  1) py install 3.14
  2) winget install Python.Python.3.14
  3) offiziellen python.org Installer
- Fuer DSFTool ist weiterhin DSFTool.exe noetig.
- Bei XP12 werden X-World network Ordner erkannt.
- Bei XP11 werden typische simHeaven X-Europe/X-America Scenery/Roads Ordner mit erkannt.
====================================================================================
