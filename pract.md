# Repaso Certificacion AWS Practitioner

## Conceptos Cloud

### Fundamentos del Cloud

Cloud Foundations proporciona una ruta guiada para ayudar a los clientes a implementar, configurar y proteger sus nuevas cargas de trabajo, garantizando al mismo tiempo que están preparados para las operaciones continuas en el Cloud. Cloud Foundations ayuda a los clientes a navegar a través de las decisiones que necesitan tomar mediante Servicios de AWS, Soluciones de AWS, Soluciones de socios y Orientación.

### Amazon Machine Image (AMI)

Una Amazon Machine Image (AMI) proporciona la información necesaria para lanzar una instancia. Debes especificar una Amazon Machine Image (AMI) cuando lances una instancia. Puedes lanzar varias instancias desde una única AMI cuando necesites varias instancias con la misma configuración.

La Amazon Machine Image (AMI) debe estar en la misma región que la de la instancia de Amazon EC2 que se va a lanzar. Si la Amazon Machine Image (AMI) existe en una región diferente, puedes copiar esa Amazon Machine Image (AMI) a la región en la que deseas lanzar la instancia EC2. La región de la Amazon Machine Image (AMI) no influye en el rendimiento de la instancia de Amazon EC2.

### VPC

Amazon Virtual Private Cloud (Amazon VPC) es una sección lógicamente aislada del Cloud de AWS donde puedes lanzar recursos de AWS en una red virtual que tú defines. Tienes un control total sobre tu entorno de red virtual, incluida la selección de tu rango de direcciones IP, la creación de subredes y la configuración de tablas de rutas y gateways de red. Una Amazon Virtual Private Cloud (Amazon VPC) abarca todas las zonas de disponibilidad (AZ) de la región.

Una subred es un rango de direcciones IP dentro de tu Amazon Virtual Private Cloud (Amazon VPC). Una subred abarca sólo una zona de disponibilidad (AZ) de la región.

Amazon Virtual Private Cloud (Amazon VPC) abarca todas las zonas de disponibilidad (AZ) de la región, mientras que una subred abarca sólo una zona de disponibilidad (AZ) de la región

### AWS Cost & Usage Report (AWS CUR)

AWS Cost & Usage Report (AWS CUR) contiene el conjunto más completo de datos de costes y uso disponible. Puedes utilizar el AWS Cost & Usage Report (AWS CUR) para publicar tus informes de facturación de AWS en un bucket de Amazon Simple Storage Service (Amazon S3) de tu propiedad. Puedes recibir informes que desglosen tus costes por hora o mes, por producto o recurso de producto, o por etiquetas que tú mismo definas. AWS actualiza el informe en tu bucket una vez al día en formato de valores separados por comas (CSV).

### AWS CloudTrail

Puedes utilizar CloudTrail para registrar, monitorizar y conservar la actividad de la cuenta relacionada con acciones en toda tu infraestructura de AWS. CloudTrail proporciona un historial de eventos de la actividad de tu cuenta de AWS, incluidas las acciones realizadas a través de la consola de administración de AWS, los SDK de AWS, las herramientas de línea de comandos y otros servicios de AWS.

Cómo funciona CloudTrail:
![como_funciona_cloud_trail](img/Product-Page-Diagram-AWSX-CloudTrail_How-it-Works.d2f51f6e3ec3ea3b33d0c48d472f0e0b59b46e59.png)

AWS CloudTrail es un servicio que permite la gobernanza, la normativa, la auditoría operativa y la auditoría de riesgos de tu cuenta de AWS. Con AWS CloudTrail, puedes registrar, monitorizar continuamente y conservar la actividad de la cuenta relacionada con acciones en toda tu infraestructura de AWS. AWS CloudTrail proporciona un historial de eventos de la actividad de tu cuenta de AWS, incluidas las acciones realizadas a través de la consola de administración de AWS, los SDK de AWS, las herramientas de línea de comandos y otros servicios de AWS.

### AWS Config

AWS Config es un servicio que te permite evaluar, auditar y valorar las configuraciones de tus recursos de AWS. Config monitoriza y registra continuamente las configuraciones de tus recursos de AWS y te permite automatizar la evaluación de las configuraciones registradas comparándolas con las configuraciones deseadas.

Con AWS Config, puedes hacer lo siguiente:

1. Evaluar tus configuraciones de recursos de AWS en función de los ajustes deseados

2. Obtener una instantánea de las configuraciones actuales de los recursos soportados que están asociados a tu cuenta de AWS. 

3. Recupera las configuraciones de uno o más recursos que existan en tu cuenta. 

4. Recuperar configuraciones históricas de uno o más recursos. 

5. Recibir una notificación cada vez que se cree, modifique o elimine un recurso. 

6. Ver las relaciones entre recursos. Por ejemplo, puedes querer encontrar todos los recursos que utilizan un grupo de seguridad determinado.

### Amazon CloudWatch

Amazon CloudWatch es un servicio de monitorización y observabilidad creado para ingenieros DevOps, desarrolladores, ingenieros de fiabilidad de sitios (SRE) y administradores de TI. CloudWatch proporciona datos y perspectivas procesables para monitorizar aplicaciones, responder a cambios de rendimiento en todo el sistema, optimizar la utilización de recursos y obtener una visión unificada de la salud operativa. Es un servicio excelente para construir sistemas resistentes.

### CloudWatch Logs

Puedes utilizar Amazon CloudWatch Logs para monitorizar, almacenar y acceder a tus archivos de registro desde instancias de Amazon Elastic Compute Cloud (Amazon EC2), AWS CloudTrail, Route 53 y otras fuentes como servidores locales.

Amazon CloudWatch Logs te permite centralizar los logs de todos tus sistemas, aplicaciones y servicios de AWS que utilices, en un único servicio altamente escalable. Luego puedes verlos fácilmente, buscar en ellos códigos de error o patrones específicos, filtrarlos en función de campos concretos o archivarlos de forma segura para futuros análisis.

### AWS Trusted Advisor

AWS Trusted Advisor es una herramienta online que te proporciona orientación en tiempo real para ayudarte a aprovisionar tus recursos siguiendo las mejores prácticas de AWS sobre optimización de costes, seguridad, tolerancia a fallos, límites de servicio y mejora del rendimiento.

### CloudWatch vs CloudTrail vs Config

Piensa en supervisión del rendimiento de los recursos, eventos y alertas; piensa en CloudWatch.

Piensa en actividad y auditoría específicas de la cuenta; piensa en CloudTrail.

Piensa en el historial de cambios, la auditoría y el cumplimiento de recursos específicos; piensa en Config.

### AWS Snowball

AWS Snowball, que forma parte de la familia AWS Snow, es un dispositivo de migración de datos e informática de borde. Si tienes grandes cantidades de datos que necesitas migrar a AWS, la transferencia de datos offline con AWS Snowball puede superar el reto del ancho de banda limitado, y evitar la necesidad de alquilar ancho de banda adicional. AWS Snowball mueve terabytes de datos en aproximadamente una semana. Puedes utilizarlo para mover cosas como bases de datos, copias de seguridad, archivos, registros sanitarios, conjuntos de datos analíticos, datos de sensores IoT y contenido multimedia, especialmente cuando las condiciones de la red impiden plazos realistas para transferir grandes cantidades de datos tanto dentro como fuera de AWS.

### El AWS Well-Architected Framework

proporciona orientación sobre la creación de infraestructuras seguras, de alto rendimiento, resistentes y eficientes para aplicaciones basadas en el Cloud. ***Basado en seis pilares***:

- **excelencia operativa**
- **seguridad**
- **fiabilidad**
- **eficiencia del rendimiento**
- **optimización de costes**
- **sostenibilidad**

#### Excelencia operativa

El AWS Well-Architected Framework te ayuda a comprender los pros y los contras de las decisiones que tomas al crear sistemas en AWS. Utilizando el Framework aprenderás las mejores prácticas de arquitectura para diseñar y operar sistemas fiables, seguros, eficientes y rentables en el Cloud. Te proporciona una forma de medir sistemáticamente tus arquitecturas con respecto a las mejores prácticas e identificar áreas de mejora.

El AWS Well-Architected Framework se basa en seis pilares: Excelencia Operativa, Seguridad, Fiabilidad, Eficiencia de Rendimiento, Optimización de Costes y Sostenibilidad.

El pilar de la excelencia operativa incluye la capacidad de ejecutar y supervisar sistemas para aportar valor empresarial y mejorar continuamente los procesos y procedimientos de apoyo. En el Cloud, puedes aplicar a todo tu entorno la misma disciplina de ingeniería que utilizas para el código de las aplicaciones. Puedes definir toda tu carga de trabajo (aplicaciones, infraestructura) como código y actualizarla con código. Puedes implementar tus procedimientos operativos como código y automatizar su ejecución activándolos en respuesta a eventos.

#### Optimización de costes

La optimización de costes se centra en evitar costes innecesarios. Los temas clave incluyen comprender y controlar dónde se gasta el dinero, seleccionar los tipos de recursos más adecuados y el número correcto, analizar el gasto a lo largo del tiempo y escalar para satisfacer las necesidades de la empresa sin gastar más de la cuenta.

el Framework proporciona un enfoque coherente para que clientes y socios evalúen arquitecturas e implanten diseños que escalen con el tiempo.

#### Eficiencia del rendimiento

El pilar de la eficiencia del rendimiento se centra en el uso eficiente de los recursos informáticos y de TI. Los temas clave incluyen la selección de los tipos y tamaños de recursos adecuados en función de los requisitos de la carga de trabajo, la supervisión del rendimiento y la toma de decisiones informadas para mantener la eficiencia a medida que evolucionan las necesidades empresariales.

#### Seguridad

El pilar de la seguridad se centra en la protección de la información y los sistemas. Los temas clave incluyen la confidencialidad e integridad de los datos, la identificación y gestión de quién puede hacer qué con la gestión de privilegios, la protección de los sistemas y el establecimiento de controles para detectar eventos de seguridad.

### Amazon Route 53

