# Administración pública y gestión institucional · Skills para empleados IA de IAbot.io

Expedientes, actas, presupuestos, atención ciudadana y seguimiento institucional con fuentes y responsabilidades explícitas.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Organizar expedientes administrativos](skills/public-case-file-index/SKILL.md) | un empleado de apoyo administrativo público | Índice trazable del expediente y lista de documentación pendiente. |
| [Preparar actas y acuerdos institucionales](skills/institutional-meeting-minutes/SKILL.md) | un empleado de secretaría de apoyo | Borrador de acta y registro de acuerdos con fuente y estado. |
| [Revisar ejecución presupuestaria pública](skills/public-budget-execution-review/SKILL.md) | un empleado de análisis presupuestario | Cuadro de ejecución y diferencias con fuentes y definiciones. |
| [Seguimiento de compromisos institucionales](skills/institutional-commitment-tracker/SKILL.md) | un empleado de gabinete o coordinación institucional | Registro de compromisos e informe de avance basado en evidencias. |
| [Organizar solicitudes ciudadanas](skills/citizen-request-routing/SKILL.md) | un empleado de atención ciudadana | Registro de solicitudes con información faltante y ruta propuesta. |
| [Dossier de evidencia para decisiones públicas](skills/public-policy-evidence-brief/SKILL.md) | un empleado de análisis institucional | Dossier con datos, alternativas, incertidumbres y preguntas de decisión. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/public-sector-skills --list
npx skills add Iabot-io/public-sector-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Organizar expedientes administrativos:** «Organiza este expediente y señala documentos ausentes sin dar por realizada ninguna actuación administrativa.»
- **Preparar actas y acuerdos institucionales:** «Prepara un borrador de acta con los acuerdos que constan y marca los pasajes que deben validarse.»
- **Revisar ejecución presupuestaria pública:** «Resume la ejecución por programa y distingue crédito, compromiso, obligación y pago según los datos aportados.»

## Herramientas y límites

Usa expedientes y datos públicos o autorizados. Conserva los procedimientos del organismo, las competencias de cada órgano y la protección de datos; no adopta resoluciones administrativas.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Portal de Administración Electrónica](https://administracionelectronica.gob.es/)
- [Boletín Oficial del Estado](https://www.boe.es/)
- [Portal de datos abiertos del Gobierno de España](https://datos.gob.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
