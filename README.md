# Escape Room 3D

Proyecto colaborativo de laboratorio de Git + GitHub + Visual Studio Code + Unity.

## Integrantes
- Joel Illanes
- Alexander Vigabriel
- Kevin Alanes
- Santiago Vargas

## Ramas
- main
- Dev
- Feature_PlayerMovement
- Feature_Interaction
- Feature_Animation
- Feature_Puzzle

## Estrategia de ramas
- `main`: solo versiones estables. Recibe cambios únicamente por Pull Request desde `Dev`.
- `Dev`: rama de integración. Las Features se integran aquí primero.
- `Feature_*`: cada integrante trabaja en su Feature, creada **desde Dev**.

| Integrante | Rol | Rama principal |
|---|---|---|
| Joel Illanes | Integrador (C) | `Dev` |
| Alexander Vigabriel | A | `Feature_PlayerMovement`, `Feature_Puzzle` |
| Kevin Alanes | B | `Feature_Interaction` |
| Santiago Vargas | QA / bitácora (D) | `Feature_Animation` |

## Objetivo
Explorar una habitación, resolver un código, abrir un cofre, obtener una llave y abrir la puerta de salida.

Controles: WASD para moverse, E para interactuar.

## Requisitos
- Unity 6000.3.23f1
- Escena principal: `Assets/Scenes/MainScene.unity`
