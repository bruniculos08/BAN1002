# Aula 03

**Modelagem** 

- Quadrado: entidade
- Quadrado dentro de quadrado: entidade fraca e guarda uma informção que pode se repetir e que não possui chave primária específica (sua chave está em outra entidade).
- Losango: relação simples.
- Losango com quadrado em volta: entidade relacional.
- Objeto Oval não vazio: atributo simples. 
- Objeto Oval não vazio e sublinhado: atributo que é chave primária.

Note que podemos ter:

1) Relação simples entre duas entidades: dada uma entidade A e uma entidade B, A se relaciona com 1 B e B se relaciona com n A's, o que é representado
por dois quadrados ligado por uma linha, com o número 1 na ponta da linha conectada e B e com o número m na ponta da linha conecta em A; só é utilizada em relação
de 1-1 ou n-1.

**[A]-1--<>--n-[B]**

2) Relação via entidade entre duas entidades: dada uma entidade A e uma entidade B, A se relaciona com n B's e B se relaciona com m A's, devemos nesse caso utilizar 
uma entidade de relacionamento C, visto que se trata de uma relação m-n, assim teremos:

**[A]-1---n-[<'C'>]-n---1-[B]**
