# CHESS GAME APP

TODO: cambiar github action para que se actualice las referencias de los submodulos automaticamente cuando se hace commit en algun submodulo
TODO: Docker para empaquetar aplicacion
TODO: Subida documentacion

```bash
git submodule deinit -f .
git submodule update --init --recursive
git submodule foreach --recursive git reset --hard
git submodule foreach --recursive git pull origin main
```
