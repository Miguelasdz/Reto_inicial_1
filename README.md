# Reto_inicial_1:books:

## :page_facing_up: 

# Reto Master.
## :open_book: Contenido...
- [Modulo 1: Descripción de conceptos básicos..](https://github.com/Miguelasdz/Reto_inicial_1#bookmark_tabs-modulo-1--descripci%C3%B3n-de-conceptos-b%C3%A1sicos)
- [Modulo 2: Conceptos fundamentales de Azure.](https://github.com/Miguelasdz/Reto_inicial_1#bookmark_tabs-modulo-2--conceptos-fundamentales-de-azure)
- [Modulo 3:  Componentes principales de la arquitectura Azure.](https://github.com/Miguelasdz/Reto_inicial_1#bookmark_tabs-modulo-3-)


# :bookmark_tabs: Modulo 1 : Descripción de conceptos básicos.
Hablemos sobre el Cloud Computing

## ¿Qué es el Cloud Computing o Cómputo en la nube?. :interrobang: :cloud:
Tecnología que te permite acceder a diferentes servicios (almacenamiento, archivos, redes software, etc.) a través de internet en **cualquier lugar** del mundo y en **cualquier momento**.

# :bookmark_tabs: Modulo 2 : Conceptos fundamentales de Azure.

## Cloud Computing según privacidad. :closed_lock_with_key:
Hay **tres** tipos diferentes de modelos en la nube: pública, privada e híbrida. Todas varían en términos del nivel de administración y el nivel de seguridad que proporcionan.

|            :earth_americas: Nube pública       |      :shushing_face: Nube privada    | :octopus: Nube híbrida   |
|:----------------------------:|:------------------------:|:------------------------:|
|Toda la infraestructura está en las instalaciones del proveedor de la nube, que ofrece estos servicios al cliente a través de Internet.|Es utilizada exclusivamente por una organización. |Se alojan las aplicaciones más importantes en sus propios servidores (de la empresa) a, mientras que sus demás aplicaciones se almacenan en las instalaciones del proveedor de la nube.|
|Solo se paga por lo que se usa segun lo que se necesite. | Se debe de adquirir todo desde el inicio y durante el uso de sus servicios, control total por la empresa | Flexibilidad ante todo, se determina en donde se va ejecutar que aplicación, controlan la seguridad y requisitos legales. |

## Beneficios de usar Cloud Computing. :gem:
* La reducción de costos: generalmente usan un modelo de pago por uso *Pagas por lo que Usas*, permite ejecutar la infraestructura de forma eficaz.
* Escalabilidad y elasticidad de tus recursos acorde a tus necesidades.
* El trabajo remoto.
* Disponibilidad de los recursos: siempre se tiene acceso a ellos si hay internet, en **cualquier lugar** del mundo y en **cualquier momento**.
* Copias de tus aplicaciones: los puedes recuperar si es necesario.

## CapEx :vs: OpEx

|             **CapEx** :moneybag:         |       **OpEx**  :receipt:       |
|:----------------------------:|:------------------------:|
| Los **gastos de capital** es la inversión previa de dinero en infraestructura física, tiene un valor que disminuye con el tiempo.  |       Los **gastos operativos** es dinero que se invierte en servicios o productos y se factura al instante.  *Por la forma de consumo los **servicios de la nube** se clasifican como OpEx*                |






## Servicios del Cloud Computing. :satellite:
Hay tres tipos principales de servicios en la nube: *Software as a Service* (*SaaS*), *Platform as a Service* (*PaaS*) e *Infrastructure as a Service* (*IaaS*). No existe un enfoque único, lo ideal es **encontrar la solución adecuada** que respalde los requisitos de tu empresa.

|            **SaaS** :frowning_person:       |       **PaaS**  :man_technologist:    |  **IaaS**  :construction_worker_woman: :computer::gear:  |
|:----------------------------:|:------------------------:|:------------------------:|
|Las **aplicaciones** del cliente están alojadas en las instalaciones del proveedor de la nube.| Brinda la ventaja de acceder a las herramientas de desarrollo que necesitan para crear y administrar sus aplicaciones. |    permite acceder a servicios de infraestructura a pedido a través de Internet   |
|Sin CapEX, no hay costo inicial. | Sin CapEX, se opera bajo el modelo OpEx| Sin CapEX, se opera bajo el modelo OpEx|
|Para el usuario final: **APLICACIONES** | Para el desarrollador: **O.S, HERRAMIENTAS, DB** | Para el SysAdmin: **SERVIDORES, ALMACENAMIENTO, FIREWALLS**|


# :bookmark_tabs: Modulo 3 :  Componentes principales de la arquitectura Azure.

## Zonas de disponibilidad, pares de regiones y regiones de Azure

Cuando nosotros hacemos uso de recursos dentro de la nube de Azure, hacemos uso de componentes físicos (hardware), los cuales se encuentran en __centros de datos__ que están ubicados en diferentres regiones.

Y...__¿Qué es una región?__

- Una ***región*** es un área geográfica en dónde por lo menos existe un centro de datos.

***Nota: No todos los servicios o características de las máquinas virtuales están disponibles en todas las regiones, se tiene que investigar que Servicios y características se encuentran disponibles en la región en la que queramos crear nuestro grupo de recursos.***

Algunas de las regiones donde se encuentra al menos un centro de datos Azure son:

- Oeste EE.UU
- Centro de Canadá
- Europa Occidental
- Este de Australia
- Japón Occidental
- ***US DoD(centro)***
- ***US Gov Virginia***
- ***US Gov Iowa***

Estos tres últimas regiones son zonas especializadas, en las que se crean aplicaciones referentes al cumplimiento normativo o aspectos legales de los EE.UU., los cuales cuentan con aislamiento de red. 

- ***Este de China***
- ***Norte de China***

Estas dos últimas no las opera directamente Microsoft, ya que se teniene un combenio con la empresa 21Vianet el cual se encarga de operarlas.

## Zonas de disponibilidad

Una **zona de disponibilidad** es aquella en donde hay uno o varios centros de datos separados físicamente dentro de una _región_.

## Autores :pencil2:
- :octocat: [Jorge Cazarez](https://github.com/JorgeCasarez)
- :octocat: [Miguel Hernández.](https://github.com/Miguelasdz)
- :octocat: [Iris Martinez.](https://github.com/IrisYMartinez)
- :octocat: [Ricardo Ruíz](https://github.com/Yatram)
