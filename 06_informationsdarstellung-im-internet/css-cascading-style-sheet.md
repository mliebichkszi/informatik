# CSS - Cascading Style Sheet

## Webseiten formatieren mit CSS

{% hint style="info" %}
CSS steht für **C**ascading **S**tyle **S**heet. Mit CSS kannst du Formatierungsregeln definieren, die du dann in deiner html-Datei anwenden kannst.
{% endhint %}

{% embed url="https://codepen.io/wavemind/pen/eYWJewQ" %}

### Ein CSS-Beispiel

Im folgenden Beispiel werden Formatierungsregeln für `body` `h1`und `ul`definiert. Die Datei wird mit der Endung \*.css gespeichert \(bspw. als style.css\) im gleichen Ordner wie die \*.html-Datei gespeichert.

{% hint style="info" %}
CSS-Dateien bestehen aus Blöcken. Diese wiederum aus:

* einem Selektor, um das Element, das wir stylen wollen, auszuwählen
* Eigenschaften mit Name und Wert

Eigenschaften werden in geschweiften Klammern geschrieben. Die Eigenschaftswerte werden nach einem Doppelpunkt angegeben.
{% endhint %}

```css
{
  background-color: orange;
  color: black;
  font-size: small;
  font-family: Georgia, "Trebuchet MS", Verdana, sans-serif;
}

h1, em
{
  font-weight: bold;
  font-style: normal;
}

h1
{
  font-size: 200%;
}

em
{
  color: blue;
}

ul em
{
  color: red;
}
```

{% hint style="info" %}
`h1`steht für die oberste Überschrift. Probiere andere aus:

* `<h1>` : Heading level 1
* `<h2>` : Heading level 2
* `<h3>` : Heading level 3
* `<h4>` : Heading level 4
* `<h5>` : Heading level 5
* `<h6>` : Heading level 6
{% endhint %}

### Selektoren

Selektoren sind im folgenden Beispiel `ul`und `em`.

```css
ul em
{
  color: red;
}
```

### Vererbung

Beim Formatieren muss man beachten, dass Elemente von in der Hierarchie höher stehenden Elementen erben. Die folgende Regel für `body`bewirkt, dass alle "tieferen" Elemente ebenfalls eingefärbt werden. Möchte ich das für bspw. die `em`ändern, so muss ich eine eigene Regel für `em`erstellen.

```css
body
{
  background-color: orange;
  color: black;
  font-size: small;
  font-family: Georgia, "Trebuchet MS", Verdana, sans-serif;
}
```

![DOM. https://wiki.selfhtml.org/wiki/JavaScript/DOM](../.gitbook/assets/grafik%20%2819%29.png)

{% code title="Eigene Regel für em" %}
```css
body
{
  background-color: orange;
  color: black;
  font-size: small;
  font-family: Georgia, "Trebuchet MS", Verdana, sans-serif;
}
em
{
  color: blue;
}
```
{% endcode %}

### Klassen

Wie kann ich aber bspw. nur einzelne Paragraph individuell formatieren? Dazu kann man mit sogenannten Klassen arbeiten.

{% tabs %}
{% tab title="style.css" %}
```css
p.individuell
{
  background-color: green;
}
```
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="index.html" %}
```markup
<p class="individuell">
     Das ist ein grün gefärbter Absatz.
</p>
```
{% endtab %}
{% endtabs %}

### Einbinden der css-Datei in der html-Datei

Damit wir auf die Formatierungsdefinitionen in der html-Datei zugreifen können, müssen wir die css-Datei einbinden. Das machen wir im head-Teil:

```markup
<head>
    <meta charset="utf-8"/>
    <link href="style.css" rel="stylesheet" type="text/css"/>
    <title>Steckbrief von Yann Sommer</title>
  </head>
```

### Aufgabe

{% hint style="success" %}
Verändere die css-Datei; verwende bspw. eine unterschiedliche Farbe. Hier findest du wieder viele Beispiele: [https://www.w3schools.com/css/](https://www.w3schools.com/css/)
{% endhint %}



