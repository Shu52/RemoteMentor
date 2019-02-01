# Remote Mentor
Policy for Remote Mentor for common tables

## Intro
For many students and Alumni, it can be a hardship to meet at the school for the Alumni common table. This policy is meant to remove the pain point of trying to connect Alumni-student teams remotely.

### Getting started
- Alumni will check in on the Slack channel, ` ask_alumni` when they are available.
- The student will contact the mentor through this channel to start a session.
- Slack can handle a voice call, and we suggest using the [live share extension](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) for VS Code for screen sharing. Both parties will be required to have the live share extension installed.
- Also, ensure both parties are signed in on their respective IDEs.
- The student should use the *read only link* to avoid alumni take over.
- The student will open the *Command Palette* with either `ctrl + shift + p` or `F1`.
- Type `Live Share: Share Server` and copy & paste their url into the field. This will allow the alumni to see the DOM.
- The following field is optional. Feel free to hit enter to move passed it.

Alternately, teams can use Google Hangouts and screen share, but the resolution is worse and makes the code harder to read. It also forces the student to scroll for the alumni to read.
### Example workflow

*In Slack Channel*
```
Alumni: Hey, everyone! I'm available to answer questions from 4-7 today.
I can help with React, Js, C#, and .NET."
```
```
Student: I could use some help with React please!
I am working on my front-end project, and the app doesn't route the user correctly after login.
```
The alumni will make the call when they are ready. Check volume and mic settings if needed.
```
Alumni: I will call you through Slack.
Prepare to Direct Message me your LiveShare link
```
- **Alumni** will click on student's name and select call.
- **Student** will answer call and Slack out the LiveShare link (read only) in direct message.
- **Alumni** may want to Slack out in the channel that they are with a student and are currently unavailable.
- **Student** will click on "LiveShare" link on bottom left of VS Code. A popup will appear on bottom right. Student should select *"Make Read-Only"* button and paste link into direct message to alumni in Slack.
- **Student** will also follow steps to share their server so Alumni can see the DOM.
- After the session is over, the student should stop the collaborating session in VS Code. The Alumni should make a Slack message that they are now available.

### Other uses
It is acceptable for Alumni and students to arrange a tutoring session outside normal common table hours via the `ask alumni` Slack channel.
