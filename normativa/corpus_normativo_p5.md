# Corpus normativo verificado — Proyecto 5
## Dashboard de Monitoreo de Cumplimiento KYC — FinPago S.A.S. (PSPCP)

**Estado de verificación:** corpus estable.
No se identificaron modificaciones a la Res. UIF N° 200/2024 publicadas
entre diciembre de 2024 y marzo de 2026 que afecten los artículos
relevantes para este proyecto.

**Fuente de verificación primaria:** boletinoficial.gob.ar
**Fecha de última verificación:** marzo de 2026

---

## 1. Res. UIF N° 200/2024 — Norma principal aplicable a FinPago S.A.S.

**Publicación:** Boletín Oficial del 19/12/2024.
**Vigencia:** desde el 20/12/2024. Deroga la Res. UIF N° 76/2019.
**Aplicación a FinPago S.A.S.:** FinPago opera como PSPCP (Proveedor de
Servicios de Pago que ofrece Cuentas de Pago), definición contenida en
el Art. 2°, inciso q) de esta resolución. Es sujeto obligado en los
términos del Art. 20, inciso 5 de la Ley N° 25.246 y sus modificatorias.

### Artículos verificados directamente en el texto oficial

**Art. 1° — Objeto**
Establece los requisitos mínimos para la identificación, evaluación,
monitoreo, administración y mitigación de los riesgos de LA/FT/FP que
los sujetos obligados incluidos en el Art. 20, incisos 5 y 6 de la Ley
N° 25.246 deberán adoptar y aplicar.

**Art. 2°, inciso q) — Definición de PSPCP**
Define al Proveedor de Servicios de Pago que ofrece Cuentas de Pago
como el proveedor de servicios de pago que ofrece cuentas para la
realización de débitos y créditos dentro de un esquema de pago.
FinPago S.A.S. encuadra en esta definición como billetera virtual.

**Art. 2°, inciso s) — Definición de Reportes Sistemáticos**
Define a los Reportes Sistemáticos como la información que
obligatoriamente deberá remitir cada sujeto obligado a la UIF, a
través de los mecanismos informativos establecidos. Esta definición
es la base legal de la Página 3 del dashboard.

**Art. 5° — Informe técnico de autoevaluación de riesgos (RSA)**
Obliga al sujeto obligado a elaborar un informe técnico de
autoevaluación de riesgos de LA/FT/FP, actualizarlo anualmente y
enviarlo a la UIF y al BCRA, junto con la metodología y la declaración
de tolerancia al riesgo, antes del 30 de abril del año calendario
correspondiente (inciso e).

Plazos específicos para FinPago S.A.S. como sujeto obligado que no
estaba comprendido en la Res. 76/2019:

- Primer Informe de Autoevaluación de Riesgos y Declaración de
  Tolerancia al Riesgo: antes del 30 de abril de 2026.
- Primer Informe de Revisor Externo Independiente: antes del
  31 de agosto de 2026.

**Art. 6° — Declaración de tolerancia al riesgo**
El sujeto obligado debe realizar una declaración de tolerancia al riesgo,
aprobada por el órgano de administración o máxima autoridad, y enviarla
a la UIF y al BCRA antes del 30 de abril del año calendario
correspondiente, junto con el informe técnico de autoevaluación.

**Art. 8° — Políticas, procedimientos y controles de cumplimiento mínimo**
Contiene la lista de obligaciones de cumplimiento mínimo. Los incisos
directamente relevantes para el dashboard son los siguientes:

- **Art. 8°, inciso g):** Realizar una Debida Diligencia Continuada de
  todos sus clientes y mantener actualizados sus legajos. Este inciso
  es la base normativa de las columnas de vencimiento del dashboard
  (FECHA_PROX_VENCIMIENTO, ESTADO_VENCIMIENTO, PRIORIDAD_REVISION)
  y del Índice de Cumplimiento KYC de la Página 2.

- **Art. 8°, inciso k):** Establecer alertas y monitorear todas las
  operaciones y/o transacciones con un enfoque basado en riesgos.
  Este inciso es la base del indicador de alertas activas de la
  Página 1 y de la pestaña ALERTAS_ACTIVAS del archivo de datos.

- **Art. 8°, inciso l):** Analizar y registrar todas las Operaciones
  Inusuales. Complementa el sistema de alertas del dashboard.

- **Art. 8°, inciso n):** Formular los Reportes Sistemáticos a la UIF.
  Este inciso es la base normativa de toda la Página 3 del dashboard
  (Cumplimiento Regulatorio) y de la pestaña REPORTES_SISTEMATICOS
  del archivo de datos.

### Artículos del Capítulo IV — Monitoreo, análisis y reporte

La Res. UIF N° 200/2024 contiene un capítulo específico de Monitoreo,
Análisis y Reporte que regula el perfil transaccional del cliente, el
monitoreo continuo de la operatoria y los reportes sistemáticos con
sus plazos específicos (RSA anual, RTE mensual). Estos artículos
existen en el texto de la norma y son los que dan contenido técnico
a las obligaciones declaradas en el Art. 8°, incisos g), k) y n).

