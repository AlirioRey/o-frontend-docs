# Smoke tests
0) Prerrequisitos: mirror actualizado; whitelist con stock.move(read_group,read,search_read), stock.picking(read,search_read), product.(product,template,supplierinfo)(read,search_read).
1) Rafael Dudamel: lee Task+MCI+Whitelist (URLs RAW) y emite handoff → Next=Winston.
2) Winston: JSON-RPC read_group 90d, calcula tabla (sku_id, demanda_90d, demanda_diaria, sigma_diaria, lead_time_d, SS, min, max) + EXPLAIN.
3) Dennis Ritchie: patch unified UI tabla+Descargar CSV (≤80 líneas).
4) Imhotep: plan JSON-RPC para persistir min/max (sin ejecutar).
5) Nelson Mandela: patch .env.example/SECURITY.md si aparecen variables.
6) Leonardo: wireframe de la vista.
