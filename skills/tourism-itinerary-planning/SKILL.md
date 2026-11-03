---
name: tourism-itinerary-planning
description: Diseñar itinerarios con horarios, desplazamientos y condiciones contrastados. En IAbot.io, asígnala a un empleado de planificación turística y aporta destino, fechas, preferencias, movilidad y presupuesto del viajero.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Turismo y hostelería
---

# Itinerarios turísticos documentados

## Uso en IAbot.io

Asigna esta skill a **un empleado de planificación turística** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta destino, fechas, preferencias, movilidad y presupuesto del viajero.

**Ejemplo de encargo:** «Propón dos días de visitas con tiempos realistas y separa precios orientativos de reservas realizadas.»

**Resultado a revisar:** Itinerario con fuentes fechadas, alternativas y reservas pendientes.

## Cuándo usarla y qué necesita

Diseñar itinerarios con horarios, desplazamientos y condiciones contrastados

Trabaja con destino, fechas, preferencias, movilidad y presupuesto del viajero. Usa documentos y exportaciones de reservas o ventas; cualquier consulta o cambio en PMS, canales de venta o correo necesita la conexión autorizada correspondiente.

## Procedimiento

1. Fija fechas, ritmo, restricciones y punto de partida, pidiendo solo lo que impida una propuesta útil.
2. Consulta fuentes oficiales de horarios, acceso, cierres y requisitos relevantes.
3. Ordena visitas con tiempos de desplazamiento y márgenes identificados, sin rellenar cada minuto.
4. Calcula costes por persona y grupo distinguiendo estimación, tarifa publicada y pago confirmado.
5. Entrega alternativas ante cierres o disponibilidad; no efectúes reservas ni pagos fuera del alcance autorizado.

## Comprobación del resultado

- Los horarios corresponden a las fechas del viaje.
- La accesibilidad se apoya en datos del lugar, no en suposiciones.
- Se conservan las fuentes y la fecha de consulta.

## Entrega

Itinerario con fuentes fechadas, alternativas y reservas pendientes.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INE, empresas de hostelería](https://www.ine.es/dyngs/Prensa/es/DIRCE2025.htm)
- [SEGITTUR, conocimiento turístico](https://www.segittur.es/)
