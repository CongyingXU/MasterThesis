# MasterThesis

#### 写作计划
* v1：翻译论文，并通顺化；
    * 明确一些术语词汇的翻译。
    * 适当增加一些例子，如：RQ2中的定义。
* v2：补充相关工作及绪论处的背景


#### 成文后，需check
* url的引用 -> 脚注引用(加字数)
* 所有符号的中文化 如：括号
* 中文语法check？断句及标点符号，想想办法？
* 如：Requested Commit VS. Merged Commits , 英语单词首字母大写
* 【前后逻辑是否顺承？上一句和下一句之间是否逻辑通顺？】
* 【文章章节直接，逻辑是否通顺？由绪论打头，章节间增加过渡语句】
* “分析发现：”这个冒号能这么用？
* 引号check：“引用分析” ？ ``bugzilla"？
* 多余空格的check
* 统一的命名，如：会确保commit message中包含该漏洞的CVE ID、 Advisory ID或Issue ID
* sec的引用，全部统一 （Sec. \ref{sec:study}）？ 看下Kaifeng的论文？
* Red Hatqua
* 论文中的很多例子都可以直接放图哇

* 先根据chen老师发的ppt，自查一遍问题

#### 措辞:
* 广度数据集构建 / 深度数据集构建 ?
* 在\tocheck{\ref{sec:preparation}小节}中? sec的引用咋写？参考下
* 三种类型：一对一、\tocheck{一对一组}及一对多
* advisory analysis ，reference analysis，reference Augment: 公告节点分析和引用节点分析, 知识源扩增?
* \tool 将引用链接节点分为三种类型：补丁节点（Patch Node）、\tocheck{Issue 节点}（Issue Node）和\tocheck{混合节点}（Hybrid Node）。
* 到底是写：commit？还是写：提交？
* 漏洞知识源？从多个\tocheck{漏洞知识源}（即：NVD、Debian\cite{debian}、RedHat\cite{redhat}和GitHub）

* title：不太敢定为“知识”感觉太大了。。先统一改为信息把。