# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 06/05/2026
Empresa: Abstergo Industries 
Responsável : Daniele Rodrigues Martins
## Introdução

Este presente relatório apresenta uma proposta de processo de implementação de ferramentas de serviços AWS na farmácia Abstergo Industries, realizado por Daniele Rodrigues Martins. O objetivo foi oferecer ao cliente, 3 serviços AWS, com a finalidade de reduzir custos operacionais da empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3
- Serviço de armazenamento de arquivos escalável, durável e seguro e controle de acesso principalmente a dados sensíveis mantendo a empresa de acordo com as diretrizes da LGPD  
- A ferramenta Amazon S3 será utilizada para:
    - guardar notas fiscais dos clientes, fornecedores, 
    - backups de documentos gerais, notas, relatórios
    - documentos : dos funcionários, clientes(dados de      cadastro pessoal e receitas controladas), regulatórios da farmácia junto a Anvisa e CRF 
    relatórios: de vendas, de novos clientes, controle de frequência de funcionários 
- Justificativa da redução de custos: 
   - elimina necessidade de servidores locais de arquivos,    reduzindo significativamente os custos com infraestrutura física
   - alta durabilidade, garantindo que todo dado gerado pela empresa esteja disponível mesmo em caso de desastres 
   - pagar apenas pelo uso. A Amazon S3 utiliza o modelo de pagamento sob demanda, cobrando de acordo com armazenamento utilizado, transferência de dados e padrão de acesso.


Etapa 2: 
- Amazon EC2
- Serviço de máquinas virtuais escaláveis para hospedagem de aplicações e sistemas corporativos
- A ferramenta Amazon EC2 será utilizada para:
  - hospedar sistema da farmácia 
  - ERP 
  - controle de estoque
  - controle de receitas de medicamentos controlados
  - controle de receitas de antibióticos
  - controle de quem tem autorização para fazer aplicação de injetáveis, aferição de pressão e medição de glicose
  - controle de licenças ligadas a Anvisa e ao CRF  
  - suportar aplicações internas utilizadas pelo setor de marketing e comunicação digital 
  -  A infraestrutura EC2 também poderá oferecer suporte a aplicações de análise de dados e inteligência de negócios. Essas aplicações poderão auxiliar a empresa na identificação de métricas importantes, como desistência de compras, fidelização de clientes e perdas relacionadas ao vencimento de produtos em estoque.
- Justificativa da redução de custos:
   - evita compra de servidores físicos
   - possibilita escalabilidade computacional para aplicações corporativas e futuras soluções de análise de dados.
   - escalabilidade sob demanda 

Etapa 3: 
- Amazon RDS 
- Serviço gerenciado de banco de dados relacional
- A ferramenta Amazon RDS será utilizada para armazenamento, consulta, alteração e exclusão de dados corporativos: 
  - dados de  funcionários
  - dados dos produtos medicamentos, perfumaria e higiene pessoal
  - dados de clientes
  - dados de estoque
  - dados de pedidos
  - dados de fornecedores
  - dados de controle junto à Anvisa e CRF
  
- Justificativa da redução de custos:
   realização de backups automáticos, reduzindo riscos de perda de dados;
   diminuição da necessidade de manutenção manual do banco de dados;
   eliminação da necessidade de servidores físicos dedicados;
   utilização de criptografia para proteção de dados sensíveis, auxiliando a empresa na adequação à LGPD.

## Conclusão
De acordo com as necessidades do cliente, a implementação dos serviços AWS na empresa Abstergo Industries tem como resultado esperado a otimização dos processos da empresa, permitindo maior adaptação às mudanças da demanda do mercado e possibilitando a escalabilidade dos serviços conforme o crescimento da organização.

A utilização das ferramentas em nuvem contribuirá para a redução de custos operacionais, aumento da eficiência e produtividade, além de garantir maior segurança para dados sensíveis e maior resiliência em casos de desastres, evitando perdas de informações importantes para o negócio.

A modernização da infraestrutura tecnológica da empresa por meio de serviços cloud também permitirá que a farmácia se mantenha competitiva no mercado.

Recomenda-se a continuidade da utilização das ferramentas implementadas, bem como a busca por novas tecnologias que possam contribuir para a melhoria contínua dos processos da empresa.



## Anexos
- Documentação da Amazon
https://docs.aws.amazon.com/pt_br/

Assinatura do Responsável pelo Projeto:

Daniele Rodrigues Martins 