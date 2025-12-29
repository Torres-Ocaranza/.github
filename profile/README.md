<div align="center">

# 🏢 Torres Ocaranza

**Empresa líder en enfierradura, construcción y suministro de acero desde 1983**

[![Website](https://img.shields.io/badge/Website-torresocaranza.cl-2ea44f?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.torresocaranza.cl)
[![GitHub](https://img.shields.io/badge/GitHub-Organization-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Torres-Ocaranza)
[![Email](https://img.shields.io/badge/Email-info@torresocaranza.cl-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@torresocaranza.cl)

*Soluciones internas de software para optimizar nuestros procesos operativos*

</div>

---

## 📊 Estadísticas de la Organización

<div align="center">

![GitHub Org's stars](https://img.shields.io/github/stars/Torres-Ocaranza?style=social&logo=github)
![GitHub followers](https://img.shields.io/github/followers/Torres-Ocaranza?style=social&logo=github)
![GitHub repos](https://img.shields.io/badge/Repositorios-16-blue?style=flat-square&logo=github&logoColor=white)
![GitHub last commit](https://img.shields.io/github/last-commit/Torres-Ocaranza/.github?style=flat-square&logo=github&logoColor=white)

</div>

---

## 📋 Sobre la Organización

<div align="center">

**Torres Ocaranza** es una empresa especializada en enfierradura, suministro e instalación de acero para construcción, con más de **42 años de experiencia** en el mercado nacional (desde 1983).

</div>

### 🏭 Capacidad y Infraestructura

- ⚡ **+80.000 toneladas anuales** de capacidad instalada
- 🏗️ **4 plantas** estratégicamente ubicadas en Chile
- 📍 **Cobertura nacional** en proyectos de construcción
- 🎯 **Áreas de negocio**: Minería, Infraestructura, Energía, Salud, Inmobiliario

### 💻 Soluciones Internas

Los repositorios en esta organización contienen **soluciones internas de software** desarrolladas para optimizar nuestros procesos operativos:

- 📄 **Gestión documental y certificaciones** - Sistemas para gestión de documentos, certificaciones de calidad y trazabilidad
- 🚛 **Trazabilidad logística y transporte** - Seguimiento GPS en tiempo real, gestión de viajes y despachos
- 📐 **Cubicación y optimización** - Sistemas de cubicación de planos y optimización de cortes de acero
- 🏗️ **Sistemas de control de obras** - Gestión integral de obras, producción, facturación y calidad
- 📊 **Gestión de proyectos industriales** - Control de producción, metalurgia, estados de pago y líneas de crédito
- 💰 **Gestión comercial y financiera** - Cotizaciones, líneas de crédito, estados de pago y facturación

---

## 🚀 Proyectos Principales

### 🔷 Gestión Documental y Certificaciones

<table>
<tr>
<td width="50%">

#### [AceroConexionDossier](https://github.com/Torres-Ocaranza/AceroConexionDossier)
**Aplicación de escritorio Python** para la carga, validación y gestión automatizada de documentos de certificación de calidad en S3. Sistema con optimizaciones avanzadas de rendimiento y detección automática de recursos del sistema.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- ✅ Subida automática de PDFs a AWS S3 con validación de integridad
- 📊 Trazabilidad completa en PostgreSQL (tablas `trazabilidad_subidas` y `estado_its`)
- ⚡ Optimización de consultas SQL (hasta 36x más rápido) - Cache de estados, `estado_its` como fuente principal
- 🔄 Pool de conexiones thread-local PostgreSQL (4.24 archivos/segundo, 74% más rápido)
- 📧 Notificaciones por correo con resúmenes detallados (solo bloqueos nuevos)
- 🛡️ Gestión de estados (SUBIDO, FALLIDO, PARCIAL, BLOQUEADO) con 4 Leyes de procesamiento
- 🔁 Reintentos automáticos con límite configurable para archivos corruptos
- 🧹 Limpieza inteligente de archivos comprimidos (4 reglas de protección)
- 🎯 Detección automática de recursos (CPU, RAM) para optimización de hilos
- 📋 Interfaz gráfica moderna con barra de progreso y cancelación de procesos

</td>
<td width="50%">

#### [Acero-Back-v2](https://github.com/Torres-Ocaranza/Acero-Back-v2)
**Backend modular NestJS v1.3.2** para gestión documental, trazabilidad y automatización en proyectos de acero. Arquitectura moderna con Cloudflare Tunnel, migración PostgreSQL completada, y sistema completo de permisos RBAC.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

- 🔐 Autenticación JWT con refresh tokens (30 min access, 24h refresh)
- 🌐 Cloudflare Tunnel para exposición segura (`api.torresocaranza.com`)
- 🔄 Sincronización automática con Cubigest (cron jobs configurable)
- 📧 Notificaciones por email con plantillas Handlebars personalizables
- ☁️ Manejo avanzado de archivos S3 (ZIP masivo, URLs firmadas, preview)
- 📚 Documentación Swagger interactiva (`/api`)
- 🔑 Sistema RBAC completo con permisos granulares por módulo/acción
- 💓 Sistema de heartbeat para mantener sesiones activas
- 📊 Estadísticas de usuarios con métricas de uso y seguridad
- 🔍 Búsqueda de seguridad avanzada (blocked, inactive, failed-logins)
- 🔗 Integración con Acero-Front-v2 y sincronización manual de obras

</td>
</tr>
<tr>
<td width="50%">

#### [Acero-Front-v2](https://github.com/Torres-Ocaranza/Acero-Front-v2)
**Portal de clientes React v0.13.8** para gestión documental, permisos y certificaciones. Aplicación moderna con Material UI, TypeScript, Vite y optimizaciones de build avanzadas.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=flat-square&logo=mui&logoColor=white)

- 🔐 Autenticación JWT integrada con manejo de sesión
- 🗂️ Navegación jerárquica (Sucursales → Obras → ITs → Archivos)
- 📁 Visualización de PDFs en navegador y descarga masiva ZIP
- 📄 Sistema completo de rectificaciones (subida individual/múltiple inteligente)
- 👥 Gestión avanzada de usuarios con geolocalización (banderas, IPs, VPN detection)
- 🔑 Control granular de permisos por rol y página
- 📊 Dashboard de estadísticas con 8 métricas clave
- 🔍 Filtros de seguridad avanzados (5 criterios)
- 🚀 Code-splitting implementado (vendor chunks separados)
- 🔄 Sistema de reconexión inteligente para desconexiones de red
- 🌐 Desplegado en Cloudflare Workers con SPA routing
- 🔗 Integración completa con Acero-Back-v2

</td>
<td width="50%">

#### [TransportManager-backend](https://github.com/Torres-Ocaranza/TransportManager-backend)
**Backend Node.js/Express v1.9.6** con arquitectura en capas (DDD Pragmático) para sistema de seguimiento GPS. Soporte dual SQLite/PostgreSQL, WebSocket en tiempo real, procesamiento OCR con BullMQ y sistema completo de despachadores.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

- 📍 Seguimiento GPS en tiempo real (WebSocket/Socket.IO con rooms)
- 🔐 Autenticación JWT con refresh tokens (HTTP-only cookies) y 2FA (TOTP)
- 📊 Sistema RBAC completo con permisos granulares por módulo/acción
- 📄 Procesamiento OCR de guías (AWS Textract) con cola BullMQ y Redis
- 📋 Gestión de guías de despacho con validación (despachador vs conductor)
- 🚛 Sistema de despachadores completo (subida de fotos/guías, asignación por RUT)
- 📊 Sistema mejorado de logs de auditoría (13 acciones críticas registradas)
- ☁️ Almacenamiento en S3 con estructura organizada (`Despacho/{obra}_{fecha}/`)
- 🔄 Soporte dual SQLite/PostgreSQL con migración automática
- 🛡️ Validación de archivos con magic numbers y protección SQL Injection
- 📧 Sistema de emails (manual guides, trip completion) con URLs firmadas

</td>
</tr>
</table>

---

### 🚛 Gestión Logística y Transporte

<table>
<tr>
<td width="50%">

#### [TransportManager-frontend](https://github.com/Torres-Ocaranza/TransportManager-frontend)
**Frontend dual v1.12.2** con panel administrativo React y visualización GPS en tiempo real. Sistema completo con replay de viajes históricos, gestión de despachadores y sistema mejorado de auditoría.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)

- 🔗 Panel administrativo React con autenticación 2FA (TOTP y códigos de respaldo)
- 🗺️ Visualización GPS en tiempo real con Leaflet y clustering de marcadores
- 📍 Sistema de replay de viajes históricos (velocidad 0.25x-32x, barra de progreso)
- 🚛 Gestión completa de viajes, choferes, transportistas y despachadores
- 📋 Gestión de guías de despacho con OCR y validación de guías faltantes
- 📊 Dashboard con métricas y estadísticas en tiempo real
- 🔐 Sistema RBAC con permisos granulares y permisos directos por usuario
- 📝 Sistema mejorado de logs de auditoría (filtros por usuario, acción, entidad, fecha)
- 🚛 Gestión de transportistas con campos de empresa (RUT y nombre)
- ⏱️ Sistema de timeout de inactividad con advertencia visual
- 🗺️ Integración Google Maps Places Autocomplete para direcciones

</td>
<td width="50%">

#### [mobiletrackinggps](https://github.com/Torres-Ocaranza/mobiletrackinggps)
**Aplicación React Native** para choferes que necesitan iniciar viajes, enviar guías y transmitir ubicación GPS en tiempo real. Sistema completo con seguimiento continuo foreground/background.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)

- 📍 Seguimiento GPS continuo (foreground/background)
- 🚛 Inicio y término de viajes con carga de guías
- 📋 Sistema de despachador (acceso por RUT, subida de fotos y guías)
- 🔄 Persistencia local y sincronización offline
- 📊 Integración REST/WebSocket con backend
- ✅ Validaciones de RUT, permisos y ubicación
- 🔐 Autenticación con manejo de sesión

</td>
</tr>
</table>

---

### 🏗️ Sistemas de Gestión de Obras

<table>
<tr>
<td width="50%">

#### [CubigestFichaObra2](https://github.com/Torres-Ocaranza/CubigestFichaObra2)
**Sistema integral de gestión empresarial v2.0** para Torres Ocaranza. Aplicación web ASP.NET multicapa que centraliza el ciclo productivo desde recepción de órdenes hasta despacho final. 9 módulos principales con integración a sistemas externos.

![Version](https://img.shields.io/badge/version-2.0-blue?style=flat-square)

![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- 🏗️ Gestión integral de obras, producción, inventarios, RRHH, facturación y calidad
- 🔗 Integración bidireccional con INET (guías de despacho, facturación, inventarios)
- 🏭 Integración con Gerdau (materias primas, coladas, certificaciones)
- 📊 Reportería ejecutiva con dashboards y análisis de datos
- 🔐 Sistema de permisos granular por módulo (U.V/I/M, O.V/I/M, CIT.V/C, etc.)
- ⚡ Mantenimiento preventivo automatizado (actualización guías, kilos, totems)
- 📈 100+ usuarios concurrentes, 99.5% uptime, <2s tiempo de respuesta

</td>
<td width="50%">

#### [OBRACIVIL](https://github.com/Torres-Ocaranza/OBRACIVIL)
**Sistema Windows Forms** para gestión de obras civiles. Aplicación de escritorio VB.NET especializada en ingreso y gestión de piezas de acero con cálculo automático de pesos, soporte para piezas variables y generación de imágenes con cotas.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows_Forms-0078D4?style=flat-square&logo=windows&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![Crystal Reports](https://img.shields.io/badge/Crystal_Reports-FF6B35?style=flat-square&logo=crystal-reports&logoColor=white)

- 🏗️ Ingreso de piezas con formas geométricas (ID de forma, cotas a-n, ángulos k-n) y cálculo automático de pesos
- 📐 Piezas variables: barras con cotas variables (formato "valor1/valor2"), cálculo de promedios y múltiples variantes
- 🏭 Soporte obras Bechtel y normales: formatos de ingreso diferenciados (Paquete/PiezasXMarca vs Item/Cantidad)
- ⚖️ Cálculo según Norma 353: aplicación de 1% adicional, cálculo de largo real con descuentos por desarrollo y dobleces
- 🔌 Gestión de conectores: validación de diámetros según tipo, soporte para conectores izquierdo/derecho
- 📊 Hojas de despiece: organización por Obra/Plano/Figura/Nivel/Elemento/Ubicación, grabación vía servicios web
- 🖼️ Generación de imágenes: renderizado de formas con cotas y ángulos superpuestos, guardado en base de datos
- 📋 Módulos adicionales: gestión de ITs, trazabilidad de coladas, reportes Crystal Reports, códigos de barras
- 🔗 Integración con servicios web corporativos (Px_Ws) para obras, diámetros, formas y grabación de piezas

</td>
</tr>
</table>

---

### ⚙️ Sistemas Especializados

<table>
<tr>
<td width="50%">

#### [LineaCredito](https://github.com/Torres-Ocaranza/LineaCredito)
**Sistema de Línea de Crédito v1.0** (Abril 2019). Aplicación web ASP.NET MVC 5 para gestión y control de líneas de crédito otorgadas a clientes corporativos. Sistema completo con cálculo automático de disponibilidad, alertas por utilización e integración con servicios corporativos.

![ASP.NET MVC](https://img.shields.io/badge/ASP.NET_MVC-512BD4?style=flat-square&logo=.net&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- 💰 Gestión completa de líneas de crédito por cliente (RUT)
- 📊 Cálculo automático de disponibilidad en UF con actualización desde SBIF
- 🚦 Sistema de alertas por utilización (semáforo verde/ámbar/rojo)
- 🔗 Integración con Web Services de facturación y despachos
- 📄 Generación de reportes Excel con plantillas personalizadas
- 🔐 Control de acceso por perfiles (ADMIN/USER/VIEW)
- 📝 Auditoría completa de operaciones
- 📈 200+ líneas gestionadas, 500+ consultas diarias, 50+ reportes mensuales

</td>
<td width="50%">

#### [Metalurgica](https://github.com/Torres-Ocaranza/Metalurgica)
**Sistema Windows Forms** para gestión operativa metalúrgica: recepción de coladas, producción multi-máquina, despacho (bodega y camión) e integración con ERP/INET. Aplicación de escritorio con arquitectura en 3 capas y ruteo por tótem/máquina.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows_Forms-0078D4?style=flat-square&logo=windows&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- 🔐 Login corporativo con control de sesión por tótem/máquina (Registro Windows)
- 🏭 Recepción de coladas (AZA/CAP) con mapeo a códigos internos (TO/TOSOL)
- ⚙️ Producción multi-máquina con validaciones por empresa y sucursal
- 🚛 Despacho por bodega y camión con integración de báscula (Access)
- 📊 Integración con servicios SOAP corporativos (WS_Sesion, Ws_To, WsCrud, WsOperacion)
- 📄 Generación de reportes CSV y unión de PDFs (iTextSharp)
- 🔄 Trazabilidad extremo a extremo (colada → producción → despacho)
- 🔌 Integración con conectores y producción externa (Calidad y Oficina Técnica)

</td>
</tr>
<tr>
<td width="50%">

#### [EstadosdePagos](https://github.com/Torres-Ocaranza/EstadosdePagos)
**Sistema de Gestión de Estados de Pago (Proyecto D)**. Cliente Windows Forms para gestión del ciclo de vida completo de Estados de Pago (EP) para obras/contratos. Sistema con generación de reportes, adjuntos automáticos y aprobación cliente.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows_Forms-0078D4?style=flat-square&logo=windows&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- 📋 Creación, edición y seguimiento de Estados de Pago
- 📎 Adjuntos y respaldos automáticos (guías de despacho e ITs desde carpetas de red P:/, S:/)
- ✅ Aprobación cliente con trazabilidad completa
- 📄 Generación de reportes con plantillas Excel (Office Interop)
- 🔐 Autenticación integrada con servicios SOAP (WsSesion, WsOperacion, WsMensajeria)
- 📧 Notificaciones internas y exportaciones ejecutivas
- 📝 Bitácora completa de operaciones (AccionEPLog)
- 🔄 Integración con sistemas corporativos para datos de obras y EP

</td>
<td width="50%">

#### [ControlDimencional](https://github.com/Torres-Ocaranza/ControlDimencional)
**Sistema de Control Dimensional (Proyecto D)**. Aplicación web ASP.NET Web Forms para control y trazabilidad dimensional de piezas/paquetes en planta, con generación de informes PDF y notificación por correo. Sistema QA/QC con almacenamiento de imágenes en base de datos.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
![ASP.NET Web Forms](https://img.shields.io/badge/ASP.NET_Web_Forms-512BD4?style=flat-square&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- 🔍 Validación de etiquetas y consulta de información de paquetes
- 📄 Generación de informes PDF con datos de inspección (iTextSharp 5.5.12)
- 📧 Envío de notificaciones por correo con adjuntos (imágenes) - SMTP Gmail
- 🖼️ Visualización de imágenes almacenadas en SQL Server (varbinary, tipos P/PB/O/I)
- 🔐 Autenticación basada en procedimientos almacenados (SP_CONTROL_DIMENSIONAL)
- 📝 Trazabilidad completa para auditorías QA/QC
- 📋 Gestión de destinatarios de correo por obra

</td>
</tr>
<tr>
<td width="50%">

#### [Optisteel](https://github.com/Torres-Ocaranza/Optisteel)
**Sistema de optimización v1.1.0** de corte de acero con algoritmos MVP (Minimum Variable Packing) para minimizar desperdicio. Compatible con Windows 10/11, Ubuntu y macOS.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![pyvpsolver](https://img.shields.io/badge/pyvpsolver-3776AB?style=flat-square&logo=python&logoColor=white)

- 🎯 Optimización de cortes con algoritmos MVP para minimizar desperdicios
- 📊 Gestión de largos especiales y múltiples diámetros (6mm a 36mm)
- 📄 Generación automática de SKUs y reportes completos (Excel y SQLite)
- 📈 KPIs de eficiencia (porcentaje de aprovechamiento, desperdicio)
- 🪟 Compatibilidad completa con Windows 10/11 (desde 2024)

</td>
<td width="50%">

#### [CUBILINK-CERRILLOS](https://github.com/Torres-Ocaranza/CUBILINK-CERRILLOS)
**Sistema de automatización industrial** para monitoreo y control de 12 líneas de corte en planta Cerrillos. Comunicación PLC Siemens S7 con SQL Server y interfaz gráfica PyQt5.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white)
![snap7](https://img.shields.io/badge/snap7-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- 🔌 Comunicación PLC Siemens S7 (lectura/escritura de datos)
- 🗄️ Integración con SQL Server para almacenamiento de datos
- 🖥️ Interfaz gráfica PyQt5 con monitoreo en tiempo real
- ⚙️ Procesamiento asíncrono multitarea (QThread)
- 🏭 Gestión completa de 12 líneas de producción de corte

</td>
</tr>
<tr>
<td width="50%">

#### [Gestor_OC_Gerdau](https://github.com/Torres-Ocaranza/Gestor_OC_Gerdau)
**Sistema Windows Forms** para gestión integral de órdenes de compra de Gerdau (proveedor de materias primas). Aplicación de escritorio C# que automatiza el ciclo completo desde obtención de datos hasta envío vía FTP y notificaciones por correo.

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square)

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows_Forms-0078D4?style=flat-square&logo=windows&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![Crystal Reports](https://img.shields.io/badge/Crystal_Reports-FF6B35?style=flat-square&logo=crystal-reports&logoColor=white)

- 📋 Gestión de órdenes de compra: obtención de datos, creación de archivos CSV con formato Gerdau, subida vía FTP
- 📧 Notificaciones automáticas por correo electrónico del estado de envío de OC
- 🔄 Envíos automáticos programados: Packing Lists (PL) electrónicos, Bill of Materials (BOM), informes de línea de crédito
- ✅ Módulo de Calidad: certificación de viajes, gestión de lotes, descarga de certificados PDF desde IDIEM/CAP
- 📊 Módulos especializados: Calidad, Facturación, Logística, Pago, Producción
- 🔗 Integración con servicios web corporativos (WS_Gerdau, WS_TO) y FTP
- 📄 Generación de reportes con Crystal Reports

</td>
<td width="50%">

#### [PAGO](https://github.com/Torres-Ocaranza/PAGO)
**Sistema de Gestión de Cotizaciones v1.1.0** (Proyecto de Administración y Gestión de Ofertas). Aplicación web ASP.NET Web Forms para automatizar el proceso de gestión de cotizaciones comerciales, desde recepción de solicitudes hasta generación y envío de documentos.

![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
![ASP.NET Web Forms](https://img.shields.io/badge/ASP.NET_Web_Forms-512BD4?style=flat-square&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- 📋 Gestión de solicitudes de cotización desde clientes
- 📄 Creación y edición de cotizaciones técnicas (variantes TO y Tosol)
- 📑 Generación automática de documentos PDF con formato corporativo (Word Interop + iTextSharp)
- 🔄 Control de versiones y clonación de cotizaciones
- 📊 Consulta y seguimiento de estado de cotizaciones
- 📧 Envío de correos electrónicos con documentos adjuntos
- 🔗 Integración con servicios WCF (PX_Facturacion, Px_Ws_to)
- 📈 Módulo de estadísticas y reportes

</td>
</tr>
</table>

---

## 🛠️ Stack Tecnológico

<div align="center">

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=for-the-badge&logo=mui&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Infraestructura
![AWS](https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 📊 Estadísticas

<div align="center">

| Métrica | Valor |
|---------|-------|
| 📦 **Repositorios** | 16 activos (todos privados) |
| 🐍 **Python** | 3 proyectos (AceroConexionDossier, Optisteel, CUBILINK-CERRILLOS) |
| 🔷 **TypeScript/JavaScript** | 5 proyectos modernos (Backend/Frontend NestJS, React, Express) |
| 💎 **C#/VB.NET** | 8 sistemas especializados (ASP.NET MVC/Web Forms, Windows Forms) |
| 📱 **React Native** | 1 aplicación móvil (GPS Tracking) |
| 🔒 **Visibilidad** | Repositorios privados (desarrollo interno) |
| 🏭 **Capacidad** | +80.000 toneladas anuales |
| 📅 **Experiencia** | +42 años en el mercado (desde 1983) |
| 👥 **Usuarios Activos** | 100+ usuarios concurrentes (Cubigest) |
| ⚡ **Uptime** | 99.5% disponibilidad (sistemas críticos) |
| 🌐 **Plantas** | 4 plantas estratégicamente ubicadas en Chile |
| 🎯 **Áreas de Negocio** | Minería, Infraestructura, Energía, Salud, Inmobiliario |

</div>

---

## 🔐 Acceso

<div align="center">

⚠️ **Los 16 repositorios activos son privados** y requieren permisos de acceso a la organización.

El repositorio [`.github`](https://github.com/Torres-Ocaranza/.github) es público pero solo contiene configuración y plantillas para la organización (no cuenta como repositorio activo de negocio).

Para solicitar acceso a los repositorios privados, contacta con los administradores de la organización.

</div>

---

## 📝 Notas

- ✅ Estos repositorios contienen **soluciones internas** desarrolladas para uso exclusivo de Torres Ocaranza
- 🔄 Los proyectos están en constante desarrollo y mejora continua
- 📚 Se siguen buenas prácticas de desarrollo y arquitectura limpia (DDD Pragmático, Clean Architecture)
- 📖 Documentación técnica disponible en cada repositorio
- ⚡ Sistemas optimizados para producción y pruebas
- 🔒 Todos los repositorios activos son privados y requieren permisos de acceso
- 🚀 Versionado semántico (SemVer) aplicado en proyectos modernos
- 🧪 Testing implementado en proyectos críticos (Jest, pytest, React Testing Library)

---

## 📧 Contacto

<div align="center">

[![Website](https://img.shields.io/badge/Website-www.torresocaranza.cl-2ea44f?style=flat-square&logo=google-chrome&logoColor=white)](https://www.torresocaranza.cl)
[![Email](https://img.shields.io/badge/Email-info@torresocaranza.cl-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:info@torresocaranza.cl)
[![Phone](https://img.shields.io/badge/Teléfono-%2B56%202%202380%209664-25D366?style=flat-square&logo=whatsapp&logoColor=white)](tel:+56223809664)

**Dirección**: Vista Clara #2351, Cerrillos, Santiago, Chile

</div>

### 👥 Equipo de Tecnología

<div align="center">

| Nombre | Cargo | Email |
|--------|-------|-------|
| **Roberto Becerra** | Gerente Informática y Procesos | [![Email](https://img.shields.io/badge/Email-rbecerra@torresocaranza.cl-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rbecerra@torresocaranza.cl) |
| **René Auger** | Jefe de Soporte e Infraestructura – Desarrollo TI | [![Email](https://img.shields.io/badge/Email-rauger@torresocaranza.cl-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rauger@torresocaranza.cl) |

</div>

---

<div align="center">

### **Desarrollado con ❤️ por Torres Ocaranza**

*Última actualización: Enero 2025*

[![GitHub](https://img.shields.io/badge/GitHub-Torres--Ocaranza-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Torres-Ocaranza)

</div>