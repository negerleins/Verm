# Verm [App] : blacksmith(@negerleins)

| `⚠️`  | `❕`  | Indication(s)                              |
| :-- | :-- | :--------------------------------------------- |
| `❓`  | `❗`  | Please read carefully before installation. | 

---
### ⚠️This application is only for a select few ⚠️
 - *[⚠️] : **Installation**; is not permitted without an invitation.*
 - *[❕] : **This repository**; will be public indefinitely for the future.*
 - *[❓] : **This application**; has a select few tweak(s) that do not abide by certain regulations.*
 - *[❓] : **This application**; has a **Private Backend Infrastructure (PBI)** for all feature(s).*
 - *[❗] : **Disclaimer of Liability:** I, as the creator, **disclaim** any **responsibility** for the **misuse** of this **application**.*
---
#### Installation

- **Install VermApp for Android (🤖)**
> https://github.com/negerleins/Verm/releases/latest/download/VermApp.apk
Using [adb](https://developer.android.com/tools/adb) *(Android Debug Bridge)
1. `Connect your device to a computer` *(recommended)*.
2. `Allow USB debugging` *(recommended)*.
3. `Install the adb-cli` *(recommended)*.

4. List all avaliable devices.
```bash
  ❯ adb devices
  List of devices attached
  NS18JASUZX	device
  # We will assume "NS18JASUZX" is the device connected.
```
5. Check shell connectivity.
```bash
  ❯ adb -s NS18JASUZX shell
  a13:/ $ whoami
  shell
  # Expected result above "shell", after that then exit.
  a13:/ $ exit
``` 
6. Download our APK, and install it.
```bash
  ❯ wget https://github.com/negerleins/Verm/releases/latest/download/VermApp.apk
  XXXX-XX-XX XX:XX:XX (XX MB/s) - ‘VermApp.apk’ saved [XX/XX]
  ❯ adb -s NS18JASUZX install VermApp.apk
  Performing Streamed Install
  Success
  # Expected result, "Success"
``` 
- **Install VermApp for iOS ()**
> https://github.com/negerleins/Verm/releases/latest/download/VermApp.ipa
Using [TrollStore](https://github.com/opa334/TrollStore) *(Fake-signer)
1. `Download our IPA from the GitHub` *(recommended)*.
2. `Press, "Open in "TrollStore"`.
3. `Finally, press "Install"`.
- Yeah guys it's not that hard.
Using [appdb](https://appdb.to/) *(Developer Certificate Needed.)
