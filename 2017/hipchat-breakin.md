Title: Datenklau bei HipChat – Cloud und Gesellschaft
Date: 2017-04-30
Category: Artikel
Tags: HipChat, Datenklau, Cloud, Slack, SaaS
Slug: datenklau-bei-hipchat-cloud-und-gesellschaft
Author: cookie
Summary: Am 24. April gab der SaaS-Anbieter Atlassian bekannt, dass Kundendaten des eigenen Chat-Tools HipChat entwendet worden seien. Dieser Vorfall ist ein gutes Beispiel für Risiken von Cloud-basierten Kommunikationstools. Wir möchten die Gelegenheit nutzen auf andere vergleichbare Tools aufmerksam zu machen und den Zwischenfall in einen größeren Rahmen einzubinden.

Am 24. April 2017 gab der SaaS-Anbieter Atlassian bekannt, dass Kundendaten des eigenen
Chat-Tools HipChat entwendet worden seien. Dieser Vorfall ist ein gutes Beispiel
für Risiken von Cloud-basierten Kommunikationstools. Wir möchten die Gelegenheit
nutzen auf andere vergleichbare Tools aufmerksam zu machen und den Zwischenfall
in einen größeren Rahmen einzubinden.

HipChat ist eine sog. SaaS, d.h. Software as a Service, betrieben von der Firma
Atlassian, welche unter anderem auch für das Ticketsystem Jira und die
Wikisoftware Confluence bekannt ist. Anmerkung: HipChat ist auch als Software für eigene Server verfügbar. Hierzu wird
die Software bei Atlassian lizenziert, kann aber auf einem eigenen Server installiert
werden. Dieser Artikel nutzt die Cloud-Variante als Beispiel – stellvertretend
für andere Tools, welche nur als SaaS verfügbar sind (z.B. Slack).

## Was ist SaaS?
SaaS bedeutet, dass die genutzte Software -
hier eine Weboberfläche zum Chatten - auf den Servern eines Anbieters betrieben
wird und man selbst keine Infrastruktur betreiben muss. In den meisten SaaS-Modellen bezahlt man beispielsweise pro Monat pro Nutzer
oder kauft Pakete für eine gewisse Anzahl von Nutzern. Darüber hinaus gibt es bei vielen
Produkten mehrere Editionen, die verschiedene Features beinhalten bzw. mehr Features hinzufügen.

Brauche ich für mein Team von fünf
Entwicklern z.B. nur eine einfache Chatoberfläche, buche ich ein kleines Paket.
Benötige ich aber nun für meine 100 Entwickler unterschiedliche Chaträume, dazu eine
Anbindung an mein Ticketsystem und zum Schluss auch noch Support durch Atlassian,
brauche ich ein wesentlich größeres (und teureres) Paket.

Atlassian ist hier ein sehr gutes Beispiel für eine umfangreiche SaaS-Plattform,
da ein Atlassian-Account in allen Produkten der Firma
wiederverwendet werden kann – sowohl für HipChat, als auch Jira und andere. Dies erleichtert
die gegenseitige Integration der Tools. Die einheitliche Verwaltung der Nutzer und deren Gruppen erzeugt nebenbei
einen Anreiz für Administratoren, innerhalb der Produktfamilie zu bleiben.

## Und was hat das nun mit dem Datenklau zu tun?
Die Erläuterung zu SaaS ist deshalb hilfreich, weil hier nun klar werden sollte
wo die Daten – Chats, Benachrichtigungen, Accounts – meiner Firma am Ende lagern:
beim Anbieter. Der Nutzer der Software muss sich in diesem Falle darauf verlassen,
dass der Anbieter

*  die Daten [gegen Verlust absichert][gitlab-db-incident],
*  nicht unbefugt [die Daten weiterverwertet][whatsapp-fb-sharing],
*  verhindert, dass Dritte die [Daten missbrauchen][datenreichtum],
*  seine Systeme [gegen fremden Zugriff schützt][sec-note],
*  ggf. eine Methode zum [Export eigener Daten][vendor-lockin] bereitstellt.

Diese Dinge sind rechtlich durch Verträge (Nutzungsbedingungen, AGB) mehr oder weniger
geklärt.

Jedoch verhindert Text auf Papier nicht, dass destruktive Zwischenfälle nun doch passieren.
Kommt es zum Ausfall einer Plattform hilft kein Service-Level Agreement (SLA),
mit welchem der Anbieter seine Zuverlässigkeit gegenüber dem Kunden verspricht.
Dann sind die Systeme halt aus, nicht erreichbar oder in sonstigen Zuständen – der
Kunde hat hier keine Eingriffsmöglichkeiten. Es bleiben lediglich rechtliche
Schritte, wie Rückzahlungen oder Entschädigungen. Steht das eigene Geschäft aber wegen
Ausfall für mehrere Tage still, ist ein unverschuldeter finanzieller Verlust beim Kunden unumgänglich.

