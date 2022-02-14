Title: Code-Hosting-Plattformen – Reaktion auf Lilith Wittmann
Date: 2022-02-13 20:00
Category: Artikel
Tags: Freie Software, Infrastruktur, Git
Slug: Code-Hosting-Plattformen-Lilith-Wittmann
Author: CarK
Summary: Die Aktivistin Lilith Wittmann ist der Meinung, Public Code müsse auf der Microsoft-Plattform Github liegen. Andere Plattformen seien bestenfalls nett gemeint, aber eigentlich sinnlos. Wir sind anderer Meinung: Eine Gegenrede.


## Hintergrund

Lilith Wittmann vertritt in einem ([Twitter-Thread](https://twitter.com/LilithWittmann/status/1489733926935576584)) die Auffassung,

- a) dass öffentliche Stellen gemäß dem Prinzip *Public Money Public Code*  ihren Code veröffentlichen sollten und
- b) dass dies auf github passieren soll. Zitat: *"Doch das muss Github sein. Weil man es sonst nicht mitbekommt. Solange wir kein dezentrales Github haben, muss es Github sein."*

Ansicht a) ist in der Techi-Szene (aka Chaos-Bubble) ziemlicher Konsens. Ansicht b) stößt auf Kritik.

**Update 2022-02-05 12:42:31**: Lilith Wittmann hat sich ausführlich auf Mastodon zu dem Thema geäußert: [Link](https://chaos.social/@Lilith/107744638364954082). Das ermöglicht eine konkrete Auseinandersetzung mit ihrer Position (siehe unten).


## Warum ist das relevant?

Lilith Wittmann hat durch Ihre beeindruckenden Veröffentlichungen \[z.B. [1](https://lilithwittmann.medium.com/wenn-die-zivilgesellschaft-bei-open-data-hilft-905add0aa21b), [2](https://lilithwittmann.medium.com/bundesservice-telekommunikation-enttarnt-dieser-geheimdienst-steckt-dahinter-cd2e2753d7ca) \] und ihren [Aktivismus](https://de.wikipedia.org/wiki/Lilith_Wittmann#Aktivismus) eine nicht unerhebliche Strahlkraft und eine Vorbildwirkung. Wenn Sie sich dann vehement für die Nutzung von zentralisierter Monopol-Infrastruktur (Github) durch öffentliche Stellen ausspricht, sendet das problematisches Signal.


## Was ist die Gegenposition

Unserer Meinung nach sollte das Prinzip *Public Money Public Code* auf Infrastruktur umgesetzt werden, deren Betrieb möglichst dezentral und am Gemeinwohl orientiert organsiert ist. Ein Beispiel hierfür ist der gemeinnützige Verein <https://codeberg.org/>. Eine weitere begrüßenswerte Möglichkeit wären von öffentlichen Stellen betriebene Instanzen von gitea oder gitlab. Relevante Kriterien sind, dass barrierefreies Klonen der Repositorien möglich ist und jede:r sich auf der Plattform registrieren kann, um sich an Diskussionen (Issues) zu beteiligen und Verbesserungsvorschläge (Pull/Merge-Requests) einzureichen.

Um den unbestreitbaren Netzwereffekt der Plattform Github zu nutzen und die damit von Lilith Wittmann als essentiell erachtete Sichtbarkeit zu erreichen, spricht nichts dagegen, dort jeweils eine automatisch aktualisierte Kopie der Public-Code-Repositorien zu hosten.

---

## Anmerkungen zu ihren [ausführlichen Erläuterungen](https://chaos.social/@Lilith/107744638364954082)

>  Ich stehe weiterhin voll hinter der Position, dass die öffentliche Verwaltung bei ihren FOSS Projekten, solange wir noch keine ernsthafte dezentrale Alternative haben, die Plattform Github benutzen sollten. Um Plattformeffekte zu nutzen. Weil das anderswo sehr gut klappt.

Meinungsverschiedenheiten bestehen hier vermutlich bezüglich den Bedeutung von *"ernsthaft"* und der Wichtigkeit von *Plattformeffekten*.

1. *"ernsthaft"* kann man in Bezug auf a) die technischen Features der Plattform beziehen (Repo-Hosting, Issuetracker, Pull/Merge-Requests, CI-Dienste) oder b) auch die nichttechnischen Merkmale (Community-Größe etc) einbeziehen. Bezüglich a) gibt es unserer Meinung nach mit **gitlab und gitea gute Lösungen**. Aspekt b) ziehlt auf Punkt 2.

2. *Plattformeffekte* von Github sind nützlich, damit möglichst viele Menschen ein Projekt sehen und möglichst niedrigschwellig beitragen können. Gleichzeitig zementiert dieser Effekt die **Monopolstellung**. Für *Public Code*-Projekte sollte daher eine **Doppelstrategie** gefahren werden: Präsenz der Projekte auf Github, Issue-tracking etc. möglichst auf dezentralen Plattformen. Transparenz bezüglich dieser Strategie kann auf der Landeseite (`README.md`) des Projekts hergestellt werden.


> Ich stehe aber auch dahinter, weil ich nicht in vom Staat geownte Räume kommen mag, um mir deren Code anzuschauen oder dazu zu contributen.

