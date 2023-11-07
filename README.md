# PixelPlusUI GSI

## Build
To get started with building PixelPlusUI GSI, you'll need to get familiar with [Git and Repo](https://source.android.com/source/using-repo.html) as well as [How to build a GSI](https://github.com/phhusson/treble_experimentations/wiki/How-to-build-a-GSI%3F).
- Create a new working directory for your PixelPlusUI build and navigate to it:
    ```
    mkdir ppui; cd ppui
    ```
- Clone this repo:
    ```
    git clone https://github.com/changanmoon/treble_build_ppui -b tiramisu
    ```
- Finally, start the build script:
    ```
    bash treble_build_ppui/build.sh
    ```

## Notes
- This repository is **still under construction**. (This line will be removed if the repository is ready for public use.)
- If bluetooth calls or bluetooth media do not work well for you, make sure you have the "Use System Wide BT HAL" checkbox enabled on the Misc page of Treble App. If not, enable and reboot.
- If you have a non-Samsung device with a Qualcomm chipset and VoLTE isn't working with the default IMS package provided by Treble App, try installing this [alternative IMS package](https://treble.phh.me/stable/ims-caf-s.apk).
- I'm not an expert in building an Android ROM, so please don't criticize me. :)

## Credits
Special thanks to these people because this repository would not be possible without their efforts on other projects:
- [PixelPlusUI Team](https://github.com/PixelPlusUI)
- [phhusson](https://github.com/phhusson)
- [ponces](https://github.com/ponces)
- [AndyYan](https://github.com/AndyCGYan)
- [eremitein](https://github.com/eremitein)
- [kdrag0n](https://github.com/kdrag0n)
- [Peter Cai](https://github.com/PeterCxy)
- [haridhayal11](https://github.com/haridhayal11)
- [sooti](https://github.com/sooti)
- [Iceows](https://github.com/Iceows)
- [ChonDoit](https://github.com/ChonDoit)
