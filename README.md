# Relatório de Implementação de Ferramentas AWS
**Redução de Custos Operacionais — Farmácia Abstergo**

---

## Identificação do Projeto

- **Data de Início:** 23 de maio de 2026
- **Empresa:** Abstergo Industries — Divisão Farmacêutica
- **Responsável:** Caio Costa — Gerência de TI da Abstergo Industries
- **Objetivo:** Implementação de 3 serviços AWS para redução imediata de custos operacionais

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na Abstergo Industries, realizado pela Gerência de TI. O objetivo do projeto foi selecionar e descrever 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos, eliminando a necessidade de infraestrutura física onerosa e otimizando os processos internos da farmácia.

A Abstergo Industries, como empresa do setor farmacêutico, lida diariamente com grandes volumes de dados de estoque, prescrições, clientes e fornecedores. A migração estratégica para serviços gerenciados na nuvem representa uma oportunidade concreta de reduzir custos fixos de TI, aumentar a disponibilidade dos sistemas e garantir conformidade com regulamentações do setor.

---

## Descrição do Projeto

O projeto de implementação foi dividido em 3 etapas, cada uma correspondendo a um serviço AWS selecionado com base no potencial de redução de custos e facilidade de adoção.

---

### Etapa 1

| Campo | Descrição |
|---|---|
| **Ferramenta** | Amazon S3 (Simple Storage Service) |
| **Foco** | Armazenamento de documentos e arquivos |
| **Caso de Uso** | Substituição dos servidores de arquivos físicos locais pelo Amazon S3 para armazenamento de notas fiscais eletrônicas, receitas digitalizadas, laudos e documentos regulatórios. O S3 elimina custos de hardware, manutenção e backup local, oferecendo armazenamento escalável com pagamento apenas pelo uso efetivo. |

---

### Etapa 2

| Campo | Descrição |
|---|---|
| **Ferramenta** | Amazon RDS (Relational Database Service) |
| **Foco** | Banco de dados gerenciado para estoque e clientes |
| **Caso de Uso** | Migração do banco de dados de estoque de medicamentos, cadastro de clientes e histórico de vendas para o Amazon RDS (MySQL). O serviço gerenciado elimina os custos com licenciamento de banco de dados local, administração de DBA e hardware dedicado, além de oferecer backups automáticos e alta disponibilidade com Multi-AZ. |

---

### Etapa 3

| Campo | Descrição |
|---|---|
| **Ferramenta** | AWS Lambda |
| **Foco** | Automação de processos e geração de relatórios |
| **Caso de Uso** | Implementação de funções Lambda para automação de tarefas recorrentes: geração de relatórios de estoque crítico, alertas de vencimento de medicamentos e integração com sistemas de fornecedores. O modelo serverless elimina a necessidade de servidores dedicados para processos pontuais, cobrando apenas pelo tempo de execução das funções. |

---

## Conclusão

A implementação das ferramentas Amazon S3, Amazon RDS e AWS Lambda na Abstergo Industries tem como resultado esperado a redução significativa dos custos de infraestrutura de TI, maior confiabilidade dos sistemas de gestão farmacêutica e automação de processos operacionais críticos. A substituição de servidores físicos e licenças locais por serviços gerenciados na nuvem representa economia imediata em manutenção, energia e hardware.

Recomenda-se a continuidade da utilização das ferramentas implementadas, bem como a avaliação de serviços complementares como Amazon CloudWatch (monitoramento) e AWS IAM (controle de acesso), que podem ampliar a segurança e a governança da infraestrutura cloud da empresa.

---

## Documentos Recomendados

- Planilha de comparativo de custos: infraestrutura local vs. AWS
- Diagrama de arquitetura dos serviços implementados
- Manual de configuração do Amazon S3 para documentos farmacêuticos
- Guia de migração de banco de dados para Amazon RDS
- Documentação das funções Lambda implementadas
- Política de segurança e controle de acesso (AWS IAM)

---

*Caio Costa — Gerência de TI da Abstergo Industries*  
*Data: 23 de maio de 2026*

