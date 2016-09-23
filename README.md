# Zen, la Plataforma Comunitaria de CoderDojo

[!Únete al chat en https://gitter.im/CoderDojo/community-platform](https://badges.gitter.im/CoderDojo/community-platform.svg)](https://gitter.im/CoderDojo/community-platform?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

¡Bienvenidos a "Zen"! Pueden ver el sitio web en [zen.coderdojo.com](https://zen.coderdojo.com).

Este repositorio es la documentación del proyecto. [Aquí registramos todo](https://github.com/CoderDojo/community-platform/issues).

También hay [tres repositorios de microservice y a frontend repository](https://github.com/CoderDojo/community-platform/blob/master/architecture.md).

Si quieres comenzar a configurar tu espacio ya, [visita el repositorio para configuración del espacio](https://github.com/CoderDojo/cp-local-development).

# Sobre el proyecto

[CoderDojo](coderdojo.com) es una comunidad gratuita de grupos de programación para niños y adolescentes de 7 a 17 años. Es una organización benéfica mundial y actualmente tenemos más de 900 grupos en más de 63 países.

Zen fue desarrollado originalmente para encontrar nuevos "Dojos" (grupos de programación) y ayudar a la [Fundación CoderDojo](https://coderdojo.com/about/coderdojo-foundation/) a buscar los nuevos Dojos que se formen.
En 2015, lo volvimos a desarrollar para que fuese una plataforma integral de la comunidad. La construimos completamente mediante javascript, [NodeJS](https://nodejs.org/) y [AngularJS](https://angularjs.org/).

Incluye:
- la posibilidad de buscar un Dojo (un grupo de programación) y unirse a él
- un sistema personalizado por el cual los padres y los mentores pueden reservar una entrada al grupo
- un perfil para los padres, los mentores y los niños
- dos foros (Over 13 and community forum), que funcionan en [NodeBB](https://nodebb.org/).
- integración de [Mozilla Open Badges](http://openbadges.org/)

La mayor parte de la tecnología que usamos es un recurso público, y ¡estamos orgullosos de eso! Para dudas relacionadas con CoderDojo, comunicarse al e-mail info@coderdojo.org .
Por cuestiones técnicas, comunicarse con guillaume@coderdojo.org .

## Colaborar con Zen

Hay muchas formas de colaborar con Zen:

* ser programador y mentor, las instrucciones para crear un espacio de trabajo local se encuentra en el repositorio [cp-local-development](https://github.com/CoderDojo/cp-local-development) . Tal vez te interese leer la guía de colaboración [contributing](CONTRIBUTING.md).
* ser traductor, usamos[CrowdIn](https://crowdin.com/project/zen-community-platform) para administrar la localización, ¡por favor ingresa y ayúdanos!
* reportar problemas, registramos las fallas o problemas en un repositorio de GitHub, [aquí puedes ayudar](https://github.com/CoderDojo/community-platform/issues)
* documentación, puedes añadir documentación en el repositorio.

## En dónde comenzar

Mira nuestro [Speaker Deck](https://speakerdeck.com/helloworldfoundation/contributing-to-zen-the-coderdojo-open-source-community-platform)!

Hay algunas secciones que son especialmente útiles si eres nuevo en Zen:
* La sección [principiante](https://github.com/CoderDojo/community-platform/labels/beginner) tiene cosas lo suficientemente sencillaz para alguien que recién comienza. 
* La sección [solicitud de comentarios](https://github.com/CoderDojo/community-platform/labels/request%20for%20comments) es muy buena para aquellos que no programan o para quienes quieran conocer el sistema. Aquí hay funciones que no estamos seguros de querer implementar o algunas cuestiones que requieren mejores instrucciones.
* La sección [recomendaciones](https://github.com/CoderDojo/community-platform/labels/hints%20provided) contiene fallas que tienen indicaciones técnicas dadas por algún programador.
* [Ver este documento resumen](https://github.com/CoderDojo/community-platform/blob/master/creating-test-data.md) en donde están las secciones del sistema y cómo acceder a ellas con una cuenta de prueba.

### Corrección de Bugs (errores)

* Lo ideal es que los [bugs](https://github.com/CoderDojo/community-platform/labels/bug) se arreglen primero ya que son los errores más importantes. Los catalogamos como prioridad.
* Hay un [documento para bugs urgente](https://github.com/CoderDojo/community-platform/milestones/Critical%20bugs) para los bugs mmás importantes.
* Algunos bugs son problemas CSS pequeños y no es tan importante trabajar en ellos.

### Prioridades para el proyecto

Después que te familiarices con el código base, hay una serie de secciones que te guiarán en el proyecto:
- La sección [muy importante](https://github.com/CoderDojo/community-platform/labels/top%20priority) es para las funciones principales.
- Para cuestiones urgentes, existe la sección [Q1 2016](https://github.com/CoderDojo/community-platform/milestones/2016%20Q1)
- Clasificamos los problemas en otras categorías, [bajos](https://github.com/CoderDojo/community-platform/labels/low%20priority), [normales](https://github.com/CoderDojo/community-platform/labels/normal%20priority) and [altos](https://github.com/CoderDojo/community-platform/labels/high%20priority)
- También tenemos la [guía a corto plazo](https://github.com/CoderDojo/community-platform/milestones/Short%20term%20roadmap) y la [guía a largo plazo] (https://github.com/CoderDojo/community-platform/milestones/Long%20term%20roadmap)

¿Todavía no estás seguro de cómo ayudar? Comunícate con nosotros, cuéntanos en que gustaría colaborar y podremos orientarte.

#### ¿Estás trabajando en un problema?

- Comenta en él para que sepamos y no dupliquemos el trabajo.
- Podemos añadirte al grupo oficial de desarrollo de CoderDojo para que puedas asignarte a ti mismo las fallas.
- Por favor agrega pruebas de unidad en donde sea posible en tu código. Tenemos el [end to end test repository](https://github.com/CoderDojo/cp-e2e-tests) para pruebas iniciales. También hay un directorio de pruebas en el directorio principal de cada servicio y en el [front end repository](https://github.com/CoderDojo/cp-zen-platform/tree/master/test).
- Etiqueta a [@tangentfairy](https://github.com/tangentfairy) si tienes alguna pregunta.

## Asistencia al programador

* La Fundación Principal Técnica de CoderDojo está disponible para ayudarte a organizarte.
* Únete al [chat gitter](https://gitter.im/CoderDojo/community-platform) si tienes dudas.
* Aquellos que se han unido al proyecto, podemos agregarlos al espacio de la Fundación para comunicarnos todos los días.¡Comunícate para ser añadido!
* Para comunicarte con nosotros puedes enviarnos un e-mail al info@coderdojo.org
* Para implementar un cambio, debes comunicarte con nosotros ya que solo aquellos que tienen acceso pueden hacerlo.
* Échale un vistazo a las [closed pull requests](https://github.com/CoderDojo/cp-zen-platform/pulls?q=is%3Apr+is%3Aclosed) en el repositorio para que sepas en qué hemos trabajado.

## Licencia

La Plataforma de la comunidad (Zen) es copyright de la Fundación CoderDojo y es un recurso público bajo la [licencia MIT](LICENSE.md).

## Documentación

A continuación hay otros documentos para leer:

* [Arquitectura](architecture.md) - una vista rápida del sitema, el diseño del código, etc.
* [Localización](localisation.md) - algunas notas sobre localización.
* [Foros](forums.md) - algunas notas de los programadores sobre los foros
