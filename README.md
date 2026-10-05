#Basic Employee Onboarding (AD)(RBAC)

##Problem Statement
Northstar Medical Group (NMG) is a simulated company that had its Active Directory environment previously managed by an MSP. The environment lacked a clear structure for organizing employees and managing access. User onboarding and access were handled manually, which made it easier for users to be placed in the wrong groups or receive incorrect permissions. For a healthcare organization, these access issues could also create security concerns and potential HIPAA risks.

##Solution Overview
For this project, I rebuilt the NMG Active Directory environment from the ground up. I created the NMG.com domain and organized employees into Finance, HR, IT, and Operations OUs based on their departments. I created security groups for each department and used a flat RBAC model to manage access based on a user's role. I then provisioned users into the appropriate OUs and security groups so their access matched their job responsibilities. I also worked through an incorrect permission scenario to identify why a user had the wrong access and correct their OU and security group assignments.
Video Walkthrough
Video walkthrough coming soon.

##Tools Used
- Windows Server
- Active Directory Domain Services
- VirtualBox
- UTM
- RBAC
- GitHub

##Project Timeline
Day 1: Domain creation and domain controller promotion
Day 2: Organizational unit and security group design
Day 3: User provisioning and RBAC implementation
Day 4: Incident response and resolution (NMG 0047)
Day 5: Documentation and case study packaging

##Key Accomplishments
- Built the NMG.com Active Directory domain from scratch
- Created OUs and security groups to organize users and manage access by department
- Provisioned users and implemented role based access using security group membership
- Identified and corrected incorrect OU placement and security group membership during an access troubleshooting scenario
