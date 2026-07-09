# 10 - Gestión de Riesgos de Seguridad de la Información

---

## Conceptos Clave

Los riesgos de seguridad deben identificarse basados en las **vulnerabilidades y amenazas** que afectan a cada activo de información.

| Concepto | Definición |
|----------|------------|
| **Vulnerabilidad** | Debilidades, condiciones o factores que tenemos o no controlamos y cuya explotación puede implicar una amenaza |
| **Amenaza** | Causa potencial de un incidente no deseado que puede ocasionar daño a un sistema u organización — es la posible causa de materialización de un riesgo *(ISO 27001:2018)* |
| **Riesgo** | Lo que le puede ocurrir a la organización; el daño que se puede causar si se explota una amenaza |

> La sola presencia de una vulnerabilidad **no causa daños por sí misma** — es necesario que exista una amenaza que la explote. Cada tipo de activo puede verse afectado por diferentes tipos de riesgos.

---

## Ejemplos por Tipo de Activo

*Fuente: Modelo de Gestión de Riesgos de Seguridad MGRS – MINTIC Colombia*

| Tipo de Activo | Amenaza | Vulnerabilidad | Riesgo |
|----------------|---------|----------------|--------|
| **Software** | Acceso no autorizado a los sistemas | Uso de versiones desactualizadas | Secuestro de información |
| **Información** | Acceso no autorizado a las bases de datos | Bases de datos no seguras | Modificación de bases de datos sin autorización |
| **Redes** | Acceso no autorizado a los sistemas | Redes no protegidas con contraseñas | Filtración y robo de información |
| **Infraestructura física** | Pérdida del suministro de energía | No se cuenta con plantas generadoras independientes | Fallas en la prestación de servicios |
| **Hardware** | Ubicación física de los equipos | Incumplimiento en el mantenimiento del sistema de información | Fallas en la prestación de servicios |
| **Información** | Transmisión de bases de datos no autorizada | No se cuenta con sistema de alertas | Copia no autorizada de información |

---

## Clases de Riesgos

*Según la Guía para la Administración del Riesgo DAFP — Colombia*

| Clase | Descripción |
|-------|-------------|
| **Estratégico** | Se asocia con la administración del negocio: misión, objetivos estratégicos, políticas y conceptualización por parte de la alta gerencia |
| **Imagen** | Relacionados con la percepción y confianza de la ciudadanía hacia la institución |
| **Operativo** | Provenientes del funcionamiento de sistemas de información, procesos, estructura organizacional y articulación entre dependencias |
| **Financiero** | Relacionados con el manejo de recursos: ejecución presupuestal, estados financieros, tesorería y bienes |
| **Cumplimiento** | Capacidad de cumplir requisitos legales, contractuales, de ética pública y compromiso con la comunidad |
| **Tecnología** | Relacionados con la capacidad tecnológica para satisfacer necesidades actuales y futuras del negocio |

---

## Gestión de Incidentes de Seguridad de la Información

Una vez identificados los riesgos, se procede a su **valoración** para definir los tipos de control y la forma de gestionar los incidentes.

**Pasos:**

1. Valorar el **riesgo inherente** (riesgo propio del negocio) de todos los activos
2. Identificar la **probabilidad de ocurrencia** y el **impacto** sobre las variables:
   - Confidencialidad
   - Integridad
   - Disponibilidad
3. Establecer los **controles** asociados para mitigar cada riesgo identificado, determinando si el control:
   - Disminuye el nivel de riesgo, o
   - Lo desplaza en el mapa de calor

**Metodologías de referencia:**

- CCN-CERT
- OWASP

---

## Referencias

*Metodologías de referencia (disponibles en [Links.md](Links.md)):*

- [OWASP Top 10 2017 — en Español (PDF)](https://wiki.owasp.org/images/5/5e/OWASP-Top-10-2017-es.pdf)
- [MAGERIT v3 — Catálogo de Elementos (CCN-CERT)](https://pilar.ccn-cert.cni.es/docman/documentos/2-magerit-v3-libro-ii-catalogo-de-elementos/file)
