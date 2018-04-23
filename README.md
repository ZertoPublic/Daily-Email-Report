# Legal Disclaimer 
This script is an example script and is not supported under any Zerto support program or service. The author and Zerto further disclaim all implied warranties including, without limitation, any implied warranties of merchantability or of fitness for a particular purpose.

In no event shall Zerto, its authors or anyone else involved in the creation, production or delivery of the scripts be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or the inability to use the sample scripts or documentation, even if the author or Zerto has been advised of the possibility of such damages. The entire risk arising out of the use or performance of the sample scripts and documentation remains with you.

# Daily Email Report 
This script will automate the creation of multiple reports across many Zerto Virtual Managers and vCenters. The script will them provide an email report to the appropriately configured email recipients. 

# Getting Started
Instructions on how to utilize this automation example can be found in Section 4.3 Daily Email Reports in the following whitepaper: http://s3.amazonaws.com/zertodownload_docs/Marketing_Material/White%20Paper%20-%20Automating%20Zerto%20Virtual%20Replication%20with%20PowerShell%20and%20REST%20APIs.pdf

# Prerequisites 
Environment Requirements
  - ZVR 5.0u3+
  - PowerCLI 6.0+ 
Script Requirements
  - Each combination of a vCenter and ZVM is referred to as a POD, add your PODs into the Create-vCenter Array function on line 24
  - POD ZVM user and password 
  - POD vCenter User and password
  - Email addresses to send email to 
  - SMTP server
  - SMTP user / password 
  - SMTP SSL enabled 
  - Start with default reports and customize from line 2500 
  - Run script manually or using Windows Task Scheduler 

# Running Script 
Once the necessary requirements have been completed select an appropriate host to run the script from. To run the script type the following: 

.\ZVRDailyEmailReport.ps1
