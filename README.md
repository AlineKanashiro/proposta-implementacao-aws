# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 20/02/2026  
Empresa: Abstergo Industries  
Responsável: Aline Kazumi Kanashiro  
  
  ## Introdução
  Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Aline Kazumi Kanashiro. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

  ## Descrição do Projeto
  O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir serão descritas as etapas do projeto:

  ### Etapa 1:
  - AWS EC2 Auto Scaling
  - Manter a disponibilidade das aplicações utilizadas na empresa e redimensionar o uso conforme a necessidade da empresa
  - Caso ocorra algum problema com relação as instâncias utilizadas, é possível a implantação de multi-AZ o que manteria todas as aplicações ativas, evitando a interrupção do funcionamento das aplicações. Outro ponto é a questão de adequar a capacidade de acordo com o uso. Com o machine learning é possível prever e programar o número de instâncias a serem usadas, evitando custos desnecessários ao manter uma capacidade maior do que o necessário.

  ### Etapa 2:
  - Amazon VPC
  - Garantir a segurança dos dados com a utilização de sub-redes e controle de acesso
  - Com essa ferramenta será possível segmentar a rede de forma mais organizada e segura em duas sub-redes, privada e pública. Sub-redes públicas para aplicações que precisam de acesso direto a internet e sub-redes privadas para os bancos de dados, garantindo a segurança dos dados da empresa. Além da divisão em sub-redes, também há camadas de segurança que definirão o acesso com base em IP, porta e protocolo.

  ### Etapa 3:
  - S3 Intelligent-Tiering
  - Otimização da utilização do banco de dados
  - Essa ferramenta monitora a utilização do banco e armazena os dados em três níveis de acesso, sendo que o primeiro é para dados com acesso frequente, o segundo é para dados com acesso pouco frequente, o terceiro é para dados que são raramente acessados. O custo mensal de monitoramento e automação por objeto é baixo e seria o ideal para iniciar a implementação na empresa por os padrões de acesso ainda são desconhecidos.

  ## Conclusão
  A implementação de ferramentas na empresa Abstergo Industries tem como esperado a utilização de recursos de forma otimizada para a situação atual e com foco em segurança dos dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

  ### <u>Assinatura do responsável pelo projeto:</u> Aline Kazumi Kanashiro
  
