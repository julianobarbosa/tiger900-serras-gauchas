# Análise da Estrutura de Arquivos

## Árvore do Projeto

```
tiger900-serras-gauchas/
│
├── README.md                    # Documentação principal do projeto
│
├── assets/                      # Materiais auxiliares
│   ├── README.md                   # Descrição dos assets
│   ├── Roteiro_Tiger900_SerrasGauchas.xlsx  # Planilha master de custos
│   ├── Links_Triumph_MyApp.txt     # URLs Google Maps e Triumph App
│   ├── logo_tiger900.png           # Logomarca da moto
│   ├── mapa_preview.png            # Visualização da rota completa
│   └── rota_cenica.jpg             # Foto da Serra do Rio do Rastro
│
├── Rotas_Tiger900RallyPro/      # Arquivos GPX para GPS Garmin
│   ├── 01_Rota_Cenica_Completa.gpx # Rota completa ida+volta (16 waypoints)
│   ├── 02_Rota_Ida_Cenica.gpx      # Apenas ida cênica (6 waypoints)
│   └── 03_Rota_Volta_Asfaltada.gpx # Volta por asfalto (7 waypoints)
│
└── docs/                        # Documentação gerada (este diretório)
    ├── index.md                    # Índice mestre
    ├── project-overview.md         # Visão geral
    ├── source-tree-analysis.md     # Este arquivo
    ├── data-inventory.md           # Inventário de dados
    ├── usage-guide.md              # Guia de uso
    └── project-scan-report.json    # Metadados do scan
```

## Descrição dos Diretórios

### `/` (Raiz)

Contém o README principal com visão geral do projeto, custos estimados e instruções básicas.

### `/assets/`

Materiais de suporte para a viagem:
- **Planilha Excel**: Fonte de verdade para custos diários, hospedagens reservadas, postos de abastecimento
- **Links**: URLs prontas para abrir no Google Maps ou enviar para o My Triumph App
- **Imagens**: Logo, mapa de preview e foto ilustrativa

### `/Rotas_Tiger900RallyPro/`

Arquivos GPX compatíveis com:
- Garmin BaseCamp
- Garmin Zumo/Montana/eTrex
- My Triumph App (via Bluetooth)
- Qualquer app que suporte GPX (OsmAnd, Kurviger, etc.)

### `/docs/`

Documentação técnica gerada automaticamente pelo workflow BMAD document-project.

## Formatos de Arquivo

| Extensão | Formato | Uso |
|----------|---------|-----|
| `.md` | Markdown | Documentação legível |
| `.gpx` | GPS Exchange Format | Rotas e waypoints |
| `.xlsx` | Excel OpenXML | Planilha de custos |
| `.txt` | Texto puro | Links e notas |
| `.png/.jpg` | Imagem | Assets visuais |
| `.json` | JSON | Metadados do scan |
