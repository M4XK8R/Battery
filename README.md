# Battery
Application that notify you with sound when battery reaches a certain level while charging.

Simple but enought interesting app. Using "no UI" foreground service which recieve broadcasts from the system.
Broadcast receiver class is not working at the main thread using extension function that working in coroutine. 

The application can be stopped by using "STOP" button at the notification or simple by remove charger from your smartphone.
Also, you can chose desired battery level by "SETTINGS" button at the notification. 
