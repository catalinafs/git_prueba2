
# Introducci贸n al internet
# Clase 1
# indice
- Historia del internet.
- Lenguaje binario.
- Bits y bytes.
- Codigo ASCII.
- UniCode
- RGB
- Que es el internet.
- Protocolos.
- Modelo OSI
- Protocolo TCP.
- ISP
- DNS
- W3C
- Metodos HTTP.
- Que es el HTML, CSS y JAVASCRIPT.
- DOM
- CSSOM
-Layout

## Historia de la computaci贸n.
![](./imagenes_1/historia.png)
![](./imagenes_1/historia2.png)
![](imagenes_1/in_out.png)

馃敼 La entrada o input son la informaci贸n que ingresamos a la computadora, esto puede ser a trav茅s de dispositivos de entrada como: Escaner, Micr贸fono, WebCam, Mouse, Teclado, etc.

馃敼 El Proceso consiste en los c谩lculos que har谩 la computadora tomando como base la informacion ingresada.

馃敼 La salida o output son la informaci贸n que devuelve la computadora y esta inforamci贸n puede ser visualizada a trav茅s de dispositivos de salida como: Impresora, Proyector, Parlante, Monitor, etc.

## Lenguaje Binario
La base de los procesos anteriores es el lenguaje binario.
![](imagenes_1/binario.png)
### Ejercicio:
Convertir un numero decimal en binario.

## Bits y Bytes
![](./imagenes_1/bitd.png)
![](./imagenes_1/byte.png)
![](./imagenes_1/escala_byte.png)

## Codigo ASCII
https://www.ascii-code.com

El codigo ASCII es la representaci贸n simbolica de un numero decimal representado por un numero contruido en Bytes.
![](imagenes_1/ascci1.png)
![](./imagenes_1/ascii2.png)
### Ejercicios
- Convertir un texto a un codigo ASCII
- luego convertirlo en codigo binario.
- Calcular su peso en Bytes.
- Calcular su peso en Bits

## Unicode
- https://unicode-table.com/es/
- https://www.oscarlijo.com/blog/tabla-de-caracteres-unicode/
Unicode es un est谩ndar de codificaci贸n de caracteres dise帽ado para facilitar el tratamiento inform谩tico, transmisi贸n y visualizaci贸n de textos de numerosos idiomas y disciplinas t茅cnicas, adem谩s de textos cl谩sicos de lenguas muertas. El t茅rmino Unicode proviene de los tres objetivos perseguidos: universalidad, uniformidad y unicidad.
En caracter de unicode puede formarse desde 1 byte hasta 6 bytes.
![](imagenes_1/unicode.png)

## RBG
Es un formato de colores, donde cada pixel dentro de una imagen est谩 compuesta por 3 subpixeles: Rojo (Red), Verde (Green) y Azul (Blue) con un tono de 0 a 255.
Ejemplos:
馃敼 Negro (0, 0, 0)
馃敼 Blanco (255, 255, 255)
馃敼 Rojo (255, 0, 0)
鉅?
Combinando tonalidades se pueden formar colores espec铆ficos.
鉅?
Ejemplos:
馃敼 Plum Purple (178, 80, 228) - 10110010, 01010000, 11100100


````info
**Porque verde? Si no es un color primario鈥?**
Los pigmentos (pinturas) son colores de 芦sustracci贸n禄. Ya sabes, el color que ves es el que no han absorbido de la luz. Al juntar azul y amarillo 芦absorben m谩s frecuencias禄 y da el verde (modelo RYB, de las siglas de red, yellow y blue). Pero la luz es un modelo de adici贸n: al juntar dos colores ves la suma de sus 芦frecuencias禄, es decir Verde + azul= amarillo (modelo RGB)
Por eso la TV y el PC usan modelos de RGB (emiten luz) pero el cartucho de tinta de tu impresora usa el RYB.

Cada pixel representa un c谩lculo de la computadora.
````
![](imagenes_1/rgb1.png)
![](imagenes_1/rgb2.png)

### Hexadecimal
Otro formato de colores es el Hexadecimal donde el RGB formado por 3 bytes, es traducido a Hexadecimal
![](imagenes_1/hexadecimal.png)

## Internet
https://www.submarinecablemap.com
![](imagenes_1/internet1.png)
![](imagenes_1/internet2.png)
![](imagenes_1/internet3.png)

