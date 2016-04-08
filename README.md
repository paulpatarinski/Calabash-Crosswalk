# Calabash-Crosswalk

A Sample repo demonstrating how to test Crosswalk Apps with Calabash

### Start Calabash Android Console

```
calabash-android console .\app\dist\android-debug.apk
reinstall_apps
start_test_server_in_background
```

#### Query for Web Elements
```
query("org.xwalk.core.internal.XWalkContent$1 css:'*'")
```
