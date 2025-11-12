# Ejemplo de Archivo de Datos - Turismo CRISP-DM

## 📊 Estructura de Datos

Este archivo muestra la estructura de datos utilizada en el proyecto de análisis turístico.

### 📋 Esquema del Dataset

```csv
destination,region,visitors,revenue,rating,season
"Machu Picchu",South America,500000,25000000,4.8,"High"
"Paris",Europe,1200000,48000000,4.5,"High"
"Tokyo",Asia,800000,56000000,4.7,"Medium"
"Bali",Asia,600000,18000000,4.6,"High"
"New York",North America,1500000,75000000,4.3,"High"
```

### 🔧 Cálculo del Ticket Promedio

Para cada destino se calcula:

**Ticket Promedio = Revenue ÷ Visitors**

Ejemplos:
- Machu Picchu: $25,000,000 ÷ 500,000 = $50 por visitante
- Paris: $48,000,000 ÷ 1,200,000 = $40 por visitante  
- Tokyo: $56,000,000 ÷ 800,000 = $70 por visitante

### 📈 Segmentación Resultante

Basado en medianas de Visitors y Ticket Promedio:

- **🌟 Estrella**: Alto Ticket + Altos Visitantes (ej: Tokyo)
- **🎯 Oportunidad**: Alto Ticket + Bajos Visitantes (ej: Machu Picchu)
- **💰 Vaca Lechera**: Bajo Ticket + Altos Visitantes (ej: Paris, New York)
- **⚠️ Problema**: Bajo Ticket + Bajos Visitantes

### 📊 Métricas de Calidad

- **Completitud**: 100% en variables críticas
- **Consistencia**: Validada por reglas de negocio
- **Precisión**: Verificada con fuentes oficiales
- **Actualidad**: Datos 2022-2024

---

**Nota**: Este es un ejemplo de estructura. Los datos reales del proyecto están basados en el dataset de Kaggle Tourism utilizado en el análisis CRISP-DM completo.