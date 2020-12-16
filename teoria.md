<!--Estados de GIT -->

1. Working Directory ( Directorio de Trabajo )
    - Es donde tenemos todos nuestros archivos
    - Nuestro Proyecto
2.  Staging Area ( Area de Preparacion )
    - Todo lo que esta listo , para realizar cambios
    - Todo lo que hemos modificado 
3.  .git Directory 
    -   Todos los cambios confirmados, o cambios realizados
1       -           2            -        3
    (git add)               (git commit)
     git add .

    Configurar nombre: git config --global user.name "Ricardo"
    Configurar correo: git config --global user.name "jr.naldos@gmail.com"

Primero iniciar git init
git add . 
luego:   para hacer cambios: git commit -m 'create folder images'