**Plazos de los Reportes Sistemáticos verificados para PSPCPs:**

| Reporte | Periodicidad | Plazo de presentación |
|---|---|---|
| RSA — Reporte Sistemático Anual | Anual | Del 2 de enero al 15 de marzo de cada año |
| RTE — Reporte de Transacciones con Efectivo | Mensual | Hasta el día 15 del mes siguiente al reportado |
| RMTC — Reporte mensual Tarjetas de Crédito | Mensual | No aplica a PSPCPs |

Los primeros Reportes Sistemáticos mensuales (RTE) para FinPago S.A.S.
corresponden a partir de mayo de 2025. El primer RSA corresponde al
período 2025 y debe presentarse entre el 2 de enero y el 15 de marzo
de 2026.

---

## 2. Res. UIF N° 3/2026 — Listas FPADM

**Publicación:** Boletín Oficial del 08/01/2026.
**Vigencia:** desde enero de 2026.
**Deroga:** Res. UIF N° 29/2013 en lo relativo al congelamiento
administrativo de activos por FPADM.
**Aplicación en el dashboard:** indicador de cotejo de listas en la
Página 2 (Tabla resumen cotejo OFAC/ONU/FPADM).

Establece las obligaciones, procedimientos y mecanismos operativos
aplicables al Reporte de Operaciones Sospechosas vinculadas con el
Financiamiento de la Proliferación de Armas de Destrucción Masiva (FP)
y al congelamiento administrativo de bienes y otros activos de personas
físicas y jurídicas incluidas en las listas FPADM.

El dashboard registra por cliente:
- `COTEJO_LISTAS_ULTIMO`: fecha del último cotejo realizado.
- `COTEJO_LISTAS_RESULTADO`: resultado con tres valores posibles —
  Sin coincidencia / Coincidencia parcial / Coincidencia confirmada.

Ante una Coincidencia confirmada, corresponde aplicar de inmediato
las medidas de congelamiento establecidas en esta resolución y en la
Res. UIF N° 207/2025.

---

## 3. Res. UIF N° 207/2025 — RFT (Reporte de Financiamiento del Terrorismo)

**Publicación:** Boletín Oficial, 2025.
**Vigencia:** desde abril de 2025.
**Deroga:** Res. UIF N° 29/2013 en lo relativo al RFT.
**Aplicación en el dashboard:** define la acción a disparar ante
coincidencia confirmada en el cotejo de listas de la Página 2.

Establece la obligación de congelamiento inmediato de activos ante
una coincidencia confirmada en listas RFT/OFAC/ONU, sin requerir
orden judicial previa.

**Valor diferenciador en entrevistas:** la mayoría de los candidatos
jr desconoce esta norma o la confunde con la Res. 29/2013. Su
incorporación en el dashboard y en el documento de especificación
demuestra conocimiento normativo actualizado a 2025-2026.

---

## 4. Res. UIF N° 233/2025 — Intercambio de información entre OCEs

**Publicación:** Boletín Oficial del 22/12/2025.
**Aplicación en el dashboard:** contexto normativo del cotejo de listas
y resolución de coincidencias parciales.

Regula el nuevo régimen normativo y de procedimientos para el intercambio
de información entre Organismos de Control y Supervisión (OCEs). Relevante
para el tratamiento de casos con coincidencia parcial o confirmada en
cotejo de listas FPADM, en los que puede requerirse consulta con
otros organismos.

---

## 5. BCRA Comunicación "A" 7462/2022 — Trazabilidad de operaciones

**Emisor:** Banco Central de la República Argentina.
**Aplicación en el dashboard:** trazabilidad de operaciones y requisitos
de auditoría. Complementa las obligaciones de monitoreo de la
Res. UIF N° 200/2024.

Establece requisitos de trazabilidad de operaciones y auditoría para
Proveedores de Servicios de Pago. Relevante para el indicador de
auditoría del dashboard y para justificar la conservación del historial
de alertas en la pestaña ALERTAS_ACTIVAS.

---

## Normas excluidas del portfolio — justificación

| Norma | Motivo de exclusión |
|---|---|
| Res. UIF N° 76/2019 | Derogada por la Res. UIF N° 200/2024 a partir del 20/12/2024. No aplicable. |
| Res. UIF N° 14/2023 | Marco para entidades bancarias y cambiarias. No aplicable a PSPCPs. |
| Res. UIF N° 29/2013 | Derogada parcialmente por la Res. N° 207/2025 (RFT) y la Res. N° 3/2026 (FPADM). No aplicable. |
| Res. UIF N° 30/2017 | Excluida explícitamente de todos los proyectos del portfolio FinPago. |

---

## Nota metodológica

Los artículos de la Res. UIF N° 200/2024 referenciados en
este documento (Arts. 1° al 16°)  verificados directamente en el
texto del Boletín Oficial
(boletinoficial.gob.ar/detalleAviso/primera/318446/20241219).


---

> Este documento fue elaborado con fines exclusivamente educativos
> y de portfolio profesional. FinPago S.A.S. es una entidad ficticia.
> Ver DISCLAIMER.md.