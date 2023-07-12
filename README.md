# 🥷 ReactNative101
## 📈 React Native 101: A Beginner's Guide to Building Cross-Platform Apps

####  Welcome to React Native 101, your comprehensive guide to getting started with React Native development! This repository serves as a beginner-friendly resource for those interested in building powerful cross-platform mobile applications using React Native.

#### In this guide, we'll cover the fundamentals of React Native, including setting up your development environment, understanding the core concepts of React Native, and building your first React Native app from scratch. Whether you're a seasoned JavaScript developer or new to mobile development, this repo will provide you with a solid foundation to start building robust, native-like apps for iOS and Android.

## General Files Installation 
## 1) NodeJS : It is the root of any React projects, so make sure you should have installed it in your system.
   Recommended : use LTS version for better support.
   ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/c8315c34-0c0e-4ff0-acba-f6681d148f64)

## 2) OpenJDK / JDK : React Native have some dependencies which also includes Java Development kit (JDK).
  ### Recommended JDK version /OpenJDK : ``` 11 ```  ( as per the ReactNative docs )
  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/d71e62d7-c340-4f8b-b216-bd77945c6d35)

  ## Note : Java JDK version and gradle version should match ! ( what is gradle ? will see further)
  Here you can check the version compatibility : https://docs.gradle.org/current/userguide/compatibility.html

## 3) Android Studio : Without Android Studio , your app will not run on the system. 
Link: https://developer.android.com/studio
![image](https://github.com/yash-devop/ReactNative101/assets/112558970/34688587-a1af-4a45-b115-cb2b7b10c76e)

### You may be wondering if there will be any impact on the speed or responsiveness of your system.
Answer is NO ! , we are not going to open Android studio for ReactNative, we will be doing all the programming related to React Native inside our Vscode.

Do this Steps : 
## This will be the First Screen you will get , just hit  ``` more actions ```  and select ```SDK manager```
![image](https://github.com/yash-devop/ReactNative101/assets/112558970/5f6ed75f-599a-471e-b58c-7178f3c6b1b6)
  
  ### a) SDK Manager: 
  Inside the SDK Platforms tab , Make sure that Android SDK Platform 34 , Android SDK Platform 33, Google APIs intel x86_64 Atom System image or intel x86_64 Atom System image is selected.
  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/d554c755-f788-4de1-983b-6403c9450770)


  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/3b39df2d-255c-4ea7-9d57-0a4549212f16)

  Go to ``` SDK Tools ``` and select the versions : ``` 33.0.0 ``` , ```33.0.2 ``` , ``` 30.0.3 ```
  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/77860840-1726-491e-9d6c-38438aac88c4)

  ### b) Virtual Device Manager : 
  Now , there will be 2 preferences : Either you want to use directly the app inside your computer ( using Virtual Device Emulator ) or by attaching the 
  Smartphone( android or IOS ) to the System.

  #### Steps : 
  1) Click ```Create Virtual Device```
  2) Select any device accordingly and hit apply. 
     ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/84a298d4-9ec8-4b36-a0cc-65e3481bc669)

  ##                                           OR

  ## Using your smartphone :
  
  Enable USB Debugging :
  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/e8ccbf88-fdfc-4a01-b3d1-4281e73a099c)
  
  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/04bb6e15-308d-4325-986a-8b4f71041b62)

  ## Environment Variables ( DO IT CAREFULLY )
  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/19b9cada-4c3a-466c-abbb-e88b3330f073)

  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/98bc5d6c-29b6-406a-ac1d-799b5fc98b1c)

  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/9ee487b8-0e80-418e-a7b1-6beeb74bf1f9)
  
  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/8150b7b3-e136-4116-b27f-145241b67813)

  ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/0339e1b7-598e-4276-8135-7b0f098dabda)


  ### YAY ! Done with the Setup .

  # Installation of React Native

1) Type this Command on your Command prompt (cmd) or in Vscode Terminal but before that create a folder where you want to create React native apps.
   
   ```js
      npx react-native init <yourProjectName>    // dont include <> this brackets.
   ```
   
2) Install React Native Doctor : This will help you to find and fix the issues related to installation and checking the dependencies.
   
   ``` npx @react-native-community/cli doctor ```

3) To run the React Native Application , simply type : ``` cd <yourProjectName> ```
   then run this command : 
  ``` npx react-native run-android  ```

   So , it will build some of its files before actually deploying the app to your smartphone.
   Once everything is done , it will look like :
   
   ![image](https://github.com/yash-devop/ReactNative101/assets/112558970/2f789b83-0311-4076-9dc5-7eedf3408489)