Amazon Route 53 es un servicio web de Sistema de Nombres de Dominio (DNS) en el Cloud altamente disponible y escalable. Está diseñado para ofrecer a desarrolladores y empresas una forma extremadamente fiable y rentable de dirigir a los usuarios finales a las aplicaciones de Internet, traduciendo nombres como www.example.com en direcciones IP numéricas como 192.0.2.1, que los ordenadores utilizan para conectarse entre sí.

Si tu aplicación está alojada en varias regiones de AWS, puedes utilizar la política de enrutamiento basado en la latencia para mejorar el rendimiento de tus usuarios, sirviendo sus solicitudes desde la región de AWS que proporcione la latencia más baja. Para utilizar el enrutamiento basado en la latencia, crea registros de latencia para tus recursos en varias regiones de AWS. Cuando Amazon Route 53 recibe una consulta DNS para tu dominio o subdominio (ejemplo.com o acme.ejemplo.com), determina para qué regiones de AWS has creado registros de latencia, determina qué región proporciona al usuario la latencia más baja y, a continuación, selecciona un registro de latencia para esa región. Amazon Route 53 responde con el valor del registro seleccionado, como la dirección IP de un servidor web.

Visión general de la política de enrutamiento de Amazon Route 53:

![img](img/pol-enru.jpg)

### Amazon CloudFront con Amazon Route 53

AWS aloja los servicios Amazon CloudFront y Amazon Route 53 en una red distribuida de servidores proxy en centros de datos de todo el mundo denominados ubicaciones de borde (Edge Locations). El uso de la red global de Amazon de ubicaciones de borde para la entrega de aplicaciones y el servicio DNS desempeña un papel importante en la construcción de una defensa integral contra ataques DDoS para tus aplicaciones web dinámicas.

### Amazon Relational Database Service (Amazon RDS)

Facilita la configuración, el funcionamiento y el escalado de una base de datos relacional en el Cloud. Proporciona una capacidad rentable y redimensionable, al tiempo que automatiza tareas de administración que llevan mucho tiempo, como el aprovisionamiento de hardware, la configuración de la base de datos, la aplicación de parches y las copias de seguridad.

Amazon RDS proporciona una selección de tipos de instancia optimizados para adaptarse a diferentes casos de uso de bases de datos relacionales. Los tipos de instancia comprenden distintas combinaciones de CPU, memoria, almacenamiento y capacidad de red, y te ofrecen la flexibilidad de elegir la combinación adecuada de recursos para tu base de datos, a fin de optimizarla para tu caso de uso seleccionando el tipo y tamaño de instancia correctos.

Como las instancias RDS están optimizadas para la memoria, el rendimiento o la E/S, por lo tanto, el rendimiento de la instancia de Amazon Relational Database Service (Amazon RDS) administrada por AWS es mejor que el de una instancia de base de datos administrada por el cliente.

### 6 Ventajas de servicios en la nube

![ventajas_cloud](img/ventajas.jpeg)

### Cloud caracteristicas

**Agilidad**
En el mundo de la computación en el Cloud, "Agilidad" se refiere a la capacidad de desarrollar, probar y lanzar rápidamente aplicaciones de software que impulsen el crecimiento empresarial Otra forma de explicar la "Agilidad": AWS proporciona una infraestructura global masiva en el Cloud que te permite innovar, experimentar e iterar rápidamente. En lugar de esperar semanas o meses por el hardware, puedes desplegar instantáneamente nuevas aplicaciones. Esta capacidad se llama agilidad.

**Elasticidad**
Esto se refiere a la capacidad de adquirir recursos según los necesites y liberarlos cuando ya no sean necesarios, se denomina Elasticidad del Cloud.

**Fiabilidad**
Se refiere a la capacidad de un sistema para recuperarse de las interrupciones de la infraestructura o de los servicios, mediante la adquisición dinámica de recursos informáticos para satisfacer la demanda y mitigar las interrupciones.

**Escalabilidad**
La escalabilidad es la medida de la capacidad de un sistema de crecer para adaptarse a un aumento de la demanda, o reducirse ante una demanda decreciente.

### Servicios Cloud

Una de las principales ventajas de los servicios en el Cloud es la capacidad que te ofrece de optimizar los costes para adaptarlos a tus necesidades, incluso cuando éstas cambian. Los servicios de AWS no tienen dependencias complejas ni requisitos de licencia, por lo que puedes obtener exactamente lo que necesitas para crear soluciones innovadoras y rentables utilizando la tecnología más reciente.

Hay tres factores fundamentales del coste con AWS: computación, almacenamiento y transferencia de datos salientes. Estas características varían algo, dependiendo del producto de AWS y del modelo de precios que elijas. Los datos salientes a Internet desde todas las regiones de AWS se facturan a tarifas de transferencia de datos escalonadas específicas de cada región. La transferencia de datos entrantes a todas las regiones de AWS desde Internet es gratuita.

### Grupo de seguridad

Un grupo de seguridad actúa como un firewall virtual para tus instancias EC2 para controlar el tráfico entrante y saliente. Las reglas de entrada controlan el tráfico entrante hacia tu instancia, y las reglas de salida controlan el tráfico saliente desde tu instancia. Los grupos de seguridad sólo tienen reglas de "permitir". No puedes utilizar los grupos de seguridad para bloquear usuarios de determinadas geografías.
Visión general del grupo de seguridad:
![grupo_seguridad](img/grupos.jpeg)

El grupo de seguridad actúa como firewall a nivel de instancia, mientras que la lista de control de acceso a la red (NACL) actúa como firewall a nivel de subred

### lista de control de acceso a la red (NACL)

Visión general de la lista de control de acceso a la red (NACL):
![nacl](img/nacl.jpeg)

### AWS CloudHSM

AWS CloudHSM es un módulo de seguridad de hardware (HSM) basado en el Cloud que te permite generar y utilizar fácilmente tus claves de cifrado en el Cloud de AWS. Con CloudHSM, puedes gestionar tus claves de cifrado utilizando HSM validados por FIPS 140-2 Nivel 3. Se trata de un servicio totalmente gestionado que automatiza por ti las tareas administrativas que requieren mucho tiempo, como el aprovisionamiento de hardware, la aplicación de parches de software, la alta disponibilidad y las copias de seguridad. CloudHSM no puede utilizarse para evitar ataques distribuidos de denegación de servicio (DDoS).

### AWS CloudFormation

AWS CloudFormation te permite utilizar lenguajes de programación o un simple archivo de texto para modelar y aprovisionar, de forma automatizada y segura, todos los recursos necesarios para tus aplicaciones en todas las regiones y cuentas. Piensa en infraestructura como código; piensa en CloudFormation. CloudFormation no proporciona el estado general de disponibilidad de los servicios de AWS para todas las regiones.

### AWS Health Dashboard

Estado del servicio es el único lugar para conocer la disponibilidad y el funcionamiento de los servicios de AWS. Puedes ver el estado general de los servicios de AWS, y puedes iniciar sesión para ver comunicaciones personalizadas sobre tu cuenta u organización de AWS en particular.

### AWS Health Dashboard Estado de su cuenta

AWS Health Dashboard - Estado de su cuenta proporciona alertas y orientación para remediarlo cuando AWS experimenta eventos que pueden afectarte.

AWS Health Dashboard - Estado de su cuenta, las alertas se activan con los cambios en la salud de tus recursos de AWS, proporcionándote visibilidad de los eventos, y orientación para ayudar a diagnosticar y resolver rápidamente los problemas.

Alerta de examen:

Mientras que el AWS Health Dashboard - Estado del servicio muestra el estado general de los servicios de AWS, el AWS Health Dashboard - Estado de su cuenta te ofrece una visión personalizada del rendimiento y la disponibilidad de los servicios de AWS subyacentes a tus recursos de AWS.

### AWS Basic Support

El plan AWS Basic Support sólo proporciona acceso a lo siguiente:

Servicio de atención al cliente y comunidades - Acceso 24x7 al servicio de atención al cliente, documentación, Whitepapers y foros de soporte. AWS Trusted Advisor - Acceso a las comprobaciones básicas de Trusted Advisor y orientación para aprovisionar tus recursos siguiendo las mejores prácticas para aumentar el rendimiento y mejorar la seguridad. Salud de AWS - El panel de salud de tu cuenta : Una vista personalizada de la salud de tus servicios AWS, y alertas cuando tus recursos se vean afectados.

### AWS Developer Support

Deberías utilizar el plan AWS Developer Support si estás probando o realizando desarrollos iniciales en AWS y deseas tener la posibilidad de obtener soporte técnico por correo electrónico durante el horario laboral, así como orientación general sobre arquitectura a medida que construyes y pruebas. Este plan proporciona acceso sólo a las comprobaciones básicas de Trusted Advisor de la Cuota de Servicio y a las comprobaciones básicas de Seguridad.

### AWS Enterprise Support

El plan AWS Enterprise Support proporciona a los clientes un servicio similar al de un conserje, en el que el objetivo principal es ayudar al cliente a conseguir sus resultados y encontrar el éxito en el Cloud. Con AWS Enterprise Support, obtienes soporte técnico 24x7 de ingenieros de alta calidad, herramientas y tecnología para administrar automáticamente el estado de tu entorno, orientación arquitectónica consultiva y un administrador técnico de cuentas (TAM) designado para coordinar el acceso a programas proactivos/preventivos y a expertos en la materia de AWS. También obtienes acceso completo a las comprobaciones de buenas prácticas de AWS Trusted Advisor.

### AWS Business Support

Deberías utilizar el plan AWS Business Support si tienes cargas de trabajo de producción en AWS y quieres acceso telefónico, por correo electrónico y por chat 24x7 a soporte técnico y orientación sobre arquitectura en el contexto de tus casos de uso específicos. También obtienes acceso completo a las comprobaciones de buenas prácticas de AWS Trusted Advisor.

### AWS Enterprise On-Ramp Support

Deberías utilizar el plan AWS Enterprise On-Ramp Support si tienes cargas de trabajo de producción/negocio críticas en AWS y quieres acceso 24x7 a soporte técnico y necesitas orientación experta para crecer y optimizar en el Cloud. Obtendrás acceso completo a las comprobaciones de buenas prácticas de AWS Trusted Advisor.

### Socio consultor de APN

La red de socios de AWS (APN) es el programa global de socios para empresas de tecnología y consultoría que aprovechan Amazon Web Services (AWS) para crear soluciones y servicios para los clientes.

