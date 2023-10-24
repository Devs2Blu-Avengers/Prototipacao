# Saveblu 

Projeto desenvolvido como avaliação final do curso +Dev2Blu 2023. A Saveblu é uma aplicação
que gerência denúncias e solicitações de SOS quando o cidadão estiver em perigo de acordo com a sua localização.

#Figma

[Para ver uma simulação do aplicativo clique aqui](https://www.figma.com/proto/CEcNU5FwVZSpT18mN2P2OE/SAVEBLU?type=design&node-id=1-2&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A2)

[Para ver todas a telas do nosso aplicativo clique aqui](https://www.figma.com/file/CEcNU5FwVZSpT18mN2P2OE/SAVEBLU?type=design&node-id=0-1&mode=design)

# Diagrama de Classes

![Diagrama de Classes](https://github.com/Devs2Blu-Avengers/Saveblu-Api/raw/main/documentation/Class%20Diagram.png)

# Diagrama ER



![Diagrama ER](https://github.com/Devs2Blu-Avengers/Saveblu-Api/raw/main/documentation/DiagramaER.png)

# Requisitos Funcionais

- Como um cidadão quero solicitar um S.O.S quando minha vida estiver em risco.
- Como um cidadão quero registrar uma denúncia sobre problemas e crimes Ambientais.
- Como um cidadão quero registrar uma denúncia sobre outros assuntos.
- Como cidadão quero visualizar pontos no mapa de acordo com uma categoria escolhida.
- Como cidadão quero receber notificações sobre alertas próximos a mim.
- Como um usuário da Defesa Civil quero visualizar denúncias ou S.O.S. e filtrar por categorias. 
- Como um usuário "especial" quero receber notificações sobre S.O.S. que posso atender próximos a mim.

# Requisitos Não Funcionais

- Desenvolvido em Java SDK 17.

- Spring Boot Framework.

- Cobertura mínima de código de 50%(testes unitários).

- Banco de Dados em Postgres.

- Documentação das API’s no Swagger.

- Maven para gerenciamento das dependências do projeto.
- Flyway para gerenciamento dos migrations do projeto.

- Deploy da aplicação na AWS.

# Regras de Negócio

- Deve ser possível para o usuário visualizar uma lista de incidentes próximos.
- Usuários do tipo cidadão ou não logado só podem visualizar o tipo do incidente, sem nenhum outro dado adicional.
- Usuários especiais podem visualizar informações adicionais do incidente de acordo com o seu tipo de usuário.
- Um usuário é automaticamente cadastrado ao se logar com o google.
- A aplicação deve permitir filtrar os incidentes por categoria.

# User-Flow: 
![Diagrama de fluxo de usuário](https://github.com/Devs2Blu-Avengers/Prototipacao/assets/99457651/0367e587-4d24-46d1-b18d-32b51104aa8f)

# Design de Interface do Usuário (UI):
-Estilo visual atrativo, consistência entre os elementos da interface e layout intuitivo e organizado.

# Documentação

- Documentação swagger pode ser visualizada na url da Api Rest acrescentando o caminho /swagger-ui/index.html

- [Arquivo Insomnia](https://github.com/Devs2Blu-Avengers/Saveblu-Api/blob/main/documentation/IncidenceController_Endpoints_Insomnia_2023-10-23.json)

 
