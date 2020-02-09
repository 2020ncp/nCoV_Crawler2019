# nCoV_Crawler2019
注：此2020NCP仓库用来整理收集保存针对特大事件可快速使用的开源项目
# 新型肺炎疫情数据爬虫+数据持久化+邮件通知



数据源来自“丁香园” ：https://3g.dxy.cn/newh5/view/pneumonia_peopleapp?from=timeline&isappinstalled=0

- 共三部分数据： 实时新闻 + 全局信息（全国 确诊 2055 例 疑似 2692 例 死亡 56 例 治愈 49 例） + 各省份疫情
- 数据库用MYSQL，建表语句在SQL目录下
- 功能：
  - jsoup获取数据，正则匹配筛选数据
  - 用mybatis+mysql做数据持久化
  - 数据发生变化时，发邮件通知

2020年2月8日，国务院联防联控新闻发布会上，新闻发言人现场发布关于新冠病毒感染的肺炎暂命名的通知，新型冠状病毒感染的肺炎统一称谓为“新型冠状病毒肺炎”，简称“新冠肺炎”，英文名为“Novel coronavirus pneumonia”，简称为“NCP”。
