# 🏋️‍♂️ Ejercicios Resueltos - Bloque 2: Secuenciales

## 1. Suma de dos números

*Consigna:* Hacer un programa para solicitar dos números enteros por teclado y luego emitir por pantalla el resultado de la suma de ambos.

```python
n1 = int(input("Ingrese el primer número: "))
n2 = int(input("Ingrese el segundo número: "))

suma = n1 + n2

print("El resultado de la suma es:", suma)

```

---

## 2. Elevar al cubo

*Consigna:* Hacer un programa para solicitar por teclado un número y luego devolver su valor elevado al cubo.

*Nota: no olvides que sólo contamos con las cuatro operaciones básicas.*

```python
n1 = int(input("Ingrese su número: "))
cubo = n1 * n1 * n1

print("Su número elevado al cubo es:", cubo)

```

---

## 3. Calcular edad

*Consigna:* Hacer un programa que permita ingresar el año actual y el año de la fecha de nacimiento de una persona y luego calcule y emita por pantalla su edad.

*Nota: no hay que tener en cuenta si la persona cumplió años o no, simplemente calcular.*

```python
anio_actual = int(input("Ingrese el año actual: "))
anio_nacimiento = int(input("Ingrese su año de nacimiento: "))

edad = anio_actual - anio_nacimiento

print("Su edad aproximada es de:", edad, "años.")

```

---

## 4. Tiempo estimado de viaje

*Consigna:* Hacer un programa que permita ingresar los kilómetros existentes entre dos ciudades y la velocidad promedio de un vehículo. Calcular y emitir por pantalla el tiempo aproximado que demandará llegar de un punto a otro teniendo en cuenta los datos ingresados.

```python
distancia = float(input("Ingrese los kilómetros entre ambas ciudades: "))
velocidad = float(input("Ingrese la velocidad promedio (km/h): "))

tiempo = distancia / velocidad

print(f"El tiempo estimado de viaje es de: {tiempo} hs")

```

