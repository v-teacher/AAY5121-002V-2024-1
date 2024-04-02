Notas :notes:
======

Ejemplo creación de rol para 
RBAC usando Azure Cli :floppy_disk::
------------------------------------------------
```
az ad sp create-for-rbac --name "myApp" --role contributor --scopes /subscriptions/{subscription-id}/resourceGroups/{resource-group} --json-auth
```
