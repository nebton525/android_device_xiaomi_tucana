# android_device_xiaomi_tucana
For building OrangeFox (TWRP) for Xiaomi Mi Note 10

TWRP device tree for Xiaomi Mi Note 10

## What's working?
Pretty much everything

## Clone the repository
```git clone https://github.com/ItsBen12000/android_device_xiaomi_tucana.git device/xiaomi/tucana -b master```

## Build it
```build/envsetup.sh
export ALLOW_MISSING_DEPENDENCIES=true
export FOX_USE_TWRP_RECOVERY_IMAGE_BUILDER=1
export LC_ALL="C"
lunch omni_tucana-eng && mka recoveryimage```

## The build is located in
```/out/target/product/tucana/OrangeFox.zip```

## Other informations
- Precompiled Stock Kernel
