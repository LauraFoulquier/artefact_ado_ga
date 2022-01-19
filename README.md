# Deploying artefact to Azure DevOps (ADO)

## .npmrc files
The following secrets need to be added in your github repository:
- AZURE_ARTIFACTS_PAT_B64 : your PAT encoded in base64
- AZURE_ORGANIZATION_NAME
- AZURE_ARTIFACTS_FEED_URL

> All the above data are available in ADO (see References below if you need a hand). Select "Other" after clicking "Connect Feed"

## Installing library from ADO
See work done on the `install_library` branch, specifically on file `fetch_artefact.yml` 

## References
- https://docs.microsoft.com/en-us/azure/devops/artifacts/get-started-npm?view=azure-devops&tabs=Windows
