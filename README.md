# CCAC 2022 Task 2

# 评测结果

| 队伍名称       | macro_f1   | Rank  |
|----------------|------------|-------|
| **HS100**      | **0.4202** | **1** |
| **给力队**     | **0.3756** | **2** |
| **蟹蟹爱吃粥** | **0.3748** | **3** |
| hx2021         | 0.3712     | 4     |
| BERT的信徒     | 0.3586     | 5     |
| qditem         | 0.3500     | 6     |
| 好好解释队     | 0.3347     | 7     |
| TextMidas队    | 0.2678     | 8     |
| 我要毕业队     | 0.2057     | 9     |

- 恭喜各位参赛队伍取得优异的成绩！
- 后续相关事宜请继续关注 CCAC 公众号与本代码仓库，感谢各参赛队伍的参与。
- [HS100 队伍赛题思路分享](https://aistudio.baidu.com/aistudio/projectdetail/4446086)。

---

## 面向微博话题的群体情感识别

### **任务背景**

微博等社交媒体已经成为人们日常生活中不可分割的一部分，越来越多的互联网用户参与在微博上讨论热点新闻、分享自己的观点和看法、这为研究者提供了一个庞大的可以获取流行话题、倾听公众针对热点事件意见的资源。但是，微博中与日俱增的信息与内容，大大超越了人们所能获取信息的极限，我们迫切需要一些手段辅助我们进行情感分析。之前现有的研究主要针对写作者的情感，较少有工作涉及到公众和群体对微博话题的反应情绪。本评测主要通过分析微博话题的简短描述（hashtag），预测公众可能产生的群体性反应情绪。

### **任务介绍**

本任务旨在预测在线平台用户评论中挖掘用户情感信息，可以体现大众对于热门话题的感受与情感取向。为体现本任务的时效性，我们选取了按时间排序前五条的评论文本。本任务的输入数据包含两部分：热门话题(hashtag)与前五条用户评论，输出为该话题下用户的情感取向，由三个表情标签表示。数据集中共包含24个表情标签。例如，部分表情为'[Smile]', '[给力]', '[允悲]','[给力]', '[给你小心心]', 本次测试以多分类 macro F1 值作为评测指标。

### 关键时间点

| 时间点                               | 内容                        |
| ----------------------------------- | -------------------------- |
| 2022年6月7日 10:00AM (GMT +08:00)   | 任务发布与报名启动         |
| 2022年6月30日 10:00 AM (GMT +08:00) | 训练集语料发布             |
| 2022年7月21日 10:00 AM (GMT+08:00)  | 测试集语料发布             |
| 2022年7月30日 10:00 AM (GMT +08:00) | 提交截止 （报名结束）      |
| 2022年8月8日 10:00 AM (GMT +08:00)  | 比赛结果公布               |
| 2022年8月20日 10:00 AM (GMT +08:00) | CCAC2022大会召开及颁奖典礼 |

## **预测文件提交格式**

- 提交测试结果需以 **.txt** 文件保存，其中每一行代表候选情感，第一个数字代表行 ID，如

```
0 [笑cry] [给力] [嘻嘻] 
1 [笑cry] [给力] 
2 [doge] [嘻嘻] 
3 [doge] [给力] [嘻嘻] 
4 [给力] [嘻嘻]
...
2399 [doge] [给力] [嘻嘻]
```
- 预测个数 $<=3$ 个

## **报告文件提交格式**
- 提交测试结果需以 **.pdf** 文件保存
- 报告格式参考 [ACL Template](https://www.overleaf.com/latex/templates/template-for-2-columns-acl-proceedings-style/bdxxrbqzsmpv)

## **文件命名方式**

- 预测文件以 **.txt** 文件保存，文件名为 **机构名缩写+队伍名称**，如
```
PolyU+TeamName.txt
```

- 报告文件以 **pdf** 文件保存，文件名为 **机构名缩写+队伍名称**

### FAQ

- 报名人数限制（含指导老师）：5
- 任务提交形式：report
- 是否需要提交测试结果：需要
- 是否需要提交代码：不需要
- 奖励设置情况：无
