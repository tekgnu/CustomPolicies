This GitHub Repo is to help build and prototype JSON Configurations for Azure Policies. JSON policies in Azure should implemented to help uniformly add governance and controls over Azure Resource Groups, Subscriptions, and even across Tenants (via Management Groups). See Microsoft's Cloud Adoption Framework for more details - https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/index

* Newly added the Deploy GRS on Production (or the dep rules and parameter) custom policy.  This allows you to deploy with a remediation task GRS on any storage account with the defined tags (in my case I used environment: production).

Helpful Links for developing Azure Custom Policies:

Core Governance and Policy documentation: https://docs.microsoft.com/en-us/azure/governance/policy/ 
Link to Microsoft Azure sample Policies: https://docs.microsoft.com/en-us/azure/governance/policy/samples/  
Azure Policy Definition: https://docs.microsoft.com/en-us/azure/governance/policy/concepts/definition-structure  
For more information on Azure Policy Effects: https://docs.microsoft.com/en-us/azure/governance/policy/concepts/effects 

GitHub repository for Azure Policy samples to build from : https://github.com/Azure/azure-policy

Lastly just a quick note on implementing the Policy definitions in Powershell see - https://docs.microsoft.com/en-us/azure/governance/policy/samples/enforce-tag-value#deploy-with-powershell or cli - https://docs.microsoft.com/en-us/azure/governance/policy/samples/enforce-tag-value#deploy-with-powershell

Note all code included in this site is for learning purposes and is for all to use at your own risk.
