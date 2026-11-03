---
name: citizen-request-routing
description: Clasificar solicitudes ciudadanas y preparar su derivación sin decidir derechos o prestaciones. En IAbot.io, asígnala a un empleado de atención ciudadana y aporta solicitudes autorizadas, catálogo de trámites y reglas de derivación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Administración pública y gestión institucional
---

# Organizar solicitudes ciudadanas

## Uso en IAbot.io

Asigna esta skill a **un empleado de atención ciudadana** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta solicitudes autorizadas, catálogo de trámites y reglas de derivación.

**Ejemplo de encargo:** «Organiza estas solicitudes por trámite y señala qué órgano o dato falta para poder derivarlas.»

**Resultado a revisar:** Registro de solicitudes con información faltante y ruta propuesta.

## Cuándo usarla y qué necesita

Clasificar solicitudes ciudadanas y preparar su derivación sin decidir derechos o prestaciones

Trabaja con solicitudes autorizadas, catálogo de trámites y reglas de derivación. Usa expedientes y datos públicos o autorizados. Conserva los procedimientos del organismo, las competencias de cada órgano y la protección de datos; no adopta resoluciones administrativas.

## Procedimiento

1. Lee la solicitud completa y separa petición, hechos aportados y documentación adjunta.
2. Relaciona la materia con el catálogo vigente del organismo y conserva casos ambiguos.
3. Identifica datos administrativos indispensables sin pedir información excesiva.
4. Prepara la derivación o respuesta informativa con fuentes y contactos confirmados.
5. Mantén la resolución, prioridad legal y reconocimiento de derechos en el órgano competente.

## Comprobación del resultado

- No se infiere elegibilidad de personas a partir de atributos sensibles.
- La clasificación no equivale a admitir o resolver una solicitud.
- Los datos personales no aparecen en resúmenes públicos.

## Entrega

Registro de solicitudes con información faltante y ruta propuesta.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Portal de Administración Electrónica](https://administracionelectronica.gob.es/)
- [Boletín Oficial del Estado](https://www.boe.es/)
- [Portal de datos abiertos del Gobierno de España](https://datos.gob.es/)
