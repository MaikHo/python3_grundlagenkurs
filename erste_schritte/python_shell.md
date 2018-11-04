
# Python als Taschenrechner

Es gibt mehrere Möglichkeiten, Python zu verwenden. Im Editor **Anaconda Spyder** findest Du rechts unten die interaktive *Python-Shell*.


### Aufgabe 1

In diesem Abschnitt werden wir zuerst die Python-Shell als Taschenrechner ausprobieren. Du solltest folgende Eingabeaufforderung sehen:

    In [1]:

Führe einige Berechnungen in Python durch, indem Du die fehlenden Zeichen in die Lücken einsetzt:

    In [1]: 1 + ___
    Out[1]: 3

    In [2]: 12 ___ 8
    Out[2]: 4

    In [3]: ___ * 5
    Out[3]: 20

    In [4]: 21 / 7
    Out[4]: ___

    In [5]: ___ ** 2
    Out[5]: 81

Gib die Befehle ein und schau was passiert. Gib den ersten Teil (`In [1]` etc.) **nicht** ein, diese erscheinen automatisch.


### Aufgabe 2

Was ist der Unterschied zwischen folgenden Anweisungen?

    10 / 3
    10.0 / 3
    10.0 / 3.0
    10 // 3

<!--
    <question multiple>
        <p>Markiere alle korrekten Aussagen:</p>
        <answer correct>Alle Anweisungen sind Divisionen</answer>
        <answer correct>Der Operator <code>/</code> ergibt immer eine Gleitkommazahl</answer>
        <answer>Der Operator <code>//</code> rundet auf oder ab</answer>
        <explanation>Die "Floor-Division" (<code>//</code>) rundet 
        stets ab, unter Python 3 ist das Ergebnis der gewöhnlichen Division eine Kommazahl.</explanation>
    </question>
!-->

### Aufgabe 3

Welche Operationen ergeben 8?

    0 + 8
    4 4
    65 // 8
    17 % 9
    2 * * 4
    64 ** 0.5    

----

## Variablen

### Aufgabe 4

Um Zahlen und Rechenergebnisse für spätere Berechnungen aufzuheben, können wir sie in **Variablen** speichern.

Ergänze die Lücken:

    In [1]: emily = 25952
    In [2]: hannah = 23073
    In [3]: sarah = 5
    In [4]: emily
    Out[4]: ______
    In [5]: hannah + 1
    Out[5]: ______
    In [6]: 3 * sarah
    Out[6]: ______

### Aufgabe 5

Ändere den Inhalt der Variablen:

    In [7]: emily = emily + 1
    In [8]: emily
    Out[8]: _____

    In [9]: summe = _____ + _____ + _____
    In [10]: summe
    Out[10]: 49031

Setze die korrekten Werte und Variablennamen ein.


### Aufgabe 6

Probiere aus, ob folgende Variablennamen in Python erlaubt sind:

    YODA
    darth vader
    luke99
    2000imperator
    óbi_wan_kenobi
    darth.maul


### Aufgabe 7

Welche Zuweisungen an Variablen sind korrekt?
        <answer correct><code>a = 1 * 2</code></answer>
        <answer correct><code>2 = 1 + 1</code></answer>
        <answer><code>5 + 6 = y</code></answer>
        <answer correct><code>sieben = 3 * 4</code></answer>
        <explanation>Der Zuweisungsoperator (=) arbeitet immer von rechts nach links.</explanation>
    </question>
</quiz>


### Aufgabe 8

Führe folgende Befehle aus:

    import math

    math.log(16, 2)
    math.sin(math.pi / 2)

<quiz name="">
    <question multiple>
        <p>Markiere alle korrekten Aussagen:</p>
        <answer correct>Die Funktion <code>sin()</code> arbeitet mit Winkeln im Bogenmaß</answer>
        <answer>Das Ergebnis des Logarithmus ist <code>2</code></answer>
        <answer>Die <code>import</code>-Anweisung könnte man auch weglassen</answer>
        <answer correct>Die math-Bibliothek enthält eine Funktion <code>sqrt()</code> zum Wurzeln ziehen.</answer>
        <explanation>Mehr zum Modul math findest Du auf <a href="https://docs.python.org/3/library/math.html" target="_blank">docs.python.org/3/library/math.html</a></explanation>
    </question>
</quiz>
