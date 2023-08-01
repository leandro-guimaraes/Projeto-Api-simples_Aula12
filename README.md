

# API de Clientes usando ASP.NET Core

# Descrição:
Este é um projeto ASP.NET Core que implementa uma API simples para gerenciamento de clientes.
A API fornece endpoints para criar, recuperar, atualizar e excluir clientes a partir de um conjunto de dados simulado.
O projeto utiliza o padrão MVC e é construído sobre o framework ASP.NET Core.

# Recursos:
- ASP.NET Core
- MVC (Model-View-Controller) pattern
- Endpoint para listar todos os clientes
- Endpoint para recuperar cliente por ID
- Endpoint para recuperar cliente por CPF
- Endpoint para criar novo cliente
- Endpoint para atualizar cliente existente
- Endpoint para excluir cliente

# Instruções de Uso:
1. Clone este repositório em sua máquina local.
2. Abra o projeto no Visual Studio ou no Visual Studio Code.
3. Execute o projeto para iniciar o servidor local.
4. Use um cliente HTTP (por exemplo, Postman) para testar os diferentes endpoints da API.

# Observação:
Este projeto é apenas um exemplo de API de clientes simples e utiliza um conjunto de dados simulado.

# Postman:
Com o Postman, você pode enviar requisições HTTP para os endpoints da sua API e verificar as respostas recebidas. 
Isso permite testar o funcionamento correto da API, bem como verificar se ela está respondendo como esperado.

Aqui estão algumas etapas básicas para testar a API usando o Postman:

1. Abra o Postman e crie uma nova requisição.
2. Selecione o método HTTP adequado (GET, POST, PUT, DELETE) para o endpoint que deseja testar.
3. Insira a URL completa do endpoint que você deseja testar. Por exemplo, se você estiver testando o endpoint para recuperar um cliente por ID, a URL pode ser algo como "http://localhost:porta/api/customers/1", onde "porta" é a porta em que sua API está sendo executada e "1" é o ID do cliente que você deseja recuperar.
4. Se necessário, adicione parâmetros de consulta, cabeçalhos ou corpo da requisição, dependendo do tipo de endpoint que está testando.
5. Clique no botão "Send" (Enviar) para enviar a requisição para a sua API.
6. Verifique a resposta recebida no painel de resposta do Postman. Verifique se a resposta está correta, se os dados estão corretos e se o status da resposta é o esperado (por exemplo, 200 OK para sucesso, 404 Not Found para recurso não encontrado, etc.).

Usando o Postman, você pode testar todos os endpoints da sua API, garantindo que tudo esteja funcionando conforme o esperado. Além disso, o Postman permite que você salve e organize suas requisições para uso futuro, facilitando a realização de testes regulares na sua API.

Lembre-se de garantir que sua API esteja em execução localmente ou em um ambiente de teste acessível antes de iniciar os testes no Postman. E certifique-se de implementar as medidas de segurança apropriadas, como autenticação e controle de acesso, se a API estiver em um ambiente de produção.

![alllog](https://github.com/leandro-guimaraes/AllogEnter_Exercicios_Modulo_01/assets/85081592/c62c8d57-f214-49d5-a99d-107885af3366)
