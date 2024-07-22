<p align="center">
    <a href="https://docs.icure.com">
        <img alt="icure-your-data-platform-for-medtech-and-ehr" src="https://icure.com/assets/icons/logo.svg">
    </a>
    <h1 align="center">iCure MedTech React Native Expo Template</h1>
</p>

Start working on your e-health React Native Expo app with iCure in a few minutes, by using our dedicated React Native Expo template:
```
npx create-expo-app my-new-app --template https://github.com/icure/icure-medical-device-react-native-expo-boilerplate-app-template
```

Rename the following folder and files in the root directory:

- `dot.yarn` -> `.yarn`
- `dot.buckconfig` -> `.buckconfig`
- `dot.editorconfig` -> `.editorconfig`
- `dot.env` -> `.env`
- `dot.eslintrc` -> `.eslintrc`
- `dot.node-version` -> `.node-version`
- `dot.prettierrc` -> `.prettierrc`
- `dot.ruby-version` -> `.ruby-version`
- `dot.watchmanconfig` -> `.watchmanconfig`
- `dot.yarnrc.yml` -> `.yarnrc.yml`

Once your app is created, complete the following values in the file `.env`:
- **EXPO_PUBLIC_PARENT_ORGANISATION_ID**
- **EXPO_PUBLIC_EXTERNAL_SERVICES_SPEC_ID**
- **EXPO_PUBLIC_FRIENDLY_CAPTCHA_SITE_KEY**
- **EXPO_PUBLIC_EMAIL_AUTHENTICATION_PROCESS_ID** and/or **EXPO_PUBLIC_SMS_AUTHENTICATION_PROCESS_ID**,

Check out our [Quick Start](https://docs.icure.com/sdks/quick-start/) in order to know what are those information and how to get them from our [Cockpit Portal](https://cockpit.icure.cloud/).

*WARNING: Without these information, you won't be able to complete an authentication*

## Requirements
Make sure the following tools are installed on your machine:
- **Yarn Package manager**
- **Ruby**, same version than referenced in the `.ruby-version` file at the root of the template.
- **XCode**
- **Android Studio**

*Note: XCode and Android Studio are needed in order to run your app on iPhone & Android emulators*

## How to start the project ?
Follow these steps to get your project up and running:

1. Open your terminal or command prompt.
2. Run the following command:

    ```
    npx expo
    ```
3. A list of platforms will appear. Select the platform you'd like to run the application on (e.g., iOS, Android, or web).

That's it! Your project should now be starting on your chosen platform.


## Which technologies are used ?
This React Native Template is based on the same technologies as our [Petra example app](https://github.com/icure/icure-medical-device-react-native-app-tutorial). Meaning this template includes the use of:
- [Typescript](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html), as a language
- [Redux](https://redux.js.org/introduction/getting-started), as a state container
- [MMKV](https://github.com/Tencent/MMKV), as a key-value storage
- [FriendlyCaptcha](https://friendlycaptcha.com/), as a CAPTCHA solution

We chosed this set of technologies, because we consider them as the most efficient ones to work with.
Nonetheless, you can of course work with the technologies of your choices and still integrate the iCure MedTech Typescript SDK in your React Native app.

## What includes this template ?
All the needed dependencies to work with iCure in a React Native Expo app, including:
- the [iCure MedTech Typescript SDK](https://github.com/icure/icure-medical-device-js-sdk)
- the [iCure Expo-Kryptom](https://github.com/icure/expo-kryptom) libraries

This template also includes the implementation of the [iCure authentication flow](https://docs.icure.com/sdks/how-to/how-to-authenticate-a-user/how-to-authenticate-a-user) (Both registration and login).

## What's next ?
Check out our [MedTech Documentation](https://docs.icure.com/sdks/quick-start/react-native-quick-start) and more particularly our [How To's](https://docs.icure.com/sdks/how-to/index), in order to start implementing new functionalities inside your React Native App ! 
