# ChromeDriverKillerTray

ChromeDriverKillerTray is a simple tray icon which changes colour when it detects a chromedriver process running locally. You can then click on it to kill the chromedriver. I wrote this because when using selenium with chromedriver if the controlling process was stopped or crashed or anything else during development it wasn't cleaning up the chromedriver instances and then wouldn't work properly if restarted. This was a simple, crude but easy solution to that problem
