# Automations

## Notify when Home Assistant starts

This Home Assistant blueprint sends a notification to specified devices or scripts each time Home Assistant starts. It allows you to configure the notification title, message, sound, and target devices or scripts, making it ideal for monitoring system restarts and ensuring you’re notified when Home Assistant is back online.

Features

- Customizable Title and Message: Define the notification title and message to suit your preferences.
- Device and Script Selection: Choose multiple mobile devices (via mobile_app) or notification scripts to receive the notification.
- Optional Sound Configuration: Add a custom sound to play with the notification.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fsn0kerbuzz%2FHA-Recipes%2Fblob%2Fmain%2FAutomations%2Fnotify-ha-start.yaml)

## Notify when a person changes zones

This Home Assistant blueprint sends a notification to a specified mobile device when any tracked person changes their zone (such as moving from home to not_home, or arriving at a specific location). It provides timely alerts for monitoring the location changes of family members or other tracked persons.

Features

- Multiple Person Tracking: Select multiple persons to monitor for zone changes.
- Customizable Notifications: Sends different messages depending on whether the person is arriving or leaving a zone:
  - Arrival Notification: Notifies when a person arrives at a specific zone.
  - Departure Notification: Notifies when a person leaves a zone, with the notification indicating the previous zone.
- Device Selection: Choose a target device from your mobile devices connected via the mobile_app integration.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fsn0kerbuzz%2FHA-Recipes%2Fblob%2Fmain%2FAutomations%2Fnotify-person-zone-change.yaml)

## Notify when running process finished

This Home Assistant blueprint sends a notification when a binary sensor (configured with a running device class) changes from an “on” to an “off” state, indicating that a process has finished. It includes options to set a confirmation duration, custom messages, and choose devices or scripts to receive the notification, ensuring you stay informed about completed processes.

Features

- State Sensor Monitoring: Tracks the state of a binary sensor linked to the washing machine, detecting when it turns “off.”
- Confirmation Duration: Configurable delay to confirm the washing machine has indeed finished before sending the notification.
- Customizable Title and Message: Set a personalized title and message to make the notification informative and engaging.
- Device and Script Notifications: Choose multiple mobile devices (via mobile_app) and/or notification scripts to receive the alert.
- Optional Notification Sound: Specify a sound to play with the notification for added emphasis.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fsn0kerbuzz%2FHA-Recipes%2Fblob%2Fmain%2FAutomations%2Fnotify-finished-running.yaml)
