# Plan de trabajo (fases / testing / resultados)
F0 Base: estructura docs/agents y policies.
F1 MinMax: SQL lectura + handoff → pequeño patch UI.
F2 OC por proveedor: plan JSON-RPC + validaciones.
F3 OCR facturas: pipeline OCR→validación→borrador factura.
F4 Reportes/KPIs: panel compras/rotación.
Testing: React (lint + ts/js build), Odoo dry-run/simulación, verificación JSON-RPC contra whitelist.
Resultados: tiempo ciclo↓, errores manuales↓, trazabilidad completa (handoff/patch/PR).
