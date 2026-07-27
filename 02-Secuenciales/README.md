# 🔢 Bloque 2: Estructuras Secuenciales

En este bloque aprendemos las bases del pensamiento algorítmico y las estructuras secuenciales en Python: cómo fluye la información en un programa, la representación con diagramas de flujo, la gestión de memoria mediante variables, los tipos de datos primitivos y el esquema **Entrada -> Proceso -> Salida**.

---

## 📖 1. El Esquema Básico de todo Programa

Todo programa o algoritmo opera bajo un ciclo fundamental:

```text
  [ ENTRADA (Datos) ]  ──>  [ PROCESO (Fórmulas / Algoritmo) ]  ──>  [ SALIDA (Información) ]

```

* **Entrada:** Recolección de los datos de inicio (ej: pedir valores por consola mediante `input()`).
* **Proceso:** Aplicación de operaciones matemáticas, lógicas o transformaciones sobre los datos.
* **Salida:** Muestra del resultado transformado en información útil (ej: imprimir por pantalla con `print()`).

> 💡 **Dato vs. Información:**
> Un **Dato** es un símbolo sin significado propio (ej: `10`). La **Información** es el resultado de procesar esos datos y otorgarles un contexto/sentido (ej: `"El sueldo final es $10"`). El fin del software es **transformar datos en información**.

---

## 📖 2. Diagramas de Flujo y Pensamiento Algorítmico

Un **Diagrama de Flujo** es la representación gráfica de un algoritmo secuencial. Nos ayuda a modelar la solución lógica antes de escribir código.

### Simbología Principal:

* **Óvalo / Óvalo estirado:** Inicio / Fin del algoritmo.
* **Paralelogramo:** Entrada / Salida de datos (lectura o impresión).
* **Rectángulo:** Proceso / Asignación de variables / Cálculos matemáticos.
* **Flechas:** Flujo de ejecución secuencial (de arriba hacia abajo).

---

## 📖 3. Variables y Memoria RAM

Una **variable** es un espacio reservado en la memoria RAM para alojar un valor temporalmente durante la ejecución del programa.

### Analogía con la Memoria:

Imagina la memoria RAM como una planilla llena de celdas. En lugar de usar direcciones físicas complejas, les asignamos un **nombre representativo** (identificador) a cada celda (ej: `numero1`, `sueldo_final`).

### ⚠️ Reglas para Nombrar Variables (Identificadores):

1. No pueden comenzar con números (ej: `1numero` ❌).
2. No pueden ser únicamente números (ej: `100` ❌).
3. No pueden contener caracteres especiales ni operadores (ej: `num*1`, `suma+1` ❌).
4. No pueden ser **palabras reservadas** del lenguaje (ej: `print`, `input`, `int` ❌).
5. Se recomienda usar la convención **snake_case** (ej: `precio_unitario`).

---

## 📖 4. Tipos de Datos Primitivos en Python

Python es de **tipado dinámico** (detecta el tipo de dato automáticamente según el valor asignado).

| Tipo | Clase en Python | Descripción | Ejemplos |
| --- | --- | --- | --- |
| **Enteros** | `int` | Números sin parte decimal (positivos, negativos o cero). | `10`, `-5`, `0`, `2026` |
| **Decimales** | `float` | Números con punto flotante. Usa punto (`.`), no coma. | `3.14`, `199.99`, `-0.5` |
| **Cadenas** | `str` | Texto encerrado en comillas simples (`'...'`) o dobles (`"..."`). | `"Hola"`, `"Mariano"`, `"123"` |
| **Booleanos** | `bool` | Estados de verdad (`True` o `False`). Primera letra en mayúscula. | `True`, `False` |

---

## 📖 5. Operadores Aritméticos y Asignación

### Operadores Básicos:

* **`+`** : Suma (o concatenación en cadenas).
* **`-`** : Resta.
* **`*`** : Multiplicación.
* **`/`** : División (devuelve un decimal `float`).
* **`//`**: División entera.
* **`%`** : Módulo (resto de la división).
* **`**`**: Potenciación.

### El Operador de Asignación (`=`):

El signo `=` **NO significa igualdad matemática**, sino **asignación**: evalúa lo que está a la derecha y lo guarda en la variable de la izquierda.

```python
edad = 25              # Asigna el valor 25 a la variable 'edad'
resultado = edad + 5   # Suma 25 + 5 y asigna 30 a 'resultado'

```

---

## 📖 6. Entrada / Salida y Conversión de Tipos (Casteo)

### Captura con `input()`:

La función `input()` **siempre devuelve un `str` (cadena de texto)**. Para operar matemáticamente debemos realizar la conversión explícita (*casteo*).

```python
# ❌ ERROR COMÚN: Concatenará texto ("10" + "5" = "105")
# n1 = input("Ingresá un número: ")
# n2 = input("Ingresá otro: ")

# ✅ CORRECTO: Casteo a entero (int) o flotante (float)
n1 = int(input("Ingresá un número entero: "))
n2 = float(input("Ingresá un número decimal: "))

```

### Funciones Útiles:

* **`type(variable)`**: Muestra el tipo de dato actual almacenado en la variable.
* **`int(valor)`**: Convierte a entero.
* **`float(valor)`**: Convierte a decimal.
* **`str(valor)`**: Convierte cualquier valor a cadena de texto.

---

## 💻 Patrón Estándar de Código Secuencial

```python
# 1. ENTRADA DE DATOS (Con casteo incluido)
num1 = int(input("Ingrese el primer número: "))
num2 = int(input("Ingrese el segundo número: "))

# 2. PROCESO (Cálculo lógico o aritmético)
suma = num1 + num2

# 3. SALIDA DE INFORMACIÓN
print("El resultado de la suma es:", suma)

