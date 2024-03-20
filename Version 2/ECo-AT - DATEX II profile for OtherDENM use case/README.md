# ECo-AT - DATEX II profile for OtherDENM use case

Status definition refers to ISO 14187
Card
Profile object
SituationPublication
Profile information
This profile describes the message content for the OtherDENM use case as described by the project ECo-AT using the Situation publication. This profile distinguishes between 64 different message types in the context of traffic messages. Location referencing is done using three location containers indexed by “ItineraryByIndexedLocations”. The first location container with index “0“ uses “PointByCoordinates“, whereas the second and third location containers uses the extension “LinearByCoordinates”. In addition to “LinearByCoordinates” each location container of type “Linear” also contains an “AlertCLinear (AlertCMethod4Linear)” container. Change log: Changes from V1 to V2 (published on 05.11.2015):

- Added the data field “ClientIdentification” for the dissemination radius of the message as needed by the C-ITS-S. It is part of the exchange container.
- Added an additional location container of type “Point(PointByCoordinates)” to “ItineraryByIndexedLocations”. This represents the event position.

Changes from V2 to V3 (published on 26.11.2015):
- Added “AlertCLinear (AlertCMethod4Linear)” to each location container of type “Linear” in addition to “LinearByCoordinates”.
- Added the field “informationStatus” to differentiate between live and test data feed.

Changes from V3 to V4 (published on 27.07.2016):
- Added the situation record extension for indicating safety related traffic messages.
- Added more enumeration literals

Changes from V4 to V5 (published on 13.9.2016):
- Included "nonGeneralPublicComment" in the SituationRecord.

Organization name
ECo-AT (The Austrian contribution to the Cooperative ITS Corridor)
Organization description
ECo-AT (European Corridor – Austrian Testbed for Cooperative Systems) is the Austrian project to create harmonised and standardised cooperative ITS applications jointly with partners in Germany and the Netherlands. The project is led by the Austrian motorway operator ASFINAG and the consortium consists of Kapsch TrafficCom AG, Siemens AG Österreich, SWARCO AG, High Tech Marketing, Volvo Technology AB, FTW, ITS Vienna Region, and BASt (Bundesanstalt für Straßenwesen).

Organization logo

Website
http://www.eco-at.info/

Contact name
Dipl.-Ing. Peter Meckel
Contact mail
Peter.Meckel@asfinag.at

EA Model File

DATEX_II_PIM_ASFINAG.zip

XMI file

see_zip_file..xml

XML schema

DATEXII-Profile_OtherDENM_ECo-AT_WithDefinitions.xsd

PDF Documentation

DATEXII-Profile_OtherDENM_ECo-AT.pdf

Selection file

OtherDENMProfile.sel
