# Casos de Uso

## Identificación

### Actores
- Trabajador
- Usuario extiende Trabajador
- Administrador extiende Usuario

### Casos de Uso
 
- Trabajador:
  - Crear fichaje

- Usuario:
  - READ Fichaje Diario
  - READ Informe
    - READ Dia
    - READ Semana
    - READ Mes

- Administrador(Usuario):
  - READ Fichaje Diario
  - UPDATE Fichaje Diario
  - READ Informe
  - CRUD Usuario

## Priorización
1. Fichaje
2. Revisión de tiempo

## Detalles
- Fichaje: Cuando se extrae del Lector de huellas los registros
- Revisión de tiempo: Cuando los trabajadores revisan cuanto tiempo han trabajado en un día, semana o mes y cuanto les falta para acabar.

<details>
<summary>Casos de uso</summary>

|  |  |
| -- | -- |
| ![](../../imagenes/casosDeUso/diagramaCasosDeUso.svg) | [Codigo PUML](../../modelosUML/casosDeUso/casosDeUso.puml) |

</details>

<details>
<summary>Diagrama de contexto</summary>

|  |  |
| -- | -- |
| ![](../../imagenes/casosDeUso/diagramaContexto.svg) | [Codigo PUML](../../modelosUML/casosDeUso/diagramaContexto.puml) |

</details>