# Tarefa 02 - MER e Projeto de Banco de Dados Relacional

## Q1. Descreva os três elementos básicos de um Modelo Entidade Relacionamento (MER).

O Modelo Entidade-Relacionamento é construído a partir de três elementos básicos:

**1. Entidade**
Representa um objeto ou conceito do mundo real sobre o qual queremos armazenar dados, e que tem existência própria e independente (ex.: Cliente, Funcionário, Projeto). É representada graficamente por um retângulo. Cada entidade dá origem a um conjunto de ocorrências (instâncias) — por exemplo, cada cliente cadastrado é uma instância da entidade Cliente.

**2. Atributo**
É uma propriedade ou característica que descreve uma entidade ou um relacionamento (ex.: nome, email, data de nascimento). Atributos podem ser simples ou compostos, monovalorados ou multivalorados, e podem ser derivados de outros dados. Um ou mais atributos formam o **identificador** (chave primária) da entidade, ou seja, o conjunto mínimo de atributos capaz de distinguir uma ocorrência das demais.

**3. Relacionamento**
É uma associação entre duas ou mais entidades, representando como elas se relacionam no domínio do problema (ex.: "Cliente possui Projeto"). Todo relacionamento possui uma **cardinalidade**, que define quantas ocorrências de uma entidade podem se associar a quantas ocorrências de outra entidade (1:1, 1:N ou N:M).

