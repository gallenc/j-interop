# j-interop
local patches for j-interop

OpenNMS uses j-interop for WMI but I have had problems authenticating to a number of windows server machines. the Linux WMIC doesnt seem to have the same problems. This project adds a patch provided by Danny Tylman to provide j-interop with similar login capabilities to WMIC. For more details see the wiki.
