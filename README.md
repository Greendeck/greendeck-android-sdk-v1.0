# Sample Android Application for Greendeck Integration

This repository contains a sample application demonstrating how you
can use Greendeck in your Android apps.

## Getting Started

The sample application can be build using either Android Studio.

### Using Android Studio
Integration in Android Studio is very simple.

- Clone this git repository (the instructions are at the top of the page)
- Within Android Studio, go to "File > Import Project"
- Select the directory you just cloned.
- When the gradle popup shows up, choose "use gradle default wrapper (recommended)" and click OK

You should now be able to run the sample application

## Add your Greendeck Project's CLIENT_ID and CLIENT_SECRET to the Source Code

There are two values in AppController.java that you'll need to update
before you can send data to Greendeck and receive prices for your products. You'll need to update the source code with
your Greendeck Project's Credentials to send data. You can find in your Dashboard. For any queries; drop a mail at developers@greendeck.co
