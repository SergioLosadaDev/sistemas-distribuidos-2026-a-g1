# Repo personal

1. Crear fork → repo de clase  
2. optional-activity  

******

# repo-api

- **develop**: recibe las HU provenientes de `hu-dev`.  
- **qa**: recibe las HU provenientes de `hu-qa`.  
- **release.x**: agrupa los cambios recibidos desde `qa`, una vez cuenten con *approved*, pero con su propia sub-rama, es decir, `HU-realease`.  
- **main**: recibe `release.x`. Esto ocurre en cada corte.  

## Nota

- Las ramas principales (`develop`, `qa`, `main`) solo pueden configurarse de forma directa una única vez, en la primera pre-organización del repositorio.  
- Las ramas principales no deben permitir cambios directos. Solo se permiten cambios mediante *Merge Requests (MR)*, es decir, a través de `HU-ambiente`, según el alcance de la HU y su respectivo DoD.  
- Cada rama principal puede recibir *hot-fix*, siempre que el cambio corresponda a esta naturaleza. Asimismo, se debe garantizar la estabilización de ambientes, ya sea de forma ascendente o descendente.  
