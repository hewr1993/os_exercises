# 操作系统概述思考题

## 个人思考题

---

分析你所认识的操作系统（Windows、Linux、FreeBSD、Android、iOS）所具有的独特和共性的功能？
- [x]  

> 共性是都有文件管理系统、CLI与GUI等。Windows开始菜单深入人心，注册表也挺独特（虽然带来复杂性）；Linux各发行版我最爱arch，可移植性强，几乎一切皆可配置；Android下拉菜单深入人心，App生命周期稍有不同，但早期版本由于设计会导致性能问题；iOS动画细节丰富，资源调度合理，硬件配置不高却甚少卡顿。

请总结你认为操作系统应该具有的特征有什么？并对其特征进行简要阐述。
- [x]  

>   多个任务能同时进行（或时间片方式）；资源私有与共享管理；对硬件的抽象能力，使开发者不需依赖硬件环境；

请给出你觉得的更准确的操作系统的定义？
- [x]  

>  操作系统式管理计算机硬件与软件资源的计算机程序，是计算机系统的核心与基石，提供配置内存、决定资源供需优先级、控制输入输出、操作网络、管理文件系统等服务，也提供GUI或NUI等必要交互方式。

你希望从操作系统课学到什么知识？
- [x]  

>  更具体的修改Linux内核代码的能力，玩转小型开发板（如树莓派、Intel Galileo）的能力。 

---

## 小组讨论题

---

目前的台式PC机标准配置和价格？
- [x]  

| 配件类型 | 大致配置 | 大致价位 |
| ---------------- | ---- | ---- |
| CPU | i5 | ¥400 |
| 主板 | - | ¥300 |
| 内存 | 4GB | ¥200 |
| 硬盘 | 1TB机械硬盘 | ¥300 |
| 显卡 | 660M独立显卡 | ¥600 |
| 机箱 | - | ¥200 |
| 电源 | - | ¥200 |
总计约¥2200。

你理解的命令行接口和GUI接口具有哪些共性和不同的特征？
- [x]  

> 共性：都能输入输出；多数情况下，能完成相同的事情；不同：GUI操作更直观，能完成很多CLI无法完成的界面任务，但需要更多的开发精力；命令行操作精准快速，开发迅捷，但学习曲线陡峭；

为什么现在的操作系统基本上用C语言来实现？
- [x]  

>  大量开源库；较统一代码风格（相对C++）便于二次开发；内存控制精准；编译所得二进制文件不依赖操作系统；极高的运行效率。

为什么没有人用python，java来实现操作系统？
- [x]  

>  不问是不是就问为什么的都是流氓，java有JNode。一般没人这么干是因为相对于C，python和java这类语言更抽象，实现操作系统时需要自行实现的库太多。而且要实现系统层级的控制，这些语言要更费劲。

请评价用C++来实现操作系统的利弊？
- [x]  

>  利：可以利用STL、boost等标准库减轻处理底层细节的工作量；在开发操作系统这样庞大的工程时，组织程序比C容易，大多数情况下还能兼容C，支持面向对象使代码实现更灵活、更易扩展；弊：体量庞大，编译出的二进制文件尺寸难以控制；不同的代码风格会使得源码难以理解；ABI兼容问题，不同编译器的隐式参数给调试增加难度，还会带来性能上的问题；

---

## 开放思考题

---

请评价微内核、单体内核、外核（exo-kernel）架构的操作系统的利弊？
- [x]  

>  微内核结构性与功能性部件分离，轻量级，但针对特定需求而配置其他服务的特点使其要求较高专业素养以及配置时间；
单体内核比较传统主流，包含所有OS功能，但也造成其体量以及兼容性的问题；
外内核减少软件的抽象，使开发者专注于硬件的抽象，但需要额外的库来支持，开发上也带来难题。

请评价用LISP,OCcaml, GO, D，RUST等实现操作系统的利弊？
- [x]  

>  

进程切换的可能实现思路？
- [x]  

>  

计算机与终端间通过串口通信的可能实现思路？
- [x]  

>  

为什么微软的Windows没有在手机终端领域取得领先地位？
- [x]  

> 手机终端硬件配置低，与PC有很大不同，微软早期不重视，导致现今其上应用数量质量均被抛离。Windows不开源，新版本与旧版本不兼容，也迫使用户逃离。
等到手机硬件平台发展到媲美传统桌面，甚至兼容exe时，Windows或许有机会利用长久以来的积累反败为胜。

你认为未来（10年内）的操作系统应该具有什么样的特征和功能？
- [x]  

>  更注重网络，轻本地硬件。就像Google的Chrome OS，本地配置支撑少量计算，通过网络利用服务器完成繁重的计算任务，甚至利用云端计算本地画面通过网络传输。

---
