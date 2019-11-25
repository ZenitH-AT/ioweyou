# I Owe U
ITSP300 group project

### **Required software for the development environment**
- Android Studio (for the SDK and AVD)
> You may also use your device with USB debugging turned on, or another emulator, such as Genymotion
- Node.js
- A code editor, such as Visual Studio Code

### **Setting up the app**
- Open Android Studio > Configure > AVD Manager and create a new virtual device
> Reccomended: Google Pixel 2 with Android 10
- Start the newly-created AVD
- Download the GitHub repository (project files)
- Open the project folder in your code editor
- Create the android/local.properties file with the following contents:
> Example (Windows): `sdk.dir=C\:\\Users\\your_user_folder_here\\AppData\\Local\\Android\\Sdk`
- Set up the config.json file with your own Firebase and SendGrid configuration
> Use these ![rules](http://batman.gyptis.org/zerobin/?b5953dffbc49810f#AWa1Avg7iYl1kUhrqHdu8c2rbfICMX39EFT/H9Z+/rI=) for your realtime database
- Open a terminal ("Ctrl + \`" in VS Code) and run the following commands:
> `npm install`
> `cd android`
> `./gradlew clean`
> `cd ..`
> `npm start`
> `npm run android`
