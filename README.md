<img src="./assets/header.svg" alt="Operationalizing VCF" width="100%">
<div align="right">
<sub>Owner: Kunthaka Nilaweera</sub>
</div>
<br>
This repo will serve as a collection of notes, scripts, and frameworks to help operationalize a VMware Cloud Foundation 9.1 environment.

<img src="./assets/divider.svg" alt="" width="100%">

<!--## VCF Adoption Tracker

# Overview

This repo will serve as a collection of notes, scripts, and frameworks to help operationalize a VMware Cloud Foundation 9.1 enviornment.
-->

## VCF Adoption Tracker

An interactive HTML page for tracking VCF adoption and use cases across organizations. Click a square to cycle its status (not started, in progress, adopted), tracked separately for "Usage" and "Use Case" per app. Export the results to Excel or CSV, or re-import a saved file to continue editing later.

[![Open the VCF Adoption Tracker](https://img.shields.io/badge/Open-VCF%20Adoption%20Tracker-007B8C?style=for-the-badge)](./tools/VCF_Adoption_Tracker.html)
<!--[Open the tracker](./tools/VCF_Adoption_Tracker_v1.html)-->

<img src="./assets/divider.svg" alt="" width="100%">

## Monitoring and Observability

A framework and discovery tool for standing up meaningful alerting and dashboards on VCF 9. The framework defines an MVP set of day one alerts across availability, performance, and capacity, a "deny all, permit by exception" alert policy strategy, and the five dashboards worth building first. The discovery tool is an interactive HTML page for assessing what a customer already has in place. Export a findings CSV for reporting, or save the session as JSON to resume later.

[![Open the Monitoring Discovery Tool](https://img.shields.io/badge/Open-Monitoring%20Discovery%20Tool-CC092F?style=for-the-badge)](./tools/Monitoring-Observability-Discovery.html)

<img src="./assets/divider.svg" alt="" width="100%">

## Incident Management

A framework and discovery tool for turning VCF 9 alerts into tracked, owned incidents. The discovery tool is an interactive HTML page for assessing how far a customer has got. Step through 47 checks across the pipeline, ITSM integration, escalation model, response playbooks, and notification rule strategy, marking each as in place, partial, or a gap, and attribute coverage to whatever tooling the customer actually runs.

[![Open the Incident Management Discovery Tool](https://img.shields.io/badge/Open-Incident%20Management%20Discovery%20Tool-A96A05?style=for-the-badge)](./tools/Incident-Management-Discovery.html)

<img src="./assets/divider.svg" alt="" width="100%">

## Lifecycle Management

A framework and discovery tool for keeping the platform current and secure through patching, password, and certificate management. The discovery tool is an interactive HTML page for assessing how far a customer has got. Step through 48 checks across the depot and Bill of Materials foundation, patching and upgrades, password management, certificate management, and operating cadence, marking each as in place, partial, or a gap, and attribute coverage to whatever tooling the customer actually runs. 

[![Open the Lifecycle Management Discovery Tool](https://img.shields.io/badge/Open-Lifecycle%20Management%20Discovery%20Tool-5B3E90?style=for-the-badge)](./tools/Lifecycle-Management-Discovery.html)
