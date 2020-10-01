![](Images/GadgetsMain.png)
# Gadgets
**System monitoring gadgets inspired by the well-known AddGadgets.com Windows Sidebar gadgets.**

Arguably, some of the best and most popular Vista and Windows 7 Gadgets for system monitoring were done by [AddGadgets.com](http://addgadgets.com/). Unfortunately, with the deprecation of the Gadget platform and outright banning of gadgets by some corporate policies, these gadgets have become obsolete. Gadgets aren't supported in Windows 8 or Windows 10 without hacks and workarounds and often they break after applying Windows Updates.

I've searched everywhere to find equivalent gadgets, and finally found one on the Rainmeter forums, the "All CPU Meter" skin, by user james31231. The skin never made it out of beta, so I've completed his original work and expanded the suite to include a number of the most widely used AddGadgets.com gadgets. For help and more, visit the Gadgets on the [Rainmeter Forums](https://forum.rainmeter.net/viewtopic.php?f=27&t=20699).

**[Download the latest version here (5.5.x)](https://github.com/SilverAzide/Gadgets/releases/download/v5.5.x/Gadgets_5.5.x.rmskin)**

## Features
**All CPU Meter**
* Displays CPU utilization for 1 to 64 logical cores.
* Displays processor model and clock speed.
* Shows used, free, and total RAM available.
* Shows used, free, and total page file available (optional).
* Shows core temperatures (optional, requires [CoreTemp](http://www.alcpu.com/CoreTemp/), [SpeedFan](http://www.almico.com/speedfan.php), or [HWiNFO](http://www.hwinfo.com); more info [here](https://github.com/SilverAzide/Gadgets/wiki/HOW-TO-Configure-the-All-CPU-Meter-to-show-core-temperatures#how-to-configure-the-all-cpu-meter-to-show-core-temperatures).
* Shows CPU fan speed (optional, requires [SpeedFan](http://www.almico.com/speedfan.php) or [HWiNFO](http://www.hwinfo.com); more info [here](https://github.com/SilverAzide/Gadgets/wiki/HOW-TO-Configure-the-All-CPU-Meter-to-show-fan-usage#how-to-configure-the-all-cpu-meter-to-show-fan-usage).**\***
* Displays graphical line chart of CPU utilization, with RAM and page file percent usage.
* Shows Task Manager when gadget is double-clicked.
* Scales to any desired size.

**Drives Meter**
* Displays disk information for up to 26 physical drives (fixed and removable only). Gadget dynamically adjusts to handle adding and removing drives.
* Shows used, free, and total disk space available.
* Displays percent disk utilization for each drive, plus the total.
* Shows throughput for each drive (read and write).
* Shows total bytes read/written since bootup for each drive on mouseover (optional).**\***
* Displays disk throughput graph.
* Displays disk time percentage histogram (optional).
* Drive space bar graph changes color when disks are nearing capacity.**\***
* Shows Explorer when gadget is double-clicked.
* Opens drive in Explorer (or runs any user-defined command) when disk label is clicked.**\***
* Scales to any desired size.

**Network Meter**
* Shows data for all or selected network interfaces ([info](https://github.com/SilverAzide/Gadgets/wiki/INFO-Network-statistics-monitoring#info-network-statistics-monitoring)).
* Displays internal and external IP addresses (optional).
* Displays peak network throughput.**\***
* Shows inbound and outbound throughput in bits/sec and bytes/sec.
* Displays graphical chart of inbound and outbound network activity. Does not require guesstimating your network speed, chart dynamically scales to handle both LAN and WAN traffic.
* Shows statistics for the current session and the total to date (optional).
* Indicates internet connectivity.
* Animated network icon shows network activity (in/out/both/neither/disconnected).**\***
* Performs external IP address and location lookup.
* Shows Network and Sharing Center when gadget is double-clicked.
* Includes dedicated Wireless Network gadget for monitoring wireless activity.
* Scales to any desired size.

**Network Meter Pro**<br>
A precision network monitor with all the features of Network Meter, plus:
* More accurate network interface statistics monitoring, including data when Rainmeter is not running or no user is logged into the system.
* Not affected by Rainmeter restarts/refreshes.
* Not affected by network adapter configuration changes.
* Includes dedicated Wireless Network Pro gadget for monitoring wireless activity.
* Note: Requires installation of a Windows service (included).

**GPU Meter**
* Displays GPU model and clock speed (requires [HWiNFO](http://www.hwinfo.com); more info [here](https://github.com/SilverAzide/Gadgets/wiki/HOW-TO-Configure-the-GPU-Meter#how-to-configure-the-gpu-meter)).
* Shows used, free, and total RAM available, with memory clock speed.
* Shows GPU temperature, core load, and core voltage.
* Shows GPU fan speed and percent utilization.
* Displays graphical line chart of RAM, core load, temperature, and fan usage.
* Multiple GPU Meters provided to allow monitoring more than one GPU (for dedicated GPUs and 2-way SLI-equipped systems; for 4-way SLI systems, see [this](https://github.com/SilverAzide/Gadgets/wiki/HOW-TO-Configure-the-GPU-Meter-to-monitor-multiple-GPUs#how-to-configure-the-gpu-meter-to-monitor-multiple-gpus).**\***
* Scales to any desired size.

**Weather Meter**
* Displays the current weather for any location from [The Weather Channel](http://www.weather.com/). _Does NOT use the deprecated Wxdata feed_.
* Displays data in metric or imperial units.
* Shows current temperature, forecast high and low temperatures, "feels like" temperature, current conditions, current location and station, humidity, visibility, barometric pressure, wind speed, wind direction, and chance of precipitation.
* Shows current sunrise and sunset times, day length, and sun angle.
* Shows current moonrise and moonset times, moon phase and description, and moon angle.
* Shows complete 5 day forecast in a "flyout" window.
* Shows severe weather alerts for the current location.**\***
* Opens Google Maps for the observation location when location name is clicked.**\***
* Includes additional language translations: Bulgarian, Catalan, Czech, Dutch, English (GB), English (US), Finnish, French, German, Hebrew, Hungarian, Italian, Korean, Polish, Portuguese (BR), Russian, Serbian (SP), Slovak, Spanish (SP), Swedish, Ukrainian ([info](https://github.com/SilverAzide/Gadgets/wiki/HOW-TO-Change-the-default-language-or-temperature-units-of-the-Weather-Meter#how-to-change-the-default-language-or-temperature-units-of-the-weather-meter), source [here](http://fav.me/d2ylush)).
* Supports having multiple Weather Meters to allow monitoring more than one location ([info](https://github.com/SilverAzide/Gadgets/wiki/HOW-TO-Configure-the-Weather-Meter-to-show-multiple-locations#how-to-configure-the-weather-meter-to-show-multiple-locations)).
* Scales to any desired size.
* Includes variant gadget in a smaller size; expands to full size on mouseover.

**Battery Meter**
* Displays the current battery status, including time remaining and current percentage remaining.
* Shows current voltage, charge and discharge rates, current and maximum charge capacity.
* Shows battery manufacturer/model.
* Displays power in either watts or milliamps.
* Supports automatic failover on systems having multiple batteries.**\***
* Shows Power Options when gadget is double-clicked.**\***
* Scales to any desired size.
* Includes variant gadget that works with [HWiNFO](http://www.hwinfo.com).

**Calendar**
* Based on [LuaCalendar](https://smurfier.github.io/LuaCalendar/), styled to match the Gadget suite.**\***
* Supports localized month/day names automatically.
* Scales to any desired size.
* Includes variant gadget that shows the current day, similar to the original Windows Sidebar gadget.

**Chronometer**
* Digital Clock displays time, date, day, week, and quarter of the year.
* Shows computer uptime and session logon time (optional).
* Shows event countdown with customizable sound (optional).
* Includes configurable chime and multiple alarms with customizable sounds (optional).
* Supports Windows localized or custom time and date formats.
* Supports world times, can be adjusted for time zones and daylight saving time.**\***
* Supports having multiple clocks to allow monitoring time in multiple locations ([info](https://github.com/SilverAzide/Gadgets/wiki/HOW-TO-Create-multiple-Chronometers#how-to-create-multiple-chronometers)).
* Scales to any desired size.
* Includes Analog Clock variant, styled to match the Gadget suite.**\***
* Includes analog clocks ported from the original Windows Vista/Windows 7 Sidebar gadgets.

**Update Checker**
* Automatically checks for and optionally installs new Gadgets releases (enable/disable from the Welcome gadget).

**...get even more Gadgets!\***
* [Clipboard Meter](https://github.com/SilverAzide/Clipboard-Meter)
* [Stopwatch](https://github.com/SilverAzide/Stopwatch)
* [Top Process Meter](https://github.com/SilverAzide/Top-Process-Meter)
* [Weather Meter for Yahoo](https://github.com/SilverAzide/Weather-Meter-Yahoo)

**\*** Feature not part of original AddGadgets.com gadgets.

## Requirements
Rainmeter 4.4-r3404-beta or later: <https://www.rainmeter.net>.<br>
.NET Framework 4.5.2 or later.

**Optional**<br>
CPU Meter can use either [HWiNFO](https://www.hwinfo.com), [CoreTemp](https://www.alcpu.com/CoreTemp/) or [SpeedFan](http://www.almico.com/speedfan.php) to report temperatures and/or fan speeds.<br>
GPU Meter requires [HWiNFO](https://www.hwinfo.com).<br>
Battery Meter can use either native Rainmeter plugins or [HWiNFO](https://www.hwinfo.com).

## Attribution
* All CPU Meter gadget based on [All CPU Meter](https://forum.rainmeter.net/viewtopic.php?f=27&t=18381) by james31231.
* Calendar gadget is [LuaCalendar 5.0](http://fav.me/d4n57jh) by Smurfier, with scaling enhancement added by [TGonZ0](http://tgonz0.deviantart.com/), with localization and style mods by me.
* Clock gadget uses techniques from the System skin in [JSMeterVIII 8.0](https://forum.rainmeter.net/viewtopic.php?f=27&t=25130) by [JSMorley](https://www.deviantart.com/jsmorley).
* Network Meter gadget based on [NetTraffic](https://docs.rainmeter.net/tips/network-skin) by JSMorley.
* Update Checker gadget based on [ModernGadgets](https://github.com/raiguard/ModernGadgets) Update Checker by raiguard.
* Weather Meter gadget uses the [Weather.com](https://forum.rainmeter.net/viewtopic.php?f=27&t=34734) JSON V3 include templates by JSMorley, and includes translations from [VClouds Weather 2](http://fav.me/d2ylush) by VClouds, and includes weather icons by JSMorley (and others) with modifications by me.
* Weather Meter gadget uses a Lua script from [Sunset-Moonrise](http://fav.me/d5ybxqr) by Mordasius to calculate sun/moon times.
* Welcome gadget uses the [ConfigActive](https://forum.rainmeter.net/viewtopic.php?f=18&t=28720) plugin by JSMorley.
* Additional code cleanup and tweaks by Milamber33.

## License
Creative Commons Attribution-Noncommercial-Share Alike 3.0 License
