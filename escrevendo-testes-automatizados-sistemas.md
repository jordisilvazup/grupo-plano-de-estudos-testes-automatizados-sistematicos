# Plano de estudos sobre Testes Automatizados

Os testes são uma parte fundamental do processo de desenvolvimento de software. Eles permitem garantir a qualidade, a estabilidade e a funcionalidade do software e ajudam a evitar prejuízos financeiros e de reputação para a empresa. Existem diferentes tipos de testes que podem ser realizados durante o desenvolvimento de software, cada um com sua importância e finalidade específicas.

Os testes unitários são responsáveis por testar as funcionalidades individuais do software, garantindo que elas funcionem de acordo com o esperado. Esses testes são geralmente automatizados e podem ser executados com rapidez, permitindo que os desenvolvedores identifiquem problemas rapidamente e façam correções antes que eles se tornem mais complexos e difíceis de resolver. Os testes unitários são uma parte essencial do processo de desenvolvimento de software e ajudam a garantir a qualidade do código.

Os testes de integração, por outro lado, verificam a interação entre as diferentes funcionalidades do software. Eles são responsáveis por garantir que o software funcione de forma integrada e que as diferentes partes do sistema estejam funcionando corretamente. Esses testes podem ser mais complexos e demorados do que os testes unitários, mas são essenciais para garantir a qualidade do software e evitar problemas futuros.

Outra técnica importante de teste é o Teste de Aceitação, que verifica se o software atende aos requisitos do usuário e se está funcionando corretamente. Esses testes podem ser escritos usando ferramentas como o Selenium e o Cucumber, que permitem a automação de testes de interface de usuário e a escrita de testes baseados em comportamento. Os testes de aceitação são essenciais para garantir que o software entregue atenda às expectativas dos clientes e atenda aos objetivos de negócio.

Além disso, os testes de aceitação também podem ser usados para criar testes de histórias de usuário e testes voltados para o negócio, que verificam se as funcionalidades do software estão atendendo às expectativas do cliente e se estão alinhadas com os objetivos de negócio. Esses testes são importantes para garantir que o software entregue atenda às expectativas dos clientes e atenda aos objetivos de negócio.

Para garantir que o software esteja sendo testado adequadamente, é importante adotar uma pirâmide de testes bem estruturada. A pirâmide de testes é uma estratégia que divide os testes em três camadas: testes unitários, testes de integração e testes de aceitação. Os testes unitários são responsáveis por testar as funcionalidades individuais do software, enquanto os testes de integração testam a interação entre essas funcionalidades. Já os testes de aceitação são responsáveis por garantir que o software atenda às expectativas do usuário. A pirâmide de testes é uma abordagem eficaz para garantir que o software seja testado de forma completa e eficiente.

Por fim, é importante ressaltar que os testes não devem ser vistos como uma tarefa secundária ou desnecessária durante o processo de desenvolvimento de software. Testes de qualidade são essenciais para garantir a estabilidade, a segurança e a funcionalidade do software e para evitar prejuízos.

