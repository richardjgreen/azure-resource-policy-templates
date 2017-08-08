# azure-resource-policy-templates
Repository for all Azure Resource Manager Resource Policy templates.

These policy templates can be used to apply restrictions to an Azure Subscription, Resource Group or Resource Type. The restrictions can include limiting locations, resource types entirely or the size of resource that can be deployed. Resource Policies can also be used to enforce mandatory resource tagging.

Policies included are:
- permittedLocationsEU | Only permits resource creation in EU Azure Regions
- permittedLocationsUK | Only permits resource creation in UK Azure Regions
- permittedVMSizes | Limits IaaS VM creation to a desirable subset of sizes
- permittedStorageAccountTypes | Limits Storage Account creation to a desirable subset of types
- forceVMNamingConvention | Enforces standardised naming convention to IaaS VM creation
- forceStorageAccountEncryption | Enforces Storage Accounts to use Storage Service Encryption (SSE)
- forceMandatoryARMTags | Enforces the use of mandatory Resource Tags on ARM resources
