# TeamsProvisioning

## Installation

Rough steps are:

 * Register an app and give it Group.ReadWrite.All app permissions. Generate a key.

 * Create a Key Vault and add the key

 * In the TeamsProvisioningRG folder, create a parameters.json file for your target environment

* Edit and adapt one of the InstallDev.ps1 or InstallProd.ps1 with your parameter file name and desired geography

* Run Connect-AzureRmService, and then the Install command you just edited

* Find the storage account and get the queues, and wire them to a Flow

