# Use Cases

## Analyze Software

Title:

* Analyze Software

Primary Actor:

* Corporate Developer

Goal in Context:

* The corporate developer is able to determine license and vulnerability information from provided package information

Stakeholders:

* Corporate Manager: To receive clear and relevant project information
* Corporate Developer: To provide the relevant file/package level information
* Project Owner: To clearly understand corporate manager decisions to green/red light a project

Preconditions:

* Relevant file/package is in the SPDX database
* Proper package information has been provided

Main Success Scenario:

* Corporate developer receives accurate license and vulnerability information for the requested package

Failed End Conditions:

* Corporate developer receives inaccurate or invalid license and vulnerability information for the requested package, or does not recieve information

Trigger:

* Corporate developer submits a package to which license and vulnerability information is provided

## Check Package Licenses and Vulnerabilities

Title:

* Check Package Licenses and Vulnerabilities

Primary Actor:

* Corporate Manager
* Corporate Developer

Goal in Context:

* The corporate manager or developer is able to access license and vulnerability information about previously scanned packages

Stakeholders:

* Corporate Manager: To access clear and relevant project information
* Corporate Developer: To access clear and relevant project information
* Project Owner: To clearly understand corporate manager decisions to green/red light a project

Preconditions:

* Relevant package has been scanned previously
* Corporate manager or developer has information to identify the package

Main Success Scenario:

* Corporate manager or developer receives accurate license and vulnerability information for the requested package

Failed End Conditions:

* Corporate manager or developer receives inaccurate or invalid license and vulnerability information for the requested package, or does not recieve information

Trigger:

* Corporate manager or developer submits package information which license and vulnerability information is provided

## Add/Edit Package Policy

Title:

* Add/Edit Package Policy

Primary Actor:

* Corporate Manager

Goal in Context:

* The corporate manager is able add or update the policy for a specified package

Stakeholders:

* Corporate Manager: To specify and be able to test package policies
* Corporate Developer: To understand what is allowable for a package's licenses and vulnerabilities
* Project Owner: To clearly understand corporate manager decisions to green/red light a project

Preconditions:

* Corporate manager has a new policy or edits to make to an existing policy

Main Success Scenario:

* Corporate manager successfully adds/updates policy information

Failed End Conditions:

* Corporate manager is unable to add/update policy information or information is added/updated inaccurately

Trigger:

* Corporate manager submits new policy or updates to an existing policy
