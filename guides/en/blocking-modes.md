Choose a mode according to what should trigger the restriction: your tap, the time, daily use, or your location. **Pause** temporarily allows access without deleting your rules.

## Before you start

Create a group, select its apps, categories, or websites, and grant Screen Time access. Open **MANAGE** beside the group to manage all its contents, or beside an app to manage that app. Some features require Premium; App Lock shows the upgrade screen when needed.

Your App Lock passcode and Face ID protect entry to App Lock. They are separate from the rules that block selected apps.

## Lock: block now

Choose **Lock** in MANAGE to block the selected content immediately. A manual lock stays in place until you unlock it; a schedule ending does not remove a separate manual lock.

Example: lock a social group before studying, then unlock it when you finish.

## Period: block between two times

Open **MANAGE → Set Schedule**, enable **Use Schedule**, and choose **Period**. Set the start, end, and weekdays, then save with the checkmark at the top right. Time is selected from **00:00 to 23:59**, without an AM/PM control.

- **09:00–18:00:** blocked during that interval on selected days.
- **22:00–07:00:** an overnight interval. A selected Monday starts Monday evening and ends Tuesday morning.

Outside the interval, that schedule does not block access. Another active rule can still keep the app blocked. To remove the schedule, turn off Use Schedule and save.

## Scenarios: ready-made periods

Scenarios fill in a Period; they are not a separate additional lock. You can change the hours and days afterward.

- **Daytime:** 09:00–18:00 every day.
- **Evening:** 18:00–23:00 every day.
- **At Work:** 09:00–18:00, Monday to Friday.
- **Weekend:** all day Saturday and Sunday.

## Daily Limit: block after daily use

Choose **Daily Limit** in the schedule editor and set the allowed daily use and days. Before the threshold, that rule allows access. After the threshold, it blocks access for the rest of that day; the allowance starts again on the next selected day.

Example: a 30-minute limit allows daily use until iOS reports that the threshold has been reached. Each selected app has its own counter; selected categories and websites share a separate combined counter. Usage already recorded today can count, so saving a limit does not necessarily start a fresh allowance. iOS measures usage; delivery of a threshold event can be delayed.

This is a daily allowance, **not a limit on every individual session or opening**.

## Lock by Location: block inside or outside an area

Choose **Lock by Location** in the group's or individual app's MANAGE menu. Select a place, set the radius, choose inside or outside, enable the rule, and save with the checkmark.

- **Inside:** block while in the chosen area, for example at work.
- **Outside:** block while outside the area, for example away from home.

Allow location access when requested. Background detection needs Always access; Precise Location improves accuracy. iOS region events are not instantaneous and depend on location availability. A location badge means a rule is configured, not that it is necessarily blocking now. Disable the rule and save to remove it.

## Pause: allow access for 5, 10, or 15 minutes

Choose **MANAGE → Pause → duration**. For that time, the selected content becomes accessible even when a saved restriction applies. A group pause affects its contents; an app pause affects that app. Other content remains protected.

The rules stay saved. After the countdown, App Lock restores whatever protection should apply then. Example: pause a schedule until 18:00 for five minutes at 17:00, and protection returns at about 17:05. If the schedule has already ended by the time the pause expires, that schedule does not block again.

Pause is elapsed time from the action, **not minutes of active use**. Closing the app does not stop its countdown. It does not erase today's Daily Limit usage or create a new daily allowance. An explicit new Lock ends the pause for that content early. If pauses overlap, an unexpired pause still allows access.

## Unlock and the blocking screen

**Unlock** removes the applicable manual restriction and bypasses the current scheduled occurrence. It does not delete the saved schedule; a later interval can block again. Unlocking an active location restriction allows access until the next area-state change; disable the location rule to stop it completely. Rules in another group can still apply.

On the blocking screen, **Close** exits the blocked app without removing protection. **Unlock** there opens App Lock, asking for its authentication if enabled; opening App Lock alone does not grant access. The Show Unlock setting only controls whether that button is visible.

## Notifications, widgets, and overlapping rules

Configure alerts and reminders in **Settings → Notifications**. A reminder warns before a restriction; it does not create a new lock. Scheduled alerts offer Unlock and timed options. Timed options work like Pause; plain Unlock bypasses the current scheduled occurrence. App Lock may ask you to authenticate first.

An unlocked widget group can be locked from the widget. A locked group opens App Lock for managing access; the widget does not silently unlock it. Widget symbols show actual counts of apps, categories, and websites.

Manual, schedule, and location rules can overlap. Turning off one does not turn off the others. **Lock** indicates current protection; a clock indicates a saved schedule; a location marker indicates a configured geographic rule; the pause countdown shows a temporary allowance.
