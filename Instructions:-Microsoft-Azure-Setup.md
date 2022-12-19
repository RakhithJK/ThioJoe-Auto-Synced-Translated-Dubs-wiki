# Azure
Using Microsoft's Azure Text to Speech service allows you to use  more advanced features and higher quality voices, so I currently recommend it over Google Cloud's TTS.

## Steps:
1. Create an Azure 'subscription' (basically just an account). Doing so is free, despite the name: [Sign Up Page](https://azure.microsoft.com/free/cognitive-services)
2. [Create a Speech resource](https://portal.azure.com/#create/Microsoft.CognitiveServicesSpeechServices) in the Azure portal.
3. Get the resource key and region. After your Speech resource is deployed, select "Go to Resource" to view and manage keys. 
   - The resource region and API key will go into the `cloud_service_settings.ini` config file
   - For more information about Cognitive Services resources, see [Get the keys for your resource](https://learn.microsoft.com/en-us/azure/cognitive-services/cognitive-services-apis-create-account#get-the-keys-for-your-resource).