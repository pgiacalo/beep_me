# Beep Me

A very simple alarm clock web app. Set the alarm to the hour, minute, and second. When it triggers, it beeps once and automatically turns off.

## Live site

https://pgiacalo.github.io/beep_me/

## Usage

1. Enter the **Hour** (0–23), **Minute** (0–59), and **Second** (0–59).
2. Click **Set Alarm**.
3. At the set time the app beeps once and turns itself off.

Click **Cancel Alarm** any time to clear a pending alarm.

## Notes

- Pure static HTML/CSS/JS — no build step, no dependencies.
- The beep uses the Web Audio API. Setting the alarm counts as the user interaction browsers require before audio can play.
- Keep the tab open for the alarm to fire.