Los socios consultores de APN son empresas de servicios profesionales que ayudan a clientes de todo tipo y tamaño a diseñar, arquitecturar, construir, migrar y administrar sus cargas de trabajo y aplicaciones en AWS, acelerando su migración al Cloud de AWS.

### Socio tecnológico de APN

Los socios tecnológicos de APN proporcionan hardware, servicios de conectividad o soluciones de software que se alojan en el Cloud de AWS o se integran con ella. Los socios tecnológicos de APN no pueden ayudar a migrar a AWS ni a administrar aplicaciones en el Cloud de AWS.

### AWS Compute Optimizer

Te ayuda a identificar las configuraciones óptimas de los recursos de AWS, como los tipos de instancias de Amazon EC2, las configuraciones de volúmenes de Amazon EBS y los tamaños de memoria de las funciones de AWS Lambda, utilizando el aprendizaje automático para analizar las métricas de utilización históricas. AWS Compute Optimizer ofrece recomendaciones para tipos seleccionados de instancias EC2, grupos EC2 Auto Scaling, volúmenes Amazon EBS y funciones AWS Lambda.

AWS Compute Optimizer calcula una puntuación de riesgo de rendimiento individual para cada dimensión de recurso de la instancia recomendada, incluyendo CPU, memoria, rendimiento de EBS, IOPS de EBS, rendimiento de disco, rendimiento de disco, rendimiento de red y paquetes de red por segundo (PPS).

AWS Compute Optimizer proporciona recomendaciones de tipo y tamaño de instancia EC2 para los grupos de Autoescalado EC2 con un tamaño de grupo fijo, lo que significa que el deseado, el mínimo y el máximo se establecen en el mismo valor y no tienen ninguna política de escalado adjunta.

AWS Compute Optimizer admite recomendaciones de IOPS y rendimiento para volúmenes de propósito general (SSD) (gp3) y recomendaciones de IOPS para volúmenes de IOPS provisionados (io1 e io2).

AWS Compute Optimizer te ayuda a optimizar dos categorías de funciones Lambda. La primera categoría incluye funciones Lambda que pueden estar sobreaprovisionadas en tamaños de memoria. La segunda categoría incluye funciones Lambda de cálculo intensivo que pueden beneficiarse de potencia de CPU adicional.

### Pruebas de penetración

Los clientes de AWS pueden llevar a cabo evaluaciones de seguridad o pruebas de penetración contra su infraestructura de AWS sin aprobación previa para unos pocos servicios comunes de AWS. Los clientes no pueden realizar evaluaciones de seguridad de la infraestructura de AWS, ni de los propios servicios de AWS.

### Prueba de estrés de la red

AWS considera "prueba de estrés de red" cuando una prueba envía un gran volumen de tráfico legítimo o de prueba a una aplicación de destino específica. Se espera que el endpoint y la infraestructura sean capaces de manejar este tráfico.

### Centro de conocimiento de AWS (AWS re:post)

El centro de conocimiento de AWS contiene las preguntas y solicitudes más frecuentes y comunes y las soluciones que AWS proporciona para las mismas. Este debería ser el punto de partida para buscar una solución o resolver un problema con los servicios de AWS.


## Tecnologia

### Amazon Simple Queue Service (SQS)

Amazon Simple Queue Service (SQS) es un servicio de cola de mensajes totalmente administrado que te permite desacoplar y escalar microservicios, sistemas distribuidos y aplicaciones sin servidor. Utilizando SQS, puedes enviar, almacenar y recibir mensajes entre componentes de software a cualquier volumen, sin perder mensajes ni requerir que otros servicios estén disponibles.

### Amazon Simple Notification Service (SNS)

Amazon Simple Notification Service (SNS) es un servicio de mensajería pub/sub de alta disponibilidad, duradero, seguro y totalmente administrado que te permite desacoplar microservicios, sistemas distribuidos y aplicaciones sin servidor. Utilizando los temas de Amazon SNS, tus sistemas publicadores pueden enviar mensajes a un gran número de puntos finales suscriptores para procesarlos en paralelo, incluidas las colas de Amazon SQS, las funciones de AWS Lambda y los webhooks HTTP/S. Además, SNS puede utilizarse para distribuir notificaciones a los usuarios finales mediante push móvil, SMS y correo electrónico.

### Arquitectura SNS SQS

![sqs_sns](img/sns_sqs.png)

### Amazon Elastic Compute Cloud (Amazon EC2)

Amazon Elastic Compute Cloud (Amazon EC2) es un servicio web que proporciona capacidad informática segura y redimensionable en el Cloud con soporte para facturación por segundos. Es la forma más sencilla de aprovisionar servidores en el Cloud de AWS y acceder al SO subyacente. EC2 no puede utilizarse para desacoplar componentes de una aplicación basada en microservicios.

### AWS Lambda

AWS Lambda te permite ejecutar código sin aprovisionar ni administrar servidores. Sólo pagas por el tiempo de cómputo que consumes. Lambda no puede utilizarse para desacoplar componentes de una aplicación basada en microservicios.

### AWS Step Functions

AWS Step Functions te permite coordinar varios servicios de AWS en flujos de trabajo sin servidor. Puedes diseñar y ejecutar flujos de trabajo que unan servicios como AWS Lambda, AWS Glue y Amazon SageMaker. AWS Step Functions no puede utilizarse para desacoplar componentes de una aplicación basada en microservicios.

### Amazon ElastiCache

Amazon ElastiCache te permite configurar, ejecutar y escalar sin problemas almacenes de datos en memoria populares compatibles con código abierto en el Cloud. Crea aplicaciones de uso intensivo de datos o aumenta el rendimiento de tus bases de datos existentes recuperando datos de almacenes de datos en memoria de alto rendimiento y baja latencia. Amazon ElastiCache es una opción popular para casos de uso en tiempo real como almacenamiento en caché, almacenes de sesión, juegos, servicios geoespaciales, análisis en tiempo real y colas. ElastiCache no puede utilizarse para el procesamiento analítico en línea.

### Amazon DynamoDB

Amazon DynamoDB es una base de datos NoSQL de valores clave, sin servidor y totalmente administrada, diseñada para ejecutar aplicaciones de alto rendimiento a cualquier escala. DynamoDB ofrece seguridad integrada, copias de seguridad continuas, replicación multirregión automatizada, almacenamiento en caché en memoria y herramientas de exportación de datos.

Las tablas globales de DynamoDB replican los datos automáticamente en las regiones de AWS que elijas y escalan automáticamente la capacidad para adaptarse a tus cargas de trabajo. Con las tablas globales, tus aplicaciones distribuidas globalmente pueden acceder a los datos localmente en las regiones seleccionadas para obtener un rendimiento de lectura y escritura de milisegundos de un solo dígito. DynamoDB ofrece el soporte activo-activo entre regiones que necesita la empresa.

### Amazon DynamoDB con DynamoDB Accelerator

DynamoDB Accelerator(DAX) es una caché en memoria que proporciona un rendimiento de lectura rápido para tus tablas a escala, permitiéndote utilizar una caché en memoria totalmente gestionada. Con DAX, puedes mejorar el rendimiento de lectura de tus tablas DynamoDB hasta 10 veces, haciendo que el tiempo necesario para las lecturas pase de milisegundos a microsegundos, incluso con millones de solicitudes por segundo. DAX no ofrece configuración activa-activa entre Regiones.

### Amazon Aurora

Amazon Aurora (Aurora) es un motor de base de datos relacional totalmente gestionado que es compatible con MySQL y PostgreSQL. Con algunas cargas de trabajo, Aurora puede ofrecer hasta cinco veces el rendimiento de MySQL y hasta tres veces el rendimiento de PostgreSQL sin necesidad de realizar cambios en la mayoría de tus aplicaciones actuales. En un Cluster multimaestro, todas las instancias de la BD tienen capacidad de lectura/escritura. Aurora no es una base de datos NoSQL, por lo que esta opción es incorrecta.

Amazon Aurora es una base de datos relacional compatible con MySQL y PostgreSQL creada paral Cloud. Amazon Aurora está totalmente administrado por Amazon Relational Database Service (RDS), que automatiza las tareas de administración que llevan mucho tiempo, como el aprovisionamiento de hardware, la configuración de la base de datos, la aplicación de parches y las copias de seguridad. El equipo de productos de AWS se encarga de aplicar parches al sistema operativo subyacente de AWS Aurora.

### Amazon Relational Database Service(Amazon RDS)

Amazon Relational Database Service (Amazon RDS) facilita la configuración, el funcionamiento y el escalado de una base de datos relacional en el Cloud. Proporciona una capacidad rentable y redimensionable, a la vez que automatiza tareas de administración que consumen mucho tiempo, como el aprovisionamiento de hardware, la configuración de la base de datos, la aplicación de parches y las copias de seguridad. Te libera para que puedas centrarte en tus aplicaciones y darles el rendimiento rápido, la alta disponibilidad, la seguridad y la compatibilidad que necesitan.

### Amazon Simple Storage Service (Amazon S3)

Amazon Simple Storage Service (Amazon S3) es un servicio de almacenamiento de objetos que ofrece escalabilidad, disponibilidad de datos, seguridad y rendimiento líderes en el sector.

### Amazon Elastic File System (Amazon EFS)

Amazon Elastic File System (Amazon EFS) proporciona un sistema de archivos NFS elástico, sencillo, escalable y totalmente administrado para su uso con los servicios en el Cloud de AWS y los recursos locales. Está diseñado para escalar bajo demanda a petabytes sin interrumpir las aplicaciones, creciendo y reduciéndose automáticamente a medida que añades y eliminas archivos, eliminando la necesidad de aprovisionar y administrar la capacidad para acomodar el crecimiento.

Pagarás una tarifa cada vez que leas o escribas datos almacenados en la clase de almacenamiento Amazon Elastic File System (Amazon EFS) - Infrequent Access

La clase de almacenamiento Amazon Elastic File System (Amazon EFS) - Acceso poco frecuente está optimizada en cuanto a costes para los archivos a los que se accede con menos frecuencia. Los datos almacenados en la clase de almacenamiento Amazon Elastic File System (Amazon EFS) - Acceso poco frecuente cuestan menos que la estándar y pagarás una cuota cada vez que leas o escribas en un archivo.

