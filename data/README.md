# 📊 Información sobre Datos del Proyecto

## 🗃️ Dataset Principal

**Fuente**: Kaggle Tourism Dataset  
**Descripción**: Dataset de turismo con información de destinos, visitantes, ingresos y calificaciones

## 📋 Variables del Dataset

### Variables Principales
- **Revenue**: Ingresos totales generados por destino
- **Visitors**: Número total de visitantes por destino
- **Destination**: Nombre del destino turístico
- **Rating**: Calificación promedio del destino (escala 1-5)
- **Region**: Región geográfica del destino

### Variables Derivadas
- **Ticket Promedio**: Calculado como Revenue ÷ Visitors
- **Efficiency Score**: Métrica normalizada de eficiencia
- **Segment Classification**: Categorización en matriz 2x2

## 🔧 Preparación de Datos

### Limpieza Aplicada
1. **Tratamiento de valores faltantes**
2. **Normalización de nombres de destinos**  
3. **Validación de rangos de datos**
4. **Eliminación de duplicados**

### Transformaciones
1. **Cálculo del Ticket Promedio**
2. **Segmentación por cuadrantes**
3. **Normalización para visualización**
4. **Agregación por región**

## 📊 Calidad de Datos

- **Completitud**: >95% en variables críticas
- **Consistencia**: Validada mediante reglas de negocio
- **Precisión**: Verificada contra fuentes secundarias
- **Actualidad**: Datos del período 2022-2024

## 🔗 Notas para Replicación

Para replicar este análisis:
1. Obtener dataset similar de turismo
2. Aplicar las transformaciones documentadas en `metodologia_crisp_dm.md`
3. Utilizar Tableau Public para visualización
4. Seguir el proceso CRISP-DM documentado

**Nota**: Los datos específicos del proyecto no se incluyen por razones de privacidad, pero la metodología es completamente replicable con cualquier dataset de turismo que contenga Revenue y Visitors.