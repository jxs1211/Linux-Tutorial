# **九张图一览 Linux 性能工具全景图**

## 1. 前言

当今时代，绝大多数企业的应用都是运行在 Linux 操作系统上，所以对应用进行性能诊断和性能优化时，离不开 Linux 的各种性能观测工具和性能优化工具。

笔者使用过的常见的Linux 性能观测和性能优化工具有：

- top/uptime
- ps/pstree
- df/du/free/lsblk
- ip/ifconfig/ping/telnet
- route/dig/nslookup
- lsof/netstat/ss
- tcpdump/tshark/wireshark
- netstat/vmstat/iostat/pidstat/dstat/mpstat
- sar/sysctl/ethtool

最近在拜读国际著名的 LINUX 性能专家 Brendan Gregg 的个人博客和技术书籍，摘抄了如下九张图，一览 Linux 性能工具全景图，大家共勉！

## 2. Linux 性能工具全景图

- linux performance observability tools![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5WGDc0UiamLVsckw1cO4EoEUZ3mQdwoeUQ8RadjiaAIuwc2iab2TOLlL1g/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)
- linux static performance tools![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5YT6gNM3YlbjrCYC0pCtzdE3yhYlcjNRSNiciaOkAqa9nC7mAGw4Niavmg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)
- linux performance benchmark tools

![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5aoibpgZKgNz57tH3iaumpoyPvDrJZr9SSxWRZuPyON4w1U89x2w5cBRg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

- linux performance tuning tools![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5pEDUUVc6kmf7Icj3nwib4M716aU5mEXVfXjnCUGB1aBBsXecXhiaygPw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

- linux performance observability: sar![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5sXOaF2kibIq7fywFSOhm6ATCkb8a4IkU5ibzTvmGLUTPibMuqYPORm2Qg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

- linux performance observability: perf-tools![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5iaHNsGuFhrmFq6tdGhmtbVibHScZoNPuHbGpRSB4tkicRIBE5eGSsmjHQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

- linux bcc/BPF Tracing tools![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5rNK70CibujphEiajb2aKOqeaseeZFo6pMeicmKZ3yV6IuQZgR657ccQZw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

- bpftrace/eBPF Tools

  ![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5DdGbBS2dKyzVRIIgq2LXYmKnLcWognjro6ic4mcYwIbGhOtJ32uvcLg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

- BPF Performance Tools: Linux System and Application Observability

  (![Image](https://mmbiz.qpic.cn/mmbiz_png/P0X0ia1B3wEZ7LcTMUZBfibwyfG7oTt3k5Xcg7goNDAvY4BX7dvia2Mk23bTDzemPKj4BW3h230icQJrBmKxSPHxWg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1))

## 3 后记

更多 LINUX 性能资料，大家可以访问大师的个人网站和和技术书籍

- https://www.brendangregg.com/
- 《性能之巅：洞悉系统、企业与云计算》（《Systems Performance: Enterprise and the Cloud, 2nd Edition (2020)》）
- 《洞悉Linux系统和应用性能》（《BPF Performance Tools》）
- ps: 要说 LINUX 内核近几年(和今后几年）最引人注目的发展模块，那就是 bpf 了，完全值得花点精力学习跟进下。