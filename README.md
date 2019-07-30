## process-time

A tiny utility that prints the total uptime of your nodejs process when it exits.

All you need to do is add this at the top of your script:

```js
require('process-time');
```

Then, when the app shuts down, it will print:

```
Process exited. Took: 23:41m
```
