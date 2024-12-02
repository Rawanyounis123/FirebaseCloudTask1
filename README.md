# Firebase Channel Subscriptions 

This is a simple React application that allows users to subscribe or unsubscribe to different notification channels. 
The application uses Firebase Cloud Messaging (FCM) for handling push notifications and integrates the ability to manage notifications for topics such as News, Sports, and Weather.

---

## Features

### Enable Notifications: A button that requests the user's permission to receive notifications.
### Subscribe/Unsubscribe: Users can subscribe or unsubscribe to different notification channels.
### Subscribed Channels: Displays a list of channels the user is currently subscribed to.
### Firebase Cloud Messaging Integration: Sends and receives push notifications using Firebase Cloud Messaging.
---
## How It Works

### Requesting Permission: When the user clicks on the "Enable Notifications" button, the app requests permission to show notifications.
### Subscribing to Channels: Once permission is granted, users can subscribe to channels (News, Sports, Weather). Each channel has a Subscribe button.
### Unsubscribing from Channels: The user can unsubscribe from any subscribed channel using the Unsubscribe button next to each channel name.
### Notification Reception: When a notification is sent to a subscribed topic, the app displays it as an alert while the app is in the foreground.
---

![image](https://github.com/user-attachments/assets/162ed9e3-ae6c-4ae1-97ae-ace246459d89)
