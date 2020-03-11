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

En esta clase vamos a hablar de todos los recursos que utilizaremos durante todo este desarrollo de aprendizaje si vamos a trabajar PHP en su versión 7 y con bases de Hatsumi SQL como primero necesitamos un servidor local instalado en nuestra computadora un servidor local es una herramienta que nos va a simular lo que hace un hosting en Internet.

Cuando tú subes una página web a internet tú necesitas de unos módulos para que funcione el PHP y sus bases de datos SQL.

Eso es lo que hace un servidor local simula estos módulos en tu computadora sin necesidad de tener el proyecto subido a internet.

Yo siempre recomiendo en mis cursos donde trabajamos PHP o bases de datos utilizar el serbio local SAP.

Hay muchos más están WAM Server Elissa y PHP.

El MAP pero para cuestiones de agilidad estabilidad y no tener problemas con el código más adelante te recomiendo que en este curso utilices el SAP lo puedes instalar sin problema en tu computadora puede ser de varios servidores locales en tu computadora.

No hay ningún inconveniente lo importante es que siempre inicies el servidor cuando vamos a trabajar en este proyecto.

Entonces para descargar el SAP lo único que tenemos que hacer es dirigirnos a la página oficial de SAP la puedes buscar en Google la palabra clave es Sam y te puedes ir a la descarga de SAP en ese momento nos muestra todas las versiones disponibles que han ido actualizando esta es la última las 7 punto 3.3.

En mi caso yo seguí trabajando con las siete punto 1.27 porque instalé el SAP hace algunos meses o un año atrás.

No he tenido la necesidad de subir al 7 punto 3.3 porque sigue comportándose en la manera en que lo necesito.

Acá nos explican que está incluido que qué actualizaciones se han hecho muy bien en este caso simplemente haz clic en Descargar.

De acuerdo a tu sistema operativo te aparecerá acá o si no en la segunda pestaña aparece s'han para Windows para linos o para Paice X ok.

En ese caso sería para Windows.

Haz click descargas y aparecerá entonces el instalador ya en la opción de descargas.

Cuando le haz click al instalador de abrir la ventanita Nami y nos aparece un aviso nos dicen para poder activar el Zam y no tener problemas necesitamos entonces desactivar y dar permisos de escritura una opción que se llama user ACAM control o hace entonces para poder desactivar el Waze en nuestro sistema Windows lo que podemos hacer es dirigirnos con la ventanita en la tecla de la ventanita la tecla de comandos que tenemos en el teclado que tiene el símbolo de Windows más la R nos debe abrir el ejecutado del ejecutado lo vamos a ejecutar el MS Conficker entonces damos Aceptar nos vamos a ir para herramientas vamos a ir para cambiar configuración de Waze veamos iniciar y tenemos que bajar hasta el final hasta la parte de abajo esta pestaña ok.

Normalmente como por acá vamos a bajar hasta el final le damos a Aceptar y la vamos a aceptar y ya le podemos continuar con la instalación del Zam.

Si tú ya tienes otro instalado como en mi caso lo que puedes hacer es crear una carpeta adicional Unsam 3.

Por ejemplo yo ya tengo el SAM 1 que fue con PHP 5 el Sandoz con PHP 7 ahora que tiene ya otra su actualización.

Si quiero puedo instalarlo en el Sam 3 o simplemente dejar Zab si es primera vez que lo vas a instalar y continuar continuar continuar continuar hasta finalizar la instalación.

Ok voy a salir del proceso instalación porque ya tengo el SAM instalado miralo acá tengo el Sam 2 que es PHP 7 y lo que necesitamos definir es que trabajaremos en la carpeta HT Docs aquí están todos los proyectos con los que he trabajado.

Ok aquí es donde vamos a trabajar.

Nuestro sistema de segundo recurso que vamos a necesitar es un editor de código en este curso y en todos los que yo dicto siempre recomiendo el editor de código Sulantay.

Hay muchos más claro esta Autana está brackets esta Visual Studio.

Qué se yo en el que te sientas mucho más cómodo trabajar pero por qué te recomiendo sus lentes.

Porque en este curso voy a enseñarte a utilizar algunos plugins y atajos para la agilización del desarrollo.

Entonces si quieres puedes tener varios editores instalados en tu computadora.

No hay problema.

Te recomiendo instalar sus lentes en su versión 3 luzcas que es la última versión.

Lo buscamos en Google sus lentes y nos aparece la página oficial y nos dice la descarga para Windows normalmente él descarga como una versión Frin cuando tienes la versión free.

Lo que sucede es que aparece una ventanita a veces cuando estás trabajando en el programa donde te dice que si quieres pasarte a la versión Pro simplemente haz clic sobre el botón que da la ventana.

