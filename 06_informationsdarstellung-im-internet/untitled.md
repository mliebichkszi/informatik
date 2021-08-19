# CSS Box-Modell

## Platzierung von Inhalten mit CSS

Browser platzieren Inhalte als Boxen. Ein Inhalt kann entweder ein Block-Element oder ein Inline-Element sein. Block-Elemente führen zu einem Zeilenumbruch. Beispiele für Block-Elemente sind `h1`, `div` oder auch `p` . Im Gegensatz dazu brauchen Inline-Elemente nur soviel Platz, wie sie breit sind. Beispiele für Inline-Elelemente sind: `a`, `img` oder auch `span` . Inline-Elemente sind Teil von Block-Elementen. Für Block-Elemente kann man Höhe und Breite im CSS definieren.

![Block mit Innenabstand \(Padding\) und Aussenabstand \(Margin\)](../.gitbook/assets/grafik%20%281%29.png)

### Das Box-Modell interaktiv kennenlernen

{% hint style="success" %}
Im folgenden Codepen kannst du das Box-Modell interaktiv kennenlernen. Schiebe dazu die Schieber und beobachte, wie sich das Box-Layout und der entsprechende CSS-Code ändert.
{% endhint %}

{% embed url="https://codepen.io/psande/pen/BDLiE" %}

### DIVs als Container für Inhalte

Im Quellcode von Webseiten sind viele `div`Tags zu finden. Sie dienen als Container für weitere Inhalte. 

```css
div {
  width: 600px;
  height: 200px;
  padding: 30px 15px;
  border: 5px solid black;
  margin: 30px 50px;
}
```

### Absolute und relative Positionierung von div's

Ein `div`kann mit `position: relative;`relativ zu anderen Elementen positioniert werden. Dazu muss man noch `left`oder `right`, `top`oder `bottom`angeben. Probiere es aus:

{% embed url="https://codepen.io/thecodercoder/pen/bJePJe" %}



