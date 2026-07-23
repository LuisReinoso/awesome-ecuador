# Awesome Ecuador [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Una lista curada de comunidades, proyectos open source, empresas, eventos y recursos del ecosistema tecnológico de Ecuador.

Inspirada en el formato [awesome-list](https://github.com/sindresorhus/awesome). Si conocés algo que debería estar acá, mandá un PR — ver [CONTRIBUTING.md](CONTRIBUTING.md).

## Contenido

- [Comunidades](#comunidades)
- [Eventos y Conferencias](#eventos-y-conferencias)
- [Gobierno Abierto, Datos Abiertos y Transparencia](#gobierno-abierto-datos-abiertos-y-transparencia)
- [Proyectos Open Source](#proyectos-open-source)
  - [Facturación Electrónica / SRI](#facturación-electrónica--sri)
  - [Datos Abiertos, Gobierno y Transparencia](#datos-abiertos-gobierno-y-transparencia)
  - [Gobierno Electrónico](#gobierno-electrónico)
  - [MCP / AI Agents](#mcp--ai-agents)
  - [Comercio y Turismo](#comercio-y-turismo)
  - [Educación](#educacion)
  - [Civic Tech y Seguridad](#civic-tech-y-seguridad)
  - [COVID-19 / Datos y Visualización](#covid-19--datos-y-visualización)
  - [Comunidad y Colecciones](#comunidad-y-colecciones)
- [Aprendizaje](#aprendizaje)

## Comunidades

- [GDG Quito](https://gdg.community.dev/gdg-quito/) - Google Developer Group de Quito, charlas y meetups sobre tecnologías de Google.
- [GDG Guayaquil](https://gdg.community.dev/gdg-guayaquil/) - Google Developer Group de Guayaquil.
- [Python Ecuador](https://www.meetup.com/es/python-ecuador/) - Comunidad de Python con reuniones en Quito, Cuenca y otras ciudades. Telegram: `@pythonecuador`.
- [EcuadorJUG](https://www.meetup.com/ecuadorjug/) - Java User Group Ecuador, charlas bimensuales sobre Java/JVM.
- [Drupal Ecuador](https://groups.drupal.org/ecuador) - Nexo de los grupos locales de Drupal en el país.
- [Quito Lambda](https://www.meetup.com/Quito-Lambda-Meetup/) - La comunidad de programación funcional más grande de Ecuador, apoyada por Stack Builders. Encuentros el último miércoles de cada mes.
- [AI Tinkerers Quito](https://quito.aitinkerers.org/) - Meetup de builders de IA hands-on (demos en vivo, sin slides), parte de la red global AI Tinkerers y organizado por Tribu IA.

## Eventos y Conferencias

- [Ecuador Tech Week](https://www.ecuadortechweek.ec/) - El festival de tecnología descentralizado más grande de Ecuador, con sede principal en Guayaquil (2025: 88 eventos, 8000+ asistentes).
- DevFest Ecuador - Conferencia de developers organizada por la red GDG, 700+ asistentes, foco en IA/ML, nube y desarrollo móvil.
- SALA (Summit of AI in Latin America) - Cumbre regional de IA en la USFQ (Quito), con foco en modelos en español y portugués.
- Future Festival Ecuador - Conferencia de innovación en Guayaquil (Hilton Colón).

## Gobierno Abierto, Datos Abiertos y Transparencia

- [Datos Abiertos Ecuador](https://www.datosabiertos.gob.ec/) - Portal oficial del gobierno: 1500+ datasets de 98+ instituciones.
- [Open Knowledge Foundation Ecuador (OKF Ecuador)](https://ec.okfn.org/) - Nodo ecuatoriano de la red global Open Knowledge Foundation, promueve datos y conocimiento abierto.
- [Asamblea Abierta](https://luisreinoso.dev/asamblea-abierta/) ([código](https://github.com/LuisReinoso/asamblea-abierta)) - Plataforma de transparencia legislativa: transcribe, diariza e identifica oradores en las sesiones de la Asamblea Nacional usando modelos de IA 100% locales (Whisper, pyannote, PaddleOCR), sin APIs de pago.
- [Minka](https://minka.gob.ec/) - Instancia oficial de GitLab del gobierno ecuatoriano (MINTEL): forja de código abierto donde ministerios y entidades públicas publican su software (FirmaEC, Quipux, gob.ec, entre otros).

## Proyectos Open Source

### Facturación Electrónica / SRI

- [open-api-facturacion-sri](https://github.com/AngeloBarzolaVillamar/open-api-facturacion-sri) - API REST open source en NestJS para facturación electrónica Ecuador SRI. Facturas, NC, ND, retenciones, guías de remisión. Firma XAdES-BES, multi-tenant, BullMQ, Docker.
- [f-sri](https://github.com/XaviMontero/f-sri) - Sistema de facturación electrónica libre y open-source para Ecuador con integración completa al SRI. Genera PDFs, firma digital y API RESTful.
- [facturaec](https://github.com/pabloveintimilla/facturaec) - Librería PHP para manejar facturas electrónicas del Ecuador (SRI).
- [Open-SRI](https://github.com/nulldoomer/Open-SRI) - SDK open-source multi-lenguaje para facturación electrónica del SRI: generación XML, firma digital, envío y autorización.
- [SRI-Xades-Signer](https://github.com/Juanja1306/SRI-Xades-Signer) - Librería Python para generar firmas digitales XML (XAdES-BES) compatibles con el SRI.
- [SriYa](https://github.com/JJQuispillo/SriYa) - API open-source de facturación electrónica SRI en .NET, self-hosted (XML, firma digital, integración SRI).
- [sri-cli](https://github.com/luismanuu/sri-cli) - CLI + MCP server para facturación electrónica SRI Ecuador: emitir y validar facturas desde terminal o agentes de IA.
- [go_ec_sri_invoice_signer](https://github.com/nelsonmarro/go_ec_sri_invoice_signer) - Implementación en Go del firmador de facturas electrónicas (XAdES-BES) para Ecuador.
- [factura-electronica-ec](https://github.com/Dantell12/factura-electronica-ec) - Generador y firmador de comprobantes electrónicos del SRI.
- [facturacionec](https://github.com/jonacastroeras/facturacionec) - Facturación open source para Ecuador.
- [odoo-ecuador](https://github.com/odoo-ecuador/odoo-ecuador) - Localización ecuatoriana para Odoo (ERP open source), con módulos de facturación, contabilidad y finanzas adaptados a Ecuador.
- [sri-mcp](https://github.com/smooth-coder/sri-mcp) - Servidor MCP para descargar documentos del SRI Ecuador.
- [mcp-sri](https://github.com/mcphub-ec/mcp-sri) - Servidor MCP para emisión directa de facturas electrónicas al SRI con firma XAdES-BES.
- [cobra-mcp](https://github.com/Motivandollc/cobra-mcp) - Servidor MCP de facturación electrónica del SRI. Emite facturas, notas de venta y retenciones.
- [SriInvoiceProcessing](https://github.com/Wason1797/SriInvoiceProcessing) - Herramienta Python para extraer datos relevantes de facturas del SRI.
- [tax-calculator](https://github.com/mario-m2/tax-calculator) - Plugin WordPress para cálculo de impuestos en Ecuador.
- [sribot](https://github.com/cesardlinx/sribot) - Bot web para hacer devolución de impuestos en el SRI Ecuador.
- [ViaSRI](https://github.com/egorky/ViaSRI) - Integración ERPNext ↔ SRI Ecuador: automatización de facturación electrónica y cumplimiento tributario.
- [autotaxflow](https://github.com/alicelabs-llc/autotaxflow) - Motor automatizado de flujo tributario para Ecuador: integración SRI, generación de proformas, automatización de cumplimiento.
- [ecu_ir_model](https://github.com/kevinplc191924/ecu_ir_model) - Calculadora automatizada de Impuesto a la Renta (IR) para Ecuador, en Python.
- [odoo-ice-module](https://github.com/bistropay/odoo-ice-module) - Módulo Odoo para cálculo de ICE, reporte SRI Form 105 e integración EDI para cervecerías artesanales en Ecuador.
- [WHMCSEcuadorTAXIDValidator](https://github.com/linkeia/WHMCSEcuadorTAXIDValidator) - Módulo WHMCS para validación de cédulas y RUC ecuatorianos.
- [customs-bi-project](https://github.com/JCentt/customs-bi-project) - Solución de Business Intelligence para el Servicio Nacional de Aduana del Ecuador.

### Datos Abiertos, Gobierno y Transparencia

- [enighur-2025-analisis](https://github.com/LuisReinoso/enighur-2025-analisis) - Análisis reproducible de microdatos ENIGHUR 2024-2025 (INEC). Desmonta el mito del ingreso promedio: 65,8% de hogares gana menos que la media de $1.135, mediana real $838. Python, datos CC BY 4.0, sitio con gráficos.
- [EcuDataMCP](https://github.com/DweskZ/EcuDataMCP) - Servidor MCP para que IAs (Claude, ChatGPT, Gemini, Cursor) consulten datos abiertos de Ecuador. Unifica CKAN (1,581 datasets de 98+ instituciones), trámites de gob.ec y 18 categorías temáticas. 11 tools: búsqueda, preview de CSVs, consulta de trámites (RUC, pasaporte, cédula), sin API key. Docker, Python, MIT.
- [osint-api](https://github.com/daxrpm/osint-api) - API para investigar datos abiertos en Ecuador.
- [data-explorer-ecuador](https://github.com/odmoreno/data-explorer-ecuador) - Exploración de iniciativas de parlamento abierto en Ecuador usando tecnología.
- [ecuador-administrative-divisions](https://github.com/open-admin-data/ecuador-administrative-divisions) - Divisiones administrativas de Ecuador: 24 provincias, 221 cantones, 1042 parroquias — datos abiertos.
- [ecuadorian-legal-codes](https://github.com/alicelabs-llc/ecuadorian-legal-codes) - Legislación ecuatoriana en JSON legible por máquina: COIP, COGEP, CC, CT, CRE, CNJ (3,847+ artículos). Ideal para RAG legal, compliance, NLP y fine-tuning de LLMs. MIT.

### Gobierno Electrónico

Software público desarrollado por MINTEL y otras entidades del Estado ecuatoriano, alojado en [Minka](https://minka.gob.ec/), la forja de código abierto del gobierno.

- [CTI - cti-app](https://minka.gob.ec/mintel/ge/cti/cti-app) - Nueva versión del Sistema de Contratación de Tecnologías de la Información del Estado ecuatoriano (en desarrollo).
- [FirmaEC - firmadigital-api](https://minka.gob.ec/mintel/ge/firmaec/firmadigital-api) - Servicio que conecta el firmador standalone de FirmaEC con los sistemas requirentes.
- [FirmaEC - firmadigital-libreria](https://minka.gob.ec/mintel/ge/firmaec/firmadigital-libreria) - Librería core de firma digital: firma, verifica documentos y valida certificados emitidos por Entidades Certificadoras del Ecuador. GNU AGPL v3.
- [FirmaEC - firmadigital-servicio](https://minka.gob.ec/mintel/ge/firmaec/firmadigital-servicio) - Servicio que comunica FirmaEC con el sistema requirente para la firma digital de documentos.
- [gob.ec (gobec)](https://minka.gob.ec/mintel/ge/rutr/gobec) - Módulo Drupal base de la plataforma gob.ec: gestiona trámites, instituciones y regulaciones del Ecuador.
- [gobec_forms](https://minka.gob.ec/mintel/ge/rutr/gobec_forms) - Módulo de digitalización de formularios y trámites de la plataforma Gob.ec.
- [Quipux - quipux-app](https://minka.gob.ec/mintel/ge/quipux/quipux-app) - Sistema core de gestión documental usado por instituciones públicas ecuatorianas. GNU AGPL v3.

### MCP / AI Agents

- [mcp-contifico](https://github.com/mcphub-ec/mcp-contifico) - Servidor MCP para integrar agentes IA con el ERP Contífico. Gestión de inventario, clientes y facturación.
- [mcp-computrabajo](https://github.com/georgegiosue/mcp-computrabajo) - Servidor MCP para acceder a listados de empleo de Computrabajo en Latinoamérica (incluye Ecuador).
- [deley-ecuador-legal-plugin](https://github.com/admin-deley/deley-ecuador-legal-plugin) - Plugin para Claude Code con normativa, jurisprudencia y case briefs ecuatorianos.

### Comercio y Turismo

- [TunguMarket](https://github.com/kiramman-mp3/TunguMarket) - Plataforma unificada y multiplataforma de comercio electrónico y marketplace para Ecuador.
- [etvx](https://github.com/georod/etvx) - Explorador de viajes y turismo de Ecuador.
- [Ecuador-Travel-Journal](https://github.com/erickariasec/Ecuador-Travel-Journal) - App React + Vite con los mejores lugares para visitar en Ecuador.

### Educación

- [goscraper.edu.ec](https://github.com/Club-de-Software-EPN/goscraper.edu.ec) - CLI para extraer información de páginas web de instituciones de educación superior del Ecuador.
- [Dashboard-Higher-Education-Ecuador](https://github.com/RobertoZevallos/Dashboard-Higher-Education-Ecuador) - Dashboard con datos y recomendaciones para stakeholders universitarios en Ecuador.
- [educational-institutions-DB](https://github.com/BarbDMC/educational-institutions-DB) - Buscador de la oferta universitaria en Ecuador para estudiantes.
- [financial-education-ecuador](https://github.com/mairaramon/financial-education-ecuador) - Proyecto de investigación sobre la influencia de la educación financiera en Ecuador.

### Civic Tech y Seguridad

- [Pulso](https://github.com/StevSant/buildathon_openai) - PWA mobile-first de seguridad ciudadana para Ecuador: reporte de incidentes urbanos con IA (foto y audio), verificación automática.

### COVID-19 / Datos y Visualización

- [covid19-monitor](https://github.com/juanmnl/covid19-monitor) - Dataviz accesible y tracker de COVID-19 en Ecuador.
- [COVID19_EC](https://github.com/pablora19/COVID19_EC) - Datos oficiales en CSV de los reportes de COVID-19 en Ecuador.
- [Ecuador-Covid19](https://github.com/juanmnl/Ecuador-Covid19) - Listado de iniciativas y recursos tecnológicos para enfrentar la crisis del Covid-19 en Ecuador.
- [covid19EC](https://github.com/loreabad6/covid19EC) - Dataviz de datos Covid en Ecuador.
- [covid-ec](https://github.com/anthonymanotoa/covid-ec) - Análisis de datos de la evolución del Covid en Ecuador.
- [COVID19-Ecuador](https://github.com/capa2ooo/COVID19-Ecuador) - Data analysis de la evolución y propagación del coronavirus en Ecuador.
- [ec-covid19](https://github.com/byron7cueva/ec-covid19) - Monorepo con información oficial del COE Nacional Ecuador.

### Comunidad y Colecciones

- [floss-ecuador](https://github.com/pythonecuador/floss-ecuador) - Colección sobre Software Libre y Open Source del Ecuador.
- [made-in-ecuador](https://github.com/IonicaBizau/made-in-ecuador) - Lista de proyectos open source hechos en Ecuador, organizados por lenguaje.
- [pythonecuador/pythonecuador.github.io](https://github.com/pythonecuador/pythonecuador.github.io) - Sitio web de la comunidad de Python del Ecuador.

## Aprendizaje

*(sección por completar — PRs bienvenidos: bootcamps, cursos, universidades con programas de CS/software relevantes)*

## Licencia

[CC0](LICENSE) - Dominio público. Copiá, adaptá, usá como quieras.
