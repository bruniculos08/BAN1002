# Banco de Dados - Aula 1

**Definições iniciais**

- **Dados:** compõe uma informação, e sozinhos não possuem significado relevante.

- **Informação:** é a composição de diferentes dados, de maneira que ganhem um significado relvente.

- **Computador:** entidade que processa dados, mas não informação. 

- **Humano:** entidade que elabora informação através da associação de dados.

- **BD (banco de dados):** é um agrupamento de dados inter-relacionados representando informações de um domínio específico ligado à diversos programas para acesso e modificação destes dados.

**Definições de Bancos de Dados**

1) **SGBD (sistema gerenciador de bancos de dados):** tem objetivo de gerenciar o acesso e a modificação dos dados armazenados em um BD, tendo como principais funções as seguintes:

  - **métodos de acesso:** DDL (Data Definition Language; especifica o esquema do BD quanto à dados, índices e etc) e DML (Data Manipulation Language; trata da manipulação dos dados) ambos que permitem o processamento eficaz de consultas.

  - **integridade semântica:** garante que um dado inserido em um estrutura seja um valor valído para o domínio no qual a aplicação se encontra.

  - **segurança:** tem objetivo de evitar violação nos dados, permitir acesso diferenciado à determinados usuários e aplicações e previnir falhas na realização das transações.

  - **concorrência:** evita conflito em caso de acesso simultâneo à dados por trasações utilizando meios como bloqueio e timestamp.
 
  - **independência:** engloba a transparência da organização de dados e cria os níveis de indepêndencia entre os dados, existinto então a independência física (transparência de organização física dos dados como distribuição, agrupamento, organização dos arquivos e indexação) e indepêndencia lógica (transparência lógica do BD como as visões do mesmo ou seja seus esquemas externos).

