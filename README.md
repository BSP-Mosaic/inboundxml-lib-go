# InboundXML

## Module publish instructions

Use the `publish.sh` script to publish this Go project to the Artifactory go-local repository

```sh
./publish.sh v1.0.0
```

Please check the current version on Artifactory before publishing.

Ensure that ARTIFACTORY_ACCESS_TOKEN, ARTIFACTORY_URL, and ARTIFACTORY_USERNAME are present in the environment variables before using the script.
