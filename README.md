# Buenos Aires Compras - Estándar de Datos para las Contrataciones Abiertas
Documentación de la publicación de los datos de Compras y Contrataciones del GCBA bajo el estándar Open Contracting.

## Política de Publicación 

La política de datos abiertos del Gobierno de la Ciudad de Buenos Aires tiene sus inicios en 2012 con el lanzamiento del portal data.buenosaires.gob.ar, el cual al día de hoy ya concentra más de 1000 recursos disponibles en formato abierto. Hace más de una década que la Ciudad cuenta con el sistema de compras y contrataciones públicas llamado BAC (Buenos Aires Compras), el cual garantiza transparencia y celeridad en los procesos. Si bien desde sus inicios el sistema contaba con un portal para consultar información acerca de los procesos de compra, la misma no se encontraba en formato abierto lo cual obstaculizaba su reutilización. Desde principios del año 2018 el Gobierno de la Ciudad de Buenos Aires comenzó a trabajar en la publicación de la información del sistema de compras y contrataciones públicas BAC (Buenos Aires Compras) en formato abierto. Con este trabajo, se pone a disposición de la ciudadanía, el acceso a información sobre las contrataciones públicas que le permite saber cómo se gestionan las mismas. La disponibilidad de estos datos fue un salto cualitativo fundamental, garantizando el derecho a la información, fortaleciendo la transparencia de los actos de gobierno.

El procedimiento de compras y contrataciones que se realiza en la ciudad, se instrumenta a través del Sistema de Registro Informatizado de Contrataciones en el ámbito del Ministerio de Hacienda de la Ciudad de Buenos Aires. Regulada por la Ley N° 2.095, Ley de Compras y Contrataciones de la Ciudad de Buenos Aires y su decreto reglamentario.

La adopción del Estándar de Datos para las Contrataciones Abiertas (OCDS por sus siglas en inglés) fue un desafío para el Gobierno de la Ciudad que implicó la revisión de sus procesos actuales y traducción de los mismos al estándar dispuesto por Open Contracting Partnership. Con este trabajo, se contribuyó a la política de transparencia e integridad pública que se lleva adelante y de esta forma, inspirar a otras ciudades a encarar procesos similares. 

La publicación de las compras y contrataciones en formato abierto y con el estándar de Contrataciones Abiertas fue gracias al trabajo en conjunto entre el Ministerio de Economía y Finanzas y Secretaría General y Relaciones Internacionales del Gobierno de la Ciudad de Buenos Aires.


### 1- Propósito de la publicación

El Estándar de Datos para las Contrataciones Abiertas (OCDS) es una estándar global de datos que promueve la divulgación de datos y documentos en todas las etapas del proceso de contratación. Este estándar ha sido desarrollado para que los proveedores de información compartan datos estructurados, estandarizados y reutilizables.

La publicación de los datos de contratación, se encuentran disponibles data.buenosaires.gob.ar y tiene como objetivo garantizar que toda la información que se produce en las compras y contrataciones públicas de bienes y servicios en la ciudad estén disponibles en línea y en formatos abiertos.  

La importancia de la adaptación a este estándar radica en:

- Mejorar la calidad de los datasets publicados.
- Mejorar la capacidad de comprensión de los datasets utilizados.
- Impulsar la adopción de estándares para la apertura de datos.
- Impulsar la reutilización de los datos abiertos.
- Promover la toma de decisiones basadas en evidencia.
- Mejorar la competitividad entre los proveedores de gobierno.
- Reducir los costos y optimizar la relación precio calidad que enfrentan las áreas de gobierno.

### 2- Detalles de la publicación


Con previa autorización del Ministerio de Economía y Finanzas, la Dirección General de Calidad Institucional y Gobierno Abierto (DGCIGA), responsable de la política de gobierno abierto, accede a la base de datos de Buenos Aires Compras (BAC), la cual  incluye todos los procesos de compra en sus distintas etapas:
- Convocatoria: Licitación o concurso
- Adjudicación 
- Contratación: Detalle de órdenes de compra
	
	Los procesos de compras y contrataciones que se incluyen en la extracción de datos están relacionados con las modalidades especificadas en el sistema BAC y se detallan a continuación: 
	
Pliegos de Bases y Condiciones Generales: contiene el conjunto de condiciones aplicables a la totalidad de los contratos del Gobierno de la Ciudad, lo elabora y aprueba la Dirección General de Compras y Contrataciones en su carácter de Órgano Rector. 

