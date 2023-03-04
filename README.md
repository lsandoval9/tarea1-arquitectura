# Tarea 1 - Arquitectura del computador

![1copy](https://user-images.githubusercontent.com/63022972/221295740-ac8c9cc7-3882-4254-8f71-9e2486ccf059.png)

## Integrantes:

- Luis Sandoval - [Github](https://github.com/lsandoval9)
- Gerardo Díaz - [Github](https://github.com/GerardoDiaz22)

# Construcción de un computador para criptografía

## Introducción
La criptografía es una técnica para proteger la seguridad de la información y las comunicaciones mediante el uso de códigos que solo aquellas personas a las que está destinada dicha información puedan entenderla y procesarla. Previniendo así el acceso no autorizado a los datos enviados. [1,2]

De este modo, el presente documento plantea la construcción de un computador orientado al calculo criptografico, de forma que permita realizar la encriptación y desencriptación de un mensaje. Para lograr este objetivo se propone el uso del algoritmo de encriptación AES, ya que es el algoritmo con mayor popularidad en la industria de redes y ciberseguridad. [3]

Asimismo, para establecer un marco de investigación, se asume una empresa ficticia llamada *Don Gerardo*, con un modelo de negocio enfocado en la venta de computadores para la encriptación de datos. Además, la compañia se enfrenta al desafío de crear una nueva linea de computadoras para satisfacer las necesidades de sus clientes. Los requisitos para la construcción de las mismas son un presupuesto máximo de US$3000, garantizando que no se presenten cuellos de botella y que sean capaces de cumplir sus tareas incluso en situaciones de alto estrés.

#### c-) AES

AES (**A**dvanced **E**ncryption **S**tandard) es un esquema de cifrado estadarizado para encriptar y desencriptar informacion. El proceso involucra el cifrado de la información en bloques, utilizando una llave, que es un conjunto de bits que se utiliza para encriptar y desencriptar la información. El algoritmo AES es un algoritmo de cifrado simetrico, es decir, que utiliza la misma llave para encriptar y desencriptar la información.

AES es el algoritmo seleccionado para la encriptación de datos en **Don Gerardo ©**, debido a que es el algoritmo de cifrado mas usado en la actualidad y uno de los mas seguros.

**Notas curiosa sobre AES**:

- El Esquema AES es tan seguro que esta aprovado por la NSA (Agencia de Seguridad Nacional de los Estados Unidos) y por el gobierno de los Estados Unidos para la encriptación de datos clasificados.

- AES es el algoritmo de cifrado mas usado en la actualidad.

- El algoritmo AES fue desarrollado por el grupo de criptografía de la NIST (Instituto Nacional de Estándares y Tecnología de los Estados Unidos).

- El algoritmo AES puede encontrarse en routers de uso domestico como una alternativa a TKIP, para encriptar el envio y recepción de datos en redes inalambricas.

## Especificaciones del computador

### Procesador: Ryzen 9 7950X3D
#### [US$370.99 - 25/02/2023](https://www.ebay.com/itm/225436166793?hash=item347d0aea89:g:S9wAAOSw1d5j87f5&amdata=enc%3AAQAHAAAAoGdDsaMagfVxrx%2B7%2BkvVsH7RWGzWxuKzdIQ%2FKcYwbbXs8jJ2GnK%2B57A3bAyIPfuNXWTmfO6f0GuIq2rUTSwJB9kUO7VKYM6PKquUkP922Y8Jw1UTQoEwMOCjSLGHBf%2B91%2BRt8u2k1RMHR29XFzGgptHr9ZJ%2F4%2FLRWyn%2Bw1%2Bp1teTegQqWjbbXFxQzh5M0eyCcPzxYw%2B5yuI9T1E%2FvlXXvMk%3D%7Ctkp%3ABk9SR6SgvpDRYQ)

El Ryzen 9 7950x3D es un procesador de 16 núcleos y 32 hilos, con una frecuencia base de 4.2 GHz y una frecuencia turbo de 5.7 GHz. Este procesador es el mas potente de la serie ryzen 9 y es el mas potente de la serie ryzen en general. Este procesador es ideal para la encriptación de datos debido a que cuenta con 16 núcleos y 32 hilos, lo que permite que el procesador pueda realizar varias tareas al mismo tiempo y de una forma eficiente.[4]

En benchmarks como AIDA64, el Ryzen 9 7950X es capaz de encriptar 1.5 GB de datos en 1 segundo, lo que lo convierte en el procesador mas rapido para la encriptación de datos. Inclusive superando a la serie threadripper de AMD. Cabe destacar que el Ryzen 9 7950x3D es una versión superior al Ryzen 9 7950X.[5]

### Tarjeta Madre: GIGABYTE X670 AORUS Elite AX
#### [US$279.00 - 25/02/2023](https://www.amazon.com/GIGABYTE-X670-AORUS-AX-Motherboard/dp/B0BF7FT26Z?th=1)

La tarjeta madre AORUS X679 Elite AX es la seleccionada debido a que cuenta con un socket AM5 para nuestro Ryzen 7950x3D y tiene un diseño avanzado para la disipación del calor llamado thermalguard 3. Este diseño permite que el procesador se mantenga fresco y que no se sobrecaliente, aun en periodos de gran estres.
Ademas, Gigabyte tambien cuenta con un sistema de alto rendimiento llamado Twin 16+2 Power Phase Design. Este ultimo redistribuye la energia de forma eficiente y eficaz, lo que permite que el procesador pueda funcionar a su maxima capacidad.[6]

### Gabinete: CORSAIR 7000D Airflow
#### [US$287.94 - 25/02/2023](https://www.amazon.com/-/es/CORSAIR-7000D-Airflow-Gabinete-torre/dp/B09444VWX2/ref=sr_1_15?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=R00A677PFTGC&keywords=NZXT%2BH510%2BElite&qid=1677278479&sprefix=nzxt%2Bh510%2Belite%2Caps%2C149&sr=8-15&th=1)

El gabinete Corsair 7000D Airflow esta diseñado para que el aire caliente generado por el procesador y la tarjeta madre pueda salir del gabinete por la parte superior del mismo, lo que permite que el aire caliente no se acumule dentro del gabinete y que el aire frio pueda entrar por la parte frontal del mismo. Esto permite que el procesador y la tarjeta madre se mantengan frescos y que no se sobrecalienten, por lo que el procesador podra funcionar a su maxima capacidad.[7]

### Fuente de Poder: EVGA Supernova 1000 P5, 80 Plus Platinum 1000W
#### [US$258.99 - 25/02/2023](https://www.amazon.com/-/es/totalmente-ventilador-autocomprobador-alimentaci%C3%B3n-220-P5-1000-X1/dp/B09C2QJ5W6/ref=psdc_1161760_t2_B09M9639VW)

La fuente de poder EVGA Supernova 1000 P5 es una fuente de poder de 1000W con certificacion Platinum. Esta fuente de poder tambien cuenta con un sistema de ventilacion llamado "fan control with auto sensing", el cual permite que la fuente de poder se mantenga fresca en todo momento. Esta fuente tambien cuenta con condensadores japoneses de alta calidad, con un sistema ultrasilencioso y con protecciones contra cortocircuitos, sobrecargas, sobrecalentamiento y sobre tensiones para mantener a nuestro equipo a salvo de cualquier eventualidad.[8]

### Refrigeración: Cooler Master MasterLiquid ML280 Mirror ARGB
#### [US$ 96.05](https://www.amazon.com/-/es/Cooler-Master-MasterLiquid-ML280-Mirror/dp/B08BV2RHZW/ref=sr_1_3?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=9LFX3P8LHLJX&keywords=liquid%2Bcooler%2BAM5&qid=1677334985&sprefix=liquid%2Bcooler%2Bam5%2Caps%2C198&sr=8-3&th=1)

El Cooler Master MasterLiquid ML280 Mirror ARGB es un cooler liquido que cuenta con un sistema de enfriamiento de 280mm y ademas es compatible con nuestro procesador tipo AM5. Este es un sistema de enfriamiento para procesadores de alto rendimiento, como nuestro Ryzen 7950x3D.[9]

### Memoria RAM: 2 x Kingston Technology Fury Beast Black 16GB 6000MT/s DDR5
#### [US$290.00 (2 x 145.99) - 25/02/2023](https://www.amazon.com/-/es/Kingston-Technology-Beast-Black-4800MT/dp/B09T9BVSW3/ref=sr_1_1?keywords=ram%2Bddr5%2B16gb&qid=1677280785&sprefix=ram%2Bddr5%2Caps%2C186&sr=8-1&th=1)

La memoria RAM Kingston Technology Fury Beast Black 16GB es una memoria RAM de 16GB con una frecuencia de 6000MT/s. Esta memoria RAM es ideal para nuestro procesador Ryzen 7950x3D debido a que cuenta con una frecuencia de 6000MT/s, lo que permite que nuestro procesador pueda funcionar a su maxima capacidad, evitando cuellos de botella al procesar datos. 
Kingston tambien garantiza, al menos un 50% mas de rendimiento que las ultimas gamas de DDR4, ademas de disminuir el consumo de energia en un 40% y de reducir el calor generado por la memoria RAM en un 30%, gracias a su disipador de calor de aluminio.[10]

### Almacenamiento: 2 x Serie Samsung 980 PRO 2TB NVMe M.2
#### [US$358.00 (2 x US$179.99) - 25/02/2023](https://www.amazon.com/-/es/PCIe-NVMe-interno-juegos-MZ-V8P2T0B/dp/B09JHKSNNG/ref=sr_1_4?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=YA8TUVPXTPXW&keywords=nvme%2Bm.2&qid=1677281921&sprefix=nvme%2Bm.2%2Caps%2C162&sr=8-4&th=1)

El NVMe M.2 Samsung 980 PRO 2TB es un disco duro de estado solido con una capacidad de 2TB. Esta unidad cuenta con una velocidad de lectura de 7.000 MB/s y una velocidad de escritura de 5.000 MB/s. Su alta velocidad de lectura y escritura permite que nuestro procesador pueda procesar datos a una velocidad mucho mas rapida al tratarse de grandes bancos de datasets.[11]


### Tarjeta de Video: Gigabyte GeForce RTX 4070 Ti AERO OC 12G
#### [US$1,011.08 - 25/02/2023](https://www.amazon.com/-/es/Gigabyte-ventiladores-WINDFORCE-GV-N407TAERO-OC-12GD/dp/B0BRR1MPTX/ref=sr_1_13?keywords=geforce+rtx+4070+ti&qid=1677331967&sprefix=gefeorce+rt%2Caps%2C139&sr=8-13)

La GeForce RTX 4070 Ti AERO OC 12G es una tarjeta de video con una capacidad de 12GB de memoria RAM. Esta tarjeta cuenta con 7680 CUDA cores, 480 Tensor cores y 120 Ray tracing cores. Esta tarjeta tambien cuenta con un sistema de enfriamiento llamado "WINDFORCE 3X", lo que permite que se mantenga a temperaturas bajas incluso en periodos de gran estres.[12]

Los Cuda cores son utiles para el procesamiento de grandes cantidades de datos, los Tensor cores son utiles para el procesamiento de datos de gran complejidad. Esto es util cuando se necesitan procesar grandes bancos de datasets desde la memoria secundaria, sobre todo cuando se trata de archivos que no son texto plano como imagenes, videos, etc. Nuestro equipo debe ser capaz de procesar grandes cantidades de datos en paralelo, por lo que es beneficioso que nuestra tarjeta de video cuente con una gran cantidad de Cuda cores y Tensor cores para apoyar al procesador. Esto es util tambien para el procesamiento y encriptacion de datos usando AES o RSA.[13]

### Pasta Térmica: Arctic MX-4
#### [US$21.99 - 25/02/2023](https://www.amazon.com/-/es/compuesto-t%C3%A9rmico-densidad-polisint%C3%A9tico-AS5-12G-R/dp/B0087X71ZO/ref=sr_1_5?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1NHBHSI8VTMY7&keywords=silver+thermal+paste&qid=1677335269&sprefix=pasta+termica+plata%2Caps%2C133&sr=8-5)

La pasta térmica Arctic MX-4 es una pasta térmica de alta calidad, compuesta por un 99.9% de plata pura y con un diseño de gran viscosidad. Esto garantiza gran estabilidad térmica y una gran disipacion de calor.[14]

El Cooler Master MasterLiquid ya posee una pasta térmica de alta calidad, pero muchos expertos en el ensamblaje de equipos de alto rendimiento recomiendan cambiar la pasta térmica que viene por defecto en los coolers liquidos, por una pasta térmica de mayor calidad.[15]

### Presupuesto: US$ 3000
### Precio total: US$ 2974.04

## Bibliografía

[1] https://www.geeksforgeeks.org/cryptography-and-its-types/
[2] https://ieeexplore.ieee.org/abstract/document/8757514
[3] https://techjury.net/blog/what-is-aes/#gref
[4] https://www.amd.com/es/products/apu/amd-ryzen-9-7950x3d
[5] https://www.muycomputer.com/2022/10/13/amd-ryzen-9-7950x-y-ryzen-7-7700x-analisis/
[6] https://www.gigabyte.com/Motherboard/X670-AORUS-ELITE-AX-rev-10#kf
[7] https://www.corsair.com/ru/es/Categorías/Productos/Chasis/Chasis-de-supertorre-y-torre-completa/7000D-AIRFLOW-Full-Tower-ATX-PC-Case/p/CC-9011218-WW
[8] https://www.evga.com/Products/product.aspx?pn=220-P5-1000-X1
[9] https://www.coolermaster.com/catalog/coolers/cpu-liquid-coolers/masterliquid-ml280-mirror/
[10] https://www.kingston.com/es/memory/gaming/kingston-fury-beast-ddr5-memory
[11] https://www.samsung.com/es/memory-storage/nvme-ssd/980-pro-2tb-nvme-pcie-gen-4-mz-v8p2t0bw/
[12] https://www.gigabyte.com/es/Graphics-Card/GV-N407TAERO-OC-12GD#kf
[13] https://link.springer.com/chapter/10.1007/978-981-15-5558-9_39
[14] https://www.arctic.de/en/MX-4/ACTCP00007B
[15] https://linustechtips.com/topic/510610-never-leave-pre-applied-thermal-paste-on-your-cpu-read_me/