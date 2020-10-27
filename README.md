Starts virutal machines in a subscription using Python from Azure Automation
============================================================================

            




Starts Azure resource manager virtual machines in a subscription. An Azure Automation RunAs account is required for this runbook.

This Azure Automation runbook runs on Azure to start Azure vms in a subscription.
If no arguments are specified, then all VMs that are currently stopped are started.
If a resource group is specified, then all VMs in the resource group are started.
If a resource group and VM are specified, then that specific VM is started.

Args:
    groupname (-g) - Resource group name.
    vmname (-v) - virtual machine name

    Starts the virtual machines
    Example 1:
            start_azure_vm.py -g <resourcegroupname> -v <vmname>
            start_azure_vm.py -g <resourcegroupname>
            start_azure_vm.py


 



** *** *




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
