# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```


# Coding Scenario - React Native Expo
### You have about 30 mins to go through the below tasks. 

## Setup
Setup: Create two additional folders – one named components and another called pages. You may add additional folders if necessary. Setup a page called Home, that will be loaded up when you first start the application.

## 1.	State: In the Home screen, render the text 

```bash
Hello World - Press me to toggle
```
	a. When pressed, the text should toggle between CAPITALISED and lower case. This functionality will only be used on this screen.


## 2. Resusable Components:  
### Build a very simple reusable container component, that will resize based off the width of the screen. 
### Place this container into the page created
	a.	Full screen should take up 75% window space; mobile should take up 100% space.
	The container should also have 14px vertical and horizontal padding when resized to mobile width
	b.	The container should allow children to be rendered inside of it.
	c.	This container can be bordered, or not bordered, depending on the property passed into it.

## 3. Functions/Hooks: Create a text button inside of this container that will do the following:
	a. when pressed, will grab the user’s Platform information (“iOS, Android, or Web”)
	b.	return this in a console log to the user. 
	c.	Note: This function may be used in multiple places in the app.
	d. Name the Text/Button "Get Platform Details
