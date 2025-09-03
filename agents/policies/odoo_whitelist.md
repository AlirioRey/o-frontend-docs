# Odoo whitelist
Modelos:
- purchase.order: search_read, read, name_search, create, write
- stock.picking:  search_read, read, create, write
- stock.move:     search_read, read
- res.partner:    search_read, read, name_search
Prohibido: unlink y cualquier write en account.move/account.payment/res.users.
Reglas: sólo JSON-RPC; nada de SQL crudo; “contenedor-primero” para OCA.
