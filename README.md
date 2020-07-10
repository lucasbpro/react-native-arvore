# React-Native Árvore

This repository currently contains the mobile application developed by "Time 53" in the Mega Hack 3.0 from Shawee. The team developed a solution for [Árvore Educação](https://arvoreeducacao.com.br/) with the aim to boost the interest of brazilian teens in reading. This repo has been copied from https://github.com/otaviopetry/arvore-53, the original repository from @otaviopetry in which I contributed with just a bit of code. 

In this repo I intend to implement more functionalities, do code refactoring and work on styles just for learning sake.

## How to run the backend application

You need to have **[Node v13.8.0](https://nodejs.org/en/)** (or later) installed in your machine.

First, open the *backend* directory in a terminal and install all the dependencies:
```bash
$ npm install
```
Then, start the development server:
```bash
$ npm start
```
Server will start at http://localhost:3000.

## How to run the mobile application

You need to have **[Node v13.8.0](https://nodejs.org/en/)** (or later) installed in your machine.

Open the *mobile* directory in a terminal and install all the dependencies:
```bash
$ npm install
```

The application can be run with *react-native* or by using the [explo-cli](https://expo.io/learn). If you have the explo-cli installed, just type the command below in the terminal/bash window:
```bash
$ expo start
```
This will generate a QR-code in your terminal. Then you will be able to open the expo app in your cellphone device (you need to download it from Play Store or Apple Store) and use the QR-code scanner to
run the application on your cellphone. You can also access the application via yur desktop browser in  

If you prefer running *react-native* and you are in a MAC, you will need to type: 
```bash
$ react-native run-ios
```
If you are not in a MAC, open a android device emulator by using *AVD Manager* from  [Android Studio](https://developer.android.com/studio/?gclid=Cj0KCQjwo6D4BRDgARIsAA6uN19j1nhmNn7gamscdvoMooDSMffWn91S2Ue772Uw0gobEOGX2_mfeL8aAivXEALw_wcB&gclsrc=aw.ds) and type on the terminal/bash:
```bash
$ react-native run-android
```
