---
schema: foundry-doc-v1
title: "Estructura Corporativa"
slug: topic-corporate-structure
aliases:
  - topic-corporate-structure
short_description: "Estructura de tres entidades bajo Woodfine Capital Projects Inc., que separa al proveedor de tecnología del operador inmobiliario comercial."
category: company
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-corporate-structure.md
cites: []
---

Woodfine Capital Projects Inc. es la empresa matriz de Ontario que tiene dos subsidiarias de propiedad absoluta: PointSav Digital Systems y MCorp. Las tres entidades ocupan roles distintos —propiedad, tecnología y operaciones comerciales— que no se superponen. El arreglo implementa el [[topic-vendor-customer-model|modelo proveedor-cliente]] a nivel corporativo y sustenta el [[topic-direct-hold-framework|Marco de Tenencia Directa]] bajo el cual opera WMC, con la [[topic-fiduciary-data-mandate|custodia fiduciaria de datos]] en manos de WMC y los servicios de plataforma prestados por PointSav.

## Entidad matriz

Woodfine Capital Projects Inc. está constituida en Ontario, Canadá. Es la propietaria al 100% de ambas subsidiarias y proporciona el marco de gobernanza en el que cada una opera. La entidad matriz no gestiona activos inmobiliarios ni desarrolla productos tecnológicos por sí misma. Su función es estructural: sostiene la relación de propiedad y establece el marco normativo que rige a las dos entidades operativas que dependen de ella.

## Proveedor de tecnología

PointSav Digital Systems es una subsidiaria de propiedad absoluta de Woodfine Capital Projects Inc. PointSav desarrolla y mantiene la plataforma de [[topic-property-ledger-technology|registro de propiedades]], el portal de inversores y la infraestructura de datos que utiliza el operador comercial para gestionar activos bajo el modelo de Tenencia Directa, en virtud del [[topic-technology-services|acuerdo de servicios tecnológicos]].

PointSav no posee participaciones en ninguna propiedad gestionada. PointSav no toma decisiones de inversión ni gestiona las relaciones con inversores. Su mandato se limita a la tecnología: desarrollo de plataforma, integridad del registro, seguridad informática y disponibilidad del sistema. Las decisiones de inversión y capital corresponden al operador comercial.

## Operador comercial

MCorp (Woodfine Management Corp.) es una subsidiaria de propiedad absoluta de Woodfine Capital Projects Inc. WMC gestiona las relaciones con inversores, origina y rige las sociedades limitadas de tenencia directa a través de las cuales se mantienen los activos comerciales, y opera el registro de propiedades en su calidad de custodio fiduciario de datos. La titularidad legal de los activos se mantiene dentro de la respectiva sociedad limitada de tenencia directa establecida para cada propiedad; WMC ostenta participaciones en dichas sociedades como parte de la estructura de gestión y actúa como entidad de cara al inversor dentro del programa de Tenencia Directa.

WMC es la entidad con la que transaccionan los inversores. Es responsable de la gobernanza de activos, las comunicaciones con inversores y la exactitud de los registros del libro de propiedades.

## Principio de separación

La estructura de tres entidades separa las decisiones tecnológicas de las decisiones inmobiliarias a nivel corporativo. PointSav no puede tomar decisiones de inversión; su mandato es la prestación de servicios tecnológicos. WMC no puede modificar el código de la plataforma; ese es el dominio de PointSav. Ninguna entidad tiene autoridad en el ámbito operativo de la otra.

Esta separación es estructural, no contractual. Un contrato puede modificarse; un límite corporativo requiere una reestructuración. La intención del diseño es que ni una falla operativa en PointSav ni un evento financiero en WMC perjudiquen automáticamente la función principal de la otra entidad.

## Véase también

- [[topic-vendor-customer-model|Modelo Proveedor-Cliente]] — la relación de servicios entre PointSav y WMC
- [[topic-direct-hold-framework|Marco de Tenencia Directa]] — la estructura de propiedad de activos que opera WMC
- [[topic-regulatory-posture|Postura Regulatoria]] — las obligaciones de divulgación ante la OSC aplicables al grupo

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
