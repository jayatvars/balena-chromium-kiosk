# BalenaOS/BalenaCloud RaspberryPi Chromium Kiosk
This is a simple kiosk for loading a web site in Chromium running on a Raspberry PI using BalenaOS/Balena Cloud. 
## Original Source
The project was originally a fork from the [resin-electronjs](https://github.com/balena-io/resin-electronjs) template. 
## Updates
Updated from the original fork to use Chromium and the latest Balena Libs. The template will load the necessary packages and initialize [systemd](https://github.com/balena-io-playground/balenalib-systemd-example) which is required for local device input to the app container. The chromium user is created, given appropriate permissions and Chromium is launched. 
## Hardware
Tested on Raspberry Pi 3b and 3b+. Input from local device touch screen, keyboard and a USB wedge scanner has been tested. Use at your own risk.
## Getting Started
[What is Balena](https://www.balena.io/what-is-balena/)
## Environment Variables
Create an enviroment variable in your Balena app named URL_LAUNCHER_URL and assign it your web accessible URL. The Chromium start page loads by default.
### Disclaimer
No expert claims here. ;) I am sure there are better ways to put this together. But this solution works for us and meets our needs.
