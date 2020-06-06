### HEMLab团队在Water Resources Research发表新成果：基于二维高性能水动力模型和数值天气预报的实时洪水预报系统
 
>HEMLab团队在Water Resources Research发表新成果：基于二维高性能水动力模型和数值天气预报的实时洪水预报系统

>高精度，全流域，纯水动力，实时淹没深度预报
 
>欢迎咨询、引用！


![封面图片](https://github.com/mingxiaodong/markdown_test/blob/master/Paper_preview.png)

洪水预报系统一般至少包括天气预报和洪水模拟两个模块。当前大部分预报系统的洪水模拟模块依赖于水文模型或者水文与水动力耦合模型，往往过度简化或者不考虑洪水演进的动力过程。当面对极端降雨导致、伴随着高速地表径流的洪水时，忽视洪水动力机制而过多依赖经验参数可能会使模拟失准。本研究基于最新开发的高性能二维水动力学模型HiPIMS，利用英国气象部提供的数值天气预报，开发出一套实时洪水预报系统(图1)，能够提供高精度、全时段和全流域的洪水水深和淹没范围预报结果，并可进一步用于支持洪水风险评估与防灾减灾工作。
![图一](https://github.com/mingxiaodong/markdown_test/blob/master/Figure%201.png)
图1. 洪水预报系统框架

该系统应用于流域面积为2500平方公里的英国Eden流域，以2015年12月的一次极端洪水事件为例，成功验证了其提前34小时发布10m精度的精确洪水淹没预报的能力<sup>*</sup>。该预报包含覆盖洪水事件全时段和整个流域空间的淹没深度(图2)和水流流速，并与观测数据进行了对比(表1)，证明该系统具有较高的准确度和时效性。


![图二](https://github.com/mingxiaodong/markdown_test/blob/master/CA1_4map.png)
图2. 不同时段的洪水淹没深度及范围预报

表1. Carlisle市中心区域的淹没范围预报表现(基于10m×10m网格)
Total cells|Hits|Misses|False alarms|Correct negatives|POD|FAR|CSI
-----------|----|------|------------|-----------------|---|---|---
105583|24369|249|9644|71321|0.99|0.28|0.71

本研究具有以下亮点：
* 基于全水动力学模拟和数值天气预报的高精度实时预报系统
* 通过多GPU加速技术实现全流域2500万（10m×10m）网格级别的二维水动力学洪水模拟
* 该系统应用于英国Eden河流域，以2015年12月的一次极端洪水事件的36小时降雨预报为例，成功验证了提前34小时发布10m精度的洪水淹没预报的能力<sup>*</sup>

<sup>*</sup>采用安装有8×NVIDIA Tesla K80 GPU的服务器

该论文由HEMLab研究团队[明晓东](https://www.researchgate.net/profile/Xiaodong_Ming2)博士、[梁秋华](https://www.lboro.ac.uk/departments/abce/staff/qiuhua-liang/)教授和[夏熙临](https://www.lboro.ac.uk/departments/abce/staff/xilin-xia/)博士以及英国纽卡斯尔大学和气象部合伙伴联合发表在水资源顶级期刊**Water Resources Research**上：
Ming, X., Liang, Q., Xia, X., Li, D., & Fowler, H. J. (2020). [Real‐time flood forecasting based on a high‐performance 2D hydrodynamic model and numerical weather predictions.](https://doi.org/10.1029/2019wr025583) Water Resources Research.

原文链接：https://doi.org/10.1029/2019wr025583

敬请访问[HEMLab团队网站](https://www.hemlab.org)，了解模型开发动态，关注最新研究成果。
![qrcode](https://github.com/mingxiaodong/markdown_test/blob/master/HEMLab_Wechat_QRcode.jpeg)
