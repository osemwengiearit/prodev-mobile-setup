MOBILE DEVELOPMENT SETUP USING EXPO CLI
react native full installation
Expo CLI (npm install -g expo-cli)

Create a New Expo Project
Run the following command to create a new Expo project with TypeScript: 

npx create-expo-app MyApp

npx expo start

cd MyApp
- npm run android
- npm run ios # you need to use macOS to build the iOS project - use the Expo app if you need to do iOS development without a Mac
- npm run web

3. Run Your App
Start the development server: npx expo start Scan the QR code with the Expo Go app on your phone, or open the app in an emulator.



 
 
 
  Commands:

    init [name]                       Create a new Expo project
    start [path]                      Start a local dev server for the app
    start:web [path]                  Start a Webpack dev server for the web app
    export [path]                     Export the static files of the app for hosting it on a web server
    install [packages...]             Install a module or other package to a project
    run:android [path]                Run the Android app binary locally
    run:ios [path]                    Run the iOS app binary locally
    send [path]                       Share the project's URL to an email address

    login                             Login to an Expo account
    logout                            Logout of an Expo account
    register                          Sign up for a new Expo account
    whoami                            Return the currently authenticated account

    client:install:ios                Install Expo Go for iOS on the simulator
    client:install:android            Install Expo Go for Android on a connected device or emulator

    config [path]                     Show the project config
    doctor [path]                     Diagnose issues with the project
    upgrade [sdk-version]             Upgrade the project packages and config for the given SDK version

    customize:web [path]              Eject the default web files for customization
    prebuild [path]                   Create native iOS and Android project files before building natively.      
                                      Learn more: https://docs.expo.dev/workflow/customizing/

    build:web [path]                  Build the web app for production

    credentials:manager [path]        Superseded by eas credentials in eas-cli

    url [path]                        Log a URL for opening the project in Expo Go
    url:ipa [path]                    Log the download URL for the standalone iOS binary
    url:apk [path]                    Log the download URL for the standalone Android binary

    webhooks [path]                   List all webhooks for a project
    webhooks:add [path]               Add a webhook to a project
    webhooks:remove [path]            Delete a webhook
    webhooks:update [path]            Update an existing webhook

    build:ios [path]                  Superseded by eas build in eas-cli
    build:android [path]              Superseded by eas build in eas-cli
    build:status [path]               Superseded by eas build:list in eas-cli
    eject [path]                      Superseded by expo prebuild
    fetch:ios:certs [path]            Superseded by eas credentials in eas-cli
    fetch:android:keystore [path]     Superseded by eas credentials in eas-cli
    fetch:android:hashes [path]       Superseded by eas credentials in eas-cli
    fetch:android:upload-cert [path]  Superseded by eas credentials in eas-cli
    publish [path]                    Superseded by eas update in eas-cli
    publish:set [path]                Superseded by eas update:republish in eas-cli
    publish:rollback [path]           Superseded by eas update:republish in eas-cli
    publish:details [path]            Superseded by eas update:view in eas-cli
    push:android:upload [path]        Superseded by eas credentials in eas-cli
    push:android:show [path]          Superseded by eas credentials in eas-cli
    push:android:clear [path]         Superseded by eas credentials in eas-cli
    upload:android [path]             Superseded by eas submit in eas-cli
    upload:ios [path]                 Superseded by eas submit in eas-cli
    client:ios [path]                 Superseded by Expo Dev Clients

  Run a command with --help for more info




  Objective
Mobile development demands more computational resources compared to web development. To ensure a smooth development experience, we will be using the Expo Framework for React Native, which simplifies mobile app development and testing.

To successfully complete this task, ensure you have the following:

Node.js LTS installed
VS Code (our recommended IDE)
macOS, Linux, or Windows
Expo Go installed on your physical device (Android or iOS)
These tools are essential for completing the upcoming projects efficiently.

Instructions
By now, you should already have Node.js LTS, VS Code, and a compatible operating system installed. This task focuses on setting up Expo Go on your physical device.

Why Expo Go?
Unlike web development, mobile development relies on device emulators to test applications. However, keeping up with the ever-evolving mobile ecosystem (e.g., iPhone 7 → iPhone 16 Pro Max, various Android devices) can be costly in terms of hardware requirements.

Expo Go provides a cost-effective solution by allowing you to test and run your React Native applications directly on your physical device, supporting both iOS and Android seamlessly.

Steps to Install Expo Go
Visit the official Expo Go homepage: https://expo.dev/go.
Select the latest SDK version.
Click on Install for your device:
Android: Install from the Google Play Store.
iOS: Install from the Apple App Store.
Open the Expo Go app on your device.
Create a new account or log in if you already have one.
Document your setup process and any challenges faced in the README.md file. This will help you track your progress and troubleshoot any issues that arise during development.