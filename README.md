# UDOM BloodLink

A responsive public-facing website prototype for the proposed UDOM Blood Donor Management and Emergency SMS System.

## Current contents
- `index.html`: public landing page
- `assets/style.css`: responsive design

## Important status
This commit is **website version 1 (front-end landing page)**. It is not yet the complete donor-management application. It does not currently store donor records, provide staff authentication, connect to a database, or send SMS messages.

## Planned next development
1. Secure staff authentication and role-based access.
2. MySQL database and donor registration with informed consent.
3. Donor search and availability management.
4. Emergency blood request tracking.
5. SMS gateway integration after provider, credentials and costs are confirmed.
6. Testing, privacy review and deployment.

## Safety
Use synthetic data during development. Do not upload real student names, phone numbers, blood groups, medical records, passwords or API keys to this public repository. Donor eligibility must be assessed by qualified healthcare professionals. Obtain institutional approval before collecting real data or using the system operationally.

## InfinityFree deployment
InfinityFree supports PHP and MySQL as well as uploads through its online File Manager or FTP. Upload the website files into the domain's `htdocs` directory. The current static landing page needs no database. The planned application will require database setup and secure configuration before real use.
