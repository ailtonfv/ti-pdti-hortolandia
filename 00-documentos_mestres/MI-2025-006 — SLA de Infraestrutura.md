# MI-2025-006 — SLA de Infraestrutura e Operações (DITI)

**Departamento de Infraestrutura da Tecnologia da Informação (DITI)**  
**Prefeitura Municipal de Hortolândia**  
**Ano-base: 2025**

---

## 1. Finalidade

Estabelecer o Acordo de Nível de Serviço (SLA) específico para as atividades de **infraestrutura, suporte técnico, redes, data center, disponibilidade e continuidade operacional**, executadas pelo **DITI**.

Este documento complementa o MI-2025-007, que regula os serviços de desenvolvimento, evolução e interoperabilidade (DSTI).

---

## 2. Escopo

Abrange os seguintes serviços:

- Gestão de redes e conectividade  
- Suporte técnico de Nível 1 e 2  
- Administração de servidores e máquinas virtuais  
- Monitoramento e continuidade operacional  
- Segurança básica de infraestrutura  
- Backups, restaurações e contingência  
- Atendimento a incidentes físicos ou lógicos  
- Gestão de atualizações e correções (patching)

Não inclui:

- Desenvolvimento de sistemas  
- Evolução de software  
- Construção de APIs  
- Integrações de sistemas  
(abrangidos pelo MI-2025-007)

---

## 3. Indicadores (KPIs)

### KPIs principais do DITI:

- **Disponibilidade dos serviços críticos (% uptime mensal)**  
- **Tempo Médio de Resposta (TMR)**  
- **Tempo Médio de Solução (TMS)**  
- **Taxa de reincidência de incidentes**  
- **Integridade dos backups (sucesso em testes de restauração)**  
- **Adesão às janelas de manutenção**  
- **Número de interrupções não programadas**  
- **MTBF — Mean Time Between Failures**

---

## 4. Níveis de Serviço

### 4.1 Disponibilidade

| Serviço | Disponibilidade mínima | Horário |
|--------|------------------------|---------|
| Data Center Municipal | **99,5%** | 24x7 |
| Sistemas críticos | **99%** | horário de expediente |
| Redes internas | **98%** | horário de expediente |
| E-mail corporativo | **98%** | horário de expediente |

---

### 4.2 Prazos de Atendimento

| Tipo de chamado | Prioridade | Tempo de resposta | Tempo de solução |
|------------------|-----------|-------------------|------------------|
| Interrupção total do DC | A | 15 min | 4h |
| Rede parada (setor inteiro) | A | 20 min | 4h |
| Máquina ou usuário indisponível | B | 1h | 8h |
| Solicitações sem impacto | C | 4h | 48h |

---

## 5. Obrigações do DITI

- Manter monitoramento contínuo dos serviços estratégicos  
- Garantir backups diários e testes de restauração mensais  
- Priorizar incidentes conforme matriz de criticidade  
- Registrar todas as ações no sistema oficial de chamados  
- Manter inventário atualizado dos ativos  
- Realizar janelas de manutenção de forma controlada e comunicada

---

## 6. Obrigações das Secretarias Usuárias

- Registrar chamados exclusivamente pelo sistema oficial  
- Garantir informações precisas no momento da abertura  
- Facilitar acesso às equipes técnicas quando necessário  
- Cumprir orientações técnicas de prevenção e uso adequado

---

## 7. Janelas de Manutenção

Manutenções programadas ocorrerão em:

- **Quartas-feiras, 19h–22h**  
- **Sábados, 08h–12h**

Manutenções emergenciais seguirão fluxo acelerado de aprovação e comunicação.

---

## 8. Penalidades e Ações Corretivas

*Aplicável somente a fornecedores terceirizados.*

- Descumprimento de SLA crítico: **desconto de até 5%** na fatura  
- Reincidência superior a 3 ocorrências: abertura de **Plano de Correção Obrigatória (PCO)**  
- Falhas graves ou deliberadas: **substituição obrigatória do recurso técnico**

> **Nota:** Servidores públicos não estão sujeitos a multas financeiras; em vez disso, aplicam-se instrumentos de gestão: orientação, reforço de capacitação, redistribuição de tarefas ou ajustes de processo.

---

## 9. Escalonamento

- **Nível 1:** Central de Atendimento  
- **Nível 2:** DITI (Infraestrutura)  
- **Nível 3:** Equipes especializadas / fornecedores  
- **Escalonamento executivo:** Diretoria / Secretaria de Governo

---

## 10. Conexão com o Data Lakehouse Municipal

O cumprimento deste SLA é **pré-requisito** para:

- Confiabilidade das coletas automáticas  
- Redução de falhas de ingestão  
- Rastreabilidade operacional  
- Segurança e continuidade das pipelines  
- Governança de dados sustentável

---

**Documento aprovado por:**  
Diretoria de Tecnologia da Informação – Prefeitura Municipal de Hortolândia  
**Vigência:** Janeiro/2025 a Dezembro/2025  
