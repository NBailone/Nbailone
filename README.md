# Nicolás Bailone

**Ingeniero en Sistemas de Información** · Automatización de procesos y datos · Argentina

Identifico procesos manuales y repetitivos y los convierto en flujos automáticos y verificables: extracción de datos, ETL, OCR e integración con APIs. También desarrollo aplicaciones web full stack. Vengo del mundo de la logística y el comercio exterior, así que entiendo el negocio que hay detrás de los datos, no solo la parte técnica.

[LinkedIn](https://www.linkedin.com/in/nicolas-bailone-2976462a3) · [nbailone@gmail.com](mailto:nbailone@gmail.com)

Trabajo principalmente con **Python, Java, SQL y APIs REST**.

---

## Proyectos destacados

## [multiagente-operaciones](https://github.com/NBailone/multiagente-operaciones): automatización de operaciones logísticas

Desarrollé una aplicación de escritorio para Windows que coordina el flujo diario de un agente de carga: descarga de correos, lectura de tickets de balanza con OCR, control de datos contra planillas Excel, impresión documental y envío de correos. La persona solo valida las excepciones.

Antes, cada operación exigía revisar manualmente los papeles de exportación que se llevan los choferes, con foco constante en detectar errores. Con el sistema en marcha, ese control manual dejó de ser necesario y se redujo de forma notable el tiempo dedicado a la tarea.

- **Armado automático de planillas:** a partir de las carpetas de carga diarias completa las planillas mensuales (envíos, cobro y precintos de aduana con su permiso asignado) y detecta operaciones compartidas entre dos permisos.
- **OCR con dos motores en paralelo:** PaddleOCR local y modelos de visión por API (Gemini, Gemma vía OpenRouter). Si uno falla o duda, el otro cubre la lectura.
- **Validación campo por campo** de tickets contra planillas y datos de aduana, con diferencias marcadas en rojo.
- **Backup automático** de las carpetas de trabajo de las exportaciones, y modo "Súper Auto" que encadena todo el flujo rutinario en un solo paso.
- **Seguridad y distribución:** credenciales y API keys encriptadas (PBKDF2), fuera del control de versiones, y empaquetado como `.exe` con PyInstaller e instalador idempotente.
- Desarrollado con un enfoque **spec-driven**: cada cambio se especifica primero (`openspec/`) y después se implementa. Más de 100 commits.

**Stack:** Python · CustomTkinter · PaddleOCR · Tesseract · OpenPyXL · IMAP · pywin32 · PyInstaller

---

## [sistema-analisis-financiero](https://github.com/NBailone/sistema-analisis-financiero): análisis de mercados financieros

Desarrollé una aplicación web full stack con un pipeline completo de datos financieros: extracción desde múltiples APIs → ETL (limpieza, validación y almacenamiento) → cálculo de indicadores técnicos (RSI, MACD, ADX, entre otros) → visualización interactiva, con generación de predicciones sobre activos financieros.

- Extracción en tiempo real e histórica desde múltiples APIs.
- Pipeline ETL automatizado con Pentaho Data Integration.
- Predicciones sobre activos financieros y visualizaciones interactivas con Chart.js.

**Stack:** Java (Servlets + JSP) · Python · Pentaho · MySQL · Chart.js

---

## [sistema-inventario-ventas](https://github.com/NBailone/sistema-inventario-ventas): gestión comercial

Aplicación web full stack para gestión comercial, con arquitectura MVC en capas y patrón DAO.

- Gestión de productos y control de stock.
- Registro de ventas y administración de clientes.
- Control de inventario en tiempo real.

**Stack:** Java EE (Servlets + JSP) · MySQL / MariaDB · Bootstrap

---

## Tecnologías en mis proyectos

| Área | Tecnologías |
| --- | --- |
| Lenguajes | Java, Python, SQL, JavaScript |
| Datos y ETL | Pentaho Data Integration, MySQL / MariaDB, procedimientos almacenados, APIs REST, OpenPyXL |
| OCR e IA | PaddleOCR, Tesseract, modelos de visión por API (OpenRouter) |
| Backend | Java EE (Servlets, JSP), MVC, DAO |
| Frontend | HTML5, CSS3, JavaScript, AJAX, Bootstrap, Chart.js |
| Automatización | CustomTkinter, pywin32, PyInstaller, PowerShell, IMAP |
| Herramientas | Git, GitHub, Apache Tomcat, Cloudflare Tunnel |

---

## Formación

Ingeniería en Sistemas de Información, Universidad Tecnológica Nacional (Facultad Regional Rosario).
