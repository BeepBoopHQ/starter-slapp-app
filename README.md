# starter-slapp-app

This repository is meant as an example and starting point for building a Slack app on [Beep Boop][bb].  It's written in [node.js](), uses the [Slapp][slapp] library, and takes advantage of the [Slack Events API][slack-events-api].

## Setup Instructions

Once you've created a new [Beep Boop](bb) project with this repo, go to your project's **Settings** tab and enable a Slack App.

![Enable Slack App](https://cloud.githubusercontent.com/assets/367275/19362140/b4039c86-9142-11e6-9b31-941609c1b090.gif)

Follow the steps laid out in the wizard. You'll want to enable **Event Subscriptions** on your Slack App using the `URL` provided and add subscriptions for the following **Bot Events**:

+ `message.channels`
+ `message.im`

### 🔥 it up

Once you've finished setting up your Slack App and saved the `Client ID`, `Client Secret` and `Verification Token` on Beep Boop, go ahead and **Start** your project.

![Start](https://cloud.githubusercontent.com/assets/367275/19364564/edb43efa-914b-11e6-9265-d33122bf5f9a.png)

Once your project has started, go to the **Teams** tab and add your new Slack App to one of your Slack teams.

![Add Team](https://cloud.githubusercontent.com/assets/367275/19364343/012e4922-914b-11e6-8f0a-bb020b016fd2.png)

Send `@slappbot` a Direct Message of `help` to see what it can do.

![Help](https://cloud.githubusercontent.com/assets/367275/19364707/7a4f8964-914c-11e6-99cd-d4cd65c9061a.png)

[bb]: https://beepboophq.com
[slapp]: https://github.com/BeepBoopHQ/slapp
[slack-events-api]: https://api.slack.com/events-api
[presence-polyfill]: https://github.com/BeepBoopHQ/beepboop-slapp-presence-polyfill

