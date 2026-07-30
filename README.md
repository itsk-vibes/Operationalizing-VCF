# Overview

This repo will serve as a collection of notes, scripts, and frameworks to help operationalize a VMware Cloud Foundation 9.1 enviornment.



## VCF Adoption Tracker

An interactive HTML page for tracking VCF adoption and use cases across organizations. Click a square to cycle its status (not started, in progress, adopted), tracked separately for "Usage" and "Use Case" per app. Export the results to Excel or CSV, or re-import a saved file to continue editing later.

[![Open the VCF Adoption Tracker](https://img.shields.io/badge/Open-VCF%20Adoption%20Tracker-007B8C?style=for-the-badge)](./tools/VCF_Adoption_Tracker_v1.html)
<!--[Open the tracker](./tools/VCF_Adoption_Tracker_v1.html)-->


## Monitoring and Observability

A framework and discovery tool for standing up meaningful alerting and dashboards
on VCF 9. The framework defines an MVP set of day one alerts across availability,
performance, and capacity, a "deny all, permit by exception" alert policy strategy,
and the five dashboards worth building first.

The discovery tool is an interactive HTML page for assessing what a customer already
has in place. Step through the 21 MVP alerts, 5 dashboards, and 8 operating practice
checks, marking each as covered, partial, or a gap, and attribute coverage to whatever
tooling the customer actually runs. Export a findings CSV for reporting, or save the
session as JSON to resume later.

[![Open the Monitoring Discovery Tool](https://img.shields.io/badge/Open-Monitoring%20Discovery%20Tool-CC092F?style=for-the-badge)](./tools/Monitoring-Observability-Discovery.html)

<!--## Contents
- [Scripts](./scripts)
- [Configs](./configs)
- [Screenshots](./screenshots)


## Notes
Add your write-ups here as you go.
-->
