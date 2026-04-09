# OTP Bot

Bypass SMS verifications from Paypal, Instagram, Snapchat, Google, 3D Secure, and many others... using a Discord Bot or the private API.
It's really simple. Imagine that your friend got a Snapchat account, you try to reset his password using the sms system :
he's gonna receive the sms confirmation code.
Then, you use the bot (!call 33612345678 snapchat). The bot is gonna call him, using the snapchat service, ask for the code received. If he send the code using the numpad, then your gonna receive the code and be able to reset the password.

## How to Compile

1. Open the solution file (.sln).
2. Select **Build Solution** from the **Build** menu or press `Ctrl+Shift+B` to compile the project.

- Ready to Install the Bot

## How To Use?

- When you do a !call (3312345678) Citibank, the OTPBYPASS Bot sends a post request to the api, which will save the call into a sqlite DB and send the call to the custom twilio API.
- The Twilio API use our /status route to know what to do in the call, the status route returns TwiML code to Twilio.
- The /status route returns the self hosted service song using the /stream/service route.
- If the user enter the digit code using the numpad, the song stops, it thanks him for the code, and end the call.
- The /status route send the code to your discord channel using a webhook.

## Question&Answer

<details>
<summary>What is Call Spoof</summary>
Spoof CallerID
With RCSOTP you get the ability to change what someone sees on their Caller ID display when they receive a phone call from you using RCSOTP bot
  </details>

 <details>
<summary>In Which Countries Does It Work?</summary>
* North Africa
* Sub-Saharan Africa
* Antarctic
* Europe
* Caribbean Islands
* North, Central, South America
* Oceania
* East, North, South, West, Central & Southest Asia
  </details>

<details>
<summary>What can i do with it?</summary>
The bots that enable attackers to extract one-time passwords from consumers without human-intervention are commonly known as OTP bots. Attackers use these programmed bots to call up unsuspecting consumers and trick them into divulging their two-factor authentication codes. They then use these codes to authenticate and complete unauthorized transactions from compromised accounts.
  </details>

## Features

- **Paypal**
- **Google**
- **Snapchat**
- **Instagram**
- **Facebook**
- **Whatsapp**
- **Twitter**
- **Amazon**
- **Cdiscount**
- **Default : work for all the systems**
- **Banque : bypass 3D Secure**
- **Custom Caller ID (can spoof any company/bank)**
- **Unique text-to-speech api**
- **Human like voice**
- **Multiple modes**
- **Multiple countries supported**
- **Custom Caller ID (can use any company or bank)**
- **Unique text-to-speech for each call**
- **Human like voice**
- **Multiple modes to choose from**
- **Multiple languages supported**
- **Multiple countries supported**

### OTP Photos

![OTP](https://user-images.githubusercontent.com/116966987/198891700-1b6871eb-56c3-4e58-8ef2-53b9761f3874.png)

![OTP BOT](https://user-images.githubusercontent.com/116966987/198891636-93812890-82c8-4e5e-8941-e2f80f2d7a5d.gif)

## Disclaimer

This source code is for educational purposes only.

## License

This project is licensed under the MIT. For more information, see the [License](LICENSE).
