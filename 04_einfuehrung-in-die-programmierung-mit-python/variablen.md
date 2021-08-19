# Variablen

## Variablen in Python

Damit wir Dinge nicht vergessen und auf sie zugreifen können, legen wir sie ab. Daten eines Sensors möchte man z.B. weiterverwenden können.

In Python kannst du Daten wie schon in Sratch in Variablen speichern. Du kannst dir eine Variable wie eine Schachtel vorstellen, in die du was ablegst. Probiere es unten gleich aus - drücke das Play-Symbol in der Mitte ganz oben um den Code auszuführen.

{% embed url="https://repl.it/@liebich/01Variablen?lite=1&outputonly=1" %}

Weil 'schoen' eine Zeichenfolge ist, muss sie in Anführungs- und Schlusszeichen eingebettet sein. Ob diese doppelt oder einfach sind, ist dir überlassen - ich werde meistens _einfach_e verwenden.

Leider passiert gar nichts im schwarzen Bereich, der sogenannten Konsole:

![](../.gitbook/assets/grafik%20%2822%29.png)

Das ist auch nicht weiter erstaunlich. Auch in Scratch würde nichts passieren, wenn wir nur Variablen notieren sie aber gar nie verwenden. Bei Scratch hättest du die Variable anzeigen lassen, indem du sie angekreuzt hättest. Du kannst in Python vor die Variable `print`schreiben, damit die Variable in der Konsole erscheint \(print = drucken\):

![](../.gitbook/assets/grafik%20%284%29.png)

Was würde wohl passieren, wenn wir die `zahl2`mit `wetter`multiplizieren? Also `print(wetter*zahl)` schreiben? Probieren Sie es selbst aus. Klicken Sie in den Code oben und bearbeiten Sie ihn entsprechend. Führen Sie dann den Code aus.

Es erscheint eine Fehlermeldung - eine gute Sache!

![](../.gitbook/assets/grafik%20%283%29.png)

{% hint style="info" %}
Fehlermeldungen sind in der Regel hilfreich. Sie geben dir wichtige Hinweise, um den Fehler beheben zu können.
{% endhint %}

In der obigen Fehlermeldung steht, dass in Zeile 7 \(line 7\) beim Code `print(wetter*zahl2)`der Fehler aufgetreten ist. Das Problem wird weiter beschrieben mit `can't multiply sequence by non-int of type 'float'`. Eine Zeichenkette wie 'wetter' kann offenbar nicht mit einer Dezimalzahl \(float\) multipliziert werden.

{% hint style="success" %}
a\) Versuche, den Fehler zu beheben.  
b\) Multipliziere die zahl1 mit der Variable wetter. Was ist der Output in der Konsole \(schwarzes Fenster\)?  
c\) Addiere die `zahl1` mit `wetter` . Was ist der Output?
{% endhint %}

Offenbar ist es wichtig zu wissen, um welchen Datentyp es sich handelt. Den Datentyp kannst Du wie folgt herausfinden:

```python
print(type(wetter))
```

![](../.gitbook/assets/grafik%20%2817%29.png)

`wetter` ist also ein String \('str'\). Es gibt noch andere wichtige Datentypen: boolean \(True oder False\) und float \(Gleitkommazahl, bspw. 4.25\).

Manchmal möchte man auch einen Input des Benutzers speichern:

```python
x = input('Bitte x-Wert eingeben: ')
```

Jetzt kann der Benutzer den x-Wert eingeben und dieser wird in der Variablen x gespeichert. Prüfen wir wie vorher den Datentyp von x, so erscheint wieder:

![](../.gitbook/assets/grafik%20%289%29.png)

Es handelt sich also wiederum um eine Zeichenkette \(ein String\). Damit lässt sich natürlich schlecht rechnen. Deshalb sollte der String in eine Ganzzahl, einen Integer, umgewandelt werden:

```python
x = int(x)
```



