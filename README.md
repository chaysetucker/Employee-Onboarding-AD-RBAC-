# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement

Northstar Medical Group (NMG) is a simulated healthcare company that was growing quickly and had its identity lifecycle managed by a third party MSP. As the company grew, the lack of structure started to create problems. There was no RBAC policy in place, users were being given access on an ad hoc basis, and there was no clear audit trail for tracking access. These issues made onboarding harder to manage and created unnecessary security and HIPAA risks.

## Solution Overview

For this project, I built a basic employee onboarding environment in Active Directory for NMG. I created the NMG.com domain and organized users into Finance, HR, IT, and Operations OUs. I also created security groups for each department and used a flat Role Based Access Control (RBAC) model to manage access. Users were provisioned into the appropriate OU and security group based on their role instead of being given access individually. I also worked through a simulated incident where a user was assigned the wrong permissions, identified the cause, and corrected their OU and security group assignments.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used

* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* Role Based Access Control (RBAC)
* GitHub

## Project Timeline

* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG 0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments

* Built the NMG.com Active Directory domain from scratch
* Created four departmental OUs and their corresponding security groups
* Provisioned users and assigned access based on their roles using security groups
* Troubleshot and corrected a simulated user access issue involving incorrect OU and security group assignments