Pliegos de Bases y Condiciones Particulares: contiene las especificaciones que se establecen para cada contrato en particular, por ejemplo, cantidades, lugares, plazos de entrega y de pago, etc. Estos pliegos son elaborados por las distintas UOAs.

Orden de compra cerrada: procede en el caso que la cantidad de bienes o servicios a contratar se fije concretamente en el contrato. 

Orden de compra abierta: procede en el caso que la cantidad de bienes o servicios se fije sólo de forma aproximada en el contrato pudiendo realizar requerimientos en el lapso de duración. 

Compra unificada: cuando dos o más reparticiones desean adquirir un mismo tipo de bien o servicio y se tramita de forma conjunta. 

Subasta inversa: se adjudica al precio más bajo o a la oferta económica más ventajosa luego de efectuada la compulsa interactiva de precios. 

Convenio Marco: se selecciona uno o más proveedores para procurar el suministro directo de bienes y servicios a las unidades ejecutoras en la forma, plazo y demás condiciones establecidas en dicho convenio. 

Teniendo en cuenta las distintas etapas que conforman los procesos y las modalidades de contratación, los procedimientos de selección que se encuentran incluidos en el sistema BAC, son los siguientes: 

Licitación Pública: la licitación o concurso es público cuando el llamado a participar está dirigido a una cantidad indeterminada de posibles oferentes con capacidad para obligarse, sin perjuicio del cumplimiento de los demás requisitos que exija el pliego de bases y condiciones particulares y el pliego de bases y condiciones generales.

Licitación Privada: la licitación o concurso privado es el procedimiento de selección en el cual intervienen como oferentes los invitados en forma directa, sin anuncio público y debidamente fundado por el organismo licitante, debiendo hallarse inscriptos en el Registro Informatizado Único y Permanente de Proveedores.

Contratación Directa: la contratación es directa cuando se selecciona directamente al proveedor, debiendo encontrarse dicha medida debidamente fundada y ponderada por la autoridad competente. 

Contratación Menor: es aquel procedimiento de contratación directa que se aplica cuando el monto total de la contratación no supere el equivalente a cien mil (100.000) unidades de compra.

### 2.1. 	Creación de Datasets OCDS
La Dirección General de Compras y Contrataciones dependiente del Ministerio de Economía y Finanzas de la Ciudad de Buenos Aires realiza la instrumentación de los procedimientos para la tramitación de compras o contrataciones, cualquiera sea su modalidad o naturaleza, interviniendo en todas las instancias del trámite administrativo que se derivan de la acción de contratar, regulado por la Ley de Compras y Contrataciones de la Ciudad de Buenos Aires y su decreto reglamentario. 

La Dirección General de Calidad Institucional y Gobierno Abierto posee el permiso para la extracción completa de la base de datos de Buenos Aires Compras (BAC) que incluyen las tres etapas del proceso de compras y contrataciones, las modalidades de contratación y los procedimientos de selección, descriptos precedentemente. 

Las modalidades de contratación se encuentran detalladas como prefijo en los valores de campo contracts/0/id. 

- SPR- para los contratos con modalidad orden de compra abierta

- OCC- para los contratos con modalidad orden de compra cerrada

- CM- para los contratos con modalidad convenio marco

Los procedimientos de selección de los proveedores se encuentran detallados en el campo  procurementMethod y procurementMethodDetails de la etapa “tender”. 

Esta información es proporcionada a través de un archivo CSV con datos estructurados y la conversión a OCDS se realiza a través de un script de python. La publicación de datos de compras de bienes o servicios bajo el estándar propuesto están disponibles en formato CSV y JSON. Su actualización se realiza con una frecuencia de 15 días corridos.

### 2.2. Acceso a los datos 

El acceso a los datos de compras y contrataciones de bienes y servicios de la ciudad en formato abierto, se realiza a través del portal de datos abiertos data.buenosaires.gob.ar.

#### Portal de datos
Buenos Aires Data es el portal de datos abiertos de la ciudad, está disponible en data.buenosaires.gob.ar.  Utiliza código abierto CKAN / Andino desarrollado por el Gobierno Nacional. CKAN es un software libre que permite la organización de los datos publicados a través de un esquema de conjunto de datos y recursos, así como el acceso programático a estos, aplicando estándares aprobados internacionalmente para la generación de datos. Este software es distribuido bajo la licencia GNU Affero General Public License. 

