# microservice---eureka
Este projeto é um microservice simples desenvolvido com a tecnologia Spring Boot utilizando Maven e API Rest, onde os demais projetos conseguem efetuar requisições apenas pelo nome dos projetos.

Obs: Este projeto só faz sentido executando juntamente com os outros 4 serviços
   - [Carteira](https://github.com/GustavoCSchmitz/microservice---carteira)
   - [Pagamentos](https://github.com/GustavoCSchmitz/microservice---pagamentos)
   - [Saque, depósito e transferencia](https://github.com/GustavoCSchmitz/microservice---saqueDeposito)
   - [Usuários](https://github.com/GustavoCSchmitz/microservice---usuarios)


### Requisitos de API e instruções para execução
 - Java 8
 - Maven 3 para construir o aplicativo.
 - Abrir na pasta raíz do projeto e executar o comando:
 
      `mvn clean install`
 - Após a instalação, subir o projeto com o comando:
       
      `mvn spring-boot:run`
      
### API endpoint
  - Método : GET
     - [http://localhost:8761/eureka/apps]()
     - Esta rota mostra todas as informações de nome e porta que os demais projetos estão rodando


 

 
