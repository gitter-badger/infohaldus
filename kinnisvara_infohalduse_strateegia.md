# Riigi kinnisvara infohalduse strateegia
Staatus: [draft](https://github.com/kinnisvara/infohaldus/edit/master/kinnisvara_infohalduse_strateegia.md)

## Sissejuhatus
Riigi kinnisvara infohalduse strateegia alusteks on strateegia "[Dokumendihalduselt infohaldusele](https://www.mkm.ee/sites/default/files/dokumendihalduselt_infohaldusele_strateegia_1.9.pdf)" ja selle [alusdokument](https://www.mkm.ee/sites/default/files/lopparuanne_-_dokumendi-_ja_infohalduse_hetkeolukorra_ja_rahvusvaheliste_kogemuste_analuus_1_2.0.pdf) ning projekti "[Riigi kinnisvara kasutusnormatiivide väljatöötamine ja rakendamine riigi eelarveprotsessis](http://riigivara.fin.ee/lr1/web/guest/tof)" [tulemused](https://github.com/kinnisvara/infohaldus/tree/master/tof).

### 1.1 Strateegias kasutatavad mõisted

### 1.2 Töö metoodika

## 2 Visioon ja eesmärgid

### 2.1 Lahendamist vajavad probleemid
* riigi kinnisvara andmekogude nõrk koosvõime, peamisteks põhjusteks andmete koosseisu, kvaliteedi ja semantika erinevused
* vajalik info ei ole kättesaadav (puudulikud infomudelid, info halb kvaliteet)
* raiskamine info mitmekordsel taastootmisel

### 2.2 Visioon: terviklik hästi korraldatud riigi kinnisvara infohaldus

### 2.3 Riigi kinnisvara infohalduse strateegia eesmärgid

#### **Kvaliteetsem töö- ja elukeskkond**

#### **Efektiivsem riik** 
Aastal 2020 peab riik toime tulema viiendiku võrra väiksema eelarvega ning pakkuma vähemalt samas mahus vähemalt sama kvaliteediga avalikke teenuseid.

#### **Informeeritud otsused** 

Kinnisvara ja ehitiste infohalduses BIM'i rakendamise majanduslik sääst võib uuringutele ja teiste riikide kogemusele tuginedes olla märkimisväärne: 
* [Digital Built Britain, Ühendkuningriigid](http://www.buildingsmart.org/2015/03/03/digital-built-britain-launch/): The standards and savings delivered by the BIM level 2 initiative has been central to the __£840M savings achieved on central public spend in 2013/14__. [@nick_tune #BIMsday](https://twitter.com/FINAL_CAD/status/611436392258891776): The main rationale for the UK gov to introduce the mandate on #BIM was to reduce costs. __£1.7B saved between '11 and '14__.
* [Rijkswaterstaat, Holland](https://www.rijkswaterstaat.nl/en/images/Factsheet%20Design%20Standards%20-%20open%20Building%20Information%20Modelling_tcm224-340520.pdf): *By implementing BIM in the infra sector, road authorities will reduce failure costs and transaction costs. Studies have shown that __savings can be up to 10% of the building costs__*.
* [NIST, USA](http://catenda.no/archives/1923): *you __can save 2-3 USD per square meter per year__ by use of open BIM in facility management*.

### 2.4 Seonduvad initsiatiivid

[e-ehitus](http://e-ehitis.ee/)

## 3 Meetmed eesmärkideni jõudmiseks, tegevused ja mõõdikud

### Semantikavarade haldamise rakendamine

Riigi kinnisvaravaldkonnas tuleb süstemaatiliselt hakata semantikavarasid haldama. Selleks tuleb esmalt luua andmete semantiliseks kirjeldamiseks vajalik **kontseptsioon** (ontoloogia OWL vormingus, [#2](https://github.com/kinnisvara/infohaldus/issues/2)) ja seejärel **kirjeldada andmeteenused ja -koosseisud** ([kirjeldamise juhis](https://www.ria.ee/public/RIHA/semantilise_kirjeldamise_juhis_v04.PDF)). 

[Figure 7](http://www.bimtaskgroup.org/wp-content/uploads/2014/09/The-Asset-Information-Model-using-BIM.pdf) provides an overview of how the organisation can approach the development of its information requirements and how the information relates to the Asset Information Model (AIM) PAS 1192:3 and the Project Information Model (PIM) PAS 1192:2, http://www.bimtaskgroup.org/wp-content/uploads/2014/09/The-Asset-Information-Model-using-BIM.pdf

![ih_mudelite_diagramm](https://cloud.githubusercontent.com/assets/146800/8399839/322bb45c-1e1e-11e5-8bea-d0ac210a4d74.png)

Semantikavarade haldamine peab olema järjepidev.

![semantikavarade_haldamine](https://cloud.githubusercontent.com/assets/146800/8126481/9311bd22-10f7-11e5-9951-668d4aa924b2.PNG)

Semantikavarade haldamine peab olema taaskasutav - uute mõistete loomist paralleelselt olemasolevate kõrvale tuleb vältida. Selle asemel tuleb taotleda olemasoleva täiendamist vastavalt muudatusvajadusele.

Kinnisvaravaldkonna semantika parim praktika:
* OSCRE: http://www.oscre.org/index.php/oscre-resources/choose-and-use
* IFC: http://www.buildingsmart-tech.org/specifications/ifc-overview

### Ehitiste ja kinnisvara infohalduse parimate praktikate rakendamine

#### ISO 55001:2014 Asset Management 
http://www.bsigroup.com/en-GB/Asset-Management/

- BS ISO 55000 provides critical overview, concepts and terminology
- BS ISO 55001 specifies the requirements for an effective Asset Management System
- BS ISO 55002 offers interpretation and guidance for such a system to be implemented.


#### BIM level 2

![bim_maturity_levels](https://cloud.githubusercontent.com/assets/146800/8399085/c650e02c-1e0e-11e5-8fc3-df5a560e5311.png)

![1192-5_skeem](https://cloud.githubusercontent.com/assets/146800/8399094/ea0503c2-1e0e-11e5-9ef9-cf69cd59f39b.png)

UK tase 2 (1192 seeria) standardid on [2017 plaanis tõsta ISO tasemele](https://youtu.be/oAwGPhgFPAM?t=6m38s):

![1192-to-iso](https://cloud.githubusercontent.com/assets/146800/8399467/b4dde39a-1e17-11e5-8ca0-b4ce5443c542.png)


##### [BS 1192:2007](http://shop.bsigroup.com/forms/PASs/BS-1192-2007/) Collaborative production of architectural, engineering and construction information. Code of practice.

This standard establishes the methodology for managing the production, distribution and quality of construction information, including that generated by CAD systems, using a disciplined process for collaboration and a specified naming policy.

##### [PAS 1192-2](http://shop.bsigroup.com/forms/pass/pas-1192-2/) Specification for information management for the capital/delivery phase of construction projects using building information modelling

[PAS 1192-2](http://www.theb1m.com/video/pas-1192-2-in-5-minutes) provides the framework for collaborative working and information management in a BIM Level 2 environment.
![pas 1192-2](https://cloud.githubusercontent.com/assets/146800/8249462/fa71d922-1672-11e5-8aa2-fef0ebd4ffec.PNG)

##### [PAS 1192-3](http://shop.bsigroup.com/forms/pass/pas-1192-3/) Specification for information management for the operational phase of assets using building information modelling (BIM).

The PAS 1192:3 provides an approach to support the objectives of asset management through the use of asset information. Benefits targeted might be:
* Reduced costs as a result of the automated transfer of accurate, complete and unambiguous information at asset handover and during transfer of operation from one service provider to another.
* Better awareness of the operational and maintenance needs of assets.
* Better decisions regarding operation and maintenance expenditure based on actual asset performance and status.
* Better identification of poor performance, faults and impending failure by providing a home for data from dynamic measuring and condition sensing devices.
* Better organisation planning and strategic planning by having more complete and accurate asset information.
* Better information quality as a result of the automated verification introduced by the governance requirements.

![asset_info_model](https://cloud.githubusercontent.com/assets/146800/8250437/7793bf3e-167c-11e5-9414-6c707c5989bc.PNG)

How the approach outlined in document PAS 1192 Part 3 might be used by an organisation to develop their bespoke digital Asset Information Model to support decision making - __[The Asset Information Model 
using BIM](http://www.bimtaskgroup.org/wp-content/uploads/2014/09/The-Asset-Information-Model-using-BIM.pdf)__.

##### [BS 1192-4:2014](http://shop.bsigroup.com/forms/PASs/BS-1192-4-2014/) Collaborative production of information. Fulfilling employer's information exchange requirements using COBie. Code of practice

COBie (Construction Operations Building information exchange) provides a common structure for the exchange of information about new and existing Facilities, including both buildings and infrastructure.

This standard defines expectations for the exchange of information throughout the lifecycle of a Facility. The use of COBie ensures that information can be prepared and used without the need for knowledge of the sending and receiving
applications or databases. It ensures that the information exchange can be reviewed and validated for compliance, continuity and completeness.

COBie is the UK Government’s chosen information exchange schema for federated building information management (BIM) (UK level 2), alongside BIM models and PDF documents, with the aim of integrating commercially valuable information with other parts of the employer’s business. It can be used within less structured projects (UK level 1) and might have a role within integrated BIM (UK level 3) alongside a fuller building information model.

The scope of the exchange is given by the Facility – a distinct operational unit, typically a building or section of infrastructure or network – along with the temporary project and permanent site details. COBie holds information about the spatial locations and the equipment and components that make up the Facility.

To make these manageable during the Facility lifecycle, spatial locations are allocated to intermediate addresses or locations and into other spatial groupings, and equipment, and components are assigned their common specification and grouped by their functional purposes.

![cobie_british](https://cloud.githubusercontent.com/assets/146800/8399276/1bdbc864-1e13-11e5-8528-4c8df9495256.png)

[COBie 2016 and its importance for 'Digital Britain'](https://thebimhub.com/2015/05/25/cobie-2016-and-its-importance-for-digital-britain/)

##### [PAS 1192-5:2015](http://shop.bsigroup.com/forms/PASs/PAS-1192-5/) Specification for security-minded building information modelling, digital built environment and smart asset management ([pdf](http://shop.bsigroup.com/upload/271469/PAS1192-5-BSI.pdf))

PAS 1192-5 specifies the processes which will assist organisations in identifying and implementing appropriate and proportionate measures to reduce the risk of loss or disclosure of information which could impact on the safety and 
security of:
- personnel and other occupants or users of the built asset and its services;
- the built asset itself;
- asset information; and/or
- the benefits the built asset exists to deliver

![1192-5_protsess](https://cloud.githubusercontent.com/assets/146800/8399102/07dfbdb0-1e0f-11e5-96eb-f136d0cf9e41.png)

#### BIM Level 3



### Kvaliteedijuhtimise rakendamine äriprotsesside ja teenuste haldamisel. [Continuous improvement](http://businesscasestudies.co.uk/corus/continuous-improvement-as-a-business-strategy/continuous-improvement.html#axzz3dLCJSEHA) põhimõtete rakendamine

### Õigusloome protsessi parendamine

Õigusloomele peab eelnema äriprotsessi kirjeldamine ja semantika ühtlustamine.

### Parimaid praktikaid toetavate infohalduse töövahendite arendamine ja kasutuselevõtmine

* [NBS BIM Toolkit](https://toolkit.thenbs.com/), [tutvustav video](http://www.theb1m.com/video/nbs-bim-toolkit-explained)*
* [BRE COBie](http://brecobie.bre.co.uk/), [tutvustavad videod](https://www.youtube.com/playlist?list=PLdw8FwXDx_dgzFSZinArHrjiIUvpKFaPD), [lähtekood](https://github.com/kinnisvara/BreCOBie))

[RIBA vs BRE](http://bimcrunch.com/2014/09/ribas-nbs-win-uk-government-level-2-bim-dpow-contract/)

Töövahendite arendamisel tuleb lähtuda avatusest, koostööst ja pidevast parendamisest: http://wunderkraut.github.io/WunderFlow/

## 4 Mõõdikud ja seire

## 5 Riskid

## Lisad
