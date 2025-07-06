# 基于上海餐厅排行榜的数据分析

## 项目简介
本项目基于 TripAdvisor 上海餐厅数据进行全面的数据分析和可视化展示，旨在探索上海餐饮行业的特点和趋势。

## 数据来源
- 数据来源：TripAdvisor 网站
- 数据文件：
  - `tripadvisor_shanghai.csv`：原始数据
  - `tripadvisor_shanghai_fixed_cleaned.xlsx`：清洗后的数据

## 分析内容
项目包含多个维度的分析：
1. 餐厅评分分布分析
2. 评论数量分布分析
3. 餐厅类型分析
4. 价格区间分析
5. 评分与评论数关系分析
6. 区域分布分析
7. 区域与价格关系分析

## 可视化展示
所有可视化结果保存在 `restaurant_plots` 目录下：
1. `1_rating_distribution.html`：餐厅评分分布
2. `2_review_distribution_boxplot.html`：评论数量分布箱线图
3. `3_type_radar_chart.html`：餐厅类型雷达图
4. `4_price_polar_bar.html`：价格极坐标条形图
5. `5_rating_review_scatter.html`：评分-评论数散点图
6. `6_district_funnel.html`：区域分布漏斗图
7. `7_district_sunburst.html`：区域旭日图
8. `8_district_price_heatmap.html`：区域-价格热力图

## 项目文件
- `Project_tripadvisor/`：数据爬取相关代码
- `Visualization.ipynb`：数据分析和可视化的主要代码
- `restaurant_plots/`：可视化结果输出目录

## 使用技术
- Python 数据分析库：pandas, numpy
- 数据可视化库：plotly
- 网页爬虫：requests, BeautifulSoup
