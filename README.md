# Firefly Algorithm - Análisis Computacional del Comportamiento Colectivo

## 🎯 Objetivo
Implementar el Algoritmo de las Luciérnagas para analizar computacionalmente el comportamiento colectivo en sistemas biológicos multimodales.

## 🔬 Contexto Biológico
El algoritmo simula el comportamiento de fototaxis de luciérnagas, donde individuos se atraen mediante señales lumínicas.

## 📊 Función Multimodal
Paisaje con 3 zonas óptimas de bioluminiscencia:
- **Pico 1**: (4.0, 4.0), Intensidad: 1.0
- **Pico 2**: (-3.0, 3.0), Intensidad: 0.8  
- **Pico 3**: (2.0, -4.0), Intensidad: 0.7

## ⚙️ Configuración Experimental
- **20 luciérnagas** durante **100 generaciones**
- Espacio de búsqueda: [-8, 8] × [-8, 8]
- Parámetros: α = 0.25, β₀ = 1.0, γ = 0.15

## 📈 Resultados Principales
- **90% de convergencia** a zonas óptimas
- Distribución: 40% Pico 1, 30% Pico 2, 20% Pico 3
- Fitness final promedio: 0.71 ± 0.14

## 🚀 Cómo Ejecutar
1. Abrir `Firefly_Algorithm.ipynb` en Google Colab
2. Ejecutar todas las celdas secuencialmente
3. Los resultados se generarán automáticamente

## 👥 Autores
- **Wilmer Alexis Leal Duran** - 1005040351
- **Nelsis Cassiani**

---
*Proyecto desarrollado para el curso de Algoritmos Evolutivos y Bioinspirados*
