<p align="center"><img src="https://i.imgur.com/A6bWGFl.gif"/></p>
<h1 align="center"> ⚙️ MEJORA EN LA MANUFACTURA DE PLACAS PBC A TRAVÉS DE UNA MAQUINA CNC PARA ALUMNOS DE TSU EN MECATRÓNICA DENTRO DE LA UTEZ ⚙️ </h1>
<h3 align="center">🚀 Ing. de proyectos 🚀</h3>
<h4> Integrantes: </h4> 
<p>- 👷‍♂️ ARZATE VALLE JOSE MARTÍN </p>  
<p>- 👷‍♂️ FLORES FIGUEROA ALEJANDRO </p> 
<p>- 👷‍♂️ REYES ARAUJO ALDO </p> 
<p>- 👷‍♂️ ROQUE MORALES ALEJANDRO </p> 
<p>- 👷‍♂️ TZEC VARGAS ARATH </p>

### CONTENIDO
#### Descripción del proyecto
- 📚 Resumen
- 🏢 Planteamiento del problema 
- ⚙️ Objetivos
  - General 
  - Específicos 
- Justificación
- Alcances
#### Desarrollo
- 📎 Planeación
- Desarrollo del proyecto
  - Definición del proyecto
  - ✍ Boceto
  - 💰 Presupuesto estimado del proyecto
  - 🔨 Definición de partes mecánicas
  - 💻 Investigación de software de calibración de motores
  - 🖊 Diseño en SolidWorks
  - 💲 Compra de materiales
  - ✂ Cortar los perfiles de aluminio
  - 🖨 Impresión de piezas 3D
  - 👁 Verificar y corregir tolerancias de las piezas impresas
  - 🤏 Ajuste y lubricacion de ejes, rodamientos, guias, etc
  - 🔩 Configuracion, calibracion e instalacion del firmware/software
  - ✔ Prueba de funcionamiento 
#### Resultados y conclusiones 
- Resultados
  - Conclusiones y recomendaciones   

<h4 align="center"> DESCRIPCIÓN DEL PROYECTO </h4> 

##### 📚 Resumen 
<p>Actualmente las máquinas CNC se encuentran en una infinidad de aplicaciones a lo largo y ancho del planeta, desde la fabricación de electrodomésticos, pasando por la ebanistería hasta la producción de piezas para automóviles y aviones. Los beneficios de este tipo de tecnología son muchos, tales como: alta precisión en el fresado, permite mecanizar piezas más complejas, alta repetibilidad, los ajustes iniciales son mínimos y reduce al máximo los errores cometidos por el operario, a la vez que no requiere mucha habilidad por parte del mismo. </p> 
<p>Con la creación del prototipo de una máquina-herramienta CNC para el fresado y perforado automático de PCB, se brinda una calidad final muy alta a un costo de fabricación y esfuerzo muy bajo. </p>
<p>La máquina será de gran ayuda para los estudiantes de ingeniería en mecatrónica y todo tipo de personas que se dediquen al desarrollo de productos electrónicos, debido a que les permitirá llevar fácilmente sus circuitos desde la protoboard hasta la placa de impreso, en un tiempo de producción bastante corto. Por lo tanto, desde el punto de vista funcional, económico, y académico práctico, se confirma como necesario la sistematización del proceso de fabricación de placas de circuito impreso. </p>

##### 🏢 Planteamiento del problema
<p>Las PCB son una pieza fundamental en el montaje final de todo tipo de desarrollo tecnológico, ya que permite darle firmeza al circuito y darle una presentación adecuada, lamentablemente cuando los estudiantes requieren llevar de la protoboard a una PCB sus desarrollos se realiza de manera artesanal como el serigrafiado el cual es un método muy costoso, otro método es el de planchado el cual requiere demasiado tiempo y el peor de los casos dibujar manualmente el circuito sobre la placa. Por supuesto el resultado final deja mucho que desear, ya que no es muy presentable o incluso se pueden generar cortocircuitos que no se observaron y por supuesto el uso de cloruro férrico el cual es nocivo para la salud y el medio ambiente. </p> 

##### 🏹 Objetivos

###### General
- Crear una CNC que nos permita hacer PCBs de manera más precisa y con riesgo de falla mínimo.
###### Específicos 
- Realizar el diseño de cada una de las partes que conformarán la CNC.
Realizar la programación de la máquina-herramienta CNC, para fresar y perforar PCB de forma automática.

##### Justificación
<p>La razón de este proyecto es para que los estudiantes puedan pasar el desarrollo de sus circuitos en protoboard a una placa de circuito impreso con riesgo de falla mínimo, mas preciso, barato y en el menor tiempo posible, ya que los métodos empleados actualmente son muy costosos, requieren de mucho tiempo y se usan sustancias nocivas para la salud, por otro lado, la posibilidad de falla por cortocircuito es mayor debido a que en muchos casos no es posible apreciar a simple vista los errores cometidos. </p> 

##### Alcances
<p>Con este proyecto se pretende diseñar, construir y programar un prototipo de máquina fresadora y perforadora para la elaboración automática de placas de circuito impreso, utilizando para ello el control numérico por computador (CNC). La máquina es capaz de fresar placas de una dimensión máxima de 15x25cm, para ello se utilizan motores paso a paso con una resolución de 200 pasos por vuelta en configuración de paso completo. EI intercambio de herramientas en la máquina se realiza de forma manual, ya que por el reducido número de herramientas necesarias para el fresado y perforado de las PCB, no se hace necesario implementar un intercambiador automático.<p>
  
