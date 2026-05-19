---
schema: foundry-doc-v1
title: "Gobernanza de Datos"
slug: topic-data-governance
short_description: "El marco de custodia de datos de WMC: quién posee qué datos, dónde y bajo qué obligaciones, coherente con el Mandato Fiduciario de Datos y los requisitos de PIPEDA."
category: operations
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-05-19
editor: pointsav-engineering
paired_with: topic-data-governance.md
cites: []
---

Woodfine Management Corp. es el custodio legal de todos los datos del registro de propiedades, los registros de inversores y los datos operativos generados en relación con los activos gestionados por WMC. PointSav Digital Systems procesa los datos como proveedor de servicios tecnológicos contratado; PointSav no ostenta derechos independientes sobre los datos bajo la custodia de WMC.

## Custodio de datos

El custodio legal de un conjunto de datos es la entidad con el derecho y la responsabilidad de determinar cómo se almacena, utiliza y, en última instancia, destruye. WMC es el custodio legal de todos los registros del libro de propiedades, los datos de identidad de los inversores, el historial de transacciones y los registros operativos generados por los activos gestionados por WMC.

PointSav procesa estos datos en virtud del acuerdo de servicios tecnológicos, actuando como procesador de datos en lugar de responsable del tratamiento, en el sentido de que las instrucciones de WMC rigen el tratamiento de los datos. PointSav no utiliza, comparte ni retiene los datos bajo la custodia de WMC más allá del alcance del acuerdo de servicios.

## Información personal

Los datos de identidad de los inversores y la información de contacto se recogen en virtud de la Ley de Protección de la Información Personal y los Documentos Electrónicos (PIPEDA). El aviso de privacidad de WMC rige la recopilación, el uso y la conservación de la información personal. Los datos personales no se venden ni se transfieren a terceros salvo cuando exista una obligación legal —como el reporte contra el blanqueo de capitales en virtud de la Ley sobre el Producto del Crimen (Blanqueo de Dinero) y la Financiación del Terrorismo (PCMLTFA).

Los registros de identidad de los inversores se conservan durante el período exigido por la legislación de valores aplicable y la normativa contra el blanqueo de capitales. Transcurrido el período de conservación requerido, los registros se destruyen conforme al calendario de conservación de datos de WMC.

## Segregación de datos operativos

Los datos operativos a nivel de activo —eventos financieros, registros de ocupación, historial de mantenimiento— están segregados por activo. Un inversor en un activo de Tenencia Directa no puede acceder a los datos operativos ni a los registros de posición de un activo diferente. Esta segregación es una propiedad de la arquitectura del registro: los controles de acceso se aplican a nivel de activo, no a nivel de cartera. Ninguna excepción de política ni anulación administrativa puede conceder acceso cruzado entre activos sin un cambio estructural en el registro.

## Portabilidad de datos

El marco de gobernanza de datos de WMC requiere que todos los datos del registro sean exportables en formatos estándar. El requisito de portabilidad se impone a PointSav en virtud del acuerdo de servicios tecnológicos. WMC puede solicitar una exportación completa de datos en cualquier momento; PointSav está obligado a entregar la exportación en un formato que WMC pueda leer y operar de forma independiente de la plataforma de software de PointSav.

La portabilidad es el mecanismo por el cual WMC conserva la opción de cambiar de proveedor de tecnología sin perder el historial operativo ni el registro de capital de ningún activo.

## Conservación

Los registros del libro de propiedades se conservan durante la vida operativa del activo más el período exigido por la legislación de valores aplicable. Los registros de eventos financieros son de solo adición durante la vida operativa del activo; ningún registro anterior se sobrescribe ni elimina. Al final del período de conservación requerido tras la disposición del activo, los registros se destruyen conforme al calendario de conservación de datos de WMC y los estándares de destrucción aplicables.

## Véase también

- [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] — las obligaciones de gobernanza que WMC ostenta como custodio del registro de propiedades
- [[topic-property-ledger-technology|Tecnología del Registro de Propiedades]] — la infraestructura técnica en la que se almacenan y mantienen los datos del registro
- [[topic-vendor-customer-model|Modelo Proveedor-Cliente]] — la relación de servicios que rige el rol de PointSav como procesador de datos

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución 4.0 Internacional](https://creativecommons.org/licenses/by/4.0/).*
