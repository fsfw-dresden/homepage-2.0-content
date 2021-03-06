Title: Funding Freedom Initiative - Idee zur Finanzierung freier Softwareprojekte
Date: 2018-08-15 20:00
Category: Artikel
Tags: Freie Software, Gesellschaft
Slug: funding-floss
Author: Carsten
Summary: Der Artikel schlägt unter dem Arbeitstitel „Funding Freedom Initiative“ eine Finanzierungsmöglichkeit zur Steigerung der Verbreitung und Qualität von Freier Software vor. Sie beruht im Wesentlichen auf der Kombination existierender Geschäftsmodellle: Spenden, Merchandise, Bounties, Funding-Organisationen.

## Note:
An english version of this blog post and presentation slides prepared for 35C3 are availible in the [wiki](https://wiki.fsfw-dresden.de/doku.php/doku/funding-foss).

## tl;dr

Dieser Text beschreibt eine Idee zur Steigerung der Verbreitung und Qualität von freier quelloffener Software (kurz: [FLOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software)).
Durch die Kombination existierender Geschäftsmodelle (Spenden, Merchandise, Bounties, Funding-Organisationen) sollen
Finanzmittel akquiriert werden, die FLOSS-Projekten für Entwicklung, Design, Marketing, Dokumentation etc. nutzen können. Kernidee ist der „Verkauf“ von FLOSS-Support-Zertifikaten.


## Vorbemerkung

Der Autor ist ein starker Befürworter Freier Software und richtet sich an ein gleichgesinntes Publikum. Vor diesem Hintergrund ist auch die im folgenden deutlich formulierte Kritik einzuordnen.
Der Text geht nicht darauf ein, *warum* die Förderung Freier Software erstrebenswert ist, siehe dazu (bezogen auf den Hochschul-Kontext) <https://fsfw-dresden.de/programm>.
Der Beitrag ist stark inspiriert durch [Colin Percivals Plan für Open Source Software Maintainer](http://www.daemonology.net/blog/2017-05-11-plan-for-foss-maintainers.html) und Diskussionen im [FSFW-Plenum](https://fsfw-dresden.de#plenum).


## Bestandsaufnahme

Ausgangslage: Mit zunehmend fortschreitender Digitalisierung wird Software privat und beruflich immer wichtiger.
Freie quelloffene Software ist über 30 Jahre nach Gründung der Free Software Foundation und 20 Jahre nach Etablierung des eher „business-orientierten“
Konzeptes *Open-Source* für Endbenutzer*innen dabei immer noch (oder mehr denn je) ein Nischenprodukt.
Gründe sind einerseits mangelnde Bekanntheit der Produkte und ihrer Vorteile, andererseits aber auch Qualitätsfragen wie Usability-Schwächen, fehlende Features, Stabilitätsprobleme und fehlende bzw. veraltete Dokumentation.

Mit freien dezentralen Diensten (z.&#x202F;B. [Jabber-Server](https://wiki.fsfw-dresden.de/doku.php/doku/software/jabber) als Ersatz für WhatsApp) verhält es sich ähnlich.
Der Einfachheit halber geht der folgende Text aber hauptsächlich auf Desktop-Applikationen ein.


### Warum ist proprietäre Software meist verbreiteter und in den genannten Punkten oft qualitativ besser?
Das Geschäftsmodell (Verkauf von Software und/oder Daten) generiert Einnahmen. Dafür kann Arbeitskraft und Aufmerksamkeit eingekauft werden.

### Warum funktioniert das bei Freier Software so nicht?
Ein wesensbestimmendes Merkmal Freier Software ist, dass niemand von der Nutzung ausgeschlossen ist.
Ein Hersteller könnte zwar Freie Software verkaufen, muss aber davon ausgehen, dass Kunden das Produkt weitergeben - was die freie Lizenz ausdrücklich erlaubt.
Praktisch ist der Verkauf (im Sinne von „Ermöglichung der Nutzung als Gegenleistung für die Bezahlung“) von Freier Software allein also kein tragfähiges Geschäftsmodell. Dadurch ist es deutlich schwieriger, Einnahmen zu generieren.

### Warum funktioniert das Konzept „Freie Software“ dann überhaupt?
Weil für manche Menschen/Organisationen nicht nur kurzfristige Nutzenmaximierung handlungsleitend ist.
Konkrete Quellen von Ressourcen sind 1. Arbeit an Freier Software als Hobby (Sinnstiftung durch Problemlösen, Zusammenarbeit mit anderen, Anerkennung durch positives Feedback), 2. Demonstration eigener Fähigkeiten (z.&#x202F;B. für Bewerbungsverfahren) 3. Lerneffekt, 4. auf Grund von konkretem Eigeninteresse durch Unternehmen oder öffentliche Einrichtungen bezahlte Entwicklung ([z.&#x202F;B. im Hochschulkontext](https://fsfw-dresden.de/2018/06/interview-sander-finanzierung-freie-software.html)), 5. Spenden (Altruismus oder zukunftsorientiertes Eigeninteresse) und 6. tragfähige kommerzielle [Geschäftsmodelle](https://en.wikipedia.org/wiki/Business_models_for_open-source_software) (z.&#x202F;B. Verkauf von Support und Anpassungen).

Fakt ist aber: In den allermeisten Projekten fehlt es an Ressourcen für eine wünschenswerte Weiterentwicklung.
Mit anderen Worten, obige Quellen von Ressourcen sind nicht ausreichend.


## Analyse existierender Geschäftsmodelle

Wikipedia listet insgesamt [18 Geschäftsmodelle](https://en.wikipedia.org/wiki/Business_models_for_open-source_software)
für „Open-Source-Software“ auf (Stand Juni 2018). Einige davon kommen für nachhaltige Endanwender-Applikationen nicht in Frage z.&#x202F;B. „open sourcing on end-of-life“ oder „dual-licensing“. Andere stehen zumindest im Konflikt mit dem Ziel die bestmögliche Freie Software (inkl. selbsterklärender Doku) zu bekommen, z.&#x202F;B. „delayed open-sourcing“ oder „Verkauf von Support“.


Von den gelisteten Geschäftsmodellen verbleibt dann die knappe Hälfte:

1. Selling of branded merchandise
2. Selling of certificates and trademark use
3. Partnership with funding organizations
4. Voluntary donations
5. Bounty driven development
6. Pre-order/crowdfunding/reverse-bounty model
7. Crowdsourcing
8. Advertising-supported software

Der folgende Ansatz versucht diese Modelle zu kombinieren.

## Ideenskizze zur Kombination einiger dieser Methoden

### Vorbemerkung
Die obige Formulierung „Voluntary donations“ legt nahe, Zahlungen zu leisten „entgegen der ökonomische Vernunft“ und allein aus „irrationalem Altruismus“.
In vielen anderen Bereichen sind Menschen aber bereit, erhebliche Mittel „gegen die ökonomische Vernunft“ auszugeben, Stichworte: Markenbewusstsein und Statuskonsum.
Zudem kann, wie oben schon erwähnt, die finanzielle Unterstützung eines Projektes von dem man individuell profitiert, auch mit zukunftsorientiertem Eigeninteresse begründet werden.


### Beschreibung des Kombinationsmodells
Es gibt eine Organisation (Arbeitstitel: „Funding Freedom Initiative“ (FFI)).
Bei dieser haben sich alle an Finanzierung interessierten FLOSS-Projekte registriert und haben ein „Konto“.

Als Endbenutzer\*in *kauft* man ein Free-Software-Support-Zertifikat (Bronze, Silber, Gold, Platin (z.&#x202F;B. 10, 30, 100, 200 Cent pro Tag)).
Mit dem so eingenommen Geld, werden Projekte unterstützt und (zu einem kleinen Teil) der Verwaltungsaufwand finanziert.

#### Warum sollten Menschen für sowas Geld ausgeben?

1\. Man unterstützt Freie Software („Voluntary Donation“).
2\. Man bekommt (optional) Merchandise-Material („Selling of branded merchandise“), z.&#x202F;B. Aufkleber oder ein *schickes* T-Shirt. Zusätzlich sind „virtuelle Accessoires“ denkbar, also z.&#x202F;B. Badges für GitHub oder andere soziale Netzwerke. Das geht in Richtung Statuskonsum bzw. [Distinktionsbedürfnis](https://de.wikipedia.org/wiki/Distinktion_(Soziologie)).
3\. Man bekommt privilegierten Kommunikationskanal ins Projektteam (z.&#x202F;B. höhere Priorität bei Feature-Wunsch-Abstimmungen (Bounty driven development) oder Support-Anfragen)
4\. Man bekommt ggf. kleine extra-Features (Für Projekte, die das wollen).

#### Wie erfolgt die Verteilung des Geldes?

Abgerechnet wird in bestimmten Intervallen (z.&#x202F;B. pro Quartal).
Der Zertifikatspreis wird in vier Kategorien (K1-K4) aufgeteilt:

**K1 (z.&#x202F;B. 60&#x202F;%)** wird nach individuellen Käufer-Wünschen auf die Projektkonten verteilt. Als Entscheidungshilfe wird eine Software angeboten (opt-in), die lokal das Nutzungsverhalten analysiert und Vorschläge für die Verteilung macht. Die Prämisse dabei ist: Häufig laufende Programme sind subjektiv wichtiger. Vorbild: [Debian Popularity Contest](https://popcon.debian.org/). Man kann aber unabhängig von diesen Vorschlägen beliebige Projekte unterstützen.

**K2 (z.&#x202F;B. 30&#x202F;%)** werden nach Einschätzung der Organisation auf die Projektkonten verteilt. Die Annahme dabei ist: Die FFI hat besseren Überblick über die Projekte und kann ggf. auch strategisch Projekte mit Potential fördern, die noch nicht hinreichend bekannt sind.

**K3 (z.&#x202F;B. 10&#x202F;%)** sind Betriebskosten (Personal und Infrastruktur der FFI)


**K4** sind Materialkosten (für T-Shirts etc.) und werden zusätzlich berechnet. Einen Aufkleber gibt es auf Wunsch aber „gratis“. ;-)

#### Wie wird Veruntreuung verhindert?

Die Zuteilung der Gelder wird „crypto-transparent“ veröffentlicht:

Beim Bezahlen bekommt man einen Token mitgeteilt. Alle verkauften Support-Zertifikate werden veröffentlicht, inkl. der folgenden Daten: Token, Gesamtsumme (K1 + K2 + K3) und K1-Zuteilungsschema. Dadurch kann jede\*r Käufer\*in sich überzeugen, ob das eigene Zertifikat korrekt in der Gesamtbilanz enthalten ist (partielle Geldflüsse) und auch jedes Projekt kann sich überzeugen, dass es alle zustehenden Zahlungen erhält. Zudem können sich alle überzeugen, dass die Gesamtbilanz aufgeht. Die FFI kann sich vor Anschuldigung der Unterschlagung schützen, da alle verkauften Zertifikate signiert sind.

#### Was passiert mit dem Geld bzw. durch das Geld?

Die registrierten Projekte können sich das Geld a) auszahlen lassen oder b) transparent an andere Projekte weiterleiten (z.&#x202F;B. zu Libs von denen sie abhängen). Formal gesehen sind es Spendengelder. Die Verwendung (und Versteuerung) liegt in der Verantwortung der Empfänger\*innen.

Die Projekte verpflichten sich bei der Registrierung regelmäßig einen Bericht zur Verwendung der Gelder zu veröffentlichen. Mögliche Beispiele könnten folgendermaßen aussehen:

- „Konnte es mir leisten, meine Wochenarbeitszeit zu reduzieren und mehr Zeit in Projekt XYZ zu investieren.“
- „Von dem Geld wurden eine Anzeigenkampagne (Print- und Online) bezahlt. Die Downloadzahlen haben sich in dem Zeitraum verdreifacht. Wir wollen das wieder machen.“
- „Durch das Geld konnten wir zwei Mitarbeiter\*innen aus unserem Usability Team zu je 20&#x202F;% Vollzeit auf das Projekt ansetzen. Und eine studentische Hilfskraft hat die Doku aktualisiert.“
- „Wir haben Firma XYZ beauftragt, Issue 123 zu fixen. Für die Zukunft planen wir das gleiche mit Issue 456.“
- „Ich sehe das Geld als Anerkennung für die im letzten Jahr geleistete Arbeit. Danke Leute!“ (Ähnelt dem Bounty-Modell, siehe oben.)
- „Im letzten Quartal wurden hauptsächlich Issues bearbeitet, die von Spender\*innen hoch bewertet wurden. Details: siehe Release-Notes.“ (Entspricht dem Reverse-bounty-Modell.)

#### Wird dafür eine eigene (neue) Organisation gebraucht?

Für einzelne Projekte ist der Fundraising Aufwand meist zu groß.
Das spricht für eine *separate* Organisation. Eine solche muss aber nicht notwendigerweise neu gegründet werden. Ggf. könnte eine bestehende Organisation (naheliegend: Free Software Foundation, FSFE) die Idee umsetzen. Durch den einkalkulierten Betriebskosten-Anteil könnte sich das Projekt selbst tragen - innerhalb einer größeren Organisation oder ggf. sogar als klassisches StartUp mit Risiko-Kapital. Eine eigene neue Organisation wäre vermutlich *agiler* als eine etablierte mit gewachsenen Strukturen und interner Meinungspluralität. Dem steht der Nachteil gegenüber, dass sie unbekannt wäre und sich Vertrauen erst mühsam erarbeiten müsste. Denkbar wäre auch, dass mehrere etablierte Organisationen gemeinsam eine neue anschieben bzw. deren Gründung durch ihre Netzwerke unterstützen.

#### Potentielle Kritikpunkte und mögliche Gegenargumente

- *Es gibt schon ähnliche Versuche (siehe untenstehende Links) ohne durchschlagenden Erfolg.*
    - Diese Versuche sind ähnlich, aber nach aktueller Kenntnislage doch hinreichend anders.
    Außerdem braucht es für manche gesellschaftliche Innovationen auch mehrere Anläufe.
- *Eine Kritische Masse wird benötigt.*
    - Die ließe sich durch ausreichend Marketing herstellen. Das Budget dafür könnte aus Crowdfunding oder öffentlicher Förderung stammen.
- *Kommerzialisierung schadet der FLOSS-Entwicklung.*
    - Auch jetzt gibt es schon Geld-Ströme (z.&#x202F;B. Google-Summer-of-Code, Bounties, ...).
    Es geht darum, berufliche Perspektiven im FLOSS-Bereich zu schaffen.
- *Registrierung und Bezahlprozess sind zu aufwendig.*
    - Das kommt auf die Umsetzung an und außerdem nehmen FLOSS-Nutzer\*innen ggf. auch etwas Unbequemlichkeit in Kauf
- *Das Konzept baut zu sehr auf Vertrauen und Freiwilligkeit -> Gefahr geringer Akzeptanz.*
    - FLOSS lebt schon jetzt zum großen Teil von Freiwilligkeit. Viele Nutzer*innen würden gerne etwas zurückgeben, wissen aber nicht wo und wie. Zudem funktioniert Freiwilligkeit in anderen Bereichen auch (z.&#x202F;B. [Atmosfair](https://www.atmosfair.de/de/)). Weiterhin steht es jedem Projekt frei, „dezente Erinnerungsmechanismen“ an Spendenmöglichkeit einzubauen, die still sind, wenn ein aktuelles Zertifikat gefunden wird. Wen das stört, kann den Mechanismus rauspatchen oder das Projekt forken. Beides sind etablierte FLOSS-Abläufe.
- *Es könnte auf Grund der positiven Rückkopplung (siehe unten) zu einem Verdrängungswettbewerb und zu einer Einschränkung der Angebots-Vielfalt kommen.*
    - Gegenthese: Da „Feindliche Projektübernahmen“ anders als bei Unternehmen bei FLOSS-Projekten nicht möglich sind, ist eher von einer Ausweitung des Angebots auszugehen: Wirtschaftlicher Erfolg einzelner Projekte könnte potentielle Wettbewerber um so mehr motivieren.
- *Es ist unklar, wie man mit Projekten umgeht, die andere Ressourcen-Quellen haben (Mozilla, Linux-Kernel, ...)*
    - Das können die Nutzer\*innen z.&#x202F;B. auf Basis der oben erwähnten Berichte selbst entscheiden.
- *Durch die Zentrale Rolle der FFI könnte es langfristig eine unerwünschte Abhängigkeit bestimmter Projekte von der FFI geben.*
    - Registrierte Projekte können natürlich eine Möglichkeit zum Direkt-Spenden vorsehen, oder anderweitig Geld einwerben. Darüber hinaus können Menschen, die der Meinung sind, das Projekt sei zu groß (Machtkonzentration), es forken (Dank [AGPL](https://en.wikipedia.org/wiki/Affero_General_Public_License) etc.). Zu guter Letzt sollte klar sein, dass Datensparsamkeit und Transparenz zentral in der Umsetzung beachtet werden müssen. Es geht nicht darum Daten zu erheben und zum eigenen Vorteil zu nutzen, sondern eine Möglichkeit zu bieten,  FLOSS-Projekte zu fördern.

#### Potentielle positive Effekte

1. Es gäbe eine positive Rückkopplung: Qualität steigt -> Anzahl der Nutzer*innen steigt -> Anzahl der verkauften Zertifikate steigt -> Verfügbare Ressourcen steigen ->  Qualität steigt -> usw.
2. Mit guter Freier Software könnte man tatsächlich ordentlich Geld verdienen. Es ergäben sich bessere berufliche Perspektiven für Fans Freier Software.
3. Es gäbe die Möglichkeit eines opt-in-Kommunikationskanals von Entwickler\*innen zu Anwender\*innen: Wenn man für ein Projekt Geld gespendet hat, ist man bestimmt auch bereit, an einer Umfrage teilzunehmen.
    -> Mehr Identifikation zwischen Nutzer*innen und Projekt.
4. Man könnte Freie Software verschenken (z.&#x202F;B. Zertifikats-Abo. + T-Shirt). Das wäre auch aus [Nachhaltigkeitssicht](https://bits-und-baeume.org/ziele/de) ein sinnvolles Geschenk (hoher immaterieller Anteil).

### Kurze Überschlagsrechnungen zur Wirtschaftlichkeit


**Bottom-Up**: Ab 1000 Leuten (100 Euro täglich), die mitmachen, könnte man jeden Tag einen (kleinen) Bug fixen lassen. Ab da wäre es sinnvoll (ehrenamtlich). Ab 10K Leuten (100 Euro Betriebskosten täglich) könnte Konzept als StartUp überleben.

**Top-Down**: Es gibt geschätzt weltweit 1 Mrd. PCs in Betrieb. Als Proxy-Schätzwert für überzeugte FLOSS-Nutzer\*innen dient der Marktanteil von Linux als Desktop-Betriebssystem. Er beträgt 1.3&#x202F;% (Quelle: [statista.com](https://de.statista.com/statistik/daten/studie/157902/umfrage/marktanteil-der-genutzten-betriebssysteme-weltweit-seit-2009/)).
Von diesen würden geschätzt 10&#x202F;% ein Zertifikat für Durchschnittspreis von 10 Cent pro Tag kaufen.
Das ergibt 10^9 (Anzahl der PCs) * 0.013 (Linux-Marktanteil) * 0.1 (Kaufbereitschaftsquote) * 0.1 (Euro / Tag) = **130K Euro pro Tag** für Investitionen in das FLOSS-Ökosystem. Je nach Weltregion sind das zwischen 100 und 1000 Vollzeit-Stellen.

Beide Rechnungen zeigen, dass das ganze 1. nicht komplett utopisch ist und 2. theoretisch großes Potential hat.


Anmerkung: Wenn es gelänge, den App-Markt auf mobilen Endgeräten einzubeziehen, wäre der Kuchen nochmal deutlich größer (und ein kleineres Stück davon würde reichen).

## Ausweitung auf dezentrale IT-Dienste
Genau wie die Entwicklung guter Freier (Desktop-)Software, verursacht auch der Betrieb von freier dezentraler IT-Infrastruktur Aufwand und Kosten.
Die Situation ist strukturell ähnlich zu FLOSS-Software und die gesellschaftliche Bedeutung ist langfristig ggf. sogar größer.
Bisherige Geschäftsmodelle basieren oft auf dem Verkauf von Daten. Das ist aus vielen Gründen nicht erstrebenswert.
Beispiele für Bedarf an Finanzierung (digitale Infrastruktur für eine lebendige Zivilgesellschaft):

- Betrieb und Wartung freier dezentraler Alternativen zu Dropbox, Trello, Google docs, Skype, WhatsApp, Doodle, Polldaddy etc.
- Server für Wikis, Etherpad, Mailinglisten, Jabber
- Soziale Netze (Diaspora, Mastodon)

Natürlich besteht auch bei der Infrastruktur-Software teils erheblicher Entwicklungsbedarf (laut FSFW-Infrastruktur-Haufen z.&#x202F;B. bei Etherpad). Auch dieser ließe sich ggf. durch die FFI finanzieren.

## Wie gehts weiter?

Text ist geduldig. Damit etwas passiert, braucht es meist menschliche Aktivität.
Klar ist: So ein Projekt sollte man nur in Abstimmung mit der FLOSS-Community anfangen und deswegen ist der erste Schritt: [Feedback](mailto:kontakt@fsfw-dresden.de) einholen.
Kritik (Prinzipielle Denkfehler?, Unrealistische Annahmen?, „Konkurrenzprodukt“?) und Zuspruch sind beide gleich wichtig.
Die Erfahrung zeigt dabei: Kritik kommt meist von alleine :-).

Sollte es hinreichend viel positives Feedback geben, eventuell sogar Unterstützungszusagen, könnten die nächsten Schritte angegangen werden:
Namen überlegen und Domains sichern, Konzept präzisieren und ins Englische übersetzen, Feedback im größeren Rahmen einholen (NGOs, Distributoren, Reddit, Mailinglisten, Jurist\*innen), Infrastruktur aufsetzen, Crowdfunding-Kampagne starten, ...

Nicht desto trotz: [Feedback](mailto:kontakt@fsfw-dresden.de) bleibt der erste Schritt.

## Zusammenfassung

Wer gute FLOSS-Software will, sollte bereit sein, dafür auch etwas zu tun bzw. zu bezahlen.
Die „Funding Freedom Initiative“ ist ein Vorschlag zur kooperativen Verteilung von monetärer Anerkennung.
Feedback an [kontakt@fsfw-dresden.de](mailto:kontakt@fsfw-dresden.de).

Zur Verbreitung dieses Beitrags kann bei Bedarf der Tweet <https://twitter.com/fsfwdresden/status/1029988144949731328> genutzt werden.


## Potenziell relevante Links

- <http://www.daemonology.net/blog/2017-05-11-plan-for-foss-maintainers.html>
- <https://liberapay.com/>
- <https://freedomsponsors.org/>
- <https://www.bountysource.com/>
- <https://snowdrift.coop/>
- <https://opencollective.com/>
- <http://goteo.org/>
- <https://gitcoin.co/>
- <https://gratipay.com/> (Betrieb eingestellt)
- <https://patreon.com>
    - Hat [offenbar keine](https://learn.patreon.com/build/selecting-a-creator-category/) Kategorie speziell für (freie) Software.
    - Ist nicht auf Offenheit und Datensparsamkeit etc. getrimmt (Login mit Facebook, AGPL?).
- <https://opensourcefriday.com/>
- <https://www.codetriage.com/> (Versendet neues offenes Issue jeden Tag)
- <https://www.unixstickers.com/>
- <https://creativecommons.org/use-remix/made-with-cc/>
- <https://sandstorm.io/news/2014-07-21-open-source-web-apps-require-federated-hosting>
- <http://www.fossfactory.org/> („Funding Open collaboration“, scheint inaktiv)
- <https://store.kde.org/browse/ord/top/#plings> Monetarisierung für Icons, Themes etc.
- [GNU Taler](https://taler.net/en/) (Elektronisches Bezahlsystem, evtl. für Umsetzung oder gemeinsame Kampagne im Auge behalten.)

## Beispiele für spendenfinanzierte Infrastruktur

<https://uberspace.de/prices>, <https://riseup.net/de/spenden>, <https://www.zwiebelfreunde.de/>,
