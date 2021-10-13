# Aula 02

## **Projeto de BD**
- é definido em 3 partes:

1. **Modelo Conceitual:** diagrama de entidade-relacional.

2. **Projeto Lógico:** transformação do modelo conceitual em modelo lógico (tabelas) onde se define o que será implementado.

3. **Projeto Físico:** onde o BD é "enriquecido".

## **Modelos de dados - Parte 1**
- definem um conjunto de regras para a representação de dados.

**Modelo Conceitual:** é uma descrição do BD independente do SGBD, no qual a técnica mais utilizada é a de entidade relacional (ER).

## **Modelos de dados - Parte 2**

**Modelo ER - propriedades:**

1. O modelo de dados ER não possui ligação com o SGBD.

2. Neste preocupa-se apenas com a utilização dos dados e não com a estrutura lógica das tabelas.

3. Segue os requisitos estabelecidos.

4. Note que na imagem à seguir, A só pode se relacionar com 1 B (1 até 1 que é o mesmo que apenas 1) e B pode se relacionar com 0 ou n A's (0 até n), e que em A, a chave primária
é o atributo AA1 e em B a chave primária é o atributo BB1, enquanto AA2 é um atributo simples de A e BB2 é um atributo simples de B:

<p align="center">
  <img class="gatsby-resp-image-image" src="https://www.tiparafiscos.com.br/wp-content/uploads/2020/03/figurabanco.gif" width="370" title="Selection Sort">
</p>

**Modelo Lógico - propriedades:**
- representa a estrutura de dados em um BD vista pelo usuário do SGBD e define: 

1) tabelas

2) nome das tabelas

3) colunas

4) nomes das colunas 

- ou seja, nele temos o seguinte:

<p align="center">
  <img class="gatsby-resp-image-image" src="https://i.stack.imgur.com/Vh4Iq.jpg" width="550" title="Selection Sort">
</p>

- o mesmo também é compreende: 

1. suporte aos métodos de acesso: conceitos de modelo (DDL) tais como dados domínios, relacionamento e restrições, e a manipulação dos conceitos modelados (DML)

2. esquema lógico do BD: resulta da especificação dos dados de um domínio de aplicação em um modelo de BD.

