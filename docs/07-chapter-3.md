# **Chapter III: Requirements Specification**
## **3.1. User Stories**
## **3.2. Impact Mapping**
## **3.3. Product Backlog**


## **3.1 User Stories**

En esta sección se presentan los requisitos funcionales del sistema Meditrack definidos mediante User Stories y agrupados en Epics a partir del análisis realizado en el Capítulo II.

#### Epics

| Epic ID | Título | Descripción |
|--------|--------|------------|
| EP01 | Gestión de productos | Registro y administración de medicamentos |
| EP02 | Gestión de stock | Control de entradas y salidas |
| EP03 | Sistema de alertas | Notificaciones de riesgos |
| EP04 | Dashboard | Visualización de indicadores |


---

#### User Stories

| ID | Título | Descripción | Criterios de Aceptación | Relación |
|----|--------|------------|--------------------------|----------|
| US01 | Registrar producto | Como administrador, deseo registrar productos para gestionar el inventario | Dado datos válidos cuando guarda entonces el sistema registra correctamente | EP01 |
| US02 | Editar producto | Como administrador, deseo modificar productos para mantener información actualizada | Dado producto existente cuando edita entonces el sistema actualiza | EP01 |
| US03 | Eliminar producto | Como administrador, deseo eliminar productos para depurar el sistema | Dado producto existente cuando elimina entonces el sistema lo remueve | EP01 |
| US04 | Ver inventario | Como administrador, deseo visualizar productos para control | Dado productos existentes cuando accede entonces se listan | EP01 |
| US05 | Buscar producto | Como administrador, deseo buscar productos para acceso rápido | Dado criterio de búsqueda cuando consulta entonces muestra resultados | EP01 |
| US06 | Registrar entrada | Como administrador, deseo registrar ingresos para actualizar stock | Dado datos válidos cuando registra entonces aumenta stock | EP02 |
| US07 | Registrar salida | Como administrador, deseo registrar consumo para control | Dado datos válidos cuando registra entonces disminuye stock | EP02 |
| US08 | Ver historial | Como administrador, deseo ver movimientos para auditoría | Dado registros cuando consulta entonces muestra historial | EP02 |
| US09 | Configurar stock mínimo | Como administrador, deseo definir límites para alertas | Dado valor definido cuando guarda entonces sistema registra límite | EP03 |
| US10 | Alertar stock bajo | Como administrador, deseo alertas para evitar desabastecimiento | Dado stock bajo cuando evalúa entonces genera alerta | EP03 |
| US11 | Alertar vencimiento | Como administrador, deseo alertas para evitar pérdidas | Dado fecha próxima cuando evalúa entonces alerta | EP03 |
| US12 | Ver alertas | Como administrador, deseo visualizar alertas para actuar | Dado alertas activas cuando accede entonces se muestran | EP03 |
| US13 | Ver dashboard general | Como administrador, deseo ver indicadores para decisiones | Dado datos cuando accede entonces muestra métricas | EP04 |
| US14 | Ver productos críticos | Como administrador, deseo identificar riesgos | Dado datos cuando accede entonces muestra críticos | EP04 |
| US15 | Ver estadísticas | Como administrador, deseo analizar datos | Dado datos cuando consulta entonces muestra gráficos | EP04 |


---


