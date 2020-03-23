## DISEÑO PLATAFORMA WEB DE CONCESIONARIO DE VEHÍCULOS

###### Diseño de un sistema de información para un concesionario 

Diseñar un sistema de información para el concesionario XXX el cual es distribuidor autorizado de vehículos de alta gama, dicho sistema debe permitir la  administración de vehículos por parte del gerente técnico, asigna y personaliza las partes compatibles según el tipo de vehículo, por parte del usuario, se le permitirá realizar una simulación de rendimiento donde podrá consultar la información asociada con el rendimiento del vehículo, consumo de combustible, aceleración, potencia del motor.


El sistema se diseña para su aplicación en un concesionario de vehículos de alta gama. El sistema debe contar con usuarios los cuales pueden acceder a la información referente a: 


  - Vehículos: Pueden existir diferentes modelos de vehículo con características diferentes, aplica solo para gama alta.
  
  - Partes: Hace referencia a componentes específicos de un vehículo. Las partes deben corresponder a un modelo de vehículo con el cual son compatibles (Sistema de inyección de agua, turbo cargador, eje de levas, sistema de escape, filtro de aire, llantas de alto desempeño). 

Además el usuario debe tener la posibilidad de ejecutar simulaciones sobre un modelo de vehículo con unas partes preseleccionadas para obtener información como:
 
  - Consumo de combustible 
  - Aceleración   
  - Potencia del motor

Según la narrativa establecida se detectan los siguientes elementos. 

  - Usuario 
  - Vehículo
  - Parte

Las acciones identificadas son:

  - Gestión de usuario 
  - Gestión de vehículo
  - Gestión de parte
  - Configurar partes del vehículo 
  - Generar simulación


### Modelos UML

Para el diseño del sistema se plantean los siguientes modelos basados en Lenguaje de Modelado Unificado. 

#### Casos de uso

Muestra la funcionalidad global del sistema en tratamiento. Con este se pretende mostrar una vista general de las actividades funcionales que debe contener el diseño del sistema. 

![Image of Yaktocat](https://github.com/iamcamiloperez/ModeloConcesionario-/blob/master/images/Actividades.png)

#### Diagrama de clases persistentes 

El diagrama de clases permite realizar el modelamiento del esquema lógico de la base de datos. Es útil para visualizar la abstracción de los objetos. Este es seleccionado a fin de poder tener una estructura clara del modelo de datos. 


#### Diagrama de objetos

Este diagrama es útil para centrarse en los los atributos y la relación de los objetos entre sí. Funciona a su vez como prueba del diagrama de clases desarrollado al presentar con más detalle la estructura de los objetos del sistema. 

#### Diagramas de actividades

Los diagramas de actividades en UML nos brindan una vista comportamental del sistema presentando el flujo de trabajo de las actividades. Este sistema al tener una importante responsabilidad en el desarrollo de actividades como configuración de vehículos y simulación requiere una atención especial al desarrollo de actividades para garantizar su correcta aplicación y funcionamiento. 
