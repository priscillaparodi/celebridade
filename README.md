# Chatbot com Watson

Esse app contém um front que comunica com o Watson Assistant;
Siga os seguintes passos:
1) Crie uma conta no https://www.bluemix.net;
2) No catálogo busque por Watson Assistant e crie o serviço;
3) Crie um chatbot;
4) Clique no botão "Deploy to IBM Cloud";
5) Mude o arquivo config/bot.js com as suas credenciais do Watson Assistant, dessa forma:

    username = "xxxx-xxxx-xxxxxx-xxxx";
    password = "xxxxxxxx";
    conversationWorkspace = "xxx-xxxxx-xxxxx-xxxxx-xxxx";

[![Deploy to IBM Cloud](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/priscillaparodi/celebridade)

## Para executar o app localmente

1. [Instalar Node.js][]
+ cd no diret'roio raiz do projeto
+ Execute `npm install` para instalar as dependências do app
+ Altere o aquivo config/bot.js e coloque as credenciais e workspace_id do conversation nas lilnhas à seguir:
    
    username = "<username>";
    password = "<password>";
    conversationWorkspace = "<workspace_id>";

+ Execute `npm start` para o iniciar o app
+ Acesse a aplicação no browser no link <http://localhost:6001>

[Instale Node.js]: https://nodejs.org/en/download/
