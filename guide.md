## 翻译流程：

1. 准备工作
    - 获取版权
    - 格式转换：用mathpix实现PDF转markdown，
    - 机器翻译，用有道、火山、百度等引擎翻译文章到Word，作为参考
2. 建立项目：发起人在Github建立相关项目，把文章的markdown放上去
3. 翻译：翻译人员翻译文章，最后提交PR到发起人项目上
    - 在github上fork相关项目
    - 比对多家机器翻译结果，给出初版译文
    - 在本地，逐句修正句子，译文在原文之后；达到内容可信，流畅
    - 提交到自己的Github账户上
    - 提交PR到发起人的翻译项目上
4. 校对，通读校对，纠错、修正难受的句子。建议2~3轮，依次进行
    - 第1轮校对和PR
    - 第2轮校对和PR
    - 第3轮校对和PR
5. 定稿
    - 删除文章中的原文
    - 美化其中的截图
    - 修正文章的图表地址，保障国内外访问速度    


## 注意事项：

1. 转换后的md文件格式问题
    - 得到的md文件\section{} 等LaTeX代码手工硬编码修改为 ## 2.3 类似的章节名
    - 部分公式转换错误，在vscode中可以直接预览修正
    - LaTeX表格修正为md中的，或者直接截图到云端，超链接引入
2. 翻译问题
    - 注意翻译的时候检查和修正公式、图表
    - 拿不住的地方请以这种形式标记，【译者注：XXX】。比如【译者注：专业名词】、【译者注：内容不理解】、【表格不对】
    - 疑问的地方请定期汇总反馈出来，以解决问题
    - 翻译尽量意译，用通顺的中文表达原文意思。读起来顺畅、自然。
    - 原文的大长句、复杂从句，可以拆分为多句，符合中文表达习惯。
    - 修正翻译的时候很大的一个障碍是当前版本先入为主的影响，遇到拗口句子的时候，可以脑子里想一想同样的意思如何自然的表达。

3. 合作问题
    - 部分校对人员（比如老教授）可能不会使用Github等，此时弄成word给他们。他们校对完发过来，我们代替修改再提交PR。


## 辅助工具：

1. VS-code，本地编辑、markdown渲染、公式渲染等
2. [Git操作和GitHub](https://chinese.freecodecamp.org/news/how-to-make-your-first-pull-request-on-github/)，版本控制，多人协作
3. 线上翻译工具，如有道、百度、火山；翻译浏览器插件，推荐火山翻译
4. PDF转换工具，转word可以用WPS，转markdown可以线上mathpix
 
