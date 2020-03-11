# 1. Introducción 01:31:44

* Bienvenida 09:09
* Recursos - parte 1 11:49
* Recursos - parte 2 17:07
* Plugins para agilizar el desarrollo - documento 00:26
* Material de apoyo e inquietudes 11:03
* Contáctame 00:12
* ¿Qué es un sistema de ventas por suscripción? 04:49
* Elementos de una plataforma web de ventas por suscripción 03:57
* ¿Qué es un programa de afiliados? 05:34
* ¿Qué es el marketing multinivel? 05:21
* Diferentes esquemas de las redes multinivel 22:17

## Bienvenida 09:09

Tengan un cordial saludo.

Este curso crea sistemas de ventas por suscripción y marketing multinivel con PHP y PayPal.

Mi nombre con Fernando Urrego y seré quien los acompañaré en este proceso de aprendizaje.

El gran negocio del siglo XXI son los sistemas de suscripción.

Empresas como Netflix, Amazon, Apple, PlayStation entre otras grandes ofrecen servicios de entretenimiento o capacitación bajo esta metodología de ventas por suscripción.

En ese curso te enseñaré desde cero crear una plataforma web para ofrecer cualquier servicio producto a través de pagos cíclicos y automatizados.

Utilizaremos la API de PayPal, PHP en su versión 7 y bases de datos MySQL.

Además te enseñará a integrar programas de afiliados y herramientas de marketing multinivel en este sistema para que los mismos consumidores se conviertan en los mejores vendedores de la empresa.

En esta clase te hablaré del alcance que tiene este curso vamos a mirar.

