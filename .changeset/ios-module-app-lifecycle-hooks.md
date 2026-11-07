---
'expo-modules-core': patch
---

[iOS] Add the `appWillEnterForeground`, `appDidBecomeActive`, and `appDidEnterBackground` lifecycle hooks to modules. They are equivalents of the `OnAppEntersForeground`, `OnAppBecomesActive`, and `OnAppEntersBackground` DSL components and work in `@ExpoModule` modules.