Obviamente no vamos a cambiarnos a la versión pero si no lo quieres comprar puedes continuar sin problema trabajando en la versión Frin.

Cierras esa ventanita y continúas trabajando.

Yo sí compré la versión Pro y aquí está instalada en mi computador por eso a mí no me aparece la ventanita mientras estoy explicando en el curso.

Es algo muy tedioso que me aparezca la ventanita cada vez que estoy dando una clase.

Ok entonces ya tiene terminando su Leites instalado.

Pasemos a lo que son los plugins que vamos a utilizar.

Son plugins para agilizar el desarrollo en este entorno de trabajo para poder instalar plugins en sus lentes necesitamos instalar lo que se llama el control o el control de paquetes.

Aquí está la dirección del control o simplemente lo vamos a buscar en Google como Aakash control entonces cuando ingresas a la página oficial del control acá te dicen las instrucciones de instalación te vas a meter a la pestaña Sulantay estrés que es la última versión que descargase copias este código o esta escritura y acá nos dice que debemos ir a la pestaña View Chow Conso y luego copiar esto los copiamos esto una vez nos vamos para BYU vistas Chop Consol visualizar consola y pegás ese código acá le haz click derecho pegar.

Yo no lo hago porque ya tengo el control instalado.

Entonces simplemente es pegarlo y aquí te muestra todo el proceso de la instalación cuando ya está instalado completamente puedes salirte con Skype y en preferencias te aparecerá esa pestaña de control y ya con esto instalado podemos comenzar a instalar esos plugins estos plugins Aquí hay seis plugins que vamos a utilizar mucho en ese curso te lo voy a compartir en una siguiente clase como documento de texto para que veas el funcionamiento o los atajos.

El primer plugin que vamos a instalar es el MKT recuerda que esto es sólo para sus lentes en su versión 3 entonces vamos a instalar el Emet preferencias pagas control instalar paquetes debe aparecer una ventana nueva y buscamos el plugin Emet lo cual vamos a instalar este primerito tal cual como está escrito Emet.

Qué hace este plugin de Emet.

Por ejemplo yo tengo un nuevo archivo y luego estoy trabajando en sintaxis HTML me da el atajo de construir una estructura HTML muy rápido simplemente con el cine admiración invertido ítalo y vamos a ver si si no lo instalo bien preferencias pacá setting Emet muy bien ahí está vamos a hacer otras elejercicio sintaxis HTML que ahora ya está dando ya me está dando los tips me no me toma a colocar HTML ahora si se mira simplemente con HTML obstaculo inmediatamente me aparece la estructura de un documento HTML.

Si yo coloco por ejemplo un dip ovulo aparece la etiqueta completa si yo coloco un huele a ulo y dentro coloco un Elai multiplicado por cinco y solo bien no me está dando todas las funciones completas del EMET y tuve que cerrar su Leites volverlo a abrir está presentando conflicto con la instalación de Emet.

Ahora si vamos a colocar un documento HTML vamos a abrir uno nuevo colocamos HTML obstaculo y ahora si me aparece la estructura HTML estamos explicando que si colocamos un dip aparecía sin problema que si colocamos un 9 aparece sin problema.

Y si multiplicamos Ucelay por 5 aparecían los 5 elegi perfecto esto era lo que necesitaba con el plugin

Emet que me ayuda a agilizar el proceso de maquetación.

Vamos a instalar otro paquete de Emet que viene siendo pero vamos a que aparezca sanarte paquetes Emet CSS CSS snippets cuando yo instalo el MTSS Stripped me permite hacer lo siguiente Vamos a cerrar acá cerrar acá vamos a colocar un documento de tipo CSS.

Vamos a colocar unas opciones globales y me saca las propiedades en atajo.

Por ejemplo se colocó la PEM me saca todo lo que pude utilizar con la P en el CSS se colocó la N y colocó la a perfecto son atajos entonces que puede utilizar Emet CSS snippets que no lo coloque acá vamos a ponerlo CSS es Ninet muy bien otro atajo que vamos a ver.

Otro plugin es el auto Fainé nos permite autocompletar la ruta del archivo vincular eso te lo voy a explicar en la próxima clase.

## Recursos - parte 2 17:07

## Plugins para agilizar el desarrollo - documento 00:26

## Material de apoyo e inquietudes 11:03

## Contáctame 00:12

## ¿Qué es un sistema de ventas por suscripción? 04:49

## Elementos de una plataforma web de ventas por suscripción 03:57

## ¿Qué es un programa de afiliados? 05:34

## ¿Qué es el marketing multinivel? 05:21

## Diferentes esquemas de las redes multinivel 22:17
