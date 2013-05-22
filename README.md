android-quiet-logs
==================

A set of patterns to ignore in Android log spew.

Unlike grepping for your own log tag, this'll catch relevant system events, stack traces, etc.

Put it somewhere, then:

```
adb logcat -v time | fgrep -v -f android.ignore
```
