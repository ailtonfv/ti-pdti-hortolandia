# 📘 04. Riscos e Controles  
**Prefeitura Municipal de Hortolândia — PDTI 2026–2029**

Este diretório apresenta a gestão de riscos e os mecanismos de controle que sustentam a segurança, a continuidade e a governança da Tecnologia da Informação no município.  
A gestão de riscos é fundamental para garantir estabilidade, resiliência operacional, integridade dos sistemas e proteção dos dados públicos.

O conteúdo deste capítulo abrange:

- identificação e classificação dos riscos de TI;  
- avaliação de impacto e probabilidade;  
- priorização e categorização segundo boas práticas (TCU, COBIT, ISO 27005);  
- mecanismos de mitigação e contingência;  
- controles internos aplicáveis;  
- conformidade com a LGPD e normativos municipais;  
- diretrizes de continuidade e recuperação de desastres.

Este conjunto assegura que as decisões do PDTI sejam orientadas pela redução de riscos e pela continuidade dos serviços essenciais à população.

---

## 1. Metodologia de Gestão de Riscos

A metodologia empregada segue quatro referências:

- **ISO/IEC 27005** — Gestão de riscos de segurança da informação;  
- **COBIT 2019** — Domínio MEA (Monitorar, Avaliar e Analisar);  
- **TCU – Acórdãos sobre Governança de TI**;  
- **SISP – Instruções Normativas e Manuais de Governança**.

As etapas incluem:

1. identificação dos riscos;  
2. classificação;  
3. avaliação de impacto e probabilidade;  
4. definição de categoria;  
5. aplicação de controles e mitigadores;  
6. monitoramento contínuo.

---

## 2. Classificação dos Riscos de TI

Os riscos estão agrupados em seis categorias principais:

### 2.1 Operacionais
- indisponibilidade de sistemas ou serviços;  
- falhas no Data Center;  
- obsolescência tecnológica;  
- interrupção de redes e conectividade.

### 2.2 Tecnológicos
- storages, servidores ou equipamentos fora de garantia;  
- vulnerabilidades em sistemas legados;  
- ausência de monitoramento;  
- falhas de backup e recuperação.

### 2.3 Segurança da Informação
- acessos indevidos;  
- vazamento de dados;  
- malware e ransomware;  
- ausência de políticas de segurança atualizadas.

### 2.4 Conformidade e Auditoria
- não aderência à LGPD;  
- não conformidade com TCU/TCE;  
- falhas em registros obrigatórios;  
- ausência de políticas e POPs.

### 2.5 Contratos e Fornecedores
- dependência excessiva de empresas externas;  
- atrasos em suporte e manutenção;  
- inconsistências contratuais ou SLAs insuficientes.

### 2.6 Humanos e Organizacionais
- equipe reduzida;  
- rotatividade;  
- ausência de capacitação;  
- sobrecarga operacional.

---

## 3. Matriz de Riscos (Impacto x Probabilidade)

A matriz segue o padrão 3x3 (Alta, Média, Baixa).

```md
| Nº | Risco Identificado                                   | Probabilidade | Impacto | Nível | Mitigação / Controle                               |
|----|------------------------------------------------------|---------------|---------|-------|-----------------------------------------------------|
| 01 | Falha no Data Center ou indisponibilidade crítica    | Alta          | Alta    | Alto  | redundância, monitoramento, backup e DRP           |
| 02 | Equipamentos obsoletos e fora de garantia            | Alta          | Média   | Alto  | renovação gradual do parque; contratos de suporte   |
| 03 | Vazamento de dados / incidente de segurança          | Média         | Alta    | Alto  | LGPD, políticas SI, treinamentos, firewalls         |
| 04 | Sistemas legados sem integração                      | Alta          | Média   | Alto  | APIs, modernização, governança de dados             |
| 05 | Dependência elevada de fornecedores externos         | Média         | Alta    | Alto  | revisão contratual, capacitação interna             |
| 06 | Falhas de backup ou recuperação                      | Média         | Alta    | Alto  | política de backup, testes periódicos               |
| 07 | Rotatividade ou insuficiência de equipe técnica      | Alta          | Média   | Alto  | capacitação, ampliação da equipe, POPs              |
| 08 | Ausência de catálogo de serviços e SLAs              | Alta          | Média   | Alto  | implantação do catálogo, GLPI e indicadores         |
| 09 | Vulnerabilidades tecnológicas não corrigidas         | Média         | Média   | Médio | atualização, patch management, auditorias           |
| 10 | Falhas em conformidade LGPD e auditorias             | Baixa         | Alta    | Médio | revisões, políticas internas, controles de acesso   |



## 4. Controles Internos Recomendados

### 4.1 Controles Técnicos
- autenticação forte e revisão periódica de acessos;  
- políticas de senhas e MFA;  
- segmentação de redes;  
- firewalls, IDS/IPS e antivírus;  
- patch management contínuo;  
- automação de logs.

### 4.2 Controles Administrativos
- políticas e normas de TI atualizadas;  
- POPs operacionais;  
- catálogo de serviços oficial;  
- registro de incidentes;  
- avaliação anual do PDTI.

### 4.3 Controles de Backup e Continuidade
- política formal de backup;  
- retenção e segregação de cópias;  
- testes mensais de restauração;  
- plano de recuperação de desastres (DRP).

### 4.4 Controles de Auditoria
- relatórios periódicos de conformidade;  
- verificação de contratos e SLAs;  
- rastreabilidade de ações críticas.

---

## 5. Conformidade e LGPD

A gestão de riscos deve assegurar conformidade com:

- **LGPD – Lei Geral de Proteção de Dados**;  
- **Marco Civil da Internet**;  
- **Lei de Acesso à Informação**;  
- **Normas Internas da Prefeitura**;  
- **Recomendações do TCU e TCE**;  
- **Políticas Municipais de Segurança da Informação**.

Principais obrigações:

- minimização de dados;  
- medidas técnicas e administrativas adequadas;  
- registros de tratamento;  
- controle de acessos;  
- resposta a incidentes;  
- transparência.

---

## 6. Continuidade e Recuperação de Desastres

Diretrizes essenciais:

- definição de sistemas críticos e prioridades de recuperação (RTO/RPO);  
- uso de redundância e espelhamento;  
- armazenamento de backups fora do Data Center;  
- plano formal de DRP;  
- testes anuais de continuidade;  
- procedimentos para incidentes de segurança.

A continuidade garante que os serviços essenciais à população não sejam interrompidos.

---

## 7. Conclusão

A gestão de riscos é um componente essencial do PDTI, pois protege a operação, preserva a integridade das informações e fortalece a resiliência institucional.  
Este diretório consolida as boas práticas necessárias para orientar decisões, reduzir vulnerabilidades e garantir sustentabilidade ao longo do ciclo 2026–2029.
