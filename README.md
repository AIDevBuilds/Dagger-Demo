# Dagger Demo (Android)

Android sample that shows Dagger 2 dependency injection with an application component, an activity component,
modules and custom scopes.

This is an older sample kept for reference. It is not actively maintained.

## What it shows

- `ApplicationComponent` and `ActivityComponent`, with `ApplicationModule` and `ActivityModule`
- Custom scopes `@PerActivity` and `@PerFragment`
- Injected helpers: `DataManager`, `DbHelper` and `SharedPrefsHelper`

## Stack

Java, Dagger 2.14.1, `minSdkVersion 15`, `compileSdkVersion 27`.

## Run

Open the project in Android Studio and run the `app` module. It uses an older Android Gradle plugin (3.1.x) and `compileSdkVersion 27`, so Android Studio may ask you to update the Gradle wrapper and plugin.

## License

MIT. See [LICENSE](LICENSE).
