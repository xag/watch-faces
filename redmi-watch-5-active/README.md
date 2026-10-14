# Installing a face on the Redmi Watch 5 Active

Mi Fitness only installs faces from Xiaomi's own catalogue. A face from here goes on through Gadgetbridge, a free Android app that talks to the watch in Mi Fitness's place. There is no way to do it from an iPhone.

The first time takes about twenty minutes; after that, installing a face is steps 8 and 9 only.

## Before you start

- **Never unpair the watch in Mi Fitness** and never reset it: that changes the key Gadgetbridge needs in step 1, and you would have to start again.
- **Make room:** the watch keeps three downloaded faces. To make room, delete the ones you no longer want: press and hold the face on the watch, then delete it.
- **Menu names:** the menus below may appear in your phone's language, and their names may differ slightly from what is written here.

## Steps

1. **Get the watch's key from Mi Fitness.**
   - In Mi Fitness, go to Profile, then About this app, and tap the app's icon five times. A log is saved as a zip file in the Download/wearablelog folder of your phone.
   - Unzip it, open XiaomiFit.main.log with a text viewer and search for `token`. The key is the 32 letters and digits after it: copy them.
   - Also note the watch's address, six pairs of characters like `A1:B2:C3:D4:E5:F6`. It is on the watch under Settings, About.
2. **Pause Mi Fitness.** In the phone's Settings, open Apps, then Mi Fitness, and tap Force stop. Then in its Permissions, set Nearby devices to Don't allow. Do not uninstall it.
3. **Forget the watch in Bluetooth.** In the phone's Bluetooth settings, forget the watch.
4. **Install Gadgetbridge.** Install F-Droid from [f-droid.org](https://f-droid.org), then install Gadgetbridge from inside F-Droid.
5. **Add the watch.** In Gadgetbridge, open the menu, then Debug, then Add test device manually. Choose Redmi Watch 5 Active and type the watch's address. Accept the pairing on the phone and on the watch.
6. **Keep it connected.** Still in the Debug menu, make the watch a companion device.
7. **Give it the key.** Tap the gear under the watch in Gadgetbridge, then Authentication, then Auth key. Type `0x` followed by the 32 characters from step 1, without pressing Enter, and go back. Gadgetbridge connects to the watch.
8. **Install a face.**
   - Download the face's .bin file to the phone.
   - Open it from the Files app and choose to open it with Gadgetbridge's installer.
   - Gadgetbridge says the face matches this watch. Tick "I understand the risk" and tap Install. Do this for each face you want.
9. **Choose it on the watch.** Press and hold the current face and swipe to the new one.

## If something goes wrong

- **The watch reboots** when a face is chosen: it comes back with its usual face and nothing is lost. Delete that face and say which one it was.
- **Going back to Mi Fitness:** give Mi Fitness its Nearby devices permission back. Nobody has reported yet whether the faces from here stay on the watch after that.
