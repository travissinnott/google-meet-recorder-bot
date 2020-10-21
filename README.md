# google-meet-recorder-bot
The beginnings of a project to automatically record Google Meet sessions by calendar invite

The basic concept is simple: a bot sits and watches your inbox (via IMAP or Gmail API) for calendar invites with Google Meet links.  At the appointed time of the meeting, the bot fires up a headless chrome browswer and records the audio (and hopefully whole screen).  These recordings would then be uploaded to Google Drive, or somewhere to be store and shared.

## Project Status

This is in the planning and research phase.

## Resources

* https://github.com/puppeteer/puppeteer/blob/main/README.md
* https://www.npmjs.com/package/puppeteer-recorder
* https://www.npmjs.com/package/electron-recorder
