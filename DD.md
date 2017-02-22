# Data Dictionary

## External Entities

### Developer

The developer is a software developer, generally the creator of a package.

### Manager

The manager is a project leader and policy setter, usually in charge of developers.

## Data Stores

### NIST Vulnerability Database

An external database of known vulnerabilities in software.

### Software Database

A database containing scanned software packages with information about the package's licenses and vulnerabilities.

### Policies

A database containing policies regarding acceptable licenses and vulnerabilities for software packages.

## Processes

### Analyze Software

Accepts a software package from a developer, checking it against the NIST Vulnerability Database and the License Scanner before storing the results in the Software Database and sending them to the developer.

### Scan for Licenses

The License Scanner checks a software package for licensed components, recording and returning information about any licenses found.

### Check Package Licenses and Vulnerabilities

Checks the Software Database for a package's licenses and vulnerabilites, sending them to a Developer or Manager on request.

### Add/Edit Package Policy

Allows a Manager to submit a package policy or view and edit an existing policy.

### Check Policy Compliance

Loads a software package's policy from the Policy Database and relevant details from the Software Database, then checks the package licenses and vulnerabilities against the policy. Sends the package's compliance results to the requesting Manager.

## Data Flows

### Software Package

A piece of software developed by a Developer to be scanned for licenses and vulnerabilities.

### Package Info

Identifying information for an already processed software package.

### Component Name

The name of a software component of a software package.

### Component Vulnerabilities

The vulnerability list for a component piece of software.

### Software Vulnerabilities

The vulnerability list for a software package.

### Software Licenses

The licenses of a software package.

### Package Policy

The license and vulnerability policy pertinent to a software package.

### Package Compliance

The compliance report for a software package against its relevant policy.

### Policy Request

A request to view an existing software policy.

### New Policy Info

The information to create a new policy or edit an existing one.