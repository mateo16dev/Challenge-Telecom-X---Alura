#📊 Análisis de Churn – TelecomX

## Descripción

Análisis de la evasión de clientes (Churn) en TelecomX, identificando patrones de cancelación y variables que afectan la retención, con el fin de proponer estrategias para reducir la evasión.

---

## Estructura del repositorio
```text
📁 Challenge-Telecom-X---Alura
├──📁 Archivos Analisis/  
│   ├──TelecomX_Data.json → dataset original.
│   ├──TelecomX_diccionario.md → diccionario de variables.
│   └──TelecomX_LATAM.ipynb → notebook con el análisis completo.
└── README.md
```
## Estructura del desarrollo
```text
- Extracción
- Transformación
- Carga y análisis
- Informe final
```
---

## Herramientas y librerías

**Python 3.10**

**Google Colab**

**Librerías:**

 * **pandas** → manipulación y análisis de datos
 * **numpy** → operaciones numéricas
 * **matplotlib y seaborn** → visualización de datos
 * **json, os, requests** → carga y manejo de archivos JSON

---

## Objetivos

Comprender la distribución de churn.
Analizar la relación entre churn y variables demográficas, contractuales y de facturación.
Identificar patrones para estrategias de retención.

---

## Hallazgos Clave

Los clientes nuevos y con planes más caros presentan mayor churn.
La antigüedad es un factor importante de retención.
La facturación total es más alta en clientes que permanecen, aunque el gasto diario puede ser similar al de los que cancelan.

---

## Recomendaciones

Implementar incentivos tempranos para nuevos clientes.
Monitorear clientes con alto gasto diario y baja antigüedad.
Ajustar precios y paquetes para reducir percepción de sobrecosto.
Crear dashboards para seguimiento continuo de churn.


---
## Autor
Andres Mateo Coca Barragan

Proyecto desarrollado como parte del desafío Alura Telecom X — Especialización Data Science.

---
## Instrucciones para ejecutar el notebook
1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/mateo16dev/Challenge-Alura-Store.git
