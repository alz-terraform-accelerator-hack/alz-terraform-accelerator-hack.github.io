# Challenge 01

**[Home](./introduction.md)** - [Next Challenge >](./challenge-02.md)

## Description

In this challenge you will use the ALZ PowerShell Module to firstly, deploy the alz-terraform-accelerator and then, upon success, deploy the ALZ Terraform implementation into your Azure environment.

You will then validate some of the security features are working as expected.

## Success Criteria

- Successfully run the ALZ PowerShell Module, with `starter_module` set as "basic".
  - Verify the deployment by ensuring the following resources are created:
    - Repo containing ALZ code.
    - Pipelines:
      - Validation Pipeline
      - Deployment Pipeline
    - Storage Account in Azure.
    - Identities in Azure. (Service Principal)

- Deploy the the ALZ Terraform implementation with a single run of the Continuous Delivery pipeline/workflow.

- Branch off main in the repo containing the ALZ code and make a change (e.g. set `disable_telemetry = false`). Then open a Pull Request into main and verify that the Validation Pipeline runs. Once merged verify that the Deployment Pipeline runs.

## Resources

- [Quick Start](https://github.com/Azure/alz-terraform-accelerator/wiki/%5BUser-Guide%5D-Quick-Start)
- [Starter Modules](https://github.com/Azure/alz-terraform-accelerator/wiki/%5BUser-Guide%5D-Starter-Modules)
