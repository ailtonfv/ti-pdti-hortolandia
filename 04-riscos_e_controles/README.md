# 04. Riscos e Controles  
*Prefeitura Municipal de Hortolândia — PDTI 2026–2029*

Este diretório reúne a matriz de riscos, os controles internos e os instrumentos de conformidade que sustentam a continuidade, a segurança e a governança da TI municipal.

A gestão de riscos é essencial para assegurar resiliência operacional, integridade das informações e disponibilidade dos serviços prestados ao cidadão.

---

## 1. Identificação dos Riscos de TI

Os riscos mapeados abrangem:

- indisponibilidade de infraestrutura crítica;  
- obsolescência de equipamentos;  
- incidentes de segurança e vazamento de dados;  
- falhas de backup e recuperação;  
- dependência elevada de fornecedores externos;  
- sistemas legados sem integração;  
- falhas de conformidade com a LGPD;  
- insuficiência e rotatividade da equipe técnica;  
- ausência de catálogo de serviços e SLAs;  
- vulnerabilidades tecnológicas acumuladas.

---

## 2. Classificação e Priorização

Modelo adotado:

- **Probabilidade:** Baixa • Média • Alta  
- **Impacto:** Baixo • Médio • Alto  
- **Nível do Risco:** Combinação entre impacto e probabilidade  
- **Mitigação:** Controles técnicos, administrativos e operacionais

---

## 3. Matriz de Riscos (Impacto × Probabilidade)

A matriz segue o padrão 3×3 (Alta, Média, Baixa).

| Nº | Risco Identificado                                   | Probabilidade | Impacto | Nível | Mitigação / Controle                               |
|----|------------------------------------------------------|---------------|---------|-------|-----------------------------------------------------|
| 01 | Falha no Data Center ou indisponibilidade crítica    | Alta          | Alta    | Alto  | redundância, monitoramento, backup e DRP           |
| 02 | Equipamentos obsoletos e fora de garantia            | Alta          | Média   | Alto  | renovação gradual, contratos de suporte             |
| 03 | Vazamento de dados / incidente de segurança          | Média         | Alta    | Alto  | LGPD, políticas, firewall, treinamento              |
| 04 | Sistemas legados sem integração                      | Alta          | Média   | Alto  | APIs, modernização, governança de dados             |
| 05 | Dependência elevada de fornecedores externos         | Média         | Alta    | Alto  | revisão contratual, formação interna                |
| 06 | Falhas de backup ou recuperação                      | Média         | Alta    | Alto  | política de backup, testes periódicos               |
| 07 | Rotatividade ou insuficiência de equipe técnica      | Alta          | Média   | Alto  | capacitação, ampliação da equipe, POPs              |
| 08 | Ausência de catálogo de serviços e SLAs              | Alta          | Média   | Alto  | implantação do catálogo, GLPI, indicadores          |
| 09 | Vulnerabilidades tecnológicas não corrigidas         | Média         | Média   | Médio | patching, atualização, auditorias                   |
| 10 | Falhas de conformidade LGPD e auditorias             | Baixa         | Alta    | Médio | revisões, políticas internas, controle de acesso    |

---

## 4. Controles Internos Recomendados

### 4.1 Controles Técnicos

- autenticação multifator (MFA);  
- firewalls e segmentação de rede;  
- criptografia;  
- gestão de patches;  
- monitoramento contínuo (SIEM/NOC);  
- antivírus corporativo;  
- backups e testes recorrentes;  
- RBAC — controle baseado em função.

---

### 4.2 Controles Administrativos

- políticas formais de TI e Segurança da Informação;  
- POPs (Procedimentos Operacionais Padrão);  
- documentação técnica;  
- matriz RACI;  
- auditorias internas e externas;  
- gestão de contratos e SLAs com fornecedores.

---

### 4.3 Controles Operacionais

- registro de incidentes e chamados;  
- checklists de manutenção;  
- rondas técnicas no data center;  
- validação pós-incidente;  
- conformidade com a LGPD.

---

## 5. Conformidade e Auditoria

Abrange:

- LGPD — Lei Geral de Proteção de Dados;  
- normas municipais de TI e segurança;  
- ISO 27001, 27002 e 27005;  
- COBIT 2019;  
- ITIL 4;  
- recomendações do TCU sobre riscos de TI;  
- políticas e normas internas do município.

---

## 6. Continuidade e Recuperação de Desastres (DRP)

Recomenda-se:

- plano oficial de continuidade (PCN);  
- plano de recuperação de desastres (DRP);  
- definição de RTO/RPO;  
- redundância em rede, energia e servidores;  
- testes anuais de contingência;  
- atualização periódica dos documentos.

---

## 7. Conclusão

A gestão de riscos integra o núcleo estratégico do PDTI 2026–2029, fortalecendo:

- segurança institucional;  
- continuidade dos serviços críticos;  
- capacidade de resposta a incidentes;  
- governança e conformidade;  
- proteção dos dados públicos e dos cidadãos.







