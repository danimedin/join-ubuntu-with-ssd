Receta ANSIBLE para unir un equipo UBUNTU/Debian a un dominio con el cliente SSSD.

Utiliza el fichero encryptado con ansible-vault domain-info.yml con las variables del dominio.
Se adjunta un fichero de ejemplo domain-info.yml.example para ver su contenido.

Despues de modificarlo
```
mv domain-info.yml.example domain-info.yml
ansible-vault crypt domain-info.yml
```




