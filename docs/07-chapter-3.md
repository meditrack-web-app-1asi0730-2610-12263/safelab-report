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
| EP01 | Organización del laboratorio | Estructurar sedes, áreas y equipos para ubicar y gestionar recursos |
| EP02 | Gestión de inventario | Registro de productos, control de cantidades y fechas de vencimiento |
| EP03 | Monitoreo de condiciones | Supervisión de temperatura y variables ambientales en tiempo real |
| EP04 | Alertas y seguimiento | Notificación de problemas y control de acciones tomadas |
| EP05 | Historial y cumplimiento | Registro de actividades y generación de reportes para auditorías |
| EP06 | Dashboard | Visualización general del estado del laboratorio e indicadores clave |
| EP07 | Acceso de usuarios | Inicio de sesión seguro y recuperación de acceso |
| EP08 | Gestión de usuarios | Administración de usuarios y permisos dentro del sistema |
| EP09 | Configuración del sistema | Ajuste de parámetros como rangos, reglas y tipos de datos |
| EP10 | Soporte y mantenimiento | Gestión de errores y continuidad del sistema |


---

#### User Stories

| ID | Título | Descripción | Criterios de aceptación | Épica |
|----|--------|------------|--------------------------|----------|
| US01 | Registrar sede | Como usuario, deseo registrar una sede para organizar el laboratorio por ubicación | Dado datos válidos cuando guarda entonces la sede se registra | EP01 |
| US02 | Crear sala | Como usuario, deseo crear salas para ubicar equipos | Dado sede existente cuando crea entonces la sala se registra | EP01 |
| US03 | Registrar equipo | Como usuario, deseo registrar equipos de almacenamiento para gestionarlos | Dado datos válidos cuando guarda entonces el equipo se registra | EP01 |
| US04 | Asignar equipo | Como usuario, deseo asignar un equipo a una sala para ubicarlo | Dado equipo y sala cuando asigna entonces queda vinculado | EP01 |
| US05 | Ubicar equipo | Como usuario, deseo ubicar un equipo rápidamente para operarlo | Dado equipos registrados cuando busca entonces muestra ubicación | EP01 |

| US06 | Registrar producto | Como usuario, deseo registrar productos para controlar inventario | Dado datos válidos cuando guarda entonces se registra | EP02 |
| US07 | Registrar lote | Como usuario, deseo registrar lotes con vencimiento para controlarlos | Dado datos válidos cuando guarda entonces se registra lote | EP02 |
| US08 | Ver stock | Como usuario, deseo ver stock disponible para tomar decisiones | Dado productos cuando consulta entonces muestra cantidades | EP02 |
| US09 | Registrar entrada | Como usuario, deseo registrar entrada de productos para actualizar stock | Dado datos válidos cuando registra entonces aumenta stock | EP02 |
| US10 | Registrar salida | Como usuario, deseo registrar salida de productos para control | Dado datos válidos cuando registra entonces disminuye stock | EP02 |
| US11 | Ver productos por vencer | Como usuario, deseo ver productos próximos a vencer para evitar pérdidas | Dado productos cuando consulta entonces muestra próximos a vencer | EP02 |

| US12 | Ver temperatura actual | Como usuario, deseo ver la temperatura de equipos para asegurar conservación | Dado equipo cuando consulta entonces muestra temperatura | EP03 |
| US13 | Ver historial de temperatura | Como usuario, deseo revisar historial para validar estabilidad | Dado equipo cuando consulta entonces muestra historial | EP03 |
| US14 | Ver estado de monitoreo | Como usuario, deseo saber si el equipo está siendo monitoreado | Dado equipo cuando consulta entonces muestra estado | EP03 |
| US15 | Detectar condiciones anormales | Como usuario, deseo identificar condiciones fuera de rango para actuar | Dado valores cuando evalúa entonces detecta anomalías | EP03 |
| US16 | Ver gráfico de temperatura | Como usuario, deseo visualizar comportamiento en el tiempo | Dado datos cuando consulta entonces muestra gráfico | EP03 |
| US17 | Detectar pérdida de señal | Como usuario, deseo saber si un equipo deja de reportar datos | Dado equipo cuando deja de enviar entonces sistema indica falla | EP03 |

