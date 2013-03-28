
# Emitter

A non-blocking event emitter. Non-blocking as in "if I call `emitter.emit()`, the emission of events to their handlers won't block".

Given the nature of "events", one would think event emission is *always* asynchronous. Looking at most implementations; that's not the case. This fixes it.

## Install with [bower](http://twitter.github.com/bower/)

```shell
$ bower install emitter
```


