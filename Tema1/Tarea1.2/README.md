# Miguel Ángel López Alfaya
## Tarea 1.2: Lenguajes de programación

### 1. ¿Qué es un lenguaje de programación?

Es un conjunto formal de reglas sintácticas y semánticas diseñado para permitir a un programador escribir instrucciones precisas que una computadora pueda interpretar y ejecutar. Actúa como una interfaz de comunicación entre el razonamiento humano y la arquitectura de hardware.

<br>

### 2. Clasificación de los lenguajes según su nivel de abstracción

* **Lenguaje Máquina (Bajo nivel):**

  * **Descripción:** Es el lenguaje nativo del procesador, compuesto exclusivamente por secuencias binarias (0 y 1). Depende totalmente de la arquitectura del hardware.
  * **Ejemplo:** Código binario ejecutable (`01100001 01100010`).

* **Lenguaje Ensamblador (Nivel medio/bajo):**

  * **Descripción:** Representa las instrucciones de máquina mediante mnemotécnicos (abreviaturas de texto). Sigue muy cercano al hardware, pero es legible por humanos.
  * **Ejemplo:** `Assembly` (x86/ARM), usando comandos como `MOV`, `ADD`, `PUSH`.

* **Lenguajes de Alto Nivel:**

  * **Descripción:** Ofrecen un alto grado de abstracción del hardware, utilizando sintaxis cercana al lenguaje humano (inglés) y estructuras lógicas complejas. Son independientes de la plataforma.
  * **Ejemplo:** `Java`, `Python`, `C++`, `JavaScript`.

<br>

### 3. Clasificación de los lenguajes según su forma de ejecución

* **Compilados:**
  * **Descripción:** Un programa (compilador) traduce todo el código fuente de una sola vez a código ejecutable ejecutable directamente por el procesador antes de su ejecución.
  * **Ejemplo:** `C`, `C++`, `Rust`, `Go`.

* **Interpretados:**
  * **Descripción:** Un programa (intérprete) lee y traduce el código fuente línea por línea en tiempo real mientras se ejecuta.
  * **Ejemplo:** `Python`, `JavaScript`, `PHP`, `Ruby`.

* **Intermedios / Basados en Máquina Virtual (Híbridos):**
  * **Descripción:** El código fuente se compila a un formato intermedio de bajo nivel (bytecode) que posteriormente es ejecutado por una máquina virtual.
  * **Ejemplo:** `Java` (JVM), `C#` (.NET).

<br>

### 4. Ventajas e inconvenientes entre lenguajes interpretados, compilados y virtuales

| Tipo | Ventajas | Inconvenientes |
| :--- | :--- | :--- |
| **Compilados** | **Máxima velocidad** y rendimiento de ejecución; protección del código fuente al distribuir ejecutables binarios. | Proceso de desarrollo más lento (hay que compilar); **dependientes de la plataforma** (un binario para Windows no corre en Linux). |
| **Interpretados** | **Multiplataforma** e independientes del SO; depuración y desarrollo ágil y rápido. | **Menor rendimiento** y velocidad de ejecución; el código fuente queda expuesto. |
| **Virtuales / Híbridos** | **Portabilidad total** (*Write Once, Run Anywhere*); gestión automática de memoria y optimización en tiempo de ejecución (JIT). | Consumo adicional de memoria RAM y ligera sobrecarga inicial al arrancar la máquina virtual. |

<br>

### 5. ¿Qué es el código fuente?

Es el conjunto de instrucciones, líneas de texto y declaraciones escritas por un programador utilizando un lenguaje de programación de alto o medio nivel. Es el punto de entrada antes de cualquier proceso de compilación e interpretación.

<br>

### 6. Indica qué es un compilador

Es un software especializado que toma como entrada el código fuente completo escrito en un lenguaje de alto nivel y lo traduce de forma íntegra a código objeto o binario ejecutable por la máquina objetivo.

<br>

### 7. ¿Qué es el código objeto?

Es el código resultante de la traducción previa realizada por un compilador sobre el código fuente. Aunque está expresado en lenguaje máquina o código intermedio, suele necesitar una fase de enlazado (*linker*) para convertirse en un ejecutable final (*.exe*, *.bin*).

<br>

### 8. Indica qué es un intérprete

Es un programa informático que procesa el código fuente paso a paso, traduciendo e instruyendo al sistema operativo para ejecutar cada orden de manera inmediata, sin generar previamente un archivo binario independiente.

<br>


### 9. ¿Qué es una máquina virtual?

Es un entorno de software que simula el comportamiento de un ordenador físico, proporcionando una capa de abstracción sobre el sistema operativo base sobre la cual se pueden ejecutar programas compilados a un código intermedio (*bytecode*).

<br>


### 10. ¿Qué son los bytecodes?

Es una forma de código intermedio de instrucciones optimizadas generado por la compilación de lenguajes como Java. No es código máquina puro para una CPU específica, sino un conjunto de instrucciones diseñadas para ser interpretadas o compiladas por una Máquina Virtual (como la JVM).

<br>


### 11. ¿Qué es JDK y JRE?

* **JDK (Java Development Kit):** Es el kit completo de herramientas de desarrollo necesario para programar en Java. Incluye el compilador (`javac`), utilidades de depuración, herramientas de empaquetado y el JRE.
* **JRE (Java Runtime Environment):** Es el entorno de ejecución necesario únicamente para **correr y ejecutar** aplicaciones creadas en Java. Contiene la Máquina Virtual de Java (JVM) y las librerías estándar de clases, pero **no contiene herramientas de desarrollo** ni compiladores.