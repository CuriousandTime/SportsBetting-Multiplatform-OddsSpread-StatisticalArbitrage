# 体育博彩多平台赔率差统计套利

<p align="center">
  <img src="https://user-images.githubusercontent.com/113403062/190924275-629eaf18-183c-4781-81a2-fd0337143ba9.jpg" alt="animated"/>
</p>

*以上是输出Excel文件的示例。*

## 此项目鉴于 [ryankrumenacker/ports-betting-arbitrage-project]([https://openai.com](https://github.com/ryankrumenacker/sports-betting-arbitrage-project))

项目修改而来。

利用**实时体育赔率 API**（https://the-odds-api.com/） 获取数据，整理统计后在在全球即将到来的体育赛事中寻找赔率差的套利机会。========================================================
## 简单的比喻：

### 比如A-B两支球队比赛

**A平台**的赔率是A（45%）- B（55%），但在**B平台**的赔率是A（65%）- B（35%）

那么我们在**A平台**买B赢，在**B平台**买A赢，就可以保证无论A-B两支球队哪支球队获胜，我们都能获得稳定的收益。====================================================================================================

**实时体育赔率 API**是一个免费的、开放源代码的 API，可以跟踪美国各地的博彩公司提供的任何给定的体育赛事的当前赔率。

通过 API 的数据，该程序能够找到在八个最近即将到来的体育赛事中的所有可能的套利机会。一旦程序找到这些机会并进行了必要的计算以使用户了解输出，它会将所有发现写入一个 Excel 文件供用户访问。

该文件包括**ID**和**Sport Key**（这两个指标都是针对实时体育赔率 API 的特定指标），以及每个博彩公司的每个相应赌注的**比赛时间**、**预期收益**、**博彩平台**、**球队名称**、**赔率、**和**购买金额**。文件中的每一行都代表一个套利机会。

### 优化了哪些：

1.删除API_KEY.txt文件，在Colab执行文件中添加即可，不需要调用

2.所有代码尽量详尽的增加了中文注释，对小白更友好。

3.表格添加了比赛时间单元格

4.表格中项目名称全部替换为中文

5.不需要倒来倒去，点击 [Colab_AutomaticRobot]([https://colab.research.google.com/drive/1DbPgAVf0D_Q_bmYM20R5zxgKsqftWjgt?usp=sharing](https://colab.research.google.com/drive/12AEObDy5F6VkHBSCQ605j6MpicLm1Q8Y#scrollTo=9d71f761)) 就可以直接运行。
