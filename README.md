![header-ios](https://user-images.githubusercontent.com/24476344/43458226-0f1219b4-94e7-11e8-9b00-ca89b2da8952.png)

[![Version](https://img.shields.io/cocoapods/v/Kommunicate.svg?style=flat)](http://cocoapods.org/pods/Kommunicate)
[![License](https://img.shields.io/cocoapods/l/Kommunicate.svg?style=flat)](http://cocoapods.org/pods/Kommunicate)
[![Platform](https://img.shields.io/cocoapods/p/Kommunicate.svg?style=flat)](http://cocoapods.org/pods/Kommunicate)


## [Kommunicate](https://www.kommunicate.io/?utm_source=github&utm_medium=readme&utm_campaign=ios) iOS Chat SDK for Customer Support

An Open Source iOS Live Chat SDK for Customer Support

## Overview

Kommunicate provides open source live chat SDK in iOS. The Kommunicate SDK is flexible, lightweight and easily integrable. It lets you easily add real-time live chat and in-app messaging in your mobile applications and websites for customer support. The SDK is equipped with advance messaging options such as sending attachments, sharing location and rich messaging. 

![support-ios](https://user-images.githubusercontent.com/24476344/43457761-7d26b452-94e5-11e8-891d-ca765d589f30.gif)

Kommunicate SDK lets you integrate custom chatbots in your mobile apps for automating tasks. It comes with multiple features to make it a full-fledged customer support SDK. 

![bot-ios](https://user-images.githubusercontent.com/24476344/43457795-9e019cfa-94e5-11e8-8824-5d2cfd073a94.gif)

## Get Started

To get started with Kommunicate iOS SDK, head over to the Kommunicate website and [Signup](https://dashboard.kommunicate.io/signup?utm_source=github&utm_medium=readme&utm_campaign=ios) to get your Application ID.

## Dialogflow Chatbot Integration

Dialogflow is a Google-owned NLP platform to facilitate human-computer interactions such as chatbots, voice bots, etc. 

Kommunicate's Dialogflow integration provides a more versatile, customizable and better chatting experience. Kommunicate iOS Live Chat SDK supports all of Dialogflow's features such as Google Assistant, Rich Messaging, etc. On top of that, it is equipped with advanced features such as bot-human handoff, conversation managing dashboard, reporting, and others. 

You can connect your Dialogflow chatbot with Kommunicate in the following 4 simple steps. [Here](https://www.kommunicate.io/blog/building-ios-chatbot-with-dialogflow-api-ai/) is a step by step blog to add Kommunicate SDK in your iOS app. 

### Step 1: Get your API credentials from Dialogflow
- Login to Dialogflow console and select your agent from the dropdown in the left panel.
- Click on the settings button. It will open a setting page for the agent.
- Inside the general tab search for GOOGLE PROJECTS and click on your service account.
- After getting redirected to your SERVICE ACCOUNT, create a key in JSON format for your project from the actions section and it will get automatically downloaded.

### Step 2: Create a free Kommunicate account
Create a free account on [Kommunicate](https://dashboard.kommunicate.io/signup) and navigate to the [Bots section](https://dashboard.kommunicate.io/bots/bot-integrations).

### Step 3: Integrate your Dialogflow chatbot with Kommunicate
- In the Bot integrations section, choose Dialogflow. A popup window will open.
- Upload your Key file here and proceed.
- Give a name and image to your chatbot. It will be visible to the users chatting with your chatbot.
- Enable/Disable chatbot to human handoff. If enabled, it will automatically assign conversations to humans in case the chatbot is not able to answer.

### Step 4: Install the Kommunicate iOS SDK to your app
You can add the Kommunicate SDK in your iOS app easily. More information on how to integrate with your iOS app [here](https://docs.kommunicate.io/docs/ios-installation). 

> Note: Here's a [sample chatbot](https://docs.kommunicate.io/docs/bot-samples) for you to get started with Dialogflow. 


## Other Features

**Live chat widget:**  Make it easier for your visitors and users to reach you with an instant website and in-app support through chat. The widget is highly customizable. 

**Chatbots:** Automate and speed up your customer service by integrating AI-powered chatbots. Build your chatbots and deploy them using Kommunicate and seamlessly add them to the live chat.

**Conversations:** Manage all your customer queries coming from the live chat plugin. Easily manage and assign agents to cater to user conversations.

**Dashboard:** A powerful dashboard to see, analyze and act upon your customer conversation data. It helps you analyze the performance of support agents as well.

**Helpcenter:** Create your knowledge base and deploy on a dedicated page to cater to generic and recurring customer queries. Your customers will also be able to directly access FAQs in chat.

**Mailbox:** A simple and powerful team inbox for ticketing, managing, receiving and replying to all your customer support emails. 

**Integrations:** Easily move data between Kommunicate and your other favorite apps. Integrate your favorite CRM, knowledge base software and other apps.

**Conversation Routing:** Select routing rules for incoming conversations for both your agents and bots. Choose between automatic assignments or to notify all.

**Smart Rich Messaging:** Leverage rich messages using buttons, cards, carousels, forms or lists to provide an exquisite support chat experience to your customers.

**Quick Replies:** Quickly respond to generic user queries using Quick Replies. Easily create and manage templated messages from your dashboard.

------------------------

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

* iOS 9.0+
* Xcode 8.2+
* Swift 3.0+

## Installation

Kommunicate is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'Kommunicate'
```

Then run `pod install`.

In any file you'd like to use Kommunicate in, don't forget to
import the framework with `import Kommunicate`.

## Docs

Please check the [documentation](https://docs.kommunicate.io/docs/ios-authentication.html) for more details on installation, configuration, and customization.

## License

Kommunicate is available under the BSD-3-Clause license. See the [LICENSE](LICENSE) file for more info.

[img0]:https://raw.githubusercontent.com/Applozic/ApplozicSwift/master/Screenshots/screenshot0.png
[img1]:https://raw.githubusercontent.com/Applozic/ApplozicSwift/master/Screenshots/screenshot1.png
