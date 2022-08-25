# Docker  
## ARQUITECTURA  CON DIAGRAMA DE BLOQUES

1 ,2 y 3.La virtualizacion consiste en contar con computador se instala un sistema operativo  el cual ejecuta las aplicaciones de la siguiente manera como lo vamos haber en los siguientes diagrama de bloques.

![imagen 1](imagenes/img1.png)

la virtalizacion utiliza la funcionalidad del hardware o también  la capa de software llamada hipervisor.

Las cuales puede contener varias maquinas virtuales

![imagen 2](imagenes/img2.png)

El objetivo de este lo que hace es dividir el hardware y el software  en varias cargas de trabajo en contenedores y maqina virtuales en que se puede ejecutar aplicaciones.


![imagen 3](imagenes/img3.png)

Ademas con este se puede tener el cuenta los contenedores que empaqueta  una aplicación,esta estructura de contenedores  contiene la de pendencia y servicios del sistema operativo,es una virtualizacion adicional 

Diferencia de virtualizacion y los contenedores

![imagen 4](imagenes/img4.png)

Se puede ejecuta un contenedor que active el kernel y hasta se pueda mover el contener entre maquinas que tengan el mismo kernel,ya que tiene proceso aislados solo tiene que tener recursos  como la cpu,memoria ,la red que  pongan en funcionamiento este proceso.

Estos se ejecutan en un entorno aislado,por tanto son livianos y el proceso de encendido y apagado  rápidamente.la diferencia entre un contenedor y la maquina virtual  es la ubicación de la capa de virtualizacion y la forma que se utilizan  los recursos en el sistema operativo.y aunque son diferentes tecnología cumple el mismo fin  se diferencia  en que tiene características y compensaciones únicas para las cargas de trabajo.
En el mercado se consiguen varios con diferencias técnicas,por el ejemplo

El docker es una plataforma muy reconocida,este permite agregar y almacenar  una aplicación  y sus dependencias en el paquete llamado imagen. Con esta se puede realizar una instancia de su aplicación.

Rkt: este es otro docker pero  implementado para la seguridad
Lxc: esta permite ofrecer contenedores de sistema completo.
 

Entre otros,como Windows que también tiene la función de contenedores

Esta el contenedor Windows es igual a docker comparte el kernel.
 Por ultimo el contenedor Hiper-V  son maquinas optimizadas  que contienen una copia del kernel de Windows,en este cada contenedor tiene su propio kernel

# 4

  ![imagen 5](imagenes/img5.png)

# 5

![imagen 6](imagenes/img6.png)

# 6

Prerrequisitos
Antes de instalar el back-end de Docker Desktop WSL 2, debe completar los pasos siguientes:
1.	Instale Windows 10, versión 1903 o superior o Windows 11.
2.	Habilite la característica WSL 2 en Windows. Para obtener instrucciones detalladas, consulte la documentación de Microsoft.
3.	Descargue e instale el paquete de actualización del kernel de Linux


7, 8  y 9
# INSTALACION DE DOCKER
 
 Descargar  el instalador de docker desktop para Windows 10

 ![imagen 7](imagenes/docker1.png)

 Dejar las dos pestañas y  darle en ok

![imagen 8](imagenes/docker2.png)

 Descargando los paquetes necesarios para instalar en nuestro sistema

 ![imagen 9](imagenes/docker3.png)

Cerrar y reiniciar

![imagen 10](imagenes/docker4.png)

Esta ventana emergente  salen el siguiente link de color azul en donde contendrá los siguientes pasos a seguir
Por que nosotros al estar en Windows debemos configurar el kernel de Linux para poder trabajar sobre esa virtualizacion

![imagen 11](imagenes/docker5.png)

Este es el link para poder realizar el paso 4 donde se descarga el paquete de kernel linux 

Pasos de instalación manual para versiones anteriores de WSL | Microsoft Docs
* [pagina de descarga de kernel][1_0]
[1_0]:https://docs.microsoft.com/en-us/windows/wsl/install-manual


Paso 4: Descarga del paquete de actualización del kernel de Linux
Descargue la versión más reciente:
•	Paquete de actualización del kernel de Linux en WSL 2 para máquinas x64

