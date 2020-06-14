# StopAllAzureVMs
PowerShell script designed to be run in Azure Automation that will enumerate all VMs in all Resource Groups and shut them down.  It has an exception list for those VMs you never want to shut down.  At the end of the Job it will send email with the current status of all VMs
