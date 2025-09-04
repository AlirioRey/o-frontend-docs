# Odoo whitelist

Modelos:

- product.product: search_read, read
- product.template: search_read, read
- product.supplierinfo: search_read, read
  Prohibido: unlink y cualquier write en account.move/account.payment/res.users.
  Reglas: sólo lectura SQL para análisis; JSON-RPC para operaciones; “contenedor-primero” para OCA.
 - stock.move:          search_read, read, read_group
 - stock.picking:       search_read, read
 - stock.picking.type: search_read, read
