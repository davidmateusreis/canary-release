<h1 align="center">
  Canary Release
</h1>

Este projeto demonstra a técnica de Canary Release utilizando o Spring Cloud Gateway. A implementação apresentada [nesse vídeo](https://www.youtube.com/watch?v=3RAoM3PPD_U) direciona 90% do tráfego para a versão stable do serviço e 10% para a versão canary. Essa configuração permite testar a nova versão em um pequeno grupo de usuários antes de disponibilizá-la para todos.

## Executando o projeto

- Clone o repositório para o seu diretório local.
- Instale as dependências necessárias.
- Execute a aplicação Spring Boot.
- Acesse o endpoint do serviço e observe o comportamento do roteamento de tráfego.

## Tecnologias
 
- [Spring Cloud Gateway](https://spring.io/projects/spring-cloud-gateway)

## Funcionamento

O Spring Cloud Gateway atua como um proxy, roteando as requisições de acordo com a configuração definida. No caso deste projeto, 90% das requisições são direcionadas para a versão stable do serviço, enquanto 10% são direcionadas para a versão canary. Essa configuração pode ser facilmente ajustada para direcionar diferentes percentuais do tráfego para cada versão.