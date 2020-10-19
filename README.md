Update Management - Turn On VMs
===============================

            


This script is intended to be run as a part of Update Management Pre/Post scripts.

It requires the ThreadJobs modules from the PowerShell gallery.


It requires a RunAs account.
This script will ensure all Azure VMs in the Update Deployment are running so they recieve updates.
This script works with the [Turn Off VMs](https://gallery.technet.microsoft.com/Update-Management-Turn-Off-be60ed99) script. It will store the names of machines that were started in an Automation variable so only those machines are turned back off when the deployment is finished.


 





        
    
Note: TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group.
