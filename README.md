# HP ZBOOK 15 G2

## Hardware

- CPU: Intel Core I7 4810MQ
- IGPU: Intel HD Graphics 4600
- DGPU: NVIDIA QUADRO K2100M

### Ventura


![Ventura](https://github.com/stivengjinaj/hp-zbook-15-g2/blob/main/Ventura.png)


## What's working:

Basically everything.
I have used Monterey (heavily) for 2 years daily and it worked perfectly smooth.
Recently installed Ventura. Until now, everything works:

1) Graphics acceleration with OCLP
2) NVIDIA disabled
3) Wi-fi working
4) Bluetooth working
5) Keyboard, mouse/trackpad with gestures working
6) Battery readings
7) Sleep

## Not working/Issues:

1) Trackpad after sleep
2) SD Card reader
3) Disabling DGPU with SSDT works but fan spins faster than it should even though the pc is way cooler than without the SSDT. Until further testing, better use `-wegnoegpu` without SSDT.
4) ecc. need testing

## Sequoia:
Added test EFI for macOS 15 Sequoia. Graphics acceleration with OCLP 2.1.0 nightly.
Seems to work fine until now. Trackpad works after sleep, but overall is not as smooth as
in Monterey and Ventura. Other things need testing.
