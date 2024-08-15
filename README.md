# APAV - Algoritmo para Perímetros, Áreas y Volúmenes

## Descripción

El **Algoritmo para Perímetros, Áreas y Volúmenes (APAV)** es una herramienta desarrollada en Python para calcular perímetros, áreas y volúmenes de figuras geométricas planas y sólidos regulares. Además, incluye una solución alternativa para estimar el volumen de sólidos irregulares mediante métodos de integración numérica. Este algoritmo es modular y se puede adaptar a diversas aplicaciones matemáticas y de ingeniería.

## Características

- **Perímetro y Área**:
  - Cuadrado
  - Círculo
  - Rectángulo
  - Triángulo
- **Volumen y Área**:
  - Cubo
  - Esfera
  - Cilindro
- **Solución Alternativa**:
  - Estimación de volúmenes de sólidos irregulares mediante integración numérica

## Instalación

Para utilizar este algoritmo, asegúrate de tener Python instalado en tu sistema. Puedes instalar las dependencias necesarias ejecutando:

```bash
pip install numpy

**Uso
Aquí hay ejemplos de cómo utilizar el algoritmo:**

import math
import numpy as np
from apav import *

# Ejemplos de uso

# Figuras Planas
print("Perímetro del cuadrado:", perimeter_square(5))
print("Área del cuadrado:", area_square(5))

print("Perímetro del círculo:", perimeter_circle(3))
print("Área del círculo:", area_circle(3))

print("Perímetro del rectángulo:", perimeter_rectangle(4, 6))
print("Área del rectángulo:", area_rectangle(4, 6))

print("Perímetro del triángulo:", perimeter_triangle(3, 4, 5))
print("Área del triángulo:", area_triangle(3, 4))

# Sólidos Regulares
print("Volumen del cubo:", volume_cube(3))
print("Área del cubo:", area_cube(3))

print("Volumen de la esfera:", volume_sphere(4))
print("Área de la esfera:", area_sphere(4))

print("Volumen del cilindro:", volume_cylinder(3, 7))
print("Área del cilindro:", area_cylinder(3, 7))

# Volumen de un sólido irregular
def example_solid(x):
    return np.sin(x) + 2

volume_irregular = volume_irregular_solid(example_solid, 0, math.pi)
print("Volumen estimado del sólido irregular:", volume_irregular)

**Contribuciones
**Las contribuciones son bienvenidas. Si deseas contribuir a este proyecto, por favor realiza un fork del repositorio, realiza tus cambios y envía un pull request.

**Licencia
**Este proyecto está licenciado bajo la Licencia MIT.

**Contacto
**Para preguntas o comentarios, por favor contacta a: esoporteingenieria2020@gmail.com

Este archivo `README.md` proporciona una visión general clara del proyecto, instrucciones de instalación, ejemplos de uso y detalles sobre cómo contribuir. Puedes ajustar la información según sea necesario para adaptarla a tus necesidades específicas.
