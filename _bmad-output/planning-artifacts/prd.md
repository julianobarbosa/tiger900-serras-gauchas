---
stepsCompleted:
  - step-01-init
  - step-02-discovery
  - step-03-success
  - step-04-journeys
  - step-05-domain-skipped
  - step-06-innovation-skipped
  - step-07-project-type
  - step-08-scoping
  - step-09-functional
  - step-10-nonfunctional
  - step-11-polish
  - step-12-complete
completedAt: "2026-01-17T19:30:00Z"
inputDocuments:
  - docs/index.md
  - docs/project-overview.md
  - docs/roteiro-dia-a-dia.md
documentCounts:
  brief: 0
  research: 0
  brainstorming: 0
  projectDocs: 3
classification:
  projectType: data-repository
  domain: travel-tourism
  complexity: low
  projectContext: brownfield
workflowType: 'prd'
---

# Product Requirements Document - tiger900-serras-gauchas

**Author:** Barbosa
**Date:** 2026-01-17

## Executive Summary

Repositório de planejamento e navegação para viagem de moto de 15 dias pelas Serras Gaúchas (19/01 → 02/02/2026), com rotas GPX para Garmin, planilha de custos e documentação completa para integração com dispositivos de navegação e My Triumph App.

## Success Criteria

### User Success

- Rotas GPX carregam corretamente no Garmin e My Triumph App
- Informações de hospedagem, alimentação e combustível acessíveis em cada etapa
- Alertas sobre trechos fechados (Corvo Branco, Tirolesa) claramente documentados
- Alternativas de rota (retorno cênico vs asfaltado) disponíveis para decisão durante a viagem
- Guias específicos para cada região (vinícolas, cânions, serras) completos e úteis

### Business Success

- Viagem completa de 15 dias realizada com sucesso
- Orçamento mantido dentro do planejado (~R$ 8.000)
- Zero problemas de navegação por falta de informação
- Tempo de planejamento minimizado com documentação centralizada

### Technical Success

- 4 arquivos GPX funcionais em formato 1.1
- Planilha Excel com custos detalhados por dia
- 17+ documentos markdown organizados e indexados
- Links Google Maps funcionais para backup de navegação

### Measurable Outcomes

| Métrica | Target |
|---------|--------|
| Arquivos GPX válidos | 4/4 |
| Documentação completa | 100% |
| Waypoints mapeados | 16+ |
| Guias por região | 5+ |

## Product Scope

### MVP - Minimum Viable Product

- [x] Rotas GPX completas (ida + volta + alternativas)
- [x] Planilha de custos por dia
- [x] Roteiro dia-a-dia detalhado
- [x] Guias de emergência e manutenção
- [x] Links Google Maps de backup

### Growth Features (Post-MVP)

- [ ] Integração com app de tracking (Scenic, Calimoto)
- [ ] Versão offline completa para smartphone
- [ ] Fotos dos pontos de interesse
- [ ] Reviews de hospedagens após a viagem
- [ ] Versão interativa com mapa

### Vision (Future)

- Compartilhamento da rota com comunidade de motociclistas
- Template reutilizável para futuras viagens
- Integração com apps de previsão do tempo
- Versão web interativa com filtros por interesse

## User Journeys

### Journey 1: Barbosa - O Planejador (Pré-viagem)

**Persona:** Barbosa, 35 anos, DevOps Engineer, motociclista experiente com Tiger 900 Rally Pro. Planeja sua primeira grande viagem de moto pelas Serras Gaúchas.

**Opening Scene:** É dezembro de 2025. Barbosa está em casa em Goiânia, olhando o calendário de janeiro. Depois de um ano intenso de trabalho, ele finalmente tem 15 dias de férias. A Tiger 900 está na garagem, pedindo estrada.

**Rising Action:**
1. Pesquisa destinos → descobre as Serras Gaúchas, Cânions, Vale dos Vinhedos
2. Tenta planejar no Google Maps → rotas confusas, sem waypoints salvos
3. Precisa de: hospedagem, custos, pontos de interesse, alertas de estradas
4. Cria o repositório → organiza GPX, planilha, documentação

**Climax:** Com tudo organizado, Barbosa sincroniza os GPX com o Garmin, envia rotas para o My Triumph App, e tem a planilha de custos no celular. Pela primeira vez, sente que a viagem está sob controle.

**Resolution:** Parte em 19/01 com confiança total. Cada dia está mapeado, cada parada planejada, cada custo estimado. A documentação vira seu copiloto digital.