### Versionado de Amazon S3

El versionado es un medio de mantener múltiples variantes de un objeto en el mismo bucket. Puedes utilizar el versionado para conservar, recuperar y restaurar cada versión de cada objeto almacenado en tu bucket de Amazon S3. Con el versionado, puedes recuperarte fácilmente tanto de acciones no intencionadas del usuario como de fallos de la aplicación.

Los buckets con versiones habilitadas te permiten recuperar objetos en caso de borrado o sobrescritura accidental. Por ejemplo: si borras un objeto, en lugar de eliminarlo permanentemente, Amazon S3 inserta un marcador de borrado, que se convierte en la versión actual del objeto.

### S3 Standard-Infrequent Access (S3 Standard-IA)

Amazon S3 Standard-Infrequent Access (S3 Standard-IA) es para datos a los que se accede con menos frecuencia, pero que requieren un acceso rápido cuando se necesitan. S3 Standard-Infrequent Access (S3 Standard-IA) ofrece la alta durabilidad, el alto rendimiento y la baja latencia de S3 Standard, con un bajo precio por GB de almacenamiento y por GB de recuperación. Esta combinación de bajo coste y alto rendimiento hace que S3 Standard-Infrequent Access (S3 Standard-IA) sea ideal para almacenamiento a largo plazo, copias de seguridad y como almacén de datos para archivos de recuperación ante desastres.

### Amazon S3 Standard

El S3 Standard de Amazon ofrece almacenamiento de objetos de alta durabilidad, disponibilidad y rendimiento para datos a los que se accede con frecuencia.

### Amazon S3 Intelligent-Tiering (S3 Inteligente)

La clase de almacenamiento Amazon S3 Intelligent-Tiering está diseñada para optimizar los costes moviendo automáticamente los datos al nivel de acceso más rentable, sin impacto en el rendimiento ni sobrecarga operativa. Funciona almacenando objetos en dos niveles de acceso: un nivel optimizado para el acceso frecuente y otro nivel de menor coste optimizado para el acceso infrecuente.

### Amazon S3 Glacier

Amazon S3 Glacier es una clase de almacenamiento en el Cloud de Amazon S3 segura, duradera y de coste extremadamente bajo para archivar datos y realizar copias de seguridad a largo plazo. Está diseñado para ofrecer una durabilidad del 99,999999999% y proporcionar capacidades integrales de seguridad y normativa que pueden ayudar a cumplir incluso los requisitos normativos más estrictos. S3 Glacier no admite la recuperación rápida de datos.

### Amazon S3 Glacier Deep Archive

Amazon S3 Glacier Deep Archive es la clase de almacenamiento de menor coste de Amazon S3 y soporta la retención a largo plazo y la preservación digital de datos a los que se puede acceder una o dos veces al año. Está diseñado para clientes -especialmente los de sectores muy regulados, como los servicios financieros, la sanidad y el sector público- que conservan conjuntos de datos durante 7-10 años o más para cumplir los requisitos normativos. S3 Glacier Deep Archive también puede utilizarse para casos de uso de backup y recuperación de desastres. Tiene un tiempo de recuperación (latencia del primer byte) de 12 a 48 horas.

### Amazon EMR

Amazon EMR es la plataforma de big data en el Cloud líder del sector para procesar grandes cantidades de datos utilizando herramientas de código abierto como Hadoop, Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi y Presto. Amazon EMR puede utilizarse para aprovisionar recursos para ejecutar cargas de trabajo de big data en clústeres Hadoop. Amazon EMR aprovisiona instancias EC2 para administrar su carga de trabajo. Amazon EMR no es un servicio sin servidor.

### AWS Elastic Beanstalk

AWS Elastic Beanstalk es un servicio fácil de usar para implementar y escalar aplicaciones y servicios web. Sólo tienes que subir tu código y Elastic Beanstalk se encarga automáticamente del despliegue, desde el aprovisionamiento de capacidad, el equilibrio de carga y el autoescalado hasta la monitorización del estado de la aplicación. AWS Elastic Beanstalk aprovisiona servidores, por lo que no es un servicio sin servidor.

### Amazon Kendra

Amazon Kendra es un servicio de búsqueda inteligente impulsado por aprendizaje automático. Kendra reimagina la búsqueda empresarial para tus sitios web y aplicaciones, de forma que tus empleados y clientes puedan encontrar fácilmente el contenido que buscan, incluso cuando está disperso por múltiples ubicaciones y repositorios de contenido dentro de tu organización.

Con Amazon Kendra, puedes dejar de buscar entre montones de datos no estructurados y descubrir las respuestas adecuadas a tus preguntas, cuando las necesites. Amazon Kendra es un servicio totalmente administrado, por lo que no hay servidores que aprovisionar ni modelos de aprendizaje automático que crear, entrenar o implementar. Amazon Kendra admite datos no estructurados y semiestructurados en formatos .html, MS Office (.doc, .ppt), PDF y texto.

### Amazon Transcribe

Puedes utilizar Amazon Transcribe para añadir capacidad de conversión de habla a texto a tus aplicaciones. Amazon Transcribe utiliza un proceso de Deep Learning llamado reconocimiento automático del habla (ASR) para convertir el habla en texto con rapidez y precisión. Amazon Transcribe puede utilizarse para transcribir llamadas de atención al cliente, automatizar subtítulos y subtitulado, y generar metadatos para activos multimedia.

Casos prácticos de Amazon Transcribe:
![amazon_transcrbe](img/amazon_transcribe.jpeg)

### Amazon Polly

Puedes utilizar Amazon Polly para convertir texto en habla realista, lo que te permitirá crear aplicaciones que hablen. El servicio de conversión de texto en habla (TTS) de Polly utiliza tecnologías avanzadas de Deep Learning para sintetizar el habla humana con un sonido natural.

Beneficios de Amazon Polly:

![polly](img/polly.jpeg)

### Amazon Rekognition

No puedes utilizar Amazon Rekognition para cambiar el tamaño de las imágenes y crear miniaturas.

Con Amazon Rekognition, puedes identificar objetos, personas, texto, escenas y actividades en imágenes y vídeos, así como detectar cualquier contenido inapropiado. Amazon Rekognition también proporciona capacidades de análisis facial y búsqueda facial de gran precisión que puedes utilizar para detectar, analizar y comparar rostros para una amplia variedad de casos de uso de verificación de usuarios, recuento de personas y seguridad pública.

Casos de uso de Amazon Rekognition:
![rekog_cu](img/cu_rekog.jpg)

### AWS X-Ray

Puedes utilizar AWS X-Ray para analizar y depurar aplicaciones distribuidas y sin servidor, como las creadas con una arquitectura de microservicios. Con X-Ray, puedes comprender el rendimiento de tu aplicación y sus servicios subyacentes para identificar y solucionar la causa raíz de los problemas y errores de rendimiento.

Cómo funciona AWS X-Ray:
![xray](img/xray.png)

### Amazon FSx para Windows File Server

Amazon FSx para Windows File Server proporciona almacenamiento de archivos totalmente gestionado, altamente fiable y escalable, accesible a través del protocolo estándar del sector Service Message Block (SMB). Está basado en Windows Server y ofrece una amplia gama de funciones administrativas, como cuotas de usuario, restauración de archivos de usuario final e integración con Microsoft Active Directory (AD).

Para soportar un amplio espectro de cargas de trabajo, Amazon FSx proporciona altos niveles de rendimiento, IOPS y latencias constantes por debajo del milisegundo. Se puede acceder a Amazon FSx desde instancias y dispositivos informáticos Windows, Linux y macOS.

Para aplicaciones basadas en Windows, Amazon FSx proporciona servidores de archivos Windows totalmente administrados con características y rendimiento optimizados para cargas de trabajo de aplicaciones críticas para el negocio "lift-and-shift", incluidos directorios personales (recursos compartidos de usuario), flujos de trabajo multimedia y aplicaciones ERP. Es accesible desde instancias Windows y Linux a través del protocolo SMB.

### Amazon EventBridge

Amazon EventBridge es un servicio que proporciona acceso en tiempo real a los cambios en los datos de los servicios de AWS, tus propias aplicaciones y aplicaciones de software como servicio (SaaS) sin necesidad de escribir código. El Programador de Amazon EventBridge es un programador de tareas sin servidor que simplifica la creación, ejecución y administración de millones de programaciones a través de los servicios de AWS sin aprovisionar ni administrar la infraestructura subyacente.

### Amazon Athena

Amazon Athena es un servicio de consultas interactivas que facilita el análisis de datos en Amazon S3 utilizando SQL estándar. Amazon Athena no tiene servidor, por lo que no hay infraestructura que administrar, y sólo pagas por las consultas que ejecutas.

### AWS Global Accelerator

AWS Global Accelerator es un servicio que mejora la disponibilidad y el rendimiento de tus aplicaciones con usuarios locales o globales. Proporciona direcciones IP estáticas que actúan como punto de entrada fijo a los puntos finales de tus aplicaciones en una o varias regiones de AWS, como tus balanceadores de carga de aplicaciones, balanceadores de carga de red o instancias de Amazon EC2. El Acelerador Global de AWS utiliza la red global de AWS para optimizar la ruta de tus usuarios a tus aplicaciones, mejorando el rendimiento de tu tráfico hasta en un 60%.

AWS Global Accelerator mejora el rendimiento de una amplia gama de aplicaciones a través de TCP o UDP mediante la transferencia de paquetes en el borde a aplicaciones que se ejecutan en una o más regiones de AWS. El Acelerador Global de AWS es adecuado para casos de uso no HTTP, como juegos (UDP), IoT (MQTT) o Voz sobre IP, así como para casos de uso HTTP que requieran específicamente direcciones IP estáticas o una conmutación por error regional rápida y determinista.

### Usuario Root

