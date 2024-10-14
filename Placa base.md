# PLACAS BASES

## Evolución

  > La **placa base**, conocida como placa madre o placa principal, es una tarjeta de circuito impreso que conecta los componentes que conforman un ordenador. Se       conforma de una serie de circuitos integrados que veremos en el apartado `Componentes`

  Antes de su invención, los sistemas informáticos eran ensamblados en **mainframes**, con un conjunto de engranajes unidos a un panel posterior; para ello, se requería cables que unían las clavijas del conector de la tarjeta. Este sistema fue reemplazado por las placas de circuito impreso. Los primeros ordenadores tenían una estructura simple con firmware que almacenaban las intrucciones acerca del comportamiento del ordenador. El problema que suponía era que, con cada cambio, era necesario **reescribir el almacenamiento del firmware**; es decir, si el usuario quería cambiar un componente de su dispositivo, debía, además, reescribir el firmware con la información necesario para el nuevo componente.

  A finales de los 80' surgió el concepto de placa base de la mano de la ingeniera **Patty McHugh**. IBM denominó a esta placa base como *Planar*, siendo un modelo básico a lo que hoy conocemos que contenía la CPU y la RAM. Con este invento, ya no era necesario reescribir la información, sino instalar un nuevo **driver**. Posteriormente, en la década de los 90', se comezaron a incluir diversos componentes a la placa base: periféricos de baja velocidad (como teclados o puertos serie), elementos de audio, video, redes, almacenamiento, tarjetas gráficas, etc.

```
El concepto de la placa base se mantiene desde su invención, siendo la única diferencia los nuevos elementos que se han ido
añadiendo. De este modo, podríamos decir que, actualmente, las placas bases son más complejas aunque su funcionalidad
permanezca inalterada.
```

## Formato 

  Las placas bases necesitan tener un **formato** o factor de forma que cuente con unas características mecánicas que sean compatibles con la caja en la que tendremos dicha placa. Dichas características tratan de la distribución de los componentes; por ejemplo, la posición de los tornillos, la dimensión de los elementos, etc. Algunos de los distintos formatos que fueron aprobados a lo largo de la historia son:

- **XT** o _Extended Technology_, desarrollado en 1983 y que estableció el tamaño de un folio A4 con un único conector externo para el teclado.
- **AT** o _Advanced Technology_, es uno de los formatos más grande de la historia con unas dimensiones de 350x279x330mm. Además, estableció un conector de potencia conformado por dos partes.
- **ATX** o _Advanced Technology Extended_, las conexiones exteriores aparecen como un panel de E/S y estableció un conector de veinticuatro pines de energía. Actualmente, podemos encontrarlo con algunas modificaciones que aumentan la energía o reducen su tamaño.
- **ITX** o _Information Technology Extended_ , encontramos un diseño creado para la integración de un gran número de componentes. Así mismo, cuenta con el hardware gráfico en su propio chipset, por lo que no es necesario instalar una tarjate gráfica.
- **BTX** o _Balanced Technology Extended_, fue creada para solventar los problemas de uido y refrigeración; no obstante, no fue bien recibido por la comunidad.
- **DTX3​**, pensadas para los dispositivos de pequeño formato. Hacen uso de un conector de energía de veinticuatro pines y de un conector adicional de 2 × 2.
- **Formatos privativos**, trata de un esquema de hardware cerrado, dando lugar a placas bases incompatibles con los formatos más inusuales. 


## Componentes

  Encontramos los siguientes componentes:

  1. _Conectores de alimentación_: Suministra los voltajes e intensidades necesarias para el funcionamiento.
  2. _Puertos de CPU_: Podemos encontrar un único zócalo, siendo denominado **monoprocesador**, o más de uno, denominado **multiprocesador**.
  3. _Ranura de RAM_: Suelen aparecen entre 2 a 6 ranuras en la misma placa.
  4. _Chipset_: 
  5. 

El chipset es una serie o conjunto de circuitos electrónicos, que gestionan las transferencias de datos entre los diferentes componentes de la computadora (procesador, memoria, tarjeta gráfica, unidad de almacenamiento secundario, etcétera).

El chipset, generalmente se divide en dos secciones:

Puente norte (northbridge): gestiona la interconexión entre el microprocesador, la memoria RAM y la unidad de procesamiento gráfico.
Puente sur (southbridge): gestiona la interconexión entre los periféricos y los dispositivos de almacenamiento, como los discos duros o las unidades de disco óptico.
Las nuevas líneas de procesadores de escritorio tienden a integrar el propio controlador de memoria dentro del procesador.

