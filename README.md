# FortiGate Firewall Pack
----
* This pack is targeted for collections of Fortinet Fortigate firewall events
* The FortiGate-traffic pipeline inside the pack includes Sample files for testing, Lookup Tables for Enrichment, and multiple examples of Dropping events
* Furthermore, the pipeline show example of shaping the events into JSON before sending the event to the Analytics store
* The pack 4 additional pipelines FortiGate-utm, FortiGate-event, FortiGate-dns, and FortiGate-anomaly are all similar to the FortiGate-traffic pipeline. 


# Important Information
---
```
FortiGate Log types details can be found here: https://docs.fortinet.com/document/fortigate/7.0.0/fortios-log-message-reference/160372/list-of-log-types-and-subtypes
```

# What to Expect
---
* Event Reduction:  Expect 30% reduction in total size using Drop or Sampling functions.
* Event Erichment:  As you enable Lookkup Tables expect to see additional fields in the events.
* Event Shaping:  Expect the pack to shape the events into JSON format

## Requirements
---
Before you begin, ensure that you have met the following requirements:

1. Create a Route with with a filter for your Fortinet Fortigate events
2. Select the `CriblFortinetFortigateFirewall` pack as the pipeline.

## Release Notes
---
### Version 0.5.0 - 2021-05-18
* Fortinet Fortigate Firewall pack Initial release!
* Support for Fortinet Fortigate Firewall events including the following 5 sourcetypes FortiGate-traffic, FortiGate-utm, FortiGate-event, FortiGate-dns, and FortiGate-anomaly

## Contributing to the Pack
---
Discuss this pack on our Community Slack channel 

## Contact
---
The author of this pack is Raanan Dagan and can be contacted at <rdagan@cribl.io>.

## License
---
This Pack uses the following license: [`Apache 2.0`](https://github.com/criblio/appscope/blob/master/LICENSE).