# Miguel Ángel López Alfaya <BR> 1-DAW

## Tarea 1.4. índices de los lenguajes de programación. Depurador

## >**1. Observa todos los índices de los lenguajes de programación más usados**


   ### - **1.1 ¿Por qué crees que es importante conocer estos índices?**
   
  Creo que es fundamental porque, al fin y al cabo, cuando termine el grado voy a meterme de lleno en el mundo laboral. Si bien es cierto que a nivel personal hay que usar el lenguaje con el que uno esté más cómodo o que más le guste, me parece un error absoluto ignorar cuáles son los más demandados por las empresas. Estos índices son una brújula para saber hacia dónde se mueve el mercado de trabajo y dónde van a estar las oportunidades reales de empleo.

<br>

   ### - **1.2 Crees que es importante para tu profesión conocer estos índices. Justifica tu respuesta**

   Sí, totalmente. Viniendo de ASIR y metiéndome ahora de lleno en el desarrollo con 28 años, tengo claro que no puedo permitirme estudiar a ciegas. Conocer estos índices me ayuda a enfocar mis esfuerzos en tecnologías que realmente tienen tracción industrial. No se trata solo de aprender a programar, sino de adquirir competencias que las empresas estén buscando activamente para poder integrarme en el mercado laboral con garantías.
   Por otro lado, ante fenómenos actuales como el vibecoding o la costumbre de copiar y pegar código generado por IA directamente en los sistemas de una empresa, creo que nos estamos precipitando. Eso puede parecer que funciona a corto plazo, pero a largo plazo genera problemas y fallos muy difíciles de resolver si no hay detrás un profesional consciente con criterio que entienda realmente lo que se está ejecutando. Por eso, conocer el mercado y dominar las bases te asegura no ser un simple 'copia y pega', sino un desarrollador preparado.

<br>

   ### - **1.3 Con la clasificación actual, opina sobre los lenguajes de programación usados en el ciclo.**

   En cuanto a los lenguajes que solemos ver en el ciclo (centrados principalmente en **Python y Java**), creo que son una combinación muy acertada.

   Por un lado, **Python** me parece especialmente interesante por el tema del auge de la IA, ya que las empresas quieren incorporarla a sus sistemas de trabajo y es la gran novedad. Además, tiene una curva de aprendizaje muy suave, lo que lo hace perfecto para aquellos que no estén familiarizados de primeras con la lógica de la programación. Bajo mi punto de vista, una vez que dominas las bases y la lógica con Python en este curso, cambiar a otros lenguajes es mucho más fácil, ya que al final se reduce a cambiar la nomenclatura aplicando los conceptos que ya conoces.

<br>

## > **2.  Utilidad de un depurador/debugger**

   - Un **depurador** (debugger) es una herramienta específica facilitada por los Entornos de Desarrollo Integrados (EDIs) diseñada fundamentalmente para la detección, verificación y corrección de errores, especialmente los errores lógicos y de ejecución.

     Su utilidad práctica radica en lo siguiente:

     - **Trazado del programa**: Permite ejecutar el código sentencia a sentencia para seguir de cerca el flujo de ejecución.  

     - **Inspección de datos**: Facilita visualizar el contenido de las variables y las direcciones de memoria en tiempo real mientras el programa corre.   

     - **Modificación del comportamiento**: Permite alterar el flujo de ejecución, cambiar los valores de las variables sobre la marcha e introducir puntos de parada para diagnosticar fallos que el compilador no puede detectar por tratarse de problemas de lógica y no de sintaxis. 

<br>

## > **3. Punto de ruptura en un depurador. Indica qué es y qué permite hacer**

   - **¿Qué es?**

     Un **punto de ruptura** (o punto de parada) es una marca que se configura en un punto determinado del código para detener la ejecución de la aplicación en esa línea concreta.   

   - **¿Qué permite hacer?**
   
     Permite que el depurador **detenga el programa de forma controlada** —bien de manera directa o bajo ciertas condiciones (punto de ruptura condicional)— para que, durante esa interrupción, el usuario pueda realizar las siguientes acciones:   
   
     - **Examinar y modificar**: Consultar y alterar el estado de la memoria, los valores de las variables y el contenido de los registros del procesador.   

     - **Analizar la pila de llamadas**: Revisar la secuencia de llamadas que han desembocado en la situación actual del programa.   

     - **Controlar la ejecución detallada**: Continuar ejecutando el código instrucción a instrucción, saltar al interior de funciones específicas o cambiar el punto exacto de reanudación de la ejecución. 
