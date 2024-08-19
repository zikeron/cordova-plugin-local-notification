# cordova-plugin-local-notification (fork)

This is a fork of [@moodlehq/cordova-plugin-local-notification](https://github.com/moodlemobile/cordova-plugin-local-notification). If you are looking for the documentation, you can read the original at [katzer/cordova-plugin-local-notifications](https://github.com/katzer/cordova-plugin-local-notifications).

## Modifications from the original

We created this fork because we needed to include the following modifications in [our mobile application](https://github.com/moodlehq/moodleapp):

| PR | Description |
| -- | ----------- |
| [#1781](https://github.com/katzer/cordova-plugin-local-notifications/pull/1781) | Reuse existing messages when using MessagingStyle |
| [#1853](https://github.com/katzer/cordova-plugin-local-notifications/pull/1853) | Use correct authority name |
| - | Support Android X |
| - | Support sender image |
| - | Fix crash with target SDK 31 |
| - | Declare SCHEDULE_EXACT_ALARM permission |
| - | Fix click notifications in Android 12 |
| - | Inexact alarms will be scheduled in Android if 'Alarms & reminders' setting is disabled |
| - | Add new methods to check permissions and open native settings |

It also includes some commits that are in master and haven't been released.

You can see all the changes here: [0.9.0-beta.3...moodlemobile:v0.9.0-moodle.12](https://github.com/katzer/cordova-plugin-local-notifications/compare/0.9.0-beta.3...moodlemobile:v0.9.0-moodle.12)

## Installation

You can install this package using:

```sh
cordova plugin add https://github.com/zikeron/cordova-plugin-local-notifications.git
```
