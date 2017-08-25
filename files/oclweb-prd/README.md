## Description

OCL web for production.

Check <https://github.com/OpenConceptLab/oclweb/tree/jetstream> for details.

Please set the following variables in .env:

```
ENVIRONMENT=production
ROOT_PASSWORD=<appRootPassword>
POSTGRES_USER=ocl
POSTGRES_PASSWORD=<someSecret>
OCL_API_TOKEN=<apiToken>
OCL_ANON_API_TOKEN=<apiToken>
OCL_API_HOST=https://oclapi.openmrs.org
```