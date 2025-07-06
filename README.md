# NL2Sql_notes
数据分析师、NL/TEXT2SQL、数据可视化、数据报告等文档笔记

## 工作流程
### 提高准确性的手段
#### 核实入参增加容错
利用group by double check疑似入参
#### 良好的Schema格式
1. 字段
2. 类型
3. 描述
4. 多个表之间的字段关系 如“外键”
#### 提供表样例数据
1. 使用df.head 获取样例数据
2. 利用group by 提供高概率的枚举值
#### 提供样例问答sql
#### 大模型对多个生成sql评分 甄选
#### 约束校验
对已知的规则进行校验，提供对话重试
# 良好的Schema格式
![img.png](img.png)


## NL2SQL Reference
[](https://www.zhihu.com/question/609600071/answer/3520041194)
[](https://arxiv.org/abs/2403.09732)
[](https://zhuanlan.zhihu.com/p/27612459266)
[](https://zhuanlan.zhihu.com/p/1915001536171476928)
[Awesome-Text2SQL](https://github.com/eosphoros-ai/Awesome-Text2SQL)
[PET-SQL](https://github.com/maohangyu/PET-SQL)
[XiYan-SQL](https://github.com/XGenerationLab/XiYan-SQL)
[vanna](https://github.com/vanna-ai/vanna)
[DB-GPT](https://github.com/eosphoros-ai/DB-GPT)
[supersonic](https://github.com/tencentmusic/supersonic)
[Chat2DB](https://github.com/CodePhiliaX/Chat2DB)
[WrenAI](https://github.com/Canner/WrenAI)
[mindsdb](https://github.com/mindsdb/mindsdb)
[data-formulator](https://github.com/microsoft/data-formulator)
[textSQL](https://github.com/caesarHQ/textSQL)
[ai-analyst](https://github.com/e2b-dev/ai-analyst)
[DATAGEN](https://github.com/starpig1129/DATAGEN)
[dbt-llm-agent](https://github.com/pragunbhutani/dbt-llm-agent)
[LuminAI-Data-Analyst](https://github.com/spandan114/LuminAI-Data-Analyst)
# 沙箱生成sql
[](https://ai.pydantic.dev/mcp/run-python/#installation)
