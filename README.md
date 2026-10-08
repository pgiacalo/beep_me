# Beep Me

A very simple alarm clock web app. Set the alarm to the hour, minute, and second. It counts down with warning beeps, sounds a 1-second tone at the set time, and automatically turns off.

## Live site

https://pgiacalo.github.io/beep_me/

## Usage

1. Enter the **Hour** (0–23), **Minute** (0–59), and **Second** (0–59).
2. Click **Set Alarm**.
3. Countdown warnings:
   - **30 seconds** before: 3 beeps
   - **20 seconds** before: 2 beeps
   - **10 seconds** before: 1 beep
4. At the set time the app plays a 1-second tone and turns itself off.

If the alarm is set less than 30 seconds out, any warnings already passed are skipped.

Click **Cancel Alarm** any time to clear a pending alarm.

## Notes

- Pure static HTML/CSS/JS — no build step, no dependencies.
- The beep uses the Web Audio API. Setting the alarm counts as the user interaction browsers require before audio can play.
- Keep the tab open for the alarm to fire.
