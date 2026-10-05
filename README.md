# AI model audit

Revisión de entregas BIM con IA: compara dos versiones IFC contra el BEP y las actas de coordinación, con evidencia por elemento.

**Lo que cambió. Lo que falta. La evidencia.**

## Qué contiene

Un solo archivo, `index.html`, con dos partes:

- **Sitio**: problema, solución, integración de IA, mercado, precio y solicitud de piloto.
- **Prototipo navegable** (botón «Probar la demo»): el flujo principal de la solución.
  1. **Entrega**: carga de V01, V02 y los acuerdos escritos. Los archivos se leen en el navegador; no se suben a ningún servidor.
  2. **Requisitos**: la IA propone reglas a partir del BEP y las actas; el coordinador las aprueba, corrige o devuelve.
  3. **Visor**: modelo 3D por estado de cambio o de cumplimiento, con la vista Antes · Ahora · Esperado por elemento.
  4. **Avance**: información y geometría por separado, con alerta de retrocesos.
  5. **Reporte**: observaciones con evidencia, descargables en CSV y HTML, más el registro de medición para el Kit.

El botón «Recorrido» guía las 4 tareas de la prueba con coordinadores (T1 a T4) y mide el tiempo de cada una.

## Sobre la IA en esta versión publicada

- Con el **caso de ejemplo**, la propuesta de reglas es una respuesta de IA pregrabada (modo demostración).
- Con **archivos propios**, sin conexión a un modelo, se usa un asistente local aproximado por coincidencia de palabras.
- Dentro de Claude, la misma página llama al modelo en vivo.

En todos los casos la IA solo propone: ninguna regla se verifica sin aprobación humana, y el cumplimiento lo calcula un motor determinista.

## Transparencia

Los datos del caso de ejemplo son sintéticos. Las cifras de mercado citan su fuente; precios, ahorros y escenarios son supuestos en validación. Claude (Anthropic) apoyó el código y la redacción, con revisión del equipo.

## Equipo

- Manuel Daniel Bencomo Rojas
- Rainer Luice Murrieta Huaranca

Diplomado Internacional IA en Ingeniería y Construcción, AECODE ED.03. Eje Startup, Hito 2.
