# **Ecommerce Back-End**

## **Descrição**
Este é o back-end de um sistema de e-commerce desenvolvido com Java 23 e Spring Boot, projetado para oferecer uma arquitetura robusta e modular em camadas. Ele fornece uma API RESTful para gerenciar produtos, usuários, carrinhos de compras, categorias e marcas, além de integração com um banco de dados MySQL e H2 para testes.

---

## **Tecnologias Utilizadas**
- **Java 23**: Linguagem principal para o desenvolvimento.
- **Spring Boot**: Framework para construção de APIs REST.
  - Spring Web
  - Spring Data JPA
  - Spring Security
- **MySQL**: Banco de dados relacional principal.
- **H2**: Banco de dados em memória para testes.
- **Hibernate**: ORM para persistência.
- **Lombok**: Redução de código boilerplate.
- **Swagger/OpenAPI**: Documentação da API.
- **Maven**: Gerenciamento de dependências e build.

---

# **Como Configurar o Banco de Dados**

 **Para Testes: H2**

O banco de dados **H2** será usado por padrão em ambiente de testes. A configuração já está pronta no arquivo application-test.properties:

```properties
spring.datasource.url=jdbc:h2:mem:ecommerce
spring.datasource.driver-class-name=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=create-drop
spring.h2.console.enabled=true
```

**Para acessar o console do H2, use**:

- URL: http://localhost:8080/h2-console
- JDBC URL: jdbc:h2:mem:ecommerce
- User: sa
- Password: (deixe em branco)


## **Executando o Projeto**

**Clone o Repositório**

```bash
git clone https://github.com/seu-usuario/ecommerce-backend.git
cd ecommerce-backend
```
**Compile e Execute**

```bash
mvn spring-boot:run
```
**Acesse a API**

```arduino
http://localhost:8080
```


## **Estrutura do Projeto**

~~~text
src/main/java/com/ecommerce/
├── controller/         # Camada de apresentação
├── service/            # Camada de lógica de negócios
├── repository/         # Camada de persistência
├── model/              # Entidades do sistema
├── dto/                # Objetos de transferência de dados
├── exception/          # Tratamento de exceções
├── config/             # Configurações do sistema
└── utils/              # Classes utilitárias
~~~

## **Documentação da API**

A documentação completa da API está disponível no Swagger. Acesse:

```bash
http://localhost:8080/swagger-ui.html
```

## **Contribuindo**
Contribuições são bem-vindas! Siga os passos abaixo para colaborar:

  1. Faça um fork do projeto.
  2. Crie uma branch para sua feature:
   
  ```bash
  git checkout -b minha-feature
  ```
  3. Faça as alterações e adicione os commits:
    
```bash
git commit -m "feat: descrição da feature"
```
  4. Faça o push:
    
```bash
git push origin minha-feature
```
  5. Abra um pull request no GitHub.

# 👏 Conecte conosco

# Carlos Eduardo
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaduesr/)[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KaduSR)[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaduesr@gmail.com)

# Alexsandro 
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexsandro-da-silva-antunes-b52a76267/)[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlexsandroSAntunes)

# Nícolas Santos
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white
)](https://www.instagram.com/nicolassantos.dev/)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/n%C3%ADcolas-santos-107467b2/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NickRicardo)




---



Este arquivo está em **Markdown** e pronto para ser utilizado como `README.md` no seu repositório. Ele está bem estruturado, abrangendo H2, MySQL e todos os pontos relevantes do projeto. Se precisar de mais ajustes, é só pedir! 😊
"# QuantumStoreVirtual" 
