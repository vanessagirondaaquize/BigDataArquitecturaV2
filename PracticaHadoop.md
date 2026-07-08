# Laboratorio 1 Hadoop

## Descripción del Repositorio
Habilita el repositorio:

- Hadoop
- Hive

Todo el contenido se ejecutara en codespace de github.

## Desplegar container

1. Crear un codespace para el repositorio e ingresar al mismo
2. Abrir terminal de codespace
3. Considerar el archivo docker-compose-hadoop.yml
4. Ejecutar el siguiente comando para desplegar los contenedores<br>
```    >_ docker-compose up     ``` <br>

#### PRACTICA 1 ## 

1 Descargar un set de datos en formato csv

2 crear base de datos en mysql de su preferencia

3 Importar la base de datos con la herramienta adminer


### Error al subir cambios
```    $ git add . && git commit -m "update" && git push origin master     ``` <br>
```    error: failed to push some refs to xxxxxxxx ``` <br>
```    hint: Updates were rejected because the remote contains work that you do not``` <br>
```    hint: have locally. This is usually caused by another repository pushing to``` <br>
```    hint: the same ref. If you want to integrate the remote changes, use``` <br>
```    hint: 'git pull' before pushing again.``` <br>
```    hint: See the 'Note about fast-forwards' in 'git push --help' for details.``` <br>
```    $ git push origin master --force``` <br>
```    $ git add . && git commit -m "update" && git push origin master``` <br>
