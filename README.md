# azsdkexample
azure sdk for go example demonstrates the following concepts.

1. Using `auth.NewAuthorizerFromEnvironment()` for authorization.
2. ...

# How to Build

1. Execute `go get https://github.com/bartvanbenthem/azsdkexample`
2. Execute `dep ensure`
3. Execute `go build`

# How to Run

Set the appropriate environment variables depending on the type of authentication you wish to use.
For authorization with a service principal set the following environment variables.
```
AZURE_CLIENT_ID
AZURE_CLIENT_SECRET
AZURE_TENANT_ID
AZURE_SUBSCRIPTION_ID
```
More information about authorization can be found [here](https://github.com/azure/azure-sdk-for-go#more-authentication-details).
