---
name: hotel-reservation-reconciliation
description: Conciliar reservas entre canales y PMS identificando cambios, duplicados y discrepancias de cobro. En IAbot.io, asígnala a un empleado de reservas y aporta exportaciones del PMS, canales, cancelaciones y pagos.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Turismo y hostelería
---

# Conciliar reservas de alojamiento

## Uso en IAbot.io

Asigna esta skill a **un empleado de reservas** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta exportaciones del PMS, canales, cancelaciones y pagos.

**Ejemplo de encargo:** «Compara estas reservas del PMS y los canales para detectar diferencias de fechas, estado y pago.»

**Resultado a revisar:** Registro de reservas conciliadas y excepciones con siguiente acción.

## Cuándo usarla y qué necesita

Conciliar reservas entre canales y PMS identificando cambios, duplicados y discrepancias de cobro

Trabaja con exportaciones del PMS, canales, cancelaciones y pagos. Usa documentos y exportaciones de reservas o ventas; cualquier consulta o cambio en PMS, canales de venta o correo necesita la conexión autorizada correspondiente.

## Procedimiento

1. Relaciona localizadores y canales sin fusionar huéspedes por coincidencia de nombre.
2. Normaliza llegada, salida, zona horaria, habitación y estado conservando cambios y cancelaciones.
3. Contrasta importes brutos, comisiones, anticipos y cobros distinguiendo tarifa de liquidación.
4. Identifica reservas sin correspondencia y discrepancias que necesiten confirmación del canal.
5. Prepara propuestas de corrección sin cancelar, cobrar ni alterar inventario automáticamente.

## Comprobación del resultado

- No se confunde una modificación con una segunda reserva.
- No se mezclan importes netos de canal y precio pagado por el huésped.
- Los datos personales se limitan a lo necesario para conciliar.

## Entrega

Registro de reservas conciliadas y excepciones con siguiente acción.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INE, empresas de hostelería](https://www.ine.es/dyngs/Prensa/es/DIRCE2025.htm)
- [SEGITTUR, conocimiento turístico](https://www.segittur.es/)
