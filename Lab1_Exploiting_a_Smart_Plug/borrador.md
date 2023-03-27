# UPRM-PandaHat

## Lab 1: Exploiting a Smart Plug

### Reverse Engineering the mobile Application

Utilized JADX to navigate the Android application source code to find  where the encryption key is located. 

``` Jadx Command: $ jadx-gui homemate.apk ```

Found SecurityAes.java class located in the package homateap.orvibo.com.security, which declared methods "createPassword", "decryptByte", "decryptByteKey", "encryptByte" and "encryptByteKey". The code for these methods can be found in the native library libHomeMate_Security.so that can be located in the lib/armeabi and lib/x86 directories which were found by extracting the application binary.

```
    $ unzip HomeMate.apk -d homemate
    $ cd homemate/lib/armeabi/
    $ ls libHomeMate_Security.so
```

Reverse Engineering the native library in ARM utilizing Binary Ninja Cloud.



