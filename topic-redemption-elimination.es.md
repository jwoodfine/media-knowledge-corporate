---
schema: foundry-doc-v1
title: "Eliminación de Reembolsos"
slug: topic-redemption-elimination
aliases:
  - topic-redemption-elimination
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
paired_with: topic-redemption-elimination.md
short_description: "Eliminación estructural del derecho de reembolso de los inversores, suprimiendo el lastre de la reserva de efectivo y el riesgo de corrida inherente a los vehículos inmobiliarios colectivos."
cites: []
---

Los activos de [[topic-direct-hold-framework|Tenencia Directa]] de Woodfine no tienen cola de reembolso — el capital de cada inversor corresponde a una propiedad específica, y la liquidez depende del mercado privado para ese activo, no de las reservas de efectivo de la entidad corporativa. Dado que no existe un fondo mancomunado, la condición que hace necesarios los mecanismos de reembolso está ausente por diseño. La liquidez se ejecuta a través del [[topic-equity-transfer-model|Modelo de Transferencia de Capital]], y la deuda a nivel de activo está limitada por el [[topic-interest-coverage-ratio|Ratio de Cobertura de Intereses]] de modo que no se requieren reservas de efectivo para atender las obligaciones.

## Por qué existen las colas de reembolso

En un fondo mancomunado, una cola de reembolso gestiona la tensión entre las solicitudes de liquidez de los inversores y la naturaleza ilíquida del inmueble físico. El fondo mantiene una reserva de efectivo para honrar los reembolsos a corto plazo. Si las solicitudes de reembolso superan la reserva, la cola se activa — los inversores esperan mientras el fondo vende activos o capta nuevo capital.

La reserva de efectivo es un pasivo estructural. Rinde menos que los activos subyacentes. Debe mantenerse incluso cuando no hay reembolsos pendientes. Su tamaño es una decisión discrecional del gestor.

## Lo que elimina la arquitectura de Tenencia Directa

La arquitectura de Tenencia Directa elimina la condición que requiere una reserva de efectivo. No hay capital mancomunado. El capital de cada inversor corresponde a una propiedad específica, no a una participación en un fondo. La entidad corporativa no promete devolver capital a demanda — porque no hay fondo del que extraer.

Un inversor que quiera salir localiza un comprador dispuesto en el mercado privado. La entidad corporativa actualiza el [[topic-property-ledger-technology|libro contable]]. No se accede a ninguna reserva de efectivo. La posición de ningún otro inversor se ve afectada.

## "Corridas bancarias" artificiales

Una cola de reembolso es vulnerable a un fallo de coordinación: si los inversores anticipan que la cola será suspendida, las solicitudes tempranas de reembolso pueden desencadenar la misma suspensión que temían. La arquitectura de Tenencia Directa es inmune a este modo de fallo. No hay cola que unirse, ni suspensión que anticipar, ni ventaja de primer movimiento en coordinar una salida anticipada.

## Implicaciones para los inversores

La consecuencia estructural para los inversores es explícita: MCorp no ofrece un mecanismo de reembolso. La liquidez depende del mercado privado para el activo específico. La estructura de Tenencia Directa conlleva un perfil de riesgo diferente al de un fondo mancomunado — la entidad corporativa no asume ningún compromiso de liquidez que no pueda cumplir, dado que no existe capital mancomunado del que dicho compromiso pudiera satisfacerse.

Sin cola de reembolso, ninguna presión de salida coordinada puede desestabilizar la cartera. El capital a largo plazo se capitaliza sin la carga estructural de una reserva de efectivo que rinde menos que los activos subyacentes, coherente con el [[topic-perpetual-equity-model|modelo de capital perpetuo]] aplicado a las participaciones fraccionales de los inversores.

## Véase también

- [[topic-direct-hold-framework]] — la estructura de propiedad que hace innecesarios los mecanismos de reembolso
- [[topic-equity-transfer-model]] — cómo salen en la práctica los inversores de sus posiciones
- [[topic-interest-coverage-ratio]] — la disciplina de servicio de deuda que elimina la necesidad de reservas de efectivo

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
