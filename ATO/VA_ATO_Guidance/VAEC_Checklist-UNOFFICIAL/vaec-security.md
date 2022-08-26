# VAEC ATO: Securing Veteran Data in the Cloud

Reference: 
https://vaww.portal.va.gov/sites/ECS/Pages/Cybersecurity-in-the-VAEC.aspx


Ensuring that sensitive Veteran data is secure, available, and safe from cyber threats is among the highest priorities of VA OIT and the Enterprise Cloud Solutions Office (ECSO).  For that reason, VAEC applications must meet the same rigorous cybersecurity requirements as any other VA IT system.  These requirements are defined by the VA Handbook 6500 and the National Institutes of Standards and Technology (NIST) cybersecurity standards. 

In a typical on-premises application (i.e., an app hosted in a VA-owned data center), the IT and Operations Services (ITOPS) team is typically responsible for security from the networking components through application-level security.  Cloud-leveraged systems use a shared responsibility model where the accountability for security is split among the Cloud Service Provider (CSP), the VA enterprise, the VAEC team, and the project team.  This has two benefits.  First, VA can take advantage of the billions of dollars of investments in security made by CSPs to build secure applications faster.  Second, VA project teams can obtain an Authority-to-Operate or ATO more quickly since their applications are only reviewed for the security controls that they are responsible for.  The remaining security controls are "inherited" from the lower layer components which have already by tested by the Federal Risk and Authorization Management Program (FedRAMP) or VA OIT.

Typical Shared Responsibility Model

ATO-Typical Shared Responsibility Model.jpg 

## Getting Thru the Cloud ATO Process Quickly

The ECSO team, working with VA cybersecurity groups such as the Office of Information Security (OIS), has developed three documents to help your project team go through the ATO process quickly:

### VAEC Application On-Boarding Form
Provides a quick description of your new or to-be-migrated application. Filled out by the project manager, it is designed to help VA and ECSO cybersecurity staff quickly understand your cloud-leveraged systems and its requirements.  When complete, this form should be sent to ecsoinfo@va.gov.

https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/VAEC_Application_Onboarding_Form.pdf

### Cloud ATO Process
Explains how to get a VA ATO for a cloud-leveraged system. *This document doesn't replace existing VA ATO process documentation* but is meant to supplement it by explaining how the ATO process works with a cloud-leveraged system. 

https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/Cloud_ATO_Process_2018-11-09.pdf


* Pre-Submission Checklist
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/Cloud_ATO_Checklist-FULL.pdf

* Cloud Authority to Operate (ATO) Checklist - Cloud authorization checklist for deployments within the VAEC
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/Cloud_ATO_Checklist.pdf


### Customer Responsibility Matrix (CRM)
Building on the concept of the shared responsibility model, the CRM identifies who is responsible for which NIST security control.  This responsibility will shift based on the service model used: SaaS, PaaS or IaaS.

https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/VAEC_CRM_2019-02-06.xlsx

The following templates include the VAEC information and can be used as a basis for your documents:

AWS Incident Response Plan (IRP) Template
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/VAEC_AWS_IRP_Template_2018-11-30.docx

AWS Disaster Recovery Plan (DRP) Template  
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/VAEC_AWS_DRP_Template_2018-11-25.docx

AWS Configuration Management Plan (CMP) Template
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/VAEC_AWS_CMP_Template_2018-11-25.docx

AWS Information System Contingency Plan (ISCP) Template
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/VAEC_AWS_ISCP_Template_2018-11-25.docx


### Nessus scans
The VAEC Security team can run UNOFFICIAL pre-ATO Nessus scans for your environment to aid in assessing your security posture. Download the following documents:

Instructions for submitting a scan request
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/Nessus_Scan-Application-template.xlsx

Template for Nessus scan
https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/ATO/VAEC_Guide/source/Nessus_scan-Information_required_to_run_in_VAEC.docx

