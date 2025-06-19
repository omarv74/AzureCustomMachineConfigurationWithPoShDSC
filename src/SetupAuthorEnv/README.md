# Setup the authoring environment

https://learn.microsoft.com/en-us/azure/governance/machine-configuration/how-to/develop-custom-package/1-set-up-authoring-environment

To install the **GuestConfiguration** module on either Windows or Linux, run the following command in PowerShell 7.

``` PowerShell
# Install the machine configuration DSC resource module from PowerShell Gallery
Install-Module -Name GuestConfiguration

# Validate that the module has been imported:
# Get a list of commands for the imported GuestConfiguration module
Get-Command -Module GuestConfiguration

# Install PSDesiredStateConfiguration version 2.0.7 (the stable release)
Install-Module -Name PSDesiredStateConfiguration -RequiredVersion 2.0.7
Import-Module -Name PSDesiredStateConfiguration
```
