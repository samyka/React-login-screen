# React Native Starter Kit 🚀

Bootstrap your app development by using this awesome react native starter kit, integrated with Firebase Auth and Facebook Login. Clone this boilerplate app to get you up and running quickly.

## Fully working features

- Login with Facebook
- User Management with Firebase Auth
- Firebase Firestore Integration
- Email/Password Registration
- Persistent Login Credentials (a.k.a Remember password)
- Logout Functionality
- Beautiful UI and transitions

## App Designs

<div align="center">
    <img src="https://github.com/samyka/react-native-login-screen/blob/master/ScreenShot/react-native1.png" width="200px"</img>
    <img src="https://github.com/samyka/react-native-login-screen/blob/master/ScreenShot/react-native2.png" width="200px"</img>
    <img src="https://github.com/samyka/react-native-login-screen/blob/master/ScreenShot/react-native3.png" width="200px"</img>
    <img src="https://github.com/samyka/react-native-login-screen/blob/master/ScreenShot/react-native.png" width="200px"</img>
   
</div>

## Google signin

- when signing in with google on android and you get "developer_error google sign in".
- take the following steps:

      	* in the command line, enter:
      		keytool -exportcert -list -v -alias androiddebugkey -keystore ~/.android/debug.keystore

      	*  when prompted for password, enter:
      		android

      	* you should successfully generate some keys.
      	* copy the "SHA1:" key
      	* visit firestore console in your browser
      	* under settings>>Project settings select "RN Starter Kit Android"
      	* click "add fingerprint"
      	* paste the copied "SHA1:" key

      	* then rebuild app
# React-login-screen
