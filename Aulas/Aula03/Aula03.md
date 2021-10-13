# Aula 03

## **Modelo Relacional** 

**Definições:**

- Chave primária: é um atributo (coluna) de uma entidade (tabela) , qual serve para identifica-la e que não permite que haja uma repetição de itens dessa entidade visto que cada um tem um chave primária única.

- Chave Secundária: é um atributo (coluna) de uma determinada entidade (tabela) que referência outra registros de outra entidade.

- Domínio: é o conjunto de valores válido para determinado dado.

- Atributo: possui nome e domínio e pertence à uma entidade.

- Tupla: conjunto de pares, e nesse caso são usadas de (atributo, valor) ou (número mín., número máx.)

- Relação: formada por um cabeçalho (número fixo de atributos) e um corpo (número variável de tuplas).

- Agregação: quando em uma relação existem outras relações. 

**Figuras:**

- Retângulos: entidade
- Retângulos dentro de quadrado: entidade fraca e guarda uma informção que pode se repetir e que não possui chave primária específica (sua chave está em outra entidade).
- Losango: relação simples.
- Losango com quadrado em volta: entidade relacional usada no caso de agregações.
- Elipse não vazia: atributo simples. 
- Elipse não vazia e sublinhada: atributo que é chave primária.
- Linhas: ligam atributos (elipse) a conjuntos-entidades e conjuntos-entidade (retângulo) a conjunto-entidades ou a conjuntos-relacionamento (losango).

Note que podemos ter:

1) Relação simples entre duas entidades: dada uma entidade A e uma entidade B, A se relaciona com 1 B e B se relaciona com n A's, o que é representado
por dois quadrados ligado por uma linha, com o número 1 na ponta da linha conectada e B e com o número m na ponta da linha conecta em A; só é utilizada em relação
de 1-1 ou n-1.

**[A]-1--<>--n-[B]**

o que é equivalente à:

**[A]-(1,1)--<>--(0,n)-[B]**

2) Relação via entidade relacional entre duas entidades: dada uma entidade A e uma entidade B, A se relaciona com n B's e B se relaciona com m A's, devemos nesse caso utilizar 
uma entidade de relacionamento C, visto que se trata de uma relação m-n, assim teremos:

**[A]-1---n-[<'C'>]-n---1-[B]**

o que é equivalente à:

**[A]-(1,1)---(0,n)-[<'C'>]-(n,0)---(1,1)-[B]**

**obs.:** a entidade relacional sempre se relaciona com apenas 1 A e 1 B (caso contrário sua existência não seria necessária). 

Note que para cada uma das relações a seguir temos:

1. (1,1)--(1,1) chave estrangeira em uma das entidades.
2. (1,1)--(0,n) chaves estrangeiras apontando para n entidades dentro de uma entidade.
3. (0,n)--(0,n) [nessa há uma entidade relacional no meio] chave estrageira apontado para n entidades dentro de n entidades.

