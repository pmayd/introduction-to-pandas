# introduction-to-pandas

pandas ist ein Python-Paket, das schnelle, flexible und ausdrucksstarke Datenstrukturen bereitstellt, um die Arbeit mit "relationalen" oder "gelabelten" Daten einfach und intuitiv zu gestalten. pandas ist das zentrale Paket für die praktische, reale Datenanalyse in Python und ein unverzichtbares Werkzeug fürjeden, der mit tabellarischen Daten arbeiten möchte, egal ob Data Analyst, Data Scientist oder Tabellenliebhaber.

Die beiden primären Datenstrukturen von Pandas sind die Series (1-dimensional) und das DataFrame (2-dimensional). Sie eignen sich für die meisten typischen Anwendungsfälle im Finanzwesen, in der Statistik, in den Sozialwissenschaften und in vielen Bereichen der Technik. pandas baut auf NumPy auf und ist so konzipiert, dass es sich gut in eine wissenschaftliche Berechnungsumgebung mit vielen anderen Bibliotheken von Drittanbietern integrieren lässt.

Wir werden uns in diesem Workshop anschauen, was man mit pandas alles erreichen kann, u. a.:

- Einfache Handhabung von fehlenden Daten (dargestellt als NaN)
- Größenveränderlichkeit: Spalten können in DataFrame eingefügt und gelöscht werden
- Automatische und explizite Datenausrichtung: Objekte können explizit an einem Satz von Beschriftungen ausgerichtet werden
- Leistungsstarke, flexible Gruppierungsfunktionen zur Durchführung von Split-Apply-Combine-Operationen
- Intuitives Zusammenführen und Verbinden von Datensätzen
- Flexible Umformung und Pivotierung von Datensätzen
- Robuste IO-Tools zum Laden von Daten aus Flat Files (CSV und mit Trennzeichen), Excel-Dateien, Datenbanken und zum Speichern/Laden von Daten aus dem ultraschnellen HDF5-Format
- Zeitreihen-spezifische Funktionen: Generierung von Datumsbereichen und Frequenzkonvertierung, Statistiken für gleitende Fenster, Datumsverschiebung und Verzögerung

Von den Teilnehmer*innen werden Grundkenntnisse in Python vorausgesetzt. Eine Python Entwicklungsumgebung sollte vorab installiert sein, ich empfehle Miniconda. Den Teilnehmer*innen werden Jupyter Notebooks zur Verfügung gestellt, um dem Workshop live folgen zu können. Das Ziel des Workshops ist dabei bewusst offen formuliert und die Teilnehmer*innen dürfen sich an jedem Punkt mit eigenen Ideen einbringen.

## Resources

Repository: <https://github.com/pmayd/introduction-to-pandas>
Agenda: <https://devopenspace.de/>
Pandas Material: <https://github.com/tommyod/awesome-pandas>

## Setup

Lokales Setup: 

1. Miniconda installieren: <https://docs.conda.io/en/latest/miniconda.html>
2. Anaconda Prompt starten
3. `conda create -n pandas python=3.10`
4. `conda activate pandas`
5. Dieses Repository clonen oder downloaden
6. In das root Verzeichnis dieses Repositorys wechseln
7. `pip install -r requirements.txt`
8. `jupyter notebook` oder `jupyter lab`

Google Colab Setup (erfordert Google Konto):

1. Einfach nur diesem Link folgen: <https://colab.research.google.com/github/pmayd/introduction-to-pandas/>

Binder Setup:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pmayd/introduction-to-pandas/HEAD)