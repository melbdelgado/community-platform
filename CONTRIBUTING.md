# Colaborar en la plataforma de la comunidad (Zen)

## Para ayudar con las fallas

Cuando reportes nuevos problemas o quieras comentar en alguno 
que ya fue reportado en el repositorio, por favor asegúrate de que 
las discusiones se refieran a problemas técnicos concretos con el software de Zen.   

Lo ideal es que las discusiones sobre temas que no son técnicos, 
incluyendo la propiedad intelectual, la marca y las preguntas complejas 
sobre el proyecto sean propuestas en los [Foros](https://forums.coderdojo.com) 

## Para ayudar con la programación

El proyecto Zen les da la bienvenida a los nuevos colaboradores.
Los invididuos que contribuyen activa y significativamente se convierten en
_Colaboradores_ y obtienen permiso de acceder al proyecto.

Este documento te guiará por el proceso de colaboración.

### Paso 1: Copiar

Encuentra y realiza una copia del proyecto [en GitHub](https://github.com/CoderDojo/cp-local-development).
Luego verifica que tengas una copia propia.

#### ¿En cuál área?

Para programa nuevas funciones y arreglar bugs (errores),
es necesario desarrollar el área `master` . Zen sigue un modelo de [integración continua](https://en.wikipedia.org/wiki/Continuous_integration),
en el cual el área master se dedica siempre a producir. 

Por favor lee y sigue las [instrucciones en el repositorio de desarrollo](https://github.com/CoderDojo/cp-local-development) para iniciar tu espacio de desarrollo.


### Paso 2: Área

Crea una función en el área y comienza a hackear: 

```text
$ git checkout -b my-feature-branch -t origin/master
```

### Paso 3: Enviar

Asegúrate de que Git renoce tu usuario y tu e-mail:

```text
$ git config --global user.name "J. Random User"
$ git config --global user.email "j.random.user@example.com"
```

Es importante escribir correctamente los reportes. Un mensaje de reportes debe describir qué fue modificado y por qué. 
Sigue estas instrucciones cuando escribas:

1. La primera línea debe tener 50 caracteres o menos y describir brevemente la modificación.
2. La segunda línea queda en blanco.
3. Inserta las demás líneas en 72 columnas.

Un buen mensaje es similar a lo siguiente:

```
explicar el reporte en una línea

En el cuerpo  del reporte explicar detalladamente los cambios
y tal vez proporcionar algunos antecendentes de la solución del problema, etc.

El cuerpo puede ocupar varios párrafos. Por favor, achica las palabras y mantén las columnas 
en menos de 72 caracteres más o menos. De esa forma el 'git log' mostrará * show things
nicely even when it is indented.
```

El encabezamiento debe ser significativo ya que es lo que las otras personas verá cuando ingresen a  `git shortlog` o a `git log --oneline`.


### Paso 4: Reconstruir

Usa `git rebase` (no `git merge`) para sincronizar tu trabajo de vez en cuando.

```text
$ git fetch upstream
$ git rebase upstream/master
```


### Paso 5: Prueba

 Es necesario  **incluir pruebas** cuando se reparan bugs y otras funciones. Agrega tus pruebas en el directorio de prueba de cada microservicio afectado. Revisa otras pruebas para ver cómo deben estructurarse. 

```text
$ npm test
```

Make sure the linter is happy and that all tests pass.  Please, do not submit
patches that fail either check. *

puedes llevar a cabo pruebas individuales en el laboratorio:

```text
$ ./node_modules/.bin/lab test/lib/test-user-data.js
```

### Pase 6: Ejecutar

```text
$ git push origin my-feature-branch
```

Ve a https://github.com/yourusername/<zen-repo> y selecciona tu área.
Haz click en 'Pull Request' y completa el formulario.

Revisamos las solicitudes en unos días. Si quieres realizar comentarios,
aplica los cambios en un reporte aparte y envíalos a tu área.
Publica comentarios en la solicitud después.
GitHub no envía notificaciones cuando añades reportes.


## Certificado del Programador 1.0

Al contribuir certifico que:

* (a) Yo realicé (parcial o completamente) la contribución y
tengo el derecho de enviarla bajo la licencia del recurso
público indicada en este archivo; o
* (b) La contribución está basada en trabajo anterior
con mi conocimiento, está bajo la licencia del recurso público
correspondiente y tengo el derecho de (bajo esa licencia,
excepto tenga permiso de usar otra) de enviar ese trabajo 
con modificaciones parciales o totales hechas por mí; o
* (c) Otra persona que certificó (a), (b) o (c)
* me proporcionó la contribución y no la he modificado.


## Código de Conducta

Este código ha sido adaptado de [Rust's wonderful
CoC](http://www.rust-lang.org/conduct.html).

* Estamos comprometidos a proveer un ambiente amigable y seguro
para todos, sin importar el sexo, la orientación sexual,
las discapacidades, la etnia, la religión u otras características
personales similares.
* Evita utilizar abiertamente apodos sexuales o que puedan menoscabar
el ambiente amigable, seguro y tolerante para todos.
* Por favor sé amable y cordial. No es necesario ser agresivo o grosero.
* Respeta el hecho de que las personas difieren en sus opiniones
y que diseñar e implementar elecciones acarrea cambios y costos.
Rara vez hay una respuesta correcta.
* No realices críticas que no sean constructivas. Si tienes ideas
sólidas con las que quieres experimentar, haz un esfuerzo y
observa cómo funcionan.
* Serás excluido de la interacción si insultas, degradas o 
acosas a cualquier persona. No toleramos ese comportamiento. 
Interpretamos el término "acoso" según la definición el
[Código de Conduta](http://citizencodeofconduct.org/);
si no comprendes el concepto, por favor revisa la definición.
Particularmente, no toleramos que se excluya a personas en grupos
socialmente marginalizados.
* El acoso privado no es aceptable. No importa quien seas, si sientes
que algún miembro de la comunidad te acosa o te hace sentir incómodo,
por favor comúnicate a través de algún canal o con cualquier miembro
de TC de inmediat con alguna captura (foto, email) del acoso en lo posible.
Ya seas un colaborador habitual o un nuevo miembro, nos importa
que la comunidad sea un lugar seguro para ti y te apoyaremos.
* Del mismo modo, cualquier spamming, trolling, flaming, baiting
u otras formas de llamar la atención son intolerables.
*Evita utilizar pronombres personales en los comentarios del código
o en la documentación. No es necesario mencionar personas cuando
expliques el código.