<h4 align="center"> DESARROLLO </h4> 

##### Planeación
<p>En la siguiente tabla se presenta el Diagrama de Gantt de las actividades a realizar en el proyecto.<p>
 
 |       Actividad       | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 | S11 | S12 | S13 | S14 |
 |-----------------------|----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|
 |Definición de proyecto | X  |    |    |    |    |    |    |    |    |     |     |     |     |     |
 |Elección de proyecto   |    | X  |    |    |    |    |    |    |    |     |     |     |     |     |
 |Boceto del proyecto    |    |    | X  |    |    |    |    |    |    |     |     |     |     |     |
 |Presupuesto            |    |    | X  |    |    |    |    |    |    |     |     |     |     |     |
 |Def. partes mecánicas  |    |    | X  | X  |    |    |    |    |    |     |     |     |     |     |
 |Inv. software de motores|   |    |    | X  | X  |    |    |    |    |     |     |     |     |     |
 |Diseño en SolidWorks   |    |    |    |    | X  | X  | X  |    |    |     |     |     |     |     |
 |Compra de materiales   |    |    |    |    | X  | X  |    |    |    |     |     |     |     |     |
 |Cortar perfiles de aluminio| |   |    |    |    |    | X  |    |    |     |     |     |     |     |
 |Impresión de piezas 3D      |    |    |    |    |    | X  |    |    |     |     |     |     |     |
 |Verificar y corregir tolerancias| | | |    |    |    |    | X  |    |     |     |     |     |     |
 |Ensamble de la CNC     |    |    |    |    |    |    |    |    | X  |     |     |     |     |     |
 |Ajuste y lubricación   |    |    |    |    |    |    |    |    |    |  X  |     |     |     |     |
 |Configuración e instalación de firmware/software|||||||   |    |    |     |  X  |     |     |     |
 |Primer prueba de funcionamiento| | |  |    |    |    |    |    |    |     |     |  X  |     |     |
 |Corrección de errores  |    |    |    |    |    |    |    |    |    |     |     |  X  |  X  |     |
 |Segunda prueba         |    |    |    |    |    |    |    |    |    |     |     |     |  X  |     |
 |Entrega                |    |    |    |    |    |    |    |    |    |     |     |     |     |  X  |
  
##### Desarrollo del proyecto
<p>En esta sección se describe paso a paso todo el procedimiento que se llevó a cabo para el diseño de una CNC con el objetivo de mejorar la manufactura de PCBs y reducir los riesgos de falla.<p>

###### Definición de proyecto
<p>Para comenzar en la realización de este proyecto se pensó en una máquina que diera solución alguna problemática y se eligieron a los integrantes adecuados para formar un equipo de alto rendimiento.<p>

###### Elección de proyecto
 <p>Ya que hemos definido hacia dónde va el proyecto, se dieron varias propuestas que se muestran a continuación:<p>
   
  |         Integrante        |                Prouesta               |
  |---------------------------|---------------------------------------|
  | Arzate Valle Jose Martín  | *Maquina CNC*                         |
  | Flores Figueroa Alejandro | Sistema de llenado y sellado de bolis |
  | Reyes Araujo Aldo         | Protección para soldadura de mano     |
  | Roque Morales Alejandro   | Sistema de enfriamiento de hielera    |
  | Tzec Vargas Arath         | Compuerta automática para perros      |
   
###### ✍ Boceto

###### 💰 Presupuesto estimado del proyecto

###### 🔨 Definición de poartes mecánicas
   
###### 💻 Investigación de software de calibración de motores
<p>GRBL es un firmware para el control de máquinas CNC, está pensado para usarse en placas Arduino con un microcontrolador Atmega328, ya que nos permite configurar el control y desplazamiento de nuestra máquina. Los controladores paso a paso se clasifican para una longitud de impulso mínima de paso.<p>
  
###### 🖊 Diseño en SolidWorks
<p>Para realizar el proyecto de manera física, primero se requiere un diseño que ayudará para evitar problemas y proporcionar parámetros para optimizar aspectos cruciales del proyecto. A continuación, se muestra el diseño en el programa SolidWorks:<p>
  
###### 💲 Compra de materiales
<p>Se realizó la compra de los materiales listados anteriormente por medio de tiendas en línea como lo fueron Amazon y Mercado Libre, en la siguiente figura se muestra el material comprado.<p>
  
###### ✂ Cortar perfiles de aluminio
<p>Se cortaron los perfiles de aluminio en medidas de:
  - 2 perfiles de 40 cm
  - 2 perfiles de 25.5 cm
  - 2 perfiles de 24 cm<p>
    
###### 🖨 Impresión de piezas 3D
  
###### 👁 Verificar y corregir tolerancias de las piezas impresas
  
###### 🤏 Ajuste y lubricación de ejes, rodamientos, guias, etc.
  
###### 🔩 Configuracion, calibracion e instalacion del firmware/software
  
###### ✔ Prueba de funcionamiento 
  
##### Entrega de proyecto
  
<h4 align="center"> RESULTRADOS Y CONCLUSIONES </h4> 

