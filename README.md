# Gestão de Chamados de TI

Projeto de implantação de um sistema e processo de gestão de chamados de TI, aplicando práticas de gerenciamento de projetos e metodologias ágeis para aumentar a visibilidade, a organização e a previsibilidade do atendimento.

---

## 🎯 Objetivo

Estruturar e implantar um modelo centralizado para registro, triagem, priorização e acompanhamento de chamados de TI, reduzindo solicitações dispersas, melhorando o tempo de resposta e garantindo maior controle sobre as entregas.

---

## 🧩 Contexto e Problema

A necessidade do projeto surgiu a partir de gargalos comuns na rotina de suporte e TI quando não há um fluxo centralizado:
- **Solicitações fora do fluxo:** Pedidos recebidos por mensagens diretas, e-mails soltos ou conversas informais, dificultando o rastreamento.
- **Falta de clareza na prioridade:** Demandas urgentes disputando espaço com solicitações simples sem critério objetivo.
- **Baixa visibilidade do andamento:** Usuários sem retorno claro sobre o status do chamado e dificuldade para acompanhar gargalos na fila.
- **Retrabalho no atendimento:** Chamados abertos sem informações mínimas necessárias para diagnóstico e resolução.

Este projeto estrutura a implantação de um fluxo padronizado para resolver esses pontos na operação.

---

## 📋 Escopo do Projeto

O projeto abrange desde o mapeamento inicial das necessidades até o acompanhamento pós-implantação:
- Levantamento de requisitos funcionais e operacionais;
- Padronização do ciclo de vida do chamado e das categorias de atendimento;
- Definição de critérios de priorização e níveis de serviço (SLA);
- Estruturação e priorização do backlog;
- Planejamento das fases de implantação, testes e alinhamento com os usuários;
- Acompanhamento de indicadores, riscos e lições aprendidas.

---

## 🔄 Fluxo de Atendimento (Ciclo de Vida do Chamado)

Para garantir clareza tanto para quem solicita quanto para quem executa, o chamado segue um fluxo definido:

1. **Aberto:** Registro inicial com título objetivo, categoria, descrição do problema, impacto e evidências/prints (quando aplicável).
2. **Em Triagem:** Validação das informações, classificação (incidente, requisição de serviço, acesso, melhoria), definição de prioridade e direcionamento.
3. **Em Andamento:** Atuação técnica, investigação ou execução da solicitação com registros de evolução.
4. **Aguardando Solicitante / Terceiros:** Aguardando retorno do usuário, aprovação ou ação de fornecedor/outra área.
5. **Resolvido:** Solução aplicada e validada; aguarda confirmação ou encerramento pelo fluxo padrão.
6. **Fechado:** Chamado concluído, documentado e finalizado.

---

## 🚦 Critérios de Priorização e SLA

As demandas são priorizadas combinando **Impacto** (quantos usuários/processos são afetados) e **Urgência** (o quão rápido a resolução é necessária):

| Prioridade | Descrição do Cenário | Exemplo Prático | Expectativa de Acompanhamento |
| :--- | :--- | :--- | :--- |
| **Crítica** | Parada de serviço essencial ou bloqueio severo da operação | Sistema principal fora do ar para toda a equipe | Atendimento imediato e acompanhamento contínuo |
| **Alta** | Impacto relevante em atividade importante, com alternativa limitada | Usuário sem acesso a sistema necessário para entrega do dia | Tratamento prioritário com atualizações frequentes |
| **Média** | Problema ou solicitação com contorno simples ou impacto moderado | Ajuste de permissão secundária ou dúvida operacional | Entrada organizada no fluxo normal de atendimento |
| **Baixa** | Melhoria, solicitação futura ou dúvida sem bloqueio imediato | Sugestão de melhoria de fluxo ou demanda planejada | Backlog planejado conforme capacidade da equipe |

---

## 🛠️ Metodologia e Práticas Aplicadas

- **Gerenciamento de Projetos:** Definição de escopo, divisão em fases, marcos de entrega, controle de riscos e plano de implantação.
- **Scrum / Práticas Ágeis:** Organização do trabalho em backlog priorizado, entregas incrementais, inspeção contínua e adaptação conforme feedback.
- **Gestão de Backlog:** Itens descritos com clareza, priorização contínua por valor/urgência e separação entre implantação e rotina operacional.
- **Melhoria Contínua:** Uso de métricas e lições aprendidas para refinar categorias, campos obrigatórios e tempos de atendimento.

---

## 🗺️ Etapas de Implantação

1. **Fase 1 — Levantamento e Diagnóstico:** Mapeamento do cenário atual, principais tipos de chamados, dores dos usuários e requisitos.
2. **Fase 2 — Desenho do Processo e Backlog:** Definição de status, categorias, matriz de prioridade, campos obrigatórios e backlog inicial.
3. **Fase 3 — Configuração e Testes:** Parametrização do sistema, testes de fluxo ponta a ponta e ajustes de usabilidade.
4. **Fase 4 — Piloto e Treinamento:** Validação em ambiente controlado, alinhamento com a equipe e orientação aos usuários.
5. **Fase 5 — Virada (Go-Live) e Acompanhamento:** Início da operação oficial, monitoramento de indicadores, ajustes finos e registro de lições aprendidas.

---

## 📊 Indicadores de Acompanhamento (KPIs)

Para avaliar a eficiência do processo na operação, o acompanhamento é feito por meio dos seguintes indicadores:
- **Volume de chamados por categoria e prioridade:** Identifica gargalos e demandas recorrentes.
- **Tempo médio de primeira resposta e resolução:** Mede a agilidade do atendimento e o cumprimento dos SLAs.
- **Taxa de reabertura:** Aponta se os chamados estão sendo encerrados com resolução definitiva e comunicação clara.
- **Chamados abertos vs. resolvidos no período:** Mostra o equilíbrio entre entrada de demandas e capacidade de entrega.

---

## ⚠️ Principais Riscos e Mitigações

- **Adesão baixa ou abertura fora do padrão:** *Mitigação:* Formulário simples, campos essenciais bem definidos e comunicação clara sobre o canal oficial.
- **Excesso de chamados marcados como "Crítica":** *Mitigação:* Critérios objetivos de impacto e urgência alinhados com as áreas solicitantes.
- **Falta de clareza na responsabilidade de cada etapa:** *Mitigação:* Definição explícita dos status do fluxo e das pendências externas ou do solicitante.

---

## 📌 Entregas do Projeto

- [x] Levantamento de requisitos
- [x] Criação e priorização do backlog
- [x] Planejamento da implantação
- [x] Definição das atividades, fluxo e critérios de SLA
- [x] Acompanhamento das entregas
- [x] Registro das lições aprendidas

---

## 💡 Lições Aprendidas

- Um fluxo simples e bem comunicado gera muito mais adesão do que um processo complexo logo na implantação.
- Critérios objetivos de priorização reduzem ruídos e mantêm o foco nas demandas de maior impacto.
- Documentar requisitos, etapas e riscos desde o início garante previsibilidade na execução e facilita a evolução contínua do processo.

---
## 📂 Estrutura do Repositório

```text
gestao-chamados-ti/
├── README.md
└── docs/
    ├── backlog-implantacao.md
    └── checklist-implantacao.md

## 👩‍💻 Autora

**Cláudia Palomares**  
[GitHub](https://github.com/claupalomars)