| US18 | Recibir alerta de temperatura | Como usuario, deseo recibir alertas para actuar rápido | Dado valor fuera de rango cuando ocurre entonces alerta | EP04 |
| US19 | Recibir alerta por correo | Como usuario, deseo recibir notificación por correo para enterarme | Dado alerta cuando ocurre entonces envía correo | EP04 |
| US20 | Ver alertas activas | Como usuario, deseo ver alertas para priorizar acciones | Dado alertas cuando accede entonces lista activas | EP04 |
| US21 | Atender alerta | Como usuario, deseo marcar alerta como atendida | Dado alerta cuando actualiza entonces cambia estado | EP04 |
| US22 | Registrar comentario | Como usuario, deseo documentar lo ocurrido en una alerta | Dado alerta cuando comenta entonces guarda observación | EP04 |
| US23 | Ver historial de alertas | Como usuario, deseo revisar incidentes pasados | Dado alertas cuando consulta entonces muestra historial | EP04 |
| US24 | Alertar pérdida de monitoreo | Como usuario, deseo recibir alerta si equipo deja de reportar | Dado falla cuando ocurre entonces alerta | EP04 |

| US25 | Ver historial de condiciones | Como usuario, deseo consultar historial para auditorías | Dado datos cuando consulta entonces muestra registros | EP05 |
| US26 | Ver acciones de usuarios | Como usuario, deseo ver quién hizo cambios para control | Dado acciones cuando consulta entonces muestra usuario | EP05 |
| US27 | Generar reporte | Como usuario, deseo generar reportes para revisión | Dado datos cuando genera entonces crea reporte | EP05 |
| US28 | Descargar reporte | Como usuario, deseo descargar reportes para compartir | Dado reporte cuando descarga entonces exporta archivo | EP05 |
| US29 | Garantizar integridad de datos | Como usuario, deseo confiar en que datos no se alteran | Dado registros cuando consulta entonces son inmutables | EP05 |

| US30 | Ver dashboard general | Como usuario, deseo ver estado del laboratorio | Dado datos cuando accede entonces muestra resumen | EP06 |
| US31 | Ver equipos con problemas | Como usuario, deseo identificar equipos críticos | Dado datos cuando consulta entonces muestra problemas | EP06 |
| US32 | Ver alertas en dashboard | Como usuario, deseo ver alertas rápidamente | Dado alertas cuando accede entonces se muestran | EP06 |
| US33 | Ver indicadores clave | Como usuario, deseo tomar decisiones rápidas | Dado datos cuando consulta entonces muestra métricas | EP06 |
| US34 | Ver equipos sin monitoreo | Como usuario, deseo identificar equipos sin datos | Dado equipos cuando consulta entonces indica estado | EP06 |

| US35 | Iniciar sesión | Como usuario, deseo acceder al sistema | Dado credenciales válidas cuando ingresa entonces accede | EP07 |
| US36 | Recuperar contraseña | Como usuario, deseo recuperar acceso | Dado correo cuando solicita entonces recibe enlace | EP07 |
| US37 | Cerrar sesión | Como usuario, deseo cerrar sesión | Dado sesión activa cuando cierra entonces termina | EP07 |
| US38 | Recibir correo de recuperación | Como usuario, deseo recibir correo para recuperar acceso | Dado solicitud cuando ejecuta entonces envía correo | EP07 |

| US39 | Crear usuario | Como administrador, deseo crear usuarios | Dado datos válidos cuando guarda entonces registra usuario | EP08 |
| US40 | Asignar rol | Como administrador, deseo asignar roles | Dado usuario cuando asigna entonces define permisos | EP08 |
| US41 | Editar usuario | Como administrador, deseo actualizar datos | Dado usuario cuando edita entonces guarda cambios | EP08 |
| US42 | Desactivar usuario | Como administrador, deseo restringir accesos | Dado usuario cuando desactiva entonces bloquea acceso | EP08 |

| US43 | Definir condiciones de temperatura | Como usuario, deseo establecer condiciones adecuadas | Dado valores cuando define entonces guarda reglas | EP09 |
| US44 | Definir condiciones anormales | Como usuario, deseo definir cuándo algo es incorrecto | Dado valores cuando configura entonces establece regla | EP09 |
| US45 | Aplicar condiciones por producto | Como usuario, deseo adaptar condiciones según producto | Dado producto cuando configura entonces aplica reglas | EP09 |
| US46 | Configurar notificaciones | Como usuario, deseo definir quién recibe alertas | Dado correos cuando guarda entonces quedan registrados | EP09 |

| US47 | Buscar equipo | Como usuario, deseo encontrar equipos rápidamente | Dado criterio cuando busca entonces muestra resultados | EP09 |
| US48 | Filtrar equipos | Como usuario, deseo analizar por ubicación | Dado filtros cuando aplica entonces muestra resultados | EP09 |
| US49 | Filtrar alertas | Como usuario, deseo gestionar alertas por estado | Dado filtros cuando aplica entonces lista resultados | EP09 |
| US50 | Ver equipos en estado normal | Como usuario, deseo confirmar operación correcta | Dado equipos cuando consulta entonces muestra normales | EP09 |


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
