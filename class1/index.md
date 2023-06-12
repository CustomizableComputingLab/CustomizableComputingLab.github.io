![logo](./header.jpg)

芯动力——硬件加速设计方法
===

[课程主页，课程视频请戳此链接](https://www.icourse163.org/course/SWJTU-1207492806)。
- 中国大学MOOC平台，免费注册学习！练习、作业、考试题请见“中国大学MOOC”。
- 教师可以联系邮箱zxdi@home.swjtu.edu.cn获取课程所有作业参考答案。  
- 如果VerilogHDL基础较薄弱，建议课前在B站学习《从电路设计的角度入门VerilogHDL》[请戳此链接观看](https://www.bilibili.com/video/BV1PS4y1s7XW?spm_id_from=333.999.0.0&vd_source=11e1c053bd139ab5a2798c3f31d057df)。  

![课程图片](./MOOC.jpg)



课程概述
---
本课程的教学内容主要包括：

1.  VerilogHDL可综合设计。课程收获：如何避免常见的VerilogHDL代码误区，如何在考
    虑性能、面积、功耗、后端实现的情况下，编写高质量代码。

2.  同步电路设计与跨时钟域电路设计。课程收获：学会理解经典跨时钟域同步电路设计
    原理；理解和掌握异步FIFO"空""满"设计原理，掌握FIFO深度计算方法；理解"异步复
    位、同步释放"的原理和方法；理解 "一段式"、"两段式"、"三段式"状态机电路结构
    的异同，掌握状态机编写方法。

3.  逻辑综合DesignCompiler基本原理和方法。课程收获：掌握DesignCompiler使用流程，
    并理解DesignCompiler的约束；掌握Synopsys TCL语言的应用方法。

4.  静态时序分析。课程收获：理解建立时间与保持时间的计算原理，掌握多时钟下数据
    路径的建立时间和保持时间的检查方法。

5.  FPGA硬件加速案例等。"FPGA硬件加速案例"采用了2018年全国大学生集成电路创新创
    业一等奖作品"基于Xilinx PYNQ FPGA的Softmax函数硬件加速设计"，相关工程和代码
    已经在github开源。如果听众手里有PYNQ Z2开发板，则可以复现该作品。


课程大纲（附每章节slide文件）
---

<details>
<summary>
01: 概述
</summary>

学习目标：了解硬件加速的意义；知悉芯片设计领域的行业分工与特点；熟悉数字芯片设计的流程和EDA工具；

[slide](./slides/1-1.pdf)

</details>

<details>
<summary>
02: VerilogHDL可综合设计
</summary>

学习目标：知悉如何避免常见的VerilogHDL代码误区；掌握如何在考虑性能、面积、功耗、后端实现的情况下，编写高质量代码；掌握常见的RTL设计指导原则。

该章节课时标题：

- 2.1. VerilogHDL可综合描述原则，常见语法描述对应的硬件电路结构 [slide](./slides/2-1.pdf)

- 2.2. 在RTL书写中如何考虑延迟、面积等 [slide](./slides/2-2.pdf)

- 2.3. RTL设计指导原则 [slide](./slides/2-3.pdf)
</details>

<details>
<summary>
03: 同步电路设计与跨时钟域
</summary>

学习目标：学会理解经典跨时钟域同步电路设计原理；理解和掌握异步FIFO"空""满"设计原理，掌握FIFO深度计算方法；理解"异步复位、同步释放"的原理和方法；理解
"一段式"、"两段式"、"三段式"状态机电路结构的异同，掌握状态机编写方法。

该章节课时标题：

- 3.1. 亚稳态 [slide](./slides/3-1.pdf)

- 3.2. 单bit信号的跨时钟域传输电路；FIFO导言 [slide](./slides/3-2.pdf)

- 3.3. FIFO-空满信号生成机制与深度设计方法 [slide](./slides/3-3.pdf)

- 3.4. FIFO知识点总结 [slide](./slides/3-4.pdf)

- 3.5. 同步复位异步释放电路设计 [slide](./slides/3-5.pdf)

- 3.6. 状态机概述与分类 [slide](./slides/3-6.pdf)

- 3.7. 两段式与三段式状态机的电路设计结构与分析 [slide](./slides/3-7.pdf)

</details>


<details>
<summary>
04: 逻辑综合DesignCompiler
</summary>

学习目标：掌握DesignCompiler使用流程，并理解DesignCompiler的约束；掌握Synopsys
TCL语言的应用方法。

该章节课时标题：

- 4.1. 逻辑综合概述与基本知识 [slide](./slides/4-1.pdf)

- 4.2. 标准单元工艺库 [slide](./slides/4-2.pdf)

- 4.3. 逻辑综合中如何施加环境约束 [slide](./slides/4-3.pdf)

- 4.4. 逻辑综合设计约束 [slide](./slides/4-4.pdf)

- 4.5. 逻辑综合中优化电路常用方法 [slide](./slides/4-5.pdf)

- 4.6. Synopsys TCL语言简介 [slide](./slides/4-6.pdf)
</details>

<details>
<summary>
05: 静态时序分析
</summary>

学习目标：理解建立时间与保持时间的计算原理，掌握多时钟下数据路径的建立时间和保持时间的检查方法。

该章节课时标题：

- 5.1. 静态时序分析入门 [slide](./slides/5-1.pdf)

- 5.2. 静态时序分析工具如何检查时序路径的建立时间 [slide](./slides/5-2.pdf)

- 5.3. 保持时间检查 [slide](./slides/5-3.pdf)

- 5.4. 慢时钟与快时钟切换的静态时序分析 [slide](./slides/5-4.pdf)

- 5.5. 多时钟与半周期静态时序分析 [slide](./slides/5-5.pdf)
</details>

<details>
<summary>
06: FPAG硬件加速案例
</summary>

学习目标：FPGA硬件加速案例-人工智能算法中softmax函数的硬件加速设计。基于给出的"FPGA硬件加速案例"的开源代码，理解并复现该作品。相关工程和代码已经在github开源。

[slide](./slides/6-1.pdf)

</details>

**课内设计**：
Open Mini Bitcoin Miner [slide](./slides/ASIC_ex.pdf)  

---
**课程图片**：
![课程图片](./jxnr-horizontal.webp)

参考资料
---
![参考书目](./cksm.webp)

<details>
<summary>
第二章-VerilogHDL可综合设计
</summary>

1.  SoC设计方法与实现(第3版).郭炜 等. 电子工业出版社.2017年.第六章.

2.  设计与验证. EDA先锋工作室. 人民邮电出版社. 第四章.

3.  Altera FPGA/CPLD设计(高级篇).EDA先锋工作室. 人民邮电出版社. 第一章.

4.  数字专用集成电路的设计与验证. 杨宗凯，黄建，杜旭 编著.
    电子工业出版社. 2004.第五章.

5.  数字IC设计：方法、技巧与实践. 唐杉，徐强，王莉薇 编著.
    机械工业出版社. 2006.

6.  Clifford E. Cummings经典论文
</details>

<details>
<summary>
第三章-同步电路设计与跨时钟域
</summary>

1.  SoC设计方法与实现(第3版).郭炜 等. 电子工业出版社.2017年.第七章.

2.  设计与验证. EDA先锋工作室. 人民邮电出版社. 第六章.

3.  FPGA深度解析. 樊继明，陆锦宏 著. 北京航空航天大学出版社.
    2015年.第八章.
</details>

<details>
<summary>
第四章-逻辑综合DesignCompiler
</summary>

1.  Design Compiler User Guide

2.  数字VLSI芯片设计：使用Cadence和Synopsys CAD工具. （美）布鲁范德
    著，周润德 译. 电子工业出版社. 2009.第九章.

3.  综合与时序分析的设计约束：Synopsys设计约束（SDC）实用指南

4.  Sridhar Gangadharan，Sanjay，Chur 著，韩德强 张丽艳 王宗侠等译 译.
    机械工业出版社.2018年.

5.  Tcl for Synopsys Tools

6.  Design Compiler Optimization Reference Manual

7.  Static Timing Analysis for Nanometer Designs: A Practical
    Approach. J. Bhasker, Rakesh Chadha. Springer. 2009. Chapter 3.
</details>

<details>
<summary>
第五章-静态时序分析
</summary>

1. Static Timing Analysis for Nanometer Designs: A Practical Approach. J.
Bhasker, Rakesh Chadha. Springer.2009. Chapter 8.
</details>


课程内容
---
![教学内容](./jxnr-horizontal.webp)


作业答案与解析 
---
[习题答案](./MOOC_solutions_2023.pdf)


练习题
---
20分钟RTL快速练习题  

 [RTL TEST1](./test/RTL_TEST.zip)  
 [RTL TEST2](./test2/test2.zip)  
 [RTL TEST3](./test3/test_student.zip)  
 [RTL TEST4](./test4/matrix_multi.zip)  


参考网站
---
- [PYNQ: PYTHON PRODUCTIVITY](http://www.pynq.io/)   


**返回教师主页**
---
[个人主页](http://www.dizhixiong.cn/)
