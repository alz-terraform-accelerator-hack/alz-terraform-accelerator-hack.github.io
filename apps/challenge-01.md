# Challenge 01

**[Home](./introduction.md)** - [Next Challenge >](./challenge-02.md)

## Description

In this challenge you will deploy the alz-terraform-accelerator using the Azure DevOps version control system with the full security features enabled, and then subsequently deploy some sample infrastructure using Azure Pipelines.

## Success Criteria

- Successfully run the ALZ PowerShell Module, with `starter_module` set as ".test" (Note: ".test" does not exist in the documentation, but it is a valid starter_module that is not related to the ALZ.)
  - Ensure that before you run the Azure Pipeline, somebody reviews the Terraform apply at runtime.
  - Ensure that you are using OpenID Connect (OIDC) for authentication.
  - Validate all artifacts have been deployed: Repos(ADO), Storage Account(Azure), Pipelines(ADO), Identities(Azure) and Service Connections(ADO).

- Deploy the infrastructure in your main repo using Azure Pipelines.

- Branch off main in the repo containing the terraform code and make a change (e.g. up the `length` input in `random_string` to 11). Then open a Pull Request into main and verify that the Validation Pipeline runs. Once merged verify that the Deployment Pipeline runs.

## Resources

- [Quick Start](https://github.com/Azure/alz-terraform-accelerator/wiki/%5BUser-Guide%5D-Quick-Start)
- [Apply Approvers](https://github.com/Azure/alz-terraform-accelerator/wiki/%5BUser-Guide%5D-Quick-Start-Phase-2#:~:text=the%20bootstrap%20setup.-,apply_approvers%3A%20This%20is%20a%20list%20of%20service%20principal%20names%20(SPN)%20of,filling%20this%20out%20as%20it%20can%20vary%20based%20on%20identity%20provider.,-root_management_group_display_name%3A%20The%20is)
