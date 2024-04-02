:notes:Notas:notes:
======

:floppy_disk: Ejemplo creación de rol para RBAC usando Azure Cli:
------------------------------------------------
```
az ad sp create-for-rbac --name "myApp" --role contributor --scopes /subscriptions/{subscription-id}/resourceGroups/{resource-group} --json-auth
```
Reemplace _subscription-id_ y _resource-group_ with your data