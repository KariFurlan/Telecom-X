# Telecom-X
Estrategia de Retension y Analisis de Churn

## Objetivo del Proyecto
El objetivo de este proyecto es analizar el comportamiento de los clientes de la compañía **TelecomX** para identificar las causas principales de la evasión (**Churn**). Utilizando técnicas de limpieza de datos y visualización avanzada, se proponen soluciones estratégicas para reducir la pérdida del 26.5% de la cartera de clientes.

## Desafíos Técnicos Superados
Durante el desarrollo, se implementó un pipeline de datos robusto que incluyó:
* **Manejo de JSON Complejos:** Normalización de datos anidados mediante `pd.json_normalize` para estructurar información de clientes, servicios y cuentas.
* **Limpieza y Calidad:** Resolución de valores nulos en cargos totales y conversión de tipos de datos para cálculos estadísticos.
* **Ingeniería de Variables:** Creación de la métrica `Cuentas_Diarias` para entender el impacto del gasto diario en la lealtad del usuario.

## Hallazgos de Alto Impacto (Insights)

A partir del análisis de datos, se identificaron cuatro pilares fundamentales que explican la evasión:

* **Tipo de Contrato:** Los contratos **"Mes a mes"** presentan la mayor tasa de fuga. Debido a la falta de compromiso a largo plazo, este factor se clasifica como un **riesgo crítico**.
* **Antigüedad del Cliente:** El abandono ocurre mayoritariamente durante los **primeros 6 meses**. Esto indica un **riesgo alto de fuga temprana**, sugiriendo que la experiencia inicial es determinante.
* **Tecnología de Conexión:** Los clientes de **Fibra Óptica** generan mayores ingresos pero muestran una rotación más alta. Esto representa un **riesgo medio**, posiblemente ligado a la relación precio-calidad.
* **Sensibilidad al Precio:** Existe una correlación directa: a mayor **cargo mensual**, mayor probabilidad de **Churn**. Los clientes de alto valor son, paradójicamente, los más volátiles.

## Recomendaciones Estratégicas
1. **Incentivos de Migración:** Campañas para convertir clientes de planes mensuales a anuales mediante descuentos progresivos.
2. **Onboarding de 90 días:** Reforzar el soporte técnico en los primeros 3 meses para reducir la fuga temprana.
3. **Revisión de Tarifa Fibra Óptica:** Evaluar la competitividad de precios del servicio de fibra para retener a los clientes de alto gasto.
4. **Fomento de Pago Automático:** Bonificar el cambio de cheque electrónico a métodos de pago automáticos para reducir la fricción.


Realizado por Karina Furlan - 2025