La implementación de está nueva tecnología implica una mejor experiencia de usuario ya que dispone de una interfaz moderna, que permite incorporar nuevas secciones, agregando valor a la publicación de los datos: 

- #HistoriaConDatos: se realiza la publicación de investigaciones, análisis, visualizaciones y desarrollos que usan datos abiertos para ponerlos en valor. 

- Google Dataset Search: todo el contenido de BA Data es descubrible a través del buscador google. 

En nuestro portal, se puede encontrar el dataset de las compras y contrataciones de la ciudad bajo el estándar Open Contracting en 10.17.1.206/dataset?q=bac. 

#### Datos OCDS

Los datos OCDS se encuentran disponibles en formato JSON y CVS. 

JSON es un formato para realizar intercambio de datos y puede ser leído por cualquier lenguaje de programación. Este formato describe nombres y definiciones de campos, además de estructuras para los datos.

Por su parte, CVS representa datos en forma de tabla. Existen varias  técnicas para transformar un archivo JSON a un archivo CVS y las herramientas recomendadas por Open Contrating Partnership (OCP), se pueden encontrar en: standard.open-contracting.org/latest/es/implementation/serialization/. 




#### Links a otros datos relevantes 

El Gobierno de la Ciudad de Buenos Aires también publica otro conjunto de datos que los usuarios pueden encontrar útiles en el contexto de nuestras publicaciones OCDS. 

Los datos sobre presupuesto sancionado y presupuesto ejecutado están disponibles sin la aplicación del formato Open Contracting. El presupuesto sancionado de la ciudad se encuentra disponible en data.buenosaires.gob.ar/dataset/presupuesto-sancionado contando con datos desde el año 2005. Por otro lado, el presupuesto ejecutado se encuentra disponible en https://data.buenosaires.gob.ar/dataset/presupuesto-ejecutado desde el año 2015 a la fecha. 

### 3- Alcance de los datos 
	
#### Fecha 
marzo de 2011 - Actualidad
#### compradores 
Los compradores son las unidades ejecutoras del Gobierno de la Ciudad de Buenos Aires.Incluye las áreas de Jefatura de Gobierno, Vicejefatura, Jefatura de Gabinete de Ministros, Ministerios, Secretarías, Subsecretarías, Direcciones Generales, Unidades de proyectos especiales. 
#### Valores 
El Gobierno de la Ciudad de Buenos Aires no tiene un valor de contratación por debajo o por encima del cual se excluyan los datos de contratación.
#### Tipos de proceso
Orden de compra abierta, orden de compra cerrada, compra unificada, subasta inversa y convenio Marco. 
#### Etapas 
Publicamos los datos de convocatoria, licitación o concurso, adjudicación y contratos para cada proceso de contratación. 
#### Cantidad de procesos
La cantidad de procesos publicados es creciente con el correr de los años. Esto se encuentra directamente relacionado con la extensión del uso del sistema BAC para gestionar compras y contrataciones.


##### [Diccionario de campos](http://standard.open-contracting.org/latest/es/schema/reference/)


#### 3.2. Aspectos legales y OCDS

El Gobierno de la Ciudad lleva adelante la política de apertura de datos desde el años 2012 con la firma del decreto 156/2012. Esto impulsó la creación de la plataforma de datos publicos data.buenosaires.gob.ar para facilitar la búsqueda, descubrimiento y acceso de los datos abiertos producidos por la ciudad. 

A fines de 2015, la Ciudad firmó la Carta Internacional de Datos Abiertos a través de la cual, se compromete a seguir e implementar los lineamientos para datos públicos. Sumado, a la sanción de la Ley de Acceso a la Información Pública (Ley N° 104) implicó un avance en materia de apertura ya que establece el formato abierto como criterio fundamental. 

La Dirección General de Calidad Institucional y Gobierno Abierto es el área responsable de diseñar e implementar la política de datos abiertos de la ciudad a través de data.buenosaires.gob.ar. Actualmente, aplicamos el estándar Open Contracting a través de la publicación de datos OCDS. 

### 4- Codigos, lista de códigos y extensiones utilizadas en la publicación de datos 

