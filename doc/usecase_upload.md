<b>Title:</b> Client uploads relevant SPDX documentation or package to be scanned<br>

<b>Primary Actor:</b> Client<br>

<b>Goal in Context:</b> To allow the dashboard to accept new data into the system, either a SPDX document directly, or a package to be scanned to produce a SPDX document.<br>

<b>Stakeholders and Interests:</b>
* <b>Clientele:</b>
  * To be able to upload relevant documentation to expand the existing system
  * To be able to scan packages without leaving the dashboard to retrieve SPDX documentation
  * To be able to share this information to all whom it may be relevant to (supply chain, etc.)
* <b>Maintainers of SPDX Dashboard:</b>
  * To have the ability to scan packages uploaded by clientele to pull essential licensing documentation for client viewing
  * To have the ability to properly document all packages with proper notation and relevancy per the SPDX 2.0 spec
  * To validate all documentation uploaded to verify relevance to the SPDX 2.0 spec
  * To clearly communicate license and copyright information stored within packages or uploaded documents

<b>Preconditions:</b>
* Clientele has either a SPDX document ready to upload or a package with embedded license information ready to upload/scan
* Clientele is not currently running another upload on the SPDX Dashboard

<b>Main Success Scenario:</b>
* Client uploads a SPDX document that passes validation checks and is added to the system
* Client uploads a package that is successful during scanning and thus produces a SPDX document which is added to the system

<b>Failed End Conditions:</b>
* Client uploads a SPDX document that is not correct and therefor does not pass validity checks against the SPDX 2.0 spec
* Client uploads a package that is not a package that can be scanned, and as such a SPDX document cannot be created

<b>Trigger:</b> Clientele selects the option for an upload to the SPDX Dashboard, and then are given the option to upload an SPDX document or to scan a package for licensing information<br><br>
<b>Notes:</b> Clients may upload documents that are incomplete, as these documents can be later edited to include pertinent information. Also, not all scanned packages will provide complete SPDX documents if information is not present or cannot be found, yet again if this information is known by the client – it can be added after the scan has concluded and the document has been created and added.

