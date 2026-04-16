# **Chapter III: Requirements Specification**
## **3.1. User Stories**
## **3.2. Impact Mapping**
## **3.3. Product Backlog**

### Enlace al Impact Map

El Impact Mapping ha sido elaborado utilizando la herramienta Miro. Puede acceder al tablero en el siguiente enlace:

https://miro.com/app/board/uXjVGhw33Ew=/?share_link_id=417296329604



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

| ID | Título | Descripción | Criterios de aceptación | Épica |
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


### HU01 - Listar productos

<table>
<tr>
<td><b>Número:</b></td>
<td>HU01</td>
<td><b>Usuario:</b></td>
<td>Administrador</td>
</tr>

<tr>
<td><b>Nombre HU:</b></td>
<td colspan="3">Listar productos</td>
</tr>

<tr>
<td><b>Prioridad en el negocio:</b></td>
<td colspan="3">Alta</td>
</tr>

<tr>
<td><b>Programador responsable:</b></td>
<td colspan="3">Por definir</td>
</tr>

<tr>
<td><b>Descripción:</b></td>
<td colspan="3">
Como administrador, quiero listar los productos médicos para tener control del inventario
</td>
</tr>

<tr>
<td><b>Criterios de aceptación:</b></td>
<td colspan="3">

<b>Escenario 1: Visualización de productos registrados</b><br>
Dado que el administrador ha registrado uno o más productos<br>
Cuando accede a la sección de inventario<br>
Entonces el sistema muestra el listado de productos registrados<br><br>

<b>Escenario 2: Lista vacía</b><br>
Dado que no existen productos registrados<br>
Cuando accede al inventario<br>
Entonces el sistema muestra un mensaje indicando que no hay productos<br><br>

<b>Escenario 3: Acceso al detalle del producto</b><br>
Dado que existen productos registrados<br>
Cuando selecciona un producto<br>
Entonces el sistema muestra el detalle del producto

</td>
</tr>
</table>


### 3.3 Product Backlog

Product Backlog para el sistema Meditrack...

<table>
    <thead>
        <tr>
            <th># Orden</th>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Story Points (1/2/3/5/8)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>US01</td>
            <td>Registrar producto</td>
            <td>Como administrador, quiero registrar productos médicos para gestionar el inventario.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>2</td>
            <td>US02</td>
            <td>Visualizar inventario</td>
            <td>Como administrador, quiero ver el listado de productos para tener control del stock disponible.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>3</td>
            <td>US06</td>
            <td>Alertar stock bajo</td>
            <td>Como administrador, quiero recibir alertas de stock bajo para evitar desabastecimiento.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>4</td>
            <td>US07</td>
            <td>Alertar productos por vencer</td>
            <td>Como administrador, quiero recibir alertas de productos próximos a vencer para evitar pérdidas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>5</td>
            <td>US08</td>
            <td>Visualizar dashboard</td>
            <td>Como administrador, quiero ver indicadores del inventario para tomar decisiones informadas.</td>
            <td>8</td>
        </tr>
    </tbody>
</table>
