flowchart TD
    A[Cliente llega al negocio] --> B[Explica lo que necesita]
    B --> C[Dueño anota el pedido en papel o de memoria]
    C --> D[¿Hay material disponible?]
    
    D -->|Sí| E[Acuerdan precio y fecha de entrega]
    D -->|No| F[Dueño sale a comprar el material]
    F --> E

    E --> G[Dueño fabrica el trabajo]
    G --> H[¿Está listo a tiempo?]
    
    H -->|Sí| I[Cliente recoge y paga]
    H -->|No| J[Se avisa al cliente del retraso]
    J --> G

    I --> K[Fin del proceso]

    flowchart TD
    A[Cliente llega al taller] --> B[Describe el trabajo necesario]
    B --> C[Dueño anota medidas y precio en papel]
    C --> D[¿Hay suficiente material?]
    
    D -->|Sí| E[Inicia el trabajo]
    D -->|No| F[Compra el material faltante]
    F --> E

    E --> G[¿Hay otros trabajos pendientes?]
    G -->|Sí| H[Organiza por orden de llegada]
    G -->|No| I[Termina el trabajo]
    H --> I

    I --> J[Avisa al cliente]
    J --> K[Cliente recoge y paga]
    K --> L[Fin del proceso]
