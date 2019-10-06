*Kaufmann Jan 3AHIF*
### Project Proposal
## Idee
Den aktuellen Stundenplan für einen Schüler oder einer Klasse auf einer Smartwatch mit Tizen OS abrufen können.

## Auftraggeber
Dieses Projekt wird in SYP bearbeitet werden somit ist die Lehrkraft der Auftraggeber.

## Sinn 
Vereinfachung des Herausfindens des Stundenplan für den aktuellen Tag. Um zum Beispiel: In Bus oder Bahn nicht das Smartphone aus dem Rucksack hervorkrammen zu müssen sondern einfach und bequem die Uhr am Handgelenk zu überprüfen.

## Mögliche Umsetzung
Mithilfe dieser "Überarbeitung" der originalen Web Untis API gennant [**python webuntis**](https://github.com/python-webuntis/python-webuntis) kann man auf den Stundenplan des angemeldeten Schülers oder aller Klassen aufrufen und um HTML Format anzeigen. Der Grund warum ich diese API anstatt der Originalen benutzen möchte ist, dass die ursprüngliche sehr kompliziert ist. Zur Eigentlichen Programmierung wird die IDE "**Tizen Studio**" benutzt.

Es gibt zwei Weg zur weiteren Umsetzung:
1. Es gibt eine Hauptapp die am Smartphone läuft und die Konfiguration und das Abrufen der Inhalte übernimmt und diese dann, in einem konfigurierbaren Abstand erneuert und an die Smartwatch schickt.

2. Eine reine Watchapplication die, sofern mit dem Smartphone verbunden, die Internetanbindung des Telefons benutzt um die Daten in einem konfigurierbaren Abstand zu erneuern.