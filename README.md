# Purpose
Control your LIFX smart lights through a simple webpage; solve the issue of managing lights from a desktop computers where no apps are available/require multiple clicks.

# Pre-requisites
1. Use LIFX lights connected to the internet: https://www.lifx.com/collections/all
2. Generate a LIFX personal token to log in to your account at: https://cloud.lifx.com/access_tokens. Your authentication token will be saved in your local browser cache.

# Setup
Nothing to setup or install! Just navigate to the home page, enter your personal key and all your lights will appear.

# Usage
The app allows you to turn on/off connected lights, change their colour and brightness level. If a device is turned off at the light switch level (or doesn't have access to the internet), the light will be marked offline
There are 2 tabs: Rooms and All lights.

* Rooms show the lights grouped by rooms setup in your app. You can control lights individually or a whole room at a time
* All lights simply display all the lights with the same individual features

# Troubleshooting

* if you cannot control your lights through this interface, validate that you can do it from the official apps first to confirm they are operating normally.
* Check the status of the LIFX API; if there are any outage listed here: http://status.lifx.com/ this interface won't work.
* Can't login: you may need to (re-) create a personal access token at: https://cloud.lifx.com/access_tokens. Note that you should store the token separately as it won't be visible once you've saved it in the LIFX account page. Do not share your token with other people.
* I've successfully managed to control my lights from my laptop, but I need to login again on my other computer. This is normal as the authentication is stored on the local computer and not shared or stored on any server. You'll have to re-enter your personal access token.
* I managed to control my lights from my personal computer, but it fails when logging in with my work laptop. The likely reason is that your organisation blocks access to the LIFX API from your browser, or when using your company network/VPN.

# Out od scope
This app does not allow the management of lights (setup, renaming, moving room...). Use the offical LIFX apps for this
* https://apps.apple.com/us/app/lifx/id657758311
* https://play.google.com/store/apps/details?id=com.lifx.lifx&hl=en_AU
