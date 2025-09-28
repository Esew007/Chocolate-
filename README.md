# Diagrama de Flujo - Proceso de Elaboración de Chocolate

```mermaid
graph TD
  A([Inicio]) --> B[Recepción de cacao]
  B --> C[Tostado]
  C --> D[Descascarillado]
  D --> E[Tostado de canela]
  E --> F[Triturado de pan]
  F --> G[Moler cacao]
  G --> H[Revolver canela, pan, azúcar y chocolate]
  H --> I[Revolver y moler la mezcla]
  I --> J[Entablillado]
  J --> K[Empaquetado]
  K --> L([Fin])

  %% Estilos
  classDef inicio fill:#8FBC8F,stroke:#2E8B57,stroke-width:2px,color:white;
  classDef proceso fill:#4682B4,stroke:#27408B,stroke-width:1px,color:white;
  classDef fin fill:#CD5C5C,stroke:#8B0000,stroke-width:2px,color:white;

  class A inicio;
  class B,C,D,E,F,G,H,I,J,K proceso;
  class L fin;
