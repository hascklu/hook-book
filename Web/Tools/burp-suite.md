# Burp Suite

## Introduction
Burp Suite is a pentest toolset for web applications. Here are some useful usecases with that software:

#### Use as web proxy
You can use Burp Suite to interceptate requets and responses to use them as you want. First of all, go to Firefox:
```
- Select Preferences.
- Type 'proxy' on the search bar
- Click on 'Settings', then 'Manual proxy configuration'
- Be sure to have on HTTP Proxy and Port respectively '127.0.0.1' and '8080'
```

OK, now you can launch Burp Suite. For this type of thing, you don't need specific configuration. Just go through 
boring steps until the main interface. Then, click on Proxy tab and Intercept if the button is on 'off'. That's it!
You can now navigate and look at every single communication between you and the server.