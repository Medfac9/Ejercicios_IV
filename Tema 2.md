# Ejercicios del tema 2
## Ejercicio 1
Descargar y ejecutar las pruebas de alguno de los proyectos anteriores, y si sale todo bien, hacer un pull request a este proyecto con tests adicionales, si es que faltan (en el momento que se lea este tema).

## Ejercicio 2
Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo TDD).

Ejercicio resuelto en el repositorio del [Proyecto_IV](https://github.com/Medfac9/Proyecto_IV/blob/master/bot/test.py) para el [hito 2](https://github.com/Medfac9/Proyecto_IV/milestone/2), el [issue 2](https://github.com/Medfac9/Proyecto_IV/issues/2).

## Ejercicio 3
Convertir los tests unitarios anteriores con assert a programas de test y ejecutarlos desde mocha, usando descripciones del test y del grupo de test de forma correcta. Si hasta ahora no has subido el código que has venido realizando a GitHub, es el momento de hacerlo, porque lo vas a necesitar un poco más adelante.

~~~
from funciones import comprobarTrack
from pocha import it

@it('El numero de track no existe')
def checkNoTrack():
    assert funciones.comprobarTrack('234') == -1

@it('El numero de track existe')
def checkTrack():
    assert len(funciones.comprobarTrack("PQ48K20440124700118006G")) == 4
~~~

~~~
✓ El numero de track no existe
✓ El numero de track existe

2 passing (5362ms)
~~~

## Ejercicio 4
Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

Voy a instalar virtualenv, que es el entorno virtual para Python.

`pip install virtualenv`  

Después de instalarlo, creamos un entorno virtual con la versión que queramos. Para la major version:

`virtualenv --python=/usr/bin/python3.7 ./EnvPythonIV`

Para ejecutar el entorno usamos el siguiente comando:

`source ./EnvPythonIV/bin/activate`

Por último, para cerrar el entorno usaremos el comando `deactivate`

## Ejercicio 5
Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hacen prácticas los alumnos.

Las acciones serían:

Crear empresa. Listar calificaciones para cada empresa crear calificación y añadirla (comprobando que la persona no la haya añadido ya) borrar calificación (si se arrepiente o te denuncia la empresa o algo). Hacer un ránking de empresas por calificación, por ejemplo. Crear un repositorio en GitHub para la librería y crear un pequeño programa que use algunas de sus funcionalidades.  
Si se quiere hacer con cualquier otra aplicación, también es válido.

Se trata de hacer una aplicación simple que se pueda hacer rápidamente con un generador de aplicaciones como los que incluyen diferentes marcos MVC. Si cuesta mucho trabajo, simplemente prepara una aplicación que puedas usar más adelante en el resto de los ejercicios.

## Ejercicio 6
Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas?

## Ejercicio 7
Crear una descripción del módulo usando package.json. En caso de que se trate de otro lenguaje, usar el método correspondiente.

~~~
def funcion():
	"""
	Descripcion de la función, así como toda la información que se quiera mostrar: nombre, version, autor, etc..
	"""
~~~

## Ejercicio 8
Automatizar con grunt, gulp u otra herramienta de gestión de tareas en Node la generación de documentación de la librería que se cree usando docco u otro sistema similar de generación de documentación. Previamente, por supuesto, habrá que documentar tal librería.

## Ejercicio 9
Haced los dos primeros pasos antes de pasar al tercero.

Ejercicio resuelto en el repositorio del [Proyecto_IV](https://github.com/Medfac9/Proyecto_IV/blob/master/.travis.yml) para el [hito 2](https://github.com/Medfac9/Proyecto_IV/milestone/2), el [issue 4](https://github.com/Medfac9/Proyecto_IV/issues/4).
