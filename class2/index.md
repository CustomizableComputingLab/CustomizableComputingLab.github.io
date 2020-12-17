数字集成电路静态时序分析基础
===
[“IC创新学院”课程主页，课程视频请戳此链接](https://www.iccollege.cn/portal/courseDetail/193.mooc)。
专注于集成电路的MOOC平台，免费注册学习！

课程概述
---
时序收敛是数字集成电路和FPGA都极为关注的指标，不管在前端RTL设计还是后端物理实现阶段都需要投入大量的时间和精力。本课程以经典书籍《Static Timing Analysis for Nanometer Designs: A Practical Approach》为教材，重点以Synopsys TCL语言入门、工艺库、复杂时序路径分析方法为核心内容，辅以时序分析笔试题，期望通过这门课程掌握静态时序分析方法。  


课程大纲
---
![知识点](./zsd.webp)
- 课程概述 [slide](./slides/1-课程概述.pdf)  
- 脚本语言
  1. TCL语言 [slide-1](./slides/2-TCL语言入门.pdf)  [slide-2](./slides/3-TCL语言入门.pdf) 
  2. synopsys TCL语言 [slide](./slides/4-Synopsys TCL语言入门.pdf) 
- STA基本概念 [slide](./slides/5-STA基本概念.pdf) 
- 标准单元工艺库 [slide](./slides/6-工艺库.pdf)
- 建立静态时序分析的环境 [slide](./slides/7-STA环境.pdf)
  1. 时钟相关约束
  2. 外部接口约束等
- 时序检查
  1. setup与hold检查方法 [slide](./slides/8-建立时间与保持时间检查.pdf)
  2. 多周期、半周期、伪路径 [slide](./slides/9-特殊时序检查-多周期半周期伪路径.pdf)
  3. 多时钟 [slide](./slides/10-特殊时序检查-多时钟.pdf)
- Robust Verification
  1. on chip variation [slide](./slides/11-Robust Verification.pdf)
  2. time borrowing [slide](./slides/12-Time Borrowing.pdf)
  3. data to data check [slide](./slides/13-Data_to_Data check.pdf)
  4. clock gating check [slide](./slides/14-CLock_Gating_Checks.pdf)
- 习题讲解 [slide](./slides/15-习题讲解.pdf)

前序知识
---具备数字集成电路、ASIC/SoC/FPGA设计等基础知识。

参考资料
---
1. Static Timing Analysis for Nanometer Designs: A Practical Approach. J.
   Bhasker, Rakesh Chadha. Springer Science Business Media, LLC 2009. 
2. 集成电路静态时序分析与建模. 刘峰, 机械工业出版社.出版时间：2016-07-01.  
3. 同学们也可以参考上海交通大学硕士生赵俊军对文献1的翻译工作。文章链接为https://www.zhihu.com/people/zhao-jun-jun-19/posts
在此非常感谢赵俊军同学的辛苦工作，他自发利用学习和科研空余时间来翻译了这本经典著作，如果感兴趣，请多关注他的知乎，为他点赞。
