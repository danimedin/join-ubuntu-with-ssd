Receta ANSIBLE para unir un equipo UBUNTU/Debian a un dominio con el cliente SSSD.

Utiliza el fichero encryptado con ansible-vault domain-info.yml con las variables del dominio.
Se adjunta un fichero de ejemplo domain-info.yml.example para ver su contenido.

Despues de modificarlo
```
mv domain-info.yml.example domain-info.yml
ansible-vault crypt domain-info.yml
```

Tambien es necesario renombrar el fichero pam_mount.conf.xml.example a pam_mount.conf.xml. 
Este archivo contiene los shares que se montan en el inicio de sesión del usuario