Das ist eine nachvollziehbare **persönliche Präferenz**. Mindestens genau so nachvollziehbar sollte aber die Haltung sein, dass viele Menschen keine von einem der mächstigsten Konzerne der Welt geownte Infrastruktur benutzen mögen, die außerdem einem** problematischen politischen System** (Bsp.: Trump) und einem erwiesenermaßen fatalen Zugriff verschiedener Geheimdienste (Stichwort: Snowden) unterliegt.

Aus unserer Sicht sollte die relevante IT-Infrastruktur für deutsche und europäische Belange möglichst im Einflussbereich der mit ihr arbeitenden und von ihr abhängigen Bürger:innen liegen und – natürlich – möglichst demokratisch und gemeinwohlorientiert betrieben werden. Das heißt keineswegs, lokalen Institutionen blindes Vertrauen entgegenzubringen. Die Präferenz für möglichst lokale bzw. "nationale" Lösungen entspringt der Einsicht, dass diese sich **besser kontrollieren lassen, als ein multinationales Unternehmen**, das hauptsächlich den **Gewinninteressen** seiner Anteilseigner:innen verpflichtet ist.


> Die Plattformökonomie ist für mich etwas, das existiert. Und das bekommen wir nicht weg, indem wir ein paar kleinere Plattformen aufbauen.

Es geht (aktuell) nicht darum, die Plattformökonomie grundsätzlich wegzubekommen. Es geht darum, möglichst **nicht von ihren negativen Auswirkungen** betroffen zu sein. Auf ein anderes Problemfeld übertragen, würde Liliths Argument lauten: "Hunger ist etwas, das existiert. Das bekommen wir nicht weg, indem wir ein paar Menschen etwas zu essen geben." Das ist zwar formal richtig, aber aus unserer Sicht keine besonders hilfreiches Framing des Problems.

> Sondern entweder durch echte dezentrale Ansätze (wobei das sehr schwierig wird) oder Vergesellschaftung bestehender großer Plattformen.

Beides fällt aber nicht einfach so vom Himmel. Offensichtlich müssen sich dezentrale Ansätze entwickeln können. Dazu braucht es eine wachsende Basis von (institutionellen) Nutzer:innen und Use Cases. Und auch bezüglich Vergesellschaftung gilt: das wird politisch erst denk- und verhandelbar, wenn das Problem als solches erkennbar ist. Genauso wenig wie Fische über die Abschaffung von "Wasser" diskutieren können, kann eine Gesellschaft, in der es praktisch nur einen Monopolisten gibt, über dessen Vergesellschaftung sprechen. Hinzu kommt Lobbyeinfluss etc. Die Existenz dezentraler Alternativen kann wesentlich zur Einhegung und ggf. Überwindung des Plattformkapitalismus beitragen.


> Kapitalismus führt in unserer heutigen Welt immer automatisch zu Plattformkapitalismus. Und dieses Problem müssen wir an der Wurzel angehen.

Wir vermuten, dass hiermit ein politischer Prozess gemeint ist. Dieser wird nicht ohne Konflikte möglich sein. Es ist schwer vorstellbar, dass ein Konzern einen Prozess auf bzw. mit Hilfe seiner Infrastruktur ablaufen lässt, der seine wirtschaftlichen Interessen bzw. seine Existenz bedroht. Zugespitzter Vergleich: Das ist so, als wenn man in der BILD-Zeitung Anzeigen schalten würde: "Die BILD-Zeitung ist unseriös und gefährlich. Bitte nie wieder kaufen!"


> Das selbe sehe ich persönlich so auch beim Hosting.

(Der Rest des Threads befasst sich mit Hosting-Fragen – auch ein spannendes Thema, wird aber hier aktuell nicht weiter aufgegriffen).

---

## Fazit (2022-02-13)


Lilith Wittmann ist eine reichweitenstarke Aktivistin, die schon viele coole Dinge durchgezogen hat und damit für viele Menschen ein Vorbild darstellt. Ihrer Position zur Alternativlosigkeit von Github sollte unserer Meinung nach aber nicht unkritisch übernommen werden.


---
<a name="update-2022-02-14"></a>

<br>

## Update 2022-02-14:

