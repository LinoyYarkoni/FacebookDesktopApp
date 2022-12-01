# Facebook Desktop App Using Winforms GUI

### The app is a WinForms .NET Facebook application using Facebook API.

## TECHSTACK:
* Multi-Threading
* Data Binding
* Delegates
* Serialization

# Design Patterns, based on the book The Gang Of Four, such as:
* Singleton
* Factory Method
* Adapter
* Proxy
* Strategy
* Iterator
* Observer

## Features Description:
1. Virtual Pet - The user can choose a virtual pet from a collection of pets, change its name and feed it.

2. Timer - The user can see and get alerted by the application for the time he uses the application.
The user can also set a timer for the requested time of using the application

## Usage:
* Create an application account on https://developers.facebook.com/apps to get an App ID.
* In Visual Studio add a reference to the .dll files (FbGraphApiWrapper.dll, Facebook.dll).
* Use the static login method:
`LoginResult = FacebookWrapper.FacebookService.Login(AppID, list of permission);` \n
providing your AppID and the permissions required from your app's user to display a login form to your user. For the list of permissions, see this https://developers.facebook.com/docs/facebook-login/permissions.

## Resources:
* Visit https://developers.facebook.com/docs/reference/api/ to understand more and get all the information about the Facebook Graph API.
* Use the https://developers.facebook.com/tools/explorer application to browse data on Facebook using the Graph API and understand Jason.

![mainpic(1)](https://user-images.githubusercontent.com/85076725/183270081-065c9d54-68af-4bd3-b0e1-c9a08cae76ce.jpg)

![image](https://user-images.githubusercontent.com/85076725/183270032-e338a64f-f582-4ed6-aa03-72709428146e.png)

![menupic](https://user-images.githubusercontent.com/85076725/183270196-7af0775c-64a4-48ab-937b-e8241f4bc936.JPG)
