Integrando  Chatbot com o WhatsApp Usando Amazon Lex

## Serviços utilizados

- Amazon Lex
- Whatsapp
- Twilio
 
 ## Como ficou na AWS
 Aqui o chat esta ativo
 ![Protótipo 01](chat2.png)
Aqui o chatbot onde eu tenho uma conversa com ele sobre as reservas
 ![Protótipo 02](chatbot.png) width="250" height="250" alt= "prototipo"

## Etapas

- Criar um chatbot no Amazon Lex
- Criar uma conta no Twilio
- Integrar com Whatsapp

## Criando uma conta no Twilio

- Acessar https://www.twilio.com/
- Validar email e número de celular

## Criando um chatbot de exemplo no Amazon Lex

 - AWS Console -> Lex -> Bots -> Create bot -> Start with an example -> Book Trip -> Bot name [escolher um nome] -> Create a role with basic Amazon Lex permissions -> Children’s Online Privacy Protection Act (COPPA) [No] -> Next
 - Language en-US -> Done
 - Build -> Test

## Integrando o Amazon Lex com o Whatsapp via Twilio

- Twilio Console -> My account -> Copiar SID e Token
- Amazon Lex Console -> Bot versions -> Deployment -> Channel Integrations -> Add channel -> Platform - Twilio SMS -> Inserir Account SID e Authentication token -> Create -> Copiar url de endpoint gerado
- Twilio Console -> Messaging -> Settings -> Whatsapp sandbox settings -> Colar endpoint copiado em WHEN A MESSAGE COMES IN

## Testando a integração

- Enviar mensagens e verificar as respostas
