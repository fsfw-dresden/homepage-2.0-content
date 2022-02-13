Title: Code-Hosting-Plattformen – Reaktion auf Litlith Wittmann
Date: 2022-02-05 16:00
Category: Artikel
Tags: Freie Software, Infrastruktur, Git
Slug: Code-Hosting-Plattformen-Litlith Wittmann
Author: CarK
Summary: Die Aktivistin Litlith Wittmann ist der Meinung, Public Code müsse auf der Microsoft-Plattform Github liegen. Andere Plattformen seien bestenfalls nett gemeint, aber eigentlich sinnlos. Wir sind anderer Meinung: Eine Gegenrede.


## Hintergrund

Lilith Wittmann vertritt in einem ([Twitter-Thread](https://twitter.com/LilithWittmann/status/1489733926935576584)) die Auffassung,

- a) dass öffentliche Stellen gemäß dem Prinzip *Public Money Public Code*  ihren Code veröffentlichen sollten und
- b) dass dies auf github passieren soll. Zitat: *"Doch das muss Github sein. Weil man es sonst nicht mitbekommt. Solange wir kein dezentrales Github haben, muss es Github sein."*

Ansicht a) ist in der Techi-Szene (aka Chaos-Bubble) ziemlicher Konsens. Ansicht b) stößt auf Kritik.

**Update 2022-02-05 12:42:31**: Lilith Wittmann hat sich ausführlich auf Mastodon zu dem Thema geäußert: [Link](https://chaos.social/@Lilith/107744638364954082). Das ermöglicht eine konkrete Auseinandersetzung mit ihrer Position (siehe unten).


## Warum ist das relevant?

Lilith Wittmann hat durch Ihre beeindruckenden Veröffentlichungen \[z.B. [1](https://lilithwittmann.medium.com/wenn-die-zivilgesellschaft-bei-open-data-hilft-905add0aa21b), [2](https://lilithwittmann.medium.com/bundesservice-telekommunikation-enttarnt-dieser-geheimdienst-steckt-dahinter-cd2e2753d7ca) \] und ihren [Aktivismus](https://de.wikipedia.org/wiki/Lilith_Wittmann#Aktivismus) eine nicht unerhebliche Strahlkraft und eine Vorbildwirkung. Wenn Sie sich dann vehement für die Nutzung von zentralisierter Monopol-Infrastruktur (Github) durch öffentliche Stellen ausspricht, sendet das problematisches Signal.


## Was ist die Gegenposition

Unserer Meinung nach sollte das Prinzip *Public Money Public Code* auf Infrastruktur umgesetzt werden, deren Betrieb möglichst dezentral und am Gemeinwohl orientiert organsiert ist. Ein Beispiel hierfür ist der gemeinnützige Verein https://codeberg.org/. Eine weitere begrüßenswerte Möglichkeit wären von öffentlichen Stellen betriebene Instanzen von gittea oder gitlab. Relevante Kriterien sind, dass barrierefreies Klonen der Repositorien möglich ist und jede:r sich auf der Plattform registrieren kann, um sich an Diskussionen (Issues) zu beteiligen und Verbesserungsvorschläge (Pull/Merge-Requests) einzureichen.

Um den unbestreitbaren Netzwereffekt der Plattform Github zu nutzen und die damit von Lilith Wittmann als essentiell erachtete Sichtbarkeit zu erreichen, spricht nichts dagegen, dort jeweils eine automatisch aktualisierte Kopie der Public-Code-Repositorien zu hosten.

---

## Anmerkungen zu ihren [ausführlichen Erläuterungen](https://chaos.social/@Lilith/107744638364954082)

>  Ich stehe weiterhin voll hinter der Position, dass die öffentliche Verwaltung bei ihren FOSS Projekten, solange wir noch keine ernsthafte dezentrale Alternative haben, die Plattform Github benutzen sollten. Um Plattformeffekte zu nutzen. Weil das anderswo sehr gut klappt.

Meinungsverschiedenheiten bestehen hier vermutlich bezüglich den Bedeutung von *"ernsthaft"* und der Wichtigkeit von *Plattformeffekten*.

1. *"ernsthaft"* kann man in Bezug auf a) die technischen Features der Plattform beziehen (Repo-Hosting, Issuetracker, Pull/Merge-Requests, CI-Dienste) oder b) auch die nichttechnischen Merkmale (Community-Größe etc) einbeziehen. Bezüglich a) gibt es unserer Meinung nach mit **gitlab und gittea gute Lösungen**. Aspekt b) ziehlt auf Punkt 2.

