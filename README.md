# POS - Sistema de Control de Inventario y Facturación

## 📌 Descripción general

Sistema tipo Punto de Venta (POS) desarrollado en **PHP y MySQL**, orientado a pequeños y medianos negocios (tiendas, distribuidoras, comercios). Permite gestionar el inventario de productos, registrar ventas en el punto de venta, generar facturas y controlar clientes y proveedores.

## 🧩 Problema que resuelve

Muchos comercios pequeños siguen llevando su inventario y sus ventas en cuadernos o en hojas de cálculo sueltas, lo que genera:

- Pérdida de control sobre el stock real disponible.
- Errores en el cálculo de ventas y facturación.
- Falta de trazabilidad de compras a proveedores y ventas a clientes.
- Imposibilidad de generar reportes confiables para tomar decisiones.

Este sistema centraliza inventario, ventas, facturación y reportes en una sola herramienta, reduciendo errores manuales y dando visibilidad en tiempo real del negocio.

## 🛠️ Stack tecnológico propuesto

- **Backend:** PHP
- **Base de datos:** MySQL
- **Frontend:** HTML, CSS, JavaScript (AJAX para el punto de venta)
- **Generación de PDF:** DomPDF / TCPDF (facturas y reportes)
- **Control de versiones:** Git + GitHub (Issues, Milestones, Projects)
- **Gestión ágil:** Kanban sobre GitHub Projects

## 🗂️ Estructura de épicas / fases planeadas

| Épica | Alcance | Fecha límite |
|---|---|---|
| **Épica 1 — Autenticación y Gestión de Usuarios** | Login, roles y permisos, administración de usuarios, recuperación de contraseña, bitácora de accesos | 2026-10-03 |
| **Épica 2 — Núcleo del Negocio (Inventario y Facturación)** | Catálogo de productos, control de stock, alertas de stock mínimo, punto de venta, generación de facturas | 2026-11-07 |
| **Épica 3 — Reportes, Cierre y Despliegue** | Clientes, proveedores y compras, reportes de ventas, cierre de caja, respaldo y despliegue | 2026-12-05 |

Cada épica está representada como un **Milestone** en GitHub, y cada funcionalidad como un **Issue** en formato de Historia de Usuario (HU-01 a HU-15).

## 📋 Tablero Kanban

El seguimiento del proyecto se gestiona en GitHub Projects, con las columnas:

`Backlog` → `En Progreso` → `En Revisión` → `Completado`

y un campo personalizado de **Prioridad** (Alta / Media / Baja).

🔗 **Tablero:** (https://github.com/AndresGalindo2227/pos-inventario-facturacion.git)

## 🎬 Video de Presentación

_(enlace del video)_
