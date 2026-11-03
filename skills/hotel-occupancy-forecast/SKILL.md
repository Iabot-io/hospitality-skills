---
name: hotel-occupancy-forecast
description: Preparar una previsión de ocupación distinguiendo reservas confirmadas, cancelaciones y supuestos. En IAbot.io, asígnala a un empleado de planificación hotelera y aporta reservas a fecha de corte, capacidad vendible e histórico comparable.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Turismo y hostelería
---

# Previsión de ocupación

## Uso en IAbot.io

Asigna esta skill a **un empleado de planificación hotelera** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta reservas a fecha de corte, capacidad vendible e histórico comparable.

**Ejemplo de encargo:** «Prepara la ocupación prevista de las próximas cuatro semanas con escenarios explícitos.»

**Resultado a revisar:** Previsión por fecha y tipo de habitación con supuestos y cobertura.

## Cuándo usarla y qué necesita

Preparar una previsión de ocupación distinguiendo reservas confirmadas, cancelaciones y supuestos

Trabaja con reservas a fecha de corte, capacidad vendible e histórico comparable. Usa documentos y exportaciones de reservas o ventas; cualquier consulta o cambio en PMS, canales de venta o correo necesita la conexión autorizada correspondiente.

## Procedimiento

1. Fija fecha de corte y capacidad vendible descontando habitaciones bloqueadas según datos confirmados.
2. Expande estancias por noche respetando salida y tipos de habitación; separa canceladas y provisionales.
3. Calcula ocupación confirmada y evolución de reservas con históricos comparables.
4. Construye escenarios de demanda y cancelación identificados, sin presentarlos como reservas reales.
5. Entrega una tabla por fecha y excepciones de capacidad o datos.

## Comprobación del resultado

- La noche de salida no se cuenta como estancia.
- La capacidad es la realmente vendible del periodo.
- Previsión y ocupación confirmada aparecen separadas.

## Entrega

Previsión por fecha y tipo de habitación con supuestos y cobertura.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INE, empresas de hostelería](https://www.ine.es/dyngs/Prensa/es/DIRCE2025.htm)
- [SEGITTUR, conocimiento turístico](https://www.segittur.es/)
