1. 项目名称：  
基于多源数据的太阳活动定位与爆发预判
2. 项目介绍：  
中科院科创计划项目之一
现在完成：有无爆发的检测、二型爆、三型爆、其它类型爆发的检测，不过需要用到不同的网络；  
使用迁移学习，将使用learmonth天文台数据训练好的网络，用于culgoora天文台爆发检测； 
编写软件，选择图片，自动检测（现在有BUG，本次检测的结果，只有在检测下一张图片时才会显示； 
花费大量的时间制作了数据集，但是还不完善，I型爆和IV型爆没有细分，涵盖的噪声情况较少，容易把噪声识别为爆发。



* 定位部分：  
使用神经网络对太阳射电爆发图片进行分类
* 预判部分：  
暂时没有进行

3. 成员分工：
   * 韩富韵：制作数据集、图像处理、训练神经网络、网站demo
   * 李恩泽：撰写报告、制作数据集、训练神经网络
   * 何若璞：编写软件、图像处理、网站维护

前期的代码在这个仓库https://github.com/han-fuyun/old

包括从原始的日志文件读取有效信息的代码，不过不想花时间去整理了