Lilith Wittmann hat sich nicht lumpen lassen und ihrerseits diesen Beitrag eingeordnet ([siehe Toot](https://chaos.social/@Lilith/107792969256005080)):


> Man könnte so viele gute Punkte gegen meine Position, Code der Verwaltung bei Github zu hosten, anführen.
> <br>
> <br>
> Das ist hier imho leider nicht gelungen.
> <br>
> <br>
> Möchte euch aber dieses Meisterstück von Digitalnationalismus verbunden mit der privilegiert Position "wir können das ja selber hosten, da müssen wir nicht gegen die Plattformökonomie arbeiten, das ist ja unrealistisch" nicht vorenthalten.
> <br>
> <br>
> <https://social.tchncs.de/@fsfwdresden/107792869103588092>


Genaugenommen sprechen wir uns nicht dagegen, aus Code der Verwaltung bei Github zu hosten (siehe oben: "Für *Public Code*-Projekte sollte daher eine **Doppelstrategie** gefahren werden ..."). Unsere Position ist, es sollte nicht Github *alleine* und auch nicht *primär* sein (fürs Issue Tracking etc.).


Der erste (von zwei) spannenden Punkten ist aber der **Vorwurf des "Digitalnationalismus"**. Ein Vorwurf ist es deshalb, weil "Nationalismus" im überwiegenden Teil der deutschsprachigen Gesellschaft auf Grund unvermeidlicher historische Bezüge ziemlich negativ besetzt ist. Oft wird unter "Nationalismus" u.a. eine Überhöhung der eigenen und eine Abwertung anderer ethnischer Gruppen verstanden.

Mutmaßlich ist das Plädoyer für "*nationale Lösungen*" ein wesentlicher Aufhänger für den Nationalismus-Vorwurf. Im Originalkontext betrachtet, offenbart er sich allerdings als schwer haltbar. Zitat: "Das heißt keineswegs, lokalen Institutionen blindes Vertrauen entgegenzubringen. Die Präferenz für möglichst lokale bzw. 'nationale' Lösungen entspringt der Einsicht, dass diese sich **besser kontrollieren lassen, als ein multinationales Unternehmen**, das hauptsächlich den **Gewinninteressen** seiner Anteilseigner:innen verpflichtet ist." (siehe oben).

Um Missverständnisse und mögliche Fehlinterpretationen zu vermeiden: "national" bezieht sich hier auf die existierende Verwaltungsentität "Staat" als [originäres Völkerrechtssubjekt](https://de.wikipedia.org/wiki/V%C3%B6lkerrechtssubjekt). Weil der Text sich (im Geiste der mindestens EU-weit angelegten [*Public Code*-Initiative](https://publiccode.eu/)) um eine möglichst international gültige Perspektive bemüht, steht dort nicht "bundes-deutsch" oder ähnliches. Die Aussage erfolgt außerdem unter der **Prämisse** hinreichend funktionierender rechtsstaatllicher und **demokratischer Prinzipien**.


<br>

Der zweite spannende Punkt ist der **Privilegien-Vorwurf**: "'wir können das ja selber hosten, da müssen wir nicht gegen die Plattformökonomie arbeiten, das ist ja unrealistisch'". Auch dieser Vorwurf unserer Meinung nach **ungerechtfertigt**. Gründe:

1. Wir schlagen explizit <https://codeberg.org/> als eine mögliche Alternative zu Github vor. Damit ist **kein Hostingaufwand** verbunden.
2. Die Hürde des selber Hostens (auf öffentlichen gittea oder gitlab-Instanzen) ist verglichen mit anderen staatlichen Infrastrukturaufgaben absolut zumutbar.
3. Vom Staat die Bereitstellung einer entsprechenden Infrastruktur (als Alternative zu einer weiteren Konzernabhängigkeit) zu fordern, ist unserer Meinung nach nicht "privilegiert", sondern das schlicht das Recht digital mündiger Bürger:innen.


Der zweite Teil des Vorwurfs ("'da müssen wir nicht gegen die Plattformökonomie arbeiten, das ist ja unrealistisch'") ist etwas **verwunderlich**. Aus unserer Stellungnahme geht klar hervor, dass wir die Plattformökonomie für problematisch halten. Möglicherweise ist aber unsere Formulierung "Es geht (aktuell) nicht darum, die Plattformökonomie grundsätzlich wegzubekommen." der Aufhänger dafür. Gemeint ist: Unter den gegebenen globalen, europäischen und nationalstaatlichen Machtverhältnissen ist das **Brechen der Plattformmonopole zwar wünschenswert aber unrealistisch**. Die Nutzung und die damit verbundene Stärkung dezentraler Alternativen ist ein **Schritt in die richtige Richtung, der aktuell** gegangen werden kann und eine Überwindung der Monopol-Situationen in Zukunft realistischer macht.

Lilith Wittmanns Position scheint dagegen zu sein, Monopol-Infrastruktur eifrig zu nutzen und ihre Nutzung durch die Verwaltung explizit einzufordern, während sie gleichzeitig die "Vergesellschaftung bestehender großer Plattformen" fordert, denn "dieses Problem müssen wir an der Wurzel angehen" ([Quelle](https://chaos.social/@Lilith/107744693098758404)).


Aus unserer Sicht ist **dieser Ansatz widersprüchlich** (siehe auch BILD-Beispiel oben), aber vielleicht hat Lilith Wittmann ja einen **cleveren Plan** zur Überwindung des Plattformkapitalismus von innen heraus, den wir noch nicht verstanden haben.


## Fazit (2022-02-14)

Vermutlich (und hoffentlich) hat Lilith Wittmann wichtigere Dinge zu tun, als sich auf ein nerviges Kritik-Ping-Pong einzulassen. Wir sehen unsere Rolle darin, herauszuarbeiten wo ihre bisherige Argumentation Schwächen hat, a) um ggf. sie selbst zum Überdenken anzuregen und b) um andere bei der kritischen Reflektion ihrer Positionen zu unterstützen.
