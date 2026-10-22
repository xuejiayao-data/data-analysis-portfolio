# 个人数据分析项目集

这里收录了我基于 Python 完成的数据分析与建模项目，涵盖客户分群、影响因素分析与时间序列预测等场景。

## 项目列表

### 1. 航空公司客户价值分析
- **文件**：[airline-customer-value.ipynb](./airline-customer-value.ipynb)
- **技术栈**：pandas、scikit-learn、matplotlib、seaborn
- **内容概述**：
  - 清洗 6 万余条航空会员数据，处理缺失值与异常值；
  - 构建 LRFMC 五维客户价值模型；
  - 使用 K-Means 将客户聚为 5 类，并通过雷达图完成客户画像；
  - 针对高价值客户、流失风险客户等群体提出差异化营销建议。

### 2. 民宿评分影响因素分析
- **文件**：[homestay-rating-analysis.ipynb](./homestay-rating-analysis.ipynb)
- **技术栈**：pandas、statsmodels、scikit-learn、seaborn
- **内容概述**：
  - 对 2600+ 条民宿数据做文本特征抽取，构造房东资质、交通便利性等衍生变量；
  - 使用多元线性回归与决策树模型分析评分影响因素；
  - 识别出“服务周到”“干净卫生”为影响总评分的关键因素；
  - 基于特征重要性提出民宿运营优化建议。

### 3. 财政收入影响因素分析
- **文件**：[fiscal-revenue-factors.ipynb](./fiscal-revenue-factors.ipynb)
- **技术栈**：pandas、scikit-learn、灰色预测 GM(1,1)、matplotlib
- **内容概述**：
  - 使用 Lasso 回归从 13 个经济指标中筛选关键影响因素；
  - 结合 GM(1,1) 灰色预测外推未来两年特征值；
  - 使用 LinearSVR 预测财政收入，并与真实值对比验证拟合效果。

### 4. 淘宝用户行为分析
- **文件**：[user-behavior-analysis.ipynb](./user-behavior-analysis.ipynb)
- **技术栈**：pandas、matplotlib
- **内容概述**：
  - 对 10 万条用户行为数据（pv/fav/cart/buy）做时间分布与转化漏斗分析；
  - 基于行为频次将用户分为低频/中频/高频/超级四层，分析各层级购买转化率差异；
  - 发现超级用户（≥150 次行为）仅占约 21%，但购买转化率达 80.95%，显著高于低频用户的 47.83%；
  - 对比超级用户与普通用户的行为结构，提出针对高活跃用户的运营优化建议。
 

## 联系方式
- 邮箱：joya_xue@163.com
