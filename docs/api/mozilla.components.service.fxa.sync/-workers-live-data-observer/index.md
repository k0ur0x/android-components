[android-components](../../index.md) / [mozilla.components.service.fxa.sync](../index.md) / [WorkersLiveDataObserver](./index.md)

# WorkersLiveDataObserver

`object WorkersLiveDataObserver` [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/service/firefox-accounts/src/main/java/mozilla/components/service/fxa/sync/WorkManagerSyncManager.kt#L80)

A singleton wrapper around the the LiveData "forever" observer - i.e. an observer not bound
to a lifecycle owner. This observer is always active.
We will have different dispatcher instances throughout the lifetime of the app, but always a
single LiveData instance.

### Functions

| Name | Summary |
|---|---|
| [init](init.md) | `fun init(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDispatcher](set-dispatcher.md) | `fun setDispatcher(dispatcher: `[`SyncDispatcher`](../-sync-dispatcher/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
