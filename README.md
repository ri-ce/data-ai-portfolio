# Data and AI Project Portfolio

大数据与人工智能个人项目作品集首页。该仓库只负责项目展示和导航，
两个项目的代码、测试、报告与运行说明分别位于独立仓库。

## 在线页面

- 作品集首页：`https://ri-ce.github.io/data-ai-portfolio/`
- 大数据项目：`https://ri-ce.github.io/nyc-taxi-data-pipeline/`
- 人工智能项目：`https://ri-ce.github.io/telco-churn-ml-service/`

## 项目一：NYC Yellow Taxi 大数据处理流水线

- 源码：`https://github.com/ri-ce/nyc-taxi-data-pipeline`
- 测试报告：`https://ri-ce.github.io/nyc-taxi-data-pipeline/test-report.html`
- 原始记录：3,475,226 条
- 清洗后记录：3,322,947 条
- 数据保留率：95.62%

项目使用 DuckDB 和 SQL 直接处理 Parquet 数据，覆盖质量检查、异常清洗、
日期与小时聚合、支付方式分析、热门区域分析以及报告生成。

## 项目二：Telco Customer Churn 机器学习预测服务

- 源码：`https://github.com/ri-ce/telco-churn-ml-service`
- 测试报告：`https://ri-ce.github.io/telco-churn-ml-service/test-report.html`
- 数据规模：7,043 条
- ROC-AUC：84.14%
- Recall：78.34%

项目使用 Scikit-learn 完成数据清洗、特征工程、五折交叉验证和模型比较，
并通过 FastAPI 提供流失概率预测接口。

