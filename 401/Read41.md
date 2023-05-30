# Read 41

# React Native

### Name three Core Components of React Native and describe what they do.

- Basic Components: Uses bascic components such as view, text, image, textinput, scrollview, and stylesheet.
- User Interface: Common user interface will render on any platform. Button and switch.
- List Views: Only renders elements that are currently showing on the screen. Flatlist and sectionlist.

### What problem does React Native solve (why call it native)?

- React Native uses native components to generate a user interface (UI). This makes the app feel and look like a regular native app, but also adds more flexibility. React Native provides a cost-effective and time-efficient solution for cross-platform mobile app development.

### What are the building blocks of a React Native app? How does that compare to a React app?

- Text and View are the two most basic building blocks of any React Native application. React is a JavaScript library of reusable components designed to create skeletons of the apps, whereas React Native is designed to build native mobile apps with reusable components.

### What solution does expo provide?

- The Expo managed workflow provides a shared native runtime so you don't write native code, you focus on writing your React app in JavaScript. You don't have to worry about Android or iOS specific settings, or even opening up Xcode.

### Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.

- Managed.

### What is the difference between React Native and Expo?

- Originally, Expo was designed to build products using strictly React Native code, with no support for native libraries like CocoaPods. This contrasted with the stock React Native CLI where you could include native libraries and interface with them. If you have a project requiring rapid development and have chosen React Native to build cross-platform applications, then Expo is for you. Through Expo, you can quickly develop and deploy React Native applications for iOS and Android.

### Checkout this tool. What does snack allow you to do?

- Change code in the editor and watch it change on your phone!

### What does “eject” mean within the context of Expo?

- Expo is a toolchain that allows you to quickly get a React Native app up and running without having to use native code in Xcode or Android Studio. The Expo Eject Step is necessary to eject your app to install any missing native dependencies.

### When should you not eject?

- You should only eject if you need to use a package that uses native code. If it's just JavaScript then you're fine. It is also non-reversible once you do it.

### Why might you choose to eject?

- Usually you would run eject when you want to override something in the configuration. For example if you want to use your copy-webpack-plugin. Or want to use custom aliases. Or any other plugin/function/tweak to your configurations.
