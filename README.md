Enable or disable auto-shutdown on Azure virtual machines
=========================================================

            

**Description**

The Set-AzureRmVMAutoShutdown script sets the auto-shutdown property for a virtual machine. The script itself will check for the mandatory Azure PowerShell modules, the account context and if the virtual machine exists.

**Usage**


Login to your Azure account using the 'Login-AzureRmAccount' cmdlet. Once logged on, you can use this script to enable or disable the auto-shutdown property of a virtual machine. Use 'Get-Help Set-AzureRmVMAutoShutdown.ps1 -Full' to retrieve full help information
 and examples.


**Prerequisites**


This script needs to Azure PowerShell modules installed, which can be downloaded from https://azure.microsoft.com/en-us/downloads/.


**Changelog**


2018-07-11: Added parameter to set email notifications and updated used API version


**Code**

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
