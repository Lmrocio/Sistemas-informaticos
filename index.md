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

  Las placas bases necesitan tener un **formato** o factor de forma que cuente con unas características mecánicas que sean compatibles con la caja en la que tendremos dicha placa. Dichas características tratan de la distribución de los componentes; por ejemplo, la posición de los tornillos, la dimensión de los elementos, etc. La elección de una placa base va a depender del procesador, el tipo de sistema que quieras construir y las características adicionales que necesites. Algunos de los distintos formatos que fueron aprobados a lo largo de la historia son:

- **XT** o _Extended Technology_, desarrollado en 1983 y que estableció el tamaño de un folio A4 con un único conector externo para el teclado.
- **AT** o _Advanced Technology_, es uno de los formatos más grande de la historia con unas dimensiones de 350x279x330mm. Además, estableció un conector de potencia conformado por dos partes.
- **ATX** o _Advanced Technology Extended_, las conexiones exteriores aparecen como un panel de E/S y estableció un conector de veinticuatro pines de energía. Actualmente, podemos encontrarlo con algunas modificaciones que aumentan la energía o reducen su tamaño ya que posee varias ranuras de puertos, permitiendo gran variedad de componentes.
- **ITX** o _Information Technology Extended_ , encontramos un diseño creado para la integración de un gran número de componentes. Así mismo, cuenta con el hardware gráfico en su propio chipset, por lo que no es necesario instalar una tarjate gráfica.
- **BTX** o _Balanced Technology Extended_, fue creada para solventar los problemas de uido y refrigeración; no obstante, no fue bien recibido por la comunidad.
- **MICRO-ATX**, más pequeñas que las ATX manteniendo las prestaciones de esta, aunque poseen menos ranuras de puertos.
- **MINI-ITX**, son las más pequeñas, pensadas para dispositivos compactos de bajo consumo energético. Pese a contar con pocas ranuras, permiten la instalación de los componentes más básicos.
- **E-ATX** o _Extended ATX_, es una versión más grande que las ATX, ofreciendo un mayor número de ranuras (y, por tanto, permitiendo una mayor adicción de componentes). Son empleados para dispositivos de alto rendimeinto.
- **DTX3​**, pensadas para los dispositivos de pequeño formato. Hacen uso de un conector de energía de veinticuatro pines y de un conector adicional de 2 × 2.
- **Formatos privativos**, trata de un esquema de hardware cerrado, dando lugar a placas bases incompatibles con los formatos más inusuales. 


## Componentes

  Encontramos los siguientes componentes:

  1. _Conectores de alimentación_: Suministra los voltajes e intensidades necesarias para el funcionamiento.
  2. _Puertos de CPU_: Podemos encontrar un único zócalo, siendo denominado **monoprocesador**, o más de uno, denominado **multiprocesador**.
  3. _Ranura de RAM_: Suelen aparecen entre 2 a 6 ranuras en la misma placa.
  4. _Chipset_: Es un conjunto de circuitos electrónicos encargados de gestionar las transferencias de datos entre los componentes del ordenador. Estos se dividen en dos secciones:
     - **Puente norte** o _northbrigde_: opera la conexión entre el micropocesador, la memoria RAM y la unidad de procesamiento gráfico.
     - **Puente sur** o _southbrigde_: gestiona la conexión entre los periféricos y los dispositivos de almacenamiento.
  5. _CMOS_: Es una pequeña memoria información importante mientras el dispositivo no está alimentado por electricidad.
  6. _BIOS_: Es un programa que se encarga de la interfaz entre el micropocesador y algunos periféricos. La BIOS inicia, prueba el hardware del sistema y arranca el sistema operativo contenido en un dispositivo de almacenamiento.
  7. _BUS frontal_: El cual conecta el micropocesador con el chipset.
  8. _BUS de memoria_: Conecta al chipset con la memoria temporal.
  9. _BUS de expansión_ o BUS E/S: Conecta al microprocesador con los conectores de E/S (como los puertos USB, conectores jacks, HDMI, DVI, etc) y las ranuras de expansión.
  10. _Ranuras de expansión_: Son slots o receptáculos que acogen tarjetas de expansión, con las cuales podemos añadir características para aumentar el rendimiento del ordenador). Se tratan de puertos como: ISA (Industry Standard Architecture), PCI (Peripheral Component Interconnect), AGP (Accelerated Graphics Port) o PCIe (Peripheral Componente Interconnect Express).
