# Tarea 1 - Arquitectura del computador

![1copy](https://user-images.githubusercontent.com/63022972/221295740-ac8c9cc7-3882-4254-8f71-9e2486ccf059.png)

## Integrantes:

- Luis Sandoval - [Github](https://github.com/lsandoval9)
- Gerardo Díaz - [Github](https://github.com/GerardoDiaz22)

# Construcción de un computador para criptografía

## Introducción

#### a) Breve introducción a la criptografía

Es la ciencia que estudia los métodos de codificación y decodificación de mensajes para que sean ininteligibles para terceros no autorizados. La criptografía es una herramienta que permite proteger la información de los ataques de los piratas informáticos, los espías y los hackers. La criptografía es la base de la seguridad informática. 

#### b) planteamiento del problema

El problema que se plantea es la construcción de un computador que permita realizar la encriptación y desencriptación de un mensaje utilizando el algoritmo AES. Esto con el propósito de usarse en el sector industrial de la ciberseguridad y redes.

Para esto se creó un supuesto acerca de una empresa de ciberseguridad e infraestructura llamada "Don Gerardo" que se dedica a la venta de computadores para la encriptación de datos. El problema que se plantea es que la empresa no cuenta con un computador que pueda realizar la encriptación y desencriptación de un mensaje utilizando el algoritmo AES.

#### c-) AES

AES (**A**dvanced **E**ncryption **S**tandard) es un esquema de cifrado estadarizado para encriptar y desencriptar informacion. El proceso involucra el cifrado de la información en bloques, utilizando una llave, que es un conjunto de bits que se utiliza para encriptar y desencriptar la información. El algoritmo AES es un algoritmo de cifrado simetrico, es decir, que utiliza la misma llave para encriptar y desencriptar la información.

AES es el algoritmo seleccionado para la encriptación de datos en **Don Gerardo ©**, debido a que es el algoritmo de cifrado mas usado en la actualidad y uno de los mas seguros.

**Notas curiosa sobre AES**:

- El Esquema AES es tan seguro que esta aprovado por la NSA (Agencia de Seguridad Nacional de los Estados Unidos) y por el gobierno de los Estados Unidos para la encriptación de datos clasificados.

- AES es el algoritmo de cifrado mas usado en la actualidad.

- El algoritmo AES fue desarrollado por el grupo de criptografía de la NIST (Instituto Nacional de Estándares y Tecnología de los Estados Unidos).

- El algoritmo AES puede encontrarse en routers de uso domestico como una alternativa a TKIP, para encriptar el envio y recepción de datos en redes inalambricas.

## Especificaciones del computador

#### a) Motherboard

* GIGABYTE X670 AORUS Elite AX - US$ 279.00

[Proveedor](https://www.amazon.com/GIGABYTE-X670-AORUS-AX-Motherboard/dp/B0BF7FT26Z?th=1)

La tarjeta madre AORUS X679 elite AX es la seleccionada debido a que cuenta con un socket AM5 para nuestro Ryzen 7950x3D y la cual, ademas tiene un diseño avanzado para la disipación del calor llamado thermalguard 3. Este diseño permite que el procesador se mantenga fresco y que no se sobrecaliente, aun en periodos de gran estres.

Ademas Gybabyte tambien cuenta con un sistema de alto rendimiento llamado Twin 16+2 Power Phase Design. Este ultimo redistribuye la energia de forma efiiente y eficaz, lo que permite que el procesador pueda funcionar a su maxima capacidad. 

#### b) Procesador

* Ryzen 9 7950X3D - US$370.99 

[Proveedor](https://www.ebay.com/itm/225436166793?hash=item347d0aea89:g:S9wAAOSw1d5j87f5&amdata=enc%3AAQAHAAAAoGdDsaMagfVxrx%2B7%2BkvVsH7RWGzWxuKzdIQ%2FKcYwbbXs8jJ2GnK%2B57A3bAyIPfuNXWTmfO6f0GuIq2rUTSwJB9kUO7VKYM6PKquUkP922Y8Jw1UTQoEwMOCjSLGHBf%2B91%2BRt8u2k1RMHR29XFzGgptHr9ZJ%2F4%2FLRWyn%2Bw1%2Bp1teTegQqWjbbXFxQzh5M0eyCcPzxYw%2B5yuI9T1E%2FvlXXvMk%3D%7Ctkp%3ABk9SR6SgvpDRYQ)

El ryzen 9 7950x3D es un procesador de 16 núcleos y 32 hilos, con una frecuencia base de 4.2 GHz y una frecuencia turbo de 5.7 GHz. Este procesador es el mas potente de la serie ryzen 9 y es el mas potente de la serie ryzen en general. Este procesador es ideal para la encriptación de datos debido a que cuenta con 16 núcleos y 32 hilos, lo que permite que el procesador pueda realizar varias tareas al mismo tiempo y de una forma eficiente.

En benchmarks como AIDA64, el ryzen 9 7950X es capaz de encriptar 1.5 GB de datos en 1 segundo, lo que lo convierte en el procesador mas rapido para la encriptación de datos. Inclusive superando a la serie threadripper de AMD.

**Ver bibliografia para leer un analisis que incluye los benchmarks hechos al Ryzen 7950x3D**

**El Ryzen 7950x3D es una version mejorada del Ryzen 7950x**

#### c) case

* CORSAIR 7000D Airflow - US$ 287.94

[Proveedor](https://www.amazon.com/-/es/CORSAIR-7000D-Airflow-Gabinete-torre/dp/B09444VWX2/ref=sr_1_15?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=R00A677PFTGC&keywords=NZXT%2BH510%2BElite&qid=1677278479&sprefix=nzxt%2Bh510%2Belite%2Caps%2C149&sr=8-15&th=1)

El case Corsair 7000D Airflow esta diseñado para que el aire caliente generado por el procesador y la tarjeta madre pueda salir del case por la parte superior del mismo, lo que permite que el aire caliente no se acumule dentro del case y que el aire frio pueda entrar por la parte frontal del mismo. Esto permite que el procesador y la tarjeta madre se mantengan frescos y que no se sobrecalienten, por lo que el procesador podra funcionar a su maxima capacidad.

#### d) Fuente de poder

* EVGA Supernova 1000 P5, 80 Plus Platinum 1000W - US$ 258.99

[Proveedor](https://www.amazon.com/-/es/totalmente-ventilador-autocomprobador-alimentaci%C3%B3n-220-P5-1000-X1/dp/B09C2QJ5W6/ref=psdc_1161760_t2_B09M9639VW)

La fuente de poder EVGA Supernova 1000 P5 es una fuente de poder de 1000W con certificacion Platinum. Esta fuente de poder tambien cuenta con un sistema de ventilacion llamado "fan control with auto sensing", el cual permite que la fuente de poder se mantenga fresca en todo momento. Esta fuente tambien cuenta con condensadores japoneses de alta calidad, con un sistema ultrasilencioso y con protecciones contra cortocircuitos, sobrecargas, sobrecalentamiento y sobre tensiones para mantener a nuestro equipo a salvo de cualquier eventualidad.

#### e) fan cooler

* Cooler Master MasterLiquid ML280 Mirror ARGB - US$ 96.05

[Proveedor](https://www.amazon.com/-/es/Cooler-Master-MasterLiquid-ML280-Mirror/dp/B08BV2RHZW/ref=sr_1_3?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=9LFX3P8LHLJX&keywords=liquid%2Bcooler%2BAM5&qid=1677334985&sprefix=liquid%2Bcooler%2Bam5%2Caps%2C198&sr=8-3&th=1)

El Cooler Master MasterLiquid ML280 Mirror ARGB es un cooler liquido que cuenta con un sistema de enfriamiento de 280mm y ademas es compatible con nuestro procesador tipo AM5. Este es un sistema de enfriamiento para procesadores de alto rendimiento, como nuestro Ryzen 7950x3D. 

#### f) Memoria RAM

 * 2 x Kingston Technology Fury Beast Black 16GB 6000MT/s DDR5 - US$ 290.00 (2 x 145.99) 

[Proveedor](https://www.amazon.com/-/es/Kingston-Technology-Beast-Black-4800MT/dp/B09T9BVSW3/ref=sr_1_1?keywords=ram%2Bddr5%2B16gb&qid=1677280785&sprefix=ram%2Bddr5%2Caps%2C186&sr=8-1&th=1)

La memoria RAM Kingston Technology Fury Beast Black 16GB es una memoria RAM de 16GB con una frecuencia de 6000MT/s. Esta memoria RAM es ideal para nuestro procesador Ryzen 7950x3D debido a que cuenta con una frecuencia de 6000MT/s, lo que permite que nuestro procesador pueda funcionar a su maxima capacidad, evitando cuellos de botella al procesar datos. 

Kingston tambien garantiza, al menos un 50% mas de rendimiento que las ultimas gamas de DDR4, ademas de disminuir el consumo de energia en un 40% y de reducir el calor generado por la memoria RAM en un 30%, gracias a su disipador de calor de aluminio.

#### g) NVMe M.2

* 2 x Serie Samsung 980 PRO 2TB con disipador de calor - US$ 358.00 (2 x US$179.99)

[Proveedor](https://www.amazon.com/-/es/PCIe-NVMe-interno-juegos-MZ-V8P2T0B/dp/B09JHKSNNG/ref=sr_1_4?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=YA8TUVPXTPXW&keywords=nvme%2Bm.2&qid=1677281921&sprefix=nvme%2Bm.2%2Caps%2C162&sr=8-4&th=1)

El NVMe M.2 Samsung 980 PRO 2TB es un disco duro de estado solido con una capacidad de 2TB. Esta unidad cuenta con una velocidad de lectura de 7.000 MB/s y una velocidad de escritura de 5.000 MB/s. Su alta velocidad de lectura y escritura permite que nuestro procesador pueda procesar datos a una velocidad mucho mas rapida al tratarse de grandes bancos de datasets.

#### h) tarjeta de video

* Gigabyte GeForce RTX 4070 Ti AERO OC 12G - US$1,011.08

[Proveedor](https://www.amazon.com/-/es/Gigabyte-ventiladores-WINDFORCE-GV-N407TAERO-OC-12GD/dp/B0BRR1MPTX/ref=sr_1_13?keywords=geforce+rtx+4070+ti&qid=1677331967&sprefix=gefeorce+rt%2Caps%2C139&sr=8-13)

La GeForce RTX 4070 Ti AERO OC 12G es una tarjeta de video con una capacidad de 12GB de memoria RAM. Esta tarjeta cuenta con 7680 CUDA cores, 480 Tensor cores y 120 Ray tracing cores. Esta tarjeta tambien cuenta con un sistema de enfriamiento llamado "WINDFORCE 3X", lo que permite que se mantenga a temperaturas bajas incluso en periodos de gran estres.

Los Cuda cores son utiles para el procesamiento de grandes cantidades de datos, los Tensor cores son utiles para el procesamiento de datos de gran complejidad. Esto es util cuando se necesitan procesar grandes bancos de datasets desde la memoria secundaria, sobre todo cuando se trata de archivos que no son texto plano como imagenes, videos, etc.

Nuestro equipo debe ser capaz de procesar grandes cantidades de datos en paralelo, por lo que es beneficioso que nuestra tarjeta de video cuente con una gran cantidad de Cuda cores y Tensor cores para apoyar al procesador. Esto es util tambien para el procesamiento y encriptacion de datos a traves de redes o entornos en la nube.

#### i) pasta térmica

* Arctic MX-4 - US$ 21.99

[Proveedor](https://www.amazon.com/-/es/compuesto-t%C3%A9rmico-densidad-polisint%C3%A9tico-AS5-12G-R/dp/B0087X71ZO/ref=sr_1_5?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1NHBHSI8VTMY7&keywords=silver+thermal+paste&qid=1677335269&sprefix=pasta+termica+plata%2Caps%2C133&sr=8-5)

La pasta térmica Arctic MX-4 es una pasta térmica de alta calidad, compuesta por un 99.9% de plata pura y con un diseño de gran viscosidad. Esto garantiza gran estabilidad térmica y una gran disipacion de calor.

 Nuestro Cooler Master MasterLiquid posee ya una pasta térmica de alta calidad, pero muchos expertos en el ensamblaje de equipos de alto rendimiento recomiendan cambiar la pasta térmica que viene por defecto en los coolers liquidos, por una pasta térmica de mayor calidad.
## Bibliografía

[Comparativa entre AES y Blowfish](https://www.researchgate.net/publication/342764235_Comparison_of_Encryption_Algorithms_AES_Blowfish_and_Twofish_for_Security_of_Wireless_Networks#:~:text=Blowfish%20and%20AES%2C%20on%20the,in%20encrypting%20data%20%5B3%5D.)

[Comparativa entre TKIP y AES](https://www.redeszone.net/tutoriales/redes-wifi/contrasenas-wifi-wpa2-aes-tkip/)

[Analisis del rendimiento del ryzen 7950x (incluye prueba de rendimiento AES de AIDA64)](https://www.muycomputer.com/2022/10/13/amd-ryzen-9-7950x-y-ryzen-7-7700x-analisis/)

[Review Artic MX-4](https://www.youtube.com/watch?v=3FCn1KOamuk)