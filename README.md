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

🔗 **Tablero:** (https://github.com/users/AndresGalindo2227/projects/4)

## 🎬 Video de Presentación

_(https://drive.google.com/file/d/1ikqT4gVnxnSo4dEZ2NtQ-K7CE3UvVpff/view?usp=sharing)_

## Sprint 1 — Plan

**Fecha de inicio:** 24 de septiembre de 2026
**Fecha de fin estimada:** 08 de octubre de 2026

**Historias de Usuario seleccionadas para este sprint:**

- **HU-01** — Login de usuario
- **HU-02** — Gestión de roles y permisos
- **HU-03** — Registro y administración de usuarios del sistema
- **HU-06** — Registro y catálogo de productos
- **HU-07** — Control de stock e inventario en tiempo real

**Criterio de selección:**

Se eligieron estas 5 historias porque pertenecen a las dos primeras épicas del proyecto (Autenticación y Núcleo del Negocio) y son **prerrequisito funcional** de todo lo demás: sin login ni roles no se puede controlar quién factura o quién administra inventario, y sin el catálogo de productos y el control de stock no existe base para implementar el punto de venta ni la facturación (HU-09 y HU-10, planificadas para el Sprint 2). Priorizar la cimentación del sistema reduce el riesgo de tener que rehacer trabajo más adelante.
