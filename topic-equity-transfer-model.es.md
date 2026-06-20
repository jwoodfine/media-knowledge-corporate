---
schema: foundry-doc-v1
title: "Modelo de Transferencia de Capital"
slug: topic-equity-transfer-model
aliases:
  - topic-equity-transfer-model
category: governance
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-equity-transfer-model.md
short_description: "Mecanismo de transferencia entre pares que permite a los inversores ceder su posición directamente a contrapartes dispuestas, sin necesidad de un fondo de liquidez ni recompra corporativa."
cites: []
---

El capital de [[topic-direct-hold-framework|Tenencia Directa]] de Woodfine se transfiere libremente entre partes privadas; la entidad corporativa registra el cambio pero no lo aprueba ni lo intermedia. Dos principios estructurales rigen el modelo: capital libremente transferible y ejecución estrictamente entre partes privadas — sin intermediación corporativa, sin ventanas de liquidez. El modelo se apoya en el [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] para la integridad del libro contable y opera junto con la disciplina del [[topic-interest-coverage-ratio|Ratio de Cobertura de Intereses]] aplicada a nivel de activo.

## Capital libremente transferible

MCorp emite capital privado libremente transferible en cada [[topic-property-ledger-technology|libro contable de propiedad]] aislado. "Libremente transferible" significa que el titular puede ofrecer su interés a cualquier contraparte dispuesta sin requerir aprobación corporativa para la transferencia en sí. La entidad corporativa mantiene el libro contable pero no controla quién puede adquirir capital en él. Cada unidad de capital emitida constituye una [[topic-investment-units|unidad de inversión]] en el activo nombrado.

Esto distingue el modelo de las estructuras de capital restringido — comunes en los vehículos inmobiliarios privados — donde el emisor retiene el derecho de primera opción, impone restricciones de transferencia, o requiere una nueva aprobación de calificación del inversor en cada transferencia.

## Ejecución entre partes privadas

La ejecución de la transferencia es estrictamente entre partes privadas. La entidad corporativa no mantiene un mercado secundario, un libro de órdenes ni una facilidad de recompra. Un inversor que busque liquidez localiza una contraparte dispuesta a través de sus propias relaciones comerciales o de canales de intermediación que operan independientemente de la entidad corporativa.

## Sin requisitos subjetivos de liquidez

Las estructuras de fondos tradicionales imponen puertas de redención, reservas de liquidez y períodos de bloqueo sujetos a la discrecionalidad del gestor del fondo. El Modelo de Transferencia de Capital no contiene ninguno de estos mecanismos — véase [[topic-redemption-elimination|Eliminación de Redención]] para el fundamento estructural. Los términos de liquidez los determina el mercado de compradores dispuestos, no la política de la entidad corporativa. El [[topic-perpetual-equity-model|modelo de capital perpetuo]] aplica la misma lógica a lo largo de un horizonte de tenencia indefinido.

## Integridad del libro contable

El libro contable del activo registra cada transferencia con plena cadena de titularidad. La propiedad de un interés fraccional es una entrada contable, no un certificado en papel. La integridad matemática del libro contable es mantenida por los sistemas de datos fiduciarios de la entidad corporativa, descritos en [[topic-fiduciary-data-mandate]].

## Véase también

- [[topic-direct-hold-framework]] — la estructura de propiedad que hace libremente transferible el capital
- [[topic-fiduciary-data-mandate]] — requisitos de gobernanza de datos que sustentan la integridad del libro contable
- [[topic-redemption-elimination]] — por qué no existe una facilidad de recompra corporativa

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
