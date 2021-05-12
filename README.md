# ImageUploaderProject
A complete image uploader project implemented in Android for client side and nodejs for server side


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)

## General info
This projects contains 2 apps, a backend server-side app with APIs to upload image and retrieve all upload image on the server, and a client-side Android app that's used by the end user to upload and display images.

## Technologies
#### Backend app
* NodeJs
* Express
* Multer
#### Android app
* Java
* Retrofit
* Picasso

## Setup
This project is currently setup to run on localhost port 8080. And the Android app should run on emulator which is running on the same machine hosting the backend app. If you wish to change this setup to run it on your server please do the following changes :
#### Backend app
* Replace the baseUrl with your own server url in file.controller.js line 3
#### Android app
* Replace the BASE_URL with your own server url in ApiClient.java line 12

## Features
* Upload images from android phone to server
* Display all previously uploaded image in a list
* Swipe down to refresh the app

To-do list:
* Implement IOS app
* Implement frontend web app

## Status
Project is active and fully functional

