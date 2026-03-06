<!--

author:   Linda Zollitsch
email:    zollitsch@ub.uni-kiel.de
version:  0.1.0
language: de
narrator: UK English Female

icon:     images/Logo_cau-norm-de-lilagrey-rgb-0720_2022.png

link: style_css.css
  


comment:  This document provides a brief introduction to data storage and backup.

-->

# Datenumgang (Daten speichern und teilen) 💾



<script input="button">
alert("Disclaimer: Please note that you are leaving the CAU net once you open this presentation in your browser. This presentation includes links to other third party websites and services. These sites are not under our control. RDM@CAU is not responsible for the content of linked third party websites. Please be aware that the security and privacy policies on these sites may be different than CAU policies. Please read third party privacy and security policies closely.")

"Disclaimer"
</script>


<center><img src="./images/sharing_documents.png" alt="workshop, teaching" height="40%" width="40%"></center>


handling research data


> To see this document as an interactive LiaScript rendered version, click on the
> following link/badge:
>
> [![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/RDM4CAU/TtL-FDM/main/TtL-FDM_Workshop.md#1)
>
> If you have questions, please contact us: [Central Research Data Management](https://www.datamanagement.uni-kiel.de/de)
>
> This work is licenced under CCBY 
![ccby](./images/ccby.png) (https://creativecommons.org/licenses/by/4.0/)

## Ziele dieses Workshops 🎯

Lernende können ...

* ... allgemeine Anforderungen an Datenspeicherung benennen.
* ... den Unterschied zwischen Speicherung und Backup erläutern.
* ... Beispiele für Datenspeicherung benennen.
* ... Risiken der Datenspeicherung bewerten.


## Überblick

* Forschungsdatenlebenszyklus

* Datenspeicherung und Backup: Einführung

* Datenspeicherung in der CAU-Cloud


# Forschungsdatenlebenszyklus
<!---
Lernende können	Phasen des Forschungsdatenlebenszyklus	benennen. (LZ-ID: 01_005_0079)
--->

<img src="/images/FDM_Zyklus_klein_ohneText.jpg" width="350" align="right">

<P><SMALL>Illustration: Cleo Michelsen, basierend auf dem Forschungsdatenlebenszyklus des UK Data Service</SMALL></P>

<div style="page-break-after: always;"></div>

{{1}}
********************************************************************************

**Planung**:

* Auf welche Weise entstehen neue Daten?
* Werden Daten wiederverwendet?
* Welche Datentypen, im Sinne von Datenformaten (z. B. Bilddaten, Textdaten oder Messdaten in Tabellen) entstehen?
* Welche Analysen sind geplant?
* Welches Datenvolumen ist zu erwarten?
* Welche rechtlichen und ethischen Aspekte müssen berücksichtigt werden?
* Wer ist verantwortlich?

---

********************************************************************************

{{2}}
********************************************************************************

**Erhebung und Analyse**:

* Welche Ansätze werden verfolgt, um die Daten nachvollziehbar zu dokumentieren?
* Welche Maßnahmen werden getroffen, um eine hohe Qualität der Daten zu gewährleisten?
* Welche digitalen Methoden und Werkzeuge (z. B. Software) sind zur Nutzung und Analyse der Daten erforderlich?
* Auf welche Weise werden die Daten während der Projektlaufzeit gespeichert und gesichert?
* Wie wird die Sicherheit sensibler Daten während der Projektlaufzeit gewährleistet (Zugriffs- und Nutzungsverwaltung)?

********************************************************************************

{{3}}
********************************************************************************

**Archivierung & Veröffentlichung**:

* Welche rechtlichen Besonderheiten bestehen im Zusammenhang mit dem Umgang mit Forschungsdaten in dem Forschungsprojekt?
* Sind Auswirkungen oder Einschränkungen in Bezug auf die spätere Veröffentlichung bzw. Zugänglichkeit zu erwarten?
* Auf welche Weise werden nutzungs- und urheberrechtliche Aspekte sowie Eigentumsfragen berücksichtigt?
* Existieren wichtige wissenschaftliche Kodizes bzw. fachliche Normen, die Berücksichtigung finden sollten?

********************************************************************************


{{4}}
********************************************************************************

**Nachnutzung**:

* Welche Daten bieten sich für eine Nachnutzung besonders an?
* Nach welchen Kriterien werden Forschungsdaten ausgewählt, um diese für die Nachnutzung durch andere zur Verfügung zu stellen?
* Planen Sie die Archivierung Ihrer Daten in einer geeigneten Infrastruktur?
* Falls ja, wie und wo? Gibt es Sperrfristen?
* Wann sind die Forschungsdaten für Dritte nutzbar?

********************************************************************************

<div style="page-break-after: always;"></div>


# Datenspeicherung und Backup: Einführung 📝

<div style="float:right; width:40%;">
  <img src="/images/backup.png" alt="No back up? No mercy!">
</div>


{{0-1}}
****************
Wo und wie speichern wir unsere (Forschungs)Daten? 🗨️


****************

{{1-2}}
****************

- Eigener PC

- Mobiles Speichermedium 

    - USB-Stick

  - Externe Festplatte 

- Institutionelle Speicherorte

    - Cloud

  - Virtuelle Laufwerke

* Externe Speicherorte (Cloud eines Anbieters)

****************

## Vor- und Nachteile


{{1-2}}
****************

<!--
style="
  background-color: #fee1ff;
  stroke: #9a047f;" -->
``` ascii
+-----------------+
| Eigener PC      |            +-----------------+
+-----------------+            | Mobile          |
                               | Speichermedien  |
                               +-----------------+


+-----------------+                    +-----------------+                
| Institutionelle |                    | Externe         |
| Speicherorte    |                    | Speicherorte    |
+-----------------+                    +-----------------+
                   

```


****************

{{2}}
****************


``` ascii
+-----------------+---------------------------------------------+-----------------------------------------------+
|                 |                                             |                                               | 
| Speichermedium  |                 Vorteile                    |                  Nachteile                    |
|                 |                                             |                                               |
+-----------------+---------------------------------------------+-----------------------------------------------+ 
|                 | Verantwortung & Sicherheit bei einem selbst | bei Verlust keine Datenrettung möglich        | 
| Eigener PC      | maximale Kontrolle                          | kooperatives Arbeiten Schwierig               |
|                 |                                             |                                               |
+-----------------+---------------------------------------------+-----------------------------------------------+
|                 | leichter Transport                          | Verlust oder Diebstahl möglich                | 
| Mobile          | Aufbewahrung im Safe möglich                | Inhalte separat verschlüsseln, da sonst       |
| Speichermedien  |                                             | nicht geschützt                               |
+-----------------+---------------------------------------------+-----------------------------------------------+ 
|                 | Backup & Wartung wird übernommen            | Möglicherweise langsam                        | 
| Institutionelle | Datenschutz der Institution berücksichtigt  | Sicherheitsstrategien evtl. intransparent     |
| Speicherorte    |                                             |                                               |
+-----------------+---------------------------------------------+-----------------------------------------------+ 
|                 | Einfache Nutzung und Verwaltung             | Datenschutz unklar                            | 
| Externe         | Backup und Wartung vorhanden                | Abhängigkeit von einem Anbieter               |
| Speicherorte    |                                             |                                               |
+-----------------+---------------------------------------------+-----------------------------------------------+ 

```


****************

## Cloudlösungen ☁ 

{{1-2}}
****************

Beispiel Cloudlösung

<!-- data-type="none" -->
| Cloudanbeiter           | Herkunft  | Open Source | Datenspeicherung | DSGVO  |
| ----------------------- | --------: | -----------:| ----------------:| ------:|
| Dropbox                 | USA       | nein        | unbekannt        | (ja)   |
| OneDrive (Microsoft)    | USA       | nein        | unbekannt        | (nein) |
| iCloud (Apple)          | USA       | nein        | unbekannt        | (nein) |
| Nextcloud (CAU)         | EU        | ja          | EU               | ja     |


****************

{{2}}
****************
Beispiele von zertifizierten Cloudlösungen

https://www.trusted-cloud.de/cloud-service-suche.html 

****************


## Lebensdauer von Speichermedien ⚠️

> **Speichermedien haben unterschiedlich lange Lebensdauer**:

{{1-2}}
****************

<section class="flex-container">

<!-- class="flex-child-1" style="min-width: 350px; max-height:500px" -->
``` ascii
.--------------------.-------------.
| Speichermedium     | Lebensdauer |
|                    |  in Jahren  |
.--------------------.-------------. 

.--------------------+------+------.
| Externe Festplatte |   5  |  10  |
.--------------------+------+------. 
| Festplatte HDD     |   3  |   5  | 
.--------------------+------+------.
| Festplatte SSD     |   5  |  10  |
.--------------------+------+------. 
| SD-Speicherkarte   |  10  |  30  |
.--------------------+------+------.
| USB-Stick          |  10  |  30  |
.--------------------+------+------. 
| CD/DVD gebrannt    |   5  |  10  |
.--------------------+------+------. 
| CD/DVD gepresst    |  10  |  30  |
.--------------------+------+------. 
| Blu-ray            |  30  |  80  |
.--------------------+------+------. 

```

<!-- class="flex-child-2" style="background: lightgray; max-height:400px" -->
<img src="images\Lebensdauer.png">

</section>

****************

{{2}}
****************

in Abhängigkeit von:

* Temperatur
* Feuchtigkeit
* Beanspruchung
* Lagerung
****************

## 3-2-1 Regel

Mindestens 3 Kopien der Daten 📝 📝 📝

... auf mindestens 2 unterschiedlichen Speichermedien 💾 💽

... wovon mindestens 1 Kopie dezentral ist. ☁

Datenwiederherstellung zu Beginn sowie in regelmäßigen Abständen testen!

## Sensible Daten 🔒 

Besondere Aufmerksamkeit bei sensiblen Daten:

> **Schützen Sie sensible Daten!** 
>
>- Hardware (z. B. in einem abschießbaren Raum gelagert)
>- Dateiverschlüsselung
>- Passwortsicherheit
>- Mindestens zwei Personen sollten Zugang zu den Daten haben


## Backup vs. Langzeitarchivierung 📂 

| Back up                                                                          | Langzeit Speicherung            |
| -------------------------------------------------------------------------------- | ----------------------------- |
| Automatisches Backup von allen Daten   | Speicherung von ausgewählten Daten |
| All Versionen                                                                     | Nur die finale Version            |
|   zur Verhinderung von Datenverlust <br>(technisch, z.B. Defekt, oder menschlich, z.B. versehentlich gelöscht) | Integritätssicherung <br> (z. B. regelmäßige Überprüfung auf modifizierte oder beschädigte Daten, <br>Dateisystemkonsistenz)      |
|                                                                                  | Langzeitspeicherung             |
|                                                                                  | Durchsuchbar                 |



## Zusammenfassung 🦉

{{1}}
****************
**Risiken**❗️

Technische Defekte, Katastrophen (Unwetter), Diebstahl, Vergesslichkeit...

****************
-----
{{2}}
****************
**Strategien** 💡

Speicherung auf institutionellen Servern mit automatischem regelmäßigem Backup, Sicherung wichtiger Daten in mindestens drei Kopien auf räumlich getrennten Datenträgern

****************

# Datenspeicherung in der CAU-Cloud ☁ 

{{1-2}}
****************
![landing page](/images/CAU-cloud0.png)

****************

{{2-3}}
****************
![overview](/images/CAU-cloud1.png)

****************

{{3}}
****************
![left](/images/CAU-cloud3.png)

****************
{{4}}
****************
![top](/images/CAU-cloud2.png)

****************



## Funktionen

>* Gemeinsames Arbeiten online möglich
>
>* Zugang auch für CAU-externe möglich
>
>* Backup durch CAU
>
>* Datenschutz-konform



☛ **ABER** ☚


* Begrenzte Speichervolumen

* an eine Person an der CAU gebunden

* Speicherzeit an die Anstellung der Person an der CAU gebunden




## Open-Source-Strategie

{{1-2}}
****************

<img src="/images/open-source.png" width="350" align="right">

* Digitale Souveränität

* Open Source

* Cloudlösungen (Seite 7)

* Ablösung proorietärer Software (Seite 9)
****************

{{2-3}}
****************
![Open-Source Säulen](/images/open-source_SH.png)

"Produkte von Microsoft versorgen nahezu vollständig die Arbeitsplatzsysteme, sind kritische Komponenten im Backend und bilden zudem auf der Anwendungsebene die Basis für einige Dienste." (Seite 22)
****************

{{3}}
****************
![Kosten Microsoft Bund](/images/Kosten_Microsoft.png)
****************




# Daten mit anderen teilen 📚 

* Per Mail 📄

* über die Cloud ☁

* über OpenData@CAU 




# Herzlichen Dank!

<img src="/images/rdmCAU.png" width="250" align="right">

Mehr zum FDM an der CAU finden Sie hier: https://www.fdm.uni-kiel.de/de

<div style="page-break-after: always;"></div>

# Quellen

Biernacka, K., Buchholz, P., Danker, S. A., Dolzycka, D., Engelhardt, C., Helbig, K., Jacob, J., Neumann, J., Odebrecht, C., Petersen, B., Slowig, B., Trautwein-Bruns, U., Wiljes, C., & Wuttke, U. (2021). Train-the-Trainer-Konzept zum Thema Forschungsdatenmanagement (Version 4). Zenodo. https://doi.org/10.5281/zenodo.5773203 

Biernacka, K., Dockhorn, R., Engelhardt, C., Helbig, K., Jacob, J., Kalová, T., Karsten, A., Meier, K., Mühlichen, A., Neumann, J., Petersen, B., Slowig, B., Trautwein-Bruns, U., Wilbrandt, J., & Wiljes, C. (2023). Train-the-Trainer-Konzept zum Thema Forschungsdatenmanagement (Version 5). Zenodo. https://doi.org/10.5281/zenodo.10122153

Jaeger, Philipp, & Bode, Janice. (2021). Redet über die Daten! - Forschungsdatenmanagement und Hochschullehre in der Physik und darüber hinaus. Zenodo. https://doi.org/10.5281/zenodo.5168524

Petersen, B., Altemeier, F., Boße, S., Dalby, M., Düvel, N., Engelhardt, C., Fichtner, M., Hastik, C., Haugwitz, J.-M., Jacob, J., Koch, K., Kuntz, A., Manske, A., Mühlichen, A., Murcia Serra, J., Ortmeyer, J., Richter, M., Schranzhofer, H., Slowig, B., … Zollitsch, L. (2025). Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) (Version 3). Zenodo. https://doi.org/10.5281/zenodo.15025246

https://www.bsi.bund.de/DE/Themen/Verbraucherinnen-und-Verbraucher/Informationen-und-Empfehlungen/Cloud-Computing-Sicherheitstipps/Cloud-Risiken-und-Sicherheitstipps/cloud-risiken-und-sicherheitstipps_node.html

https://forschungsdaten.info/

https://mantra.ed.ac.uk/

https://mediafix.de/die-haltbarkeit-der-speichermedien/

https://www.fdm.uni-hannover.de/fileadmin/fdm/Dokumente/Schulungsunterlagen/Schulungsunterlagen_FDM_VertiefungDatenorganisation_Folien.pdf

https://www.forschungsdaten-bildung.de

https://www.gida-global.org/care 

https://opendata.uni-kiel.de/content/index.xml 

https://opendata.schleswig-holstein.de/dataset 



# Handling research data

## Begriffsdefinition Forschungsdatenmanagement

{{1}}
********************************************************************************
Das Portal **Forschungsdaten.info** definiert den Begriff **"Forschungsdatenmanagement"** folgendermaßen:

> Forschungsdatenmanagement (FDM) umfasst die Prozesse der **Transformation**, **Selektion** und **Speicherung** von Forschungsdaten mit dem gemeinsamen **Ziel**, diese *langfristig* und *personenunabhängig* **zugänglich**, **nachnutzbar** und **nachprüfbar** zu halten.
>
>(*forschungsdaten.info, letzter Zugriff 29.11.2022*)

********************************************************************************

<div style="page-break-after: always;"></div>

## Begriffsdefinition Forschungsdaten

**Und was sind Forschungsdaten?**

{{2}}
********************************************************************************
Die **DFG** definiert den Begriff **"Forschungsdaten"** folgendermaßen:

> „Zu Forschungsdaten zählen u. a. Messdaten, Laborwerte, audiovisuelle Informationen, Texte, Surveydaten oder Beobachtungsdaten, methodische Testverfahren sowie Fragebögen. Korpora und Simulationen können ebenfalls zentrale Ergebnisse wissenschaftlicher Forschung darstellen und werden daher ebenfalls unter den Begriff Forschungsdaten gefasst. Da Forschungsdaten in einigen Fachbereichen auf der Analyse von Objekten basieren (z. B. Gewebe-, Material-, Gesteins-, Wasser- und Bodenproben, Prüfkörper, Installationen, Artefakte und Kunstgegenstände), muss der Umgang mit diesen ebenso sorgfältig sein und eine fachlich adäquate Nachnutzungsmöglichkeit, wann immer sinnvoll und möglich, mitgedacht werden. Ähnliches gilt, wenn Software für die Entstehung oder Verarbeitung von Forschungsdaten erforderlich ist.“
>
> (*DFG 2021*)

********************************************************************************

{{3}}
********************************************************************************

Etwas weniger kompliziert definierte das PrePARe Projekt der Camebridge University den Begriff **Forschungsdaten** als:

> “Any any information you use in your research.”
>
> (*University of Camebridge PrePARe Project*)

********************************************************************************
<div style="page-break-after: always;"></div>



## Data organisation
### File and folder naming
### General notes

{{0-3}}
*****************

- **Never touch raw data! Always keep your raw data unchanged in a separate folder**.

********************************************************************************

{{1-3}}
********************************************************************************

- Try to find ‘speaking’ names for folders and files ➞ no ‘fantasy names’ 🦄, no random character strings

- Develop a standardised scheme and a logical structure

  - for both folder and file names.

  - Folders in hierarchical order with the most important first.

  - Limit yourself to a maximum of three folder levels, ensure a maximum path length of 256 characters.

  - Keep your personal preferences in mind during development, e.g. for ___sorting!___

********************************************************************************

{{2-3}}
********************************************************************************
- Follow [***ISO 8601***](https://en.wikipedia.org/wiki/ISO_8601) for dates and times

  - Date and time, e.g. YYYY-MM-DD-hh-mm-ss or YYYYMMDDhhmmss

********************************************************************************

{{3-4}}
********************************************************************************

- Always avoid spaces and all special characters (including special letters, such as german umlauts).

  - The following characters in particular should **NOT** be used in folder or file names:

    - less than: <

    - greater than: >

    - colon: :
    
    - double quotation mark: “
    
    - slash: /
    
    - backslash: \
    
    - vertical bar or pipe: |
    
    - question mark: ?
    
    - asterisk: \*

  - The only unproblematic special characters in folder or file names are underscore (_) and hyphen/minus (-)

********************************************************************************

{{4-7}}
********************************************************************************

- Prefix consecutive numbers with a sufficient number of zeros (e.g. 001 for numbering from 1 to 100)

********************************************************************************

{{5-7}}
********************************************************************************

- Use only one dot per file name -> between the file name and format suffix (e.g. filename.txt)

********************************************************************************

{{6-7}}
********************************************************************************

- Upper and lower case is considered different by some file systems, but not by others.  

********************************************************************************

{{7}}
********************************************************************************

- ***Document*** your folder structures as well as the naming conventions and abbreviations used!

  - Readme.md

**********************************************************

<div style="page-break-after: always;"></div>
