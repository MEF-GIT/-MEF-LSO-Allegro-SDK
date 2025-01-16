# MEF-LSO-Allegro-SDK Irene Release

## Download Link

Download the entire repository by clicking
[here](https://github.com/MEF-GIT/MEF-LSO-Allegro-SDK/releases/download/irene/MEF-LSO-Allegro-SDK-irene.zip)

## Overview

This repository contains the release of the Allegro SDK. The SDK includes
APIs for Service Catalog, Service Order, Service Inventory, Performance
Monitoring, and Streaming Management functions of the Service Orchestration
Functionality (SOF) at the LSO Allegro Interface Reference Point (IRP) as
defined in the MEF LSO Reference Architecture.

Also included are Service schemas and Performance Monitoring definitions.

## High-level release notes

- Updated documents:
  - MEF 133.1 - Draft Release 1 Allegro, Interlude and Legato Fault Management
    and Performance Monitoring BR&UC
  - MEF 136.1 - Draft Release 1 Allegro, Interlude and Legato Service Function
    Testing Business Requirements & Use Cases
  - MEF W143 - LSO Allegro, LSO Interlude and LSO Legato Performance Monitoring
    API - Developer Guide
- New Documents:
  - MEF W99.1 - LSO Service Ordering Management API - Developer Guide
  - MEF W101 - LSO Carrier Ethernet Service Schemas and Developer Guide
  - MEF W103 - LSO L1 Service Schemas and Developer Guide
  - MEF W135.1 - LSO Service Inventory Management API - Developer Guide
  - MEF W146 - LSO Allegro, LSO Interlude and LSO Legato Threshold Crossing
    Alerts API and Developer Guide - Developer Guide
  - MEF W148 - LSO Allegro, LSO Interlude and LSO Legato Fault Management API -
    Developer Guide
  - MEF W149 - LSO Allegro, LSO Interlude and LSO Legato Service Function
    Testing API - Developer Guide
  - MEF W153 - LSO IP Schemas and Developer Guide for SOAM

## Scope

It includes API definitions for the following functional areas:

- Service Ordering - This includes support for
  - Service Order/OrderItem - Create and Retrieve operations only
  - Not in scope
    - Service Order/OrderItem - Amend/Modify/Cancel, Delete operations
- Service Inventory - This includes support for
  - Service - Retrieve operations only
  - Not in scope
    - Service - Create, Amend/Modify, Delete operations
- Alarm Management
- Fault Management
- Performance Monitoring
- Service Function Testing
- Streaming Management

In addition to the Service Provisioning APIs, the SDK includes the following
MEF Service Specification schemas:

- SD-WAN Services
- Carrier Ethernet Services
- L1 Connectivity Services
- IP/IP-VPN Services

The MEF LSO Allegro SDK is released under the Apache 2.0 license.

More information about the LSO Allegro API reference point and its roadmap
can be found here:

https://wiki.mef.net/display/CESG/LSO+Allegro

## Maturity Level

The API files contained in this SDK are evolving and subject to change. They
are based on documents that are either work in progress or draft standards that
have not yet completed the review cycles and approvals necessary to achieve the
status as a MEF standard. MEF is making these publicly available at this time
to invite wider industry review.

The maturity per functionality is presented as follows:

(\*) is used to mark an item that changes its maturity compared to the previous
release.

APIs and Developer Guides:

- Service Catalog API - **early draft version, on hold**
- \*MEF W99.1 - LSO Service Ordering Management API - Developer Guide - **work
  in progress - ready for CfC#1**
- \*MEF W135.1 - LSO Legato Service Inventory Management API - Developer
  Guide -**work in progress - ready for CfC#1**

Service Schemas:

- SD-WAN (MEF W100) - **work in progress - CfC#2**
- \*Carrier Ethernet (MEF W101) - **work in progress - CfC#3**
- Internet Protocol (MEF W102) - **work in progress - CfC#4**
- \*LSO Legato Service Provisioning Specification - L1 (MEF W103) - **work in
  progress - ready for CfC#1**

SOAM:

- MEF \*W133.1 - Allegro, Interlude and Legato Fault Management and Performance
  Monitoring BR&UC - **Draft Release 1**
- MEF \*W136.1 - Service Function Testing Business Requirements and Use Cases -
  **Draft Release 1**
- MEF W143 - Performance Monitoring API and Developer Guide - **work in
  progress - CfC#3**
- MEF \*W146 - LSO Allegro, LSO Interlude and LSO Legato Threshold Crossing
  Alerts API and Developer Guide - Developer Guide - **work in progress - ready
  for CfC#1**
- MEF \*W147 - Streaming Management API and Developer Guide - **work in
  progress - CfC#2**
- MEF \*W148 - LSO Allegro, LSO Interlude and LSO Legato Fault Management API -
  Developer Guide - **work in progress - ready for CfC#1**
- MEF \*W149 - LSO Allegro, LSO Interlude and LSO Legato Service Function
  Testing API - Developer Guide - **work in progress - ready for CfC#1**
- MEF \*W153 - LSO IP Schemas and Developer Guide for SOAM **early draft
  version, schemas only**

- Security:
  - MEF 128.1 - **Published Standard**

## Contents

This SDK contains the following items:

- `COPYRIGHT` - Copyright 2024 MEF Forum
- `LICENSE` - Contains a copy of the Apache 2.0 license
- `README` - This file
- `serviceApi` - Definitions of the APIs are found in this directory, provided
  as yaml files.
- `serviceSchema` - Contains JSON schema (draft 7) files for service
  specifications.
- `documentation` - documentation including API/Schema developer guides and
  openapi-tools generated API descriptions in markdown format
  - `supportingStandards` - The rest of the documents and standards.
- `generated`
  - `security` - A not normative version of the standard APIs including the
    security profiles as required by MEF 128.1. Provided for evaluation.

## Issues, questions, and Feedback

Issues should be reported with the use of GitHub issues. Questions and feedback
should be asked either at
[Allegro SDK Discussions](https://github.com/MEF-GIT/MEF-LSO-Allegro-SDK/discussions)
or directly to community_manager@mef.net.

**NOTE:** All artifacts included in this repository have line numbers. When
referring to specific content in any of these artifacts, please quote the line
numbers to which you are referring.

## Copyright

© MEF Forum 2025. All Rights Reserved.

## Disclaimer

The information in this publication is freely available for reproduction and
use by any recipient and is believed to be accurate as of its publication date.
Such information is subject to change without notice and MEF Forum (MEF) is not
responsible for any errors. MEF does not assume responsibility to update or
correct any information in this publication. No representation or warranty,
expressed or implied, is made by MEF concerning the completeness, accuracy, or
applicability of any information contained herein and no liability of any kind
shall be assumed by MEF as a result of reliance upon such information.

The information contained herein is intended to be used without modification by
the recipient or user of this document. MEF is not responsible or liable for
any modifications to this document made by any other party.

The receipt or any use of this document or its contents does not in any way
create, by implication or otherwise:

(a) any express or implied license or right to or under any patent, copyright,
trademark or trade secret rights held or claimed by any MEF member which are or
may be associated with the ideas, techniques, concepts or expressions contained
herein; nor

(b) any warranty or representation that any MEF member will announce any
product(s) and/or service(s) related thereto, or if such announcements are
made, that such announced product(s) and/or service(s) embody any or all of the
ideas, technologies, or concepts contained herein; nor

(c) any form of relationship between any MEF member and the recipient or user
of this document.

Implementation or use of specific MEF standards, specifications, or
recommendations will be voluntary, and no Member shall be obliged to implement
them by virtue of participation in MEF Forum. MEF is a non-profit international
organization to enable the development and worldwide adoption of agile, assured
and orchestrated network services. MEF does not, expressly or otherwise,
endorse or promote any specific products or services.
