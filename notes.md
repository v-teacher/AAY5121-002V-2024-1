:notes:Notas:notes:
======

Ejemplo creación de rol para RBAC usando Azure Cli:
------------------------------------------------
```
az ad sp create-for-rbac --name "myApp" --role contributor --scopes /subscriptions/{subscription-id}/resourceGroups/{resource-group} --json-auth
```
:floppy_disk: Reemplace _subscription-id_ y _resource-group_ con los datos de su subcripción :nail_care:
