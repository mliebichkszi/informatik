# Listen

Statt in einer Variablen kann man Werte auch bequem in einer Liste abspeichern und sie später bearbeiten.

Du kannst den Code der nachfolgenden Beispiele kopieren, falls du ihn in deinem repl ausprobieren willst.

{% embed url="https://youtu.be/O1PildmQIfM" %}

{% hint style="info" %}
Wir könnten bspw. Werte eines Temperatur-Sensors \(hier 3 Werte: x, y, z\) in einer Liste speichern:

```python
temperaturen = [x, y, z]
```

Auf diese Werte können wir über danach über den sogenannten _Index_ zugreifen:

```python
x_temperatur = temperaturen[0]
y_temperatur = temperaturen[1]
z_temperatur = temperaturen[2]
```

Wir können auch mit `for` durch die Liste durchgehen \("durchiterieren"\):

```python
for element in temperaturen:
  print (element)
```

Probiere es in [https://repl.it/](https://repl.it/) aus.  
  
Du kannst Listen sogar verschachteln, also eine Liste in einer Liste haben:

```python
sensordaten = [['montag', 'dienstag'], [22, 30]]
```

Es gibt vordefinierte Befehle \("Funktionen"\), die wir auf Listen anwenden können:

```python
# Gibt die Länge der Liste aus:
len(liste)
```

Du kannst mit `enumerate` auch den Index und den zugehörigen Wert ausgeben:

```python
for i, wert in enumerate (liste, 1):
  print (i, wert)
```

Um einer Liste einen Wert hinzuzufügen oder einen Wert zu löschen verwendest du `append` bzw. `pop`:

```python
liste = [1, 'hi']
# fügt einen Wert hinzu
liste.append(24.0)
# löscht den ersten Wert
liste.pop(0)
# fügt an erster Stelle einen Wert hinzu
liste.insert(0, 'informatik')
# entfernt das genannte Element
liste.remove('hi')
```

Du kannst eine Liste mit `for i in range` auch rasch mit Werten füllen:

```python
'''Erzeugt eine Liste mit den ersten 100 quadrierten Zahlen, von 0 aus
startend'''

liste = [x**2 for x in range(100)]
```
{% endhint %}

