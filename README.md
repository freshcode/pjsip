
# PJSIP

WARNING: This branch is locked to the latest 2.5.5 release of PJSIP; you should only be using this if your project
is absolutely required to use this version of the library.  This version has been modified to include OPUS.

We highly recommend you use the latest library from https://github.com/chebur/pjsip instead.

PJSIP is a free and open source multimedia communication library written in C language implementing standard based protocols such as SIP, SDP, RTP, STUN, TURN, and ICE.

## Features

- Supported platforms: iOS8+
- Supported architectures: armv7, armv7s, arm64, i386, x86_64
- IPv6 support
- OpenSSL support provided by the [OpenSSL-for-iPhone](https://github.com/x2on/OpenSSL-for-iPhone) build script and the [OpenSSL-Universal](https://github.com/krzyzanowskim/OpenSSL) pod
- Video support provided by the [OpenH264](https://github.com/cisco/openh264)
- OPUS now supported - this pod provides libopus

## Installation

Add the following line to your `Podfile` and run `pod install` command.

```
pod 'pjsip', :git => 'https://github.com/freshcode/pjsip.git', :tag => '2.5.5.6'
```

## Example

See [example](example/ipjsystest) folder for integration example

## Build manually

1. Run `brew install nasm` to build openh264.
1. Run [build.sh](build.sh).
2. Drag generated libraries and headers files into your xcode project.


