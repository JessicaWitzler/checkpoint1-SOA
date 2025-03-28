# Integrantes do Grupo
- **Vinícius Almeida Bernardino de Souza** - 97888
- **Jessica Witzler Costacurta** - 99068
- **Márcio Hitoshi Tahyra** - 552511


## Configuração do Banco de Dados

```properties
spring.application.name=checkpoint1
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
spring.jpa.hibernate.ddl-auto=update
spring.h2.console.enabled=true
```

## Instruções de uso:
- **JDK 21**
- **Apache Maven 3.9.9**
- **mvn spring-boot:run**

## Testes:

1. Criar um novo pedido.
![image](https://github.com/user-attachments/assets/7194ab9c-0386-4494-9852-6460d4988952)

2. Buscar todos os pedidos.
![image](https://github.com/user-attachments/assets/71d9c947-1621-485d-83be-4616218bdc00)

3. Buscar um pedido pelo ID.
![image](https://github.com/user-attachments/assets/9b9d098a-6a96-4ee0-8424-0b7fa61e99c6)

4. Atualizar um pedido.
![image](https://github.com/user-attachments/assets/966ad9ac-1911-4a82-a1e0-ce12ef1c0bc4)

5. Deletar um pedido.
![image](https://github.com/user-attachments/assets/19fccaee-d2c5-4cab-9e21-a0035d499c15)

![image](https://github.com/user-attachments/assets/7baecb05-1fa6-4765-bcfd-64104f7ed6b5)