## Protocolos
TCP (Tranmission Control Protocol) e IP (Internet Protocol) son los principales, sin protocolos de transmisi贸n de c贸mo debe pasar la informaci贸n. Se estructura en 5 etapas
- Aplicaci贸n: HTTP/ FTP
- Transporte: TCP/ UDP
- Red: IP/ Routers
- Enlace: Ethernet / Switchers
- F铆sica: cables
  
![](imagenes_1/protocolos1.png)

![](imagenes_1/protocolos2.png)

![](imagenes_1/protocolos3.png)

![](imagenes_1/protocolos4.png)

![](imagenes_1/protocolos5.png)

## ISP
Un ISP o Proveedor de Servicios de Internet ( Internet Service Provider), es el t茅rmino con el que se identifica a las compa帽铆as que proporcionan acceso a Internet, a los hogares鈥? a empresas,etc

Es decir, puedes tener el ordenador m谩s potente del mundo con una flamante tarjeta de red y la casa u oficina cableada con fibra 贸ptica, que sin un ISP no tendr谩s la posibilidad de navegar. Y para poder navegar, es necesario pagar una cuota a uno de estos proveedores.Muchas veces nos estafan.
**驴C脫MO FUNCIONA UN ISP?**
B谩sicamente, lo que hace un ISP es desplegar una red de telecomunicaciones que se conecta a otras redes.

![](imagenes_1/isp1.png)
![](imagenes_1/isp2.png)

## DNS
![](imagenes_1/dns1.png)
````
# lunix
ifconfig | grep mask

# Windows y MacOs
ipconfig

# Saber la IP de google
nslookup google.com

# ping a google
ping www.google.com
````
![](imagenes_1/dns2.png)
![](imagenes_1/dns3.png)
![](imagenes_1/dns4.png)


## Primer desarrollo Web
http://info.cern.ch/hypertext/WWW/TheProject.html
Hubo un primer desarrollador Web, su nombre es Tim Berners-Lee.
- 馃敼 Hizo la propuesta de W3, la cual es una forma de globalizar la informaci贸n y poderla linkear.
- 馃敼 Todo lo gener贸 a trav茅s de una computadora NEXT.
- 馃敼 Escribi贸 las 3 tecnolog铆as fundamentales para el desarrollo Web:
    - 馃敼 HTML: Lenguaje de marcado para la Web.
    - 馃敼 URL: Direcci贸n a la que nos conectamos.
    - 馃敼 HTTP: Forma para comunicarnos a trav茅s de peticiones
- 馃敼 Construy贸 el primer servidor Web.
- 馃敼 Construy贸 el primer navegador.

![](imagenes_1/web1.png)

## W3C
https://www.w3.org/Consortium/Member/List
![](./imagenes_1/w3c.png)

## Web Browser
Un navegador web es software que nos permite ver y acceder a las paginas web que solicitamos utilizando el **protocolo HTTP** (que basicamente dicta como esa informaci贸n viajar谩 por Internet). El navegador recibe un documento HTML y muestra la informaci贸n tal y como se especifica en el html utilizando algo llamado **rendering engine**.

![](imagenes_1/navegador.png)
1[](imagenes_1/navegador2.png)

## HTTP y HTTPs
HTTP son reglas de comunicaci贸n.
Para este protocolo existen HTTP Request y HTTP Response, los cuales se encarga del procesamiento de las solicitudes.
鉅?
Existen m茅todos dentro de HTTP:

- **GET**: Solicita datos
- **POST**: Env铆a datos.
- **PUT**: Crea o reemplaza datos.
- **DELETE**: Borra datos espec铆ficos.

![](imagenes_1/http1.png)
![](imagenes_1/http2.png)
![](imagenes_1/http3.png)
![](imagenes_1/http4.png)
![](imagenes_1/http5.png)

## Estandares Web
![](imagenes_1/ew1.png)

## DOM
![](imagenes_1/dom1.png)
![](imagenes_1/dom2.png)

## CSSOM
![](imagenes_1/cssom.png)

## Render Tree
Los 谩rboles CSSOM y DOM se combinan en un 谩rbol de representaci贸n. A continuaci贸n, este 谩rbol se utiliza para computarizar el dise帽o de cada elemento visible y sirve como entrada del proceso de pintura que permite representar los p铆xeles en la pantalla. Para lograr un 贸ptimo rendimiento de representaci贸n, es imprescindible optimizar cada uno de estos pasos.

