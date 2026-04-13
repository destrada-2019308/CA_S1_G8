# Diagrama de Flujo — Negocios Actuales

## Negocio 1 — Vidriería

mermaid
flowchart TD
    A[Cliente llega al negocio] --> B[Describe lo que necesita]
    B --> C[Dueño anota el pedido en papel o memoria]
    C --> D{¿Tiene material disponible?}
    D -->|Sí| E[Acuerdan precio y fecha de entrega]
    D -->|No| F[Dueño sale a comprar material]
    F --> E
    E --> G[Dueño fabrica el trabajo]
    G --> H{¿Está listo a tiempo?}
    H -->|Sí| I[Cliente recoge y paga]
    H -->|No| J[Se avisa al cliente del retraso]
    J --> G
    I --> K[Fin]


## Negocio 2 — Taller de Herrería

mermaid
flowchart TD
    A[Cliente llega al taller] --> B[Describe el trabajo que necesita]
    B --> C[Dueño anota medidas y precio en papel]
    C --> D{¿Tiene material suficiente?}
    D -->|Sí| E[Inicia el trabajo]
    D -->|No| F[Compra material]
    F --> E
    E --> G{¿Tiene otros trabajos pendientes?}
    G -->|Sí| H[Organiza por orden de llegada]
    G -->|No| I[Termina el trabajo]
    H --> I
    I --> J[Avisa al cliente]
    J --> K[Cliente recoge y paga]
    K --> L[Fin]
