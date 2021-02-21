# PWA_budget_tracker

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Installation

The deployed app only requires online access to begin use. To save the app to an iOS device for use anytime once at the hosted address, https://a-pwa-budget-tracker.herokuapp.com/, the app can be saved as a standalone app in the device home screen by clicking the Share screen key and scrolling to `Add to Home Screen`.

![Mobile Installation](/assets/images/install_example.jpeg)

## Sample

A live sample of this app is deployed via Heroku and is linked to MongoAtlas to enable the online database functionality. Offline database is handled by IndexedDB. Visit the app at https://a-pwa-budget-tracker.herokuapp.com/

The app is accessible via mobile devices and retains functionality even when offline, such as when Airplane Mode is enabled. Data is saved via IndexedDB until a connection is available again and the database is checked and updated with the new entries.

![Mobile Device Examples](/assets/images/mobile_example.jpeg)

## License

This app and all its code are licensed under the MIT open source license.

## Contributing

Pull requests are welcome. For any changes, please open an issue first to discuss what you would like to change.

## Feedback & Contact

Github: https://github.com/hector-gm