# Scripts

## Notify devices

This Home Assistant blueprint allows you to send a customized notification to a specified mobile device via the `mobile_app` integration. With options to set notification importance, add a title prefix, and adjust the notification sound, this blueprint is ideal for differentiating alerts and providing contextual information.

Features

- Device Selection: Choose a mobile device registered with the mobile_app integration to receive the notification.
- Title Prefix: Optionally add a prefix to the notification title to distinguish between multiple Home Assistant instances or alert sources.
- Importance Levels: Set the importance level of the notification (normal, info, warning, or critical). Each level adjusts the title icon and sound behavior:
  - normal: No special icon.
  - info: Displays an ℹ️ icon.
  - warning: Displays a ⚠️ icon.
  - critical: Displays a ❗ icon and uses a default critical alert sound.
- Custom Title and Message: Customize the title and message content to suit the notification’s context.
- Notification Tagging: Use tags to replace previous notifications with the same tag, ensuring the latest information is displayed.
- Sound Configuration: Specify a notification sound, except for critical importance (which overrides it with the default critical sound).

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fsn0kerbuzz%2FHA-Recipes%2Fblob%2Fmain%2FScripts%2Fnotify-device.yaml)
