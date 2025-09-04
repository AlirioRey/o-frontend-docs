# MCI OCA
1) Instalar/actualizar OCA vía Docker/compose.
2) No tocar odoo.conf ni credenciales.
3) Siempre un plan aprobado (Imhotep) para upgrade/rollback.
4) Log en docs/agents/handoff/.
5) Probar en staging antes de producción.
6) Config en código; secretos fuera de Git (.env + gestor).
7) Si falla upgrade, rollback inmediato.
