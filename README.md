<b> Xiaowei Liu <b>

# Alarm-Clock-project

<i>We want to develop software for an alarm clock.
The clock shows the time of day. Using buttons, the user can set the hours and minutes fields individually,
and choose between 12 and 24-hour display.
It is possible to set one or two alarms. When an alarm fires, it will sound some noise. The user can turn it off,
or choose to “snooze”. If the user does not respond at all, the alarm will turn off itself after 2 minutes.
“Snoozing” means to turn off the sound, but the alarm will fire again after some minutes of delay. This
“snoozing time” is pre-adjustable.</i>


  <img src="/Diagram.png" width="700px" />


## Use Case Description
<br>
Scenario: Alarm Clock
<br>
Triggering event: Operate the system by buttons
<br>
Actors: Buttons
<br>
Related use casese: N/A<br>
Pre-condition: The current time and snoozing time are null
<br>
Post-condition: All the time is set
<br>
Event Actors: Users press the buttons
<br>
System event: display the current time and do the alarm on time
<br>
Event: user set the current time, alarm and the length of snoozing. User is able to shut the alarm off or snooze when the alarm fires. If the alarm was asked to snooze, it would fire again after the snoozing time.

## feedback by Yi Zhao

The case diagram and descriptions are created following the provided documents. 
They explain how the alarm clock works clearly. Every possibel case is listed when alarm fires.
And I do not find anything left in this solution. I think it covers all requirements. 
The actors are named singular and use cases ideally begin with a verb. There is enough detail to help us to understand this project, which is very great.
