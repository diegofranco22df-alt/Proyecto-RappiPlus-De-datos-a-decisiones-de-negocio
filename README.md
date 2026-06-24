# Proyecto_RappiPlus:_De_datos_a_decisiones_de_negocio

RappiPlus es un servicio de suscripción dentro del ecosistema de Rappi diseñado para aumentar la frecuencia de compra y el valor generado por usuario.

Este repositorio contiene un análisis para entender el desempeño del servicio y detectar oportunidades concretas de mejora.

## 🧠 Objetivo del análisis

El objetivo del proyecto es responder las siguientes preguntas:

- ¿Podemos confiar en los datos?
- ¿Estamos ganando dinero?
- ¿Dónde se pierden los usuarios?
- ¿Los usuarios regresan?
- ¿Los cambios generan impacto?
- ¿Cómo comunicamos los hallazgos?

El proyecto incluye 7 datasets:

- rappiplus_orders_raw.csv → Cada fila representa un pedido realizado en la plataforma.
- rappiplus_catalog.csv → Cada fila representa un producto disponible en la plataforma.
- rappiplus_marketing_spend.csv → Cada fila representa una inversión en marketing realizada en un país y canal específico.
- events.csv → La tabla contiene información del comportamiento de los usuarios dentro de la plataforma.
- Tabla users → Información de registro de usuarios.
- Tabla user_activity → Actividad de los usuarios después del registro.
- datasets/experiment_checkout_ui.csv → Cada fila representa la participación de un usuario en un experimento (A/B testing).
  

## 📂 Contenido del repositorio

- `Proyecto_Rappiplus.ipynb`
→ Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/diegofranco22df-alt/Proyecto-RappiPlus-De-datos-a-decisiones-de-negocio/blob/main/S12%20Proyecto_Rappiplus.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `Proyecto_Rappiplus.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## Etapas de análisis realizadas

- Preparación y calidad de datos con Python.
- Análisis de rentabilidad del negocio con Python.
- Análisis del funnel de conversión con SQL.
- Análisis de retención por cohortes con SQL.
- Evaluación de impacto (experimentación A/B) con Python.
- Construcción del dashboard en Power BI y comunicación de insights.
  
