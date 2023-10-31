#### Login to pcf
```sh
cf login -a <> --skip-ssl-validation
```
### Command to get auth token
```sh
cf oauth-token
```
### Run the scanner jar by replacing the url and auth-token


### Install the  app-info plugin from [app-info](https://github.com/rahulkj/app-info)
```sh
cf install-plugin <Path-To-The-Downloaded-Location>/app-info-<OS>-amd64 -f
```
### Run the plugin to the data in csv
```sh
cf app-info --csv
```
### Run the below command to get the manifests

```sh
cf app-info manifests
```
