# 🛠️ Workshop Spring Boot MongoDB

Bem-vindo ao projeto Workshop Spring Boot MongoDB! Este é um projeto de exemplo que demonstra boas práticas para construir uma API RESTful completa usando Spring Boot e MongoDB.

## Sobre o Projeto

O objetivo deste projeto é fornecer um exemplo prático de como criar uma API RESTful usando Spring Boot e MongoDB. O projeto aborda boas práticas de desenvolvimento, incluindo arquitetura, organização de código, segurança, testes e documentação.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter o seguinte configurado:

1. 📦 **Java Development Kit (JDK):** Instale o JDK compatível com o Spring Boot em sua máquina.
2. 🍃 **MongoDB:** Configure um servidor MongoDB local ou remoto. Certifique-se de ter as credenciais de acesso necessárias.
3. ⚙️ **Configurações de Banco de Dados:** Altere as configurações do banco de dados no arquivo `application.properties` para corresponder ao seu ambiente.

## Executando o Projeto

Siga estas etapas para executar o projeto em sua máquina local:

1. 🔄 **Clone este repositório em sua máquina:**

   ```bash
   git clone https://github.com/seu-usuario/workshop-spring-boot-mongodb.git

 📂 Navegue até o diretório do projeto:

bash 
cd workshop-spring-boot-mongodb


2. 🛠️ Abra o arquivo application.properties e configure as propriedades do banco de dados de acordo com o seu ambiente:

spring.data.mongodb.host=localhost
spring.data.mongodb.port=27017
spring.data.mongodb.database=nome-do-seu-banco-de-dados
spring.data.mongodb.username=seu-usuario
spring.data.mongodb.password=sua-senha

3. ▶️ Execute o projeto usando o Maven:
./mvnw spring-boot:run

4. 🚀 Após a inicialização bem-sucedida, a API estará disponível em http://localhost:8080.

Endpoints da API
A API possui os seguintes endpoints principais:

📄 GET /api/produtos: Retorna todos os produtos.
📄 GET /api/produtos/{id}: Retorna um produto específico com base no ID.
✏️ POST /api/produtos: Cria um novo produto.
✏️ PUT /api/produtos/{id}: Atualiza um produto existente com base no ID.
🗑️ DELETE /api/produtos/{id}: Exclui um produto existente com base no ID.
Para obter mais informações sobre os endpoints e parâmetros de solicitação, consulte a documentação da API.

Contribuição
Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novos recursos, sinta-se à vontade para enviar uma solicitação de pull.

Licença
Este projeto é licenciado sob a Licença MIT.

Nota: Este projeto é apenas para fins educacionais e de demonstração. Certifique-se de revisar e personalizar as configurações de banco de dados e segurança de acordo com as práticas recomendadas antes de implantar em um ambiente de produção.
