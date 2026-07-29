---
name: emilio-evaluar-riesgos-obras
description: Crear evaluaciones y analisis de riesgos para obras de construccion en espanol, especialmente PSS, ESS, EBSS, obras con o sin proyecto, fases de obra, oficios, medios auxiliares, trabajos en altura, excavaciones, demoliciones, instalaciones, maquinaria, coordinacion de actividades e interferencias. Usar cuando Codex deba generar una evaluacion con matriz de probabilidad/consecuencia/nivel o un analisis preventivo sin matriz para texto tecnico de obra, usando el listado cerrado de riesgos de Quironprevencion adaptado a construccion y el criterio tecnico de la Guia INSST del RD 1627/1997.
---

# Evaluar Riesgos Obras

## Base De Trabajo

Usar este skill para documentos preventivos de obras de construccion en Espana. Trabajar siempre con dos ideas separadas:

- Quironprevencion aporta la taxonomia cerrada de riesgos para ordenar la evaluacion.
- La Guia Tecnica INSST del RD 1627/1997 aporta el criterio tecnico para aplicar esos riesgos a obras.

La jerarquia de fuentes es: BOE/RD 1627/1997, Guia Tecnica INSST de obras, INSST Evaluacion de Riesgos Laborales, metodologia Quironprevencion y recursos de Linea Prevencion/Fundacion Laboral de la Construccion. Si hay conflicto, prevalecen BOE e INSST. No presentar Quironprevencion ni Linea Prevencion como normativa obligatoria.

Leer `references/criterios-obras.md` cuando haya que explicar fuentes, limites, obra con/sin proyecto, PSS/ESS/EBSS o coordinacion preventiva. Leer `references/riesgos-quiron-obras.md` antes de seleccionar riesgos. Leer `references/modelos-salida.md` cuando haga falta formato de entrega, especialmente si el usuario aporta una seccion "Operaciones a desarrollar".


## Seleccion Del Perfil De Obra

Antes de redactar, identificar el tipo principal de obra y leer el perfil correspondiente desde `references/perfiles/` cuando aplique. Si la obra combina varios tipos, combinar los perfiles necesarios sin duplicar riesgos ni medidas.

- Si aparecen ascensor, OTIS, hueco, foso, guias, cabina, contrapeso, maniobra en revision, puertas de piso, cuarto de maquinas, estructura HIPUR o edificio habitado con instalacion de elevador: leer `references/perfiles/emilio-ascensores-otis.md`.
- Si aparecen reforma interior, local, vivienda, zonas comunes interiores, tabiqueria, pavimentos, falsos techos, pintura, alicatados, carpinteria o instalaciones interiores: leer `references/perfiles/emilio-reformas-interiores.md`.
- Si aparecen zanjas, cimentaciones, soleras, rampas exteriores, urbanizacion, canalizaciones, arquetas, saneamiento, excavacion exterior o trabajos en parcela/viario: leer `references/perfiles/emilio-obra-civil-exterior.md`.
- Si aparecen retirada, desmontaje, derribo, picado, corte, demolicion estructural o no estructural, retirada de pavimentos, muretes, jardineras o elementos existentes: leer `references/perfiles/emilio-demoliciones.md`.

Usar el perfil como ayuda tecnica para proponer operaciones, herramientas, maquinaria, medios auxiliares, riesgos caracteristicos, medidas preventivas y vigilancia del recurso preventivo. No presentar el perfil como normativa. No inventar que una herramienta, maquinaria o medio auxiliar se usara si la descripcion no lo permite; marcarlo como pendiente de confirmar.
## Seleccion Del Modo

Si el usuario pide "evaluacion de riesgos", "matriz", "probabilidad", "consecuencia", "nivel" o "riesgo residual", usar el modo evaluacion con matriz.

Si el usuario pide "analisis de riesgos", "apartado de PSS", "texto para ESS/EBSS", "redaccion preventiva", "sin matriz" o un texto narrativo, usar el modo analisis sin matriz.

Si el modo no esta claro y la salida podria cambiar materialmente, preguntar una sola vez. Si el contexto apunta a PSS/ESS narrativo, usar analisis sin matriz; si apunta a evaluacion formal, usar matriz.

## Seleccion De La Estructura

Permitir que el usuario elija la estructura de salida cuando la pida de forma expresa. Si no la concreta, usar la estructura completa por defecto.

- Apartados fijos: alcance, criterio aplicado, identificacion de riesgos, medidas preventivas, EPI, recurso preventivo y observaciones o datos pendientes.
- Apartados opcionales: `2. Herramientas y maquinaria utilizada` y `3. Medios auxiliares utilizados`.

Cuando el usuario indique que desea omitir los apartados opcionales, no incluirlos. Cuando pida solo uno de ellos, incluir solo el solicitado. Cuando pida una salida resumida, priorizar los apartados fijos y omitir los opcionales salvo que aporten valor tecnico claro.

