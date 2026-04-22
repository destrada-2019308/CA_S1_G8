flowchart TD
A[Cliente llega al taller] --> B[Describe el trabajo necesario]
B --> C[Dueño anota medidas y precio en papel]
C --> D{¿Hay suficiente material?}

    D -->|Sí| E[Inicia el trabajo]
    D -->|No| F[Compra el material faltante]
    F --> E

    E --> G{¿Hay otros trabajos pendientes?}
    G -->|Sí| H[Organiza por orden de llegada]
    G -->|No| I[Termina el trabajo]
    H --> I

    I --> J[Avisa al cliente]
    J --> K[Cliente recoge y paga]
    K --> L[Fin del proceso]