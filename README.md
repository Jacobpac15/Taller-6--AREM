# Taller 6 – Checklist de Cumplimiento Normativo: GobData

> **Asignatura:** Arquitectura Empresarial
> **Actividad:** Taller 6 – Evaluación de Cumplimiento Normativo  
> **Integrantes:** Jacobo Pacheco, Juan Diego Martinez, Santiago Navarro Cuy, David Santiago Medina

---

##  Descripción

Este repositorio contiene el checklist de cumplimiento normativo aplicado al caso base **GobData**, una plataforma estatal de atención digital donde los ciudadanos gestionan documentos, certificados, peticiones y notificaciones en línea.

El sistema procesa datos personales sensibles como números de identificación, historial clínico, direcciones y certificados digitales, por lo que está sujeto a múltiples normativas nacionales e internacionales.

---

##  Objetivo

Verificar los aspectos legales, normativos y de cumplimiento que aplican al sistema, utilizando listas de control basadas en los siguientes marcos:

| Marco normativo | Descripción |
|---|---|
| **Ley 1581 de 2012** | Protección de Datos Personales en Colombia |
| **Ley 1266 de 2008** | Habeas Data (régimen general) |
| **ISO/IEC 27001** | Gestión de Seguridad de la Información |
| **ISO/IEC 29101** | Privacy by Design |
| **Decreto 338 de 2022** | Marco de Seguridad Digital – MINTIC |

---

---

## Categorías evaluadas

El checklist cubre **9 categorías normativas**, cada una con criterios de cumplimiento, evidencia justificada y recomendaciones:

1. **Consentimiento Informado** — Ley 1581/2012, Arts. 9 y 12
2. **Habeas Data** — Ley 1266/2008 y Ley 1581/2012
3. **Seguridad de la Información** — ISO/IEC 27001
4. **Control de Acceso y Roles** — ISO 27001, Dominio A.9
5. **Retención y Disposición de Datos** — Ley 1581/2012, Art. 11
6. **Notificación de Brechas** — Ley 1581/2012, Art. 17
7. **Auditoría y Trazabilidad** — ISO 27001, Dominio A.12.4
8. **Transferencia de Datos a Terceros** — Ley 1581/2012, Arts. 17 y 26
9. **Privacidad desde el Diseño** — ISO/IEC 29101 (Privacy by Design)

---

## Resultados del análisis

| Estado | Cantidad | Porcentaje |
|---|---|---|
| ✅ Cumple | 5 | 16% |
| ⚠️ Cumplimiento parcial | 16 | 50% |
| ❌ No cumple / brecha crítica | 11 | 34% |

**Total: 32 criterios evaluados**

### Brechas de prioridad alta identificadas

- Acceso administrativo sin autenticación multifactor (MFA)
- Cuentas de ex-funcionarios activas sin proceso de offboarding
- Proveedores externos con acceso VPN permanente sin auditoría
- Backups y logs sin cifrado en reposo
- Sin mecanismo de notificación a ciudadanos afectados por brechas
- Sin canal ARCO diferenciado ni mecanismo de revocación de consentimiento

---

##  Metodología de evaluación

Cada criterio fue evaluado con base en:

- **Evidencia / Justificación:** análisis del contexto de GobData, los datos que procesa y las interacciones de la plataforma.
- **Nivel de cumplimiento:**
  - ✅ Cumple: el control está implementado y es efectivo.
  - ⚠️ Cumple parcialmente: existe el control pero presenta deficiencias o está desactualizado.
  - ❌ No cumple: el control no existe o hay una brecha crítica.
- **Recomendación:** acción concreta para remediar la brecha o fortalecer el control.

---
