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

<p align="center">
  <img class="gatsby-resp-image-image" src="https://lh4.googleusercontent.com/proxy/t3a_YTOiAvZLFL5-zEPY6s4orNcZuXv8S9KgsmfRWR4xpFoW5NFiKLCgDpRGgz6Na6INQ53BPw8lk57S8uGzAFmmrzC9v56ym9RLwN4kb0GIkqxLT7OUwUGrZoFJbpW6dg=w1200-h630-p-k-no-nu" width="370" title="Selection Sort">
</p>

**Esquema SGBD**
<p align="center">
  <img class="gatsby-resp-image-image" src="https://slideplayer.com.br/slide/364019/2/images/18/SGBD+em+Detalhe.jpg" width="500" title="Selection Sort">
  <img class="gatsby-resp-image-image" src="https://www.estudegratis.com.br/images/questoes/550001740f8fc8b15349.gif" width="550" title="Selection Sort">
</p>
</p>

**Legenda:**

- o cilindro BD é um repositório de arquivos de dados operacionais e arquivos de índices.
- o DD (dicionário de dados) possui as especificações do esquema, retrições de integridade, autorizações de acesso, visões, localizações de arquivos do BD, configurações 
e estimativas.
- o log backup é um repositório de cópias do BD e do histórico de transações.
- o DBA ou super usuário define o projeto do BD, o esquema de dados, os índices, restrições de integridade, visões, autorizações, poder de recuperação e monitoramento.
- processador run time ou módulo central possui controle de acesso físico e as responsabilidades de gerenciar arquivos e buffers e notificar falhas ao gerenciador de transações.
- a aplicação é o que dá acesso ao BD por meio de comandos DML pré-compilados em um código de uma linguagem suportada pelo SGBD.
- o usuário ad hoc têm acesso direto ao SGBD e pode executar operações DML sem uso de aplicação.

**Vantagem de se utilizar SGBD:**

- independência da aplicação em relação aos dados.
- controle de acesso.
- suporte de visões (dados apresentados de maneira diferente).
- controle de redundância.
- "simultâneidade" (é formada uma fila) de dados e transações.
- imposição de restrições de integridade (não há repetição e há integridade de referência ou seja toda transação ocorre apenas se houver uma chave primária e chave estrangeira iguais)