---

### Journey 2: Barbosa - O Viajante (Durante a viagem)

**Opening Scene:** Dia 6, 07:00. Barbosa acorda em Urubici com 5°C. Hoje é o dia da Serra do Rio do Rastro - o clímax da viagem.

**Rising Action:**
1. Consulta `roteiro-dia-a-dia.md` → confirma horário de saída e rota
2. Checa `guia-clima.md` → vê que neblina é comum de manhã, melhor esperar
3. Liga o GPS → rota já carregada, waypoints marcados
4. Consulta `guia-emergencias.md` → anota número da concessionária mais próxima

**Climax:** Desce a Serra do Rio do Rastro com 284 curvas, parando nos mirantes mapeados. O GPS indica cada ponto de parada. As fotos ficam incríveis porque chegou no horário certo.

**Resolution:** Termina o dia em Bom Jardim da Serra, dentro do orçamento, sem surpresas. Marca o dia como concluído na planilha.

---

### Journey 3: Barbosa - Resolução de Problemas

**Opening Scene:** Dia 8, na estrada para os Cânions. A corrente da moto parece frouxa, fazendo barulho estranho.

**Rising Action:**
1. Para com segurança → consulta `manutencao-viagem.md`
2. Encontra seção "Corrente" → procedimento de verificação e lubrificação
3. Verifica ferramentas → kit básico que o guia recomendou
4. Resolve o problema na beira da estrada

**Climax:** Corrente ajustada, moto funcionando. Não precisou de guincho nem mecânico.

**Resolution:** Continua a viagem com confiança. A documentação de manutenção salvou o dia.

---

### Journey 4: Futuro Motociclista - Template Reutilizável

**Persona:** Carlos, membro do grupo de Tiger no WhatsApp. Viu Barbosa postar fotos da viagem.

**Opening Scene:** Carlos quer fazer a mesma rota em março de 2026, quando o Corvo Branco reabrir.

**Rising Action:**
1. Barbosa compartilha o repositório GitHub
2. Carlos clona o repo → tem toda a estrutura pronta
3. Adapta datas na planilha → custos recalculados automaticamente
4. Adiciona waypoints próprios → vinícolas diferentes

**Climax:** Carlos tem sua própria versão do roteiro em 2 horas, não 2 semanas.

**Resolution:** A documentação vira template para a comunidade de motociclistas.

---

### Journey Requirements Summary

| Journey | Capabilities Reveladas |
|---------|----------------------|
| Planejador | GPX export, planilha estruturada, índice navegável |
| Viajante | Consulta rápida, offline-first, integração GPS |
| Problemas | Guias de troubleshooting, contatos de emergência |
| Template | Estrutura reutilizável, documentação clara |

## Data Repository Specific Requirements

### Project-Type Overview

Este é um repositório de dados de viagem otimizado para:
- Consulta offline durante a viagem
- Integração com dispositivos GPS (Garmin)
- Sincronização com apps de navegação (My Triumph App)
- Planejamento e tracking de custos

### Technical Architecture Considerations

| Componente | Tecnologia | Justificativa |
|------------|------------|---------------|
| **Dados de Rota** | GPX 1.1 | Padrão universal para GPS |
| **Custos** | XLSX | Fórmulas, filtros, compatibilidade |
| **Documentação** | Markdown | Legível, versionável, offline-ready |
| **Navegação** | Google Maps URLs | Backup universal |
| **Versionamento** | Git/GitHub | Histórico, colaboração, backup |

### Data Format Requirements

#### GPX Files
- Formato: GPX 1.1 (XML)
- Waypoints: Nomeados com padrão `Cidade - Tipo`
- Tracks: Ordenados por sequência de viagem
- Metadados: Criador, data, descrição

#### Documentation Structure
- Índice centralizado (`docs/index.md`)
- Guias temáticos por assunto
- Links relativos entre documentos
- Formatação markdown padrão

### Implementation Considerations

- **Offline-first:** Documentação acessível sem internet
- **Device-agnostic:** Funciona em qualquer leitor de markdown
- **GPS-compatible:** GPX testados em Garmin e apps
- **Human-readable:** Preferir clareza sobre automação

## Project Scoping & Phased Development

### MVP Strategy & Philosophy

**MVP Approach:** Problem-Solving MVP - resolver o problema imediato de planejamento de viagem
**Status:** ✅ MVP Completo - documentação pronta para uso na viagem

### MVP Feature Set (Phase 1) - DONE

