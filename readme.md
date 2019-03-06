## References

### Create a Bot from a Template
- [Create a bot locally with .NET](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0)
- [Create a bot locally with JavaScript](https://docs.microsoft.com/en-us/azure/bot-service/javascript/bot-builder-javascript-quickstart?view=azure-bot-service-4.0)
- [.NET Core Templates](https://github.com/Microsoft/BotBuilder-Samples/tree/master/generators/dotnet-templates)

### Scaffolding a Basic Conversation
- [Debug bots with the Bot Framework Emulator](https://github.com/Microsoft/BotFramework-Emulator/wiki/Getting-Started)
- Bot Basics
    - [Designing the First Interaction](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-design-first-interaction?view=azure-bot-service-4.0)
    - [Designing bot UX](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-design-user-experience?view=azure-bot-service-4.0)
- Tutorials
    - [Welcoming the user](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-send-welcome-message?view=azure-bot-service-4.0)
    - [Implementing sequential conversation flow](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-conversation-flow?view=azure-bot-service-4.0&tabs=javascript)
    - [Gather user input using a dialog prompt](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-prompts?view=azure-bot-service-4.0&tabs=csharp)
    - [Using Rich Cards and Buttons](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-add-media-attachments?view=azure-bot-service-4.0&tabs=csharp)
    - [Menu-bot Wiki and Sample](http://aka.ms/menu-bot)
- [BotBuilder Samples on GitHub](https://github.com/Microsoft/BotBuilder-Samples) - Look at the relevant samples based on the tutorials and documentation linked above

### Deploying and Embedding your Bot in a Website
- Bot basics
    - [BotBuilder Samples on GitHub](https://github.com/Microsoft/BotBuilder-Samples)
    - [Embed a bot in a Website](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-design-pattern-embed-web-site?view=azure-bot-service-4.0)
- Bot deployment
    - [Deploy your Bot to Azure](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-deploy-az-cli?view=azure-bot-service-4.0)
    - [Continuous deployment to Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/deploy-continuous-deployment)
- Bot Framework channels
    - [Channels and the Bot Connector Service](https://docs.microsoft.com/en-us/azure/bot-service/bot-concepts?view=azure-bot-service-4.0)
    - [Implement channel-specific functionality](https://docs.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-channeldata?view=azure-bot-service-4.0)
    - [Channel Inspector](https://docs.botframework.com/en-us/channel-inspector/channels/Skype/)

### QnA Maker and Dialogs
- Bot Concepts and Tools
    - QnA Maker
        - [QnAMaker.ai Documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/overview/overview)
        - [Use QnA Maker to answer questions in a bot](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-qna?view=azure-bot-service-4.0)
    - Dialog Flows
        - [Gather user input using Dialogs library](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-prompts?view=azure-bot-service-4.0)
        - [Menu-bot Wiki and Sample](http://aka.ms/menu-bot)
    - State Management
        - [Manage Conversation and User Data](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-state?view=azure-bot-service-4.0)
        - [Persist user data when using Dialogs library](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-tutorial-persist-user-inputs?view=azure-bot-service-4.0)
- Other Services
    - [Azure Search](https://docs.microsoft.com/en-us/azure/search/)
    - [Full Text Search](https://docs.microsoft.com/en-us/sql/relational-databases/search/full-text-search)

### Azure Search and Rich Controls
- Azure Search
    - [Azure Search](https://docs.microsoft.com/en-us/azure/search/)
    - [How to import data into Azure Search index using the Azure portal](https://docs.microsoft.com/en-us/azure/search/search-import-data-portal)
- [Lucene Search](https://lucene.apache.org/)
- Card/Carousel Docs
    - [.NET](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-add-media-attachments?view=azure-bot-service-4.0&tabs=csharp)
    - [Node](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-add-media-attachments?view=azure-bot-service-4.0&tabs=javascript)
- Card/Carousel Sample
    - [.NET](https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore/06.using-cards)
    - [Node](https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_nodejs/06.using-cards)

### NLP with LUIS
- Natural language processing
    - [LUIS.ai](http://www.luis.ai)
    - [How to plan your LUIS app](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/luis-how-plan-your-app)
    - [LUIS best practices](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/luis-concept-best-practices)
    - [Add natural language processing to your bot](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-luis?view=azure-bot-service-4.0&tabs=js)
- LUIS code samples
    - [C#](https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore/12.nlp-with-luis)
    - [Node](https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_nodejs/12.nlp-with-luis)

### Authentication in a Bot
- [Add authentication to your bot via Azure Bot Service](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-authentication?view=azure-bot-service-4.0&tabs=csharp)
- Azure AD (Optional)
    - [What is Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis)
    - [Azure Active Directory authentication basics](https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios)

### Proactive Messaging from a Bot
- [Proactive messaging](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-proactive-messages?view=azure-bot-service-4.0)
- [Proactive Messaging Samples and Wiki](https://github.com/lucashuet93/botbuilder-proactivemessaging)
- [OAuth](https://oauth.net/2/)
- [Azure Tables](https://docs.microsoft.com/en-us/azure/)
- [Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction)