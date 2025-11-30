# Proyecto de Analítica: Peru_bike (FDS-2025-2-CC52)

Este repositorio contiene el desarrollo del proyecto de Ciencia de Datos para la empresa **Peru_bike**, siguiendo la metodología estándar de la industria **CRISP-DM (Cross-Industry Standard Process for Data Mining)**.

---

## 🎯 Objetivo del Proyecto

Desarrollar un modelo de analítica de datos para **identificar el perfil de los clientes potenciales de bicicletas** y optimizar las estrategias de venta mediante un **sistema de scoring predictivo**.

---

## 👥 Integrantes del Equipo

- [Nombre del Alumno 1] - [Código de Alumno]  
- Williams Giusseppi Claros Simon - U202312907
- [Nombre del Alumno 3] - [Código de Alumno]  
- [Nombre del Alumno 4] - [Código de Alumno]  

---

## 📂 Estructura del Repositorio

El proyecto está organizado en las siguientes carpetas:

### `data/`
Contiene los datasets utilizados.
- `bike_buyers.csv`: Dataset original sin procesar.
- `bike_buyers_clean.csv`: Dataset procesado/limpio.

### `code/`
Contiene los scripts y notebooks de Python.
- `TB2.ipynb`: Notebook principal con todo el flujo de trabajo (Carga, Limpieza, EDA, Modelado).

---

## 📊 Descripción del Dataset

El conjunto de datos **bike_buyers.csv** consta de **1000 registros** y **13 variables** que describen características demográficas y socioeconómicas de los clientes.

| Variable          | Descripción                                                       |
|------------------|-------------------------------------------------------------------|
| ID               | Identificador único del cliente.                                  |
| Marital Status   | Estado civil (Married, Single).                                   |
| Gender           | Género (Male, Female).                                            |
| Income           | Ingresos anuales.                                                 |
| Children         | Número de hijos.                                                  |
| Education        | Nivel educativo.                                                  |
| Occupation       | Ocupación laboral.                                                |
| Home Owner       | Si posee vivienda propia (Yes/No).                                |
| Cars             | Cantidad de automóviles.                                          |
| Commute Distance | Distancia al trabajo.                                             |
| Region           | Región geográfica.                                                |
| Age              | Edad.                                                             |
| Purchased Bike   | **(Target)** Si compró la bicicleta (Yes/No).                     |

---

## 🚀 Conclusiones

Tras aplicar el ciclo de vida de la ciencia de datos, se llegaron a las siguientes conclusiones clave:

- **Ingresos:** Los compradores de bicicletas tienen, en promedio, mayores ingresos que los no compradores, lo que sugiere que la capacidad económica es un factor discriminante.
- **Movilidad:** Existe una relación inversa entre la posesión de autos y la compra de bicicletas; clientes con menos autos son más propensos a comprar.
- **Ubicación:** La distancia al trabajo y la región de residencia son predictores fuertes; vivir cerca del trabajo aumenta la probabilidad de compra.
- **Modelo:** Se desarrolló un modelo de **Regresión Logística** con un **AUC de 0.72**, lo que permite segmentar a los clientes con una precisión aceptable para campañas de marketing.

---

## 📄 Licencia de Uso

Este proyecto está bajo la **Licencia MIT** — mira el archivo `LICENSE` para más detalles.

---

## 📌 About

Proyecto de Ciencia de Datos para el curso de **Fundamentos de Data Science (FDS-2025-2)**. Incluye análisis exploratorio, limpieza de datos y modelado predictivo utilizando la metodología **CRISP-DM** para el caso de negocio de *Peru_bike*.
