# MasterThesis

#### 写作计划
* v1：翻译论文，并通顺化；
    * 明确一些术语词汇的翻译。
    * 适当增加一些例子，如：RQ2中的定义。
    * 【Done】2021.12.29
* v2：补充相关工作及绪论处的背景
    *  【Done】理顺语言，尤其是前后逻辑关系。。。
    *  【Done】所有图片加上横纵坐标，并且调整字体大小一致。
    *  check错别字、以及彭老师的修改注意事项 + 陈老师的修改建议
       *  或许可尝试用一些软件再玩一玩
* v3：自我再顺一遍语句及逻辑
    *  基于送审意见进行修改i
    *  自己再顺一遍语句及逻辑



#### V3,基于初审意见的修改【修改说明】

##### ❓一些疑问

* 修改说明，是否要附在论文末尾，然后再提交？
* 本轮修改，是不是只把审稿人的意见，**对点**改完就可以了？

##### 具体修改

```
初审1（通过，70分）
格式问题：
【done】扉页（提交学院和学校盲审版时去掉指导小组成员信息） ×（缺页）；
【done】摘要  中英文摘要用罗马数字编页码，从I开始；
【done】正文中各级标题 不同级标题之间不要直接相连，其间用一段总括的句子隔开；
【to explain，暂时删去】独创性声明和论文使用授权声明（提交学院和学校盲审版时去掉这部分） 缺少该页

正文内容:
正文内容完整详细，逻辑通顺，但有一些小的细节问题。
【done】第九页 语句不通顺，‘出现了许多第三方平台致力于收集并维护所有漏洞公告信息’—>‘出现了许多致力于收集并维护所有漏洞公告信息的第三方平台’。
【done】第十八页: 3.3 RQ1:补丁覆盖率分析各种比率写的比较混乱，例如对于包含10070个开源软件漏洞的广度，仅有1417个漏洞含有补丁（不是2190+1417+995？），补丁覆盖率为32%。
【done】第十九页: 表3-1 无漏洞信息、无补丁（有歧义，应注释在无漏洞信息、无补丁）。
【done】第二十页: 语言不准确 RQ2：补丁一致性分析
 1793（39%）的漏洞都存在于DBA和DBB中但在某一数据库中无补丁--> 1793（39%）的漏洞都存在于DBA或DBB中但在另一数据库中无补丁。
```
* 摘要  中英文摘要用罗马数字编页码，从I开始；
    * https://github.com/stone-zeng/fduthesis/issues/88
* 正文中各级标题 不同级标题之间不要直接相连，其间用一段总括的句子隔开；
    * 第2章，2.1 / 2.2与子标题之间，添加总括的句子。
    * 3.1 研究设计
    * 第六章，总结与展望。
* 有一些小的细节问题，以此类推？后面也查查？

```
初审2（通过，70分）
文章针对当前漏洞研究中漏洞补丁管理中的不足，设计了相关统计实验进行研究总结，并根据经验研究结果针对已有漏洞补丁数据库的痛点，设计了 TRACER 工具来自动识别相关漏洞的漏洞补丁进行漏洞补丁数据库的补充，通过充足的实验数据证明了 TRACER 能有效提升漏洞补丁的覆盖率和准确率。在实用性、通用性等都表现了较高的实用价值。可应用于安全社区、工业和学术界。

优点：文章研究内容具有一定的创新性、可用性，具有一定的学术价值。文章结构组织合理，逻辑清晰，行文流畅。实验充分。引用丰富。
【done】待改进地方： 本文缺少TRACER 测试时的硬件资源情况。例如运行的时间成本、物理环境或实现TARACER代码量等。
部分标点格式不统一。例如: p53 中 6.1节 (3) 中冒号。
```
* 部分标点格式不统一。例如: p53 中 6.1节 (3) 中冒号。
    * 全文check【todo】
* 待改进地方： 本文缺少TRACER 测试时的硬件资源情况。例如运行的时间成本、物理环境或实现TARACER代码量等。
    * 添加了5.2小节（实验环境准备）
    
      ```
      5.2 实验环境准备
      本文作者使用 Python 3.6 搭建实验平台，并完成工具 TRACER 的开发，TRACER 共包括 6117 行代码。实验评估中，TRACER 运行在含有 16 核 Intel Xeon 型 CPU (2.10GHz)、62GB 内存的服务器上。基于从广度数据集中随机抽样的 200 个漏 洞，运行结果表明，TRACER 在该实验环境下完成一次漏洞补丁定位的平均用时
      约为 22 分钟。
      ```
    
      











#### 彭老师 comments

Group Notice
几个共性问题大家请注意
1）硕士论文指导小组放3个老师即可，具体放哪3个跟负责的老师商量
2）避免长句子问题，即用了一堆逗号的长句子，注意断句。同时注意标点使用，例如：简单短语的并列一般用顿号，而不是逗号；一句话说完了就用句号结束再另起一句，不要滥用逗号。
3）不要在一个章节的开头一个字都没有的情况下就直接出现图表。
4）图表内容如果来自其他文献那么图表标题上也要标引用，文字内容绝对不能拷贝抄袭（哪怕从网页上复制几句），如果是引用那么规范标注引文。
5）名词术语及其大小写统一，例如不要“Java”、“java”等各种写法都有。
6）全文自己多通读几遍，避免笔误和不通顺。整体模板要使用实验室要求的Latex模板。
7）参考文献数量需要足够，硕士论文一般40篇以上，而且大部分应该是正规的论文而不是网站或网页，中英文参考文献都应该有一些。

Group Notice
还有一个共性问题是参考文献格式不规范不统一的问题。例如同样是国际会议，有的是Proceedings of这种格式，有的不是；有的有会议举办地有的没有。请按照规范统一标准。


#### 成文后，需check
-------------------------[Done]
* 【Done】url的引用 -> 脚注引用(加字数)
* 【Done】段首，统一用：，如\textbf{启发式方法一：}
* 【Done】所有符号的中文化 如：括号，空格
* 【Done】中文语法check？断句及标点符号：，?
* 【Done】如：Requested Commit VS. Merged Commits , 英语单词首字母大写
* 【Done】引号check：“引用分析” ？ ``bugzilla"？
* 【Done】统一的命名，如：会确保commit message中包含该漏洞的CVE ID、 Advisory ID或Issue ID
* 【Done】sec的引用，全部统一 （Sec. \ref{sec:study}）？ 
* 【Done】Red Hat
* 论文中的很多例子都可以直接放图哇
* 先根据chen老师发的ppt，自查一遍问题
* 【前后逻辑是否顺承？上一句和下一句之间是否逻辑通顺？】
* 【文章章节直接，逻辑是否通顺？由绪论打头，章节间增加过渡语句】
* “分析发现：”这个冒号能这么用？

#### 措辞:
* 广度数据集构建 / 深度数据集构建 ?
* 三种类型：一对一、\tocheck{一对一组}及一对多
* advisory analysis ，reference analysis，reference Augment: 公告节点分析和引用节点分析, 知识源扩增?
* \tool 将引用链接节点分为三种类型：补丁节点（Patch Node）、\tocheck{Issue 节点}（Issue Node）和\tocheck{混合节点}（Hybrid Node）。
* 漏洞知识源？从多个\tocheck{漏洞知识源}（即：NVD、Debian\cite{debian}、RedHat\cite{redhat}和GitHub）
