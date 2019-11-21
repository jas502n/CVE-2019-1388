# CVE-2019-1388 UAC提权 (nt authority\system)

![](./CVE-2019-1388.gif)

## 0x01 demo

```
SERVER
======

Windows 2008r2	7601	** link OPENED AS SYSTEM **
Windows 2012r2	9600	** link OPENED AS SYSTEM **
Windows 2016	14393	** link OPENED AS SYSTEM **
Windows 2019	17763	link NOT opened


WORKSTATION
===========

Windows 7 SP1	7601	** link OPENED AS SYSTEM **
Windows 8		9200	** link OPENED AS SYSTEM **
Windows 8.1		9600	** link OPENED AS SYSTEM **
Windows 10 1511	10240	** link OPENED AS SYSTEM **
Windows 10 1607	14393	** link OPENED AS SYSTEM **
Windows 10 1703	15063	link NOT opened
Windows 10 1709	16299	link NOT opened
...
```

![](./1.jpg)

![](./2.jpg)

![](./3.jpg)


## 参考链接

https://github.com/Lz1y/imggo

https://www.zerodayinitiative.com/blog/2019/11/19/thanksgiving-treat-easy-as-pie-windows-7-secure-desktop-escalation-of-privilege

https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2019-1388

https://gist.github.com/gentilkiwi/802c221c0731c06c22bb75650e884e5a
