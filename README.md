# 🦌Enma's Streamer.Bot Plugin for Touch Portal [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/enmadarei)

Seamlessly integrate Streamer.Bot with Touch Portal for **unmatched control** and **efficiency** in your streams! With **real-time updates** and **Rust-powered performance**, this plugin allows you to trigger Streamer.Bot actions through Touch Portal, and trigger Touch Portal actions when certain events are detected by Streamer.Bot! Perfect for streamers who want ultimate control and efficiency! [**[Download]**](https://github.com/EnmaDarei/tp_streamerbot_plugin/releases/latest)

## 🚀 Features

### 🔄️Action Flexibility

- **Run Actions Your Way**: Choose your actions from a list or directly type their names or IDs.
- **Custom Arguments**: Include any arbitrary arguments you want when you trigger actions.

> [!TIP]
> Since this plugin allows you to pass whatever arguments you want, the limit is your imagination (or C# coding skills)! 😉

![image](https://github.com/user-attachments/assets/461ca6a8-4da0-4364-a753-c19520f5a223)

### ⚡Dynamic Functionality

- **Real-Time Action List Updates**: The action list refreshes instantly when you add/remove/update actions on Streamer.Bot
- **Stored Information**: Access real-time information about recent events and states and use them for your buttons or as triggers.
![image](https://github.com/user-attachments/assets/4f23f0cf-b3ac-4c5a-869a-448352a88741)
![image](https://github.com/user-attachments/assets/9eb3a468-1e75-42e3-8c19-17f6d1bbd812)

### 🌐 Effortless Connectivity

- **Auto Reconnect**: No more worries about dropped connections—the plugin automatically retries connecting to Streamer.Bot, keeping your stream seamlessly active.

### 🏎 Optimized Performance

The latest version of the plugin has been entirely rewritten in Rust, significantly reducing memory usage and boosting performance.

## 🛠 Quick Start

Getting started is a breeze! Just follow these steps to unlock enhanced control for your streams:

1. [**Download the latest version of the plugin**](https://github.com/EnmaDarei/tp_streamerbot_plugin/releases/latest)
2. Install in Touch Portal
3. Configure Streamer.Bot connection settings
4. Start streaming with newfound control and efficiency!
![image](https://github.com/user-attachments/assets/894ea9a6-6eab-46a4-a7ec-24c6577f500b)

## 📊 Stored States

### Plugin

- Connection Status
- Number of actions in Streamer.bot

### Twitch

- Last Chatter: Displayname
- Last Chatter: Username
- Last Chatter: Message
- Last Sub: User
- Last Sub: Sub Tier
- Last Re-Sub: User
- Last Re-Sub: Current Streak
- Last Re-Sub: Total Months
- Last Re-Sub: Sub Tier
- Hype Train Information
- Poll Status
- Poll Title & Options
- Poll ID
- Prediction Status
- Prediction Title & Outcomes
- Prediction ID

> [!NOTE]
> Since v2.2.7 the plugin doesn't store information about latest follower since Touch Portal does that natively

### YouTube

- Last Chatter: Username
- Last Chatter: Message

### Donations/Tips (StreamElements & Streamlabs)

- User
- Amount

> [!NOTE]
> Both platforms get stored to the same state under the assumption that most people only use one or the other.

## 🎉 Available Events

Stay reactive with these customizable events, ensuring you're always ready for what's next in your stream!

- Hype Train Active
- Hype Train Level
- Poll Active
- Prediction Active
- Plugin Connected
  
![image](https://github.com/user-attachments/assets/4f23f0cf-b3ac-4c5a-869a-448352a88741)

## 💡 Why Choose This Plugin Instead of the Other One?

- **More Stored States & Events**: Track more detailed information for Twitch, YouTube, and donation platforms.
- **Streamlined and efficient**: Rewritten in Rust for a smaller memory footprint and faster execution.
- **Continuous Updates**: Built around real user feedback—because it’s the tool I use for my own streams!

### Your feedback and ideas are always welcome!

## ☕ Support the Project

If you find this plugin helpful, consider [buying me a coffee](https://ko-fi.com/enmadarei)! Your support helps keep the updates coming and makes this plugin even better for everyone. Thank you! 💖
