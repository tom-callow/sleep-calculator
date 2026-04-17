# Sleep Calculator

A minimal sleep cycle calculator designed to be saved to your iPhone home screen.

Enter your bedtime and it returns optimal wake-up times based on 90-minute sleep cycles — or flip to reverse mode and enter when you need to wake up to get ideal bedtimes instead.

**Live:** [tom-callow.github.io/sleep-calculator](https://tom-callow.github.io/sleep-calculator)

## Features

- Forward mode: enter sleep time → get wake times
- Reverse mode: enter wake time → get bedtimes
- Simple time input or iOS-style wheel picker
- Set alarm button (requires a one-time iOS Shortcut setup — see below)
- Highlights optimal wake times (5–6 cycles)
- Works offline (PWA)
- No dependencies, no build step

## Install on iPhone

Open the link above in Safari → Share → Add to Home Screen.

## Set Alarm shortcut setup

The "Set alarm" button passes the selected wake time to an iOS Shortcut. To set it up, create a new Shortcut named exactly `Sleep Alarm` with these three actions:

1. **Find Alarms** → Label → is → `Sleep`
2. **Delete Alarms**
3. **Add New Alarm** → Time: `Shortcut Input` → Label: `Sleep`

This deletes any existing alarm labelled "Sleep" and creates a fresh one — all other alarms are left untouched.
