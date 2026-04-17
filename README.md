# Sleep Calculator

A minimal sleep cycle calculator designed to live on your iPhone home screen.

Enter your bedtime and it returns optimal wake-up times based on 90-minute sleep cycles. Flip to reverse mode to enter a wake time and get ideal bedtimes instead.

**Live:** [tom-callow.github.io/sleep-calculator](https://tom-callow.github.io/sleep-calculator)

## Features

- Forward and reverse mode (sleep time → wake times, or wake time → bedtimes)
- Simple time input or iOS-style wheel picker
- Defaults to current time on load
- Set alarm button via iOS Shortcuts
- Works offline (PWA)

## Install on iPhone

Open the link in Safari → Share → Add to Home Screen.

## Set Alarm setup

Create a Shortcut named exactly `Sleep Alarm` with three actions:

1. **Find Alarms** → Label → is → `Sleep`
2. **Delete Alarms**
3. **Add New Alarm** → Time: `Shortcut Input` → Label: `Sleep`

Only alarms labelled "Sleep" are affected — all others are left untouched.
