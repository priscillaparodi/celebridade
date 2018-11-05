# Chatbot com Watson

This app is a front-end of a chatbot that uses Watson Conversation. 
Please do the following steps:
1) Create a account on https://www.bluemix.net;
2) Go to Bluemix catalog and create a Watson Conversation service;
3) Create a conversation as the guidance -->> 
4) Back to Bluemix catalog and create Continuous Delivery service and follwoing steps -->>
5) Change the file config/bot.js with your credentials of Watson Conversation and WOrkspace id create, in lines 26, 27 and 32, as the following:
    username = "xxxx-xxxx-xxxxxx-xxxx";
    password = "xxxxxxxx";
    conversationWorkspace = "xxx-xxxxx-xxxxx-xxxxx-xxxx";


[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/priscillaparodi/youtube-bot)

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
"# Conversation-demo" 
