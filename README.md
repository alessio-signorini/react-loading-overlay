# Loading Overlay

[![npm version](https://badge.fury.io/js/react-loading-overlay.svg)](https://badge.fury.io/js/react-loading-overlay)

A customizable, simple loading overlay.

![](https://d17oy1vhnax1f7.cloudfront.net/items/1f1V3g0T0u403m3U431n/Screen%20Recording%202016-10-20%20at%2002.29%20PM.gif)

-------

## Usage

```javascript
<div>
  <LoadingOverlay
    active={isActive}
    spinner
    text='Loading your content...'
    >
  <p>Some content or children or something.</p>
</div>
```


### props

+ **active**, `Boolean`, whether the loader is visible.
+ **animate**, `Boolean`, whether to fade the overlay in and out.
+ **spinner**, `Boolean`, whether to use a spinner in the loader.
+ **text**, `String`, used as content of the loader.
+ **background**, `String`, valid css color declaration for the overlay background.
+ **color**, `String`, valid css color declaration for the text and circle color.
+ **spinnerSize**, `String`, valid css size (`100px`) for the size of the spinner circle.
+ **zIndex**, `Integer`, use in case you are experiencing other z-indexed components appearing over top of the overlay.
