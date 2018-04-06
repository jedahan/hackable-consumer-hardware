# Two decades of hackable consumer hardware products

Here is my personal list of amazing consumer devices that are ubiquitous, cheap and have significant hacking values, many accidentally and unintended by the manufacturers.

The advent of custom firmwares have pushed the capabilities and use cases of those devices to far beyond their intended original use, extending their life way beyond their official support lifetime. Normally, custom firmwares mean it does it better/more customizable, but sometimes it means "oh what?"

If you are a student with limited budget to spend on hobbies and want to start working on embedded devices, many of the devices here are great starting devices: That was how I started out.

## Adding a device/hack you know

Please feel free to make pull requests :) 

To make it to this list, with a few exceptions, there are several rules-of-thumb:

1. All revisions of such product/model has to be hackable. If only earlier revisions are exploitable -- for example, many routers that have later revisions with less RAM and unable to run the Custom FW -- it can't count.
2. The latest firmware of such product/model should not be able to completely prevent the user from hacking it. The PS Vita or the Verizon Pixel 1, for example, have patched software that prevents jailbreaking, so that doesn't count.
3. If there exists a jailbroken firmware or development features from the manufacturer, that firmware has to be open-source. At the very least, it has to offer substaintial development features. Hacking doesn't mean much if only the manufacturer can "hack" it. For example, the Analogue Super Nt *definitely* doesn't count.

In other words, rule 1 and 2 mean hacking such product has to be a guarranteed goal, not a lottery when you read its serial number/manufactured date/firmware version. You shouldn't have to pray for a device you purchased to be hackable. For wildly popular and easy-to-check devices, such as iPhones or Kindles, these restrictions can be somewhat less strict.


## Table of hackable hardware 

**UB = Unbrickable**: Is this device practically unbrickable/Extremely low risk when installing the custom FW? Y = Yes, N = No, HW = Needs additional hardware to unbrick. \
**Resources**: Links to interesting trivia you might not know. See below. \
**Custom firmware**: + = There are more than one choice.