**Core User Journeys Supported:**
- ✅ Planejamento pré-viagem (GPX, custos, roteiro)
- ✅ Consulta durante a viagem (guias, emergências)
- ✅ Resolução de problemas (manutenção, contatos)

**Must-Have Capabilities:**
- ✅ 4 arquivos GPX funcionais
- ✅ Planilha de custos completa
- ✅ Roteiro dia-a-dia detalhado
- ✅ Guias por região (vinícolas, cânions, serras)
- ✅ Guia de emergências e manutenção
- ✅ Checklist de preparação

### Post-MVP Features

**Phase 2 (Pós-viagem):**
- [ ] Adicionar fotos e vídeos dos locais visitados
- [ ] Atualizar reviews de hospedagens após experiência real
- [ ] Corrigir waypoints com coordenadas exatas
- [ ] Documentar custos reais vs estimados

**Phase 3 (Compartilhamento):**
- [ ] Criar versão pública para comunidade de motociclistas
- [ ] Template genérico para outras viagens
- [ ] Versão web interativa com mapa
- [ ] Integração com apps de tracking

### Risk Mitigation Strategy

| Risco | Mitigação |
|-------|-----------|
| **Estrada fechada** | Rotas alternativas documentadas |
| **GPS sem sinal** | Google Maps URLs como backup |
| **Problema mecânico** | Guia de manutenção + contatos |
| **Custo excedido** | 3 opções de orçamento (hotel/misto/camping) |

## Functional Requirements

### Navegação GPS

- FR1: Usuário pode carregar rotas GPX em dispositivos Garmin
- FR2: Usuário pode sincronizar rotas com My Triumph App via Bluetooth
- FR3: Usuário pode visualizar waypoints com nomes descritivos
- FR4: Usuário pode escolher entre 4 variações de rota (completa, ida, volta asfaltada, volta cênica)

### Planejamento de Custos

- FR5: Usuário pode consultar custos estimados por dia
- FR6: Usuário pode comparar 3 opções de orçamento (hotel/misto/camping)
- FR7: Usuário pode ver detalhamento por categoria (hospedagem, alimentação, combustível)
- FR8: Usuário pode atualizar valores na planilha conforme reservas reais

### Consulta de Roteiro

- FR9: Usuário pode consultar itinerário dia-a-dia com horários sugeridos
- FR10: Usuário pode ver distâncias e tempo estimado entre pontos
- FR11: Usuário pode identificar dias de exploração vs deslocamento
- FR12: Usuário pode consultar alertas sobre trechos fechados

### Guias Regionais

- FR13: Usuário pode consultar guia específico do Vale dos Vinhedos
- FR14: Usuário pode consultar guia de acesso aos cânions
- FR15: Usuário pode ver pontos de interesse por região
- FR16: Usuário pode consultar opções gastronômicas locais

### Suporte de Emergência

- FR17: Usuário pode consultar contatos de emergência (hospitais, mecânicas)
- FR18: Usuário pode seguir procedimentos de manutenção básica
- FR19: Usuário pode verificar checklist de preparação pré-viagem
- FR20: Usuário pode consultar informações climáticas por região

### Documentação e Índice

- FR21: Usuário pode navegar por índice centralizado de documentos
- FR22: Usuário pode acessar documentação offline (markdown local)
- FR23: Usuário pode usar links de backup Google Maps

## Non-Functional Requirements

### Acessibilidade Offline

- NFR1: Toda documentação acessível sem conexão de internet
- NFR2: Arquivos GPX funcionam sem dependência de servidor
- NFR3: Planilha Excel funciona offline após download
- NFR4: Markdown renderizável em qualquer editor de texto

### Compatibilidade de Dispositivos

- NFR5: GPX compatível com Garmin (Zumo, Montana, eTrex)
- NFR6: GPX compatível com My Triumph App
- NFR7: GPX compatível com apps de terceiros (OsmAnd, Kurviger, Scenic)
- NFR8: Documentação legível em smartphones (responsive markdown)

### Confiabilidade de Dados

- NFR9: Todos os waypoints com coordenadas GPS válidas
- NFR10: Links Google Maps funcionais e atualizados
- NFR11: Custos estimados com margem de erro documentada
- NFR12: Alertas sobre informações que podem mudar (estradas fechadas)

### Manutenibilidade

- NFR13: Estrutura de arquivos clara e organizada
- NFR14: Versionamento via Git para histórico de mudanças
- NFR15: Índice centralizado para navegação
- NFR16: Padrão de nomenclatura consistente em arquivos

