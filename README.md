# TheMakerShowBot
This bot helps you get started as a maker by recommending online resources about project ideas, where to buy hardware boards, sensors and other parts, and more. This bot also recommends specific episodes of The Maker Show to watch based on your interests.

The bot is built in C# with [Visual Studio 2015](http://www.visualstudio.com) and [ASP.NET Web API](http://www.asp.net/web-api) using the open source [Bot Builder SDK](https://github.com/Microsoft/BotBuilder). The natural language queries are processed via the [Natural Language Intelligent Service (LUIS)](https://www.microsoft.com/cognitive-services/en-us/language-understanding-intelligent-service-luis) from [Microsoft Cognitive Services](http://microsoft.com/cognitive). For more information about building bots, see the [Microsoft Bot Framework Developer Portal](https://dev.botframework.com/).

## Features
The bot supports a few intents, queryable via natural language, such as:
- Learn a Topic: e.g. How can I get started with Arduino?
- Buy Hardware: e.g. Where can I buy a Raspberry Pi?
- Compare: What is the difference between a Particle Photon and an ESP8266?
- Who is: e.g. Who is Bret Stateham?
- Greeting: e.g. Hi there!
- Help: e.g. What can I say?
- Complain: e.g. That's not what I asked for!
- ThankYou: e.g. Thanks, that was helpful!
- None: Default catch-all that all LUIS model must include for all cases where users feed in unexpected input

## Implementation Notes
- The live version of this bot is hosted in Azure App Services at http://themakershowbot.azurewebsites.net.
- The bot is already live (though not yet visibly published) via Facebook Messenger and Skype.
- I also created a holographic app in Unity for the [Microsoft HoloLens](http://hololens.com) that can talk with this bot: [HoloBot](https://github.com/ActiveNick/HoloBot).
- The 'Compare' intent is only partially implemented since it returns the same canned answer. This was implemented during a live presentation and I need to add the bot logic to provide comparison data.

Watch The Maker Show online on [Channel 9](https://channel9.msdn.com/) at [http://themakershow.io](http://themakershow.io).

## Screenshots
The following is a sample conversation with The Maker Show bot in Facebook Messenger on Android:
![Screenshot](Screenshots/TMSBot-FBMessengerAndroid01.png)

## Follow Me
* Twitter: [@ActiveNick](http://twitter.com/ActiveNick)
* Blog: [AgeofMobility.com](http://AgeofMobility.com)
* SlideShare: [http://www.slideshare.net/ActiveNick](http://www.slideshare.net/ActiveNick)
