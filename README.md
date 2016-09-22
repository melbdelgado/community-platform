# Zen, la Plataforma Comunitaria de CoderDojo

[![Join the chat at https://gitter.im/CoderDojo/community-platform](https://badges.gitter.im/CoderDojo/community-platform.svg)](https://gitter.im/CoderDojo/community-platform?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Bienvenidos a "Zen"! Pueden ver el sitio web en [zen.coderdojo.com](https://zen.coderdojo.com).

Este repositorio es la documentación del proyecto. [We log issues in this repository](https://github.com/CoderDojo/community-platform/issues).

También hay  [three microservice repositories and a frontend repository](https://github.com/CoderDojo/community-platform/blob/master/architecture.md).

Si quieren ir directamente a la parte de iniciar su propio ámbito de desarrollo, [visiten el repositorio del ámbito de desarrollo aquí](https://github.com/CoderDojo/cp-local-development).

# Sobre el proyecto

[CoderDojo](coderdojo.com) es una comunidad de programación gratuita para grupos de niños y jóvenes entre 7-17 años.  Somos una organización benéfica mundial y actualmente tenemos más de 900 grupos en alrededor de 60 países!

Creamos Zen para encontrar nuevos "Dojos" (grupos de programación) y para ayudar a [la Fundación CoderDojo](https://coderdojo.com/about/coderdojo-foundation/) a monitorear los grupos que hay por todo el mundo.
En 2015 lo desarrollamos para que fuese una plataforma integral de la comunidad. La creamos por completo con javascript usando [NodeJS](https://nodejs.org/) y [AngularJS](https://angularjs.org/).

 Incluye:
- la posibilidad de buscar un Dojo (un grupo de programación) y unirse a este grupo
- A bespoke ticketing system where parents and mentors can book tickets for their local club
- un perfil para padres, mentores y niños/jóvenes
- dos foros (Over 13 and community forum), que funcionan en [NodeBB](https://nodebb.org/).
- integración de [Insiginias Públicas Mozilla](http://openbadges.org/) .

La mayor parte de la tecnología que utilizamos proviene de recursos públicos y ¡eso nos enorgullece! Para preguntas relacionadas con CoderDojo, comunicarse a través de info@coderdojo.org.
Comunicarse coon guillaume@coderdojo.org with por cuestiones técnicas.

## Para colaborar con Zen

Hay muchas formas de colaborar con Zen:

* programar, las instrucciones para crear un espacio de trabajo en la zona se encuentran en el repositorio. [cp-local-development](https://github.com/CoderDojo/cp-local-development) . Tal vez quieras leer la guía  [colaborar](CONTRIBUTING.md)
* traducir, usamos [CrowdIn](https://crowdin.com/project/zen-community-platform) para organizar la ubicación, ¡por favor únete y ayúdanos!
* notificar problemas, es el encargado de detallar las fallas en elrepositorio de GitHub, [puedes ayudar aquí](https://github.com/CoderDojo/community-platform/issues)
* documentar, para colaborar con la documentación en el repositorio.

## Where to begin

View our [Speaker Deck](https://speakerdeck.com/helloworldfoundation/contributing-to-zen-the-coderdojo-open-source-community-platform)!

There are a few labels in particular that are very useful if you are new to Zen:
* The [beginner](https://github.com/CoderDojo/community-platform/labels/beginner) label marks anything considered easy enough for a first time contributor. 
* The [request for comments](https://github.com/CoderDojo/community-platform/labels/request%20for%20comments) label is great for non-coders or people wishing to get familiar with the system. These are often features we are not sure if we want to produce yet, or issues that require clearer implementation guidelines.
* The [hints provided](https://github.com/CoderDojo/community-platform/labels/hints%20provided) label is attached to anything which has been given a technical spec by someone on the development team.
* [View this document for a brief overview](https://github.com/CoderDojo/community-platform/blob/master/creating-test-data.md) of the sections of the system and how to access them with the test account.

### Bug fixes

* Ideally all of the [bugs](https://github.com/CoderDojo/community-platform/labels/bug) are the most important issues to fix. They are categorised by priority. 
* There is a [critical bugs milestone](https://github.com/CoderDojo/community-platform/milestones/Critical%20bugs) for the most important bugs.
* Some bugs are smaller CSS issues that are marked low priority and so are not as important to work on. 

### Priorities for the project

Once you're familiar with the codebase, there are a number of labels/milestones to guide you through our roadmap.
- Our [top priority](https://github.com/CoderDojo/community-platform/labels/top%20priority) label is for features which are the most important
- For immediate issues, there is a section for [Q1 2016](https://github.com/CoderDojo/community-platform/milestones/2016%20Q1)
- Issues are sorted by other priority levels, [low](https://github.com/CoderDojo/community-platform/labels/low%20priority), [normal](https://github.com/CoderDojo/community-platform/labels/normal%20priority) and [high](https://github.com/CoderDojo/community-platform/labels/high%20priority)
- We also have a [short term roadmap](https://github.com/CoderDojo/community-platform/milestones/Short%20term%20roadmap) and [long term roadmap](https://github.com/CoderDojo/community-platform/milestones/Long%20term%20roadmap)

Still not sure? Get in touch, let us know what you are interested in working on and we're happy to provide guidance.

#### Working on an issue?

- Comment on it and let us know so we don't duplicate any effort.
- We can add you to the official CoderDojo development team so you can assign yourself issues. 
- Please add unit tests where possible to your code. There is an [end to end test repository](https://github.com/CoderDojo/cp-e2e-tests) for front end testing. There is also a tests directory in the root directory of each service and in the [front end repository](https://github.com/CoderDojo/cp-zen-platform/tree/master/test).
- Tag [@tangentfairy](https://github.com/tangentfairy) if you have any questions.

## Developer Support

* The CoderDojo Foundation Technical Lead is available to help you get set up.
* Join the [gitter chat](https://gitter.im/CoderDojo/community-platform) if you have any questions.
* Those who have committed to the project can be added to the Foundation Slack community for daily communications. Please get in touch to be added! 
* To get in touch, email us at info@coderdojo.org
* To deploy a change, you'll need to get in touch as only those with commit access can do so. 
* Have a read through [closed pull requests](https://github.com/CoderDojo/cp-zen-platform/pulls?q=is%3Apr+is%3Aclosed) in the frontend repository to get a feel for what we have been working on.

## License

The Community Platform (Zen) is copyright The CoderDojo Foundation, and open sourced under the [MIT license](LICENSE.md).

## Documentation

The following is a list of further reading:

* [Architecture](architecture.md) - a high level overview of the system, the code layout, etc
* [Localisation](localisation.md) - some notes on localisation
* [Forums](forums.md) - some developer notes on the forums