La dirección de correo electrónico y la contraseña utilizadas para registrarse en los servicios de AWS son las credenciales de la cuenta de usuario raíz de AWS. La cuenta de usuario raíz, por tanto, tiene permisos completos sobre todos los recursos de AWS bajo esa cuenta. No es posible restringir el acceso a la cuenta de usuario raíz. Como práctica recomendada, debe establecerse la autenticación multifactor (MFA) en la cuenta de usuario raíz. La contraseña de la cuenta de usuario raíz puede cambiarse tras la creación de la cuenta. Para todos los empleados que realicen diversas tareas administrativas, crea cuentas de usuario individuales utilizando AWS IAM, y concede los permisos administrativos necesarios.

### Host dedicado

Los hosts dedicados de Amazon EC2 te permiten utilizar tus licencias de software elegibles de proveedores como Microsoft y Oracle en Amazon EC2. Un host dedicado de Amazon EC2 es un servidor físico totalmente dedicado para tu uso, por lo que puedes ayudar a cumplir los requisitos corporativos.

### Instancia dedicada

Una instancia dedicada es una instancia de Amazon EC2 que se ejecuta en Virtual Private Cloud (VPC) en hardware dedicado a un solo cliente. Las instancias Dedicadas que pertenecen a diferentes cuentas de AWS están físicamente aisladas a nivel de hardware. Sin embargo, las instancias Dedicadas pueden compartir hardware con otras instancias de la misma cuenta de AWS que no sean instancias Dedicadas. No puedes utilizar instancias Dedicadas para utilizar licencias de software vinculadas al servidor.

### Instancia reservada (RI)

Una instancia reservada te proporciona un ahorro significativo (hasta el 75%) en tus costes de Amazon EC2 en comparación con los precios de las instancias bajo demanda. Una istancia reservada no es una instancia física, sino un descuento de facturación aplicado al uso de una instancia bajo demanda en tu cuenta. Puedes adquirir una instancia reservada (RI) para un compromiso de uno o tres años, siendo el compromiso de tres años el que ofrece un mayor descuento. No puedes utilizar una instancia reservada (RI) para utilizar licencias de software vinculadas a un servidor.

### Instancia bajo demanda

Una Instancia bajo demanda es una instancia que utilizas bajo demanda. Tienes pleno control sobre su ciclo de vida: tú decides cuándo lanzarla, detenerla, hibernarla, iniciarla, reiniciarla o terminarla. No es necesario un compromiso a largo plazo cuando adquieres instancias bajo demanda. No hay que pagar nada por adelantado y sólo pagas por los segundos que se ejecutan tus instancias bajo demanda. El precio por segundo de ejecución de una instancia bajo demanda es fijo. Las instancias bajo demanda no se pueden interrumpir. No puedes utilizar instancias bajo demanda para utilizar licencias de software vinculadas a servidor.

### Instancias SPOT

Las instancias spot de Amazon EC2 te permiten aprovechar la capacidad EC2 no utilizada en el Cloud de AWS. Las instancias spot están disponibles con un descuento de hasta el 90% en comparación con los precios de las instancias bajo demanda. Puedes utilizar instancias spot para diversas aplicaciones sin estado, tolerantes a fallos o flexibles, como big data, cargas de trabajo en contenedores, CI/CD, servidores web, informática de alto rendimiento (HPC) y otras cargas de trabajo de prueba y desarrollo.

### Amazon Redshift

Amazon Redshift es un producto de almacén de datos en el Cloud a escala de petabytes totalmente administrado, diseñado para el almacenamiento y análisis de conjuntos de datos a gran escala.

### AWS Glue

AWS Glue es un servicio de extracción, transformación y carga (ETL) totalmente administrado que facilita a los clientes la preparación y carga de sus datos para el análisis.

### Amazon Macie

Amazon Macie es un servicio de seguridad y privacidad de datos totalmente gestionado que utiliza el aprendizaje automático y la concordancia de patrones para descubrir y proteger tus datos confidenciales en AWS. Macie proporciona automáticamente un inventario de buckets de Amazon S3 que incluye una lista de buckets sin cifrar, buckets de acceso público y buckets compartidos con cuentas de AWS ajenas a las que hayas definido en AWS Organizations. A continuación, Macie aplica técnicas de aprendizaje automático y concordancia de patrones a los buckets que selecciones para identificar y alertarte sobre datos sensibles, como la información personal identificable (PII).

### AWS Secrets Manager

AWS Secrets Manager te ayuda a proteger los secretos necesarios para acceder a tus aplicaciones, servicios y recursos informáticos. El servicio te permite rotar, administrar y recuperar fácilmente credenciales de bases de datos, claves API y otros secretos a lo largo de su ciclo de vida. Los usuarios y las aplicaciones recuperan los secretos con una llamada a las API del Gestor de Secretos, eliminando la necesidad de codificar información sensible en texto plano. No puede utilizarse para descubrir y proteger tus datos sensibles en AWS.

### Almacén de instancias

Un almacén de instancia proporciona almacenamiento temporal a nivel de bloque para tu instancia. Este almacenamiento se encuentra en discos conectados físicamente al ordenador anfitrión. Es una buena opción cuando necesitas un almacenamiento con una latencia muy baja, pero no necesitas que los datos persistan cuando finalice la instancia o puedes aprovechar las arquitecturas tolerantes a fallos. Para este caso de uso, la propia aplicación de cálculo tiene una arquitectura tolerante a fallos, por lo que puede gestionar automáticamente cualquier fallo de los volúmenes del almacén de instancias de EC2

![inst_alm](img/inst_alm.jpeg)

### AWS Storage Gateway

AWS Storage Gateway es un servicio de almacenamiento en el Cloud híbrido que conecta tus entornos locales existentes con el Cloud de AWS. Los clientes utilizan AWS Storage Gateway para simplificar la gestión del almacenamiento y reducir los costes en casos clave de uso del almacenamiento en el Cloud híbrido.

El servicio AWS Storage Gateway proporciona tres tipos diferentes de puertas de enlace (Tape Gateway, File Gateway y Volume Gateway) que conectan sin problemas las aplicaciones locales con el almacenamiento en el Cloud, almacenando los datos en caché local para un acceso de baja latencia.

### AWS Database Migration Service (AWS DMS)

AWS Database Migration Service (AWS DMS) te ayuda a migrar bases de datos a AWS de forma rápida y segura. La base de datos de origen permanece totalmente operativa durante la migración, minimizando el tiempo de inactividad de las aplicaciones que dependen de la base de datos. El Servicio de Migración de Bases de Datos de AWS (AWS DMS) puede migrar tus datos desde y hacia las bases de datos comerciales y de código abierto más utilizadas.

### Enrutamiento ponderado

Amazon Route 53 es un servicio web de Sistema de Nombres de Dominio (DNS) en el Cloud altamente disponible y escalable. Está diseñado para ofrecer a desarrolladores y empresas una forma extremadamente fiable y rentable de dirigir a los usuarios finales a las aplicaciones de Internet, traduciendo nombres como www.example.com en direcciones IP numéricas como 192.0.2.1, que los ordenadores utilizan para conectarse entre sí.

El enrutamiento ponderado te permite asociar varios recursos a un único nombre de dominio (ejemplo.com) o subdominio (acme.ejemplo.com) y elegir cuánto tráfico se enruta a cada recurso. Esto puede ser útil para diversos fines, como equilibrar la carga y probar nuevas versiones de software. Para configurar el enrutamiento ponderado, crea registros que tengan el mismo nombre y tipo para cada uno de tus recursos. Asigna a cada registro un peso relativo que se corresponda con la cantidad de tráfico que deseas enviar a cada recurso. Amazon Route 53 envía tráfico a un recurso en función del peso que asignes al registro como proporción del peso total de todos los registros del grupo.

![enrutpol](img/enrutpol.jpeg)

### AWS Compute Optimizer

AWS Compute Optimizer recomienda los recursos de AWS óptimos para tus cargas de trabajo con el fin de reducir costes y mejorar el rendimiento, utilizando el aprendizaje automático para analizar las métricas de utilización históricas. Un aprovisionamiento excesivo de recursos puede generar costes de infraestructura innecesarios, y un aprovisionamiento insuficiente puede dar lugar a un rendimiento deficiente de las aplicaciones. Compute Optimizer te ayuda a elegir configuraciones óptimas para tres tipos de recursos de AWS: instancias de Amazon EC2, volúmenes de Amazon EBS y funciones de AWS Lambda, basándose en tus datos de utilización.

Compute Optimizer recomienda hasta 3 opciones de entre más de 140 tipos de instancias EC2, así como una amplia gama de opciones de configuración de volúmenes EBS y funciones Lambda, para dimensionar correctamente tus cargas de trabajo. Compute Optimizer también proyecta cuál habría sido la utilización de la CPU, la utilización de la memoria y el tiempo de ejecución de tu carga de trabajo con las opciones de recursos de AWS recomendadas. Esto te ayuda a comprender cómo habría funcionado tu carga de trabajo con las opciones recomendadas antes de poner en práctica las recomendaciones.

Cómo funciona AWS Compute Optimizer:
![comp](img/compute_opt.jpeg)

### Region

AWS tiene el concepto de región, que es una ubicación física en todo el mundo donde AWS agrupa sus centros de datos. AWS denomina zona de disponibilidad (AZ) a cada grupo de centros de datos lógicos. Cada región de AWS consta de un mínimo de tres AZ aisladas y físicamente separadas dentro de un área geográfica. Cada AZ tiene energía, refrigeración y seguridad física independientes y está conectada mediante redes redundantes de latencia ultrabaja.

### Zona de disponibildad

Una zona de disponibilidad (AZ) es uno o más centros de datos discretos con energía, redes y conectividad redundantes en una región de AWS. Todas las AZ de una región de AWS están interconectadas con redes de gran ancho de banda y baja latencia, a través de fibra metropolitana dedicada totalmente redundante, que proporciona redes de alto rendimiento y baja latencia entre las AZ.

### AWS Storage Gateway

AWS Storage Gateway es un servicio de almacenamiento en el Cloud híbrido que conecta tus entornos locales existentes con el Cloud de AWS. Los clientes utilizan Storage Gateway para simplificar la gestión del almacenamiento y reducir costes en casos clave de uso del almacenamiento en el Cloud híbrido. Entre ellos se incluyen trasladar copias de seguridad en cinta al Cloud, reducir el almacenamiento local con recursos compartidos de archivos respaldados por el Cloud, proporcionar acceso de baja latencia a datos en AWS para aplicaciones locales, así como diversos casos de uso de migración, archivado, procesamiento y recuperación de desastres.

