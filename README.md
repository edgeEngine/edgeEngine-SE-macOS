# edgeEngine-SE-macOS


#### 🚨 **Important NOTE:** 🚨
**This edgeEngine-SE-macOS repository has been archived and is no longer maintained.**  
Please visit our new repository [mimOE-SE-macOS](https://github.com/mimik-mimOE/mimOE-SE-macOS) for the latest updates.

---
edgeEngine for MacOS Platform

## Before you start  

 [explore the developer resources & documentation](https://developer.mimik.com)
 
 [sign up and create a mimik developer console account](https://developer.mimik.com/console/create_account)

## Installation Guide

1. Download latest release for MacOS [HERE](https://github.com/edgeEngine/edgeEngine-SE-macOS/releases)
2. Create a new directory
3. Move the release package to newly created directory 
4. Open terminal and navigate to the newly created directory that now has the downloaded .tar file
5. Untar package (ex:)
```
tar xvf edgeEngine-SE-macOS-developer-x86-v3.10.0.tar
```
For edgeEngine-SE-macOS-ARM
```
tar xvf edgeEngine-SE-macOS-developer-arm-v3.10.0.tar
```
6. Run start script to start edgeEngine
```
./start.sh
```
Expect a couple of macOS system security popups, the first time you run edge. Allow edge to run, then go to the Settings app (Privacy & Security) to unblock edge at the bottom of the section. Then run ./start.sh again. Allow to run, if prompted again.

7. Please visit [Developer Console](https://developer.mimik.com/console/create_account) to create an account and get started with your projects

## Notes:
- Do not close the terminal window where edgeEngine is running. Closing this window will terminate edgeEngine process
- To stop edgeEngine, simply close or use keyboard shortcut CTRL + C in terminal window where edgeEngine is running 
