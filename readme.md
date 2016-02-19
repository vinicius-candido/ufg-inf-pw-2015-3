
# Laboratório de PW 2015/2

## Links

### Vídeos das Aulas

* [Aula 1](https://www.dropbox.com/s/jkmqheu97lt4h6y/aula-01.zip?dl=0)
* [Aula 2](https://www.dropbox.com/s/rv1qr9pfhrj9nwf/aula-02.zip?dl=0)
* [Aula 3](https://www.dropbox.com/s/7e7qyan4cv323zg/aula-03.zip?dl=0)

### Materiais

* [W3Schools](http://www.w3schools.com/) - Online Web Tutorials (site)
  * [HTML](http://www.w3schools.com/html/)
  * [CSS](http://www.w3schools.com/css/)
  * [Java Script](http://www.w3schools.com/js/)
* [Aplicações Java para a web com JSF e JPA](http://www.casadocodigo.com.br/products/livro-jsf-jpa) (livro)
* [JSF Eficaz](http://www.casadocodigo.com.br/products/livro-jsf-eficaz) (livro)
* [Coletânea Front-end](http://www.casadocodigo.com.br/products/livro-coletanea-front-end) (livro)
* [HTML5 e CSS3](http://www.casadocodigo.com.br/products/livro-html-css) (livro)

### Bootstrap

* [Boootstrap](http://getbootstrap.com/)
* [Bootsnip](http://bootsnipp.com/)
* [Wrap Bootstrap](https://wrapbootstrap.com/)
* [Start Bootstrap](http://startbootstrap.com/)
* [Bootstrap Zero](http://www.bootstrapzero.com/)

### JSP

* [Tutorials Point - JSP Tutorial](http://www.tutorialspoint.com/jsp/)
* [The Java EE 5 Tutorial - JSP](http://docs.oracle.com/javaee/5/tutorial/doc/bnagx.html)

### Outros

* [Digital Ocean](https://www.digitalocean.com/)
* [Foundation](http://foundation.zurb.com/)
* [Semantic UI](http://semantic-ui.com/)
* [Flat Design vs Realism](http://www.flatvsrealism.com/)
* [Animate.css](https://daneden.github.io/animate.css/)
* [Balsamiq Mockups](https://balsamiq.com/products/mockups/)
* [SQuirreL SQL Client - Gerenciador de banco de dados](http://squirrel-sql.sourceforge.net/)
* [DBVisualizer - Gerenciador de banco de dados](https://www.dbvis.com)


## Executando a Aplicação

Goal do Maven para executar a aplicação com o Tomcat:

`org.apache.tomcat.maven:tomcat7-maven-plugin:2.2:run`

Para rodar numa porta específica, coloque o seguinte parâmetro:

Nome do parâmetro: `maven.tomcat.port`
Valor do parâmetro: `9090`

## Modelo Web

Comunicação Client/Server                      | Interação com o Usuário
---------------------------------------------- | ----------------------------------------------
![web-model-01.png](src/site/web-model-01.png) | ![web-model-02.png](src/site/web-model-02.png)

## Segunda Prova

* Organização do sistema em camadas lógicas de aplicação.
  * Data Access Object (DAO).
  * Business Object (BO).
  * Integração dos padrões MVC, DAO e BO
* Comunicação com banco de dados.
  * Java Database Connectivity (JDBC)
    * Obtentendo conexão com o banco de dados.
    * Gravando dados.
    * Obtendo dados.
    * Trabalhando com transações.
  * Java Persistence API (JPA)
    * Obtentendo conexão com o banco de dados.
    * Gravando dados.
    * Obtendo dados.
    * Trabalhando com transações.
    * Pool de conexões.
