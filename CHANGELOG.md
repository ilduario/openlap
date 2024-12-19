2.4.0 2024-12-02
----------------

- Add Português translation (courtesy of Ilduario).

- Update dependencies.


2.3.1 2024-08-19
----------------

- Upgrade to `cordova-android` 13.0.0.


2.3.0 2024-03-28
----------------

- Add voice pitch and rate settings.

- Add faster/slower indicator to lap details.

- Add `CODE` button to drivers pages.


2.2.0 2024-01-21
----------------

- Fix Android fullscreen mode based on screen orientation.

- Add Slovak translation (courtesy of Ludevik).

- Add voice selection.

- Update dependencies.


2.1.0 2023-12-22
----------------

- Add option to stop all cars when race/qualifying is finished.

- Improve drivers menu layout in portrait mode.

- Re-enable "dev" mode on Android.

- Drop monochrome Android icons.

- Update dependencies.


2.0.0 2023-08-30
----------------

- Require Android 8.1 or greater.

- Officially drop support for serial (USB-OTG) connections.  This may
  still work on older Android devices, but will be no longer maintained.

- Drop Dutch language support due to decreased demand.

- Open lap time history when clicking on leaderboard item.

- Add custom color chooser to "Drivers" menu.

- Remove "Colors" menu item.

- Use colored background for position/controller display.

- Simplify setting time/laps for qualifying and races.

- Hide "speech" icon in portrait mode and add menu entry.

- Add more notifications.

- Upgrade to Angular 15.

- Upgrade to Cordova 12.

- Upgrade to Ionic 7.


1.10.0 2023-03-30
-----------------

