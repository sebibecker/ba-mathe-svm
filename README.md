# Eine Support Vector Machine für den MNIST Datensatz

## Prerequisites

1. Bereits vorhandene Python Installation


## Installation/Anwendung

1. Herunterladen des besten Modells (best_modell.joblib) aus meiner Cloud. Ansonsten muss das Modell selber trainiert werden, was je nach Hardware aufwendig sein kann.

2. Einrichten einer neuen venv mit
```
python -m venv <name_der_venv>
```

Alternativ kann auch ein bereits bestehendes Environment genutzt werden. Es werden lediglich numpy, matplotlib und scikit-learn benötigt.

3. Installation der benötigten Module innerhalb des Environments mittels
```
pip install -r requirements.txt
```

4. Ausführen der relevanten Abschnitte im Jupyter Notebook


## Anmerkungen

- Das SVM Jupyter Notebook beinhaltet den in der Arbeit beschriebenen Aufbau inkl. Training der Modelle. Die ganze Ausführung des Notebooks kann daher dauern. Es empfiehlt sich einzelne Zellen zu testen oder einen leistungsfähigen PC zu verwenden.
- Das Graphics Jupyter Notebook ist lediglich für die Erzeugung der Grafiken in der Arbeit erstellt worden.
- Beim Trainieren der Modelle wird teilweise ein Parameter "n_jobs" verwendet. Durch das Setzen auf -1 werden alle CPU Cores in Anspruch genommen. Wenn auf dem 
PC noch andere Aufgaben während des Trainings durchgeführt werden soll, empfiehlt es sich diesen Wert auf einen Wert n zu setzen, wobei n die Anzahl der Kerne ist, die 
fürs Training verwendet werden dürfen.