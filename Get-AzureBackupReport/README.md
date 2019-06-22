#Challenges  

Unable to retrive FilesFolder Backup Job Reports from AzurePowerShell.

#Mitigation

Used AzurePowerShell & Azure CLI to get Snaphot & FilesFolder Backup Job Reports.

#Purpose 

This is regarding the getting the Azure Backup Report for both Snapshot & FilesFolder Backup Type from Azure Recovery Services Vault and send it to email using SengGrid account for all the subscriptions that you have access to.

The report will be in excel sheet along with inbuilt Pivot Table.

#Below are the information that the script is retriveing from Azure Recovery Services vault.

Subscription
ResouceGroup
Vault
JobID
ServerName
JobType
Status
Task
BackupSize
StartTime
Duration
ErrorDetails
Recommendations


#Author_Name : Taskal SAMAL

#Author_EmailID: cloud.samaltaskal@outlook.com

#Prerequisites :   

1. Install Azure PowerShell (Install-Module -Name Az -AllowClobber -Scope CurrentUser).   

2. Install Azure CLI (https://aka.ms/installazurecliwindows).   

3. Install ImportExcel (Install-Module -Name ImportExcel -RequiredVersion 5.4.0).   

4. Azure Account.   

5. SendGrid Account.
