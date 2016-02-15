---
layout: post
title: 团队文档命名规约
description: 文档命名看似简单，但其实这体现了你对你的对象在当前体系中的关系/作用的理解深度，往大了说，命名还直接反映了你对整个资源结构的理解。
category: community
---



文件命名看似简单，但其实这体现了**你对你的对象在当前体系中的关系/作用的理解**深度，往大了说，命名还直接反映了**你对整个资源结构的理解**。

统一的命名规约，对团队，尤其对团队知识管理来说，非常重要。否则创建一文件，队友很可能难以识别所含内容。

为减少这种不必要的团队协作成本，特整理一份团队文档命名规约，文件命名也可参考。

## 命名原则

- 命名尽量以 **ASCII 字串**（别用汉语拼音！）进行，尤其在取 WikiName 时
	- 方便同一目录下顺次查找
	- URL 干净清晰
- 命名尽量**简明**
	- [采用大驼峰式命名法](https://zh.wikipedia.org/wiki/%E9%A7%9D%E5%B3%B0%E5%BC%8F%E5%A4%A7%E5%B0%8F%E5%AF%AB)，比如 `HbDocName`
	- 前后两个单词相连的字母重复时，只写一个，比如 `OBSetting`（本是 `OBSSetting`），`OBSuggest`（本是 `OBSSuggest`）
	- 日期使用6位数字标注，默认忽略年份前两位以减少字符，比如 `151203`（2015年12月3日）

## 常用缩写

既然以英文命名，缩写不可避免。团队常用缩写如下（注意大小写）：

+ `WIP` ~ Work In Press 任务进行中
+ `PR` ~ Public Relationship 公关稿
+ `HR` ~ Human Resource 人力资源/人事
+ `Ml` ~ Mailling-list 邮件列表通告
+ `SOP` ~ Standard Operating Procedure 标准操作流程
+ `BGM` ~ Background Music 背景音乐
+ `Hb` ~ Handbook 手册
+ `Doc` ~ Document 文档
+ `Docs` ~ Google Docs 谷歌在线共享文档
+ `Idx` ~ Index 索引
+ `Info` ~ Infomation 资料(注意和索引类文档性质上的区别)
+ `Rec` ~ Record 录音
+ `Rep` ~ Report 报告
+ `Res` ~ Resource 资源
+ `Ref` ~ Reference 参考（资料）
+ `Tep` ~ Template 模板
+ `Del` ~ Delete 删除
+ `upd` ~ update 更新
+ `KM` ~ Knowledge Management 知识管理
+ `LM` ~ LogMeeting 会议纪要
+ `wt` ~ worktile 
+ `w` ~ week 周
+ `d` ~ day 天
+ `4` ~ for
+ `2` ~ to 




## 命名规则

### 常规命名结构：文档属性-类别/项目/使用者


1. 先定位文档属性，比如是 `idx` `info` `Hb` 还是 `Log`（这其实在引人思考所建内容的整体结构和关联）。
   - `Hb` 里一般会链接到 `Idx` `Info` 等以便进一步参考调用的内容
   - `Idx` ，注意这是**索引索引索引！**里面一般会有较多链接，尤其是 `info` 文档链接
   - `Info` 一般里头是可直接复制使用或者不需再进一步点击的内容
   - `Log` 沟通纪要、会议备忘等

 如此，在一个目录下浏览时，文档按类似树状的结构展开，比如 `Hb` ：
 
 - HbDoc ~ 文档创建规约
 - HbDocName ~ 文档命名规约
 - HbMentor ~ 教练手册
 - HbPM ~ 项目经理手册


 一些系列文档不前缀文档属性代号也 OK 。比如我们课程每周都有微信群答疑，答疑记录文档，新手一般会延续中文文档命名习惯（ `0w 微信群答疑纪要` ）以 `Log0wQA`命名，但更合适的应该是`LogQAw0`。若此，在同一个目录下，可以快速定位这个系列文档下的所有内容。若目录下，并无其它 QA 系列文档的需求，根据简明原则，还可直接命名为 `QAw0`。

2. 根据具体情境和想达成的效果确定单词的先后顺序。比如

   - HbBrandOM
   - HbOMBrand
 
	两种命名方式其实都可以让人一眼识别这是 OM 品牌使用手册，用哪种命名方式主要看这个文档在什么情境下，以及自己想干嘛：
 
   - 若在集团的 wiki 下，希望兄弟公司在同一个事务上有更多的借鉴，就以前者命名
   - 若各公司相对独立，希望每个子公司的同事更方便找到本公司的内容，以后者命名更合适

### 版本号标注规则

手册等反复修改使用的文档，版本号采用[语义化版本控制](http://semver.org/lang/zh-CN/)的命名方式。但其实基于 git 进行文档管理后，不标注版本号也无妨。

会议纪要等基于时间的文档，以日期进行命名，比如：

- LM2015Q3 ~ 2015年第3季度季会纪要
- LMApp151203 ~ 2015年12月3日产品会议纪要
	- 如果经常开产品会或其它某个主题的会，就把主题放日期前形成一个单独序列
	- 如果是临时的主题，就放在日期后面，一目了然以便日后查找，比如 LM151205Community ~ 2015年12月5日社群运营讨论纪要

## Tips
  
若刚接触这样的命名规约，难免不知所措。不必担心，多看别人怎么命名,根据命名猜测文档内容并验证，慢慢就轻车熟路啦，比如可以看 

-  [@ZoomQuiet 大妈](http://zoomquiet.io/) 在[七牛云](http://openmindclub.qiniudn.com/)中共享的文件
- GitHub 各 wiki 中的文档等（内部仓库，非团队成员别点啦）
    - [Home · anrenmind/eopenmind.com Wiki](https://github.com/anrenmind/eopenmind.com/wiki)
    - [Home · anrenmind/anrenmind.com Wiki](https://github.com/anrenmind/anrenmind.com/wiki)
    - [Home · OpenMindClub/2.OMOOC.py Wiki](https://github.com/OpenMindClub/2.OMOOC.py/wiki)

是不是十分简明干净？

--

Anyway，文档命名规则没有对错之分，若单看某个文件名，队友就能明白其中所含内容，协作需要时能即时调取，这就是好规则。

祝各位都远离「各人用词、命名习惯不一样，难以形成共识，徒增团队协作成本」的烦恼（比如俺在[《GitHub 协作五大业余姿势》](http://ishanshan.top/community/HbGitHubCooperate.html) 提到的现象，哈哈）!


## CHANGELOG

- 160210 增补完善后在 Blog 发布
- 151220 在团队仓库创建
