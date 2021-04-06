# 郭时琨 1900010695
##1.作业1
  
作业1描述
  
我分别用词云、柱状图和饼状图来表现《西游记》中师徒四人出现频次，
词云和柱状图从整体上表现四人各昵称的出现数量，并且柱状图中细分了每个人物前几多称呼的比例，饼状图则分别给出四人各昵称出现的比例
  
[作业1链接wordcloud](https://gsk5198.github.io/hw1.html)
  
[作业1链接pie](https://gsk5198.github.io/hw1.png)
  
[作业1链接bar](https://gsk5198.github.io/hw1bar.png)
  
  
##2.连线图
  
作业2描述
  
我用geo的连线功能绘制了《西游记》中唐僧师徒西行的大致路线。
  
[作业2链接](https://gsk5198.github.io/hw2.html)
  
  
##3.世界地图
  
作业3描述
  
我用Faker函数随机生成了一些跨国公司及其在一些国家的资产，用户可以输入公司数量，
图表显示的是个国家中各公司资产之和，颜色显示范围会随输入做适当调整，
假设资产可以代表公司在该地市场的规模，那么从颜色来看整体上越红就说明该地竞争越激烈。
  
[作业3链接](https://gsk5198.github.io/hw3.html)
  
  
##4.组合图表
  
作业4描述
  
我用timeline和map模拟了某个自定义的疫情在中国的发展情况，
我给每个省都设计了随机初始人数和初始患者数，用户可以输入感染率（a）、痊愈率（b）和运行年份三个参数。
感染率决定了各省之间患者数的影响，痊愈率影响一个省每年痊愈的人的数量（最终数值均包含小幅随机波动）。
每个省每年的患者数由前一年各省的情况经运算得出。
num=int(((1-b)*前一年该省患者数+a*前一年该省健康人数*外省感染者比例均值)*随机量)
  
下面的链接分别为低传染率和高传染率下疫情的蔓延情况
  
[作业4链接1](https://gsk5198.github.io/hw4_lowrate.html)
  
[作业4链接2](https://gsk5198.github.io/hw4_highrate.html)