El servicio AWS Storage Gateway proporciona tres tipos diferentes de puertas de enlace (Tape Gateway, File Gateway y Volume Gateway) que conectan sin problemas las aplicaciones locales con el almacenamiento en el Cloud, almacenando los datos en caché local para un acceso de baja latencia.

#### AWS Transit Gateway

AWS Transit Gateway conecta las Amazon Virtual Private Cloud (Amazon VPC) y las redes locales a través de un hub central. Esto simplifica tu red y pone fin a las complejas relaciones de interconexión. Actúa como un router en el Cloud: cada nueva conexión sólo se realiza una vez. A medida que te expandes globalmente, el peering entre regiones conecta las puertas de enlace de tránsito de AWS utilizando la red global de AWS. Tus datos se cifran automáticamente y nunca viajan por el Internet público.

### Amazon Elastic Container Registry (ECR)

Amazon Elastic Container Registry (Amazon ECR) puede utilizarse para almacenar, administrar e implementar imágenes de contenedores Docker. Amazon Elastic Container Registry (Amazon ECR) elimina la necesidad de operar tus repositorios de contenedores. Puedes extraer tus imágenes Docker de Amazon Elastic Container Registry (Amazon ECR) y ejecutarlas en Amazon Elastic Container Service (Amazon ECS).

### Amazon MQ

Amazon MQ es un servicio administrado de intermediario de mensajes para Apache ActiveMQ y RabbitMQ que facilita la configuración y el funcionamiento de los intermediarios de mensajes en AWS. Amazon MQ reduce tus responsabilidades operativas al administrar por ti el aprovisionamiento, la configuración y el mantenimiento de los intermediarios de mensajes. Como Amazon MQ se conecta a tus aplicaciones actuales con API y protocolos estándar del sector, puedes migrar fácilmente a AWS sin tener que reescribir el código.

Si utilizas mensajería con aplicaciones existentes y quieres trasladar la funcionalidad de mensajería al Cloud de forma rápida y sencilla, AWS te recomienda que consideres Amazon MQ. Es compatible con las API y los protocolos estándar del sector, por lo que puedes pasar de cualquier intermediario de mensajes basado en estándares a Amazon MQ sin reescribir el código de mensajería de tus aplicaciones. Si estás creando aplicaciones totalmente nuevas en el Cloud, AWS te recomienda que consideres Amazon SQS y Amazon SNS.

### AWS Local Zones

AWS Local Zones te permiten utilizar determinados servicios de AWS, como servicios informáticos y de almacenamiento, más cerca de más usuarios finales, proporcionándoles acceso de muy baja latencia a las aplicaciones que se ejecutan localmente. Las AWS Local Zones también están conectadas a la región matriz a través de la red privada redundante y de gran ancho de banda de Amazon, lo que proporciona a las aplicaciones que se ejecutan en las AWS Local Zones un acceso rápido, seguro y sin interrupciones al resto de servicios de AWS.

Deberías utilizar las AWS Local Zones para implementar cargas de trabajo más cerca de tus usuarios finales para requisitos de baja latencia. Las AWS Local Zones tienen su conexión a Internet y admiten AWS Direct Connect, por lo que los recursos creados en la Zona Local pueden servir a los usuarios finales locales con comunicaciones de muy baja latencia.

### AWS Wavelength

AWS Wavelength extiende el Cloud de AWS a una red global de Edge Locations 5G para permitir a los desarrolladores innovar y crear toda una nueva clase de aplicaciones que requieren una latencia ultrabaja. Las zonas Wavelength proporcionan una conexión segura y de gran ancho de banda a la región AWS matriz, lo que permite a los desarrolladores conectarse sin problemas a toda la gama de servicios de la región AWS a través de las mismas API y conjuntos de herramientas.

### AWS Fargate

AWS Fargate es un motor informático sin servidor para contenedores. Funciona tanto con Amazon Elastic Container Service (Amazon ECS) como con Amazon Elastic Kubernetes Service (Amazon EKS). AWS Fargate facilita que te centres en crear tus aplicaciones. AWS Fargate elimina la necesidad de aprovisionar y administrar servidores, te permite especificar y pagar recursos por aplicación, y mejora la seguridad mediante el aislamiento de aplicaciones por diseño. AWS Fargate asigna la cantidad adecuada de cómputo, eliminando la necesidad de elegir instancias y escalar la capacidad del clúster. Sólo pagas por los recursos necesarios para ejecutar tus contenedores, por lo que no hay que sobreaprovisionar ni pagar por servidores adicionales. AWS Fargate ejecuta cada tarea o pod en su núcleo, proporcionando a las tareas y pods su propio entorno informático aislado. Esto permite que tu aplicación tenga un aislamiento de la carga de trabajo y una seguridad mejorada por diseño.

### AWS Systems Manager Session Manager

AWS Systems Manager Session Manager es un servicio totalmente gestionado que te proporciona una experiencia interactiva de shell y CLI basada en navegador. Ayuda a proporcionar una gestión de instancias segura y auditable sin necesidad de abrir puertos de entrada, mantener hosts bastión y administrar claves SSH. AWS Systems Manager Session Manager ayuda a permitir el normativa de las políticas corporativas que requieren un acceso controlado a las instancias, aumentar la seguridad y la auditabilidad del acceso a las instancias, a la vez que proporciona simplicidad y acceso multiplataforma a las instancias a los usuarios finales.

### AWS Service Catalog

AWS Service Catalog permite a las organizaciones crear y administrar catálogos de servicios de TI aprobados para su uso en AWS. Estos servicios de TI pueden incluir desde imágenes de máquinas virtuales, servidores, software y bases de datos hasta arquitecturas completas de aplicaciones multinivel.

## Seguridad

### IAM Effect, Action

La mayoría de las políticas se almacenan en AWS como documentos JSON. Las políticas basadas en la identidad y las políticas utilizadas para establecer límites de permisos son documentos de política JSON que adjuntas a un usuario o rol. Las políticas basadas en recursos son documentos de política JSON que adjuntas a un recurso.

Un documento de política JSON incluye estos elementos:

Información opcional sobre toda la política en la parte superior del documento
Una o más declaraciones individuales
Cada declaración incluye información sobre un único permiso. La información de una declaración está contenida en una serie de elementos.

Versión - Especifica la versión del lenguaje de la política que quieres utilizar. Como mejor práctica, utiliza la última versión de 2012-10-17.

Declaración - Utiliza este elemento principal de la política como contenedor de los siguientes elementos. Puedes incluir más de una declaración en una política.

Sid (Opcional) - Incluye un ID de declaración opcional para diferenciar tus declaraciones.

Effect - Utiliza ALLOW o DENY para indicar si la política permite o deniega el acceso.

Principal (Obligatorio sólo en algunas circunstancias) - Si creas una política basada en recursos, debes indicar la cuenta, usuario, rol o usuario federado al que quieres permitir o denegar el acceso. Si estás creando una política de permisos IAM para adjuntarla a un usuario o rol, no puedes incluir este elemento. El principal está implícito como ese usuario o rol.

Action - Incluye una lista de acciones que la política permite o deniega.

Resource (Obligatorio sólo en algunas circunstancias) - Si creas una política de permisos IAM, debes especificar una lista de recursos a los que se aplican las acciones. Si creas una política basada en recursos, este elemento es opcional. Si no incluyes este elemento, el recurso al que se aplica la acción es el recurso al que se adjunta la política.

Condition (Opcional) - Especifica las circunstancias en las que la política concede el permiso.
### Gestión del rendimiento y la capacidad

El AWS Cloud Adoption Framework (AWS CAF) aprovecha la experiencia y las mejores prácticas de AWS para ayudarte a transformar digitalmente y acelerar tus resultados empresariales mediante el uso innovador de AWS. Utiliza el CAF de AWS para identificar y priorizar las oportunidades de transformación, evaluar y mejorar tu preparación para el Cloud y evolucionar iterativamente tu hoja de ruta de transformación.

AWS CAF agrupa sus capacidades en seis perspectivas: Negocio, Personas, Gobernanza, Plataforma, Seguridad y Operaciones. Cada perspectiva comprende un conjunto de capacidades que las partes interesadas relacionadas funcionalmente poseen o gestionan en su viaje de transformación del Cloud.

La perspectiva de operaciones ayuda a garantizar que tus servicios en el Cloud se prestan a un nivel que satisface las necesidades de tu negocio. La gestión del rendimiento y la capacidad bajo la perspectiva de Operaciones forma parte del AWS Cloud Adoption Framework (AWS CAF)

AWS Cloud Adoption Framework (AWS CAF) - Capacidades fundacionales:
![adop](img/adop.png)

### Amazon Inspector

Amazon Inspector es un servicio automatizado de evaluación de la seguridad que ayuda a mejorar la seguridad y la normativa de las aplicaciones desplegadas en AWS. Amazon Inspector evalúa automáticamente las aplicaciones en busca de exposición, vulnerabilidades y desviaciones de las mejores prácticas.

### Usuario

Las claves de acceso son credenciales a largo plazo para un usuario de IAM o el usuario raíz de la cuenta de AWS. Puedes utilizar claves de acceso para firmar solicitudes programáticas a la CLI de AWS o a la API de AWS (directamente o utilizando el SDK de AWS). Las claves de acceso constan de dos partes: un ID de clave de acceso (por ejemplo, AKIAIOSFODNN7EXAMPLE) y una clave de acceso secreta (por ejemplo, wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY). Al igual que el nombre de usuario y la contraseña, debes utilizar conjuntamente el ID de la clave de acceso y la clave de acceso secreta para autenticar tus solicitudes. Las claves de acceso son secretas, igual que una contraseña. Nunca debes compartirlas.

### Rol

Un rol IAM es similar a un usuario IAM, en el sentido de que es una identidad AWS con políticas de permisos que determinan lo que la identidad puede y no puede hacer en AWS. Sin embargo, en lugar de estar asociado únicamente a una persona, un rol está pensado para que pueda ser asumido por cualquiera que lo necesite.

