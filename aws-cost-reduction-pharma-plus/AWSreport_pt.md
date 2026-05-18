
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: Maio de 2026

Empresa: Pharma Plus

Responsável: Emily Guimarães

## Introdução

Este relatório apresenta o processo de implementação de serviços AWS na empresa Pharma Plus, realizado por Emily Guimarães. O objetivo do projeto foi identificar e implementar 3 serviços AWS com foco na redução imediata e sustentável de custos operacionais.

## Descrição do Projeto

A implementação foi dividida em 3 etapas, cada uma direcionada a uma área específica do negócio onde a adoção da nuvem poderia substituir infraestrutura local cara ou processos manuais ineficientes.

---

### Etapa 1
- **Ferramenta:** Amazon EC2 com Auto Scaling
- **Foco:** Capacidade de computação flexível e escalável
- **Descrição de caso de uso:** A Pharma Plus opera um sistema de pedidos online voltado ao cliente e uma plataforma interna de gestão de estoque. Anteriormente hospedada em servidores físicos próprios, a infraestrutura era dimensionada para suportar o pico de demanda; o que significava grande capacidade computacional ociosa fora dos horários de maior movimento. Com a migração para instâncias EC2 com Auto Scaling, a empresa passa a pagar apenas pela computação que efetivamente utiliza. As instâncias escalam automaticamente durante períodos de alta demanda (fins de semana, campanhas promocionais) e reduzem fora do horário de pico, com estimativa de redução de 40%, por exemple, nos custos de computação.

---

### Etapa 2
- **Ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco:** Armazenamento em nuvem escalável e de baixo custo
- **Descrição de caso de uso:** A Pharma Plus gerencia um volume crescente de documentos -- receitas médicas, notas fiscais de fornecedores, registros de conformidade e fichas técnicas de produtos. Esses arquivos eram armazenados em servidores locais que exigiam manutenção contínua de hardware e rotinas manuais de backup. A migração para o S3 elimina os custos de hardware, garante redundância automática entre zonas de disponibilidade e permite controle de acesso granular por departamento. Os custos de armazenamento reduziram significativamente e o risco de perda de dados por falha de hardware foi eliminado.

---

### Etapa 3
- **Ferramenta:** Amazon RDS (Relational Database Service)
- **Foco:** Banco de dados relacional gerenciado
- **Descrição de caso de uso:** O banco de dados de estoque e vendas da empresa era mantido em um servidor fixo, exigindo um administrador dedicado para atualizações, backups e ajustes de desempenho. A migração para o Amazon RDS transfere essa responsabilidade operacional para a AWS. Backups automatizados, aplicação de patches e failover multi-AZ são gerenciados pela plataforma, liberando a equipe interna para atividades de maior valor. Para uma farmácia onde a precisão do estoque está diretamente ligada à segurança dos pacientes, o ganho em confiabilidade já justifica a migração; e a redução de custos é um benefício adicional.

---

## Conclusão

A implementação dos três serviços AWS posiciona a Pharma Plus para operar com uma infraestrutura mais enxuta e resiliente. Os custos de computação passam a refletir o uso real, o armazenamento escala sem necessidade de investimento em capital e o banco de dados opera com confiabilidade de nível empresarial sem uma equipe de operações dedicada. Recomenda-se que a Pharma Plus continue avaliando novos serviços AWS; em especial o AWS Lambda para automação de tarefas operacionais rotineiras -- conforme o negócio cresce.

## Anexos

- Não há anexos aplicáveis para esta etapa de implementação.
- Baseado no modulo 5, Noções de Computação em Nuvem.

---

*Responsável pelo projeto: Emily Guimarães*
