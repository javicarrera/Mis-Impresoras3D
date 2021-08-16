# Mis-Impresoras3D
Recursos para mis impresoras


Para recursos que ocupen mucho hay que proceder de otra forma, a través de la Git Large File Storage. 

1. Instalar https://git-lfs.github.com/
2. Iniciar git lfs 'git lfs install'
   
Hasta aquí se hace para cada cuenta de usuario 
A partir de ahora en cada repositorio hay que seleccionar el tipo de arquivos que quieres que maneje el LFS

'git lfs track "*.psd"'
'git lfs track "*.STEP"'
...
Añadir a git el archivo .gitattributes que ha sido creado automáticamente:
'git add .gitattributes'

Commit & push a Github como siempre...
'''
git add file.psd
git commit -m "Add design file"
git push origin main
'''