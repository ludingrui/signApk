# Apk/Zip signing tool pulled out of the AOSP
20130124
Oracle Java和OpenJDK环境都可以用
测试环境Ubuntu16.04 64位系统OpenJDK8

## Source

The code is taken as is from build/tools/signapk/SignApk.java from the git 
repo at: https://android.googlesource.com/platform/build
and is just here for convenient access along with a prebuilt jarfile.

## Usage

example:

java -jar signapk.jar -w testkey.x509.pem testkey.pk8 OTA.zip OTA_signed.zip
