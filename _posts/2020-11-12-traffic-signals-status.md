---
title: Traffic Signals Status
created: '2020-11-12T13:22:18.248473'
modified: '2020-12-04T18:24:44.058808'
state: active
type: dataset
tags:
  - Intersections
  - Mobility
  - Roadways
  - Traffic Signals
  - Transit
  - Transportation
groups:
  - Local Government
csv_url: 'https://data.austintexas.gov/api/views/5zpr-dehc/rows.csv?accessType=DOWNLOAD'
json_url: 'https://data.austintexas.gov/api/views/5zpr-dehc/rows.json?accessType=DOWNLOAD'
layout: post

---
This dataset reports on the operation state of traffic signals in Austin, TX. Traffic signals enter flash mode when something is preventing the signal from operating normally. This is typically the result of a power surge, power outage, or damage to signal equipment. A signal may also be intentionally placed into flash mode for maintenance purposes or be scheduled to flash overnight. 

You can view an interactive map of flashing traffic signals here:
http://transportation.austintexas.io/signals-on-flash

You can view a historical data set of signals that have flash in the past, here:
https://data.austintexas.gov/dataset/Traffic-Signal-Status-Historical-BETA-/x62n-vjpq/edit_metadata


Approximately 90% of the City’s signals communicate with our Advanced Trasnportation Management System. When these signals go on flash, they will be reported in this dataset. Although we are extending communications to all signals, approximately 10% are not currently captured in this dataset. It also occasionally happens that the event that disables a traffic signal also disables network communication to the signal, in which case the signal outage will not be reported here.

In this dataset the distinction between scheduled and unscheduled flash is identified by the 'operation state' column. A signal that is in unscheduled flash mode will have a status of 2 or 7. A signal that is in in scheduled flash mode will have a status of 1.

This product is for informational purposes and may not have been prepared for or be suitable for legal, engineering, or surveying purposes. It does not represent an on-the-ground survey and represents only the approximate relative location of traffic signals.
