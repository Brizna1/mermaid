mermaid
graph TD
    A[Tratamiento] --> B[Terapia de combinación Artemisinina (ACT)]
    A --> C[Cloroquina (CQ) y Primaquina (PQ)]
    A --> D[Quinina y Artemisinina (IV o IM)]
    A --> E[Tratamiento Intermitente Preventivo (IPT)]
    A --> F[Derivados de Artemisinina]
    A --> G[Tafenoquina]
    A --> H[Monitoreo de la resistencia]

    B --> B1[Artemether-lumefantrine (AR-LM)]
    B --> B2[Artesunate amodiaquine (AS-AQ)]
    B --> B3[Artesunate-mefloquine (AS-MQ)]
    B1 --> B1a[Plasmodium falciparum no complicado]
    B2 --> B2a[Plasmodium falciparum no complicado]
    B3 --> B3a[Plasmodium falciparum no complicado]
    B1a --> B1b[Según las guías específicas de dosificación para cada combinación]
    B2a --> B2b[Según las guías específicas de dosificación para cada combinación]
    B3a --> B3b[Según las guías específicas de dosificación para cada combinación]

    C --> C1[Cloroquina (CQ)]
    C --> C2[Primaquina (PQ)]
    C1 --> C3[Plasmodium vivax en regiones sin resistencia a la cloroquina]
    C2 --> C3
    C3 --> C4[CQ: 25 mg/kg de peso en 3 días]
    C3 --> C5[PQ: 0.25 mg/kg día bajo supervisión]

    D --> D1[Quinina]
    D --> D2[Artemisinina]
    D1 --> D3[Malaria severa]
    D2 --> D3
    D3 --> D4[Administración intravenosa (IV) o intramuscular (IM) hasta que el paciente pueda tomar pastillas]

    E --> E1[Sulfadoxina-primetamina (S/P)]
    E1 --> E2[Mujeres embarazadas en zonas de alta transmisión]
    E2 --> E3[Al menos dos veces en el segundo y tercer trimestre, tres veces si hay infección con VIH]

    F --> F1[Artemetero]
    F --> F2[Dihidroartemisinina]
    F --> F3[Artesunato]
    F1 --> F4[Formas eritrocíticas y gametocitos del parásito]
    F2 --> F4
    F3 --> F4
    F4 --> F5[Actúan rápido, afectan eritrocitos y gametocitos mediante la producción y liberación de radicales libres]

    G --> G1[Tafenoquina]
    G1 --> G2[Más eficaz y menos tóxica que la primaquina, aprobada para personas mayores de 16 años]
    G2 --> G3[Vida media de 1-2 semanas]

    H --> H1[Evaluación in vitro, ensayos clínicos y marcadores moleculares]
