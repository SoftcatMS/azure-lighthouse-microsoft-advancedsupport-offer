# Azure Lighthouse Managed Offer
Stores the Azure Lighthouse Microsoft Advanced Support Offer template that can be used to provide delegation to customer environments from objects within the Softcat Partner account

The following permissions are included in this lighthouse offer.

# Delegated Permissions

| User/Group                                    | Delegated Permission                                 | Access Type | Max Duration | MFA   | Approvers                      |
| --------------------------------------------- | ---------------------------------------------------- | ----------- | ------------ | ---   | ------------------------------ |
| ALH - Managed Azure Engineers                 | Reader                                               | Permanent   | -            | -     | -                              |
| ALH - Managed Azure Engineers                 | Support Request Contributor                          | Permanent   | -            | -     | -                              |
| ALH - Managed Azure Engineers                 | Managed Services Registration Assignment Delete Role | Permanent   | -            | -     | -                              |
| ALH - Managed Azure Service Delivery Managers | Reader                                               | Permanent   | -            | -     | -                              |
| ALH - Managed Azure Services                  | Reader                                               | Permanent   | -            | -     | -                              |
| ALH - Managed Azure Services                  | Support Request Contributor                          | Permanent   | -            | -     | -                              |

# Deploy to Azure 

Use the below button to deploy this Azure Lighthouse offer to a tenant.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSoftcatMS%2Fazure-lighthouse-microsoft-advancedsupport-offer%2Fmain%2Fproduction-lighthouse-offer.json)