| Device 	| Released 	| Why 	| Custom firmware 	| UB 	| Resources 	|
|----------	|---------------	|-----------	|-----------------	|----------	|----------	|
| **Laptops**	| 	| 	| 	| 	| 	|
| Chromebooks	| 2011 -	| Linux native. Many run Windows, ME_Cleaner	| [MrChromebox](http://MrChromebox.tech)+	| HW	| chrome	|
| Acer C720	| 2013	| ... + Cheap, replacable ssd, runs OS X	| [MrChromebox](http://MrChromebox.tech)+	| HW	| chrome, peppy	|
| Dell Chromebook 13	| 2015	| ... + IPS 1080p, replacable ssd, big trackpad, backlit kb, aluminum build	| [MrChromebox](http://MrChromebox.tech)+	| HW	| chrome, lulu	|
| Thinkpads	| Various	| Ubiquity, run coreboot vanilla, ME_Cleaner, HW upgradable	| [Coreboot](https://www.coreboot.org/Supported_Motherboards)	| HW	| thinkpad	|
| Thinkpad X200	| 2009	| ... + runs libreboot, ME can be disabled entirely	| [Libreboot](https://libreboot.org/docs/hcl/x200.html)+	| HW	| thinkpad, libreboot	|
| **Routers**	| 	| 	| 	| 	| 	|
| Home routers	| 2002 -	| Many run OpenWRT, DD-WRT, Tomato, Gargoyle	| [OpenWRT](https://openwrt.org/)+	| Y/HW	| router3rd	|
| Linksys WRT54GL	| 2002	| ... + First router, favored by hams, does mesh	| [OpenWRT](https://openwrt.org/)+	| Y	| router3rd	|
| **Game Consoles**	| 	| 	| 	| 	| 	|
| Sony PS3	| 2006	| Homebrew, distributed computing, OtherOS	| [Linux](https://en.wikipedia.org/wiki/OtherOS)+	| Y	| otheros	|
| Microsoft OG XBOX	| 2006	| X86, cheap, very good emulators	| [EvoX](http://www.xbox-hq.com/html/xbox-tutorials-3.html)+	| Y	| ogxbox	|
| Sony PSP	| 2004	| Homebrew, portable, emulators	| [Homebrew](https://en.wikipedia.org/wiki/PlayStation_Portable_homebrew)	| ?	| psp	|
| Nintendo Wii	| 2006	| Homebrew, ext USB	| [Homebrew Channel](http://wiibrew.org/wiki/Homebrew_Channel)	| N	| hackmii	|
| Nintendo NES/SNES mini	| 2016	| Can add more games, simple	| None	| Y	| snesmini	|
| Microsoft Kinect	| 2010	| SDK Officially supported by MS	| [Kinect SDK](https://developer.microsoft.com/en-us/windows/kinect)	| Y	| kinect	|
| **Ereaders**	| 	| 	| 	| 	| 	|
| B&N Nook Touch	| 2012	| E-ink, relatively open, Android 2.2	| [Android](https://forum.xda-developers.com/nook-touch)	| Y	| nook	|
| Amazon Kindle (Some?)	| 2007	| E-ink, ubiquity	| [Jailbreak](https://wiki.mobileread.com/wiki/Kindle_Hacks_Information)	| ?	| kindle	|
| **MP3 Players**	| 	| 	| 	| 	| 	|
| Rockbox devices	| Various	| Runs Doom, plays lossless, drag-n-drop	| [Rockbox](http://rockbox.org/)	| Y	| rockbox	|
| iRiver H300 series	| ?	| ... + Big HDD	| [Rockbox](http://rockbox.org/)	| Y	| rockbox	|
| iPods/Nanos older gens	| 2001	| ... + Ubiquity, big HDD, moddable, accessories 	| [Rockbox](http://rockbox.org/)	| Y	| rockbox	|
| Sandisk Salsa Clip	| ?	| ... + Compact, SD card support 	| [Rockbox](http://rockbox.org/)	| Y	| rockbox	|
| iPod Touch 1/2G	| 2007	| Ubiquity, usefulness, touchscreen 	| [whited00r](http://www.whited00r.com/index?lang=en)	| Y	| whited00r	|
| iPod Touch 3G	| ?	| Ubiquity, usefulness, touchscreen 	| [grayd00r](http://www.grayd00r.com)	| Y	| grayd00r	|
| **Media Centers**	| 	| Media Centers and Streaming boxes	| 	| 	| 	|
| SteamLink	| 2015	| Very cheap, game controllers	| [Custom Apps](https://www.reddit.com/r/Steam_Link/)	| Y	| steamlink	|
| **Digital Cameras**	| 	| 	| 	| 	| 	|
| Canon DSLR	| Various	| Ubiquity, lenses 	| [Magic Lantern](http://www.magiclantern.fm)	| Y	| magiclantern	|
| Canon Point-n-Shoot	| Various	| Cheap, get the job done 	| [CHDK](http://chdk.wikia.com/)	| Y	| chdk	|
| Nikon DSLR	| Various	| Ubiquity, lenses 	| [Custom FW](https://nikonhacker.com/)	| ?	| nikonhaxxor	|
| Sony Mirrorless	| Various	| Ubiquity, lenses, Android 	| [Open Memories](https://github.com/ma1co/OpenMemories-Tweak)	| Y	| openmem	|
| **Dev boards**	| 	| 	| 	| 	| 	|
| Single Board Computers	| Various	| Affordable, runs Linux	| Linux+	| Y	| sbc	|
| Raspberry Pi 3	| 2017	| ... + Versatile, ubiquity, affordable, amazing and friendly community	| [Raspbian](https://www.raspberrypi.org/downloads/raspbian/)+	| Y	| 	|
| Raspberry Pi Zero W	| 2017	| ... + Very cheap, very small	| [Raspbian](https://www.raspberrypi.org/downloads/raspbian/)+	| Y	| 	|
| Arduino	| 2010 -	| Amazing community and support, wiring	| Bare metal	| Y	| arduino	|
| Arduino Uno	| 2010	| ... + Powerful enough, ubiquity, has enough IOs	| Bare Metal	| Y	| arduinouno	|
| ESP	| ?	| Very cheap and small, wiring	| Bare metal	| Y	| 	|
| ESP8266	| ?	| ... + Extremely cheap, many crazy projects available	| Bare metal	| Y	| esp8266	|
| ESP32	| ?	| ... + Powerful CPU, Wifi/BLE	| Bare metal	| Y	| esp32	|
| HC-0x Bluetooth	| ?	| Very cheap, does Bluetooth	| [RN42 Firmware](https://www.youtube.com/watch?v=BBqsVKMYz1I)	| N	| hc0xbt	|
| **Cars**	| 	| 	| 	| 	| 	|
| Comma.ai supported cars	| Various	| Autonomous driving/assistance	| [OpenPilot](https://github.com/commaai/openpilot)	| N	| commaai	|
| **Others**	| 	| 	| 	| 	| 	|
| Eye-Fi SD cards	| ?	| Small, Wifi, storage	| [Magic Lantern](http://magiclantern.wikia.com/wiki/Eye-Fi)	| ?	| eyefi	|
| Xiaomi Dafang Camera	| 2017	| Wifi, storage, streaming	| [Enhanced Firmware](https://hackernoon.com/hacking-a-25-iot-camera-to-do-more-than-its-worth-41a8d4dc805c)	| Y	| dafang	|
| TS100 soldering iron	| ?	| Solder things, small, fast to heat up	| [Open Firmware](https://github.com/Ralim/ts100)	| ?	| ts100	|
| T-962 Reflow Oven	| ?	| Reflows your boards, cheap, flow curves	| [Open Firmware](https://github.com/UnifiedEngineering/T-962-improvements)	| ?	| t962	|
| TI Calculator	| ?	| Ubiquity, education, slow, fun	| [TiCalc](https://www.ticalc.org/)	| Y	| ticalc	|
| Chumby, Insignia Infocast	| 2007	| Pioneering device to promote hacking	| [Linux](http://wiki.chumby.com/)	| Y	| chumby	|
| **Phones & Tablets**	| 	| *Note: Outdated as of yesteryear. Interesting but not useful, likely.*	| 	| 	| 	|
| Nokia N900	| 2009	| Runs Maemo GNU/Linux, has a keyboard	| Stock	| Y	| n900	|
| Nexus 5, OnePlus One	| 2013	| Tons of custom OSes	| Android+	| Y	| hammerhead, bacon	|
| HTC HD2	| 2009	| Runs every OS imaginable: Win 6-8, Android, etc.	| Windows Mobile+	| Y	| hd2	|
| Fairphone 2	| 2015	| Designed to be opened, swappable modules	| Android	| Y	| fp2	|
| Palm Pre 1-3	| 2009	| Runs WebOS, friendly to develop	| [WebOS Internals](http://www.webos-internals.org/)	| Y	| palmpre	|
| HP Touchpad	| 2011	| """Firesale""", runs many Android versions	| [WebOS Internals](http://www.webos-internals.org/)	| Y	| tenderlion	|
| Nexus 7	| 2013	| De facto Android tablet, runs many exotic OS	| Android+	| Y	| nexus7	|
| iPhones/iPads	| 2008	| Ubiquity, runs iOS, very active community	| [JB FW/Cydia](https://cydia.saurik.com/)	| Y	| iphone	|
| Siemens SL45	| 2001	| First phone to play MP3	| [Hacked FW](https://en.wikipedia.org/wiki/Siemens_SL45#Firmware)	| ?	| sl45	|
| 'XDA' HTC devices	| 2002	| XDA-developers was born from there	| [Hacked FW](https://en.wikipedia.org/wiki/XDA_Developers)	| ?	| xda	|

Hacks that transforms devices
--

Every once in a while, there is an amazing hack that comes out and brings a completely new function to a device. Here are my favorites.

| Device 	| Original Fn 	| New function 	| Enablement 	|  Resources 	|
|----------	|---------------	|-----------	|-----------------	|----------	|
| NVIDIA GPU	| Gaming	| Scientific research, Cryptocurrency revolution, AI/ML revolution 	| [CUDA](https://en.wikipedia.org/wiki/CUDA)+	|  gpgpu	|
| Sony PS3	| Game console	| Super computer	| [Linux](https://en.wikipedia.org/wiki/PlayStation_3_cluster)	| ps3hpc	|
| XBox	| Game console	| Media center	| [Kodi](https://kodi.tv/)	| xbmc	|
| Kinect	| Gaming peripheral	| 3D scanner/modeller	| [Kinect SDK](https://developer.microsoft.com/en-us/windows/kinect)	| kinect	|
| Amazon Dash button	| Order stuff	| Smarthome generic button	| [OpenWRT](https://github.com/misc0110/dash-button/tree/master/openwrt)	| dashbtn	|
| Raspberry Pi	| Education	| Adblock router	| [Pi-hole](https://pi-hole.net/)+	| pihole	|
| Raspberry Pi	| Education	| Android Auto head unit	| [OpenAuto](https://github.com/f1xpl/openauto)/[Crankshaft](https://getcrankshaft.com)+	| aauto	|
| Raspberry Pi	| Education	| Game console	| [libretro](https://www.libretro.com/)/[RetroPie](https://retropie.org.uk/)	| retropie	|


Resources
--

- chrome: [Subreddit](https://www.reddit.com/r/chrultrabook/), [Remove Intel ME automatically](http://www.tnhh.net/posts/ezpi4me-intel-me-be-gone.html), [Ubuntu-based distro (most distros work OOB)](https://galliumos.org/) 
- chrome_unbrick: [Flashrom](https://flashrom.org/Flashrom), [Unbrick with Raspberry Pi](http://www.tnhh.net/posts/unbricking-chromebook-with-beaglebone.html)
- peppy: [Runs macOS](https://coolstar.org/chromebook/)
- thinkpad: [You can upgrade their screens and even motherboards](https://www.reddit.com/r/thinkpad/)
- thinkpad_unbrick: Same as chrome_unbrick
- router3rd: To look up specs, try [wikidevi](https://wikidevi.com/wiki/Main_Page). There are tons of other firmwares such as DD-WRT, ASUS merlin, [tomato and other derrivatives](https://en.wikipedia.org/wiki/Tomato_(firmware)), Gargoyle-router
- router3rd_unbrick: Depends on the model, you have to consult openwrt wiki
- otheros: [Geohot's bad rap](https://www.youtube.com/watch?v=9iUvuaChDEg), [PS3 fail0verflow talk](https://www.youtube.com/watch?v=LP1t_pzxKyE)
- ogxbox: [Bunnie's site](http://hackingthexbox.com/), Modern Vintage Gamer's series [-1-](https://youtu.be/otysqrBT7ko), [-2-](https://www.youtube.com/watch?v=x7FmelyC70Y)
- psp: 
- hackmii: [Wiibrew](http://wiibrew.org/)
- kinect: [adafruit kinect bounty](https://blog.adafruit.com/2010/11/04/the-open-kinect-project-the-ok-prize-get-1000-bounty-for-kinect-for-xbox-360-open-source-drivers/)
- nook: [HaD](https://hackaday.com/tag/nook/)
- kindle: [HaD](https://hackaday.com/category/kindle-hacks/)
- xbmc: [April Fools post](https://kodi.tv/article/kodi-no-more-april-fools)
- commaai: [OpenPilot supported carts list](https://github.com/commaai/openpilot#supported-cars)
- aauto: [crankshaft subreddit](https://www.reddit.com/r/crankshaft), [aasdk](https://github.com/f1xpl/aasdk), [android version](https://play.google.com/store/apps/details?id=gb.xxy.hr&hl=en)
- retropie: The Pi works with most controllers, even wireless ones.


# Long version

## Laptops


### Acer Chromebook C720 (2013)

This laptop is cheap, runs cool, the battery lasts forever, and it runs every operating system ever. You can flash [coreboot](https://mrchromebox.tech/), an open-source UEFI BIOS for it and it will run Linux, Windows flawlessly, and even macOS. It is also extremely easy to open up. Virtually unbrickable.

### Thinkpad X200 (2009)

For the fans of truly-free BIOS. It runs [libreboot](https://libreboot.org/docs/hcl/x200.html) which has no binary blobs and it seems like the Management Engine can be partially disabled.

### The rest and resources

- [Other Thinkpads](https://libreboot.org/docs/hcl/)
- [Other Chromebooks](https://www.reddit.com/r/chrultrabook/). 
- **Where to learn more**: Search for Coreboot, GalliumOS, chrultrabook


## Routers

Routers are the exception to the norm. Most of the routers available on the market since 2002 seem to be capable of running custom firmwares and they usually don't have any protection against doing so. They make fantastic embedded Linux devices before Single Board Computers (SBC) such as the Raspberry Pi become mainstream.

### Linksys WRT54G (2002)

The router that started it all. It was sued for violating the GPLv2 license. Linksys had to publish the source code for the router, and the rest was history. It is still now being used and trusted by many many people, 15 years after its first release. It can run mesh network, has a huge ham fanbase, and has interchangable antennas. What's not to like?

## Game Consoles & Handhelds

### Sony PS3 (2006)

The PS3 was advertised as a console that can run Linux, and [could do some serious computing](PlayStation 3 cluster). Then Sony removed the functionality. Then people got mad and added it back again. Then some guy by the name Geohot got sued and [made a video for it](https://www.youtube.com/watch?v=9iUvuaChDEg). 

### Microsoft Original Xbox (2001)

The Original XBox is a x86 PC in disguise and has [a book dedicated to hacking it](http://hackingthexbox.com/). Even being a 16 year old system, it is probably still one of the best cheap readymade systems that you could buy for retro emulation. The Raspberry Pi is also a good emulation system, except for the cumbersome controller set-up.

### Other notable devices

- Sony PSP: Really good contender if you want a retro portable device.
- Nintendo Wii: Hackable and has cool games, but hardware was meh.
- Nintendo DS/2DS/3DS: Hackable.
- Microsoft XBox 360, Microsoft Kinect: Good support from Microsoft but limited applications.
- Nintendo NES/SNES minis: You can add more games and if you just need a console to play some NES/SNES games that you like, then you should have a look at them.
- **Where to learn more**: Ben Heck show. There isn't a central location for game console hacks afaik, just search *how to jailbreak yourgameconsolemodel*

## E-readers

### Barnes and Noble Nook

The Nook is a Android 2.2 device in disguise. It has wifi built-in. Coupled with a Raspberry Pi, you can have a nice e-ink display/dashboard.

### Other notable devices

- Kindles: Many of them are hackable, but I don't know enough to say what exactly is hackable and what isn't. This is a cat-and-mouse game.
- **Where to learn more**: [HN](https://news.ycombinator.com/item?id=13863046), [Hackaday](https://hackaday.com/tag/ereader/).

## Development boards

### Expressif ESP8266 (201?)

It is less-than-$5 cheap, it has wifi and it is an Arduino. Now we're talking real values. My memory about this module is murky, but I think it was intended to be a dumb WiFi module initially, but people hacked Nodejs and Arduino later on to make it a microcontroller with WiFi built-in.

### Raspberry Pi 3 (2016)

It is the gateway drug to hardware hacking. Tried-and-true device for millions of makers worldwide, the Raspberry Pi 3 is the definite device to have if you want to start hacking. It does everything and runs everything.

### Arduino Uno (2010)

If you want to start with microcontrollers, just start with this one. It has a huge fanbase and developer community, and you could always find a project worth working on with the Arduino.

### The rest and resources

- Other Arduinos, esp. the Arduino Micro: They are just as good.
- Teensy: Good and small.
- Expressif ESP32: Designed to be good, but not as crazy of a hack as ESP8266 was.
- Raspberry Pi Zero W: Good choice if you want a cheap Raspberry Pi.
- [HC-05 and HC-06 Bluetooth modules](https://www.youtube.com/watch?v=BBqsVKMYz1I).
- **Where to learn more**: Hackaday, eevblog, [reddit](http://reddit.com/r/raspberry_pi), search for single board computers

## Smartphones and Tablets

I am quite reluctant to write about smartphones because there is a new phone released every day. So of course this is outdated the moment you read it.

### Google Nexus 5 (2013) and Google Nexus 7 (2013)

Supported by many third-party, obscure, crazy mobile OS projects, including Ubuntu Touch, Maru OS, Mobile Plasma. Of course, it is still powerful enough to run the latest version of Android as well.

### HTC HD2 (2009)

It was designed to run Windows Mobile 6 but it runs _everything_. So, if you want a phone that runs _everything_, then get the HD2. It is pre-historic in terms of age in the ever-evolving mobile world, but seems like this phone is just too good to not be mentioned. 

### The rest and resources

- Nokia N900: No longer available, and hardware is outdated.
- OnePlus One: Good but not crazily good. Has/had an active development community.
- Fairphone 2: Seems like it is the only phone that is designed to be opened up. So that's only fair to include them in here.
- HP Touchpad: No longer available, and hardware is outdated. But it was phenomenal years ago.
- iPhones: Can jailbreak but once jailbroken, you can't generally upgrade or downgrade them. iPhone 4 can be hacked to run every iOS that it supports via a bootloader exploit.
- Motorola Droid: No longer available, and hardware is outdated.
- WebOS/ Palm Pre 1/2/3: They are really great but then the resources (webos-internals) are slowly dwindling down and it's hard to hack on them now.
- **Where to learn more**: XDA-developers 


## Miscleneaous devices

### Eye-Fi SD cards

The small SD-card that runs Linux. It even has [a wiki](http://magiclantern.wikia.com/wiki/Eye-Fi) dedicated to hacking it.

### Xiaomi cameras

The [Xiaomi Dafang IP camera](https://hackernoon.com/hacking-a-25-iot-camera-to-do-more-than-its-worth-41a8d4dc805c) can take an improved firmware.

### Rockbox devices

**iRiver H3{2,4}0** was one of the earlier devices with a 2,5" HDD able to run Rockbox. Even with stock firmware, it supported OGG Vorbis. It sports a NXP ColdFire (previously owned by Motorola/Freescale). (Thanks HN/Fnoord!)

**Sansa Clip (2007)**: It would have been otherwise a "no wireless, less space than a Nomad" device otherwise, but Rockbox transformed all that. Rockbox is an open-source firmware that allows your player to play every audio format imaginable. Also, who knows that [your MP3 player can run Doom now](https://www.rockbox.org/)?

**Older gens iPods**: Anything before the Classic iPod, anything before the iPod nano 3, any iPod Mini is capable of running Rockbox.

### Canon cameras

They have an [open source firmware](http://www.magiclantern.fm) that adds tons of features to the cameras, such as interval shots and finer manual controls. If you have a point-and-shoot, [there is a firmware for it](http://chdk.wikia.com/), too.


### The rest and resources

- Other than Canon, [Nikon cameras](https://nikonhacker.com/), and [Sony cameras](https://github.com/ma1co/OpenMemories-Tweak) all have models that are hackable. 
- TI Calculators: They are expensive brand new but seems a pretty fun target if you find one at Goodwill or a garage sale for a cheap price. They aren't fancy by today's standards in terms of hardware, but apparently there are active communities to hack them.   
- Chumby/Insignia Infocast 3: Good but outdated hardware, and it is no longer available. I have a lot of fond memories and good things to say about the Chumby. bunnie -- the Chumby's creator, designed it to be hackable and he cares about your freedom too.
- Everything supported by Rockbox: Could be dicey.
- TS100 soldering iron: Alt firmware at https://github.com/Ralim/ts100
- T-962 reflow oven: Alt firmware at https://github.com/UnifiedEngineering/T-962-improvements
- SteamLink: Can run some software, but it is bootloader locked. However, kexec exploit works. https://www.reddit.com/r/Steam_Link/
- **Where to learn more**: Hackaday, rockbox wiki, other wikis.



## My personal gear

As I get older, I tend to choose a more popular/widely supported device over a more performant but less widely supported device when it comes to firmware hacking. The amount of time I have to spend figure stuff out like toolchains and such can be much better spent optimizing the software, given the hardware can meet it.

- I have a lot of **Raspberry Pi Zero W**s: It is slow, it might be unreliable, its one USB port is picky, the built-in audio is bad, it has some proprietary blobs, but who cares? The Pi Zero W is good enough, easy enough, cheap enough, versatile enough for many applications. It enables me to do a lot of things that I would otherwise not bothered to do. It is probably my favorite device of all times to hack on.
- **Arduino Uno** for certain applications, especially considering robotics. It is well supported, predictable, easy to transfer, easy to debug. I personally have the *Electron Asset tracker* and I haven't seen a board that is so well designed, documented and polished.
- **Dell Chromebook 13** for personal laptop. It runs coreboot without the main ME modules.
- **Netgear R6100** for my home WiFi router. It's fast, cheap and has plenty of RAM and NAND storage.
- I run a vanilla **Google Pixel 1** with stock Google software and very few apps. I am getting too old to find phone hacking fun. 
