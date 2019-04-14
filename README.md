# DoGood Mobile Application

Homeless people have harder time communicating with others. There is currently no easy-to-use, cheap, mobile solution to solve these problems. We hope our proves to be solution to this problem by bridging the gap between help seekers and helpers. Additionally, the product can send various information about nearby aiding camps and other aiding resources. Hence, they form an excellent platform for hosting such an application that addresses the communication problems between homeless and helpers. The application can be easily installed on any Android based phone. 

Our project’s backend is Node.js application running against MongoDB database. We are using mLab (https://mlab.com/) for database hosting. Our fronted uses Flutter framework. Flutter is Google’s mobile UI framework for crafting high-quality native interfaces. Learn more at https://flutter.io.

# Getting Started

  - Download and unzip our project.


### Prerequisites
  - [Install node.js](https://nodejs.org/en/download/)
  - Download the [Flutter SDK](https://flutter.dev/docs/development/tools/sdk/releases) for your platform and add flutter tool to your path
  - [Set up the Android Emulator](https://flutter.dev/docs/get-started/install/windows#android-setup)

## Running Backend
```sh 
$ cd dogood-backend
$ npm install (to install dependencies)
$ nodemon or node server.js
```

## Running Frontend

```sh
$ cd dogood-frontend/help_app
$ flutter doctor to find out any remaining dependencies you may need to install. 
$ flutter emulators (to list and start any available device emulators).
$ flutter emulators --launch <emulator id> (to run an emulator).
$ flutter run (to run our app on an attached device, run).
```
- You can find more information on managing emulators at the links below:
- https://developer.android.com/studio/run/managing-avds 
- https://developer.android.com/studio/command-line/avdmanager

## Deployment
* Our app is deployed to Heroku:
https://dogood-backend.herokuapp.com 
* [Download and install our app](https://drive.google.com/file/d/16cMSqz6_wZxRLOT6yZFAKKfDl2KOyaDX/view)

### Authors
- Raj Kumar Shahu
- Utsav Bir Singh Tuladhar
- Pushpa Raj Dulal