### 驴Qu茅 es el Render Tree?
Es un 谩rbol que une el DOM y CSSOM para renderizarlos, creando un c贸digo que pueda interpretar el navegador. De esta manera se generan todas las p谩ginas web que vamos cargando mientras navegamos.
![](imagenes_1/rendertree.png)
![](imagenes_1/rendertree2.png)

### Proceso de renderizado
- **Bytes**: El navegador coge todo el c贸digo y lo transforma en bytes.
- **Characters**: El navegador transforma estos bytes en caracteres dependiendo de la codificaci贸n que le hemos pasado. Por ejemplo UTF-8.
- **Tokens**: Ahora transforma dichos caracteres en tokens, identificando el significado de los caracteres relacion谩ndolo a etiquetas que generan cierto tipo de contenido. W3C documenta todas la etiquetas.
- **Nodos**: Despu茅s de saber el dicho orden de los tokens har谩 una transformaci贸n a los nodos, estos nodos son objetos. Dichos objetos son lo que el navegador sabe interpretar (Los elementos).
- **DOM**: Ya cuando el navegador tiene todos los nodos los ordena en un 谩rbol jer谩rquico donde cada objeto tendr谩 una posici贸n dependiendo su etiqueta.
- **CSSROM**: Transforma el CSS y une con el DOM. Asignando los estilos a cada elemento dentro del DOM.

![](imagenes_1/layout.png)
![](imagenes_1/layout2.png)
![](imagenes_1/layout4.png)

## paint
Cuando ya tenemos el **Render Tree** y el **layout** cargados, el proyecto empieza a tomar forma. Mediante el layout se forman las cajas, se llenan con la informaci贸n y por 煤ltimo se pinta, es decir, se le dan los colores, acabaos, sombras y estilos pertinentes de todos y cada uno de los elementos.

**Paint** o **pintado** es poner los detalles finales para que el proyecto se pueda ver como quer铆amos al principio. Su velocidad es gran responsable de la velocidad final que se tenga al momento de cargar con el sitio.

![](imagenes_1/paint.png)

## JavaScript Engine
![](imagenes_1/jsengine.png)
- Recibir el c贸digo como un flujo de bytes UTF-16 y pasarlo a un decodificador de flujo de bytes (el cual hace parte del motor).
- El parser toma el c贸digo y lo descompone en tokens (los tokens son elementos de js como: let, new, s铆mbolos de operaciones, functions, promises).
- Gracias al anterior parseo se genera una estructura de datos en forma de 谩rbol, o Abstract Syntax Tree (AST).
- El int茅rprete recorre el AST y va generando el bytecode.
- El optimizing compiler optimiza el c贸digo bytecode a machine code y se reemplaza el c贸digo base.

## Critical rendering path
![](imagenes_1/criticalrenderpath.png)
Todas p谩ginas web est谩n formadas por html, css y Javascript e independienemente de la cantidad de cada uno de ellos, los navegadores siempre siguen el mismo proceso para conseguir tanto el contenido como la manera en que 茅ste se ha de mostrar al usuario:

- Generar el 谩rbol DOM a partir del html.
- Generar el CSSOM Tree a partir del css.
- Generar el Render Tree con la combinaci贸n del DOM y - CSSOM
- Calcular la disposici贸n o layout de todos los nodos.
- Pintar los nodos del Render Tree.

![](imagenes_1/critialpath.png)

**El DOM**

https://www.youtube.com/watch?v=jgU3Wn0Txec

Es el 谩rbol de nodos que representa los contenidos de la p谩gina o aplicaci贸n web. Estos contenidos est谩n determinados por el HTML y, aunque se parezca bastante al DOM, no s贸n lo mismo.

驴C贸mo se genera el 谩rbol DOM?
El DOM se genera a partir del fichero con extensi贸n .html y sigue distintos pasos para generarse:

- Convertir los bytes a car谩cteres.
- Pasar de car谩cteres a tokens.
- Generar los nodos.
- Construir el 谩rbol DOM.


La construcci贸n del DOM y del CSSOM se hacen de manera as铆ncrona/paralela. Eso significa que el proceso de generar el CSSOM no es bloqueante para poder generar el DOM, pero, s铆 que lo es para renderizarlo.

En caso de que el navegador detecte un ````<script>```` no declarado como as铆ncrono en el ````<head>```` de la p谩gina, este ser谩 descargado, pero no ejecutado hasta que el 谩rbol CSSOM termine de ser construido y, por tanto, si el **JavaScript** no es ejecutado, la construcci贸n del DOM queda bloqueada.