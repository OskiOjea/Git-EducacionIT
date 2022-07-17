# CLASE 01

## MARKDOWN

# H1
## H2
### H3
#### H4
##### H5
###### H6

### Negrita

**Soy Texto en Negrita**

### Cursiva

*Texto en cursiva*

### Negrita y Cursiva

***Negrita y Cursiva***

### Listas Ordenada

1. Item
2. Item
3. Item

### Lista Desordenada

* Item
* Item
* Item

### Separador
---

## CONSOLA
## Para mostrar la carpeta en la que estoy:
ls
## Para entrar al directorio:
cd clase01 (por ejemplo)

    cd clase01
---
```sh
    ls #veo los archivos dentro de la carpeta
```
    cd.. #vuelvo al directorio

## COMANDOS CONSOLA

* ls: listar directorios
* cd: Cambiar directorios
* cd .. : Vovler para atras un directorio
* cd ../cd .. : Para volver dos directorios
* touch <nombarch> Para crear un archivo
* mkdir : para crear directorios

---

### Para verificar la version de GIT:
    git -- version #codigo para detectar version

### Otra opcion es usando Backtick seguido del lenguaje que usare

```sh
git -- version #codigo para detectar version
```

```php
$Varialbe = "Hola Mundo"
```

```js
function sumar (a,b){
    return a+b
}
```
---
## Antes de comenzar a trabajar con GIT debo realizar la configuracion global

## Configuracion Global de GIT
    git config --global user.name "Oscar Ojea"
    git config --global user.email "oskiojea@gmail.com"

## Para visualizar las configuraciones:
    git config --get-regexp user


## Crear un repositorio
    git init

## Areas en GIT
* Working Directory (WD): Vamos a tener todos los archivos del proyecto
* Staging Area (SA): Area intermedia de confirmacion de cambios
* Local REPO (cajita de fotos - "Commits"  que voy haciendo)

---
## Para saber el estado de los archivos en WD:

    git status

## Para pasar del status WD al SA uso el comando:

    git add

## Para pasar del status de SA al LR(Local REPO) uso el comando:
    
    git commit -m "Nombre del commit"

git status

## Para ver las diferencias entre el WD y el Local Repo:

    git diff








