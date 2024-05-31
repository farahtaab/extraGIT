# Actividades extra de GIT

## Modifica el mensaje del último commit
Para cambiar el mensaje del último commit usaremos el comando siguiente `git commit --amend -m "[mensaje]"`

![Cambiar-mensaje-commit](imagenes/cambiarMssj.png)

## Elimina el último commit 
Tenemos varias opciones:
| **Comando**                      | **Descripción**                                                                                               | **Consideraciones**                                                                                     |
|----------------------------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| `git reset --soft HEAD~1`        | Deshace el último commit pero mantiene los cambios en el área de preparación (staging area).                   | No afecta los archivos en tu directorio de trabajo. Útil si quieres modificar el commit antes de hacerlo de nuevo.  |
| `git reset --hard HEAD~1`        | Deshace el último commit y elimina los cambios realizados en ese commit.                                       | Elimina permanentemente los cambios del último commit. Úsalo con precaución.                            |
| `git revert HEAD`                | Crea un nuevo commit que revierte los cambios del último commit.                                               | Seguro para usar en commits ya publicados en un repositorio remoto. No altera el historial de commits.  |

Usaremos la siguiente `git reset --hard HEAD~1`

![Eliminar-ult-commit](imagenes/eliminarUltCommit.png)

## Recuperar el último commit eliminado
![Recuperar-ult-commit](imagenes/resuperarUltCommit.png)

## Git tag

## Git stash

## Git workflow
