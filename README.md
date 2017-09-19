# ARM Template Tests

To run with Azure CLI, use:

`az login`

`az group create --name examplegroup --location "UK South"`

`az group deployment create --resource-group examplegroup --template-file myTemplate.json --parameters parameterName=value otherParameter=otherValue`