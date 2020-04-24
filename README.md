# slow. chat.

```
notification = interruption

if (emergency)
{
	interruption = good
}
else
{
	interruption = bad
}
```

Messaging platforms share a common, incorrect assumption:  that interruptions are good.  Notifications, which are interruptions, are enabled by default, and the platforms make great effort to reduce the difficulty of sending these interruptions.  What we need is a messaging platform that respects our need to focus.  Enter "slow. chat."

## Feature Set

Traditional chat functions: 
- Channels 
- Direct Messages 
- etc. 

Slowness:
- All notifications off by default
- Users have fine-grained control of when they are interrupted:
	- Set per-user and per-channel notification timers.  Example:  if my boss sends me a direct message, I want to be notified within 30 minutes (time span options: 30, 60, 120 minutes)
	- every 30 minutes, interruptions are summarized.  The application works to minimize the number of summaries.  Example:  If I have an interruption due in 47 minutes, and another due in 12, then the later interruption will be included on the same summary as the earlier interruption, so that there is only one interruption summary.  
	- For time-sensitive situations, message senders can choose to interrupt recipients immediately, via a context menu on the message.  
- Appropriate roadblocks prevent egregious interruption:
	- Notification is accessed in a message-based context menu, adding a step to the interruption process.  If an interruption will be sent to more than 5 people, the user must also click through a dialog box informing them that they are about interruption X people's productive time, and asking them if they have have a way of accomplishing their goal other than interrupting everyone immediately.  
- For emergencies, a !PANIC mode is available per channel and per direct message conversation, in which interruptions are sent by default, much like traditional messaging platforms 
