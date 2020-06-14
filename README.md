# UNICORN-HACK
SCDFxIBM Hackathon
Problem Statement 1

Scenario:
How might we help dispatchers retrieve vital personal infomation about casualties from bystanders who made the emergency call?
If the person requiring medical attention had created a profile containing the necessary personal information in advance using an SCDF ChatBot Service, bystanders can release these information to the dispatcher upon request.

We created a ChatBot using Watson Assistant 'SCDF Emergency Bot'

![ChatBotScreenshot](https://user-images.githubusercontent.com/66410682/84588399-aca46a00-ae59-11ea-8bf6-f31fb5f5c179.PNG)

[Disclaimer: We didn't manage to get the Telegram Bot or Facebook Messenger Integrated with the Watson Assistant, but we tried according to tutorials!]

**Method 1: Telegram Channel**
Resource: https://developer.ibm.com/tutorials/integrate-coversation-service-with-telegram-using-node-red/

Telegram Bot

![telegram](https://user-images.githubusercontent.com/66410682/84588831-1d995100-ae5d-11ea-9369-39068f2ff238.PNG)

Node RED Connection

  left to right: Command, Function, Assistant, Function, Sender
![node red](https://user-images.githubusercontent.com/66410682/84588700-58e75000-ae5c-11ea-8166-920218492a77.PNG)

**Method 2: Integrating Watson Assistant with Facebook Messenger**
Resource: https://www.youtube.com/watch?v=8o-FFU5sYNM&feature=youtu.be

Facebook Messenger

  ![Capturefb bot page](https://user-images.githubusercontent.com/66410682/84589469-3b68b500-ae61-11ea-8c7a-1b4fba0016e9.PNG)
