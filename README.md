
# ShowTracker

ShowTracker é uma aplicação desenvolvida dentro da disciplina de Banco de Dados I do cursos de Sistema e Mídias Digitais da UFC. Ela serve para um usuário guardar sua lista de filmes e séries assistidas.

Para construir a aplicação e deixá-la funcional foi utilizado o dataset disponível do IMDB, com todas as informações de séries e filmes. Abaixo você vai encontrar instruções de como inserir esses dados no seu banco de dados local.

## Equipe Responsável

|  Nome                            |  Matrícula    |
|  :---                            |  ---:         |
|  Yanna Torres Gonçalves          |  507773       |
|  Ívina Lara de Sousa Rosa        |  507804       |
|  Samiris Sampaio de Albuquerque  |  509735       |

Apoio de:
* João Victor Barroso Alves
* Vládia Helen Ferreira Faria

---

## Modelagem do Banco de Dados

### Modelo Entidade-Relacionamento (MER) do Banco de Dados
<br/><br/>

![MER](mer.png)

### Modelo Relacional do Banco de Dados
<br/><br/>

![MR](mr.png)

---

## Especificações Técnincas

O projeto foi feito utilizando Java 17 como back-end e HTML, CSS e JavaScript para o front-end.

Para o banco de dados foi utilizado o PostgreSQL, como instruído dentro da cadeira. Mas na versão utilizada dentro da cadeira de Programação Orientada à Objetos, foi optado por utilizar SQLite.

## Como Rodar o Projeto

????

---

## Criação do Banco de Dados e Inserção dos Dados

**ATENÇÃO:** Caso seu usuário seja diferente de _postgres_ e a sua senha seja diferente de _ufc123_, por favor altere as informações correspontdentes dentro da classe DAO no seguinte arquivo: [DAO.java](./src/java/repository/DAO.java).
