# Android Keyboard Numpad Number support

This Fork of [TitanQwerty app by fjdrjr](https://github.com/fjdrjr/titanqwerty).

Keyboard layouts for the physical QWERTY keyboards support Numpad number

## Installing

1. Build this app
2. Install from apk
   NOTE: Unknown sources must be enabled to install the App from file.

## Enabling

1. Open app and tap on "physical keyboard settings"
2. Tap on "wayland_keyboard" - that is the name of Titan Pocket's physical keyboard device
3. Tap on "Add layouts" underneath the offered selection
4. Scroll down the list until you find "Full keyboard with numpad, US QWERTY"
5. Enable the switch behind the desired layout
6. Go back and choose the layout you just enabled in the step before as your active keyboard layout

## Building

Use Java 17 for this project.

The project uses Gradle and can be built with Android Studio or via commandline, for example:

```SHELL
export JAVA_HOME="$HOME/android-studio/jre"
export ANDROID_HOME="$HOME/Android/Sdk"
./gradlew assembleDebug
```

## Layout files

Layout file `key_numpad.kcm` maps numpad number keycodes to number keys.

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.
