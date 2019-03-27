Stundenprotokolle
=
## Vorwort:
Im Folgenden sind unsere Arbeitsschritte vom Informatikprojekt bis zum 26.03.19 protokolliert.
***
## Protokolle:

### 17.12.18:
In der ersten Stunde vom neuen Projekt haben wir uns mit der reinen Ideensammlung und Konzeptentwicklung beschäftigt.
Dabei haben wir unter anderem im Internet nach Minispielen geguckt und haben so Inspiration erhalten.

### 18.12.18:
Die  Ideenfindung aus der letzten Stunde wurde weitergeführt und wir haben erste Spielekonzepte entwickelt und verbessert.
Somit haben wir diese Stunde mit Brainstorm verbracht.

### 08.01.19:
Nach den Ferien mussten wir uns erst kurz in die Ergebnisse und Mitschriften der letzten Stunde reinarbeiten und lesen, um uns 
nun für eines der Konzepte zu entscheiden. Unsere Wahl traf auf das "Tower-Defence" Genre. Nun entwarfen wir einen groben Plan,
wie unser Spiel aufgebaut sein soll und welche Komponenten enthalten sein sollen.

### 14.01.19:
Nun folgen erste Umseztungen des Plans in Greenfoot. Die erste Gegnerklasse haben wir auch erstellt und nun wollten wir, dass
diese immer den gleichen Pfad ablaufen. Dazu haben wir gewisse Wegpunkte festgelegt, an denen sich die Gegner dann in 
die Richtung des nächsten Wegpunktes drehen. Somit konnten wir dem perfekten Weg konstruieren.

### 15.01.19:
Der Pfad wurde fertiggestellt und wir haben uns weiter Gedanken über die verschiedenen Gegnerklassen gemacht.

### 21.01.19:
Da wir die Geschwindigkeit der Gegner selbst bei geringstmöglicher Geschwindigkeit als zu schnell empfanden, suchten wir 
nach Möglichkeiten diese noch weiter zu reduzieren. Unser Lehrer Herr Buhl gab uns den Hinweis die Recherche nach 
"Smooth-Mover" fortzusetzen.

### 22.01.19:
Es wurde weiter zum Smooth-Mover recherchiert, und ausprobiert.

### 29.01.19:
Da wir immer noch keine Lösung fanden wurde wieder nur recherchiert.

### 04.02.19:
Nun haben wir Herrn Buhl um Rat gefragt und nach einem kleinen Hinweis auf einen Fehler im Code sind wir jetzt recht schnell
zur Lösung des Problems gelangt und wir konnten den Smooth-Mover einrichten und endlich die perfekte Geschwindigkeit der 
Gegner festlegen.

### 12.02.19:
Jetzt folgen die eigenen Turrets, mit denen die Gegner abgewehrt werden können. Dazu erstellten wir machten wir eine 
kleine Klassenumfrage, bei der wir uns weitere Ideen erhofften. Anschließend wurden einige Turret-Konzepte entwickelt.

### 19.02.19:
Es wurde an der ersten Turret-Klasse gearbeitet, wobei wir Eigenschaften wie Reichweite und Feuerrate festlegten. Da wir aus 
dem vorigen Projekt bereits wussten, wie man Projektile erstellt mussten wir hierfür keine großartige Recherche betreiben.

### 25.02.19:
Da verschiedene Turret-Klassen geplant sind setzten wir eine Lebenspunktanzahl für die Gegnertypen fest und setzten 
verschiedene Reichweiten, Feuerraten und Schadenpunkte für die Turret-Klassen an, wobei wir uns jedoch vorerst nur mit 
einer davon auseinandersetzten.

### 26.02.19:
Da wir bisher immer die Gegner manuell, mit Betätigung einer bestimmten Taste, Gegner am Anfang des Pfades erschienen ließen
schrieben wir nun den Code so um, dass diese automatisch mit einem gewissen Zeitabstand erscheinen.

### 04.03.19:
Da wir ebenfalls aus dem vorherigen Projekt eine Explosionsanimation hatten kamen wir auf die Idee diese bei Zerstörung 
eines Gegners zu verwenden. Nun fiel uns beim Ausprobieren auf, dass immer der zuletzt in die Reichweite des Turrets
getretene Gegner von diesem angegriffen wird, und nicht wie von uns erwünscht der zuerst eingetretene. Zur Problemlösung 
haben wir recherchiert.

### 05.03.19:
Recherche ging weiter, jedoch konnten wir das Problem nicht lösen.

### 18.03.19:
Im Greenfoot-Buch fanden wir etwas zu Liste in Java und haben dies im Projekt ausprobiert, haben es allerdings nicht hinreichend
geschafft.

### 25.03.19:
Mit Hilfe von Herrn Buhl haben wir den Gegnern eine Variable hinzugefügt die bei allen unterscheidlich ist, um diese in einer Liste sortieren zu können.

### 26.03.19:
Jetzt konnten wir die Gegner mithilfe der Liste nach der Variable ordnen und daraus den anzugreifenden Gegner 
herauslesen lassen. Diese Information kann nun vom Projektil gesehen werden und wés weisß somit welchen Gegner es 
antreffen soll. Da jedoch nur der Gegner als Objekt bei Zerstörung aus der Welt entfernt wird und nicht aus der Liste gelöscht
wird haben wir recherchiert wie dies zu bewerkstelligen ist.



