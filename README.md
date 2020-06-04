# Repositorio para el meetup online de Polkadot en Español.

- Video completo [aquí](https://www.youtube.com/watch?v=EcL2o5f2A9A).

## ¿Qué es Polkadot?
Una red heterogénea y multicadena que permite a varias blockchains de diferentes características realizar comunicaciones arbitrarias de cadena cruzada bajo una seguridad compartida.

Polkadot es una plataforma inclusiva sin barreras de entrada para las economías flexibles y autónomas que actúan dentro del paraguas de seguridad de Polkadot _(similar a la forma en que los Estados Unidos comparten la seguridad a nivel nacional entre estados autónomos)_.

Polkadot se basa en dos principios clave:
- Disminución de la dificultad de acceso.
- Diseñado para cambiar. Un enfoque radicalmente innovador de la tecnología.

Disminución de las dificultades de acceso
Polkadot es diferente de la mayoría de las plataformas que tienen algún tipo de bloqueo de plataforma. Polkadot se basa en la flexibilidad, la modularidad y el fortalecimiento de las personas para que hagan lo que quieran. No existe una instancia centralizada de toma de decisiones. Los usuarios y las partes que componen el sistema _(parachains)_ están facultados para actuar y gobernarse a su antojo.

En Ethereum necesitas que el Ether interactúe, ya sea que tu DApp tenga o no su propio token o quiera usar Ether. En Polkadot no se necesitan DOTs para interactuar con el subsistema. Si el número de transacciones en Ethereum aumenta, la demanda de Ether también aumenta porque se necesita _gasolina_ para cada transacción. En Polkadot no es el caso. Las Parachains pueden tener 100 o 1m txn/segundo, pero el número de DOTs requeridos sigue siendo cero. Por supuesto, las parachains todavía tienen que vincular DOTs para asegurar una posición, pero reciben los DOTs de vuelta al final y esto no cambia en función de la cantidad de uso de la plataforma

Enfoque de la tecnología basado en la innovación
Polkadot está diseñado para el cambio. Estamos en contra de no hacer algo. Estamos en contra de la ruta segura que se ha recorrido. Estamos a favor de la mejora continua. Estamos a favor de la experimentación y la innovación. Estamos a favor de ser pioneros, inventar, explorar y pensar en grande. No sólo queremos una mejora continua del sistema principal de Polkadot, la relay chain, sino también de todos sus componentes, es decir, las parachains. Hemos diseñado todo el sistema para que haya opciones y posibilidad de actualización, lo que significa que usted puede actuar y ejecutar sus opciones.

Polkadot es actualizable, lo que significa que es morfológico. Puede cambiar. Para cumplir sus promesas, Polkadot debe ser flexible y capaz de adoptar las mejores tecnologías y los activos de mayor valor del mundo.

## ¿Qué es Substrate?
Un conjunto de herramientas modular para construir cadenas de bloques. Polkadot se construye usando Substrate. Las cadenas construidas con Substrate serán fáciles de conectar como Parachains.

## ¿Qué es Kusama?
La "red canaria" de Polkadot. Consiste en una versión anticipada y no auditada del software Polkadot. No es una red de prueba - después de la transición a NPoS, la red queda totalmente en manos de la comunidad (es decir, de los poseedores de tokens).

## ¿Qué es la Relay Chain?
La cadena que coordina el consenso y la comunicación entre las parachains (y las cadenas externas, a través de puentes).

## ¿Qué es una Parachain?
Una cadena de bloques que reúne varias características que le permiten trabajar dentro de los límites de Polkadot. También conocida como "cadena paralela". Cada una puede tener una arquitectura única. Un Parachain es una estructura de datos específica de una aplicación que es globalmente coherente y verificable por los validadores de la Relay chain de Polkadot. Lo más común es que una Parachain tome la forma de una cadena de bloques, pero no hay necesidad específica de que sean cadenas de bloques reales. Toman su nombre del concepto de cadenas paralelas que corren paralelas a la Relay chain. Debido a su naturaleza complementaria, pueden paralelizar el procesamiento de transacciones y lograr la escalabilidad del sistema Polkadot. Son mantenidas por los _Collators_

## ¿Qué son las Parathreads?
Las Parathreads son una idea para que las Parachains participen temporalmente (bloque a bloque) en la seguridad de Polkadot sin necesidad de alquilar un espacio dedicado como las Parachains. Esto se hace compartiendo económicamente el escaso recurso de un espacio para Parachain entre varios recursos en competencia (parathreads). Las cadenas que de otro modo no podrían adquirir un espacio de Parahain completo, o que no consideran económicamente sensato hacerlo, pueden seguir participando en la seguridad compartida de Polkadot, aunque con una cuota asociada por bloque. También ofrece una elegante salida a las Parachains que ya no necesitan un espacio dedicado para el Parachains, pero que desean seguir utilizando la Relay chain.

## ¿Qué son los Collators?
Los collators mantienen las Parachains recogiendo las transacciones de Parachains de las usuarias y produciendo pruebas de transición del estado para los validadores.
Estos participantes se ubicarán encima de las Parachains y proporcionarán pruebas a los validadores basadas en las transacciones de las Parachains. Los Collators mantienen las Parachains agregando las transacciones de Parachains en bloques de Parachains y produciendo pruebas estatales de transición para los validadores basadas en esos bloques. También supervisan la red y prueban el mal comportamiento a los validadores. Los Collators mantienen un "nodo completo" para una Parachain en particular, lo que significa que conservan toda la información necesaria para poder crear nuevos bloques y ejecutar transacciones de forma muy similar a como lo hacen los mineros con las cadenas de bloques actuales de PoW. En circunstancias normales, cotejarán y ejecutarán las transacciones para crear un bloque sin sellar y lo proporcionarán, junto con una prueba de transición de estado, a uno o más validadores encargados de proponer un bloque de Parachain.

## ¿Qué es BABE?
**B**lind **A**ssignment of **B**lock **E**xtension es el mecanismo para la producción de bloques de Polkadot.

## ¿Qué es GRANDPA?
**G**HOST-based **R**ecursive **An**cestor **D**eriving **P**refix **A**greement. Es el instrumento para la finalización de Polkadot, que permite una finalización asincrónica, responsable y segura para la cadena de bloques. Para una visión general de GRANDPA, vea [este](https://medium.com/polkadot-network/polkadot-proof-of-concept-3-a-better-consensus-algorithm-e81c380a2372) post en Medium.

## ¿Qué son los Fisherman?
Nodos que monitorean la red para buscar validadores o collators que se comporten mal. Los fisherman deben comprometerse con una pequeña cantidad de DOTs pero pueden ser recompensados en gran medida si encuentran un mal comportamiento.

### [Presentación Polkadot _(en Español)_](https://docs.google.com/presentation/d/1jn7AuL1cnGnL-AmMID_Xlz8389HR_5-LPgX9N29qUy4/edit?usp=sharing)

### [Presentación Embajadores Polkadot _(en Español)_](https://docs.google.com/presentation/d/1Ei-9ejBvYTsiYtOFUdkuOduGYv6cyb1WIXKNp9pN_lI/edit#slide=id.p)

### [Presentación Primeros pasos con Substrate _(en Español)_](https://docs.google.com/presentation/d/1rh9184HIE7mftai96inLv6G3Sh-mI0_KBnS9M8CRWTM/edit?usp=sharing)

### Enlaces de interés:

[Glosario Polkadot _(en Español)_.](https://wiki.colmenalabs.org/glosario/)

[Polkadot wiki _(en Inglés)_.](https://wiki.polkadot.network/en/latest/)

[Awesome Substrate _(en Inglés)_.](https://substrate.dev/awesome-substrate/)

[Documentación Substrate _(en Inglés)_.](https://substrate.dev/rustdocs/)

[Wiki Substrate _(en Inglés)_.](https://substrate.dev/docs/)

[Equipos desarrollando en Polkadot _(en Inglés)_.](https://forum.web3.foundation/t/teams-building-on-polkadot/67)

[Artículo de Alfonso Cevallos explicando cómo funcionará el Nominated Proof of Stake en Polkadot _(en Inglés)_](https://medium.com/web3foundation/how-nominated-proof-of-stake-will-work-in-polkadot-377d70c6bd43).

[Cómo hacer _staking_ en Polkadot _(wiki oficial de Parity en inglés)_](https://wiki.polkadot.network/docs/en/learn-staking)

_El meetup y la traducción de las presentaciónes han sido realizadas por [wimel](https://github.com/wimel) de [DelegaNetworks](https://delega.io/)_