### Grupo de usuarios

 Un grupo de usuarios IAM es un conjunto de usuarios IAM. Los grupos te permiten especificar permisos para varios usuarios, lo que puede facilitar la gestión de los permisos de esos usuarios.

### Politica

Gestionas el acceso en AWS creando políticas y asociándolas a identidades IAM (usuarios, grupos de usuarios o roles) o recursos AWS. Una política es un objeto de AWS que, cuando se asocia a una identidad o recurso, define sus permisos.

Las claves de acceso no están vinculadas al rol IAM, al grupo IAM o a la política de AWS. Así que las tres opciones son incorrectas.

### AWS Direct Connect

AWS Direct Connect es una solución de servicio en el Cloud que facilita el establecimiento de una conexión de red dedicada desde tus instalaciones a AWS. Puedes utilizar AWS Direct Connect para establecer una interfaz virtual privada desde tu red local directamente a tu Amazon VPC, proporcionándote una conexión de red privada de gran ancho de banda entre tu red y tu VPC. Esta conexión es privada y no va por el Internet público. Se tarda al menos un mes en establecer esta conexión física.

Cómo funciona AWS Direct Connect:
![direct_connect](img/direct.png)

### Amazon VPC Endpoint

Amazon VPC Endpoint te permite conectar de forma privada tu VPC a los servicios de AWS compatibles y a los servicios de punto final de VPC impulsados por AWS PrivateLink sin necesidad de una puerta de enlace a Internet, un dispositivo NAT, una conexión VPN o una conexión AWS Direct Connect. Las instancias de tu VPC no necesitan direcciones IP públicas para comunicarse con los recursos del servicio. El tráfico entre tu VPC y el otro servicio no sale de la red de Amazon. VPC Endpoint no puede utilizarse para conectar de forma privada el centro de datos local al Cloud de AWS.

### Internet Gateway (Puerta de enlace de internet)

Internet Gateway es un componente de la VPC de escala horizontal, redundante y de alta disponibilidad que permite la comunicación entre tu VPC e Internet. Una puerta de enlace a Internet tiene dos finalidades: proporcionar un destino en las tablas de rutas de tu VPC para el tráfico enrutable por Internet y realizar la traducción de direcciones de red (NAT) para las instancias. La puerta de enlace a Internet no puede utilizarse para conectar de forma privada el centro de datos local al Cloud de AWS.

### VPN Site-to-Site

VPN Site-to-Site crea una conexión segura entre tu centro de datos o sucursal y tus recursos en el Cloud de AWS. Esta conexión va a través del Internet público.

### AWS Web Application Firewall (AWS WAF)

AWS Web Application Firewall (AWS WAF) es un firewall de aplicaciones web que ayuda a proteger las aplicaciones web de los ataques permitiéndote configurar reglas que permiten, bloquean o monitorizan (cuentan) las solicitudes web en función de las condiciones que definas. Estas condiciones incluyen direcciones IP, cabeceras HTTP, cuerpo HTTP, cadenas URI, inyección SQL y scripts entre sitios. Puedes utilizar la regla de coincidencia basada en la dirección IP para bloquear zonas geográficas específicas. La precisión de la base de datos de búsqueda de direcciones IP por países varía según la región. Según pruebas recientes, AWS menciona que la precisión global del mapeo de dirección IP a país es del 99,8%.

### La seguridad y la normativa

es una responsabilidad compartida entre AWS y el cliente. Este modelo compartido puede ayudar a aliviar la carga operativa del cliente, ya que AWS opera, gestiona y controla los componentes, desde el sistema operativo del host y la capa de virtualización hasta la seguridad física de las instalaciones en las que opera el servicio.

- **AWS**:

  - **seguridad del Cloud**: Esto abarca sus elementos de infraestructura global, incluidas las regiones, las zonas de disponibilidad (AZ) y las Ubicaciones de Borde.

- **Cliente**:

  - **Cifrado de bases de datos**: Según el modelo de responsabilidad compartida de AWS, los clientes son responsables de la gestión de sus datos, incluido el cifrado de los mismos.

  - **Gestion de parches**: el cliente es responsable de la seguridad "en" el Cloud. Los clientes que despliegan una instancia de Amazon EC2 son responsables de la gestión del sistema operativo invitado (incluidas las actualizaciones y los parches de seguridad), de cualquier software de aplicación o utilidad instalada por el cliente en las instancias, y de la configuración del firewall proporcionado por AWS (denominado grupo de seguridad) en cada instancia.

### Red de socios de AWS (APN)

Las organizaciones pueden obtener ayuda de la red de socios de AWS (APN) para identificar los servicios de AWS adecuados para crear soluciones en el Cloud de AWS. La red de socios de AWS (APN) es el programa global de socios para empresas de tecnología y consultoría que aprovechan Amazon Web Services para crear soluciones y servicios para los clientes.

## Costos

### Etiquetas de asignacion de costes

Una etiqueta de asignación de costes es una etiqueta que tú o AWS asignáis a un recurso de AWS. Cada etiqueta consta de una clave y un valor. Para cada recurso, cada clave de etiqueta debe ser única, y cada clave de etiqueta sólo puede tener un valor. Puedes utilizar etiquetas para organizar tus recursos, y etiquetas de asignación de costes para realizar un seguimiento detallado de tus costes de AWS.

AWS proporciona dos tipos de etiquetas de asignación de costes: las generadas por AWS y las definidas por el usuario. AWS define, crea y aplica las etiquetas generadas por AWS por ti, y tú defines, creas y aplicas las etiquetas definidas por el usuario. Debes activar ambos tipos de etiquetas por separado antes de que puedan aparecer en el AWS Cost Explorer o en un informe de asignación de costes

### Cuentas separadas

Crea cuentas de AWS separadas para entornos de desarrollo y producción para recibir facturas separadas

Cada cuenta de AWS proporciona su propia factura a final de mes. Puedes obtener facturas separadas para los entornos de desarrollo y producción configurando cuentas de AWS distintas para cada entorno.

### AWS Budgets

AWS Budgets te permite establecer presupuestos personalizados para realizar un seguimiento de tu coste y uso desde los casos de uso más sencillos a los más complejos. Con AWS Budgets, puedes elegir que se te avise por correo electrónico o notificación SNS cuando el coste y el uso reales o previstos superen el umbral de tu presupuesto, o cuando la utilización o cobertura reales de tu RI y planes de ahorro caigan por debajo del umbral deseado. Con las acciones de AWS Budgets, también puedes configurar acciones específicas para responder al estado de coste y uso en tus cuentas, de modo que si tu coste o uso supera o se prevé que supere tu umbral, se puedan ejecutar acciones automáticamente o con tu aprobación para reducir el gasto excesivo involuntario.

 Hay cuatro tipos de presupuesto diferentes que puedes crear en AWS Budgets: **presupuesto de costes**, **presupuesto de uso**, **presupuesto de reservas** y **presupuesto de planes de ahorro**.

**Presupuesto de costes** - Te ayuda a planificar cuánto quieres gastar en un servicio.

**Presupuesto de uso** - Te ayuda a planificar cuánto quieres utilizar uno o varios servicios.

**Presupuesto de reserva** - Esto te ayuda a hacer un seguimiento del uso de tus instancias reservadas (RI). Dos formas de hacerlo - Presupuestos de utilización de instancias reservadas (RI) (Esto te permite ver si tus instancias reservadas (RI) están sin utilizar o infrautilizadas), Presupuestos de cobertura de instancias reservadas (RI) (Esto te permite ver qué parte del uso de tu instancia está cubierta por una reserva).

### AWS Cost Explorer

AWS Cost Explorer tiene una interfaz fácil de usar que te permite visualizar, comprender y administrar tus costes y uso de AWS a lo largo del tiempo. Cost Explorer Resource Rightsizing Recommendations y Compute Optimizer utilizan el mismo motor de recomendaciones. El motor de recomendaciones Compute Optimizer ofrece recomendaciones para ayudar a los clientes a identificar los tipos de instancia EC2 óptimos para sus cargas de trabajo. La consola y la API del Explorador de Costes muestran un subconjunto de estas recomendaciones que pueden suponer un ahorro de costes, y las aumenta con información de costes y ahorros específica del cliente (por ejemplo, información de facturación, créditos disponibles, RI y Planes de Ahorro) para ayudar a los propietarios de la Gestión de Costes a identificar rápidamente las oportunidades de ahorro mediante el redimensionamiento de la infraestructura. La consola Compute Optimizer y su API ofrecen todas las recomendaciones independientemente de las implicaciones de costes.

### Visión general de las opciones de precios de EC2

![inst](img/precio_ins.jpeg)

### Opción de pago parcial por adelantado con plazo estándar de 3 años

Puedes utilizar las instancias Reservadas (RI) de Amazon EC2 para reservar capacidad y recibir un descuento en el uso de tu instancia en comparación con la ejecución de instancias bajo demanda. El precio de uso con descuento se reserva para la duración de tu contrato, lo que te permite predecir los costes de computación durante la vigencia de la instancia reservada (RI).

### AWS Pricing Calculator

AWS Pricing Calculator te permite explorar los servicios de AWS y crear una estimación del coste de tus casos de uso en AWS. Puedes modelar tus soluciones antes de construirlas, explorar los puntos de precio y los cálculos que hay detrás de tu estimación, y encontrar los tipos de instancia disponibles y las condiciones contractuales que se ajusten a tus necesidades. Esto te permite tomar decisiones informadas sobre el uso de AWS. Puedes planificar tus costes y uso de AWS o calcular el precio de configurar un nuevo conjunto de instancias y servicios. La Calculadora de Precios de AWS puede proporcionar la estimación del uso del servicio de AWS basándose en la lista de servicios de AWS.

### Creditos

Los créditos se aplican en el siguiente orden:

1. Expira más pronto

1. Menor número de productos aplicables

1. Crédito más antiguo

Para el caso de uso dado, se aplica el crédito uno, que caduca en julio, al cargo de Amazon EC2, lo que te deja con un cargo de 900$ de Amazon EC2 y un cargo de 500$ de Amazon S3. A continuación, se aplica el crédito dos a los 900$ restantes de uso de Amazon EC2. Tienes que pagar 850$ por Amazon EC2 y 500$ por Amazon S3. Ahora se han agotado todos tus créditos.

