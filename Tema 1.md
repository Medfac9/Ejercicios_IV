# Ejercicios del tema 1
## Ejercicio 1
Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. [Consultar este artículo en Infoautónomos sobre el tema.](http://infoautonomos.eleconomista.es/consultas-a-la-comunidad/988/)

Primeramente debemos de saber que para equipos para tratamiento de la información y sistemas y programas informáticos el  máximo de años para amortizar el útil es de diez años.
Para calcular el coste de amortización de [este](https://www.dynos.es/servidor-hp-proliant-blade-bl460c-g9-xeon-e5-2620-v3-32gb--4514953918467__N1W94A.html) servidor en cuatro años seria de la siguiente manera:
* Primeramente deberemos de restar el 21% de IVA. Con lo que el precio se nos queda en 1765,59€ - 370,77 = 1394,82€
* Después dividimos el total sin IVA entre el número de años. Primero en cuatro años: 1394,82€ / 4 años = 348,705€/año. Y luego con siete años: 1394,82€ / 7 años = 199,26€/año.
* Como conclusión, con cuatro años de amortización, el coste por año sería de 348,705€/año y con siete años el coste por año sería de 199,25€/año.

## Ejercicio 2
Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

|  | Instancia | CPU | RAM | Memoria | Precio hora |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| VPS Cloud RAM | 4 | NC6 | 60 GB | 100 GB | 0,194 €/hora + IVA |
| Microsoft Azure | 6 | R2-60 | 56 GB | 340 GB | 0,984 €/hora |

En un año hay 8640 horas, si usamos el 1% de los servidores :
* VPS Cloud RAM: 16,7616€ + IVA.
* Microsoft Azure: 85,0176€.  

Si usamos el 10% de los servidores :
* VPS Cloud RAM: 167,616€ + IVA.
* Microsoft Azure: 850,176€.

## Ejercicio 3
En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?  
Modelo del procesador: Intel(R) Core(TM) i5-5257U CPU @ 2.70GHz  
![Captura de pantalla](https://imgur.com/upDkH0E.jpg)
## Ejercicio 4
Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.  
![Captura de pantalla](https://imgur.com/cdW41A6.jpg)

Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.

Voy a instalar el hipervisor LXD con el siguiente comando:  
`apt-get -t trusty-backports install lxd`

Y lo iniciamos con el comando:  
`sudo lxd init`

## Ejercicio 5
Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.

Mes he dado de alta en Amazon Web Services como estudiante obteniendo así un crédito de 100$ para usar sus servicios.

## Ejercicio 6
Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube anteriores.

Ccon Amazon Web Services podemos probar sus sistemas de gestión de nube de forma gratuita haciendo gracias al saldo por registrarnos como estudiantes.
