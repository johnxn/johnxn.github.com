---
layout: post
title: "呵呵喜闻乐见"
description: ""
category: ""
tags: []
---
{% include JB/setup %}
## 2013-12-10
今天状态不佳，上午泡了个馆，下午看论文，顺便打了场球，晚上继续看论文。总体来说干了下面这些事

- 看了 *Multi-stage Binary Code Obfuscation Using Improved Virtual
  Machine*这篇论文。有种不靠谱的赶脚。他所谓的`block-to-byte`定义十分模糊。传统虚拟机的做法是每条`instruction`对应一个`bytecode`，而这篇论文提出每一个`block`对应一个`bytecode`。事先确定`block`和`bytecode`的对应关系明显是不可能的，因为每个程序都有n多块，不同的程序又有不同的块，怎么对应？他另外提出的一个`multi-stage`到是有点意思，基本上来说就是找出每条指令的等价指令，或者是和它等价的一系列指令，然后再找这一系列指令各自的等价指令。根据
  stage 数确定深度。
- 打了场球。主要是没配合，果然少了大哥不行。下次打球多点背身单打加突破分球

## 2013-12-11
 不知所谓，泡了个馆，看了下`rose compiler`，略微看不下去的赶脚。



