# Senior Design Proposal - ReptiSense Integrated Reptile Enclosure
Kennesaw State University - CPE 4800 Senior Design Proposal - Professor Hai Ho 2025/26 - Team 5 ReptiSense Tank

## Overview
### Description
The ReptiSense Integrated Reptile Enclosure is a fully integrated enclosure that automates enclosure humidity, heating, lighting and feeding via an embedded control system while interfacing with a mobile user application to provide real-time updates, manual system control, and viewing of live cameras & interactive infrared heat maps. Additionally, the system will integrate with edge-based machine learning to provide adaptive updates and advice based on an animal's observed behavior.

### Team
Chandler Thornton
Corey Mackey
Alseny Diallo
Andy Phan

## Technical
### Documents
All important files can be found at (https://drive.google.com/drive/folders/10bbPidWtf0gV37GVmjmyDQL_MalgVVPm?usp=drive_link) including:
- Ideation phase documentation
- Formal Project Proposal Document
- In-class project proposal presentation
- System Requirements Document
- Bill of Materials
- ...

### Features
- Ambient humidity / temperature sensing
- Surface temperature sensing via IR camera
- Live camera view streaming
- Automated control system/time based lighting/heating
- Automated control system/time based misting
- Automated time based feeding
- Mobile user application

## Procedures
This set of rules and procedures lays ground work that will keep the team's project organized throughout the year.

### Software/Firmware Development
#### Requirements
- GitBash (or similar)
- Visual Studio Code
- VSCode Extensions: PlatformIO, ..., ..., ...

#### Version Control Policy
New features and changes should be broken up into digestible commits that can easily be reviewed. Commits should not be incomplete or excessively large.
To protect against versioning issues & confusion, a ruleset has been applied to the repository including:
- Block all force pushes
- Restrict deletions
- Require pull request before merging branch
- Require 3 approvals before merging branch

#### Cloning project
1. Create new branch on GitHub browser with naming convention 'main-working-FEATURE' (eg. 'main-working-tempsensor')
2. Clone branch locally from GitBash or similar terminal with
```
git clone https://github.com/chandler-thornton/Senior-Design-Proposal.git
```
3. Open folder within VSCode's 'Source Control' tab
4. Switch to your branch

#### Commiting Changes
1. From VSCode Source Control tab, write commit message and click blue 'Commit' button
2. Click blue 'Sync' button 
