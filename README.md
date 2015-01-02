Android Platform Manifest

- **Get the source:**

        $ mkdir DEANDROID
        $ cd DEANDROID
        $ repo init -u https://github.com/dsouleles/platform_manifest -b deandroid
        $ repo sync

- **Update the source:**

        $ cd DEANDROID
        $ repo sync

- **Building**

        $ source build/envsetup.sh
        $ lunch aosp_<device>-userdebug (aosp_flounder-userdebug)
        $ make -jn otapackage

- **Cleaning**

        $ source build/envsetup.sh
        $ make clean