Noch schlimmer als ein Ausfall ist ein rufschädigender Verlust von
Kundendaten des eigenen Betriebs. Nutzt eine Firma z.B. ein Cloud-basiertes CRM-System
zur Verwaltung von Kunden und Aufträgen, und die Kundendaten dieser SaaS-Plattform
werden entwendet und auf einem Schwarzmarkt verkauft, ist schnell der Kunde
des SaaS-Produkts (die Firma) Ziel von Kritik. Ob diese Kritik gerechtfertigt ist oder nicht ist
eine weiterhin offene, sehr polarisierende Diskussion in der IT-Welt.

## Alternativen zur Cloud
Wie also könnte man die Probleme zentralisierter Systeme lösen? Welche Optionen
bieten sich mir als Kunde, wenn ich nicht die Ressourcen habe, eine eigene Infrastruktur
zu betreiben?

Beginnen wir mit dem offensichtlichsten Ansatz: wir holen die Software, welche
wir in unserem Alltag brauchen, wieder ins Haus. D.h. praktisch umgesetzt: eine Firma betreibt
im Keller oder bei einem vertrauten Serveranbieter eigene Server, auf welchen
Softwarepakete laufen und die Daten der Dienste gespeichert werden. Im privaten
Bereich bedeutet dies, dass ich dezentrale Software – z.B. [Jabber][xmpp],
[Diaspora][diaspora], [Mastodon][mastodon], [Rocket.chat][rocketchat], [Mattermost][mattermost],
[Kanboard][kanboard] oder [WebRTC][palava] – verwende und zentrale Dienste ersetze.

