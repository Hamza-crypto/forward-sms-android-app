# SMS Forwarder App

A Kotlin-based Android app that listens for incoming SMS messages and forwards them to a predefined email address. The app is designed to only trigger when an SMS is received, ensuring minimal battery usage.

## Features

- **Receive SMS**: Listens for incoming SMS messages in real-time.
- **Forward SMS to Email**: Automatically forwards the SMS content and sender information to a specified email address.
- **Battery Friendly**: The app only runs when an SMS is received and does not run persistently in the background.
  
## Tech Stack

- **Kotlin**: The primary programming language used for Android app development.
- **Android SDK**: For accessing SMS and email functionalities.
- **JavaMail API**: For sending emails programmatically.

## Prerequisites

To build and run this project, you will need:

- **Android Studio**: The official IDE for Android development.
- **Kotlin**: The programming language used.
- **JavaMail API**: Used to send emails.

## Permissions

The app requires the following Android permissions:

- **RECEIVE_SMS**: To listen for incoming SMS messages.
- **READ_SMS**: To read the received SMS content.
- **INTERNET**: To send the email with the SMS content.

## Installation

1. **Clone the Repository**:
   ```bash
   