### Tarifas basas en EC2 Linux

Existe una tarifa mínima de un minuto para las instancias EC2 basadas en Linux.

### Factores Fundamentales del coste

Hay tres factores fundamentales del coste con AWS: la informática, el almacenamiento y la transferencia de datos salientes. En la mayoría de los casos, no se cobra por la transferencia de datos entrantes ni por la transferencia de datos entre otros servicios de AWS dentro de la misma región. La transferencia de datos salientes se agrega a través de los servicios y luego se cobra a la tasa de transferencia de datos salientes.

Según los precios de AWS, la transferencia de datos entre instancias S3 y EC2 dentro de la misma región no se cobra, por lo que no habría ningún cargo por transferencia de datos por mover 500 GB de datos de una instancia EC2 a un bucket S3 en la misma región.

### Reservas para optimizar costes

Los siguientes servicios de AWS admiten reservas para optimizar costes:

**Instancias reservadas (RI) de Amazon EC2:** Puedes utilizar las instancias reservadas (RI) de Amazon EC2 para reservar capacidad y recibir un descuento en el uso de tu instancia en comparación con la ejecución de instancias bajo demanda.

**Capacidad reservada de Amazon DynamoDB**: Si puedes predecir tu necesidad de capacidad de lectura y escritura de Amazon DynamoDB, la Capacidad Reservada ofrece un ahorro significativo sobre el precio normal de la capacidad de capacidad provisionada de DynamoDB.

**Nodos reservados de Amazon ElastiCache**: Los nodos reservados de Amazon ElastiCache te dan la opción de hacer un pago único y bajo por cada nodo de caché que quieras reservar y, a cambio, recibir un descuento significativo en el cargo por hora de ese nodo.

**Instancias reservadas de Amazon RDS**: Al igual que las instancias reservadas de Amazon EC2, las instancias reservadas de Amazon RDS pueden adquirirse sin pago inicial, con pago inicial parcial o con pago inicial total. Todos los tipos de instancias reservadas están disponibles para los motores de base de datos Aurora, MySQL, MariaDB, PostgreSQL, Oracle y SQL Server.

**Nodos reservados de Amazon Redshift**: Si tienes intención de mantener un clúster de Amazon Redshift en funcionamiento continuo durante un periodo prolongado, deberías considerar la posibilidad de adquirir ofertas de nodos reservados. Estas ofertas suponen un ahorro significativo con respecto a los precios bajo demanda, pero requieren que reserves nodos informáticos y te comprometas a pagar por ellos durante 1 ó 3 años.

### AWS Shield Advanced

AWS Shield Standard está activado para todos los clientes de AWS, por defecto. Para niveles superiores de protección contra ataques, puedes suscribirte a AWS Shield Advanced. Con Shield Advanced, también tienes acceso exclusivo a métricas e informes avanzados en tiempo real para obtener una amplia visibilidad de los ataques a tus recursos de AWS. Con la ayuda del DRT (equipo de respuesta DDoS), AWS Shield Advanced incluye detección y mitigación inteligente de ataques DDoS no sólo para los ataques de la capa de red (capa 3) y de transporte (capa 4), sino también para los de la capa de aplicación (capa 7).

AWS Shield Advanced proporciona protección ampliada contra ataques DDoS para aplicaciones web que se ejecutan en los siguientes recursos: Amazon Elastic Compute Cloud, Elastic Load Balancer (ELB), Amazon CloudFront, Amazon Route 53, AWS Global Accelerator.

### Endpoint de VPC

Un Endpoint de VPC (también llamado punto final) te permite conectar de forma privada tu VPC a los servicios de AWS compatibles y a los servicios de punto final de VPC impulsados por AWS PrivateLink sin necesidad de una puerta de enlace a Internet, un dispositivo NAT, una conexión VPN o una conexión AWS Direct Connect. Las instancias de tu VPC no necesitan direcciones IP públicas para comunicarse con los recursos del servicio. El tráfico entre tu VPC y el otro servicio no sale de la red de Amazon.

Hay dos tipos de endpoints de la VPC: endpoints de interfaz y endpoints de Gateway.

Un endpoint de interfaz es una interfaz de red elástica con una dirección IP privada del rango de direcciones IP de tu subred que sirve como punto de entrada para el tráfico destinado a un servicio soportado. Los puntos finales de interfaz funcionan con AWS PrivateLink, una tecnología que te permite acceder de forma privada a los servicios utilizando direcciones IP privadas.

Un Gateway Endpoint es una puerta de enlace que especificas como destino de una ruta en tu tabla de rutas para el tráfico destinado a un servicio de AWS soportado. Se admiten los siguientes servicios de AWS:

- Amazon Simple Storage Service (Amazon S3)
- Amazon DynamoDB

***Puede que veas una pregunta sobre este concepto en el examen. Recuerda que sólo Amazon S3 y Amazon DynamoDB soportan el Endpoint de Gateway de VPC. Todos los demás servicios que admiten puntos finales de VPC utilizan un punto final de interfaz de VPC (ten en cuenta que Amazon S3 también admite el endpoint de interfaz de VPC).***

### Equipo de abusos AWS

El equipo de abusos de AWS puede ayudarte cuando se utilicen recursos de AWS para incurrir en conductas abusivas.

Consulta los detalles de los distintos escenarios que el equipo de Abuso de AWS puede abordar:
![abusos_aws](img/abus.jpeg)

### AWS Organizations

Te ayuda a administrar centralmente la facturación; controlar el acceso, la normativa y la seguridad; y compartir recursos entre tus cuentas de AWS. Con AWS Organizaciones, puedes automatizar la creación de cuentas, crear grupos de cuentas que reflejen tus necesidades empresariales y aplicar políticas a estos grupos para su gobernanza. También puedes simplificar la facturación configurando un único método de pago para todas tus cuentas de AWS. AWS Organizaciones está disponible para todos los clientes de AWS sin coste adicional.

### AWS Shield Standard

AWS Shield Standard te defiende contra los ataques DDoS más comunes y frecuentes de la capa de red y transporte dirigidos a tu sitio web o aplicaciones. Aunque AWS Shield Standard ayuda a proteger a todos los clientes de AWS, obtienes mejor protección si utilizas Amazon CloudFront y Amazon Route 53. Todos los clientes de AWS se benefician de las protecciones automáticas de AWS Shield Standard, sin cargo adicional.

### AWS Web Application Firewall(AWS WAF)

AWS WAF es un firewall de aplicaciones web que te permite monitorizar las solicitudes HTTP(S) que se reenvían a una distribución de Amazon CloudFront, una API de Amazon API Gateway o un Application Load Balancer. AWS WAF cobra en función del número de listas de control de acceso web (ACL web) que crees, del número de reglas que añadas por ACL web y del número de solicitudes web que recibas (no es un servicio gratuito).

### Gestión de la configuración

La seguridad y la normativa es una responsabilidad compartida entre AWS y el cliente. Este modelo compartido puede ayudar a aliviar la carga operativa del cliente, ya que AWS opera, gestiona y controla los componentes, desde el sistema operativo del host y la capa de virtualización hasta la seguridad física de las instalaciones en las que opera el servicio.

Los controles que se aplican tanto a la capa de infraestructura como a la del cliente, pero en contextos o perspectivas completamente separados, se denominan controles compartidos. En un control compartido, AWS proporciona los requisitos para la infraestructura y el cliente debe proporcionar su propia implementación del control dentro de su uso de los servicios de AWS. La gestión de la configuración forma parte de los controles compartidos: AWS mantiene la configuración de sus dispositivos de infraestructura, pero el cliente es responsable de configurar sus propios sistemas operativos invitados, bases de datos y aplicaciones.

### Clave gestionada por el cliente (CMK)

Una clave KMS de AWS es una representación lógica de una clave criptográfica. Una clave KMS contiene metadatos, como el ID de la clave, la especificación de la clave, el uso de la clave, la fecha de creación, la descripción y el estado de la clave. Y lo que es más importante, contiene una referencia al material de la clave que se utiliza cuando realizas operaciones criptográficas con la clave KMS.

Las claves KMS que creas son claves gestionadas por el cliente. Las claves gestionadas por el cliente son claves KMS en tu cuenta de AWS que tú creas, posees y administras. Tienes control total sobre estas claves KMS, incluyendo el establecimiento y mantenimiento de sus políticas de claves, políticas IAM y subvenciones, habilitándolas y deshabilitándolas, rotando su material criptográfico, añadiendo etiquetas, creando alias que hagan referencia a las claves KMS y programando las claves KMS para su eliminación.

### Capa 7

AWS WAF es un firewall de aplicaciones web que te permite monitorizar las solicitudes HTTP y HTTPS que se reenvían a una API de Amazon API Gateway, Amazon CloudFront o un Application Load Balancer. Las solicitudes HTTP y HTTPS forman parte de la capa de aplicación, que es la capa 7.

### Capa 3

La Capa 3 es la capa de Red y en ella se decide qué ruta física seguirán los datos cuando se muevan por la red. AWS Shield ofrece protección en esta capa. WAF no ofrece protección en esta capa.

### Capa 4

La Capa 4 es la capa de Transporte y en ella se produce la transmisión de datos mediante los protocolos TCP o UDP. AWS Shield ofrece protección en esta capa. WAF no ofrece protección en esta capa.

### Política de uso aceptable de AWS

La Política de uso aceptable describe los usos prohibidos de los servicios web ofrecidos por Amazon Web Services, Inc. y sus filiales (los "Servicios") y el sitio web ubicado en http://aws.amazon.com (el "Sitio AWS"). Esta política está presente en https://aws.amazon.com/aup/ y es actualizada en función de las necesidades por AWS.

### El AWS Well-Architected Framework

proporciona orientación sobre la creación de infraestructuras seguras, de alto rendimiento, resistentes y eficientes para aplicaciones basadas en el Cloud. Basado en seis pilares -excelencia operativa, seguridad, fiabilidad, eficiencia del rendimiento, optimización de costes y sostenibilidad-, el Framework proporciona un enfoque coherente para que clientes y socios evalúen arquitecturas e implanten diseños que escalen con el tiempo.