# **Descripción Del Proyecto**
El objetivo principal de este analisis fue identificar los factores mas influyentes en la cancelación de los clientes dentro de la empresa de telecomunicaciones Telecom X 
y evaluar distintos modelos de machine learning para predecir estos casos.
**Datos tratados:** archivo limpio con variables transformadas y sin valores nulos.

**Modelos aplicados:** Árbol de Decisión, Random Forest, KNN (normalizado).

**Técnica de balanceo:** undersampling para equilibrar clases.

**Métricas evaluadas:** Accuracy, Precision, Recall y F1-score.

**Evaluación:** sobre conjunto de validación (30%) estratificado.

**Antigüedad baja →** Mayor probabilidad de cancelación.

**Menor uso/facturación →** Puede reflejar menor percepción de valor.

**Alta cantidad de reclamos →** Indicador claro de insatisfacción.

**Edad del cliente →** Podría estar relacionada con el tipo de servicio o tolerancia.

**Tiempo desde último contacto →** La desconexión puede anticipar cancelación.

Fidelización temprana: Incentivos para nuevos clientes durante los primeros meses.
Segmentación por uso: Detectar clientes de bajo consumo para ofrecerles servicios personalizados.
Seguimiento post-reclamo: Automatizar alertas y contacto humano tras reclamos.
Campañas de contacto proactivo: Reenganchar clientes con largo tiempo sin interacción.
Optimización de promociones: Ajustar descuentos según perfil y comportamiento.
