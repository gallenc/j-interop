# j-interop
local patches for j-interop

OpenNMS uses j-interop for WMI but I have had problems authenticating to a number of windows server machines. The Linux WMIC module written in C doesn't seem to have the same problems. This project adds a patch provided by Danny Tylman to provide j-interop with similar login capabilities to WMIC. The modified code is in branch 2.0.8-wmic. For more details see the wiki page https://github.com/gallenc/j-interop/wiki