Un [sistema de ventas por suscripción](https://marvelapp.com/eggg919/screen/48785985) no es más que un modelo de negocio donde rentas un producto o servicio de forma periódica mensual, semestral o anual y se basa en encontrar un patrón de compra automatizado que sea repetitivo donde el único objetivo es encontrar más y más suscriptores.

En este curso te voy a enseñar a hacer una página de aterrizaje que va a ser lo que el cliente se va a encontrar por primera vez con el sistema.

Acá le mostraremos que tiene la opción de adquirir una suscripción gratuita y una suscripción de paga.

Por qué es importante tener la opción de prueba gratuita con limitaciones.

Obviamente a determinadas herramientas.

Porque esta prueba gratuita va a servir de gancho para pasar a la opción de paga el usuario se podrá registrar a través de un formulario y pasar a lo que se llamará La oficina virtual o la página Back-Office.

Esta página Back-Office la vamos a desarrollar con la [plantilla AdminLTE](https://adminlte.io/) en su última versión que ella incorpora Bootstrap 4 y un montón de recursos interactivos.

En este Back Office el usuario podrá tener entonces acceso a los productos o servicios que está adquiriendo con la suscripción y si ingresó de forma gratuita entonces va a tener que activar la membresía si quiere ver todos los videos en este caso por tratarse de una plataforma educativa para poder ver todos los videos tendrá que comenzar la suscripción.

Te enseñará entonces a hacer un formulario para capturar toda esa información y aceptar unos términos y condiciones para que se convierta en un vendedor de la empresa ya que voy a enseñar a integrar programas de afiliados y marketing multinivel que son sistemas que ayudan a que esa persona se empodere de los servicios de la empresa para poder ganar comisiones, te enseñaré entonces dentro de la misma plataforma hacer esas dos versiones la versión gratuita y la versión paga del sistema.

También te enseñaré a hacer suscripciones y pagos automatizados con PayPal. PayPal ofrece dos opciones ofrece crear un botón de suscripción y ofrece trabajar con su API para poder interactuar con nuestra base de datos, toda la información de pagos a través de esta plataforma.

Entonces te voy a explicar cómo integrar a través de la API de PayPal.

Toda la información que necesitamos para poder hacer parte de su sistema de suscripción con todos los ensayos pruebas que se puedan hacer ya que lo vamos a hacer en modo Sanbox en este curso, ya cuando se monte la plataforma en un hosting podríamos cambiar a la versión real a la versión live.

También le voy a enseñar entonces como te lo mencioné a integrar un programa afiliados, así como lo hacen empresas como Udemy a través de Rakuten marketing invita a que otras personas ayuden a vender más cursos, ayuden a vender cursos de otros instructores, si lo hacen ganan comisiones.

En este curso vamos a integrar también esa opción de que si la persona se suscribe al sistema pueda tener un enlace de afiliado para ser compartido, lo pueda copiar en el portapapeles y luego compartirlo en sus redes sociales para que si una persona llega a comprar la suscripción a través de ese enlace afiliado, la persona que está afiliada gane comisión por esa venta que se está generando.

Te voy a enseñar a incluir material publicitario que es necesario entre estos sistemas para que la persona pueda compartir en sus redes sociales ya sean imágenes, ya sean videos, ya sean banners o lo que se necesite para poder compartir en redes sociales.

Hablaremos de la gestión de usuarios cómo podremos administrar estos usuarios desde la base de datos para saber de qué países están suscribiendo para saber quienes tienen una suscripción activa, quienes la tienen desactivada, poder filtrar por nombres, poder filtrar por países etc.

Te enseñaré a crear una plataforma de streaming al estilo Netflix donde los videos no se podrán descargar tan fácil lo normal de un video es que esté en formato mp4 y en el navegador es muy fácil buscar la ruta donde se encuentra ese video para poderlo descargar y lo que hacen muchas personas después de descargar los videos es montarlos en otras plataformas.

En este caso te voy a enseñar a convertir un video a un formato de streaming para que quede particionado, ese formato ya no permite descargar el video completo sino que tendría que descargar parte por parte de ese video como si el video estuviera fragmentado en pequeños pedazos.

Entonces esto ayuda a evitar lo que se llamaría la piratería de videos en cualquier plataforma.

También te voy a enseñar a generar diferentes tipos de redes multinivel.

Por ejemplo la red uni-nivel, vamos a trabajar cuando la persona entra debajo de otra y no hay descendencia, es lo que normalmente se hace en un programa afiliado. Simplemente ayuda a vender el producto y las personas que compran el producto a través de tu enlace afiliados se convierte en tu red uni-nivel.

Vamos a aprender también a crear una red binaria, la red binarias es aquella red que tiene pata izquierda o pata derecha o lado izquierdo o derecho, donde las comisiones que se generan es a través de la pauta o el lado que menos puntos tenga.

En la red matriz cuatro por cuatro, ya estamos hablando otro tipo de red forzada donde tendría que meter a cuatro personas en su primera línea descendiente y cada una de esas cuatro personas se encargaría de traer a otros cuatro y así se generarían unas comisiones totalmente diferente de acuerdo a los niveles de profundidad.

Todo esto te lo voy a enseñar en este curso paso a paso desde cero.

También hablaremos entonces de la gestión de ingresos y pagos de comisiones, cómo podemos llevar un histórico esas ganancias que están teniendo las personas y cómo podemos validar que esa persona si se está suscribiendo mes a mes y todo esto en piloto automático, no vas a tener que hacer ninguna acción manual.

Gracias a la API de PayPal, la API de PayPal nos permite validar si a final del mes la persona se suscribió y si hay que pagarle comisiones.

También hablaremos de una página donde se explicará el plan de compensación de ese sitio que está ofreciendo la oportunidad de que otras personas ganen dinero con ellos.Es importante dentro de cualquier programa multinivel tener ese plan de compensación.

Y por último trabajaremos el soporte al cliente, es una bandeja de entrada al mejor estilo de correos electrónicos para que la persona pueda interactuar con el administrador del back office, puede crear un tiket, adjuntar archivos, puede crear un correo con texto enriquecido, etc. para que el administrador de la plataforma pueda resolver esas inquietudes con respecto a lo que es el sistema de suscripción.

Trabajaremos muchos plugins. muchas herramientas interactivas las cuales enseñaré paso a paso, cómo integrarlas,  
demostrar de dónde vienen, cuáles son sus documentaciones, para que tú puedas también seguir manipulandolas en otros proyectos y aprenderás muchísimas cosas.

Como desarrollador web simplemente queda decirte bienvenido a este curso y estoy seguro que no te vas a arrepentir de hacerlo.

#### Resumen ¿Qué vamos a aprender?

* Página de aterrizaje
* Página BackOffice
* Versión gratuita - versión pagada
* Suscripción y pagos automatizados con PayPal
* Programa de afiliación
* Material publicitario
* Gestión de usuarios
* Plataforma de Video-Streaming
* Tipos de redes multinivel
* Gestión de ingresos y pagos de comisiones
* Soporte al cliente

## Recursos - parte 1 11:49

## Recursos - parte 2 17:07

## Plugins para agilizar el desarrollo - documento 00:26

## Material de apoyo e inquietudes 11:03

## Contáctame 00:12

## ¿Qué es un sistema de ventas por suscripción? 04:49

## Elementos de una plataforma web de ventas por suscripción 03:57

## ¿Qué es un programa de afiliados? 05:34

## ¿Qué es el marketing multinivel? 05:21

## Diferentes esquemas de las redes multinivel 22:17
