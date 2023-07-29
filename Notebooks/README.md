<p align="center">
    <h1 align="center">
        Power Platform Notebooks
    </h1>
</p>

## Prerequisites

To be able to use the notebooks in this repository, you will need:
- Option 1 (*local*)
   - [**VS Code**](https://code.visualstudio.com/)
   - The [**.Net Interactive Notebooks**](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) extension installed

> Note: You will need the [**.NET 6 SDK**](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) to be able to use this extension.

- Option 2: use [GitHub Codespaces](https://github.com/features/codespaces) with the **dev container** definition in this repository.

## Organization

| **Folder**              | **Description**                                                                                                                                                                                                                                                                                                                            |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Learning](./Learning/) | For notebooks that will help people learn how to user notebooks in Power Platform context or other concepts related to Power Platform (*like how to use the [**Microsoft.PowerPlatform.Dataverse.Client**](https://docs.microsoft.com/en-us/dotnet/api/microsoft.powerplatform.dataverse.client?view=dataverse-sdk-latest) NuGet package*) |
| [Support](./Support/)   | For notebooks that could directly be used by you or your team for support tasks (*like the verification of the configuration of a user in case of access issues*)                                                                                                                                                                          |
| Administration          | For notebooks that could directly be used by you or your team for administrative tasks (*like create and configure a new Azure AD Security Group Team in an environment*)                                                                                                                                                                  |

## External notebooks

### Learning

| **Link**                                                                                                                                     | **Description**                                                                                          |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| [rajyraman/polyglot-notebook-ideas](https://github.com/rpothin/Power-Platform-Notebooks)                                                     | "Experiments with Polyglot Notebooks" with great ideas like using SQL 4 CDS in a Notebook                |
| [rajyraman/Dataverse-Interactive-Notebook](https://github.com/rajyraman/Dataverse-Interactive-Notebook/blob/main/Dataverse%20Notebook.ipynb) | "This notebook demonstrates how you can use interactive notebooks with PowerPlatform .net core assembly" |
| [rajyraman/Playwright-Dataverse-Notebook](https://github.com/rajyraman/Playwright-Dataverse-Notebook/blob/main/notebooks/playwright.ipynb)   | Notebook that demonstrates how to use Playwright with a model driven app                                 |