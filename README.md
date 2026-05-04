# Challenge-Dio-AWS-Services
Desafio da DIO focado na seleção de três serviços da AWS para reduzir custos em uma farmácia que atua como hub de distribuição para múltiplas empresas.

RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 04/05/2026
Empresa: Abstergo Industries
Responsável: Gleisson Leonardo

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gleisson Leonardo. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos, especialmente relacionados à infraestrutura de TI, armazenamento de dados e gestão de sistemas utilizados na operação da farmácia.
Considerando que implementações em nuvem podem gerar custos elevados quando mal planejadas, este projeto prioriza soluções simples, de baixo custo inicial e com retorno rápido.

Descrição do Projeto
Etapa 1:
Nome da ferramenta: Amazon EC2
Foco da ferramenta: Redução de custos com infraestrutura física
Descrição de caso de uso: A farmácia operava com servidores locais para sistemas de vendas e controle de estoque, gerando custos com manutenção, energia e baixa flexibilidade. A proposta foi migrar esse sistema para uma instância do Amazon EC2 com dimensionamento adequado (sem superdimensionamento). Essa abordagem permite pagar apenas pelo uso computacional necessário, eliminando custos com hardware físico e reduzindo gastos com manutenção.

Etapa 2:
Nome da ferramenta: Amazon S3
Foco da ferramenta: Armazenamento de baixo custo
Descrição de caso de uso: A farmácia armazenava documentos como notas fiscais, relatórios e históricos de vendas em servidores locais, com alto custo e risco de perda de dados. Com a migração para o Amazon S3, esses arquivos passaram a ser armazenados com alta durabilidade e custo muito inferior ao armazenamento tradicional. Além disso, arquivos antigos podem ser movidos para classes mais baratas (como arquivamento), reduzindo ainda mais os custos.

Etapa 3:
Nome da ferramenta: Amazon RDS
Foco da ferramenta: Redução de custos com gestão de banco de dados
Descrição de caso de uso: A farmácia utilizava banco de dados local, exigindo manutenção constante, backups manuais e suporte técnico especializado. Com o Amazon RDS, o banco de dados passa a ser gerenciado, com backups automáticos, atualizações e maior confiabilidade. Isso reduz a necessidade de mão de obra técnica dedicada e evita falhas que podem impactar vendas e operações.

Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos com infraestrutura física, diminuição de gastos com armazenamento e eliminação de custos operacionais relacionados à manutenção de sistemas, o que aumentará a eficiência e a confiabilidade das operações.
A abordagem adotada prioriza simplicidade e baixo custo inicial, permitindo que a empresa evolua gradualmente sua arquitetura em nuvem conforme a necessidade e maturidade tecnológica.
Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação futura de novos serviços, sempre considerando o custo-benefício e o impacto real no negócio.
