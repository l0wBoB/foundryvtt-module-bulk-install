# What's this?
This script enables you to install or update a list of Foundry VTT modules easily.

# Why?
Assume that you started supporting a new content creator and thus got access to their full catalog of Foundry modules.
Usually, you would install such many modules manually by uploading the module folders into your server file system.
With this script you can command your server to download the modules itself instead, and in a single step instead of one by one through the module browser.

# How-to?
1. Gather the manifest urls of the modules you want to install or update.
2. Download and edit the [script.js](script.js) accordingly.
3. Login to your Foundry instance and enter the setup menu.
4. Open the developer tools of your web browser.
 - [Mozilla Firefox Tutorial](https://firefox-source-docs.mozilla.org/devtools-user/web_console/)
 - [Google Chrome Tutorial](https://developer.chrome.com/docs/devtools/open)
 - [Microsoft Edge Tutorial](https://learn.microsoft.com/en-us/microsoft-edge/devtools/overview#open-devtools)
4. Inside the developer tools, navigate to the Console tab.
5. Paste the content of your modified script.js here, then press Enter.
6. ???
7. Profit

# Will this script empty my bank account?
I havent tested for that but it does what it should do with [Foundry VTT 13.351](https://foundryvtt.com/releases/13.351) running on [PM2](https://pm2.io/).
