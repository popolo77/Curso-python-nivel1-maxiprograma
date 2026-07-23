# 📚 Apuntes Teóricos - Unidad 1: Introducción a Python

En este primer bloque sentamos las bases conceptuales de la programación, el funcionamiento del lenguaje Python, su entorno de ejecución y la configuración del entorno de desarrollo con Visual Studio Code.

---

## 📖 1 a 4. Pensamiento Lógico y el Rol de la Computadora

### 1. ¿Qué es programar?
Programar es indicarle a una computadora **qué hacer**, mediante una secuencia ordenada de instrucciones lógicas. Las computadoras son máquinas extremadamente rápidas para procesar datos, pero **carecen de criterio propio**: ejecutan exactamente lo que el programador les ordena.

### 2. El Pensamiento Lógico
Para resolver un problema mediante programación, primero debemos descomponerlo en pasos finitos y bien definidos. A este conjunto de pasos se lo conoce como **Algoritmo**.

```text
  [ Problema / Datos de Entrada ]  ──>  [ Algoritmo (Lógica) ]  ──>  [ Solución / Resultado ]

```

---

## 📖 5. El Lenguaje Python

Python es un lenguaje de programación de **alto nivel**, **multipropósito** y de **sintaxis limpia**, diseñado para ser fácilmente legible por los seres humanos.

### Características Clave:

* **Alto Nivel:** Se expresa de forma muy parecida al lenguaje humano (inglés directo), abstrayéndonos del manejo complejo de la memoria física de la máquina.
* **Interpretado:** No requiere ser compilado a código máquina previo a su ejecución. Existe un programa llamado **Intérprete** que lee el código fuente línea por línea en tiempo real y lo traduce a instrucciones que la CPU pueda entender.

---

## 📖 6 a 10. Entorno de Desarrollo y Ejecución

### 1. Visual Studio Code y Terminal

Para escribir software utilizamos un **Editor de Código** (como Visual Studio Code). Para ejecutarlo, invocamos al intérprete de Python desde la terminal integrada:

```bash
# Comando para verificar que Python está instalado correctamente
python3 --version

# Comando para ejecutar un archivo de script Python
python3 nombre_archivo.py

```

### 2. La Función `print()`

Es la primera instrucción que aprendemos en Python. Su objetivo es **mostrar un mensaje en la pantalla / consola**.

#### Sintaxis:

```python
print("Texto que queremos mostrar entre comillas")

```

* **`print`**: Es el nombre de la función predefinida.
* **`()`**: Los paréntesis indican que estamos llamando/ejecutando esa función.
* **`"..."`**: Las comillas (dobles o simples) le indican a Python que el contenido adentro es un texto literal (*string*).

