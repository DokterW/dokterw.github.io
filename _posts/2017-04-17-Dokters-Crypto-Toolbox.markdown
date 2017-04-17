---
layout: post
title:  "Dokter's Crypto Toolbox"
author: "Dokter Waldijk"
date:   2017-04-17
---
A humble collection of the crypto tools I have written in bash script so far.

## [shOTPad](https://github.com/DokterW/shOTPad)

shOTPad was the first major crypto bash script I wrote. I am fascinated by the [OTP](https://en.wikipedia.org/wiki/One-time_pad) crypto (not to be confused with one-time password) and wanted a challenge to see if I could make a functional electronic OTP. It took time to figure out the sequencing, but it was worth it.

## [LazyLudicr](https://github.com/DokterW/LazyLudicr)

As much as I value VeraCrypt I find the usage not so streamlined as MacOS's Disk Utility when creating encrypted disk images. After some research I found a simple way to create an encrypted disk image using LUKS. All it takes is a few clicks and you have created an encrypted disk image and mounted it.

## [reSHsync](https://github.com/DokterW/reSHsync)

If you use Resilio Sync as extensively as I do it's nice to keep track of your folder keys, especially if you are installing Resilio Sync to a new computer or server. The list is of course encrypted using mcrypt.
