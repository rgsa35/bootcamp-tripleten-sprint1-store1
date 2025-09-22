# bootcamp-tripleten-sprint1-store1
Este proyecto forma parte del análisis de datos para **Store 1**, una empresa de comercio electrónico que está preparando el lanzamiento de un nuevo **Programa de Fidelización de Clientes.
Objetivos Principales

- Limpiar y estandarizar los perfiles de clientes
- Transformar y validar la consistencia de los datos
- Calcular métricas de gasto por cliente y categoría
- Preparar los datos para generar indicadores de negocio (KPIs)
- Segmentar clientes según edad, historial de compras y categorías preferidas

## 📊 Estructura de los Datos

Los datos incluyen información de 10 clientes con las siguientes variables:

- **usuario_id**: Identificador único del cliente
- **usuario_nombre**: Nombre del cliente
- **usuario_edad**: Edad del cliente
- **categorias_fav_low**: Categorías favoritas de productos
- **gasto_por_categoria**: Montos gastados por cada categoría

## 🛠️ Técnicas y Métodos Aplicados

### Limpieza y Transformación de Datos:
- **Método `.strip()`**: Eliminación de espacios en blanco en nombres
- **Método `.replace()`**: Corrección y estandarización de texto
- **Conversión de tipos**: Transformación de float a entero para edades
- **Estandarización de nombres**: Aplicación de formato Title Case

### Análisis Realizado:
- **Cálculo de gastos totales por usuario**
- **Análisis de gastos por categoría de productos**
- **Creación de cadenas formateadas** para presentación de resultados
- **Validación de consistencia de datos**

## 📁 Archivos del Proyecto

- `sprint_1_proyecto.ipynb` - Notebook principal con todo el análisis
- `README.md` - Documentación del proyecto

## 💻 Tecnologías Utilizadas

- **Python 3**
- **Jupyter Notebook**
- Métodos nativos de Python para manipulación de strings y listas

## 📈 Resultados Principales

- Datos de clientes completamente limpiados y estandarizados
- Cálculos precisos de gastos totales y por categoría
- Base de datos preparada para análisis avanzados en Sprint 2
- Identificación de patrones de consumo por categorías


## 🚀 Próximos Pasos

Este proyecto es la **Parte 1** de un análisis más amplio. En el **Sprint 2** se desarrollará:
- Análisis completo de segmentación de clientes
-  Desarrollo de estrategias de fidelización personalizadas

---
*Proyecto desarrollado como parte del programa de análisis de datos*
- Generación de insights para el equipo de marketing
