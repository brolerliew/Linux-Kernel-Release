# LinuxKernelRelease
对Linux内核版本更新的主要功能的技术背景进行深入解释。还包括最新的内核的deb包发布。

包含各个RC版本的Linus的发布邮件和对应的代码地址和变更列表。以及LWN、phoronix和KernelNewbies的优秀的版本特性解释链接。

主要特性解释集中在内核特性和CPU/GPU的硬件特性支持。

deb包是在发布内核时最新的Ubuntu上编译得到。Ubuntu的mainline内核（https://kernel.ubuntu.com/mainline/）包含了新于当前系统发布的内核版本，但是对于最新的内核的编译支持速度较慢。我编译的最新的内核是使用Ubuntu的mainline默认配置+打开BINDER支持（可以运行Waydroid）。

# 例如6.8
## Linus Torvalds Release Email：
- 6.8-rc1:  https://lore.kernel.org/lkml/CAHk-=wiB4iHTtfZKiy5pC24uOjun4fbj4kSX0=ZnGsOXadMf6g@mail.gmail.com/T/
- 6.8-rc2:  https://lore.kernel.org/lkml/CAHk-=wgxzm+Oc1ywuNGxb1R1=ZEC85LJi776R2QEpk6=_2Qfdw@mail.gmail.com/T/#u
- 6.8-rc3:  https://lore.kernel.org/lkml/CAHk-=wisik=He=zySDRHq7fe6k_cOXZeZiCkR41TmbzK2KNZtg@mail.gmail.com/
- 6.8-rc4：https://lore.kernel.org/lkml/CAHk-=wg1c4Q1Ve6BG71DikHu-AEoKUUQoj1QbVdjwGQyTExqCw@mail.gmail.com/T/
- 6.8-rc5：https://lore.kernel.org/lkml/CAHk-=wi8vZD7EXZfob-yhfDERyfzWxzMOzG9FsOuaKU-v6+PHA@mail.gmail.com/T/
- 6.8-rc6：https://lore.kernel.org/lkml/CAHk-=whZ=iA6DhijePcW-pJjZ8YD4T5qLpLKVSUT+4gWNm_0sA@mail.gmail.com/T/#u
- 6.8-rc7：https://lore.kernel.org/linux-kernel/CAHk-=wgwt9b3yMxAQRCVJ0Jh6-4Dz1Fgo2au7g_U9VWVxXoS6Q@mail.gmail.com/T/
- 6.8 ：https://lore.kernel.org/lkml/CAHk-=wiehc0DfPtL6fC2=bFuyzkTnuiuYSQrr6JTQxQao6pq1Q@mail.gmail.com/T/

## 版本间代码变动与源代码包下载
- 6.8-rc2：https://lore.kernel.org/linux-kernel-announce/20240121230643.release-6.8-rc1@kdist.linux.kernel.org/T/#u
- 6.8-rc2：https://lore.kernel.org/linux-kernel-announce/20240129013906.release-6.8-rc2@kdist.linux.kernel.org/T/#u
- 6.8-rc3：https://lore.kernel.org/linux-kernel-announce/20240204130848.release-6.8-rc3@kdist.linux.kernel.org/T/#u
- 6.8-rc4：https://lore.kernel.org/linux-kernel-announce/20240211210538.release-6.8-rc4@kdist.linux.kernel.org/T/#u
- 6.8-rc5：https://lore.kernel.org/linux-kernel-announce/20240218213104.release-6.8-rc5@kdist.linux.kernel.org/T/#u
- 6.8-rc6：https://lore.kernel.org/linux-kernel-announce/20240226002825.release-6.8-rc6@kdist.linux.kernel.org/T/#u
- 6.8-rc7：https://lore.kernel.org/linux-kernel-announce/20240303214143.release-6.8-rc7@kdist.linux.kernel.org/T/#u

## 其它 
phoronix的6.8内核版本特性介绍：https://www.phoronix.com/review/linux-68-features

6.8内核相关的LWN文章：https://lwn.net/Kernel/Index/#Releases-6.8

KernelNewbies整理的完整6.8内核版本特性列表地址（尚未完成）：https://kernelnewbies.org/Linux_6.8
