# FEE-Purchasing-DashBoard

__项目描述__:<br>
该项目为每日早8点自动爬取新发地官网发布的当日菜价，制作可视化文档，自动邮件发送给相关部门人员<br>

__目的__：<br>
1.采购人员实时查看新发地的市场价格，对于异常变化的原材及时进行调整。<br>
2.定期查看采购情况，及时发现采购异常数据，及时进行核对和修改。<br>

__使用部门__:采购中心<br>

__数据来源__：<br>
     1.采购部门提供的历史采购情况<br>
     2.利用Python实时爬取和处理的新发地菜品价格
## 目录
+ [__数据爬虫__](https://github.com/EvelynZP/FEE-Purchasing-DashBoard/blob/master/FEE-%E9%87%87%E8%B4%AD-%E6%96%B0%E5%8F%91%E5%9C%B0%E8%8F%9C%E4%BB%B7%E5%AE%9E%E6%97%B6%E6%8A%93%E5%8F%96.ipynb)
     + 定制请求
     + 解析返回数据
     + 存储数据
     + 数据处理及可视化
+ [__数据处理及可视化__](https://github.com/EvelynZP/FEE-Purchasing-DashBoard/blob/master/FEE-%E9%87%87%E8%B4%AD-%E5%8F%AF%E8%A7%86%E5%8C%96%E7%9C%8B%E6%9D%BF.ipynb)
     + 数据预处理
     + 每日采购数量条形图
     + 分类占比饼图
     + 价格波动折线图
     + 整合图表
+ __自动邮件__



### 结果展示<br>
__以下采购数量，金额，单价，差异以及采购占比都为公司采买数据（已脱敏），其余图表都为当日新发地参考菜价__<br>

![结果展示](https://github.com/EvelynZP/FEE-Purchasing-DashBoard/blob/master/Purchasing_Dashboard.png)





