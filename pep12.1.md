## PixelExperiencePlus 12.1
### Getting started
You can also refer to this repository: <https://github.com/PixelExperience/manifest>  
To initialize your local repository, use this command:  
For PixelExperiencePlus 12.1:  
```bash
repo init -u https://github.com/PixelExperience/manifest -b twelve-plus --depth=1
```
Then to sync up:  
```bash
repo sync
```
### Adding some repositories
Download or git clone these repositories and add to your peplus project.(use pep-12.1 branch)  
<https://github.com/kindle4jerry/android_device_nubia_nx563j>  
<https://github.com/kindle4jerry/android_device_nubia_msm8998-common>  
<https://github.com/kindle4jerry/android_kernel_nubia_msm8998>  
<https://github.com/kindle4jerry/android_vendor_nubia>(Just use nx563j and msm8998-common is enough)  
### Patching
This repository provides some patches for PixelExperiencePlus build.  
Use "git am" to apply these patches.  
### Building
```bash
. build/envsetup.sh
lunch aosp_nx563j-user
mka bacon
```

