# ECo-AT - DATEX II profile for IVI use case

Status definition refers to ISO 14187
Card
Profile object
VmsTablePublication, VmsPublication
Profile information
This profile describes the location and content message for the IVI use case as described in the project ECo-AT using the VMS table publication and VMS publication. The IVI location uses the VMSTablePublication whereas the IVI content uses the VMSPublication. Location referencing is done by a level B extension which is also described in this document. The extension is named as “IviLocation”. The "IviLocation" contains two containers namely "DetectionZone" and "RelevanceZone" which uses another level B extension “LinearByCoordinates”. In addition to “LinearByCoordinates” each location container of type “Linear” also contains an “AlertCLinear (AlertCMethod4Linear)” container. Change log: Changes from V1 to V2 (published on 05.11.2015):

- Added the data field “ClientIdentification” for the dissemination radius of the message as needed by the C-ITS-S. It is part of the exchange container and only provided in the location message.

Changes from V2 to V3 (published on 26.11.2015):
- Added “AlertCLinear (AlertCMethod4Linear)” to each location container of type “Linear” in addition to “LinearByCoordinates”.
- Added the field “informationStatus” to differentiate between live and test data feed.

Changes from V3 to V4 (published on 22.12.2016):
- Added more enumeration literals to VmsDatexPictogramEnum and VmsDatexSupplementalPictogramEnum.

Changes from V4 to V5 (published on 28.02.2020):
- Updated the IviLocation container to add referencePosition with bearing

Organization name
ECo-AT (The Austrian contribution to the Cooperative ITS Corridor)
Organization description
ECo-AT (European Corridor – Austrian Testbed for Cooperative Systems) is the Austrian project to create harmonised and standardised cooperative ITS applications jointly with partners in Germany and the Netherlands. The project is led by the Austrian motorway operator ASFINAG and the consortium consists of Kapsch TrafficCom AG, Siemens AG Österreich, SWARCO AG, High Tech Marketing, Volvo Technology AB, FTW, ITS Vienna Region, and BASt (Bundesanstalt für Straßenwesen).

Organization logo<br>
![image](https://github.com/DATEX-II-EU/Profiles/assets/24648804/09b89725-964f-445f-be9d-e5d9f0ac4b0a)

Website
http://www.eco-at.info/

Contact name
Dipl.-Ing. Peter Meckel
Contact mail
Peter.Meckel@asfinag.at
EA Model File
DATEX II PIM Austria Profile.zip
XMI file
seeZipFile.xml
XML schema
DATEXII-Profile_IVILocation_ECo-AT.xsd
PDF Documentation
DATEXII-Profile_IVILocation_ECo-AT.pdf
Selection file
IviLocationProfile.sel