2. *Plattformeffekte* von Github sind nützlich, damit möglichst viele Menschen ein Projekt sehen und möglichst niedrigschwellig beitragen können. Gleichzeitig zementiert dieser Effekt die **Monopolstellung**. Für *Public Code*-Projekte sollte daher eine **Doppelstrategie** gefahren werden: Präsenz der Projekte auf Github, Issue-tracking etc. möglichst auf dezentralen Plattformen. Transparenz bezüglich dieser Strategie kann auf der Landeseite (`README.md`) des Projekts hergestellt werden.


> Ich stehe aber auch dahinter, weil ich nicht in vom Staat geownte Räume kommen mag, um mir deren Code anzuschauen oder dazu zu contributen.

Das ist eine nachvollziehbare **persönliche Präferenz**. Mindestens genau so nachvollziehbar sollte aber die Haltung sein, dass viele Menschen keine von einem der mächstigsten Konzerne der Welt geownte Infrastruktur benutzen mögen, die außerdem einem** problematischen politischen System** (Bsp.: Trump) und einem erwiesenermaßen fatalen Zugriff verschiedener Geheimdienste (Stichwort: Snowden) unterliegt.

Aus unserer Sicht sollte die relevante IT-Infrastruktur für deutsche und europäische Belange möglichst im Einflussbereich der mit ihr arbeitenden und von ihr abhängigen Bürger:innen liegen und – natürlich – möglichst demokratisch und gemeinwohlorientiert betrieben werden. Das heißt keineswegs lokalen Institutionen blindes Vertrauen entgegenzubringen. Die Präferenz für möglichst lokale bzw. "nationale" Lösungen entspringt der Einsicht, dass diese sich **besser kontrollieren lassen, als ein multinationales Unternehmen** das hauptsächlich den **Gewinninteressen** seiner Anteilseigner:innen verpflichtet ist.


> Die Plattformökonomie ist für mich etwas, das existiert. Und das bekommen wir nicht weg, indem wir ein paar kleinere Plattformen aufbauen.

Es geht (aktuell) nicht darum, die Plattformökonomie grundsätzlich wegzubekommen. Es geht darum, möglichst **nicht von ihren negativen Auswirkungen** betroffen zu sein. Auf ein anderes Problemfeld übertragen, würde Liliths Argument lauten: "Hunger ist etwas, das existiert. Das bekommen wir nicht weg, indem wir ein paar Menschen etwas zu essen geben." Das ist zwar formal richtig, aber aus unserer Sicht keine besonders hilfreiches Framing auf des Problems.

> Sondern entweder durch echte dezentrale Ansätze (wobei das sehr schwierig wird) oder Vergesellschaftung bestehender großer Plattformen.

Beides fällt aber nicht einfach so vom Himmel. Offensichtlich müssen sich dezentrale Ansätze entwickeln können. Dazu braucht es eine wachsende Basis von (institutionellen) Nutzer:innen und Use Cases. Und auch bezüglich Vergesellschaftung gilt: das wird politisch erst denk- und verhandelbar, wenn das Problem als solches erkennbar ist. Genauso wenig wie Fische über die Abschaffung von "Wasser" diskutieren können, kann eine Gesellschaft, in der es praktisch nur einen Monopolisten gibt, über dessen Vergesellschaftung sprechen. Hinzu kommt Lobbyeinfluss etc. Die Existenz dezentraler Alternativen kann wesentlich zur Einhegung und ggf. Überwindung des Plattformkapitalismus beitragen.


> Kapitalismus führt in unserer heutigen Welt immer automatisch zu Plattformkapitalismus. Und dieses Problem müssen wir an der Wurzel angehen.

Wir vermuten, dass hiermit ein politischer Prozess gemeint ist. Dieser wird nicht ohne Konflikte möglich sein. Es ist schwer vorstellbar, dass ein Konzern einen Prozess auf bzw. mit Hilfe seiner Infrastruktur ablaufen lässt, der seine wirtschaftlichen Interessen bzw. seine Existenz bedroht. Zugespitzter Vergleich: Das ist so, als wenn man in der BILD-Zeitung Anzeigen schalten würde: "Die BILD-Zeitung ist unseriös und gefährlich. Bitte nie wieder kaufen!"


> Das selbe sehe ich persönlich so auch beim Hosting.

(Der Rest des Threads befasst sich mit Hosting-Fragen – auch ein spannendes Thema, wird aber hier aktuell nicht weiter aufgegriffen).

---

## Fazit


Lilith Wittmann ist eine reichweitenstarke Aktivistin, die schon viele coole Dinge durchgezogen hat und damit für viele Menschen ein Vorbild darstellt. Ihrer Position zur Alternativlosigkeit von Github sollte unserer Meinung nach aber nicht unkritisch übernommen werden.

