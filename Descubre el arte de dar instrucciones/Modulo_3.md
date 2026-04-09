# Descubre la técnica de instrucción con algunos ejemplos
Incluir ejemplos en tu instrucción puede ayudar a un LLM ​a responder mejor a tu solicitud

 la palabra “ intento ” se utiliza a menudo como sinónimo de la palabra

​Las instrucciones de intento cero son una técnica que no proporciona ejemplos en una instrucción

el ejemplo de instrucción ofrece un solo ejemplo

“ algunos ejemplos de instrucciones ” son una técnica ​que proporciona dos o más ejemplos en una instrucción. ​

Como los ejemplos no se incluyen en las instrucciones de intento cero , ​se espera que el modelo realice la tarea ​basándose únicamente en sus datos de entrenamiento , ​y la descripción de la tarea incluida en la instrucción .

Algunos ejemplos de instrucciones pueden mejorar el rendimiento de los LLM ​proporcionando contexto adicional y ejemplos adicionales en tu instrucción. ​Estos ejemplos adicionales pueden ayudar a aclarar ​el formato deseado, fraseo o patrón general. 

no existe una regla definitiva ​para determinar el número óptimo de ejemplos que debemos incluir en una instrucción.

Algunos LLM pueden reproducir patrones precisos ​utilizando solo algunos ejemplos, mientras que otros LLM necesitan más. ​Al mismo tiempo, si incluyes demasiados ejemplos , ​las respuestas de un LLM pueden volverse menos flexibles y creativas ​y pueden reproducir los ejemplos con demasiada fidelidad.

# Técnicas para dominar tareas complejas con IA

## Instrucción de cadena de pensamiento
técnica de instrucción que consiste en pedir a un LLM que explique su proceso de razonamiento paso a paso, desde la entrada hasta la salida final. Esta técnica básicamente pide a la IA que "muestre su trabajo", haciendo que su respuesta sea más transparente y estructurada.

- "Explica tu razonamiento".
- "Ve paso a paso"

Estas adiciones indican que la IA necesita trazar su proceso de pensamiento, lo que a menudo conduce a una salida más informativa y precisa.

### Ejemplo:

Elabora una lista con viñetas en la que se describan las principales obligaciones y responsabilidades de un nuevo empleado de diseño de nivel inicial en una agencia de publicidad. Explica tu razonamiento paso a paso.

Al pedir a la IA que desglose la lógica y el razonamiento que hay detrás de las tareas que sugiere, la información que obtengas de la salida también tendrá una justificación de por qué se sugirió

## Encadenamiento de instrucciones
ayuda a abordar grandes proyectos dividiéndolos en una serie de pasos más pequeños y conectados que están todos en la misma charla.  la salida de una instrucción se utiliza como entrada para la siguiente, enlazando todas las tareas como una cadena.

1. Análisis de tareas: Empieza por dividir tu compleja tarea en una serie de pasos más pequeños y lógicos.

2. Instrucción inicial: Elabora una instrucción centrada que pida a la IA que complete solo el primer paso.

3. Flujo de entrada/salida: Utiliza la salida de la primera instrucción como contexto para la segunda instrucción. Continúa este flujo iterativo hasta completar la tarea. 

### ejemplo:
- Instrucción 1: Me voy durante 3 días a [nombre de la ciudad]. Me gusta el arte, los lugares históricos y los parques. Sugiere algunos lugares conocidos que podría visitar en mi viaje.
- Instrucción 2 (encadenada a partir de Instrucción 1): A partir de esas ubicaciones, crea un itinerario lógico, día a día, que minimice el tiempo de viaje.
- Instrucción 3 (encadenada a partir de la Instrucción 2): Para cada día del itinerario, sugiera algunos restaurantes situados cerca de cada uno de los lugares sugeridos.

## Combinar el encadenamiento de instrucciones con la cadena de pensamiento
### Ejemplo:
- Instrucción 1: Estoy organizando un club de lectura y me gustaría recibir recomendaciones de libros de fantasía para personas que son nuevas en la lectura de este género. Sugiere algunos libros que podríamos utilizar.
- Instrucción 2 (utilizando el encadenamiento de instrucciones y la instrucción de cadena de pensamiento): De esa lista, ¿puedes sugerirnos un libro si buscamos una lectura de ritmo rápido? Explica tu razonamiento.

# Limitaciones y buenas prácticas
Las herramientas de IA conversacional pueden tener dificultades para recordar el contexto de las primeras partes de la conversación a medida que la cadena de instrucciones se alarga. 

## Estrategias de solucion:
- Utiliza puntos de control: Pide periódicamente a la IA que haga un breve resumen del objetivo general.
- Trabaja en subtareas: Divide las tareas muy complejas en subtareas aún más pequeñas para poder tratar cada una como su propia cadena más corta antes de pasar a la siguiente.
- Recapitula y redirige: Si observas que una herramienta de IA se desvía del objetivo original, recapitula la información esencial y redirígela de nuevo al objetivo principal.

