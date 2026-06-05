graph TD
    %% Estilos Generales
    classDef step1 fill:#E3F2FD,stroke:#1565C0,stroke-width:2px,color:#0D47A1,font-weight:bold;
    classDef step2 fill:#E8F5E9,stroke:#2E7D32,stroke-width:2px,color:#1B5E20,font-weight:bold;
    classDef step3 fill:#FFF3E0,stroke:#EF6C00,stroke-width:2px,color:#E65100,font-weight:bold;
    classDef step4 fill:#F3E5F5,stroke:#6A1B9A,stroke-width:2px,color:#4A148C,font-weight:bold;
    classDef file fill:#FFFFFF,stroke:#37474F,stroke-width:1px,stroke-dasharray: 3 3,color:#37474F;
    classDef main fill:#263238,stroke:#263238,stroke-width:2px,color:#FFFFFF,font-weight:bold;

    %% Bloque Principal 1
    subgraph P1 ["Paso 1: Investigación y Requerimientos"]
        B1[Análisis del Contexto]:::step1
        D1["📄 Ficha del Recurso Turístico<br>(Contexto Técnico y Normativo)"]:::file
        D2["📁 Carpeta LABTON 2025<br>(Antecedentes y Lecciones)"]:::file
        D3["📁 Carpeta GUIA DE AVES<br>(Catálogo de +100 Especies)"]:::file
        B1 --> D1 & D2 & D3
    end

    %% Bloque Principal 2
    subgraph P2 ["Paso 2: Extracción y Curación de Datos"]
        B2[Preparación de Insumos]:::step2
        D4["📁 ESPECIES EMBLEMATICAS<br>(Base de Datos para la IA)"]:::file
        D5["📁 INFOGRAFIAS TURISTICAS<br>(Métricas y Datos Clave)"]:::file
        D6["📁 TRIPTICOS<br>(Textos Digeribles y Accesibles)"]:::file
        B2 --> D4 & D5 & D6
    end

    %% Bloque Principal 3
    subgraph P3 ["Paso 3: Arquitectura Digital (48 Horas)"]
        B3[Desarrollo Tecnológico]:::step3
        I1["📱 Interfaz de Entrada<br>(Voz, Multi-idioma, Accesible)"]:::step3
        I2["⚙️ Motor de Datos / IA<br>(Lógica y Respuestas Inteligentes)"]:::step3
        I3["🎧 Interfaz de Salida<br>(Guía Autónoma Interactiva)"]:::step3
        B3 --> I1 --> I2 --> I3
    end

    %% Bloque Final 4
    subgraph P4 ["Paso 4: Entregable Comprometido"]
        B4["🏆 PROTOTIPO FUNCIONAL<br>o Mockup Navegable de Alta Fidelidad"]:::step4
    end

    %% Conexiones entre Bloques Principales
    P1 ==> P2
    P2 ==> P3
    P3 ==> P4

    %% Asignación de Estilos a los Subgraphs (Vía títulos implícitos)
    style P1 fill:#F5F5F5,stroke:#BDBDBD,stroke-width:1px
    style P2 fill:#F5F5F5,stroke:#BDBDBD,stroke-width:1px
    style P3 fill:#F5F5F5,stroke:#BDBDBD,stroke-width:1px
    style P4 fill:#ECEFF1,stroke:#90A4AE,stroke-width:2px
