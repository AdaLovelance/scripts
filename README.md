# scripts
## MigroLxc
### Recibo un fichero de texto como párametro
### El fichero debe contener una lista de nombres de máquinas, una por fila para migrar a otro servidor
### Recibo el servidor a donde voy a migrar como segúndo parámetro
### Paro las máquinas y realizo la migración con rsync y vuelvo a levantar el contenedor en el destino remoto
### USAGE: bash scriptmigra fichero servidor
