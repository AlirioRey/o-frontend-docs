Carpetas: tasks/ (tickets), handoff/ (pases), changes/ (patches), policies/ (reglas).
Flujo: Task → Rafael Dudamel (handoff) → Winston (tabla) → Ritchie (patch) → tú aplicas y pruebas → Mandela (env/seg) → cierre.
Patch: aplicar en rama: git checkout -b feat/T-XXXX; git apply --check changes/*.patch; git apply --reject --whitespace=fix changes/*.patch; tests; commit.
Mirror: git branch -f docs-split $(git subtree split --prefix=docs); (cd ../o-frontend-docs && git fetch ../o-frontend docs-split && git checkout -B main FETCH_HEAD && git push -u origin main)
Reglas: whitelist manda; cambios chicos; nada de secretos; un Task = un objetivo.
