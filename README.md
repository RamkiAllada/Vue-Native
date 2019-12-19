# Vue Native

Vue Native is a framework to build cross platform native mobile apps using JavaScript

## Installation

`Vue Native is a wrapper around the APIs of React Native. So, with Vue Native, you can do everything what you can do with React Native.`



### Installation Prerequisites

Since Vue Native is a wrapper around React Native, to use the CLI, you must have either expo-cli or react-native-cli installed globally.

To install Expo globally, use the following command:

```bash
$ npm install -g expo-cli
```

to use React Native CLI instead, use the following command to install it globally:
```bash
$ npm install -g react-native-cli
```
Once the prerequisites are installed we can proceed with installing vue.

Install vue native globally.

```bash
$ npm install --global vue-native-cli
```

### Usage
#### For React Native CLI users

Generate an app with the following command:
```bash
$ vue-native init <projectName> --no-expo
```

Once the project creation is success 
```bash
$ cd <projectName>
```
We can use react native commands directly.

```bash
react-native run-ios --simulator "<simulator name>" --port <port number>
```

We need to pass the port number in order to over come the port conflict issues.
