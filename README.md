# Calabash-Crosswalk

A Sample repo demonstrating how to test Crosswalk Apps with Calabash

## Calabash Android 

#### Start Repl

```
calabash-android console .\app\dist\sample-app-crosswalk-16.apk
reinstall_apps
start_test_server_in_background
```

#### Query for Web Elements
```
query("org.xwalk.core.internal.XWalkContent$1 css:'h2'")
```


## Xamarin UITest

#### Start Repl

```
.\tests\Xamarin.UITest.1.3.6\tools\test-cloud.exe repl .\app\dist\sample-app-crosswalk-16.apk
```

#### Query for Web Elements
```
app.Query(c => c.Raw("org.xwalk.core.internal.XWalkContent$1 css:'h2'"))
```
