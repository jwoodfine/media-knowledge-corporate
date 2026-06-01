---
schema: foundry-doc-v1
title: "Tecnología del Registro de Propiedades"
slug: topic-property-ledger-technology
aliases:
  - topic-property-ledger-technology
short_description: "Infraestructura tecnológica subyacente a cada registro de propiedades de WMC: registro criptográfico de participaciones fraccionarias de capital, eventos del activo e historial de transferencias, mantenido por PointSav Digital Systems bajo la custodia de WMC."
category: operations
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-property-ledger-technology.md
cites: []
---

Cada activo mantenido bajo el [[topic-direct-hold-framework|Marco de Tenencia Directa]] tiene un registro de propiedades asociado. El registro es el documento autoritativo de las asignaciones fraccionarias de capital, los eventos financieros del activo y el historial de transferencias. Woodfine Management Corp. ostenta la custodia legal del registro en virtud del [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]]; PointSav Digital Systems mantiene la infraestructura técnica en su calidad de proveedor de servicios tecnológicos contratado bajo el [[topic-technology-services|acuerdo de servicios tecnológicos]].

## Qué registra el libro

El registro de propiedades recoge tres categorías de información:

**Asignaciones fraccionarias de capital.** El registro documenta quién posee qué porcentaje del activo nombrado en cada momento. La posición de cada inversor se expresa como un porcentaje de la propiedad específica —no como una participación en un fondo ni como un derecho proporcional sobre un conjunto de activos. Cada participación fraccional se constituye como una [[topic-investment-units|unidad de inversión]] en el activo nombrado.

**Eventos financieros del activo.** Las distribuciones, las transacciones de servicio de deuda, las valoraciones y otros eventos financieros que afectan al activo se registran en el libro con marcas de tiempo e importes. El registro es de solo adición para los asientos operativos; ningún registro de evento financiero anterior puede sobrescribirse.

**Historial de transferencias.** Cada transferencia de capital entre pares se registra con la marca de tiempo de la transacción y las identidades de las partes cedente y adquirente, coherente con el [[topic-equity-transfer-model|Modelo de Transferencia de Capital]]. El registro mantiene una cadena completa de titularidad desde la emisión inicial de capital del activo.

## Custodia y control

WMC ostenta la custodia legal de todos los datos del registro. PointSav mantiene la infraestructura técnica —claves privadas, hardware de servidores, pila de software— como proveedor de servicios contratado en virtud del acuerdo de servicios tecnológicos. La entidad que posee las claves privadas y opera el registro es la que ejerce el control técnico efectivo sobre el documento. WMC, como custodio legal, dirige cómo se opera la infraestructura y puede exigir la exportación de datos o la transferencia de infraestructura en cualquier momento.

## Principio de control soberano

Un propietario de inmueble que no puede acceder al registro que acredita su titularidad sobre un activo queda funcionalmente desposeído. La arquitectura está diseñada para que WMC pueda recuperar el control operativo completo del registro de forma independiente de cualquier proveedor de tecnología específico. Los datos del registro se almacenan en formatos portables; el documento no está vinculado a la implementación de software específica de PointSav.

## Mecanismos de integridad

La estructura de solo adición de los registros operativos impide la modificación retroactiva del historial de eventos financieros. Los cambios en el registro de capital —transferencias, nuevas asignaciones— requieren el protocolo de confirmación F12: una acción explícita del operador que no puede activarse automáticamente. Ningún proceso automatizado puede modificar el registro de capital sin que un operador humano autorice expresamente el cambio.

## No es un libro de contabilidad distribuido público

El registro de propiedades es un registro criptográfico mantenido por la entidad corporativa. No es una cadena de bloques pública ni un libro de contabilidad distribuido mantenido por validadores externos. La entidad corporativa es la autoridad sobre el estado del registro. Esta es una decisión de diseño deliberada: los libros de contabilidad distribuidos públicos introducen dependencias de contrapartes —redes de validadores, órganos de gobernanza de protocolos— que la arquitectura está específicamente diseñada para evitar.

## Véase también

- [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] — las obligaciones de WMC como custodio del registro de propiedades
- [[topic-data-governance|Gobernanza de Datos]] — cómo se manejan los datos personales y operativos bajo el marco de custodia de WMC
- [[topic-vendor-customer-model|Modelo Proveedor-Cliente]] — la relación de servicios bajo la cual PointSav mantiene la infraestructura técnica
- [Arquitectura del Registro WORM](https://documentation.pointsav.com/infrastructure/worm-ledger-architecture) — arquitectura subyacente del registro referenciada en este artículo

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
