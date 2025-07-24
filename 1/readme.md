# Lenguaje WHILE con verificación automática usando Hoare Logic y Z3

## Objetivo
Diseñar un sistema simple que permita especificar, ejecutar y verificar programas escritos en un lenguaje imperativo pequeño, usando lógica de Hoare y Z3 como motor de verificación.

## Componentes
- ast.py ->
- eval.py -> 
- vcgen.py ->
- z3_solver.py ->
- main.py ->
- examples/ ->

## Conceptos aprendidos
1. Lógica de Hoare
2. Semántica operacional de lenguajes de programación
3. Generación de condiciones de verificación (VCGen)
4. Uso de SMT solvers (Z3) para probar validez lógica
5. Separación entre ejecución (semántica) y verificación (lógica)

## Alcance del proyecto
### In-Scope
- Lenguaje imperativo sencillo con:
- Variables, enteros, expresiones aritméticas
- Asignación, secuencias, condicionales
- Bucles while con invariantes dadas
- Verificación de postcondiciones usando lógica de Hoare
- Uso de Z3 para probar propiedades sobre los programas
- Interfaz de consola para cargar y verificar programas

### Out-of-Scope (para este proyecto)
- Inferencia automática de invariantes (avanzado)
- Análisis de alias, memoria dinámica, punteros
- Verificación de concurrencia o tiempo real
- Lenguaje con funciones, recursión, etc.
