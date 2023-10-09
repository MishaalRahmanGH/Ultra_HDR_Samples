# Ultra HDR Samples

This repository contains Ultra HDR (JPEG_R) photo samples captured on a Pixel 6 Pro running Android 14 QPR1 Beta 2 with Google Camera version 9.1.098 extracted from a Pixel 8 Pro. The samples are divided into two directories: "Originals" and "SDR Emulation".

"Originals" contains the original photos captured by [Mishaal Rahman](https://linktr.ee/MishaalRahman) on his Pixel 6 Pro. "SDR Emulation" contains two variants of each photo from the "Originals" directory. Display analyst [Dylan Raga](https://twitter.com/dylan_raga) extracted the gain map from the "Originals" images, took the highest pixel value in the gain map (usually 255 = white), reduced the maximum pixel level of the original image to half (128), and added the gain map pixel values to the "_base" images to create the "_hdr" images. The following graphic shows how an HDR gain map can be added to the "_base" SDR image to create the "_hdr" HDR image.

![Ultra_HDR_Comparison_5_Watermarked](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Ultra_HDR_Comparison_5_Watermarked.png?raw=true)

(More of these graphics are available on the accompanying [*Android Police* article](https://www.androidpolice.com/android-14-ultra-hdr-hands-on/).)

The purpose of these modifications is to emulate what an SDR image *should* look like on an SDR display (as shown on an SDR display) as well as what an HDR image *should* look like on an HDR display (as shown on an SDR display). 

If you are viewing this repository on a device with an HDR-capable display and an operating system/browser that supports Ultra HDR, then you should be able to view the "Originals" (embedded below and found in the "Originals" directory) in HDR. The following devices/OSes/browsers have been tested:

* A Windows 11 PC, with Google Chrome, connected to an LG 42C2
* A 16" M2 MacBook Pro, with Arc
* A Pixel 7 Pro, with Google Chrome, running Android 14

(HDR image support on Android requires the Android 14 OS, a device that supports [SDR dimming](https://www.esper.io/blog/android-sdr-dimming) [eg. Pixel 7 and later], and a recent version of [any Chromium-based browser](https://chromium.googlesource.com/chromium/src/+/4f28fb30555f5c211d4cbb760a87043264808dee).)

![Ultra_HDR_Samples_Originals_01](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_01.jpg?raw=true)
![Ultra_HDR_Samples_Originals_02](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_02.jpg?raw=true)
![Ultra_HDR_Samples_Originals_03](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_03.jpg?raw=true)
![Ultra_HDR_Samples_Originals_04](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_04.jpg?raw=true)
![Ultra_HDR_Samples_Originals_05](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_05.jpg?raw=true)
![Ultra_HDR_Samples_Originals_06](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_06.jpg?raw=true)
![Ultra_HDR_Samples_Originals_07](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_07.jpg?raw=true)
![Ultra_HDR_Samples_Originals_08](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_08.jpg?raw=true)
![Ultra_HDR_Samples_Originals_09](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_09.jpg?raw=true)
![Ultra_HDR_Samples_Originals_10](https://github.com/MishaalRahmanGH/Ultra_HDR_Samples/blob/main/Originals/Ultra_HDR_Samples_Originals_10.jpg?raw=true)
