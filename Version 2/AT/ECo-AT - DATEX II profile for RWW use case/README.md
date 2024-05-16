# ECo-AT - DATEX II profile for RWW use case

Status definition refers to ISO 14187
Card

Profile object
SituationPublication

Profile information
This profile describes the message content for the RWW use case as described by the project ECo-AT using the Situation publication. This profile distinguishes between 21 different message types in the context of roadworks, using beside the Roadwork class also the NetworkManagement or GeneralObstruction classes. Location referencing differentiates between triggerable RWW data, where a data set directly relates to a C-ITS message and augmentation RWW data, that can used to augment a RWW C-ITS message coming from a roadworks trailer. The former is done using three location containers indexed by “ItineraryByIndexedLocations”. The latter only uses one location container of type “Linear”. For location containers of type “Point“ the “PointByCoordinates“ is used, whereas for location containers of type “Linear“, the extension “LinearByCoordinates” is used. In addition to “LinearByCoordinates” each location container of type “Linear” also contains an “AlertCLinear (AlertCMethod4Linear)” container. Change log: Changes from V1 to V2 (published on 05.11.2015):

Added the data field “ClientIdentification” for the dissemination radius of the message as needed by the C-ITS-S. It is part of the exchange container.
Added the differentiation between triggerable RWW data and augmentation RWW data. The former one uses three location containers indexed by “ItineraryByIndexedLocations”, whereas the latter only uses one location container of type “Linear”.
Changes from V2 to V3 (published on 26.11.2015):

Added “AlertCLinear (AlertCMethod4Linear)” to each location container of type “Linear” in addition to “LinearByCoordinates”.
Added the field “informationStatus” to differentiate between live and test data feed.
Organization name
ECo-AT (The Austrian contribution to the Cooperative ITS Corridor)
Organization description
ECo-AT (European Corridor – Austrian Testbed for Cooperative Systems) is the Austrian project to create harmonised and standardised cooperative ITS applications jointly with partners in Germany and the Netherlands. The project is led by the Austrian motorway operator ASFINAG and the consortium consists of Kapsch TrafficCom AG, Siemens AG Österreich, SWARCO AG, High Tech Marketing, Volvo Technology AB, FTW, ITS Vienna Region, and BASt (Bundesanstalt für Straßenwesen).

Organization logo

![image](https://github.com/DATEX-II-EU/Profiles/assets/24648804/a9b1db2f-c9a2-4f6a-9b0b-016c3c9fefe4)

Website
http://www.eco-at.info/

Contact name
Dipl.-Ing. Peter Meckel
Contact mail
Peter.Meckel@asfinag.at

EA Model File

DATEX_II_PIM_ASFINAG.zip

XMI file

seeZipFile.xml

XML schema

DATEXII-Profile_RWW_ECo-AT_WithDefinitions.xsd

PDF Documentation

DATEXII-Profile_RWW_ECo-AT.pdf

Selection file

RWWProfile.sel
