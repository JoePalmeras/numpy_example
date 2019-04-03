Install 'pip':
--------------

python -m pip install -U pip

Create 'requirements.txt' with 'pipreqs':
-----------------------------------------

pipreqs G:\...\...\...\Tutorial_1			//Beispielpfad

Erzeuge mit 'virtualenv' ein Ordner für Virtuelle Maschiene:
------------------------------------------------------------

virtualenv env		// Ordner mit Name 'env' wird erzeugt in der sich die Virtuelle Maschiene befindet

Virtuelle Maschiene starten/activieren:
---------------------------------------

env\Scripts\activate

Abhängigkeiten aus 'requirements.txt' installieren:
---------------------------------------------------

pip install -r requirements.txt


Virtuelle Maschiene beenden/deactivieren:
---------------------------------------

env\Scripts\deactivate