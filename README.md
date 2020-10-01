# Trabajo práctico ISW 2020 - Grupo 5

## Integrantes del Grupo 5 📋

* Gattarelli, Ignacio
* Manzo, Juan Pablo
* Müller, Melisa
* Wernly, Gabriel

### Consignas

### Punto 2

```
a) Realizar una modificación y publicarla (Push)
```
Primer commit: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/commit/6df43dee8cf4ef80db14a4e4097735344381d67e

```
b) ¿Cómo hacemos para no subir cambios de configuraciones locales? Configurar el repositorio para ignorar estos archivos.
```
Utilizamos el archivo .gitignore para que no existan cambios en configuraciones locales. Dependiendo el _**nombre de carpeta**_ a ignorar, o _**.nombre de carpeta**_ para los archivos que contienen ésta carpeta, o _** '*.para carpetas recursivas' **_ con archivos que desees ignorar

```
c) Crear un nuevo branch para Release 1
```
Se creó branch release/1

```
d) Crear un nuevo branch para Release 2
```
Se creó branch release/2

```
e) Realizar modificaciones en Release 1
```
Modificaciones en release/1 : https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/commit/41ecafab4ac478d9a4e63fbe5e49d64cdf637d31

```
f) Crear un PR sobre Release 2 y realizar modificaciones
```
Pull Request: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/commit/4671bfa9bbf1c8927a77db81cbbcd945b7d77be1

```
g) Llevar al entorno productivo Release 1. ¿Cómo lo hace siguiendo Gitflow?
```
Tag v1.0.0: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/releases/tag/v1.0.0

```
h) Lograr un merge de ambas ramas con master. Publicar una nueva versión.
```
Tag v2.0.0: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/releases/tag/v2.0.0

```
i) Crear otra rama para incorporar una nueva funcionalidad.
```
Nueva rama feature/f1: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/tree/feature/f1

```
j) Sobre esta nueva rama, creada en el punto anterior, realizar una modificación A y publicarla (push). Luego realizar una modificación B y publicarla (push). Deshacer la modificación B volviendo al estado en A.
```
Commit de Revert: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/commit/bbdf5a30c93db6ea57b86315db3721bfe378dcc9

```
k) Llevar los cambios de la rama creada en el punto i a producción. ¿Cómo lo hace siguiendo Gitflow?
```

Son necesarios 3 pasos a seguir.

Desde branch feature/f1, un PR con branch Develop: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/pull/5

Desde branch Develop anterior, un PR con branch release/release3:
https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/pull/6

Desde branch release/release3 anterior, un PR con branch master: https://github.com/jpmzo/ISW-Grupo5-Gattarelli-Manzo-Muller-Wernly/pull/7


### Punto 3

```
a) Realizar un readme para el código subido. ¿Qué cosas podrían? Versionar el README en el repositorio.
```
La información que puede contener el archivo README:

* Funcionalidades del proyecto (que hace el proyecto)
* Utilidad del proyecto
* Manual de instalación y aclaración de componentes que lo integran (serie de pasos para lograr su correcta instalación en respectivos sistemas operativos, detalles técnicos, etc).
* Contacto para quienes necesiten un soporte personal de ayuda para usuarios
* Fichero de quienes aportan o contribuyen con el proyecto

```
b) Si un externo realiza una modificación. Les gustaría que complete cosas en el PR para entender el cambio. ¿Qué datos le pediría?, ¿Qué nos ofrece GitHub para ayudarnos con esto?
```

Github nos ofrece las revisiones de solicitudes de extracción, llamada _Reviewers_, donde  pueden comentar cambios propuestos, aprobar cambios o solicitar mas cambios como colaboradores del proyecto.

Una revisión posee 3 posibles estados:
* Comentarios: Agrega comentarios sin necesidad de modificar cambios.
* Aprobar: Puede enviar comentarios y el permiso para hacer un merge de cambios propuestos-
* Solicitar cambios: Envía comentarios y solicita cambios antes de que pueda realizarse un merge en la solicitud de extracción.
