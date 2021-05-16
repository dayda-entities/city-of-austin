---
title: AFD Fire Incidents 2016 January Thru December
created: '2020-11-12T13:22:12.424948'
modified: '2020-11-12T13:22:12.424959'
state: active
type: dataset
tags:
  - Afd
  - Calls
  - Fire
  - Incidents
groups:
  - Local Government
csv_url: 'https://data.austintexas.gov/api/views/5tib-gqfx/rows.csv?accessType=DOWNLOAD'
json_url: 'https://data.austintexas.gov/api/views/5tib-gqfx/rows.json?accessType=DOWNLOAD'
layout: post

---
Fire Incidents in City of Austin Full Purpose which AFD responded on (does not include medical calls).

See Attachment for Metadata PDF. 

Data Descriptions
MasterIncidentNumber = unique identifier for individual incidents. If you encounter multiple rows with same MasterIncident number, it is b/c that incident had a multi-unit response.  Please refer to RespondingUnit to determine the number of units responding to the individual incident.
 
CalendarYear = calendar year in which individual incident occurred

Month = month in which individual incident occurred

DayOfMonth = calendar date in which individual incident occurred (Ex: 10 = 10th day in month)

Call_Type = generalized description of incident type for individual incidents. 

Battalion = Battalion in which individual incident occurred. A Battalion is a geographic boundary used for management of stations (Ex: Station 1, 2, 3, 4 are in Battalion 1)

Jurisdiction = Boundary of jurisdiction/department in which individual incident occurred. AFD = City of Austin Full Purpose 

ResponseArea = Small geographic boundary (often tied to a specific stations) in which individual incident occurred. Ex: 00-0101 is a ResponseArea for Station 1.  Also referred to as Fire Box.

TSUPResponseStatus = Level of response.  Code 1 = no lights/sirens, travels speedlimit.  Code 3 = lights/sirens, will travel faster than speedlimit.
Priority Description = Level of Priority of incident. Number equals priority (3 = Priority 3), letter equals general incident type (F=Fire)

Responding Unit = Units which responded to individual incident 

District = Boundary of City Council single-member district in which individual incident occurred

Latitude = non-decimal latitude.  Please use this formula to calculate for GIS geolocating = latitude *0.000001

Longitude = non-decimal longitude.  Please use this formula to calculate for GIS geolocating = longitude * -.000001
