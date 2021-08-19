# Client - Server

### Client

Unter einem Client versteht man einen Rechner, der über ein Programm \(bspw. Firefox oder ein Terminal\) verfügt, das Daten empfangen kann.

### Server

Ein Server ist ein Rechner, der Daten zentral speichert. Anfragen an die Daten werden von den Clients über ein Programm gemacht.

## Ein Beispiel

Rufst du auf deinem Rechner die Webseite kszi.ch auf, so macht dein Browser eine Anfrage an die Adresse. Diese Anfrage wird in eine eindeutige Adresse, die IP-Adresse umgewandelt, die IP-Adresse wird danach angefragt und die angeforderten Daten vom Webseiten-Server an deinen Browser zurückgeschickt. Die IP-Adresse des Webservers kannst du einfach herausfinden, indem du die Webseite in einem Terminal anpingst:

```bash
ping kszi.ch
PING kszi.ch (185.17.70.75): 56 data bytes
64 bytes from 185.17.70.75: icmp_seq=0 ttl=55 time=13.113 ms
64 bytes from 185.17.70.75: icmp_seq=1 ttl=55 time=10.487 ms
64 bytes from 185.17.70.75: icmp_seq=2 ttl=55 time=38.540 ms
64 bytes from 185.17.70.75: icmp_seq=3 ttl=55 time=10.867 ms
```

{% tabs %}
{% tab title="Frage" %}
Gibst du jetzt statt kszi.ch die IP-Adresse 185.17.70.75 ein, dann erscheint aber nicht die Webseite selbst. Warum?
{% endtab %}

{% tab title="Antwort" %}

{% endtab %}
{% endtabs %}

![Die Webseite der KZI](../.gitbook/assets/grafik%20%2816%29.png)

