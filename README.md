# CEDAPY_25_26

Curso especialización desarrollo aplicaciones en Python





---

### **Módulo 5098: Entornos y sintaxis en Python**

Este módulo es la **puerta de entrada al lenguaje** y se centra en proporcionar las bases fundamentales para que el alumno pueda empezar a escribir sus primeros programas. El objetivo, según el currículo, es que el estudiante se familiarice con la instalación de un entorno de desarrollo y asimile la sintaxis elemental de Python.

**Contenidos principales:**

1. **Preparación del Entorno de Desarrollo:** Se enseña al alumno a instalar y configurar las herramientas necesarias para programar. Esto incluye el intérprete de Python, un editor de código o IDE (como Visual Studio Code), y la gestión de paquetes con **pip**. También se introduce el uso de **entornos virtuales** (`venv`), una práctica esencial para aislar las dependencias de cada proyecto y evitar conflictos.

2. **Sintaxis Básica y Tipos de Datos:** Es el núcleo del módulo. Aquí el alumno aprende los "ladrillos" con los que se construye cualquier programa:
   
   - **Variables:** Cómo guardar información en la memoria del ordenador.
     
     - *Ejemplo:* `nombre_curso = "Desarrollo de aplicaciones en Python"`
   
   - **Tipos de Datos Primitivos:** Se estudian los tipos de datos básicos como los números (`int`, `float`), las cadenas de texto (`str`), y los booleanos (`bool`).
     
     - *Ejemplo:* `numero_alumnos = 20`, `nota_media = 8.5`, `curso_activo = True`
   
   - **Operadores:** Se aprenden los símbolos para realizar operaciones aritméticas (`+`, `-`, `*`, `/`), de comparación (`==`, `!=`, `>`, `<`) y lógicas (`and`, `or`, `not`).
   
   - **Entrada y Salida:** Se utilizan las funciones `print()` para mostrar información en pantalla y `input()` para solicitar datos al usuario, permitiendo crear los primeros programas interactivos.

En resumen, este módulo proporciona la base sintáctica y conceptual para que el alumno pueda leer y escribir código Python simple de forma autónoma.

---

### **Módulo 5100: Programación Orientada a Objetos (POO)**

Este módulo representa un **salto cualitativo** en la forma de programar. Una vez superada la programación estructurada (con funciones y estructuras de control), se introduce el paradigma de la Programación Orientada a Objetos (POO). El objetivo es enseñar a organizar el código de una manera que se asemeje más al mundo real, encapsulando datos y comportamientos en "objetos".

**Contenidos principales:**

1. **Clases y Objetos:** Es el concepto central. Se aprende que una **clase** es como un "molde" o una plantilla para crear **objetos**. Los objetos son las instancias concretas de esas clases.
   
   - *Ejemplo (basado en "CURSO INTENSIVO DE PYTHON")*: Se puede definir una clase `Coche` que sirva como plantilla. Luego, `mi_coche = Coche('Renault', 'Clio')` sería un objeto (una instancia) de esa clase.

2. **Atributos y Métodos:**
   
   - **Atributos:** Son las **características** o datos que describen a un objeto (las variables dentro de una clase).
     
     - *Ejemplo:* Para la clase `Coche`, los atributos podrían ser `marca`, `modelo` y `color`.
   
   - **Métodos:** Son las **acciones** o comportamientos que un objeto puede realizar (las funciones dentro de una clase).
     
     - *Ejemplo:* Un método podría ser `acelerar()` o `frenar()`.

3. **Pilares de la POO:**
   
   - **Encapsulación:** La idea de agrupar los datos (atributos) y los métodos que operan sobre ellos dentro de un mismo objeto, protegiendo la información del exterior.
   
   - **Herencia:** Permite crear una nueva clase (clase hija) que hereda todos los atributos y métodos de otra clase (clase padre), permitiendo la reutilización de código.
     
     - *Ejemplo (basado en "CURSO INTENSIVO DE PYTHON")*: Se puede crear una clase `CocheElectrico` que herede de la clase `Coche`, añadiendo atributos propios como `capacidad_bateria`.
   
   - **Polimorfismo:** La capacidad de que objetos de diferentes clases respondan al mismo mensaje (al mismo método) de formas diferentes.

Este módulo es fundamental para desarrollar aplicaciones complejas y mantenibles, ya que la POO es el paradigma dominante en la mayoría de los lenguajes de programación modernos.





---

### **Módulo 5099: Estructuras de control en Python**

Este módulo es el **corazón de la lógica de programación**. Su objetivo, según el currículo, es enseñar al alumno a controlar el "flujo" de un programa, es decir, a tomar decisiones y ejecutar acciones de forma repetitiva. Se abandona la ejecución secuencial (línea tras línea) para crear programas dinámicos e inteligentes que puedan reaccionar a diferentes situaciones.

