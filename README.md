# Clasificador de productos sanitarios MDR/IVDR

Herramienta docente para **cualificar** un producto (¿es producto sanitario?, ¿se rige por el MDR o por el IVDR?) y **clasificarlo por riesgo** según las reglas del Anexo VIII del Reglamento (UE) 2017/745 (MDR) y del Reglamento (UE) 2017/746 (IVDR). Cada resultado cita el artículo, la regla y el guion que lo determinan, propone la categoría EMDN y la vía de evaluación de la conformidad, y puede compararse con la propuesta de revisión COM(2025) 1023.

**Abrir la herramienta:** https://www.cesarsanchezmelendez.es/clasificaMD/

- 113 casos de práctica resueltos: 26 de cualificación, 56 del MDR y 31 del IVDR.
- Informe copiable con el razonamiento completo.
- Reglas publicadas como datos (JSON), revisables y reutilizables.
- Funciona en el navegador, sin registro, sin cookies y sin enviar datos a ningún servidor.

Desarrollada para la asignatura *Calidad y Gestión en Tecnología Sanitaria* (59718) del Grado en Ingeniería Biomédica, Escuela Politécnica de Cuenca, Universidad de Castilla-La Mancha.

> **Uso docente y orientativo.** El resultado no sustituye la clasificación del fabricante ni el criterio del organismo notificado. Normativa revisada a 14/10/2026.

## Proponer casos o avisar de errores

Abre una [incidencia (issue)](https://github.com/csmelendez/clasificaMD/issues) con el producto, su finalidad prevista, la clase que esperabas y la regla que la justifica. También puedes escribir a cesar.sanchez@uclm.es.

## Uso de inteligencia artificial

La herramienta se ha desarrollado con ayuda de un asistente de inteligencia artificial generativa (Claude, de Anthropic) en el código, la interfaz y la redacción de los textos explicativos y de los casos de práctica. Las reglas de cualificación y clasificación, y la solución de cada caso, se han contrastado con el texto de los reglamentos publicado en EUR-Lex y con las fuentes que cita la propia herramienta. El autor ha revisado todo el contenido y es responsable de él.

La herramienta no usa inteligencia artificial al funcionar: el resultado lo calcula en el navegador un motor de reglas fijo, a partir de las respuestas del usuario, y es siempre el mismo para las mismas respuestas.

## Licencias

| Parte | Licencia |
| --- | --- |
| Código (motor y aplicación) | [EUPL-1.2](LICENSE) (texto en https://choosealicense.com/licenses/eupl-1.2/) |
| Casos, textos explicativos y reglas como datos | [CC BY 4.0](LICENSE-CONTENIDO.txt) |
| Fuentes incrustadas | [SIL Open Font License 1.1](LICENSES/OFL-1.1.txt) |
| Logotipo de la UCLM | Marca de la Universidad de Castilla-La Mancha; no incluido en estas licencias |

El texto de los reglamentos procede de EUR-Lex y su reutilización se rige por la política de la Comisión Europea.

## Cómo citar

GitHub muestra el botón **Cite this repository** a partir de [`CITATION.cff`](CITATION.cff). Formato breve:

> Sánchez Meléndez, C. (2026). *Clasificador de productos sanitarios MDR/IVDR* [Software]. Universidad de Castilla-La Mancha. https://github.com/csmelendez/clasificaMD

## Estructura

- `index.html`: la herramienta completa en un único archivo (motor, reglas MDR e IVDR, cualificación e interfaz).
- `img/og-clasificador-mdr-ivdr.png`: imagen de vista previa para redes sociales.
- `LICENSE`, `LICENSE-CONTENIDO.txt`, `LICENSES/`: licencias.
- `CITATION.cff`: datos de cita.

Forma parte de los recursos docentes abiertos de https://www.cesarsanchezmelendez.es/#recursos-abiertos.

© 2026 César Sánchez Meléndez.