- Switch to [Awesome Cordova
  Plugins](https://github.com/danielsogl/awesome-cordova-plugins).

- Switch to
  [cordova-plugin-tts-advanced](https://github.com/spasma/cordova-plugin-tts-advanced).

- Re-enable serial connections on Android < 10.

- Re-enable native toasts on Android.

- Prevent content from displaying in the cutout area ("notch") on
  Android in fullscreen mode.

- Update license page.


1.9.10 2023-03-26
-----------------

- Drop USB-OTG support for Android >= 12.

- Update `shields` actions URL.

- Update dependencies.


1.9.9 2022-11-26
----------------

- Use low-latency scan mode for BLE connections on Android.

- Update dependencies.


1.9.8 2022-11-25
----------------

- Update `cordova-plugin-ble-central` (fixes Bluetooth permission
  error on Android 12).


1.9.7 2022-11-22
----------------

- Use Android 12 SplashScreen asset.

- Update Android icon.

- Add link to privacy policy.

- Update dependencies.


1.9.6 2021-10-10
----------------

- Disable native toasts on Android.  This fixes an issue with the
  `cordova-plugin-x-toast` plugin which causes the app to crash on
  devices running Android 11.  See also
  https://github.com/EddyVerbruggen/Toast-PhoneGap-Plugin/issues/136.

- Update dependencies.


1.9.5 2021-08-29
----------------

- Tuning page: Use "link" icon for changing multiple settings at once.

- Update dependencies.


1.9.4 2021-07-05
----------------

- Support serial USB-OTG connection on Amazon Fire OS.

- Improve handling of Web Bluetooth devices.

- Clean up leaderboard component.

- Update dependencies.


1.9.3 2021-04-25
----------------

- Remove references to Location settings and USB-OTG cables on platforms
  other than Android.

- Update iOS resources (thanks to Philipp Anné).

- Update dependencies.


1.9.2 2020-12-21
----------------

- Add new configuration setting _Connections: Demo Control Unit_.  Too
  many reviewers seem to mistake this app for some kind of motorsport
  manager game, so the demo mode will now be hidden by default.

- Update dependencies.


1.9.1 2020-11-18
----------------

- Improve Bluetooth LE connection handling.

- Update dependencies.


1.9.0 2020-10-05
----------------

- Use a menu toggle for switching sector times on and off.  Using
  slides for selecting the alternative leaderboard view was not
  intuitive to some users, and this also turned out to be a
  performance bottleneck, especially with older devices.

- Send CU command #7 when a car finishes a race or qualifying session.
  When using the Carrera® Position Tower, this will make the
  respective driver ID blink.

- Add notification for new race leader.

- Add separate notification for qualifying session ended.

- Fix occasional screen flicker on some devices, especially when
  on-screen keyboard is displayed.

- Update leaderboard sort order also when race is paused.

- Do not try to connect to ``undefined`` device after fresh install.

- Update dependencies.


1.8.1 2020-03-27
----------------

- Upgrade to Ionic 5.

- Upgrade to Angular 9.

- Minor UI improvements.


1.8.0 2019-11-14
----------------

- Require Android 5.1 or greater.

- Upgrade to Ionic 4/Angular 8 and dependencies.

- Add Angular service worker.

- Modernize UI.


1.7.2 2019-06-02
----------------

- Add Android 8.0 adaptive icons.

- Remove platform `cordova-electron`.

- Use `rxjs` pipeable operators.

- Update dependencies.

- Update README.


1.7.1 2019-04-04
----------------

- Add French translation (courtesy of nico12).

- Reduce use of "nagging" dialog boxes.

- Reduce duplicated speech messages.

- Add Web Bluetooth backend.

- Add basic `cordova-electron` support.

- Update dependencies.

- Update README.


1.7.0 2019-01-07
----------------

- Add SQLite storage engine to avoid uncaught ``QuotaExceededError``
  exceptions.  Note that this will effectively reset all user settings
  to default values.

- Improve iOS support (courtesy of softyde).

- Use correct number of laps for finishing lap-based races.

- Do not count pit stops if race is finished.

- Prevent startlight from wrapping at some screen sizes.

- Add translations for "No Connection".

- Improve startup message.

- Update licenses page.

- Update dependencies.


1.6.3 2018-11-30
----------------

- Improve error handling when scanning for BLE devices.

- Improve messages regarding Bluetooth and Location.

- Update dependencies.


1.6.2 2018-11-16
----------------

- Ignore lap times less than 500 ms.

- Automatically switch to full screen in landscape mode.

- Improve display of empty lap times.

- Volume buttons control media volume by default.

- Update translations (courtesy of Haarman, SdiF and Maikeru).

- Update dependencies.


1.6.1 2018-05-28
----------------

- Fix translations in ion-option elements.


1.6.0 2018-05-12
----------------

- Make connection settings configurable.

- Update dependencies.


1.5.2 2018-03-24
----------------

- Add Spanish translation (courtesy of Daphmi).


1.5.1 2018-01-12
----------------

- Add Italian translation by SdiF.

- Only show firmware version if a Control Unit is selected.

- Upgrade dependencies.


1.5.0 2017-10-23
----------------

- Add position up/down indicators.

- Track if car has started refueling.

- Close page menu when clicking checkbox items.

- Upgrade `ngx-translate` to v8.0.0.

- Update dependencies.


1.4.2 2017-10-10
----------------

- Fix sporadic `IonicToastProvider` runtime errors.

- Fix firmware version check for virtual CU button support.

- Convert `README` and `CHANGES` to Markdown format.

- Adjust `TTS` rate on iOS (courtesy of elliot2extreme).

- Remove `TypedArray.from()` for iOS compatibility (courtesy of
  elliot2extreme).

- Add icon and splash screen resources for iOS.

- Update icon and splash screen source images.

- Update dependencies.


1.4.1 2017-07-10
----------------

- Improve Bluetooth reconnect handling.

- Show three-digit CU firmware version.

- Upgrade `ionic-angular` to v3.5.0.


1.4.0 2017-06-16
----------------

- Add ESC key functionality.

- Add "CU mode" for tuning settings.

- Change tuning "link" icon to Ionicons "lock/unlock".

- Change CU firmware version to include period.

- Minor UI improvements.

- Update dependencies.


1.3.1 2017-05-06
----------------

- Hide scrollbars on Android 4.4.

- Improve leaderboard position ("colored stripe") display on Android 4.4.

- Improve handling of two-sector tracks.

- Improve `Toast` error handling.

- Upgrade to `ionic` v3.1.


1.3.0 2017-05-03
----------------

- Add support for "yellow flag" phase.

- Add pace car control button.

- Fix display issues with unset speed/brake/fuel values.

- Fix Android 4.4 SVG scaling issues.

- Fix Android 4.4 issues with multiple header buttons.

- Improve CU protocol logging.

- Default to demo mode when running in emulator or browser.


1.2.1 2017-04-23
----------------

- Fix "clear" icon background color issue.


1.2.0 2017-04-21
----------------

- Add Carrera® Check Lane support.

- Refactor and clean up settings.

- Optionally set number of drivers for race and qualifying.

- Fix Dutch translation typo (courtesy of Haarman).

- Upgrade to `ionic-native` v3.5.


1.1.0 2017-04-11
----------------

- Translate TTS notifications.

- Add speech toggle button to main page.

- Add confirm dialogs.

- Ignore section times reported by Check Lane.

- Upgrade to `ionic` v3.


1.0.2 2017-04-01
----------------

- Improve handling of default driver names.

- Increase tuning page font size.

- Add `IonicErrorHandler`.

- Add workaround for random toast errors.

- Add translation instructions to README.

- Upgrade to `ionic-native` v3.

- Upgrade to `ngx-translate` v6.


1.0.1 2017-03-20
----------------

- Update dependencies.

- Add Dutch translation by Haarman.

- Fix CSS "nowrap" spelling error.

- Move root page to separate file (fixes Webpack source map issues).


1.0.0 2017-01-09
----------------

- Change default colors.

- Refactor current/completed laps.

- Improve overall app stability.


0.9.8 2017-01-07
----------------

- Validate length of incoming CU data packets.


0.9.7 2017-01-06
----------------

- Update texts and translations.

- Close logging popover on "clear".

- Reorder event priorities.


0.9.6 2017-01-06
----------------

- Refactor lap counter and events.

- Rename "messages" to "notifications".

- Fix icon-only buttons.


0.9.5 2017-01-05
----------------

- Fix messages update.


0.9.4 2017-01-04
----------------

- Fix "fastest lap" event.


0.9.3 2017-01-04
----------------

- Select lap count mode.

- Update dependencies.


0.9.2 2017-01-03
----------------

- Various tuning page improvements.


0.9.1 2017-01-02
----------------

- Fix update of message settings.


0.9.0 2017-01-02
----------------

- Add internationalization support.

- Disable individual messages.

- Improve manual reconnect.


0.8.10 2016-12-30
-----------------

- Share log via email, etc.


0.8.9 2016-12-29
----------------

- Optimize font size in landscape mode.

- Use local storage provider for development.

- Upgrade to Ionic RC 4.


0.8.8 2016-12-17
----------------

- Ignore new cars when race is finished.

- Suppress "Final lap" message if race is stopped.

- Re-activate "False start" message.

- Update default messages.


0.8.7 2016-12-16
----------------

- Add option to use fixed driver positions.


0.8.6 2016-12-16
----------------

- Add option to stop timer when race is interrupted.

- Change "Lap Time" to "Last Lap" for consistency.


0.8.5 2016-12-08
----------------

- Filter Bluetooth devices.

- Upgrade `ionic-native`.

- Make builds more reproducible.


0.8.4 2016-12-03
----------------

- Reset driver mask after startlight and reconnect.

- Increase page load timeout.

- Upgrade `ionic-native`.


0.8.3 2016-11-29
----------------

- Fix Android 4.4 display issues.


0.8.2 2016-11-28
----------------

- Disable "stop" during practice.

- Do not close serial port when inactive.

- Use responsive layout for leaderboard.

- Improve reconnect handling.


0.8.1 2016-11-20
----------------

- Improve backend/connection handling.

- Update splash screen resources.


0.8.0 2016-11-19
----------------

- Upgrade to Ionic RC 3.

- Switch to `ionic-storage` for storing user settings.

- Add options to prematurely stop or restart a race.

- Add fullscreen option.

- Add "in pit" message.

- Various minor UI improvements.


0.7.3 2016-11-14
----------------

- Try to connect to last device on startup.

- Improve USB permission handling.

- Improve side menu UI.

- Upgrade to Ionic RC 2.


0.7.2 2016-11-02
----------------

- Show car number on leaderboard.

- Improve device orientation handling.

- Don't repeat last message when changing Speech settings.


0.7.1 2016-10-22
----------------

- Improve error handling when displaying log records.

- Remove clear button for driver input.


0.7.0 2016-10-21
----------------

- New side menu for improved connection access.

- Add custom storage provider (will reset user settings).

- Show driver names in colors page.

- Upgrade to Ionic RC 1.


0.6.4 2016-09-19
----------------

- Reset position tower and fuel on start.

- Add possible workaround for startlight update issues.

- Add default race time.

- Add chequered flag animation.


0.6.3 2016-09-14
----------------

- Fix lap-based race.


0.6.2 2016-09-12
----------------

- Improve startlight usability.

- Improve look of menus.


0.6.1 2016-09-09
----------------

- Race settings usability improvements.

- Upgrade `ionic-native`.


0.6.0 2016-09-08
----------------

- Require Android >= version 4.4.

- Add "finish all laps" option to race settings (a.k.a. "slotcar mode").

- Add "lock-all" slider to car setup.

- Add more speech notifications.

- Move controller color setup to settings menu.

- Use native `Toast` plugin.

- Various refactorings and smaller improvements.


0.5.1 2016-08-12
----------------

- Add `cordova-plugin-app-version` required by `ionic-native`.

- Add `android-versionCode` to `config.xml`.


0.5.0 2016-08-12
----------------

- Upgrade to Ionic 2 Beta 11.

- Use `TTS` plugin for speech notifications.

- Improve CU reconnect handling.

- Various refactorings and improvements.


0.4.6 2016-07-26
----------------

- Improve connection handling.


0.4.5 2016-06-29
----------------

- Upgrade to Ionic 2 Beta 10.

- Enable production mode when running on device.

- Fix lap counts starting at 1.


0.4.4 2016-06-28
----------------

- Add splash screen.

- Improve logging configuration.


0.4.3 2016-06-27
----------------

- Add settings page.

- Click log record for JSON view.

- Use `cordovarduino` plugin for serial connection.

- Various refactorings and improvements.


0.4.2 2016-06-22
----------------

- More "material" design.

- Update application icon.


0.4.1 2016-06-18
----------------

- Fix logging issues.

- Connection improvements.


0.4.0 2016-06-17
----------------

- Improve connection handling.

- Upgrade to Ionic 2 Beta 9.


0.3.1 2016-06-16
----------------

- More responsive layout.

- Mark overall best lap.

- Remove cancel buttons from dialogs.


0.3.0 2016-06-15
----------------

- Move to modal user interface.

- Setup race, qualifying, drivers and controller colors.

- Add `RaceControl` provider.

- Add global exception handler.


0.2.0 2016-06-10
----------------

- Choose connection at startup.

- Add serial connection support.

- Add application logging.


0.1.0 2016-06-04
----------------

- Implement basic practice/qualifying/race functionality.
