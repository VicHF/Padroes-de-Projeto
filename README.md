# Padrões de Projetos com Java

Neste repositório são explorados algumas implementações de padrões de projeto (design patterns), tanto com Java puro quanto com Spring Framework.

### Com **Java puro** foram utilizados os seguintes:

*Padrão Criacional*
- Singleton: Permite a criação de uma única instância de uma classe e fornece um modo para recuperá-la.

*Padrão Comportamental*
- Strategy: Simplifica a variação de algoritmos para a resolução de um mesmo problema.

*Padrão Estrutural*
- Facade: Provê uma interface que reduz a complexidade nas integrações com subsistemas.

<br>

### Com **Spring Framework** foram utilizados os seguintes:
- Singleton
- Strategy/Repository
- Facade

Projeto gerado a partir do [Spring Initializr](https://start.spring.io/)

Dependências utilizadas:

**Spring Web** para poder prover API Rest;

**Spring Data JPA** que abstrai a parte de persistência de bancos relacionais;

**H2 Database** é um banco de dados em memória;

**OpenFeign** consegue criar um cliente http pra consumir API externa.

