# LB 324
Link zu meiner App: https://arnellislb-324.azurewebsites.net/

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.

### Schritt 1
Pip installieren, falls nötig:
https://pip.pypa.io/en/stable/installation/

### Schritt 2
Öffnen Sie das Projektverzeichnis in Visual Studio Code und öffnen Sie dort ein neues Terminal.

### Schritt 3
Installieren Sie pre-commit mit diesm Befehl:
`pip install pre-commit`

### Schritt 4
Erstellen Sie eine `.pre-commit-config.yaml`-Konfigurationsdatei im Projektverzeichnis.

### Schritt 5
Führen Sie folgenden Befehl aus:
`pre-commit install`

### Schritt 6
Um pre-commit zu testen, führen Sie folgenden Befehl aus:
`pre-commit run --all-files`


## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

In Azure auf der Web-App muss man auf "Konfiguration" klicken.
![Screenshot (10)](https://github.com/EllisArn/ArnEllisLB-324/assets/89130718/a581ea4d-c69a-472a-a21b-309afd3aa327)

Dann auf "Neue Anwendungseinstellung".
![Screenshot (11)](https://github.com/EllisArn/ArnEllisLB-324/assets/89130718/cea47db2-0c94-4c75-95bb-64e25bb99448)

Dann muss man bei "Name" den Namen des env-Felds eingeben (bei mir "PASSWORD") und bei "Wert" muss man dessen Wert eingeben (bei mir "hallihallo").
![Screenshot (12)](https://github.com/EllisArn/ArnEllisLB-324/assets/89130718/f243bbfe-d172-4025-a6e2-c80bb5808af1)
