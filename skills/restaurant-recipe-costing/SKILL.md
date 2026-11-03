---
name: restaurant-recipe-costing
description: Calcular costes de recetas y raciones con conversiones y rendimientos documentados. En IAbot.io, asígnala a un empleado de control de costes de cocina y aporta recetas, rendimientos, unidades de compra y precios fechados.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Turismo y hostelería
---

# Escandallos de restauración

## Uso en IAbot.io

Asigna esta skill a **un empleado de control de costes de cocina** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta recetas, rendimientos, unidades de compra y precios fechados.

**Ejemplo de encargo:** «Calcula el coste de estas recetas y muestra cómo cambia con el rendimiento de cada ingrediente.»

**Resultado a revisar:** Escandallo reproducible por receta y ración con fuentes y sensibilidad.

## Cuándo usarla y qué necesita

Calcular costes de recetas y raciones con conversiones y rendimientos documentados

Trabaja con recetas, rendimientos, unidades de compra y precios fechados. Usa documentos y exportaciones de reservas o ventas; cualquier consulta o cambio en PMS, canales de venta o correo necesita la conexión autorizada correspondiente.

## Procedimiento

1. Identifica receta, versión, número de raciones y cantidades en la base bruta o neta correspondiente.
2. Convierte precios de compra a unidades de receta usando contenidos de envase y rendimientos confirmados.
3. Calcula el coste de ingrediente y receta evitando aplicar dos veces una merma.
4. Separa coste alimentario de personal, energía e impuestos cuando se incluya una propuesta de precio.
5. Presenta sensibilidad a cambios de precio o rendimiento y datos no confirmados.

## Comprobación del resultado

- Se distinguen gramos, kilogramos, litros y unidades.
- La suma por ingredientes coincide con el total de receta.
- Los alérgenos no se deducen de nombres de platos; requieren fichas verificadas.

## Entrega

Escandallo reproducible por receta y ración con fuentes y sensibilidad.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INE, empresas de hostelería](https://www.ine.es/dyngs/Prensa/es/DIRCE2025.htm)
- [SEGITTUR, conocimiento turístico](https://www.segittur.es/)
