+++
date = '2025-03-27T14:23:54-03:00'
draft = true
title = '[LBS API] -  Notification System'
tags =  ["Documentation", "LBS"]
+++


### Method: 

```c#
public static void MessageNotify(string message, LogType logType = LogType.Log, int duration = 2)
```
To display notifications in the tool use the LBSMainWindow's MessageNotify static function:


- **Message:** `String` Text that'll be shown on screen.
- **LogType:** `enum Logtype,Log` The type of message, it affects the icon displayed.
* **Duration:** `int` The duration in seconds of the message before it fades out and it's deleted.


### Example:

```c#
LBSMainWindow.instance.MessageNotify("[ISI Lab] Warning: You don't have any layer selected.", LogType.Warning, 2);
```


![notification result](https://github.com/user-attachments/assets/a6d5c9eb-411c-49b1-ac25-4374b981d536 "A sample notification")
