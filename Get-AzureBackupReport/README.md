# Author_Name : Taskal SAMAL

# Author_EmailID: cloud.samaltaskal@outlook.com

# Get-AzureBackupReport

# Challenges  

Unable to retrive FilesFolder Backup Job Reports from AzurePowerShell.

# Mitigation

Used AzurePowerShell & Azure CLI to get Snaphot & FilesFolder Backup Job Reports.

# Purpose 

This is regarding the getting the Azure Backup Report for both Snapshot & FilesFolder Backup Type from Azure Recovery Services Vault and send it to email using SengGrid account for all the subscriptions that you have access to.

The report will be in excel sheet along with inbuilt Pivot Table.

# Below are the information that the script is retriveing from Azure Recovery Services vault.

1. Subscription
2. ResouceGroup
3. Vault
4. JobID
5. ServerName
6. JobType
7. Status
8. Task
9. BackupSize
10. StartTime
11. Duration
12. ErrorDetails
13. Recommendations

# Prerequisites :   

1. Install Azure PowerShell (Install-Module -Name Az -AllowClobber -Scope CurrentUser).   
2. Install Azure CLI (https://aka.ms/installazurecliwindows).   
3. Install ImportExcel (Install-Module -Name ImportExcel -RequiredVersion 5.4.0).   
4. Azure Account.   
5. SendGrid Account.
