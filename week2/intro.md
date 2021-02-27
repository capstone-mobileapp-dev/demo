## React Native

- A framework for building native apps for iOS and Android using **JavaScript**.

### Apps built with React Native

        Facebook
        Instagram
        Pinterest
        Skype
        Uber Eats

## Two ways to build apps with React Native.

- **Expo CLI**
  - Simpler way to create mobile projects for beginers
- **React Native CLI**
  - More advanced version for experience mobile developers

## Setting up the Development Environment

1.  Be sure you are using node version 12 or higher

2.  ### Installing Expo CLI globally
    #### Mac OSX

- `sudo npm i -g expo-cli`
  #### Windowns OS
- `npm i -g expo-cli`

3.  Download **Expo Client** or **Expo Go** from App Store or Google Play Store
4.  Download and install vscode

    - **vscode extentions**
      - React Native Tools
      - React-Native/React/Redux Snipets
      - Prettier - Code Formatter
      - Material Icon Theme
    - Enable formatonsave in vscode settings

# Creating Your First Expo Project

run `expo init projectName` , then select blank

### Project Achitecture

- _assets_ - where static files are (images and videos)
- _App.js_ - Componenent

## Starting Expo Server to Serve our app

`npm start`

- If you get an error on mac , run `brew update` then run `brew install watchan`

##### Metro Bundler

- responsible for compiling all the javasript files into a single file
