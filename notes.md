##Ejemplo creación de rol usano Azure Cli:
------------------------------------------------
```
az ad sp create-for-rbac --name "myApp" --role contributor --scopes /subscriptions/{subscription-id}/resourceGroups/{resource-group} --json-auth

```
