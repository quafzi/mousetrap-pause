mousetrap-pause
===============

Mousetrap plugin to pause and unpause all or specific combos

Installation
------------

    npm install mousetrap-pause --save

Usage
-----

Use browserify to use Mousetrap with pausing functionality:

```javascript
var mousetrap = require('mousetrap-pause')(require('mousetrap'));
```

API
---

This plugin extends Mousetrap to pause:

```javascript
mousetrap.pause();
```

and to unpause

```javascript
mousetrap.unpause();
```

If you want to pause or unpause only single combos, e.g. mod-a:

```javascript
mousetrap.pauseCombo('mod-a');

/* ... */

mousetrap.unpauseCombo('mod-a');
```
