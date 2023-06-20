# ThreatDetection
ThreatDetection is a collection of detection rules designed by Dany Giang aka CyberMatters

## About
For the moment, the language that is used is KQL (Kusto Query Language).

Those queries are intended to be used as scheduled analytics rules or hunting queries in Microsoft Azure Sentinel.

If the queries are used in Microsoft 365 Defender "Advanced hunting", do replace `TimeGenerated` by `TimeStamp`.
