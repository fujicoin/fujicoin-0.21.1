Gitian building Mac OS SDK
==========================

Get Xcode-11.3.1-11C505-extracted-SDK-with-libcxx-headers.tar.gz
--------------------------

Get `Xcode-11.3.1-11C505-extracted-SDK-with-libcxx-headers.tar.gz` from the following site.
[https://github.com/decryp2kanon/apple_sdk/releases/download/200923/Xcode-11.3.1-11C505-extracted-SDK-with-libcxx-headers.tar.gz](https://github.com/decryp2kanon/apple_sdk/releases/download/200923/Xcode-11.3.1-11C505-extracted-SDK-with-libcxx-headers.tar.gz)


Copy SDK to Gitian VM:
----------------------

Login to the VM and:

```bash
mkdir -p gitian-builder/inputs
mv Xcode-11.3.1-11C505-extracted-SDK-with-libcxx-headers.tar.gz gitian-builder/inputs
```

