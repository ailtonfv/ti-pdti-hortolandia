# 06 — SLA e Governança Operacional

Este diretório consolida as políticas, padrões, métricas e instrumentos de governança operacional que definem a qualidade, a previsibilidade e a continuidade dos serviços de Tecnologia da Informação da Prefeitura de Hortolândia.  

O objetivo é estabelecer parâmetros claros de desempenho, atendimento, disponibilidade e tempo de resposta, fortalecendo a relação entre o DITI, as demais secretarias e a população.

---

## 1. Finalidade

Este repositório reúne os elementos centrais para a gestão de SLAs (Service Level Agreements), compondo a espinha dorsal da governança operacional:

- definição de níveis de serviço por categoria;
- responsabilidades do DITI e das áreas demandantes;
- métricas, indicadores e modelos de cálculo;
- critérios de escalonamento e priorização;
- modelos de relatórios mensais e dashboards;
- integração com o Catálogo de Serviços (Catálogo DITI);
- padronização dos fluxos de atendimento técnico.

---

## 2. Escopo do SLA Institucional

Os SLAs abrangem, entre outros:

- **Suporte técnico ao usuário**  
  (abertura de chamados, prazos, prioridades)

- **Infraestrutura de Data Center**  
  (disponibilidade, energia, refrigeração, backups)

- **Redes e Conectividade**  
  (latência, estabilidade, janelas de manutenção)

- **Sistemas corporativos e integrações**  
  (atualizações, janelas de deploy, incidentes)

- **Segurança da Informação**  
  (respostas a incidentes, monitoramento, alertas)

- **Serviços de dados e analytics**  
  Incluindo a futura operação do **Data Lakehouse Municipal**.

---

## 3. Indicadores-Chave (KPIs)

Os KPIs mínimos recomendados:

- **Disponibilidade (%)**
- **MTTR — Mean Time to Repair**
- **MTBF — Mean Time Between Failures**
- **Tempo de Resposta**
- **Tempo de Atendimento**
- **Taxa de Chamados Reabertos**
- **Nível de Satisfação do Usuário (CSAT)**

Esses indicadores poderão ser usados em dashboards do Power BI, Metabase ou Grafana.

---

## 4. Classificação de Prioridade

Uma matriz padrão baseada em *Impacto × Urgência*:

| Prioridade | Descrição | Exemplo |
|-----------|-----------|---------|
| **P1 – Crítico** | Serviço parado | Data Center fora, sistema de habitação indisponível |
| **P2 – Alto** | Degradação severa | Lentidão sistêmica, queda de rede em unidade |
| **P3 – Médio** | Impacto moderado | Problemas isolados em estações de trabalho |
| **P4 – Baixo** | Sem impacto operacional | Solicitações administrativas |

---

## 5. Fluxo Operacional (Modelo Simplificado)

```mermaid
flowchart TD
A[Abertura do Chamado] --> B[Classificação da Prioridade]
B --> C[Designação da Equipe Responsável]
C --> D[Execução da Ação Técnica]
D --> E[Validação com o Usuário]
E --> F[Encerramento e Registro no SLA]