1. [Testes automatizados: conceitos e importância](#1-testes-automatizados-conceitos-e-importância)
2. [Testes Unitarios, definindo e testando unidades de codigo.](#2-testes-unitarios-definindo-e-testando-unidades-de-codigo)
3. [Técnicas de Testes](#3-tecnicas-de-testes)
4. [Introdução a Testes Integrados conceitos e importânciaa](#4-introdução-a-testes-integrados-conceitos-e-importância)
5. [Testes Integrados com Spring Boot](#5-testes-integrados-com-spring-boot)
6. [Pirâmide de testes: conceitos e estratégias para criação de testes automatizados](#6-pirâmide-de-testes-conceitos-e-estratégias-para-criação-de-testes-automatizadosa)
7. [Testes de ponta a ponta: conceitos e técnicas para criação](#7-testes-de-ponta-a-ponta-conceitos-e-técnicas-para-criação)
8. [Testes de aceitação do usuário: conceitos e técnicas para criação](#8-testes-de-aceitação-do-usuário-conceitos-e-técnicas-para-criação)
9. [Testes de Contrato](#9-testes-de-contrato)

Ao fim desse plano de estudos, você terá heuristicas úteis que te ajudarão a olhar para trechos de código e que te permitirão identificar quais são os testes que ajudaram a encontrar bugs de foram antecipada.

## 1. Testes automatizados: conceitos e importância

- [Diferença entre fases de teste, tipos de teste e formas de execução](https://www.zup.com.br/blog/tipos-de-teste)
- [Automação de teste de software (com JUnit)](https://github.com/sf105/sttp-book/blob/master/chapters/getting-started/test-automation.md)

###  Validando o conhecimento
- [Responda este questionario](https://hr.gs/conceitos-de-testes-automatizados)

## 2. Testes Unitarios, definindo e testando unidades de codigo.
- [Conceitos de Testes Unitarios com Martin Fowler](https://martinfowler.com/bliki/UnitTest.html)
- [Conceitos de Testes Unitarios com Mocks(Dubles) com Martin Fowler](https://martinfowler.com/bliki/TestDouble.html)
- [Criando rotinas de testes para fluxos de exceção e erro](http://blog.triadworks.com.br/junit-testando-fluxos-de-excecao-e-erro)

###  Validando o conhecimento
- [Responda este questionario](https://hr.gs/conceitos-de-testes-unitarios)

## 3. Tecnicas de Testes 
- [Zup Decodifica: testes automatizados](https://youtube.com/playlist?list=PLkX9oUrQ1ev4t-3laXn7H03PBCazMULYh)
- [Testes de Unidade Reveladores de Bugs](https://handora.zup.com.br/treino-completo/15)
- [Effective Software Testing, capitulo Specification Based Test](https://www.manning.com/books/effective-software-testing)
- [Specification Based Test](https://github.com/zup-academy/materiais-publicos-treinamentos/blob/main/testes-de-unidade-reveladores-de-bugs/specification-test.md)
- [Boundary Testing](https://github.com/zup-academy/materiais-publicos-treinamentos/blob/main/testes-de-unidade-reveladores-de-bugs/boundary-test.md)
- [Structural Test (Cobertura)](https://github.com/zup-academy/materiais-publicos-treinamentos/blob/main/testes-de-unidade-reveladores-de-bugs/structural-test.md)
- [Effective Software Testing, capitulo Structural Test](https://www.manning.com/books/effective-software-testing)

## 4. Introdução a Testes Integrados conceitos e importância

- [Conceitos de Testes Integrados com Martin Fowler](https://martinfowler.com/bliki/IntegrationTest.html)         
- [O que são testes de integração](https://www.youtube.com/watch?v=S73guxvsKNk)
- [Software Engineering | Integration Testing](https://www.geeksforgeeks.org/software-engineering-integration-testing/)           
- [Unidade, integração ou sistema? Qual teste fazer?](https://www.alura.com.br/artigos/unidade-integracao-ou-sistema-qual-teste-fazer?gclid=Cj0KCQjw2cWgBhDYARIsALggUhqdHQOq-tnJ19arCkRxQSXfix-vP0X1t7wkNLuWZmyfH1FZuT96RBcaAh0HEALw_wcB)

###  Validando o conhecimento
- [Responda este questionario](https://hr.gs/conceitos-de-testes-integrados)
              
## 5. Testes Integrados Com Spring Boot

- [Escrevendo Testes de Integracao para REST APIs  de Cadastro com Spring Boot e Spring Test](https://handora.zup.com.br/cardapio/15)
- [Escrevendo Testes de Integracao para REST APIs  de Atualização com Spring Boot e Spring Test](https://handora.zup.com.br/cardapio/58)          
- [Escrevendo Testes de Integracao para REST APIs  de Consulta com Spring Boot e Spring Test](https://handora.zup.com.br/cardapio/57)
- [Testes de Integracao para REST APIs de Remoções com Spring Boot e Spring Test](https://handora.zup.com.br/cardapio/59)
- [Escrevendo Testes de Integração para Producers Kafka Com Spring Boot e EmbeddedBroker](https://dev.to/jordihofc/escrevendo-testes-de-integracao-para-producers-kafka-com-spring-boot-e-embeddedbroker-5b94)
- [3 motivos do porquê testes unitários não são suficientes para Microservices com Spring Boot](https://dev.to/jordihofc/3-motivos-do-porque-testes-unitarios-nao-sao-suficientes-para-microservices-com-spring-boot-33lk)
- [Segurança de APIs REST com Spring Security e OAuth2: Escrevendo testes de integração para sua API REST protegida por OAuth2](https://handora.zup.com.br/cardapio/67)

## 6. Pirâmide de testes: conceitos e estratégias para criação de testes automatizados

- [On the Diverse And Fantastical Shapes of Testing](https://martinfowler.com/articles/2021-test-shapes.html)
- [Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
- [Pragmatismo, estratégia e pirâmide de testes | Zup Decodifica: testes automatizados](https://www.youtube.com/watch?v=xDV-uSN5MjM)
- [Piramede de Testes por Caleum](https://github.com/caelum/apostila-microservices-com-spring-cloud/blob/master/11-testes-automatizados-e-contratos.md#pir%C3%A2mide-de-testes)

###  Validando o conhecimento
- [Responda este questionario](https://hr.gs/conceitos-de-piramide-testes)

## 7. Testes de ponta a ponta: conceitos e técnicas para criação

- [Testes E2E - Testando a aplicação de ponta a ponta como um usuário](https://www.youtube.com/watch?v=0-hoAU7LtxA)
- [Selenium: testes automatizados de aceitação em Java](https://www.alura.com.br/conteudo/selenium-testes-automatizados-aceitacao-java)
- [Curso Selenium: testes automatizados de aceitação em Java](https://www.alura.com.br/curso-online-selenium-testes-automatizados-aceitacao-java?gclid=Cj0KCQjw8qmhBhClARIsANAtbofuPXNjLdX6bVXRWxGUpLfHkgLvJufYdSG_-fc-vxdnciV4-XqA5G0aArk_EALw_wcB)
- [Testes de aceitação com o Selenium](https://www.alura.com.br/artigos/testes-de-aceitacao-com-o-selenium)
- [Tutorial: Criando testes automatizados de aceitação com Cucumber e Selenium](https://medium.com/@junioalbino/tutorial-criando-testes-automatizados-de-aceita%C3%A7%C3%A3o-com-cucumber-e-selenium-f675374ad45)

###  Validando o conhecimento
- [Responda este questionario](https://hr.gs/conceitos-de-testes-de-ponta-a-ponta)


## 8. Testes de aceitação do usuário: conceitos e técnicas para criação
- [User Journey Test ](https://martinfowler.com/bliki/UserJourneyTest.html)
- [Story Test](https://martinfowler.com/bliki/StoryTest.html)
- [Business Facing Test](https://martinfowler.com/bliki/BusinessFacingTest.html)
- [Testes de Aceitação e suas boas práticas](https://www.alura.com.br/artigos/testes-de-aceitacao-e-suas-boas-praticas)
- [Flaky tests: o que comem, onde vivem, e como reproduzem](https://www.youtube.com/watch?v=NE0Hf4HsH7o)
- [Flaky tests: As dez principais causas e possíveis soluções](https://youtu.be/AaFvJ2H0k3Y)

###  Validando o conhecimento
- [Responda este questionario](https://hr.gs/conceitos-de-testes-de-aceitacao)

## 9. Testes de Contrato

- [Testes de Contrato por Caleum](https://github.com/caelum/apostila-microservices-com-spring-cloud/blob/master/11-testes-automatizados-e-contratos.md#testes-de-contratos)
- [The Contract Test](https://martinfowler.com/bliki/ContractTest.html)

###  Validando o conhecimento
- [Responda este questionario](https://hr.gs/conceitos-de-testes-de-contrato)
