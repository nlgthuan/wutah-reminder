# 💧 Wutah reminder

<p align="center">
  <img src="./doggo-water.jpg" />
</p>

## How to install

1. Clone the repo

1. Install [terminal-notifier](https://github.com/julienXX/terminal-notifier) via homebrew:

   ```bash
   brew install terminal-notifier
   ```

1. Setup the cronjob

   ```bash
   editor=vim crontab -e
   ```

- Setup the cronjob to run at the interval you like:

  ```
  30 * * * * <PATH-TO-THE-REPO>/wutah-reminder.sh
  ```

- Example for the cronjob to run at every 30th minute

  ```
  */30 * * * * <PATH-TO-THE-REPO>/wutah-reminder.sh
  ```
