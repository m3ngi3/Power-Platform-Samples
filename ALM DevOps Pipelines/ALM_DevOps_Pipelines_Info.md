# Info about this folder

## What is in it?
- The folder [**ExportedSolutions**](./ExportedSolutions) is to represent a folder that will contain the Power Platform Solutions exported in their Unmanaged / Managed / Zipped / Unpacked form.
    - A [**DeploymentSettings**](./ExportedSolutions/DeploymentSettings/) subfolder will hold Environment specific Deployment Settings file. Following a Naming Convention using Library Variables used can save a lot of extra manual management.
- The folder [**Pipelines**](./Pipelines) should be the place where the Pipelines. Remember to give the correct path when saving a freshly created Pipeline in the Azure DevOps interface.
    - In the root folder the actual Pipeline definition lives.
    - A [**Templates**](./Pipelines/Templates/) subfolder will contain any reusable template.