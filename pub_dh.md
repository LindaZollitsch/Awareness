<!--

author:   Linda Zollitsch

email:    zollitsch@ub.uni-kiel.de

version:  0.1.0

language: de

narrator: 

icon:     images/Logo_cau-norm-de-lilagrey-rgb-0720_2022.png

licence: CC-BY

title:  Flyer zum Publikationsprozess für Geisteswissenschaften

link: https://cau-git.rz.uni-kiel.de/elBB4RDM/fdm-sh-boerse/-/blob/main/style_css.css

comment:  Überblick über wesentliche Aspekte des Publikationsprozesses

-->


# Flyer zum Publikationsprozess für Geisteswissenschaften

> Um dieses Dokument als interaktive, mit LiaScript gerenderte Version anzuzeigen, klicken Sie auf den folgenden Link/das folgende Symbol:
>
> [![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](link)
>
> Bei Fragen wenden Sie sich bitte an uns: [Zentrales Forschungsdatenmanagement](https://www.fdm.uni-kiel.de/de)
>
> Dieses Werk ist lizensiert unter CC-BY (https://creativecommons.org/licenses/by/4.0/)


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
   /--------------------/         /---------------/


``` 

## Text- und Datenpublikation



### Was ist eine Textpublikation

- Dissertation

- Artikel

- Handbücher

- Sammelbände


### Was ist eine Datenpublikation

https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/daten-publizieren/

### Formen der Datenpublikation

- Datenpublikation in Online-Repositorien

- Datenpublikation in Datenjournalen

- Datensupplemente


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

#### File formats

**Choosing file formats**

>-> Non-Proprietary, unencrypted, uncompressed and commonly used
>
>-> Open-standard-compliant, documented and royalty-free

| Data Type    | Recommended | Trade-off Matter | Not Recommented |
| ------------ | ----------- | ---------------- | --------------- |
| Tabular      | CSV, TSV, ODS| XLSX, SPSS portable| XLS, SPSS |
| Textual      |TXT, MD, HTML, ODT | DOCX, RTF, PDF/A | DOC, PDF, PS |
| Presentation | ODP, HTML   |  PPTX            |   PPT           |
| video        |MP4, MKV, OGG|  WEBM            | WMV, MOV, QT, Flash|
| Audio        | MP4, FLAC, WAV, OGG | MP3, AIF |                 |
| Image        | TIFF, PNG   |  BMP, JPG        |   PSD, GIF      |
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

**A good data documentation should include**

  - Information on the collection of data

      - Methods, units, time periods, locations, technique used, etc.

  - Structure of the data and their mutual relationships

  - Explanation of variables, labels and codes

  - Differences between different data set versions

  - Measures for data cleaning

  - Information on access and terms of use

      - Licensing

  - Ideal world

      - Description of the research undertaking

        - Goals

      - Hypotheses


## Metadaten

https://forschungsdaten.info/themen/beschreiben-und-dokumentieren/metadaten-und-metadatenstandards/

### Was sind Metadaten

Metdata is...

- Data about data

- Administrative data

  - Information on the management of the data

  - Mostly generic

- Subject data

  - Individual aspects or data sets in more detail

  - Structured with respect to the research discipline

- Generic standards

  - [DataCite Metadata Schema](https://schema.datacite.org/)

  - [Dublin Core Metadata Initiative](https://dublincore.org/)

- Discipline-specific standards

  - [Metadata Standards Directory](https://rdamsc.bath.ac.uk/)


### Was sind Metadatenstandards



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

{{3}}
********************************************************************************
>"A persistent identifier (PID) is a long-lasting reference to a digital resource and provides the information required to reliably identify, verify and locate your research data eliminating many misunderstandings. A PID may also be connected to a set of metadata which describes a digital resource." 
>
>(https://howtofair.dk/how-to-fair/persistent-identifiers/)

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
- Licenses regulate conditions of subsequent use of published data.
- Free licenses allow the use, redistribution and modification of copyrighted works

  - are usually available for free use and only need to be linked to
  - Prerequisite is that you are the copyright holder


Selection of the license depends on the type of data:

  - e.g. Creative Commons (CC) licenses for articles, monographs, images, etc.

  - Open-Database-License (ODbL) for DB or CC starting with version 4

  - General Public License (GNU) for software

- If no license is granted, the stricter copyright applies, as far as applicable to data

***********

<div style="page-break-after: always;"></div>

{{1-2}}
******************
> **CC-Licenses**

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

