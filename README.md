# Netch-CE
Netch  Collector's Edition

v1.9.7

高分辨率情况下显示效果较差，换了内核，性能好像没什么明显区别，可能比192好一丁点，但是还是不如181的网页代理，同时响应速度感觉也慢，而且会受到DNS污染的影响

v1.9.2

一次大停更前的版本，TUN模式的性能接近老版本的网页代理水平，但是响应速度还是差了点，而且日常使用过程中出现内置DNS响应异常的问题

v1.8.1 源码 https://github.com/netchx/netch/releases/tag/1.8.1

使用的是TUNTAP，性能很差很差，这个在v1.8.3被换为 WinTUN (aiocloud/tun2socks) 同时取消了本地HTTP代理和网页代理模式，WinTUN性能不错

v1.7.3-S 来自 https://github.com/AmazingDM/Netch-ForOwnUse
