# To run our App on an Android emulator


## Basic Setup

### Necessary Android development environment set up on your local machine to run the app on an emulator
Reference : https://reactnative.dev/docs/environment-setup
1. Install Android Studio
2. Install Java Development Kit (JDK)
3. Install Android SDK

### Steps after setup of Android development environment
1. Clone the App Repo & Backend Repo

App Repo Link: https://github.com/asingh88029/sollution_challenge_app

Backend Repo Link:https://github.com/asingh88029/sollution_challenge_backend

2. Open app & backend in the code editor.
3. Install packages in app & backend via using the command `npm i` or `npm install`
4. Start the **backend** using command `npm start`
5. To connect the backend with app change **Base_API_URL** in config.js     (**app->config.js**)  with the **IP address of your wifi/network** with which your system is connected.
6.  Connect your system with your mobile via cable.
7.  Start the **App** using command `npx react-native run-android`



## Features
- Chronic diseases detection by using **chatbot**
- Get any suggestion/remedies/disease suggestion/hospital suggestion/help related to healthcare by using **chatbot**
- Get Nearby **Hospitals (According to current location)**
- **Change the location** to get hospitals on other location
- Get **all information about any hospital** i.e speciality, no. of doctor, review & rating of patients etc.
- **Book the appointment** with your preffered doctor on your own slots.
- Reach to the hospital in just one via with the help of **Map**
  
  

### How to use ?
#### Having any doubt related to healthcare ?
Don't worry use our chatbot and get answer of any question with is realted to your health.

#### What if you don't have any idea about the hospitals?
Don't worry, Our App will provide you all the hospitals along the speciality & details along with patients review & rating according to your preffered location/current location

#### What if you are having a very busy schdule and want a appointment with doctor
Don't worry, Again through Our App you can book appointment in any hospital with any doctor on your available slots.


#### Having no idea, How to reach to the seleted hospital.
Simply Navigation to the selected hospital and use Map from Our App.
