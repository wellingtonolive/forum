# forum

## Descrição
O projeto é uma aplicação Back-End com objetivo de consultar topicos de um curso. Incluindo desenvolvimento do projeto de monitoramento, onde pode-se consultar o estado da API
que está sendo desenvolvida.


## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
  - [Git](https://git-scm.com) 
  - [Java 8](https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR)
  - [Maven](https://maven.apache.org/download.cgi)
  
Além disto é bom ter IDE para trabalhar com desenvolvimento em Java [Eclipse](https://www.eclipse.org/downloads/)

## 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/wellingtonolive/forum.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd forum

# Instale as dependências
$ mvn clean package

# Execute a aplicação 
$ mvn spring-boot:run

# O servidor inciará na porta:8080
Pronto. A aplicação está disponível em http://localhost:8080
```

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Spring Framework](https://spring.io/projects/spring-framework)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring MVC](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#mvc)
- [Spring Data](https://spring.io/projects/spring-data)

