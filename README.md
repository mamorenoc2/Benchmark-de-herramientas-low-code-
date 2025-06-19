# Benchmark-de-herramientas-low-code-

# **¿Qué es KNIME?**

KNIME es una herramienta de análisis y ciencia de datos que te permite crear flujos de trabajo de datos de cualquier complejidad con una programación muy accesible, sin código y de arrastrar y soltar. Las características principales de esta herramienta es que

- Es rápida de usar
- Lo pueden entender personas que son no técnicas
- Se pueden crear soluciones automatizadas y reusables
- Es low/no code, y tiene una interfaz visual que permite que sea fácil de usar

## Características del software

### Nodes:

Son la primera característica importante de la herramienta y se encarga de realizar una tarea específica en los datos, estos pueden tener cero, uno o más puertos de entrada y cero, uno o más puertos de salida, y todos estos nodos tienen un estatus que se indican en la parte inferior de este que se basa en estos 4 estados a la imágen de la derecha

![image.png](attachment:eb89f34e-d682-4f32-84d4-3896cfaaadd7:image.png)

### Workflows

Cuando se integran más de 1 nodo se obtienen los flujos de trabajo, estos pasan de derecha a izquierda y pasan por cada nodo que contenga el flujo, un ejemplo sencillo de un flujo de trabajo sería la lectura de datos y extraerlos de un archivo CSV

![image.png](attachment:16e87b1f-9fff-4c3c-bb01-5902afcd15e0:image.png)

### Fuente de datos

KNIME tiene la ventaja de que sus flujos de trabajo pueden ser reutilizables para otros flujos de trabajo, en este caso, si se quiere trabajar el mismo flujo pero con diferente fuente solo se tiene que redireccionar la nueva fuente hacia el inicio del flujo

![image.png](attachment:da55c013-4602-4795-8fb5-c78b7ef68c9c:image.png)

## Ventajas y desventajas entre ORANGE Y KNIME

### Interfaz

ORANGE = Más visual y orientado a principiantes, con un flujo de trabajo basado en widgets.

KNIME = Además del mismo enfoque de los widgets, tiene un enfoque híbrido, es decir, es posible tener scripting en Python, R, Java, etc.

---

### Curva de aprendizaje

ORANGE = Más fácil para usuarios sin programación.

KNIME = Menos intuitiva pero más potente y rápido para usuarios con conceptos de programación avanzados.

---

### **Personalización**

ORANGE = Está limitado a los widgets disponibles.

KNIME = Permite integración con código personalizado (Python, R, SQL, etc.).

---

### **Machine Learning**

ORANGE = Es bueno para algoritmos básicos (clasificación, regresión, clustering).

KNIME = Permite funcionalidades más avanzadas y se puede realizar incluso integraciones avanzadas como (DL, NLP, AutoML, etc.).

---

### **Procesamiento de Datos**

ORANGE = Básico (filtrado, transformaciones simples).

KNIME = Muy robusto (ETL avanzado, manejo de Big Data con Spark).

---

### **Visualización**

ORANGE = Excelente para gráficos interactivos, ya que contiene heatmaps, dispersión y boxplots

KNIME = Es más orientado a informes estáticos, sin embargo se puede integrar con Python/R para visualizaciones avanzadas

---

### **Comunidad y documentación**

ORANGE = Tiene una comunidad más pequeña, buena para principiantes y suele ser enfocada en educación y bioinformática.

KNIME = Tiene una comunidad más grande ya que se usa en proyectos empresariales y ciencia de datos, una documentación muy completa, con muchos ejemplos y foros activos..

---

### Versiones

ORANGE = Gratuito y open-source.

KNIME = Tiene una versión gratuita (KNIME Analytics Platform) y una versión paga (KNIME Server)
