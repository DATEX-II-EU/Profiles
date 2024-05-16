# Austrian Elementary Profile UNPLANNED EVENTS

Status definition refers to ISO 14187
Card
Profile object
SituationPublication
Profile information
ASFINAG provides DATEX II  traffic data feeds in real time with 24/7/365 availability of all Austrian highways and motorways. Principal contractors for the data would be service providers for mobile transmission to vehicles. Please visit https://services2.asfinag.at/web/trafficdata/ for registration and to acquire a contract.

Austria promotes the idea of Elementary Profiles to be provided in the same form by every EU member starte. Any necessary filtering or aggregation would be performed by the contractor.

This section describes the Austrian Elementary Profile "Unplanned Events". It uses SituationPublication to describe the unplanned events content. Location referencing is done using Points and Linear elements in the form of coordinates and ALERT-C. OpenLR location referencing is also supported. It also uses few B level extensions in addition to the approved extensions, which are also documented. One of the important extension is the extension for “Graph Integration Platform (GIP)”. The GIP provides a digital map of Austria’s transport network to all authorities.

Change log

Changes from v1.0 to v2.0 (published on 11.03.2019):
- Renamed the profile from "AustrianTrafficMessages" to "AustrianUnplannedEvents"
- Added level B extensions for GIP location referencing
- Included exchange related data elements (such as keepAlive and subscription)

Changes from v2.0 to v2.1 (published on 04.06.2019):
- Added the relative location referencing method "DistanceFromLinearElementReferent"
- Added the element "capacityRemaning" to the "Impact" class
- Added the element "situationRecordCreationReference" to the "SituationRecord" class
- Added the elements "commentDateTime" and "commentType" to the "Comment" class

The older version "v2.0" of the AustrianUnplannedEvents is provided inside the attachment "http://datex2.eu/sites/default/files/d2-profile/AustrianUnplannedEventsProfile_2.zip".

Organization name
ASFINAG

Organization description
ASFINAG acts as an economically responsible motorway operator. We are convinced that modern and sustainably developed infrastructure is essential both for the mobility requirements of every single person and for Austria as a location for business. By using new technologies and innovations, we want to make Austria's motorways and expressways amongst the safest in Europe – in the interest of our customers and to strengthen the country as a place in which to do business.

Organization logo

![image](https://github.com/DATEX-II-EU/Profiles/assets/24648804/2aa15a0a-a1ce-4c66-bc43-32833ff04437)

Website
http://www.asfinag.at/

Contact name
Dipl.-Ing. Gottfried Allmer
Contact mail
gottfried.allmer@asfinag.at

EA Model File

AustrianUnplannedEventsProfile_2.zip

XMI file

See_zip-file.xml

XML schema

AustrianUnplannedEventsProfile_1.xsd

PDF Documentation

AustrianUnplannedEventsProfile_0.pdf

Selection file

unplanned_events_1.sel
