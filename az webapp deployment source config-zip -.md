az webapp deployment source config-zip --resource-group QABot --name qabotapp-bot-53aa --src ./Restaurant-Chatbot-With-Azure.zip

az resource list --resource-group QABot --output table
