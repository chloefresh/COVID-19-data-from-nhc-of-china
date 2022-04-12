# COVID-19-data-from-nhc-of-china

---

# 前言

新冠肺炎疫情数据文本结构化，包括各省市新增确诊病例和无症状病例（来源：国家卫健委）.2021/10/1~2022/4/10

随手记录，那些年我搞过的新冠肺炎数据.

Parsing unstructured COVID-19 texts from NHC of CHINA to structured tabular data.

Including the new confirmed and new asymptomatic case


---

# 一、数据收集-Collecting Raw Texts
数据来源：http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml

收集工具：八爪鱼 https://zhuanlan.zhihu.com/p/105537407

Using a very powerful crawler "八爪鱼", we can get raw data in JSON format. 

# 二、正则表达式抽取相关数据-Regex

正则表达式测试网站 https://regex101.com/

代码都在ipynb文件里
