# 🏋️‍♂️ Ejercicios Resueltos - Bloque 2: Secuenciales

### 2. Elevar al cubo
> **Consigna:** Hacer un programa para solicitar por teclado un número y luego devolver su valor elevado al cubo.

```python
n1 = int(input("Ingrese su número: "))
cubo = n1 * n1 * n1

print("Su número elevado al cubo es:", cubo)

### 4. Tiempo estimado de viaje
> **Consigna:** Hacer un programa que permita ingresar los kilómetros existentes entre dos ciudades y la velocidad promedio de un vehículo. Calcular y emitir por pantalla el tiempo aproximado.

```python
distancia = float(input("Ingrese los kilómetros entre ambas ciudades: "))
velocidad = float(input("Ingrese la velocidad promedio (km/h): "))

tiempo = distancia / velocidad

print("El tiempo estimado de viaje es de:", tiempo, "horas.")