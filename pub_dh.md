<!--

author:   Linda Zollitsch

email:    zollitsch@ub.uni-kiel.de

version:  0.1.0

language: de

narrator: 

icon:     LindaZollitsch/Awareness/images/cau-norm-en-lilagrey-rgb.png

licence: CC-BY

title:  Flyer zum Publikationsprozess für Geisteswissenschaften

link: LindaZollitsch/Awareness/style_css.css

comment:  Überblick über wesentliche Aspekte des Publikationsprozesses für Geisteswissenschaften, digital humanities

-->


# Flyer zum Publikationsprozess für Geisteswissenschaften

> Um dieses Dokument als interaktive, mit LiaScript gerenderte Version anzuzeigen, klicken Sie auf den folgenden Link/das folgende Symbol:
>
> [![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](link)
>
> Bei Fragen wenden Sie sich bitte an uns: [Zentrales Forschungsdatenmanagement](https://www.fdm.uni-kiel.de/de)
>
> Dieses Werk ist lizensiert unter CC-BY (https://creativecommons.org/licenses/by/4.0/)



## Text- und Datenpublikation


<!--
style="
  background-color: #fee1ff;" -->
``` ascii
           +---------+   +---------+
           |         |   |         |  
           |  Texte  | + |  Daten  | 
           |         |   |         |  
           +---------+   +---------+  
                                            .--------.
                          .------------.    | Lizenz |
                          |            |--->'--------'
      .---------.         |    Open    |
     ( Metadaten )        |            |--->.---------------.
      `---------´         '------------'    |  Dateiformat  |
                  .---.                     '---------------'                   
                 ( PID )
                  `---´
     .------------.
    ( Repositorium ) 
     `------------´    
       
     .--------------------.         .---------------.
    / Datendokumentation /         / Datenqualität /
   '--------------------´         '---------------´


``` 


### Was ist eine Textpublikation

-- hier Bild einfügen von Beispielen --

- Dissertation

- Artikel

- Handbücher

- Sammelbände

- usw.


### Was ist eine Datenpublikation

https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/daten-publizieren/

- was sind Daten

-- hier Bild einfügen von Beispielen --


### Formen der Datenpublikation

- Datenpublikation in Online-Repositorien

- Datenpublikation in Datenjournalen

- Datensupplemente

erläutern und Beispiele dafür zeigen


## Publikationswege

https://open-access.network/informieren/open-access-grundlagen/open-access-gruen-und-gold

https://www.tu-chemnitz.de/ub/publizieren/openaccess/publikationswege.html


### offene und geschlossene Publikationswege

https://www.publisso.de/open-access-beraten/faqs/open-access-vs-closed-access

### Das 5-Sterne-Modell

https://5stardata.info/de/

https://data.europa.eu/elearning/de/module10/#/id/co-01

## Dateiformate für die Publikation

https://www.tu-braunschweig.de/fileadmin/Redaktionsgruppen/Einrichtungen/UB/Leitfaden_Forschungsdatenpublikation_TUBS_V1.4.pdf

https://www.uni-muenster.de/Publizieren/veroeffentlichung/dateierstellung/

https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/formate-erhalten/

**Dateiformate für eine Publikation auswählen**

>-> Nicht proprietär, unverschlüsselt, unkomprimiert und weit verbreitet
>
>-> Offener Standard, dokumentiert und lizenzgebührenfrei


| Datentyp     | Empfohlen   | Trade-off Matter | Nicht Empfohlen |
| ------------ | ----------- | ---------------- | --------------- |
| Tabellen     | CSV, TSV, ODS| XLSX, SPSS portable| XLS, SPSS |
| Texte        |TXT, MD, HTML, ODT | DOCX, RTF, PDF/A | DOC, PDF, PS |
| Presentation | ODP, HTML   |  PPTX            |   PPT           |
| Video        |MP4, MKV, OGG|  WEBM            | WMV, MOV, QT, Flash|
| Audio        | MP4, FLAC, WAV, OGG | MP3, AIF |                 |
| Bilder       | TIFF, PNG   |  BMP, JPG        |   PSD, GIF      |
| Vector       |  SVG        |                  |     AI          |
| Generic      |  XML, JSON, RDF |              |                 |
| Container    | Bagit, Frictionless, Data Package| ZIP, TAR |      |

<div style="page-break-after: always;"></div>

## Datenqualität und Qualitätskriterien für eine Publikation

https://forschungsdaten.info/kalender-index/kalender-anzeige/termin/datenqualitaet-greifbar-machen-qualitaetskriterien-und-ziele-der-datennutzung/

https://forschungsdaten.info/nachrichten/nachricht-anzeige/nfdi4memory-umfrage-zu-praktiken-standards-und-bedarfen-zur-datenqualitaet-in-den-communities-der-historisch-arbeitenden-faecher/

https://www.cdi.fau.de/informationen/qualitaet-von-forschungsdaten/


## Dokumentation

https://forschungsdaten.info/themen/beschreiben-und-dokumentieren/datendokumentation/

https://www.forschungsdaten-bildung.de/datenmanagement/dokumentieren-aufbereiten/

**Eine gute Datendokumentation sollte folgendes enthalten**

  - Informationen zu der Datensammlung

      - Methoden, Einheiten, Zeit, Ort, genutzte Technik, usw.

  - Struktur der Daten und deren Beziehung miteinander

  - Erklärung der Variablen, Explanation of variables, Labels und Codes

  - Unterschiede zwischen verschiedenen Versionen von Datensets

  - Maßnahmen zur Datenbereinigung

  - Informationen über Zugang und Nutzungsbedingungen

      - Lizenzen

  - In einer idealen Welt

      - Beschreibung des Forschungsvorhabens

        - Ziele

      - Hypothesen


## Metadaten

https://forschungsdaten.info/themen/beschreiben-und-dokumentieren/metadaten-und-metadatenstandards/

### Was sind Metadaten

Metdata sind...

- Daten über Daten

- Administrative Daten

  - Informationen zum Datenmanagement

  - Größtenteils generisch

- Subject data

  - Einzelne Aspekte oder Datensätze im Detail

  - Strukturiert nach den Anforderungen der Forschungsdisziplin



### Was sind Metadatenstandards

- Generische Standards

  - [DataCite Metadata Schema](https://schema.datacite.org/)

  - [Dublin Core Metadata Initiative](https://dublincore.org/)

- Disciplin-spezifische Standards

  - [Metadata Standards Directory](https://rdamsc.bath.ac.uk/)



## Persistente Identifikatoren (PID)

https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/persistente-identifikatoren/

-----

{{1}}
********************************************************************************
![PID](/PID.png)<!--  width="150px" align="right"
-->

Persistente Identifikatoren gibt es (unter anderem) für:

* Daten und digitale Objekte
* Personen
* Institutionen

********************************************************************************

{{2}}
********************************************************************************
"Ein Persistent Identifier ist definiert als ein dauerhafter (persistenter), digitaler Identifikator, bestehend aus Ziffern und/oder alphanumerischen Zeichen, welcher einem Datensatz (oder einem anderen digitalen Objekt) zugeordnet wird und direkt auf diesen verweist."

(https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/persistente-identifikatoren/)

********************************************************************************

### Digital Object Identifier (DOI®)

https://www.doi.org/

-----

{{1-4}}
********************************************************************************

![DOI](/DOI_logo.svg.png)<!--  width="150px" align="right"
-->

(Copyright © 2022 DOI Foundation. Licensed under a Creative Commons Attribution 4.0 International License. DOI®, DOI.ORG®, and
 shortDOI® are trademarks of the DOI Foundation.)

-----

********************************************************************************


{{2-4}}
********************************************************************************

>"DOIs are persistent identifiers to uniquely and permanently identify physical, digital and abstract objects following international standards (ISO 26324)." 
>
>(https://zenodo.org/record/8178870)

-----

********************************************************************************

{{3-4}}
********************************************************************************

DOIs sind:

* die digitale Kennung eines Objekts

* eine eindeutige Nummer, die aus einem Präfix und einem Suffix besteht, die durch einen Schrägstrich getrennt sind. Zum Beispiel: 10.1000/182.

* eine dauerhafte, eindeutige Identifizierung von Objekten für die Verwendung durch Menschen und Maschinen

(https://www.doi.org/the-identifier/what-is-a-doi/)

-----

********************************************************************************

{{4}}
********************************************************************************
![DOI](/DOI_2.png)

********************************************************************************


### ORCID

https://orcid.org/

-----

{{1-2}}
********************************************************************************

![ORCID](/ORCID-iD_icon-128x128.png)<!--  width="150px" align="right"
-->

Wrigley, Alainna Therese; Meadows, Alice; Haak, Laurel (2017). ORCID iD icon graphics. ORCID. Figure.
 https://doi.org/10.23640/07243.5008697.v4. Under CC0 License

********************************************************************************


{{2-3}}
********************************************************************************
**Was ist eine ORCID?**


eine offene Forscher- und Mitwirkenden-ID

eine eindeutige, dauerhafte Kennung, die Forschenden kostenlos zur Verfügung steht

offen, transparent, nicht proprietär

-----

> * 16-stellige Nummer und der zugehörige Datensatz, der automatische Verknüpfungen zur Forschung speichert und die Forschung mit Ihnen verknüpft
>
> * Macht Forschende eindeutig identifizierbar und verbindet Personen mit ihren Forschungsaktivitäten
>
> * Dient als Informationsplattform, die den Autor:innen und Gutachter:innen ermöglicht, sich zuverlässig mit Ihren Beiträgen zu verbinden

(info.orcid.org, letzter Zugriff: 17.08.2023)

********************************************************************************

{{3}}
********************************************************************************
**Wie sieht ein ORCID-Eintrag aus?**

![ORCID](/Orcid_record.png)

********************************************************************************

### Vorteile von Persistent Identifiers

-----

* hilft, Objekte, Personen oder Institutionen leichter zu identifizieren

* maschinenlesbar

* langlebige Referenz

* überprüfbar

* zuverlässig

* Veröffentlichung von Daten mit der Gewissheit, dass sie mit dem Autor verbunden sind

-----

## Repositorium

https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/repositorien/

## Lizenzen

https://forschungsdaten.info/themen/rechte-und-pflichten/forschungsdaten-veroeffentlichen/creative-commons-lizenzen/

{{0-1}}
*******************
- Lizenzen regeln die Bedingungen für die weitere Nutzung veröffentlichter Daten
- Freie Lizenzen erlauben die Nutzung, Weiterverbreitung und Bearbeitung urheberrechtlich geschützter Werke

  - sie sind in der Regel kostenlos verfügbar und müssen lediglich verlinkt werden
  - Voraussetzung ist, dass Sie der Urheberrechtsinhaber sind


Die Wahl der Lizenz hängt von der Art der Daten ab:

  - z. B. Creative-Commons-Lizenzen (CC) für Artikel, Monografien, Bilder usw.

  - Open-Database-Lizenz (ODbL) für Datenbanken oder CC ab Version 4

  - GNU General Public License (GPL) für Software

- Wird keine Lizenz erteilt, gelten die strengeren Urheberrechtsbestimmungen, soweit sie auf die Daten anwendbar sind

***********

<div style="page-break-after: always;"></div>

{{1-2}}
******************
> **CC-Lizenzen**

><div style="width:100%;">
  <img src="images/cc-licenses.png" alt="CC-Licenses">
</div>


*********************

<div style="page-break-after: always;"></div>

{{2}}
******************
**Take care!**

>$$
no\,license
\not =
free\,license
$$

********************


# Informationen zu diesem Dokument

| Parameter           | Info                       |
| --------            | :------                    |
| Titel:              | @title                     |
| Einsatz:            | @comment                   |
| Autor:innen         | @author                    |
| Lizenz              | @licence                   |     

