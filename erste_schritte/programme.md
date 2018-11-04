
# Programme in Python schreiben

Mit IPython Anweisungen zu schreiben ist eine Zeitlang ganz nett. Komplexere Programme Befehl für Befehl zu schreiben ist aber auf die Dauer recht beschwerlich. Um wirklich sinnvoll programmieren zu können, müssen wir unsere Anweisungen in **Programmen** speichern, so dass wir sie später beliebig oft **ausführen** können.

Ein Programm besteht aus mehreren Zeilen, die in einem Rutsch ausgeführt werden.

In diesem Abschnitt wirst Du Dein erstes Python-Programm schreiben.


### Aufgabe 1

Öffne einen Texteditor (also *keine IPython-Konsole*) und erstelle eine leere Datei. Schreibe hinein: 

    import turtle

    turtle.forward(100)
    turtle.left(50)
    turtle.forward(100)

Speichere die Datei anschließend unter dem Namen `grafik.py` ab.

### Aufgabe 2

Nun kannst Du das Programm ausführen.

* Unter **Anaconda** drückst Du dazu den *"Play"*-Knopf oder `F5`.
* Mit einer **Kommandozeile** wechselst Du in das Verzeichnis mit der Datei `ausgabe.py` und schreibst:

    python3 ausgabe.py


### Aufgabe 3

Erkläre das folgende Programm:

    import turtle

    strecke = 100
    turtle.forward(strecke)
    turtle.left(90)
    strecke = strecke - 50
    print(strecke)
    turtle.forward(strecke)


### Aufgabe 4

Zeichne ein Quadrat:

![](square.svg)


### Aufgabe 5

Zeichne ein Dreieck:

![](triangle.svg)


### Aufgabe 6

Zeichne das Haus vom Nikolaus. Eine Wurzel kannst Du mit dem Modul `math` berechnen:

    import math

    vier = math.sqrt(16)

![](nikohaus.svg)


# Eingabe von der Tastatur

Nun werden wir die Tastatur als Eingabemedium an unser Programm anschließen.

### Aufgabe 7

Was tut das folgende Programm?

    name = input("Wie heißt Du? ")
    print(name)


### Aufgabe 8

Welche `input`-Befehle sind korrekt?

* `a = input()`
* `a = input("gib eine Zahl ein.")` 
* `a = input(gib Deinen Namen ein)`
* `a = input(3)`


### Aufgabe 9

Schreibe ein Programm, bei dem der Nutzer die Größe des gezeichneten Quadrats einstellen kann. Du kannst eine Zahl mit folgendem Befehl einlesen:

    zahl = int(input("Gib eine Zahl ein: "))
    print(zahl)


### Aufgabe 10

Welche `print`-Anweisungen sind korrekt?

* `print("9" + "9")`
* `print "neun"`
* `print(str(9) + "neun")`
* `print(9 + 9)`
* `print(neun)`
