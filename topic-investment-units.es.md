---
schema: foundry-doc-v1
title: "Unidades de Inversión"
slug: topic-investment-units
category: governance
type: topic
content_type: topic
status: active
quality: complete
language_protocol: TRANSLATE-ES
short_description: "Las unidades de capital fraccional emitidas en cada activo real nombrado bajo el marco de Tenencia Directa."
paired_with: topic-investment-units.md
audience: public
bcsc_class: public-disclosure-safe
language: es
last_edited: 2026-06-16
see_also:
  - topic-perpetual-equity-model
  - topic-direct-hold-framework
  - topic-property-ledger-technology
---

Las unidades de inversión son los intereses de capital fraccional emitidos en cada activo real nombrado bajo el marco de [[topic-direct-hold-framework|Tenencia Directa]] de MCorp. Cada unidad de inversión representa un porcentaje de propiedad de la propiedad específica, no una participación en un fondo mancomunado ni una participación proporcional en una cartera.

Las unidades se registran en el [[topic-property-ledger-technology|libro contable de propiedad]] del activo nombrado. Son libremente transferibles a contrapartes dispuestas sin requerir aprobación corporativa. El [[topic-perpetual-equity-model|Modelo de Capital Perpetuo]] rige el horizonte de tenencia de estas unidades.

## Resumen

Las unidades de inversión son instrumentos específicos de cada activo. Una unidad emitida en una propiedad nombrada no comporta ningún derecho ni genera exposición a ninguna otra propiedad dentro de la estructura de tenencia de MCorp. Este aislamiento es estructural: deriva del marco de Tenencia Directa, no de representaciones contractuales. Un inversor que mantiene unidades en tres activos distintos tiene tres posiciones separadas con tres libros contables, tres estados operativos y tres derechos de distribución independientes.

## Denominación y emisión

El número de unidades de un activo nombrado se establece en el momento de su incorporación y se registra como oferta fija en el libro contable de la propiedad. La denominación se expresa como porcentaje fraccional: una unidad en un registro de 10.000 unidades representa el 0,01 % del interés económico en ese activo.

La entidad emisora no crea unidades adicionales sin una resolución corporativa formalmente documentada. La dilución no es, por tanto, una característica inherente del instrumento; cualquier decisión de ampliar la oferta es una decisión corporativa material sujeta a divulgación íntegra a los tenedores existentes antes de su entrada en vigor.

## Derechos

Cada unidad de inversión en un activo nombrado confiere tres categorías de derechos.

**Derechos económicos.** Los tenedores de unidades reciben una participación proporcional en las distribuciones declaradas para el activo correspondiente. Las distribuciones, cuando se declaran, se pagan en proporción al número de unidades en circulación; ninguna unidad del mismo activo goza de un derecho de distribución preferente sobre otra.

**Derechos de transferencia.** Las unidades son libremente transferibles a contrapartes dispuestas. Las transferencias se registran en el libro contable en el orden en que se reciben; ninguna transferencia requiere el consentimiento previo de la entidad emisora ni de los demás tenedores de unidades. El cesionario adquiere todos los derechos económicos y de información del cedente en el momento de la liquidación en el libro contable.

**Derechos de información.** Los tenedores de unidades de un activo nombrado reciben estados operativos periódicos de ese activo, que incluyen ingresos, gastos operativos y el ratio de cobertura de intereses (RCI) vigente. La información es específica del activo y no se extiende a otras propiedades de la estructura corporativa.

## Ratio de cobertura de intereses

Cada activo en la cartera de Tenencia Directa mantiene un suelo de ratio de cobertura de intereses (RCI) de 1,2×  — ingresos operativos respecto al servicio de la deuda — como restricción operativa autoimpuesta. El RCI se calcula por activo; no existe subvención cruzada entre propiedades. Un activo que opera entre 1,2× y 1,4× RCI se encuentra en el rango típico de los convenios de préstamo inmobiliario comercial. Un activo por debajo de 1,2× entra en un protocolo de preservación en el que se suspenden las distribuciones hasta que se restablece el ratio.

El suelo del RCI protege directamente a los tenedores de unidades: impide que se realicen distribuciones de una propiedad cuyos ingresos operativos sean insuficientes para sostenerlas. No se declara ninguna distribución de un activo cuyo RCI sea inferior a 1,2×.

## Relación con el Modelo de Capital Perpetuo

Las unidades de inversión son el instrumento a través del cual se expresa el [[topic-perpetual-equity-model|Modelo de Capital Perpetuo]]. El horizonte de tenencia perpetuo — sin salida obligatoria, sin ciclo de fondo fijo — significa que los tenedores de unidades no enfrentan un evento de redención forzosa. La liquidez está disponible a través del mercado secundario identificando una contraparte dispuesta; la entidad corporativa no participa en la salida.

## Conclusión

Las unidades de inversión son instrumentos de oferta fija y específicos de cada activo, sin exposición cruzada entre propiedades de la estructura corporativa. El suelo de RCI del 1,2× suspende las distribuciones antes de que superen los ingresos operativos. Las transferencias no requieren consentimiento corporativo. Para un comprador regulado, la combinación de propiedad registrada en el libro contable, aislamiento estructural del activo y una compuerta de distribución vinculada al RCI proporciona un marco predecible para la asignación permanente de capital a inmuebles nombrados.

## Véase también

- [[topic-perpetual-equity-model|Modelo de Capital Perpetuo]]
- [[topic-direct-hold-framework|Marco de Tenencia Directa]]
- [[topic-property-ledger-technology|Tecnología del Libro Contable de Propiedad]]
