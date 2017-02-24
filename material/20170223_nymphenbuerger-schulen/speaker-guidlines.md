# Speaker guidlines
CMS Talk für den Studientag am Donnerstag den 23.02.2017 in den [Nymphenburger Schulen München](http://www.nymphenburger-schulen.de/).

## Chapter: CMS / CCC
Sehr kurze Einführung in die Ziele der CMS Initiative und Vorstelung des CCC.

## Chapter: Hack
### Beschreibung
Es wurde ein Raspberry Pi als WLAN AP mit der SSID "nymph_fast" aufgestellt. Die Website der Schule wurde abgezogen und auf dem Rasspberry Pi gelegt. Die Kopie der Website wurde um einen Fake-Beitrag zum Thema Flüchtlinge erweitert. Auf dem Raspberry PI wurde ein DNS konfiguriert, welcher die Domain http://www.nymphenburger-schulen.de/ auf die Kopie der Website auf dem Raspberry PI leitete. Alle anderen DNS Request wurden an einen Forwarding DNS weitergeleitet. Der Raspberry wurde per iptables als Router konfiguriert. <br/>
Der Speaker geht auf die Infrastruktur der Schule mit eigenem WLAN (nymphlan) ein und weißt auf die SSID nymph_fast hin. Im Anschluss daran wird auf die Website eingegangen und der Fake-Beitrag gezeigt.

### Ziele
* Aufmerksamkeit bekommen.
* Audience aufmerksam machen, dass man sich nicht in jedes WLAN einlogt => Konsequenzen
* Fake-Beitrag: Nich alles glauben, was "jemand" ins Internet geschrieben hat
* Überleitung zu dem Beitrag Fake-News

## Chapter: Fake-News
### Ziele
* Sensibilisierung für das Thema
* Wie kann man Fake-News erkennen bzw. wie recherchiere ich
* Keine Fake-News weiterleiten

## Chapter: https
### Beschreibung
* Kurze Demonstration der Cäsar-Verschlüsselung
* MITM Demonstration anhand von Kontaktformulare (http vs. https)
	* [http://www.nymphenburger-schulen.de/kontakt.html]
	* [https://www.zeiss.de/messtechnik/website/contact-form.html]
* Beispiel eines falschen Zertifikates
	* [https://www.callkate.org]

### Ziele
* Sensibilisieren für verschlüsselte Kommunikation - keine Personenbezogene Daten ohne SSL übertragen
* Wie erkennt man SSL Websites
* Überprüfung der Echtheit einer Website anhand eines Zertifikates

## Chapter: Was kosten SoMe Dienste
### Ziele
* Bei kostenlosen Diensten zahlt man mit seine eigenen Daten
* Ist der Dienst das für mich Wert
* Datensparsamkeit

## Chapter: Password
### Ziele
* Passwort soll keine Details aus dem Leben beinhalten
* Passwort soll nicht auch „echten“ Wörtern bestehen
* Nutzt für jeden Dienst ein eigenes Passwort
* Benutzt einen Passwort Safe
