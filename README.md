# Welcome to NammaCable RN App 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Generate android prebuild ( Unistyles includes custom native code, which means it does not support Expo Go.)

   ```bash
   npx expo prebuild --clean
   ```

2. In gradle.properties add java home.

   ```bash
    org.gradle.java.home=C:\\Program Files\\Java\\jdk-17
   ```