- Códigos: Items
- Nombre de la lista: x_catalogo_bienes_servicios_BAC
- Descripción: Listado de códigos utilizados en el sistema BAC para identificar bienes o servicios y sus respectivos modelos. Disponible aquí[https://catalogoba.dguiaf-gcba.gov.ar/]. Usuario: CATALOGO ; Contraseña: consulta

- Códigos: Unidades de medida
- Nombre de la lista: x_unidades_medida_bac
- Descripción: Unidades de medida utilizadas en el sistema BAC

- Códigos: Unidades de medida
- Nombre de la lista: UNCEFACT
- Descripción: Códigos de unidades de medida propuestos por Naciones Unidas para el comercio internacional.

- Códigos: Código de identificación de proveedores
- Nombre de la lista: AR-CUIT
- Descripción: Listado de códigos utilizados para identificar a los proveedores de bienes o servicios. Se construye en base al número de CUIT de los mismos.

- Códigos: Código de identificación de unidades ejecutoras y unidades operativas de adquisiciones
- Nombre de la lista: CABA-UE
- Descripción: Listado de códigos utilizados para identificar a las agencias de gobierno que participan del proceso de compras.

- Campo: procurementMethod 
- Valor OCDS: direct
- Valor BAC: contratación menor; contratación directa

- Campo: procurementMethod
- Valor OCDS: open
- Valor BAC: licitación pública

- Campo: procurementMethod
- Valor OCDS: limited
- Valor BAC: licitación privada

- Extensión utilizada: Signatories
- Descripción: Listado de participantes en la firma del contrato. Compradores, proveedores y entidades procuradoras
- Link a la extensión: https://github.com/open-contracting-extensions/ocds_contract_signatories_extension

### 5- Responsabilidad, información de contacto y comentarios 

La Dirección General de Compras y Contrataciones (DGCYC) del Ministerio de Economía y Finanzas es el responsable de producir la información de las compras y contrataciones que se registran en el sistema Buenos Aires Compras (BAC). Para entender el proceso de compras de la ciudad, la Dirección General de Compras y Contrataciones (DGCYC) pone a disposición de los empleados y proveedores del Gobierno de la Ciudad, cursos de capacitación presenciales y de forma online. Para solicitar información sobre los cursos online puede acceder al campus virtual dguiafvirtual.buenosaires.gob.ar/ o puede enviar un mail a logistica@dguiaf-gcba.gov.ar. 

La Dirección General de Calidad Institucional y Gobierno Abierto (DGCIGA) es responsable de la implementación del estándar Open Contracting y de la publicación de los OCDS. Ante cualquier comentario o duda puede contactarse por mail a través de gobiernoabierto@buenosaires.gob.ar . Cuando nos envíe sus comentarios, realizaremos un análisis y seguimiento del tema planteado, posteriormente nos pondremos en contacto para informar sobre los resultados y/o acciones posteriores.
 

### 6- Licencias 

La publicación de los datos de compras y contrataciones del sistema BAC en el Estándar para las Contrataciones Abiertas (OCDS) se realiza bajo la licencia Creative Commons Legal Code Atribución 2.5 Argentina. Esto permite que los usuarios de datos realicen las siguientes acciones: 

- Compartir, copiar y redistribuir material en cualquier medio o formato. 
- Adaptar, remezclar, transformar y construir a partir del material para cualquier propósito, incluso comercial. 
- Utilizar estos datos para cualquier propósito, incluido uso comercial y no comercial.
- Publicar contenido basado en el uso de los datos publicados.

El texto completo de la licencia, se puede encontrar en creativecommons.org/licenses/by/2.5/ar/legalcode 


### 7- Documentación Adicional 

Ley 104 de Acceso a la Información Pública establece la obligación de los distintos sujetos obligados de publicar en sus respectivas páginas web, de manera completa y actualizada y en lo posible en formatos abiertos y reutilizables, la información relativa a contrataciones públicas. Se puede encontrar la ley completa así como el marco normativo en buenosaires.gob.ar/gobierno/ley-ndeg-104. 

La normativa completa que regula la compra y contratación de bienes y servicios de la ciudad, que incluye la Ley Nº 2090 y su decreto reglamentario Decreto N° 326/17, se encuentran disponibles en buenosairescompras.gob.ar/normativa.aspx.

El Pliego Único de Bases y Condiciones Generales para los procesos de compras y contrataciones mediante BAC, aprobado por Disposición Nº 396/DGCYC/14 se encuentra disponible en el portal de compras, tanto en la sección “Normativa” como en cada uno de los procesos tramitados por esa vía. 
