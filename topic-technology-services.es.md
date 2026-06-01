---
schema: foundry-doc-v1
title: "Acuerdo de Servicios Tecnológicos"
slug: topic-technology-services
aliases:
  - topic-technology-services
short_description: "Estructura del acuerdo de servicios bajo el cual PointSav Digital Systems proporciona infraestructura de plataforma a Woodfine Management Corp. como proveedor de tecnología contratado."
category: operations
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-technology-services.md
cites: []
---

PointSav Digital Systems presta servicios tecnológicos a Woodfine Management Corp. en virtud de un acuerdo contractual de servicios que implementa el [[topic-vendor-customer-model|modelo proveedor-cliente]]. El acuerdo define el alcance del compromiso de PointSav, las obligaciones en materia de datos que PointSav mantiene hacia WMC y los límites que impiden que la relación de servicios tecnológicos se extienda a funciones de gestión de inversiones o asesoramiento fiduciario. Las obligaciones de PointSav operan junto al [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] bajo el cual WMC conserva la custodia de todos los datos del libro contable.

## Estructura del acuerdo

El acuerdo de servicios establece a PointSav como proveedor de tecnología contratado —no como socio, cogestor ni asesor en materia de inversión o asuntos fiduciarios—. PointSav presta servicios definidos; WMC dirige esos servicios y conserva toda la [[topic-data-governance|custodia de los datos]], la autoridad sobre las decisiones de inversión y la responsabilidad de las relaciones con los inversores.

PointSav no posee participaciones en ninguna propiedad gestionada por WMC en virtud del acuerdo. PointSav no recibe una parte de los rendimientos de inversión. La remuneración se estructura como una tarifa por servicios tecnológicos, no como una participación en beneficios ni una asignación basada en el rendimiento.

## Alcance de los servicios

El acuerdo abarca:

- Desarrollo de plataforma y mantenimiento de software para la infraestructura del [[topic-property-ledger-technology|registro de propiedades]] y el portal de inversores
- Infraestructura de servidores y gestión de claves privadas para las operaciones del registro
- Servicios de exportación de datos y portabilidad a solicitud de WMC
- Monitoreo de seguridad y funciones de integridad del sistema
- Soporte operativo del sistema y respuesta a incidentes

Los servicios fuera de este alcance —asesoramiento de inversión, incorporación de inversores, asesoramiento en materia de cumplimiento normativo, representación fiduciaria y comunicaciones con inversores— están expresamente excluidos del compromiso de PointSav.

## Obligaciones en materia de datos

El acuerdo requiere que PointSav mantenga los datos del registro en formatos accesibles para WMC, que entregue una exportación completa de datos a solicitud, y que destruya los datos conforme a las instrucciones de WMC a la terminación del acuerdo. Estas obligaciones garantizan que los derechos de custodia de datos de WMC no dependan de la continuación de ninguna relación específica de servicios tecnológicos.

PointSav no transfiere, vende ni utiliza de forma independiente los datos bajo la custodia de WMC. Todos los datos procesados en virtud del acuerdo permanecen bajo la custodia legal de WMC.

## Exclusiones

PointSav no proporciona:

- Asesoramiento de inversión ni recomendaciones sobre adquisición, disposición o financiación de activos
- Incorporación de inversores ni determinaciones de idoneidad de inversores
- Asesoramiento en materia de cumplimiento normativo ni servicios fiduciarios
- Representación de WMC ante la OSC ni ante ningún otro organismo regulador
- Comunicaciones con inversores ni reportes a los tenedores de valores

Estas funciones corresponden a WMC. Las consultas de los inversores sobre la plataforma o la infraestructura del registro se remiten a WMC como fiduciario responsable.

## Separación de modos de fallo

El acuerdo de servicios está estructurado de modo que una interrupción operativa en PointSav no afecte la titularidad legal de WMC sobre los activos, y un evento financiero en WMC no ponga fin a las obligaciones de PointSav de mantener la integridad de los datos y la disponibilidad de la plataforma. Las dificultades operativas de ninguna de las partes perjudican automáticamente la función principal de la otra. Esta separación es la expresión práctica del modelo proveedor-cliente a nivel contractual.

## Véase también

- [[topic-vendor-customer-model|Modelo Proveedor-Cliente]] — la separación estructural entre PointSav y WMC que refleja el acuerdo de servicios
- [[topic-data-governance|Gobernanza de Datos]] — el marco de custodia de datos de WMC que rige las obligaciones de PointSav en virtud del acuerdo
- [[topic-property-ledger-technology|Tecnología del Registro de Propiedades]] — la infraestructura técnica que PointSav mantiene en virtud del acuerdo

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
