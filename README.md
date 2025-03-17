
![image](https://github.com/user-attachments/assets/57279f62-ad91-4f02-bf56-d4fb891a211a)

#  Desenvolvimento de API REST com Spring Boot

Este projeto tem como objetivo demonstrar o desenvolvimento de uma API REST completa utilizando Spring Boot 3, abordando desde a criação de um CRUD básico até conceitos mais avançados como validações, paginação e ordenação.

## ✨ Funcionalidades

* **CRUD (Create, Read, Update, Delete):** Implementação das quatro operações básicas para manipulação de dados. 
* **Validações:** Utilização do Bean Validation para garantir a integridade dos dados recebidos pela API. ✅
* **Paginação e Ordenação:** Implementação de mecanismos para otimizar a listagem de dados, permitindo a navegação e ordenação dos resultados.
* https://trello.com/b/O0lGCsKb/api-voll-med

##  Tecnologias

* **Spring Boot 3:** Framework para desenvolvimento rápido de aplicações Java. ️
* **Java 17:** Versão LTS da linguagem Java. ☕
* **Lombok:** Biblioteca para reduzir a verbosidade do código Java. ⚡
* **MySQL:** Banco de dados relacional para armazenamento dos dados da API. 
* **Flyway:** Ferramenta para controle de versionamento do banco de dados (Migrations). ✈️
* **JPA/Hibernate:** Framework para persistência de dados em aplicações Java. 
* **Maven:** Ferramenta para gerenciamento de dependências e build do projeto. ️
* **Insomnia:** Cliente REST para testes da API. 

##  Pré-requisitos

* Java 17 instalado. ✅
* Maven instalado. ✅
* MySQL instalado. ✅
* Insomnia (ou outra ferramenta de teste de API) instalado. ✅

## ⚙️ Configuração do Banco de Dados

1.  Crie um banco de dados MySQL com o nome desejado. ➕
2.  Configure as propriedades de conexão no arquivo `application.properties` ou `application.yml` do projeto Spring Boot. 

## ▶️ Execução

1.  Clone o repositório do projeto. 
2.  Execute o comando `mvn spring-boot:run` na raiz do projeto. 
3.  Acesse a API através do Insomnia ou outra ferramenta de teste de API. 

##  Testes

* Utilize o Insomnia para testar os endpoints da API, simulando requisições HTTP (GET, POST, PUT, DELETE). 
* Verifique as validações implementadas, enviando dados inválidos para a API. 
* Teste a paginação e ordenação, verificando se os resultados são retornados corretamente. 

##  Considerações

* Este projeto foca no desenvolvimento do backend da API, não incluindo uma interface gráfica ou frontend.
* https://www.figma.com/file/N4CgpJqsg7gjbKuDmra3EV/Voll.med
  
* Gerando um novo Cadastro por meio do Postman ou Insomia.
{
  "nome": "Rodrigo Ferreira",
  "email": "rodrigo.ferreira@voll.med",
  "telefone": "XX9XXXXXXXX",
  "crm": "123456",
  "especialidade": "ORTOPEDIA",
  "endereco": {
    "logradouro": "rua 1",
    "bairro": "bairro",
    "cep": "12345678",
    "cidade": "Brasilia",
    "uf": "DF",
    "complemento": "complemento",
    "numero": "1"
  }
} ️
* O uso do Flyway garante o controle de versionamento do banco de dados, facilitando a evolução do projeto. 
* O Lombok contribui para a redução da verbosidade do código, tornando-o mais limpo e legível. ✨
