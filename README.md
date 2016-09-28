airport-bssid
=============

This tool helps MacOS connect to a specific WIFI access point by its BSSID.

============
Recent changes to the Mac/OS/X airport command (>10.6) have removed the ability for selecting which access point to connect to by its BSSID. When Interop Tokyo started using a connected STM WIFI network in 2013, there were many access points overlapping each other which caused connectivity problems. Shintaro Tanaka created a tool that can re-associate the Mac operating system to specific BSSIDs on the network.

The Interop Tokyo is an insanely huge exhibition network called ShowNet. Visitors and exhibitors installed a huge number of AP to use. These overlapping access points had several different WIFI security policies, yet shared the same SSID. For ease of use it was preferred to have the same SSID for each access point without the user having to know which access point to connect to. On the other hand, the users needed to connect to specific access points based on their requirements, and they needed a way to test for the individual access point, from both the SSID and the specific BSSID, obtained in advance by performing association at the BSSID level.

This is the reason for creating this tool. I published it to github in 2013. In the past few months, it has gained popularity again. I tried to maintain it over the years. I also think that this tool is incomplete, so if you find a bug -- please report it as an issue. If you like it, that makes me happy -- please let me know and star the repository. I will attempt to address issues as possible on the same day. Have a great year.
