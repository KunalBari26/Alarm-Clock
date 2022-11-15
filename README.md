## ALARM CLOCK 
I have made a project of alarm clock where user can set multiple alarms and can snooze the alarm for a interval of 5 min .

#### CLOCK
I have used setInterval with interval of 1000ms so that the page can get the updated time after every 1 sec. The current will be displayed on the screen in the format of hh:mm:ss . I have also added date, month , year and day in the clock.

#### ALARMS
I have used an array to store all the alarm the user want to set.
I have provide input fields for hour, min , sec . All the alarm will be stored and displayed as a list. If a user don't put any time and press set alarm , a default alarm of 00:00:00 will be set.
A function will check the current time with times in list and if both the time matches it will ring the alarm.

#### SNOOZE
Whenever the alarm will go off the snooze button will be enabled and as soon as user will press snooze a new alarm with the time 5 min from current time will be added to the alarm list.