# Bank API :bank:

## Descrição :page_facing_up:
Este projeto é uma API RESTful para gerenciamento de contas bancárias, permitindo operações CRUD (Criar, Ler, Atualizar, Deletar) sobre contas. Foi desenvolvido usando Spring Boot e segue as boas práticas de design e arquitetura REST.

## Tecnologias Utilizadas :computer:
- **Java**: Versão 17
- **Spring Boot**: Versão 3.2.5
- **Maven**: Versão 3.9.7

## Configuração e Instalação :wrench:

### Pré-requisitos:
- JDK 17
- Maven 3.9.7

### Instalação:
1. Clone o repositório:
   ```bash
   git clone [URL_DO_REPOSITORIO]
2. Navegue até a pasta do projeto: **cd Bank_API**

## Configuração:
Certifique-se de que o Maven está configurado corretamente em seu ambiente. Você pode verificar a versão do Maven com o seguinte comando: **mvn -v**

## Como Executar :arrow_forward:
Para rodar a aplicação, execute o seguinte comando na raiz do projeto: **mvn spring-boot:run**

## Endpoints Disponíveis :link:
1. POST /api/v1/contas: Cria uma nova conta
2. GET /api/v1/contas: Lista todas as contas
3. GET /api/v1/contas/{id}: Busca uma conta pelo ID
4. PUT /api/v1/contas/{id}: Atualiza os detalhes de uma conta
5. DELETE /api/v1/contas/{id}: (Opcional) Deleta uma conta pelo ID
