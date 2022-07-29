# CCAC 2022 Task 2

# ！！Update！！提交入口已开放，请尽快提交

[预测文件提交入口](https://workspace.jianguoyun.com/inbox/collect/1e540c395eca48d08b7c43d4aed0ad34/submitv2)

[报告文件提交入口](https://workspace.jianguoyun.com/inbox/collect/71c6649177e6423f842ff5634df0bc9c/submitv2)

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

### **提交格式**

- 提交测试结果需以 .txt 文件保存，其中每一行代表候选情感，第一个数字代表行 ID，如

```
0 [笑cry] [给力] [嘻嘻] 
1 [笑cry] [给力] 
2 [doge] [嘻嘻] 
3 [doge] [给力] [嘻嘻] 
4 [给力] [嘻嘻]
```
- 提交方式：待定
- 命名方式：待定

### **报名方式**

~~https://docs.qq.com/form/page/DYnNmWHR4YlRtQ3Fz~~

原报名方式已失效，请按照以下格式将报名信息发送至邮箱 yixia.li@connect.polyu.hk.

![CCAC_apply_form](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/9d434622-97fa-4c14-b85c-98124879b2c4/CCAC_apply_form.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220701%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220701T062300Z&X-Amz-Expires=86400&X-Amz-Signature=7194212e1db42f0b7754de0ea2786c7798820766eb77f44c485e4ea0f7c396bc&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22CCAC_apply_form.png%22&x-id=GetObject)

### FAQ

- 报名人数限制（含指导老师）：5
- 任务提交形式：report
- 是否需要提交测试结果：需要
- 是否需要提交代码：不需要
- 奖励设置情况：无
