libjansson for iOS
=================
Build libjansson for iOS development.  
This script will generate static library for armv7 armv7s arm64 and x86_64.  
Bitcode support.  
  
Script only, please download libjansson from here: http://www.digip.org/jansson 
Tested Xcode 9.2 on macOS 10.12.6(Sierra) 

Usage
=================
```
curl -O http://www.digip.org/jansson/releases/jansson-2.10.tar.gz
tar xf jansson-2.10.tar.gz
cd jansson-2.10
curl https://raw.githubusercontent.com/matsurowa25/build-libjansson-iOS/master/build_libjansson_dist.sh |bash
......
```
Find the result libcurl-ios-dist on your home.
