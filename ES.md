# Executive Summary

This project will produce a system to aid developers and project managers in managing software licenses and vulnerabilities. The system will allow:

* **Developers** to submit software packages to be scanned for licenses and vulnerabilities.
* **Developers and Managers** to view the results of scanning a software package.
* **Managers** to create and view policies for software packages.

The new system will require databases for package scan results and policies. Changes will also be made to developer and manager workflow:

* **Developers** will be required to submit their packages for scanning before approval.
* **Managers** will be required to set policy and review package scans against the policy before approving a package.

To allow these changes to workflow, developers and managers require new authority:

* **Developers** must have the authority submit packages for scanning and view their scan results.
* **Managers** must have the authority to view package scans from their deveopers, create and edit policies for packages, and view those policies to check compliance.

To sustain the health of the system, it would be socially responsible to engage the communities of open source components of the system. In particular, the communities for the license scanner and vulnerability database should be engaged to support the communities and ensure the continued functionality of these resources as components of this system.