## Flujo Comun

1. Delimitar obra, fase, tarea, oficio, ubicacion, duracion/frecuencia, trabajadores expuestos, terceros afectados, subcontratas e interferencias.
2. Identificar por separado medios auxiliares, herramientas, maquinaria, equipos de trabajo, instalaciones provisionales, materiales, productos, energias, accesos y condiciones ambientales.
3. Seleccionar riesgos desde el listado Quiron adaptado a obra. No inventar categorias fuera del listado salvo mediante "39. Otros riesgos".
4. Adaptar cada riesgo a una situacion peligrosa concreta de construccion. Ejemplo: "caida a distinto nivel durante el montaje de barandillas en borde de forjado", no solo "caidas".
5. Proponer medidas segun jerarquia preventiva: eliminar/reducir en origen, proteccion colectiva, organizacion y coordinacion, procedimiento, formacion/informacion, senalizacion y EPI como complemento.
6. Indicar datos pendientes cuando falten evidencias: altura, medios auxiliares, herramientas, maquinaria, equipos de trabajo, acceso, interferencias, planificacion, documentacion, productos o condiciones reales.
7. No afirmar visita, medicion, aprobacion, designacion de recurso preventivo, coordinador, formacion o conformidad documental si el usuario no lo aporta.

## Modo Evaluacion Con Matriz

Usar tabla por fase, tarea o actividad. Antes de la tabla o por cada fase, incluir apartados breves separados: "Herramientas y maquinaria utilizada" y "Medios auxiliares utilizados" solo cuando el usuario los solicite, cuando la obra lo requiera de forma clara o cuando aporten valor tecnico evidente. Si el usuario los omite, tratarlos como opcionales y no incluirlos. Separar lo confirmado de lo pendiente de confirmar; no inventar modelos, marcas, potencias, certificaciones, revisiones, homologaciones, configuraciones o calculos resistentes.

Incluir como minimo:

| Fase/tarea | Riesgo Quiron | Situacion peligrosa en obra | Personas expuestas | Medidas existentes | Prob. | Cons. | Nivel | Medidas propuestas | Prioridad | Riesgo residual |
|---|---|---|---|---|---|---|---|---|---|---|

Usar la matriz general INSST cuando no exista metodo especifico aplicable:

| Probabilidad / Consecuencia | Ligeramente danina | Danina | Extremadamente danina |
|---|---|---|---|
| Baja | Trivial | Tolerable | Moderado |
| Media | Tolerable | Moderado | Importante |
| Alta | Moderado | Importante | Intolerable |

Criterio orientativo:

- Trivial: mantener controles.
- Tolerable: comprobar periodicamente y mejorar si es razonable.
- Moderado: planificar medidas en plazo definido.
- Importante: no iniciar o corregir con prioridad alta hasta reducir el riesgo.
- Intolerable: no iniciar ni continuar hasta controlar el riesgo de forma inmediata.

Valorar prudencialmente cuando falten datos y marcar la hipotesis. Para riesgos que requieran metodologia especifica, advertirlo y no sustituirla por la matriz general.

## Modo Analisis Sin Matriz

Redactar texto formal para PSS/ESS/EBSS sin columnas de probabilidad, consecuencia, nivel ni riesgo residual, salvo peticion expresa. Si el usuario aporta una seccion numerada "Operaciones a desarrollar", conservar esa logica y devolver solo los apartados que solicite o que aporten valor tecnico claro: "Herramientas y maquinaria utilizada", "Medios auxiliares utilizados", "Identificacion de riesgos", "Medidas preventivas", "Equipos de proteccion individual" y, cuando corresponda, "Actividades de vigilancia y control del Recurso preventivo".

Agrupar por fase o actividad. Para cada riesgo aplicable, incluir:

- riesgo del listado Quiron;
- situacion peligrosa en obra;
- danos previsibles;
- medidas preventivas y protecciones colectivas;
- organizacion, coordinacion, control de accesos, formacion/informacion, senalizacion y EPI cuando proceda.

Mantener estilo tecnico-documental, listo para pegar. Evitar frases genericas como "usar EPI" sin medidas previas. Evitar listados masivos de riesgos no aplicables. Para el apartado de recurso preventivo, indicar expresamente si no se preve necesario por no existir trabajos con riesgos especiales del Anexo II del RD 1627/1997; si si procede, describir las actividades concretas de vigilancia y control.

## Advertencias

No presentar la salida como evaluacion certificada ni definitiva si no hay visita, datos suficientes o validacion por modalidad preventiva competente. Recordar la necesidad de integrar la evaluacion o el analisis en la planificacion preventiva de la obra, con revision ante cambios, incidentes, interferencias nuevas, fases no previstas o modificacion de medios auxiliares/equipos.







