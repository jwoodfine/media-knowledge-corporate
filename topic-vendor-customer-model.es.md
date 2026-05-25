---
schema: foundry-doc-v1
title: "Modelo Proveedor-Cliente"
slug: topic-vendor-customer-model
short_description: "Separación estructural entre PointSav Digital Systems como proveedor de tecnología y Woodfine Management Corp. como operador inmobiliario comercial y cliente tecnológico."
category: company
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-vendor-customer-model.md
cites: []
---

PointSav Digital Systems ocupa el rol de proveedor; Woodfine Management Corp. ocupa el rol de cliente. PointSav suministra servicios de plataforma tecnológica —infraestructura del registro de propiedades, portal de inversores, mantenimiento de software— y WMC dirige los requisitos de la plataforma, ostenta la custodia de los datos y es la única responsable de las decisiones de inversión y fiduciarias.

## Obligaciones del proveedor

Las obligaciones de PointSav son operativas y técnicas. El proveedor es responsable de la disponibilidad de la plataforma, la integridad del software, la seguridad informática y la consistencia de los datos del registro. PointSav no ejerce discrecionalidad sobre qué datos se almacenan, cómo se clasifican ni cómo se utilizan; esas decisiones corresponden a WMC como custodio de los datos.

PointSav no representa a WMC ante inversores ni ante organismos reguladores. PointSav no proporciona asesoramiento en materia de cumplimiento normativo, asesoramiento de inversión ni servicios fiduciarios. El ámbito del proveedor se limita al perímetro de la plataforma.

## Derechos del cliente

WMC conserva la custodia legal plena de todos los datos procesados por la plataforma. Si WMC contrata a un proveedor de tecnología diferente, los datos del registro de propiedades son portables; no permanecen en poder de PointSav. La arquitectura está diseñada para que WMC pueda reconstruir el control operativo completo del registro a partir de datos exportados, sin depender de ninguna implementación de software específica de PointSav.

WMC dirige los requisitos de la plataforma. PointSav construye y mantiene conforme a esos requisitos. El cliente determina qué hace la plataforma; el proveedor determina cómo.

## Separación de modos de fallo

En una estructura combinada —donde un proveedor de tecnología también participa en la gestión de capital— un fallo en un ámbito se amplifica hacia el otro. Una interrupción tecnológica que afecte a un operador de plataforma que también gestiona capital genera simultáneamente riesgo operativo y financiero.

La separación proveedor-cliente impide esta amplificación. Un fallo tecnológico en PointSav no afecta la titularidad legal de WMC sobre los activos ni la validez de los registros de participaciones. Un evento financiero en WMC no interrumpe la capacidad de PointSav para mantener la infraestructura de la plataforma. Los modos de fallo están estructuralmente aislados.

## No es una relación de marketing

PointSav no comercializa los productos de inversión de WMC, y WMC no promueve la plataforma tecnológica de PointSav como parte de sus comunicaciones con inversores. La relación es un contrato de servicios, no una empresa conjunta. Ninguna entidad posee participaciones en las operaciones comerciales principales de la otra.

## Véase también

- [[topic-corporate-structure|Estructura Corporativa]] — la relación de propiedad entre ambas entidades
- [[topic-technology-services|Acuerdo de Servicios Tecnológicos]] — la estructura del contrato de servicios entre PointSav y WMC
- [[topic-data-governance|Gobernanza de Datos]] — las obligaciones de custodia de datos de WMC bajo el modelo proveedor-cliente

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
