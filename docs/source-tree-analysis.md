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
├── audio/                       # Gravações de áudio
│   └── ferias-01-17-2026 11.18.mp3 # Notas de áudio da viagem
│
├── Rotas_Tiger900RallyPro/      # Arquivos GPX para GPS Garmin
│   ├── 01_Rota_Cenica_Completa.gpx # Rota completa ida+volta (16 waypoints)
│   ├── 02_Rota_Ida_Cenica.gpx      # Apenas ida cênica (6 waypoints)
│   ├── 03_Rota_Volta_Asfaltada.gpx # Volta por asfalto (7 waypoints)
│   └── 04_Rota_Volta_Cenica.gpx    # Volta cênica alternativa
│
└── docs/                        # Documentação gerada (este diretório)
    ├── index.md                    # Índice mestre
    ├── project-overview.md         # Visão geral
    ├── source-tree-analysis.md     # Este arquivo
    ├── data-inventory.md           # Inventário de dados
    ├── usage-guide.md              # Guia de uso
    ├── camping-option.md           # Opção de acampamento
    ├── checklist-viagem.md         # Checklist de preparação
    ├── roteiro-dia-a-dia.md        # Itinerário detalhado
    ├── guia-emergencias.md         # Hospitais, mecânicas, emergências
    ├── pontos-interesse.md         # Atrações turísticas
    ├── guia-gastronomico.md        # Onde comer
    ├── manutencao-viagem.md        # Cuidados com a moto
    ├── guia-clima.md               # Previsão climática
    ├── dicas-fotografia.md         # GoPro, Insta360, melhores spots
    ├── guia-vale-vinhedos.md       # Rota de moto pelo Vale dos Vinhedos
    ├── guia-acesso-canions.md      # Acesso de moto aos cânions
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

### `/audio/`

Gravações de áudio capturadas durante o planejamento ou a viagem:
- Notas de voz para referência rápida
- Gravações com ideias e lembretes

### `/Rotas_Tiger900RallyPro/`

Arquivos GPX compatíveis com:
- Garmin BaseCamp
- Garmin Zumo/Montana/eTrex
- My Triumph App (via Bluetooth)
- Qualquer app que suporte GPX (OsmAnd, Kurviger, etc.)

**Arquivos disponíveis:**
| Arquivo | Descrição |
|---------|-----------|
| `01_Rota_Cenica_Completa.gpx` | Roteiro completo de 15 dias |
| `02_Rota_Ida_Cenica.gpx` | Trecho Goiânia → Urubici |
| `03_Rota_Volta_Asfaltada.gpx` | Retorno rápido (padrão) |
| `04_Rota_Volta_Cenica.gpx` | Retorno cênico (alternativa) |

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
| `.mp3` | MPEG Audio | Gravações de áudio |
| `.json` | JSON | Metadados do scan |

---

*Atualizado em: 2026-01-17*
