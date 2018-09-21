ELIMIAR BLOB DE TRAKING
- Copiar un .sh desde https://github.com/nachoparker/git-forget-blob/blob/master/git-forget-blob.sh  Referencia : https://github.com/nachoparker/git-forget-blob
- Otorgar permisos de ejecución
- Ejecutar SH ./git-forget-blob sc.16.tar.gz 

CAMBIAR COMENTARIOS DE COMMITS
- Crear una rama a partir de master
- Eliminar los 6 ùltimos commits
- Cambiar el comentario del primer commit "git commit -m "feat(example): first commend"
- Cambiar a la rama creada a partir de master
- Rebasear contra master y ajustar "r"  a cada commit en interactive
- Cambiar los nombres de archivos y guardar
