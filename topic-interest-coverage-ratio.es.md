---
schema: foundry-doc-v1
title: "Ratio de Cobertura de Intereses"
slug: topic-interest-coverage-ratio
aliases:
  - topic-interest-coverage-ratio
category: reference
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-interest-coverage-ratio.md
short_description: "Indicador de servicio de deuda que exige que los ingresos operativos cubran los gastos financieros al menos 1,2 veces, equilibrando la capacidad de endeudamiento con el cumplimiento de los compromisos."
cites: []
---

Un ratio mínimo de cobertura de intereses de 1,2× limita cada activo de [[topic-direct-hold-framework|Tenencia Directa]] de Woodfine — no puede emitirse nueva deuda que reduzca la cobertura de ingresos operativos sobre intereses por debajo de este umbral. La restricción está establecida en el contrato de sociedad limitada que rige cada solución de tenencia directa; se aplica a la emisión de debentures garantizados con primera hipoteca y regula la capacidad de endeudamiento de la sociedad. Opera junto con el [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] y el [[topic-equity-transfer-model|Modelo de Transferencia de Capital]] como el tercer compromiso estructural aplicado por activo.

## Qué mide la ratio

El ICR es la ratio entre los ingresos operativos netos (NOI) y las obligaciones de intereses totales, donde las obligaciones de intereses excluyen el reembolso del capital principal. Un ICR de 1,2 significa que el activo genera 1,2 dólares de ingresos operativos netos por cada dólar de intereses adeudados. En exactamente 1,0, los ingresos cubren los intereses exactamente. Por debajo de 1,0, el activo no puede servir su deuda con ingresos operativos sin recurrir a reservas de capital.

El piso de 1,2 proporciona un margen operativo del 20%. Un aumento en la tasa de vacancia, un pico de gastos de mantenimiento, o una interrupción a corto plazo de un inquilino pueden reducir los ingresos sin incumplir la obligación de intereses.

## Por qué 1,2

El umbral de 1,2 es una elección estructural deliberada, no un mínimo regulatorio. Los préstamos inmobiliarios comerciales tradicionales generalmente requieren convenios de ICR en el rango de 1,2 a 1,4. Al 1,2, la entidad corporativa acepta un margen más ajustado a cambio de mayor capacidad de apalancamiento — maximizando la base de activos desplegable y manteniendo la certeza matemática de que los ingresos operativos cubren la deuda.

## Relación con la protección de activos

El piso del ICR es el mecanismo principal mediante el cual la arquitectura de Tenencia Directa protege los activos físicos de las ejecuciones hipotecarias. Una entidad corporativa que permite que su ICR caiga por debajo de 1,0 entra en un estado donde el servicio de la deuda depende de retiros de capital — una condición estructuralmente inestable que la [[topic-redemption-elimination|ausencia de cola de redención]] dejaría de otro modo sin mitigar. La restricción de 1,2 lo previene por diseño.

Un evento de ejecución hipotecaria en un vehículo de activo no puede propagarse a otros porque cada activo está legalmente aislado. El ICR se aplica por vehículo — no puede satisfacerse subsidiando transversalmente un activo débil con uno fuerte.

Una cartera que mantiene un ICR de 1,2x de forma indefinida evita las ventas forzadas de activos desencadenadas por déficits en el servicio de la deuda, preservando el valor del capital a largo plazo sin requerir inyecciones de capital. La disciplina es coherente con el [[topic-perpetual-equity-model|modelo de capital perpetuo]] aplicado a [[topic-investment-units|unidades de inversión]] fraccionales.

## Véase también

- [[topic-direct-hold-framework]] — la estructura de propiedad que la restricción del ICR protege
- [[topic-redemption-elimination]] — por qué no existe una reserva de efectivo mancomunada junto al umbral del ICR
- [[topic-fiduciary-data-mandate]] — la disciplina paralela de soberanía de datos aplicada a cada activo de Tenencia Directa

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
