

**Client-Side-Timing** is a stand-alone javascript tool that, once linked to on a webpage, will display a little icon showing the current page's load time. Then, click on it to get a breakdown.

jQuery is used to read and display the values from the browser's Navigation Timing object: `window.performance.timing`

<img src='https://client-side-timing.googlecode.com/files/cst_screencap.png' />

# Installation #

Add these lines to `<head>` in any page you want timed.

### Disabled by default ###

```
    <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.1/jquery.min.js"></script>
    <script type="text/javascript" src="http://your.domain.com/Scripts/ClientSideTiming.js"></script>
```

Then to enable, browse to your page and add "`enableCST=1`" to the URL.


### Enabled by default ###

```
    <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.1/jquery.min.js"></script>
    <script type="text/javascript" src="http://your.domain.com/Scripts/ClientSideTiming.js" cst_enabledByDefault></script>
```

# Supported browsers #
  * Chrome
  * IE9+
  * Any others not listed here but have implemented the Navigation Spec will also work