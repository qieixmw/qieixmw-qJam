![qieixmw-qJam Main Menu](./media/pictures/qieixmw-qJam_banner.jpg)
# 😻 qieixmw-qJam
qJam is a universal ESP32 firmware that has many offensive features.
For now it only supports regular ESP32's, soon there will be more support for more devices.
# 🔗 How to install
### Easiest way to install is to use my Web Flasher!
### Link: https://qieixmw.github.io/flasher (SOON)
Alternatively, you can download the latest binary from releases or actions and flash locally using esptool.py
```sh
esptool.py --port COM0 write_flash 0x00000 qJam-<device>.bin
```
