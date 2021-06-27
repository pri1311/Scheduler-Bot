## `Captain Hook - Discord Message Scheduling Bot`

Captain Hook will send your scheduled messages to any channel set at any time and date.

### `Tech Stack`

-   NodeJs
-   MongoDB

### `Get Started`

-   npm install
-   npm start

### `Command`

-   !schedule `<Channel Tag> <YYYY/MM/DD> <HH:MM> <"AM" or "PM"> <Timezone>`
-   In the next message, provide the content to be scheduled.

Available Timezones: https://gist.github.com/AlexzanderFlores/d511a7c7e97b4c3ae60cb6e562f78300

### `Working of the Bot`

Bot is designed using discord.js. On using the schedule command, if correct arguments are provided to the bot, it uses message collector to get the next message for the content, and stores it in mongoDB. Bot checks for messages to be sent every two minutes, and deletes the messages once sent.

### `Future Scope`

-   Allow user to see scheduled messages.
-   Allow user to edit/delete scheduled messages.

### `Demo`
[<img src="https://github.com/pri1311/Scheduler-Bot/blob/master/Videos/CaptainHook.mp4" width="50%">](https://github.com/pri1311/Scheduler-Bot/blob/master/Videos/CaptainHook.mp4)
[<img src="https://github.com/pri1311/Scheduler-Bot/blob/master/Videos/ErrorHandling.mp4" width="50%">](https://github.com/pri1311/Scheduler-Bot/blob/master/Videos/ErrorHandling.mp4)