**Contenidos principales:**

1. **Sentencias Condicionales:** Es la base de la toma de decisiones. Se enseña al programa a elegir entre diferentes caminos según se cumplan o no ciertas condiciones.
   
   - **`if`**: Ejecuta un bloque de código si una condición es verdadera.
   
   - **`elif`**: Permite comprobar condiciones adicionales si la primera es falsa.
   
   - **`else`**: Proporciona un camino alternativo a seguir si ninguna de las condiciones anteriores se cumple.
     
     - *Ejemplo práctico (conceptualizado desde "CURSO INTENSIVO DE PYTHON")*: Un programa que comprueba la edad de un usuario. Si es mayor de 18, le permite el acceso; si no, le muestra un mensaje de denegación. `if edad >= 18: print("Acceso permitido") else: print("Acceso denegado")`.

2. **Bucles o Estructuras Repetitivas:** Son la clave para la automatización. Permiten ejecutar un mismo bloque de código múltiples veces sin tener que reescribirlo.
   
   - **Bucle `for`**: Se utiliza para **iterar sobre una secuencia** de elementos (como una lista de nombres, las letras de una palabra, o una serie de números generada con `range()`). Es ideal cuando sabemos de antemano cuántas veces queremos repetir la acción.
     
     - *Ejemplo práctico (conceptualizado desde "Python a Fondo1")*: Recorrer una lista de productos y aplicarles un descuento a cada uno.
   
   - **Bucle `while`**: Repite el código **mientras una condición sea verdadera**. Es perfecto para situaciones en las que no sabemos cuántas iteraciones serán necesarias.
     
     - *Ejemplo práctico*: Un menú de un cajero automático que se sigue mostrando hasta que el usuario selecciona la opción "Salir".

3. **Control del Flujo de los Bucles:** Se aprenden sentencias para manipular el comportamiento de los bucles de forma más precisa.
   
   - **`break`**: Interrumpe y sale del bucle inmediatamente.
   
   - **`continue`**: Detiene la iteración actual y salta directamente a la siguiente.

En definitiva, al finalizar este módulo, el alumno será capaz de escribir programas que piensen, decidan y realicen tareas repetitivas de forma eficiente, sentando la base para resolver problemas de lógica complejos.

---

### **Módulo 5101: Análisis de datos con Python**

Este módulo es una inmersión directa en una de las aplicaciones más demandadas de Python: la **Ciencia de Datos**. El objetivo curricular es dotar al alumno de las competencias necesarias para manejar, procesar, analizar y visualizar grandes volúmenes de datos para extraer información de valor y conocimiento útil.

**Contenidos principales:**

1. **Ecosistema de Análisis de Datos en Python:** Se presentan las librerías fundamentales que convierten a Python en una potentísima herramienta para el análisis de datos.
   
   - **NumPy:** La librería base para la computación numérica. Introduce los arrays, que son estructuras de datos increíblemente eficientes para operaciones matemáticas.
   
   - **Pandas:** La herramienta central del módulo. Proporciona estructuras de datos de alto rendimiento, como el **DataFrame** (una tabla similar a una hoja de cálculo), que permite leer, manipular y analizar datos de forma intuitiva y potente.
   
   - **Matplotlib / Seaborn:** Librerías para la **visualización de datos**, permitiendo crear todo tipo de gráficos (barras, líneas, dispersión, histogramas) para representar la información de forma visual y comprensible.

2. **Proceso de Análisis de Datos (ETL - Extract, Transform, Load):**
   
   - **Lectura y Escritura de Datos:** Se aprende a importar datos desde diversas fuentes, como ficheros **CSV** o **Excel**, a un DataFrame de Pandas.
     
     - *Ejemplo práctico (conceptualizado desde "Introducing Python 2025")*: `datos = pandas.read_csv('ventas_trimestre.csv')`.
   
   - **Limpieza y Preparación de Datos (Data Wrangling):** Es una de las fases más críticas. El alumno aprenderá a manejar datos ausentes (`NaN`), filtrar filas o columnas según condiciones, modificar tipos de datos, y transformar la información para dejarla lista para el análisis.
   
   - **Análisis Exploratorio (EDA):** Se utilizan las herramientas de Pandas para explorar los datos, calcular estadísticas descriptivas (`.describe()`), realizar agrupaciones (`.groupby()`), y buscar patrones o correlaciones entre variables.
   
   - **Visualización de Datos:** Se aplican las librerías de visualización para crear gráficos que comuniquen los hallazgos del análisis de forma efectiva.

Al completar este módulo, el alumno podrá enfrentarse a un conjunto de datos, procesarlo, analizarlo y presentar conclusiones basadas en la evidencia encontrada, una habilidad fundamental en el mercado laboral actual.
