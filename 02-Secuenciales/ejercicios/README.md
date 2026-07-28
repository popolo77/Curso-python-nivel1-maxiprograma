# 🏋️‍♂️ Ejercicios Resueltos - Bloque 2: Secuenciales

Acá tenés el código formateado de los tres ejercicios (2, 3 y 4) listo para copiar y reemplazar dentro de tu archivo **`02-Secuenciales/ejercicios/README.md`**:

```markdown
# 🏋️‍♂️ Ejercicios Resueltos - Bloque 2: Secuenciales

## 2. Elevar al cubo

*Consigna:* Hacer un programa para solicitar por teclado un número y luego devolver su valor elevado al cubo.

```python
n1 = int(input("Ingrese su número: "))
cubo = n1 * n1 * n1

print("Su número elevado al cubo es:", cubo)

```

---

## 3. Tiempo estimado de viaje

*Consigna:* Hacer un programa que permita ingresar los kilómetros existentes entre dos ciudades y la velocidad promedio de un vehículo. Calcular y emitir por pantalla el tiempo aproximado.

```python
distancia = float(input("Ingrese los kilómetros entre ambas ciudades: "))
velocidad = float(input("Ingrese la velocidad promedio (km/h): "))

tiempo = distancia / velocidad

print("El tiempo estimado de viaje es de:", tiempo, "horas.")

```

---

## 4. Sueldo total con comisión

*Consigna:* Hacer un programa para ingresar el sueldo fijo de un empleado y el monto total de sus ventas. Calcular y emitir el sueldo total a cobrar sabiendo que cobra un 5% de comisión sobre sus ventas.

```python
sueldo_fijo = float(input("Ingrese el sueldo fijo: "))
total_ventas = float(input("Ingrese el monto total de ventas: "))

comision = total_ventas * 0.05
sueldo_total = sueldo_fijo + comision

print("El sueldo total a cobrar es de: $", sueldo_total)

```

