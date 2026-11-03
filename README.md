# Turismo y hostelería · Skills para empleados IA de IAbot.io

Reservas, atención al huésped, costes de restauración y preparación de servicios turísticos.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Conciliar reservas de alojamiento](skills/hotel-reservation-reconciliation/SKILL.md) | un empleado de reservas | Registro de reservas conciliadas y excepciones con siguiente acción. |
| [Preparar respuestas al huésped](skills/guest-message-drafting/SKILL.md) | un empleado de atención al huésped | Respuesta preparada con datos confirmados y asuntos que requieren decisión. |
| [Previsión de ocupación](skills/hotel-occupancy-forecast/SKILL.md) | un empleado de planificación hotelera | Previsión por fecha y tipo de habitación con supuestos y cobertura. |
| [Escandallos de restauración](skills/restaurant-recipe-costing/SKILL.md) | un empleado de control de costes de cocina | Escandallo reproducible por receta y ración con fuentes y sensibilidad. |
| [Propuestas de eventos y grupos](skills/hospitality-event-proposal/SKILL.md) | un empleado comercial de eventos | Propuesta comercial y cuadro de servicios, costes y condiciones. |
| [Itinerarios turísticos documentados](skills/tourism-itinerary-planning/SKILL.md) | un empleado de planificación turística | Itinerario con fuentes fechadas, alternativas y reservas pendientes. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/hospitality-skills --list
npx skills add Iabot-io/hospitality-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Conciliar reservas de alojamiento:** «Compara estas reservas del PMS y los canales para detectar diferencias de fechas, estado y pago.»
- **Preparar respuestas al huésped:** «Prepara una respuesta en francés sobre la llegada tardía usando únicamente las condiciones adjuntas.»
- **Previsión de ocupación:** «Prepara la ocupación prevista de las próximas cuatro semanas con escenarios explícitos.»

## Herramientas y límites

Usa documentos y exportaciones de reservas o ventas; cualquier consulta o cambio en PMS, canales de venta o correo necesita la conexión autorizada correspondiente.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [INE, empresas de hostelería](https://www.ine.es/dyngs/Prensa/es/DIRCE2025.htm)
- [SEGITTUR, conocimiento turístico](https://www.segittur.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
