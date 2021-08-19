# Struktur einer html-Seite

## Tags

In einer html-Seite siehst du etwas sehr oft: Tags. Sie haben die Form `<tag>`und werden mit `</tag>`abgeschlossen.

### Einige wichtige Tags

<table>
  <thead>
    <tr>
      <th style="text-align:left">Tag</th>
      <th style="text-align:left">Bedeutung</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">html</td>
      <td style="text-align:left">
        <p>Der wichtigste Tag. Er macht dem Browser klar,</p>
        <p>dass es sich beim Dokument um eine html-Seite handelt.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">head</td>
      <td style="text-align:left">Im head einer Webseite wird der Zeichensatz (utf-8) und der Titel angegeben.
        <br
        />Zus&#xE4;tzlich werden hier Skripte (js) und Formatierungsdokumente (css)
        eingebunden.</td>
    </tr>
    <tr>
      <td style="text-align:left">body</td>
      <td style="text-align:left">Im body einer Webseite findet man den eigentlichen Inhalt.</td>
    </tr>
    <tr>
      <td style="text-align:left">p</td>
      <td style="text-align:left">Startet einen Absatz</td>
    </tr>
    <tr>
      <td style="text-align:left">....</td>
      <td style="text-align:left">....</td>
    </tr>
  </tbody>
</table>

### Aufgabe 1

{% hint style="success" %}
Informiere dich über weitere Tags hier: [https://wiki.selfhtml.org/wiki/HTML/Tutorials/HTML5/Element,\_Tag\_und\_Attribut](https://wiki.selfhtml.org/wiki/HTML/Tutorials/HTML5/Element,_Tag_und_Attribut). Auf dieser Seite kannst du die Tags wie bspw. `<a>` selbst ausprobieren:  
[https://www.w3schools.com/TAGS/tag\_a.asp](https://www.w3schools.com/TAGS/tag_a.asp)
{% endhint %}

### Aufgabe 2

{% hint style="success" %}
Erstelle eine Webseite mit Informationen zu bspw. deinem Lieblingstier, -buch, -verein. Dazu öffnest du mit CMD + Space und der Eingabe "Atom" den Code-Editor. Speichere deine Seite mit der Endung .html ab. Öffne die Seite im Firefox-Browser. Das Grundgerüst deiner Seite sollte wie folgt aussehen \(du kannst Code schnell kopieren durch Drücken von ![](../.gitbook/assets/grafik.png)rechts oben im Codeblock.

```markup
<!DOCTYPE html>
<html lang="de">
  <head>
    ...
  </head>
  <body>
    ...
  </body>
</html>
```
{% endhint %}

### Aufgabe 3

{% hint style="success" %}
Validiere deine Webseite auf [https://validator.w3.org/](https://validator.w3.org/). Dazu kopierst du deinen html-Code und fügst ihn unter dem Tab "Validate by Direct Input" ein.
{% endhint %}

### Aufgabe 4

{% hint style="success" %}
Der folgende html-Code validiert nicht. Behebe die Fehler!

```markup
<?xml version="1.0" encoding="iso-8859-1" ?>
<!DOCTYPE html PUBLIC
    "-//W3C//DTD XHTML 1.1//EN"
    "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="de">
  <head>
    <title>Steckbrief von Yann Sommer</title>
    <h1>Steckbrief</h1>
  </head>
  <body background="orange">
    <img src="sommer.jpg"/>
    <p>
      Ich heisse <em>Yann Sommer</em>. Ich lebe in der Nähe
      von Kaiserslautern.
    </p>
    <p>
      Ich interessiere mich für <em>Fussball</em>.
      Meine grössten Erfolge sind:
    </p>
    <ul>
      <li><em>Schweizermeister</en> 2011-2014</li>
      <li><em>EM Viertelfinal<em> 2021</li>
    </ul>
    <p>
      Du findest meine Website hier:
      <a href=https://www.yannsommer.ch/>Yann Sommer Official</a>.
    </p>
  </body>
</HTML>
```
{% endhint %}







