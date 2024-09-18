202403121000
# Seguridad de contraseñas
#seguridad #contraseñas

Hace unos días me llegó un email de una plataforma del sector bancario, tema importante, en el que alardeaban de que, a partir de ese día, aumentaban obligatoriamente las contraseñas de sus clientes de 6 dígitos numéricos a 8 dígitos numéricos y cómo esto se traducía en un aumento en la seguridad para sus clientes.

Personalmente, esto me chirrió bastante, ya que, para empezar, que una contraseña sea sólo numérica ya me parece algo indefendible. Los números son complicados de recordar y fáciles de descifrar.

Veamos una comparación de contraseñas, si realmente esta supuesta mejora es realmente eso, una mejora de la que alardear, y cómo debemos mejorar nuestras contraseñas:

Para medir la seguridad de una contraseña voy a utilizar la web [https://www.security.org/](https://www.security.org/) que, para cada contraseña dada, nos devuelve el tiempo que se necesitaría para crackearla (adivinarla a través de programas y algoritmos especializados en esto).

Contraseña de 6 dígitos numéricos aleatorios, por ejemplo '326594':

> It would take a computer about **25 microseconds** to crack your password

Ups... mal empezamos. Solo 25 microsegundos para crackear esta contraseña, además, siendo realistas, la mayoría de personas utilizaría una serie de números relacionados con sí mismo, por ejemplo con su fecha de nacimiento, o con la de sus hijos, o su pin del móvil, para que sea más fácil de recordar. Lo que haría que prácticamente cualquier persona que nos conozca un poco o pueda sacar algo de información pública de nosotros pueda crackearla sin necesidad de hacer fuerza bruta.

Comparemos ahora con el nuevo tamaño de 8 dígitos numéricos, que supuestamente, tanto mejora nuestra seguridad.

Contraseña: '52649875' (personalmente, no recordaría esto de forma fiable ni en un mes)

> It would take a computer about **2 milliseconds** to crack your password

Vaaaaya, menuda mejora, de 25 microsegundos a 2 milisegundos, me siento mucho más seguro.

Ahora solo por diversión, veamos que pasaría si pongo una contraseña mucho más fácil de recordar, para comparar bien vamos a usar 8 dígitos, pero esta vez en lugar de números usaremos letras. Por ejemplo 'holagato':

> It would take a computer about **5 seconds** to crack your password

2.500 veces más tiempo solo por usar letras minúsculas en lugar de números. Y es mucho más sencillo recordarlo. Pero 5 segundos no nos valen, continuemos.

Ahora vamos a añadirle algunos números y caracteres especiales para ver cómo de segura sería si empiezo a complicarla y que no sea solo letras minusculas:

Usaré: 'Hola9*Gato' (10 caracteres)

> It would take a computer about **5 years** to crack your password

Que tal si la hacemos un poco más larga pero que sea fácil de recordar: 'miabuelaraimunda'

> It would take a computer about **34 thousand years** to crack your password

34.000 años, esto ya sí que podemos considerarlo un salto cualitativo. Y no me digas que no es más fácil de recordar 'miabuelaraimunda' que '52649875' o 'Hola9*Gato', y más fácil de escribir tambien.

De aquí podemos deducir que es más importante para tu seguridad la longitud de tu contraseña que la complejidad o la dificultad de recordarla.

Obviamente, seguimos teniendo el problema de que cualquiera puede saber que mi abuela se llama Raimunda, y si sabe que la quiero mucho podría adivinar la contraseña con un poco de maña y sesera, así que vamos a randomizar el tema. Para esta prueba voy a usar una frase aleatoria que me hace mucha gracia y que seguro voy a recordar. 'EsteBancoEstaOcupado'

> It would take a computer about **16 quadrillion years** to crack your password

16 cuatrillones de años, no se ni qué es eso, tendría que llamar a un divulgador científico para que me haga un croquis de cuanto es eso en mi cabeza. Por hacer un acercamiento, esto es 16.000.000.000.000.000.000.000.000 años. En comparativa, el sol tiene una edad de: 4.500.000.000 años. Yo creo que podemos decir, que esta es definitivamente una contraseña segura.

Si aún así no te fías y quieres echar algún número o carácter especial por ahí, te aconsejo unos cuantos caracteres sencillos:

- 'Ñ': Un carácter fácil para los españoles, pero que quizás no tenga en su teclado un cracker Vietnamita.
- ';' y/o ':': Cuando hay una fuga de datos normalmente estos datos terminan siendo publicados por ahí en formato CSV, este formato usa por lo general alguno de estos dos caracteres, y si nuestra contraseña lleva internamente algún ';' y/o ':' le haremos la puñeta al cracker y a cualquiera que esté por ahí copiando y pegando contraseñas para echarse unas risas.

Probemos de nuevo teniendo esto en cuenta, por ejemplo con 'Este;Banco;Esta;Ocupado:02'

> It would take a computer about **33 nonillion years** to crack your password

Yo creo que esta contraseña ya si que no nos la consigue descifrar nadie. Ni merece la pena intentar reventarla con algoritmos de fuerza bruta. Y de nuevo, sigue siendo más fácil de recordar que '52649875'.

En resumen, prioriza la longitud de tus contraseñas antes que su complejidad, hazlas fáciles de recordar y estarás mucho más protegido ante ataques de maleantes en el futuro. En el peor de los casos, darás gracias.

Por último, como nota, **no reutilices tus contraseñas**. Si usas tu contraseña del correo electrónico personal, donde tienes tus billetes de avión y los extractos del banco, para tu cuenta de Zara. El día que Zara tenga una fuga de datos y tú no te enteres podrías ponerte en un serio aprieto. Si tener una contraseña para cada cosa te parece una lata, existen programas como BitWarden, ProtonPass o KeePass que te permiten guardar todas y cada una de tus contraseñas de forma segura, y acceder a ellas desde cualquier dispositivo.