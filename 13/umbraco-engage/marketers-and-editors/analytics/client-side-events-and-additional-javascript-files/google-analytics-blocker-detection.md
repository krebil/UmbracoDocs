---
icon: square-exclamation
description: Learn how Umbraco Engage handles visitors who use blocker detection.
---

# Google Analytics blocker detection

When a visitor runs an Adblocker or cookieblocker the visitor is likely not tracked in Google Analytics. With Umbraco Engage you can still track this visitor.

This is made possible by a JavaScript file that you can include before the closing `body`-tag in your HTML:

```js
<script src="/Assets/umbracoEngage/Scripts/umbracoEngage.analytics.blockerdetection.js"></script>
```

If you include the script one of the following events is sent:

* If Google Analytics is blocked in the browser of the visitor: `umbEngage("send", "event", "Tracking", "Blocked", "Google Analytics");`
* Otherwise, the following event is sent: `umbEngage("send", "event", "Tracking", "Allowed", "Google Analytics");`

To see the statistics of this event go to the Analytics section of Umbraco Engage and open the 'Events' report. Look for the category with the name 'Tracking'.

![]()