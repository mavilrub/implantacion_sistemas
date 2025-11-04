

### Conclusiones del Tema 1

En este tema hemos aprendido que:

- Los sistemas operativos son la base de cualquier sistema informático.  
- Su instalación requiere planificación y verificación de requisitos.  
- Existen distintos tipos de instalación según las necesidades del usuario.  



```powershell

New-LocalUser -Name "usuario1" -FullName "Usuario de Prueba" -Description "Cuenta local de ejemplo" -Password (ConvertTo-SecureString "P@ssw0rd123" -AsPlainText -Force)

Add-LocalGroupMember -Group "Administradores" -Member "usuario1"

Get-LocalUser
```


---

!!! success "Has completado el Tema 1 🎉"
    Ya estás preparado para continuar con el **Tema 2: Administración básica del sistema**.