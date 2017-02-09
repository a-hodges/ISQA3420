# Use Cases

## Determine Liscense and Vulnerability Information

Title:

* Determine Liscense and Vulnerability Information

Primary Actor:

* Corprate Manager

Goal in Context:

* The corporate manager is able to determine license and vulnerability information from provided project information

Stakeholders:

* Corporate Manager: To receive clear and relevant project information
* Corporate Developer: To provide the relevant file/package level information
* Project Owner: To clearly understand corporate manager decisions to green/red light a project

Preconditions:

* Relevant file/package is in the SPDX database
* Proper project information has been provided

Main Success Scenario:

* Corporate manager receives accurate license and vulnerability information for the requested project packages

Failed End Conditions:

* Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages, or does not recieve information

Trigger:

* Corporate manager identifies project information to which license and vulnerability information is provided

## Store Project Licenses and Vulnerabilities

Title:

* Store Project Licenses and Vulnerabilities

Primary Actor:

* Corporate Developer

Goal in Context:

* The corporate developer is able to submit a project to be scanned for licenses and vulnerabilities

Stakeholders:

* Corporate Developer: To document their project's relevant information
* Corporate Manager: To have access to project information

Preconditions:

* Project has been developed
* Information about license types and known vulnerabilities is available

Main Success Scenario:

* Project license and vulnerability information is stored in SPDX database

Failed End Conditions:

* Project license and vulnerability information is not stored in SPDX database or inaccurate information is stored

Trigger:

* Developer uploads project to be scanned

## Submit Vulnerability

Title:

* Submit Vulnerability

Primary Actor:

* Corporate Developer

Goal in Context:

* The corproate developer can submit a discovered vulnerability to the database

Stakeholders:

* Corporate Developer: To record known vulnerabilities in developed software
* Corporate Manager: To make decisions with up-to-date security information
* Project Owner: To be made aware of the most recent vulnerabilities in their project

Preconditions:

* Developer discovered vulnerability

Main Success Scenario:

* Vulnerability is recorded in database

Failed End Conditions:

* Vulnerability is not recorded or inaccurately recorded

Trigger:

* Developer submits new vulnerability to database
