# git-tips

Este repositorio trata de varios tips y buenas prácticas para el correcto uso de git y github.

## el commit perfecto

Para realizar un buen commit en una rama, se debe hacer un commit por cada cambio importante en el archivo.
- no debes incluir todos los cambios en un solo commit, ya que el seguimiento del versionado se torna difícil.

## Flujo de trabajo ideal

Para tener un flujo de trabajo profesional en un repositorio, se debe seguir un modelo de long-life branches y short-life branches.

Entendiendo que:
- __Long-life Branches__ son para flujos principales como master (producción), y/o development.
- __Short-life Branches__ son para características que se añaden al branch development.
  - al momento de finalizar una característica se debe hacer un pull request, para que el cambio sea evaluado.
  - Si hay cambios en el repositorio remoto, efectuar un git pull en el branch correspondiente. 
