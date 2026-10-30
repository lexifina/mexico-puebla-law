# Puebla: law history in git

The law of the State of Puebla (Estado Libre y Soberano de Puebla, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-pue/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

56 ordenamientos with 819 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE PUEBLA | 101 | as first published, then each reform: 5 October 1917 to 16 July 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO LIBRE Y SOBERANO DE PUEBLA | 62 | as first published, then each reform: 3 May 1985 to 29 July 2026 |
| `codigo-de-instituciones-y-procesos-electorales/` | CODIGO DE INSTITUCIONES Y PROCESOS ELECTORALES DEL ESTADO DE PUEBLA | 26 | as first published, then each reform: 3 October 2000 to 29 July 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO LIBRE Y SOBERANO DE PUEBLA | 19 | as first published, then each reform: 12 August 2004 to 30 December 2017 |
| `codigo-de-procedimientos-en-materia-de-defensa-social/` | CODIGO DE PROCEDIMIENTOS EN MATERIA DE DEFENSA SOCIAL PARA EL ESTADO LIBRE Y SOBERANO DE PUEBLA | 41 | as first published, then each reform: 1 January 1987 to 18 March 2016 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE PUEBLA | 46 | as first published, then each reform: 30 December 1987 to 1 August 2025 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL DEL ESTADO LIBRE Y SOBERANO DE PUEBLA | 3 | as first published, then each reform: 8 December 2001 to 17 January 2017 |
| `codigo-fiscal-y-hacendario-para-el-municipio-de-san-andres-c/` | CODIGO FISCAL Y HACENDARIO PARA EL MUNICIPIO DE SAN ANDRES CHOLULA, PUEBLA | 5 | as first published, then each reform: 1 January 2016 to 16 December 2023 |
| `codigo-fiscal-y-presupuestario-para-el-municipio-de-puebla/` | CODIGO FISCAL Y PRESUPUESTARIO PARA EL MUNICIPIO DE PUEBLA | 17 | as first published, then each reform: 1 January 2000 to 19 December 2023 |
| `codigo-penal/` | CODIGO PENAL DEL ESTADO LIBRE Y SOBERANO DE PUEBLA - ANTES CODIGO DE DEFENSA SOCIAL DEL ESTADO LIBRE Y SOBERANO DE PUEBLA - | 155 | as first published, then each reform: 1 January 1987 to 29 July 2026 |
| `codigo-reglamentario-de-desarrollo-urbano-y-medio-ambiente-p/` | CODIGO REGLAMENTARIO DE DESARROLLO URBANO Y MEDIO AMBIENTE PARA EL MUNICIPIO DE SAN ANDRES CHOLULA, PUEBLA | 1 | as first published: 23 May 2020 |
| `codigo-reglamentario-para-el-municipio-de-puebla/` | CODIGO REGLAMENTARIO PARA EL MUNICIPIO DE PUEBLA | 163 | as first published, then each reform: 3 January 2005 to 25 July 2026 |
| `ley-de-adquisiciones-arrendamientos-y-servicios-del-sector-p/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS DEL SECTOR PUBLICO ESTATAL Y MUNICIPAL | 13 | as first published, then each reform: 10 February 2001 to 14 March 2024 |
| `ley-de-agricultura-urbana/` | LEY DE AGRICULTURA URBANA PARA EL ESTADO DE PUEBLA | 1 | as first published: 31 December 2013 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE PUEBLA | 1 | as first published: 4 October 2024 |
| `ley-de-aranceles-para-el-cobro-de-honorarios-de-los-abogados/` | LEY DE ARANCELES PARA EL COBRO DE HONORARIOS DE LOS ABOGADOS O LICENCIADOS EN DERECHO DEL ESTADO DE PUEBLA | 1 | as first published: 2 July 2022 |
| `ley-de-arbolado-y-areas-verdes-urbanas/` | LEY DE ARBOLADO Y AREAS VERDES URBANAS DEL ESTADO DE PUEBLA | 2 | as first published, then each reform: 1 January 2025 to 6 June 2025 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE PUEBLA | 1 | as first published: 2 March 2024 |
| `ley-de-atencion-y-prevencion-de-la-contaminacion-visual-y-au/` | LEY DE ATENCION Y PREVENCION DE LA CONTAMINACION VISUAL Y AUDITIVA PARA EL ESTADO DE PUEBLA | 1 | as first published: 18 June 2022 |
| `ley-de-bibliotecas/` | LEY DE BIBLIOTECAS DEL ESTADO DE PUEBLA | 1 | as first published: 17 July 2024 |
| `ley-de-bienestar-animal/` | LEY DE BIENESTAR ANIMAL DEL ESTADO DE PUEBLA | 9 | as first published, then each reform: 27 February 2018 to 16 March 2026 |
| `ley-de-busqueda-de-personas/` | LEY DE BUSQUEDA DE PERSONAS DEL ESTADO DE PUEBLA | 1 | oldest version available: 5 September 2021 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO DEL ESTADO DE PUEBLA | 1 | as first published: 11 August 2023 |
| `ley-de-carrera-judicial/` | LEY DE CARRERA JUDICIAL DEL ESTADO DE PUEBLA | 3 | as first published, then each reform: 24 March 2023 to 18 March 2026 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE PUEBLA | 10 | as first published, then each reform: 17 August 2010 to 5 October 2020 |
| `ley-de-construcciones/` | LEY DE CONSTRUCCIONES PARA EL ESTADO Y MUNICIPIOS DE PUEBLA | 2 | as first published, then each reform: 21 February 2024 to 16 August 2024 |
| `ley-de-coordinacion-hacendaria/` | LEY DE COORDINACION HACENDARIA DEL ESTADO DE PUEBLA Y SUS MUNICIPIOS | 8 | as first published, then each reform: 21 March 2009 to 16 March 2026 |
| `ley-de-coordinacion-para-el-establecimiento-y-desarrollo-de/` | LEY DE COORDINACION PARA EL ESTABLECIMIENTO Y DESARROLLO DE LAS ZONAS ECONOMICAS ESPECIALES DEL ESTADO LIBRE Y SOBERANO DE PUEBLA | 1 | as first published: 15 November 2017 |
| `ley-de-cultura/` | LEY DE CULTURA DEL ESTADO DE PUEBLA | 7 | as first published, then each reform: 13 January 2009 to 27 June 2026 |
| `ley-de-derechos-cultura-y-desarrollo-de-los-pueblos-y-comuni/` | LEY DE DERECHOS, CULTURA Y DESARROLLO DE LOS PUEBLOS Y COMUNIDADES INDIGENAS DEL ESTADO DE PUEBLA | 9 | as first published, then each reform: 25 January 2011 to 6 December 2023 |
| `ley-de-desarrollo-economico-sustentable/` | LEY DE DESARROLLO ECONOMICO SUSTENTABLE DEL ESTADO DE PUEBLA | 3 | as first published, then each reform: 28 February 2024 to 11 August 2026 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE PUEBLA | 4 | as first published, then each reform: 27 June 2006 to 20 August 2025 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE PUEBLA | 11 | as first published, then each reform: 17 September 2004 to 27 June 2026 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE PUEBLA | 15 | as first published, then each reform: 17 January 2007 to 29 July 2026 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO LIBRE Y SOBERANO DE PUEBLA | 4 | as first published, then each reform: 19 December 2006 to 30 December 2017 |
| `ley-de-economia-circular/` | LEY DE ECONOMIA CIRCULAR DEL ESTADO DE PUEBLA | 2 | as first published, then each reform: 21 January 2026 to 7 August 2026 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE PUEBLA | 20 | oldest version available, then each reform: 19 May 2020 to 11 July 2026 |
| `ley-de-educacion-inicial/` | LEY DE EDUCACION INICIAL DEL ESTADO LIBRE Y SOBERANO DE PUEBLA | 2 | as first published, then each reform: 26 November 2013 to 17 March 2023 |
| `ley-de-educacion-superior/` | LEY DE EDUCACION SUPERIOR DEL ESTADO DE PUEBLA | 2 | as first published, then each reform: 4 November 2021 to 17 March 2023 |
| `ley-de-egresos/` | LEY DE EGRESOS DEL ESTADO DE PUEBLA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 7 December 2025 |
| `ley-de-ejecucion-de-medidas-cautelares-y-sanciones-penales/` | LEY DE EJECUCION DE MEDIDAS CAUTELARES Y SANCIONES PENALES PARA EL ESTADO DE PUEBLA - ANTES - LEY DE EJECUCION DE SANCIONES PENALES Y DE REINSERCION SOCIAL PARA EL ESTADO DE PUEBLA - | 2 | as first published, then each reform: 17 June 2011 to 15 September 2012 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE PUEBLA | 6 | as first published, then each reform: 22 December 2003 to 17 July 2024 |
| `ley-de-escalafon-del-magisterio/` | LEY DE ESCALAFON DEL MAGISTERIO DEL ESTADO DE PUEBLA | 1 | as first published: 1 October 1940 |
| `ley-de-estimulos-civicos/` | LEY DE ESTIMULOS CIVICOS | 2 | as first published, then each reform: 18 April 1987 to 29 July 2026 |
| `ley-de-estimulos-recompensas-y-premios-a-los-funcionarios-y/` | LEY DE ESTIMULOS, RECOMPENSAS Y PREMIOS A LOS FUNCIONARIOS Y EMPLEADOS DEL GOBIERNO DEL ESTADO DE PUEBLA | 1 | as first published: 30 August 1978 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE PUEBLA | 4 | as first published, then each reform: 4 December 2008 to 10 October 2018 |
| `ley-de-fomento-a-la-acuacultura-y-pesca-sustentable/` | LEY DE FOMENTO A LA ACUACULTURA Y PESCA SUSTENTABLE PARA EL ESTADO DE PUEBLA | 1 | as first published: 1 March 2016 |
| `ley-de-fomento-a-la-investigacion-cientifica-tecnologica-hum/` | LEY DE FOMENTO A LA INVESTIGACION CIENTIFICA, TECNOLOGICA, HUMANISTICA Y A LA INNOVACION PARA EL ESTADO DE PUEBLA | 2 | as first published, then each reform: 3 January 2005 to 3 July 2026 |
| `ley-de-fomento-a-las-actividades-realizadas-por-organizacion/` | LEY DE FOMENTO A LAS ACTIVIDADES REALIZADAS POR ORGANIZACIONES DE LA SOCIEDAD CIVIL PARA EL ESTADO DE PUEBLA | 4 | as first published, then each reform: 1 January 2015 to 30 July 2023 |
| `ley-de-fraccionamientos-y-acciones-urbanisticas/` | LEY DE FRACCIONAMIENTOS Y ACCIONES URBANISTICAS DEL ESTADO LIBRE Y SOBERANO DE PUEBLA | 5 | as first published, then each reform: 26 February 2004 to 6 April 2024 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO LIBRE Y SOBERANO DE PUEBLA | 6 | as first published, then each reform: 1 January 2002 to 16 December 2023 |
| `ley-de-hacienda/` | LEY DE HACIENDA PARA EL ESTADO LIBRE Y SOBERANO DE PUEBLA | 3 | as first published, then each reform: 9 December 2019 to 21 February 2026 |
| `ley-de-hacienda-para-el-municipio-de-tehuacan-puebla/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TEHUACAN, PUEBLA | 3 | as first published, then each reform: 2 January 2006 to 16 December 2023 |
| `ley-de-imagen-institucional/` | LEY DE IMAGEN INSTITUCIONAL DEL ESTADO DE PUEBLA | 2 | as first published, then each reform: 8 February 2024 to 1 January 2025 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE PUEBLA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 30 November 2025 |
| `ley-de-ingresos-del-municipio-de-huejotzingo-puebla-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE HUEJOTZINGO, PUEBLA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 21 December 2025 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication, the state rule SCJN cites.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
