# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 23/04/26
Empresa: Abstergo Industries 
Responsável: Alexandre Jesus Costa

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Alexandre Jesus Costa. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- AWS Cost Explorer
- Permite identificar onde os gastos estão concentrados. Ajuda a definir orçamentos e alertas para evitar despesas inesperadas.
- Analisar gasto mensal por serviço, conta ou região para descobrir onde há maior consumo.
  Detectar tendências de aumento de custo e comparar períodos para identificar despesas anormais.
  Configurar alertas de orçamento quando o custo ultrapassar um limite previsto.
  Avaliar o impacto financeiro de mudanças, como desligar instâncias não utilizadas ou migrar workloads.

Etapa 2: 
- Amazon EC2 Spot Instances
- Usa capacidade ociosa com descontos de até 90%. Ideal para cargas de trabalho flexíveis e batch, reduzindo custo de computação.
- Executar jobs batch, processamento de dados ou testes automatizados com baixa prioridade.
  Rodar pipelines de CI/CD e builds que toleram interrupções, aproveitando preços muito menores.
  Escalar capacidades de cluster para cargas variáveis em ambientes de Big Data, ML ou renderização.
  Reduzir o custo de ambientes de desenvolvimento e staging, onde a disponibilidade pode ser flexível.

Etapa 3: 
- Amazon S3 Intelligent-Tiering
- Movimenta automaticamente objetos entre camadas de armazenamento mais baratas. Reduz custos de armazenamento sem necessidade de gerenciamento manual.
- Armazenar grandes volumes de dados com perfil de acesso desconhecido ou variável.
  Guardar backups, arquivos de logs e objetos estáticos que podem ficar meses sem acesso.
  Otimizar custos em repositórios de dados onde alguns objetos são acessados esporadicamente.
  Eliminar o trabalho manual de mover objetos entre classes de armazenamento, deixando o S3 fazer a otimização.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado melhorar no controle financeiro, Redução imediata de custos de computação e Otimização automática de armazenamento, o que aumentarão a eficicácia e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Relatório do AWS Cost Explorer
Link: https://aws.amazon.com/pt/aws-cost-management/aws-cost-explorer/
Documentação de Orçamentos e alertas (AWS Budgets)
Link: https://aws.amazon.com/pt/aws-cost-management/aws-budgets/
Guia de Amazon EC2 Spot Instances
Link: https://aws.amazon.com/pt/ec2/spot/
Documentação de uso e melhores práticas de Spot
Link: https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/using-spot-instances.html
Guia de Amazon S3 Intelligent-Tiering
Link: https://aws.amazon.com/pt/s3/storage-classes/intelligent-tiering/
Documentação técnica do S3 Intelligent-Tiering
Link: https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html#storage-class-intelligent-tiering

Assinatura do Responsável pelo Projeto:

Alexandre Jesus Costa