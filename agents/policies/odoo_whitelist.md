# Odoo whitelist
Modelos permitidos:
- purchase.order: search_read, read, name_search, create, write
- stock.picking: search_read, read, create, write
- stock.move: search_read, read
- res.partner: search_read, read, name_search
Prohibido: unlink; write en account.move/account.payment/res.users.
Reglas:
- Solo JSON-RPC; NO SQL crudo.
- OCA "contenedor-primero" (instalar/actualizar/rollback vía docker compose exec odoo ...).
- Toda acción sensible pasa por patch/plan y tu aprobación.
