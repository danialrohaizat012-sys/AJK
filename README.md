# AJC Blueprint — Clean Owner Configuration

This build removes all leftover demo owner names.

## Central owner configuration
The owner identity is controlled from one place in `index.html`:

```js
const APP_CONFIG = Object.freeze({
  ownerName: "Rafiq Danial",
  ownerInitials: "RD",
  ownerRole: "Owner",
  appName: "AJC Blueprint"
});
```

Changing those values updates the dashboard greeting, profile, comments, activities, measurement updates and revision history.

All previous project, section workspace, drawing editor, LocalStorage, PWA and responsive features remain included.
