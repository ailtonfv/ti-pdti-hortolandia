# 🛠️ 06 — SLA e Governança Operacional da TI
*Prefeitura Municipal de Hortolândia — PDTI 2026–2029*

Este documento estabelece os **Acordos de Nível de Serviço (SLA)**, os **processos operacionais**, os **indicadores**, a **estrutura de atendimento** e os **compromissos de governança** para garantir previsibilidade, transparência e alinhamento entre DITI, DSTI e todas as secretarias municipais.

---

## 1. Objetivos do SLA
Os Acordos de Nível de Serviço visam:

- Definir padrões mínimos e mensuráveis de atendimento e operação;
- Estabelecer expectativas claras entre TI e demais secretarias;
- Reduzir gargalos e ruídos operacionais;
- Garantir continuidade e previsibilidade dos serviços essenciais;
- Criar base para indicadores, auditorias e priorização de demandas;
- Suportar a construção do **Data Lakehouse Municipal** (2026–2029).

---

## 2. Escopo dos Serviços Abrangidos
O SLA cobre serviços prestados por DITI e DSTI, incluindo:

- Suporte ao usuário (níveis 1, 2 e 3);
- Data Center, servidores e storages;
- Redes cabeadas, Wi-Fi e conectividade;
- Sistemas corporativos e setoriais;
- Administração de banco de dados;
- Segurança da Informação e LGPD;
- Gestão de incidentes, requisições e mudanças;
- Governança de TI e registros operacionais;
- Projetos estruturantes e integrações.

---

# 3. Classificação dos Serviços e Criticidade
A classificação determina prioridades de atendimento.

## 3.1 Criticidade Alta (Nível A)
**Serviços que impactam diretamente a continuidade da Prefeitura.**

Exemplos:
- Sistemas corporativos críticos (RH, Protocolo, SIGA, Tributário);
- Rede indisponível no Paço ou secretarias essenciais;
- Queda de servidores, banco de dados ou virtualização;
- Falha geral em e-mail ou autenticação institucional.

### SLA para Criticidade Alta
- **Tempo de resposta:** até **30 minutos**  
- **Prazo estimado de solução:** até **4 horas**  
- Atendimento **imediato** por analistas nível 2/3.

---

## 3.2 Criticidade Média (Nível B)
**Afeta setores específicos, mas não paralisa a Prefeitura.**

Exemplos:
- Impressoras, scanners, totens;
- Falhas em sistemas setoriais;
- Problemas de login individual.

### SLA para Criticidade Média
- **Tempo de resposta:** até **2 horas**  
- **Prazo estimado de solução:** até **24 horas úteis**

---

## 3.3 Criticidade Baixa (Nível C)
**Requisições rotineiras ou tarefas sem impacto operacional imediato.**

Exemplos:
- Troca de equipamento;
- Instalação de software autorizado;
- Ajuste de perfil de acesso.

### SLA para Criticidade Baixa
- **Tempo de resposta:** até **8 horas úteis**  
- **Prazo estimado de solução:** até **5 dias úteis**

---

# 4. Fluxo de Atendimento e Governança

## 4.1 Modelo Geral (ITIL 4 Adaptado)
1. **Abertura do chamado** (usuário → Service Desk)  
2. **Classificação automática** (criticidade A/B/C)  
3. **Triagem** (nível 1)  
4. **Escalonamento** (nível 2/3, se necessário)  
5. **Resolução**  
6. **Validação com usuário**  
7. **Encerramento**  
8. **Registro no catálogo de problemas** (quando aplicável)

---

## 4.2 Fluxo (versão esquemática em Mermaid)
```mermaid
flowchart LR
    A[Usuário abre chamado] --> B[Classificação (A/B/C)]
    B --> C[Nível 1]
    C -->|Sem solução| D[Nível 2]
    D -->|Necessário| E[Nível 3]
    E --> F[Resolução]
    F --> G[Validação com usuário]
    G --> H[Encerramento]

