# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 27/05/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Eduardo Dias  

---

# Introdução

Este relatório apresenta o processo de implementação de serviços da AWS na empresa Abstergo Industries.

O objetivo do projeto foi selecionar e implementar soluções em nuvem capazes de reduzir custos operacionais imediatos, aumentar a escalabilidade da infraestrutura e melhorar a disponibilidade dos serviços corporativos.

A empresa possuía altos custos com armazenamento local, servidores físicos subutilizados e dificuldades de escalabilidade. Para solucionar esses problemas, foram selecionados serviços AWS focados em computação em nuvem, armazenamento inteligente e banco de dados gerenciado.

---

# Descrição do Projeto

O projeto de implementação foi dividido em 3 etapas, cada uma com objetivos específicos voltados para otimização de custos, desempenho e modernização da infraestrutura.

---

# Etapa 1: Amazon EC2

## Nome da ferramenta
Amazon EC2 (Elastic Compute Cloud)

## Foco da ferramenta
Redução de custos com infraestrutura física e aumento de escalabilidade computacional.

## Descrição de caso de uso

A empresa utilizava servidores físicos locais para hospedar aplicações internas e sistemas administrativos, gerando altos custos de manutenção, energia elétrica e suporte técnico.

Com a implementação do Amazon EC2, foi possível migrar os servidores para instâncias virtuais na nuvem, permitindo:

- pagamento sob demanda;
- escalabilidade automática;
- alta disponibilidade;
- redução de custos com hardware físico;
- maior flexibilidade operacional.

Além disso, a utilização do Auto Scaling permitiu aumentar ou reduzir recursos automaticamente conforme a demanda da aplicação.

### Benefícios obtidos

- Redução de custos operacionais;
- Eliminação de gastos com servidores físicos;
- Melhor aproveitamento de recursos;
- Maior disponibilidade dos sistemas.

---

# Etapa 2: Amazon S3

## Nome da ferramenta
Amazon S3 (Simple Storage Service)

## Foco da ferramenta
Armazenamento escalável e econômico de arquivos corporativos.

## Descrição de caso de uso

A empresa possuía um grande volume de documentos, backups e arquivos multimídia armazenados localmente, causando alto custo de armazenamento e riscos relacionados à perda de dados.

O Amazon S3 foi implementado como solução de armazenamento em nuvem para:

- backup corporativo;
- armazenamento de documentos;
- arquivamento de mídias;
- recuperação de desastres.

Foi utilizada a classe S3 Intelligent-Tiering, permitindo otimização automática de custos conforme o padrão de acesso aos arquivos.

### Benefícios obtidos

- Alta durabilidade dos dados;
- Escalabilidade ilimitada;
- Redução de custos de armazenamento;
- Backup automatizado;
- Segurança e redundância dos arquivos.

---

# Etapa 3: Amazon RDS

## Nome da ferramenta
Amazon RDS (Relational Database Service)

## Foco da ferramenta
Gerenciamento automatizado de banco de dados relacional.

## Descrição de caso de uso

A empresa utilizava bancos de dados locais que exigiam manutenção constante da equipe técnica, incluindo backups manuais, atualizações e monitoramento contínuo.

Com a implementação do Amazon RDS, o banco de dados passou a operar em ambiente gerenciado na AWS, utilizando PostgreSQL.

Os principais recursos utilizados foram:

- backup automático;
- failover;
- replicação;
- atualizações automatizadas;
- monitoramento contínuo.

### Benefícios obtidos

- Redução do trabalho operacional;
- Maior segurança dos dados;
- Alta disponibilidade;
- Melhor desempenho;
- Redução de falhas humanas.

---

# Conclusão

A implementação dos serviços AWS na empresa Abstergo Industries proporcionou significativa redução de custos operacionais, aumento da eficiência da infraestrutura e maior segurança dos dados corporativos.

Os serviços Amazon EC2, Amazon S3 e Amazon RDS atenderam aos objetivos propostos, permitindo maior escalabilidade, disponibilidade e automação dos processos tecnológicos da empresa.

Com a adoção da computação em nuvem, a empresa passou a possuir uma infraestrutura mais moderna, flexível e preparada para crescimento futuro.

Recomenda-se a continuidade da utilização dos serviços implementados e a análise de novas soluções AWS que possam ampliar ainda mais os ganhos operacionais e financeiros.

---

# Anexos

## Documentações Oficiais AWS

- [Amazon EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
- [Amazon RDS Documentation](https://docs.aws.amazon.com/rds/)
- [AWS IAM Documentation](https://docs.aws.amazon.com/iam/)
- [AWS Pricing Calculator](https://calculator.aws/#/)

---

# Assinatura do Responsável pelo Projeto

**Eduardo Dias**