Leider bringt dies Arbeit und unter Umständen zusätzliche Kosten für Dienstleistungen
mit sich. Die Software muss installiert und gewartet,
die Server-Software regelmäßig aktualisiert und der Betrieb abgesichert werden.
Da gerade kleinere Firmen und Privatpersonen dies oft zeitlich nicht stemmen können,
hilft es, sich in Gruppen zusammen zu schließen. Dies bedeutet z.B., dass ein
paar Menschen zusammen einen Server mieten und darauf Chat-Software für diese
Gruppe und weitere Freunde betreiben. Das Modell könnte man auch auf Firmen
erweitern. Hierzu können sich Firmen zusammenschließen und jede reserviert einen Teil
der eigenen IT-Kapazitäten für den gemeinsam betriebenen Dienst. Beispiele für
kollektiv betriebene IT-Infrastruktur sind z.B. [das Datenkollektiv](https://datenkollektiv.net/)
und [IN-Berlin](https://in-berlin.de/verein/).

Hier geht es um Punkte wie Vertrauen, Zuverlässigkeit und Verantwortungsbewusstsein.
Dinge, die sowieso zu einer funktionierenden Gesellschaft gehören sollten, erweitert
auf praktische Umsetzung von IT-Infrastruktur.

Zentrale Plattformen wie Facebook oder auch Atlassian sind so groß und
beliebt, weil sie sehr einfach
bedienbar und ohne eigenen Aufwand verwendbar sind. Aber dieser Komfort
hat seinen Preis – besonders wenn für die Nutzung keine Kosten beim Kunden entstehen.
**Wenn der Dienst sich nicht durch Nutzungspreise finanziert,
müssen die Daten zu Geld gemacht werden**. Dies bedeutet z.B., dass Nutzungsdaten und
Profile der Werbeindustrie zur Verfügung gestellt werden oder dass große
Investmentfirmen mit riesigem Kapital Geld aufbringen, um Daten zu sammeln und
sie für politische Zwecke zu nutzen. Es gibt natürlich auch hier Ausnahmen, wie
Wikipedia, die sich auf Spendenbasis finanzieren.

Wenn man nun eigene Infrastruktur betreibt und die Daten der Nutzer die eigenen
Server nicht verlassen, können diese auch nicht verkauft oder missbraucht werden.
Und dafür lohnt sich der zusätzliche Aufwand allemal! Wer will schon eigene
[private Bilder frei im Netz][fappening] kursieren sehen?
Oder [Passwort-Datenbanken][leak-linkedin]? Oder
[gekaperte E-Mail-Konten][yahoo-hack]?

## Wer ist nun schuld? Der Nutzer oder der Anbieter?
Zu gerne würde man an dieser Stelle den schlechten Zustand unserer Technologie
auf die Konsumenten schieben. Denn am Ende halten sich auf dem Markt nur
Produkte, die von Kunden auch nachgefragt werden. Und diese sind zur Zeit nun
mal überwiegend datenschutzfeindlich. Es geht sogar so weit, dass die großen
Plattformen [mehr und mehr an politischem Gewicht gewinnen][denmark-digital-ambassador].
Und das alles, obwohl seit Jahren davor gewarnt wird, welche Macht
[die Anhäufung von Daten][vds-spitz] haben kann!

„Halt, stopp!“, rufen Menschen denen man solche Dinge an den Kopf wirft – zu Recht!
Diese Vorwürfe sind natürlich haltlos. **Die Abwelzung von Verantwortung ist
nämlich das eigentliche Problem.** Klar ist: jeder Mensch, der Dienste wie
Facebook, Slack oder WhatsApp nutzt, muss lernen welche Folgen dies
nach sich zieht. Es ist im 21. Jahrhundert einfach nicht mehr akzeptabel, als Bürger
einer Demokratie ein technisch ungebildeter Konsument zu sein.
Und das Problem wächst, je
technologisierter unser Alltag und unsere Arbeitswelt wird.

Aber wer steht nun in der Pflicht, Technologien gesellschaftlich akzeptabel und
nachhaltig zu gestalten?

Erstens: der Konsument bzw. Kunde eines Softwareprodukts. **Du machst durch deine
Wahl einen Unterschied, welche Software auf den Markt kommt und welche bleibt**. An
Beispielen wie MySpace und StudiVZ sieht man, dass auch große soziale Netzwerke
ihre Nutzer wieder verlieren können. Und sogar zu Facebook gibt es immer wieder
Meldungen, in denen [eine Verringerung der Nutzerzahlen][fb-decline]
prognostiziert wird.

Zweitens: der Anbieter und die Entwickler hinter einem Produkt! **Alle Menschen der
Softwareindustrie tragen [eine Verantwortung][iug]**. Jeder Schnippsel Code verändert
die Softwarelandschaft zum positiven oder negativen. Es ist im 21. Jahrhundert
einfach nicht mehr akzeptabel, dass Programmierer irgendwelche Tools auf Github
veröffentlichen, [die dann in Monopol- oder Militärsoftware integriert werden][defending-copyleft]!
Auch hier ist noch ein riesen Paket Aufklärungsarbeit zu leisten, um
Goldrauschprogrammierern ihre Mitverantwortung bewusst zu machen.

Die Informatik muss sich öffnen, aus der Blase hinaustreten und sich ihrer wachsenden
gesellschaftlichen Verantwortung  bewusster werden. Es ist schön, zu einem kleinen
Kreis Eingeweihter zu gehören und mit dem eigenen Wissen viel Geld machen zu
können – langfristig gesehen ist es aber fragwürdig, ob wir
[Algorithmen, die von einem homogenen Bruchteil der Bevölkerung entworfen wurden][ai-bias],
gesellschaftliche Prozesse anvertrauen wollen!

## Tja, und nu?
An dieser Stelle ist es schwierig einen Bogen auf das eigentliche Thema zurückzuschlagen.
Ich hoffe es ist ersichtlich, dass diese Diskussion sehr schnell größere Dimensionen
annimmt. Seit Urzeiten kann man bei jedem neuen Zwischenfall (Datenklau, weltweite
Systemausfälle, Missbrauch…) ein weltweites [Hand-gegen-Stirn-Klatschen]
[facepalm] hören – aber trotzdem bewegen sich die Dinge gefühlt schneller
in Richtung unsicherer Systeme.

Menschen sind genervt von Datenschutz-Diskussionen. Die Politik hält
Datenschutz (d.h. Verbraucherschutz!) und Software-Regularien für überholt,
die deutsche Wirtschaft sieht sich im Vergleich zum Silicon Valley im
Nachteil – und geht lieber Risiken ein, um schneller Produkte auf den deutschen
Markt zu bringen.

Aber ist das Aufsetzen von Scheuklappen zukunftsfähig?
Was passiert, wenn der Markt erstmal einen Punkt erreicht hat, an dem es keine
Rückkehr mehr gibt?
Wenn politische Systeme, die den einfachen Bürgern eigentlich ein Mitspracherecht
garantieren sollen, anhand von Datenanalysen gelenkt werden können?

Fakt ist: jeder der heute [Daten an Dienste sendet][spiegel-echo-look] und somit dem Anbieter
ermöglicht private Daten wirtschaftlich zu nutzen, zahlt nicht nur mit diesen, sondern legt Byte für
Byte den Weg in die eine oder andere Richtung. **Alle, die ein Softwareprodukt
nutzen geben implizit ihre Zustimmung** zur Art und Weise, wie dieser Dienst
funktioniert und handelt. Und welche Folgen sich daraus für die
Gesellschaft ergeben. Es ist keine gültige Ausrede, dass „es keine Alternative
gäbe“ oder gar Kritik geäußert würde, indem man auf Facebook Bilder mit „ich
widerspreche der Nutzung meiner Daten durch Facebook“ verbreitet. Im Gegenteil,
die Plattform interessiert das Null, aber man selbst ist verlockt zu denken etwas
getan zu haben.

Daher mein Appell: Menschen, die außerhalb der Softwareindustrie die Produkte nur nutzen wollen,
sollten – nein, müssen – genauer hinschauen!

Informiert euch über
[freie Software][fsfe], über [die Cloud und SaaS][stallman-saas], beim
[Bundesamt für Sicherheit in der Informationstechnik][bsi-fuer-buerger], beim
„[Forum InformatikerInnen für Frieden und gesellschaftliche Verantwortung][fiff]“ und
bei der „[Fachgruppe Informatik und Ethik][fg-ie]“ der Gesellschaft für Informatik.
Darüber hinaus gibt es eine Menge [Blogs][netzpolitik] und andere [Medien][heise-np],
die sich mit den Themen beschäftigen.

Ihr solltet eure Stimmen als Konsumenten nicht
unterschätzen – so lange ihr als Mensch Kunde seit, bestimmt **ihr**, welche
Produkte auf dem Markt sind und welche Firmen ihr unterstützt!




[sec-note]: https://blog.hipchat.com/2017/04/24/hipchat-security-notice/
[gitlab-db-incident]: https://about.gitlab.com/2017/02/01/gitlab-dot-com-database-incident/
[whatsapp-fb-sharing]: http://www.spiegel.de/netzwelt/apps/whatsapp-datenweitergabe-an-facebook-deutsche-verbraucherschuetzer-klagen-a-1132377.html
[vendor-lockin]: https://en.wikipedia.org/wiki/Vendor_lock-in
[datenreichtum]: https://datenreichtum.tumblr.com/
[denmark-digital-ambassador]: http://foreignpolicy.com/2017/01/27/denmark-creates-the-worlds-first-ever-digital-ambassador-technology-europe-diplomacy/
[vds-spitz]: http://www.zeit.de/digital/datenschutz/2011-02/vorratsdaten-malte-spitz
[iug]: https://de.wikipedia.org/wiki/Informatik_und_Gesellschaft
[facepalm]: https://www.youtube.com/watch?v=XZxzJGgox_E
[fappening]: https://de.wikipedia.org/wiki/Hackerangriff_auf_private_Fotos_von_Prominenten_2014
[leak-linkedin]: https://www.heise.de/security/meldung/LinkedIn-Passwort-Leck-hat-desastroese-Ausmasse-3210793.html
[yahoo-hack]: https://www.heise.de/security/meldung/Yahoo-muss-erneut-Massenhack-beichten-Eine-Milliarde-Opfer-3570674.html
[fb-decline]: http://www.rp-online.de/digitales/internet/facebook-auf-dem-absteigenden-ast-die-zahl-der-nutzer-sinkt-aid-1.5688742
[ai-bias]: https://www.theguardian.com/technology/2017/apr/13/ai-programs-exhibit-racist-and-sexist-biases-research-reveals
[spiegel-echo-look]: http://www.spiegel.de/netzwelt/gadgets/amazon-echo-look-aufregung-um-die-neue-alexa-kamera-a-1145052.html
[defending-copyleft]: https://lwn.net/Articles/675232/

[xmpp]: http://www.jabber.de/was-ist-jabber/
[diaspora]: https://de.wikipedia.org/wiki/Diaspora_(Software)
[mastodon]: https://mastodon.social/about
[rocketchat]: https://rocket.chat/
[kanboard]: https://kanboard.net/
[palava]: https://palava.tv/
[mattermost]: https://about.mattermost.com/slack-vs-mattermost/

[fsfe]: https://fsfe.org/about/about.de.html
[stallman-saas]: https://www.gnu.org/philosophy/who-does-that-server-really-serve.html
[bsi-fuer-buerger]: https://www.bsi-fuer-buerger.de/
[fiff]: https://www.fiff.de/about
[fg-ie]: https://fg-ie.gi.de/
[netzpolitik]: https://netzpolitik.org/
[heise-np]: https://www.heise.de/newsticker/netzpolitik/
