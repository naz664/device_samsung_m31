## PBRP device tree for the Samsung M315F.

## How to compile

1. Set up the build environment following instructions from [here](https://github.com/PitchBlackRecoveryProject/manifest_pb)
2. Clone the device tree in the root of PBRP source:
```
git clone https://github.com/naz664/device_samsung_m31.git device/samsung/m31 -b PBRP-12
```
3. To build:
```
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_m31-eng && mka recoveryimage -j$(nproc --all)
```
## Credits
- [Yilliee](https://github.com/Yilliee)
- [Soulr344](https://github.com/soulr344)
