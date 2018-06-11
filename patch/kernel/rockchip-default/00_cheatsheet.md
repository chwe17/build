#A small cheatsheet
rearange of the patching of the rk3288 patches

| namig         | meaning             | 
| ------------- |:-------------------:| 
| 100           | opp related patches, disable rk3288-linux.dtsi (bootargs set by DTS) |
| 110           | 8723bs related      |
| 120           | LED                 |
| 130           | boot&reboot         |
| 190           | TinkerS eMMC        |
| 260           | gpiomem driver      |

currently failing patches:
´´´
[ o.k. ] Looking for user patches in [ userpatches/kernel/rockchip-default ]
[ o.k. ] * [l][c] 04-patch-4.4.132-133.patch
[ warn ] * [l][c] 04-patch-4.4.133-134.patch [ failed ]
[ o.k. ] * [l][c] 04-patch-4.4.134-135.patch
´´´