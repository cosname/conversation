
# 50 Years of Data Science

# 数据科学50年

David Donoho, Department of Statistics, Stanford University, Standford, CA

David Donoho  加利福尼亚州 斯坦福大学统计系


# Abstract

# 摘要

More than 50 years ago, John Tukey called for a reformation of academic statistics. In "The Future of Data Analysis," he pointed to the existence of an as-yet unrecognized science, whose subject of interest was learning from data, or "data analysis." Ten to 20 years ago, John Chambers, Jeff Wu, Bill Cleveland, and Leo Breiman independently once again urged academic statistics to expand its boundaries beyond the classical domain of theoretical statistics; Chambers called for more emphasis on data preparation and presentation rather than statistical modeling; and Breiman called for emphasis on prediction rather than inference. Cleveland and Wu even suggested the catchy name "data science" for this envisioned field. A recent and growing phenomenon has been the emergence of "data science" programs at major universities, including UC Berkeley, NYU, MIT, and most prominently, the University of Michigan, which in September 2015 announced a $100M "Data Science Initiative" that aims to hire 35 new faculty. Teaching in these new programs has significant overlap in curricular subject matter with traditional statistics courses; yet many academic statisticians perceive the new programs as "cultural appropriation." This article reviews some ingredients of the current "data science moment," including recent commentary about data science in the popular media, and about how/whether data science is really different from statistics. The now-contemplated field of data science amounts to a superset of the fields of statistics and machine learning, which adds some technology for "scaling up" to "big data." This chosen superset is motivated by commercial rather than intellectual developments. Choosing in this way is likely to miss out on the really important intellectual event of the next 50 years. Because all of science itself will soon become data that can be mined, the imminent revolution in data science is not about mere "scaling up," but instead the emergence of scientific studies of data analysis science-wide. In the future, we will be able to predict how a proposal to change data analysis workflows would impact the validity of data analysis across all of science, even predicting the impacts field by field. Drawing on work by Tukey, Cleveland, Chambers, and Breiman, I present a vision of data science based on the activities of people who are "learning from data," and I describe an academic field dedicated to improving that activity in an evidence-based manner. This new field is a better academic enlargement of statistics and machine learning than today's data science initiatives, while being able to accommodate the same short-term goals. Based on a presentation at the Tukey Centennial Workshop, Princeton, NJ, September 18 , 2015.

50多年前，John Tukey曾呼吁对学术统计学（academic statistics）进行改革。在“数据分析之未来”（The Future of Data Analysis）文章中，他指出：存在一门尚未被认识到的科学，其研究主题是从数据中学习，或者说“数据分析”。10至20年前，John Chambers、吴建福（Jeff Wu）、Bill Cleveland 和 Leo Breiman 不约而同地再次敦促学术统计学将其边界扩展到理论统计学的经典领域之外；Chambers呼吁更加重视数据准备和数据展示，而不只是统计建模；Breiman呼吁强调预测而不是推断。Cleveland和吴建福甚至为这个设想中的领域提出了一个朗朗上口的名字“数据科学”。最近一个日益增长的现象是，包括加州大学伯克利分校（UC Berkeley）、纽约大学（NYU）、麻省理工学院（MIT）在内的诸多大学都开设了“数据科学”项目，其中最知名的是密歇根大学（University of Michigan）于2015年9月宣布的“数据科学计划”，该计划预计耗资1亿美元，招聘35名新教师。这些新项目的教学在课程主题上与传统统计课程有很大的重叠；然而，许多学术统计学家将新项目视为“新瓶装旧酒”。本文回顾了当前“数据科学时刻”的一些组成部分，包括最近媒体上广泛传播的关于数据科学的讨论，以及数据科学与统计学的区别。现在设想的数据科学领域相当于统计学和机器学习领域的超集，它增加了一些“扩展”到“大数据”的技术。这个超集是由商业而非才智发展驱动的。这样的选择，很可能会错过未来50年真正重要的才智活动。因为所有的科学本身都将很快成为可以挖掘的数据，所以数据科学即将发生的革命不仅仅是“扩大规模”，而是会激发全学科范围下的数据分析科学研究。在未来，我们将能够预测，改变数据分析工作流程的提议将会如何影响所有科学领域数据分析的有效性，甚至逐个领域预测影响。在借鉴了Tukey、Cleveland、Chambers和Breiman的工作后，我设想了未来“从数据中学习”的工作者们的数据科学活动愿景，并描述了一个致力于以循证方式改进这一活动的学术领域。这一新领域比今天的数据科学计划更好地扩大了统计学和机器学习的学术范围，同时能够实现同样的短期目标。本文基于2015年9月18日在新泽西州普林斯顿Tukey百年研讨会上的演讲。


# 1. Today's Data Science Moment

# 1. 今天的数据科学时刻

In September 2015, as I was preparing these remarks, the University of Michigan announced a \$100 million "Data Science Initiative" (DSI) $^{1}$, ultimately hiring 35 new faculty.


2015年9月，在我准备这些演讲时，密歇根大学发布了一项耗资1亿美元的“数据科学计划”（DSI） $^{1}$，其将最终聘请35名新教师。


The university's press release contains bold pronouncements:

该大学的新闻稿包含一项大胆的声明：

"Data science has become a fourth approach to scientific discovery, in addition to experimentation, modeling, and computation," said Provost Martha Pollack.

“除了实验、建模和计算之外，数据科学已经成为科学发现的第四种方法，”教务长Martha Pollack说道。


The website for DSI gives us an idea what data science is:

DSI的网站给出了数据科学的定义：

"This coupling of scientific discovery and practice involves the collection, management, processing, analysis, visualization, and interpretation of vast amounts of heterogeneous data associated with a diverse array of scientific, translational, and inter-disciplinary applications."


“数据科学是科学发现和实践的结合，它涉及：收集、管理、处理、分析、可视化和解释与各种科学、转化和跨学科应用相关的大量异质数据。”

This announcement is not taking place in a vacuum. A number of DSI-like initiatives started recently, including

这一计划并非孤例。最近开始了许多类似DSI的计划，包括

(A) Campus-wide initiatives at NYU, Columbia, MIT, ...

(B) New master's degree programs in data science, for exam- ple, at Berkeley, NYU, Stanford, Carnegie Mellon, University of Illinois, ...

(A) 学校层面的计划，比如在纽约大学、哥伦比亚大学、麻省理工学院……

(B) 数据科学的新硕士项目，比如在伯克利、纽约大学、斯坦福大学、卡内基梅隆大学、伊利诺伊大学……

There are new announcements of such initiatives weekly. $^{2}$


每周都有此类举措的新公告出现 $^{2}$。




> [2] For an updated interactive geographic map of degree programs, see http://data-science-university-programs.silk.co

> [2] 有关学位课程的更新的交互式地理图，请参见 http://data-science-university-programs.silk.co

# 2. Data Science "Versus" Statistics

# 2. 数据科学与统计

Many of my audience at the Tukey Centennial-where these remarks were originally presented-are applied statisticians, and consider their professional career one long series of exercises in the above "...collection, management, processing, analysis, visualization, and interpretation of vast amounts of heterogeneous data associated with a diverse array of ...applications." In fact, some presentations at the Tukey Centennial were exemplary narratives of "..collection, management, processing, analysis, visualization, and interpretation of vast amounts of heterogeneous data associated with a diverse array of ... applications."

我在Tukey百年纪念大会上的许多听众都是应用统计学家，他们认为他们的职业生涯便是上述“……收集、管理、处理、分析、可视化和解释与各种应用相关的大量异构数据”。事实上，Tukey百年纪念会上的一些演讲的确是这一连串工作的典范。



To statisticians, the DSI phenomenon can seem puzzling. Statisticians see administrators touting, as new, activities that statisticians have already been pursuing daily, for their entire careers; and which were considered standard already when those statisticians were back in graduate school.

对统计学家来说，数据科学计划（DSI）似乎令人费解。统计学家们认为，他们在整个职业生涯中每天都在从事的工作，被管理人员吹捧为成了鲜事；当这些统计学家回到学院时，这些工作已经被认为是普遍的。


The following points about the U of M DSI will be very telling to such statisticians:

关于密歇根大学“数据科学计划”的以下几点说明对这类统计学家来说非常重要：

- U of M's DSI is taking place at a campus with a large and highly respected Statistics Department
- The identified leaders of this initiative are faculty from the Electrical Engineering and Computer Science department (AL Hero) and the School of Medicine (Brian Athey).
- The inaugural symposium has one speaker from the Statistics department (Susan Murphy), out of more than 20 speakers.


- “数据科学计划”的发起者，密歇根大学，已经拥有一个庞大且备受尊敬的统计系。
- 该计划的领导者是电气工程与计算机科学系（AL Hero）和医学院（Brian Athey）的教师。
- 首届研讨会有20多名发言者，其中只有一名来自统计系，Susan Murphy。

Inevitably, many academic statisticians will perceive that statistics is being marginalized here; $^{3}$ the implicit message in these observations is that statistics is a part of what goes on in data science but not a very big part. At the same time, many of the concrete descriptions of what the DSI will actually do will seem to statisticians to be bread-and-butter statistics. Statistics is apparently the word that dare not speak its name in connection with such an initiative! $^{4,5}$

不可避免地，许多学术统计学家会认为统计在这里被边缘化了 $^{3}$；这种观点中的潜台词是，统计是数据科学的一部分，但不是很大的一部分。与此同时，对“数据科学计划”实际操作的许多具体描述，在统计学家看来似乎都是些最基本的统计学知识。统计显然与这样的计划甚至谈不上太大关系 $^{4,5}$！

 
Searching the web for more information about the emerging term "data science," we encounter the following definitions from the Data Science Association's "Professional Code of Conduct" (http://www.datascienceassn.org/code-of-conduct.html)

在网上搜索有关“数据科学”这一新兴术语的更多信息时，我们会看到数据科学协会“专业行为准则”中的以下定义(http://www.datascienceassn.org/code-of-conduct.html)


> "Data Scientist" means a professional who uses scientific methods to liberate and create meaning from raw data.

> “数据科学家”是指使用科学方法从原始数据中发掘并创造意义的专业人员。

To a statistician, this sounds an awful lot like what applied statisticians do: use methodology to make inferences from data. Continuing:

对统计学家来说，这听起来不就是应用统计学家的工作嘛：使用统计方法从数据中做出推断。还有：


> "Statistics" means the practice or science of collecting and analyzing numerical data in large quantities.

> “统计学”是指大量收集和分析数据的实践或科学。

To a statistician, this definition of statistics seems already to encompass anything that the definition of data scientist might encompass, but the definition of statistician seems limiting, since a lot of statistical work is explicitly about inferences to be made from very small samples-this been true for hundreds of years, really. In fact statisticians deal with data however it arrives-big or small.

对统计学家来说，统计学的这个定义似乎已经包含了数据科学家定义可能包含的任何内容，但是统计学家的定义似乎又是有限的，因为许多统计工作都是从非常小的样本中进行推断——几百年来一直如此。但事实上，统计学家处理的是数据，无论大小。

The statistics profession is caught at a confusing moment: the activities that preoccupied it over centuries are now in the limelight, but those activities are claimed to be bright shiny new, and carried out by (although not actually invented by) upstarts and strangers. Various professional statistics organizations are reacting:

统计行业正处在一个令人困惑的时刻：几个世纪以来统计一直关注的领域现在成为了焦点，但这些领域经由“暴发户”和“路人甲”开发包装后（尽管实际上不是由他们发明的），却变得光鲜亮丽焕然一新。各种专业统计组织正在做出反应：


- **Aren't we Data Science?** 
Column of ASA President Marie Davidian in AmStat News, July 2013 (http://magazine.amstat.org/blog/2013/07/01/datascience/)

- **A grand debate: is data science just a "rebranding" of statistics?** Martin Goodson, co-organizer of the Royal Statistical Society meeting May 19, 2015, on the relation of statistics and data science, in internet postings promoting that event.

- **Let us own Data Science.** IMS Presidential address of Bin Yu, reprinted in IMS bulletin October 2014 (http://bulletin.imstat.org/2014/10/ims-presidential-address-let-us-own-datascience/)

- **我们不是数据科学吗？** 
2013年7月，美国国家统计局（AmStat）新闻中美国统计学会（ASA）主席Marie Davidian的专栏（http://magazine.amstat.org/blog/2013/07/01/datascience/）

- **一场盛大的辩论：数据科学只是统计学的“换壳”吗？** Martin Goodson，2015年5月19日英国皇家统计学会（Royal Statistical Society）统计与数据科学关系会议的联合组织者，他在互联网上发布了宣传该活动的帖子。

- **让我们拥有数据科学。** 国际数理统计学会（IMS）主席郁彬的发言，转载于2014年10月的IMS bulletin（http://bulletin.imstat.org/2014/10/ims-presidential-address-let-us-own-datascience/）




One does not need to look far to find blogs capitalizing on the befuddlement about this new state of affairs:

你将很容易发现，不少博主也对这种新形势表达了困惑：

- **Why Do We Need Data Science When We've Had Statistics for Centuries?** Irving Wladawsky-Berger, Wall Street Journal, CIO report, May 2, 2014
- **Data Science is statistics.** When physicists do mathematics, they don't say they're doing number science. They're doing math. If you're analyzing data, you're doing statistics. You can call it data science or informatics or analytics or whatever, but it's still statistics. ...You may not like what some statisticians do. You may feel they don't share your values. They may embarrass you. But that shouldn't lead us to abandon the term "statistics." Karl Broman, Univ. Wisconsin (https://kbroman.wordpress.com/2013/04/05/data-science-is-statistics/ )

- **我们已经发展了几个世纪的统计学，为什么还需要数据科学？** Irving Wladawsky-Berger，华尔街日报，首席信息官报告，2014年5月2日
- **数据科学就是统计学。** 当物理学家做数学的时候，他们不会说他们在做数字科学。他们就是在做数学。如果你在分析数据，你就是在做统计。你可以称之为数据科学、信息学、分析学或其他什么，但它仍然是统计……你可能不喜欢一些统计学家做的事情；你可能觉得他们不认同你的价值观；他们可能会让你难堪。但这不应该导致我们放弃“统计”一词，Karl Broman，威斯康星大学（https://kbroman.wordpress.com/2013/04/05/data-science-is-statistics/）


On the other hand, we can find provocateurs declaiming the (near-) irrelevance of statistics:

另一方面，我们可以发现另外一种声音，宣称统计学无关紧要：

- Data Science without statistics is possible, even desirable. Vincent Granville, at the Data Science Central Blog (http://www.datasciencecentral.com/profiles/blogs/data-science-without-statisticsis-possible-even-desirable)
- Statistics is the least important part of data science. Andrew Gelman, Columbia University (http://andrewgelman.com/2013/11/14/statistics-least-important-part-data-science/)

- **没有统计学的数据科学是可能的，甚至是理想的**。 Vincent Granville，Data Science Central Blog（http://www.datasciencecentral.com/profiles/blogs/data-science-without-statisticsis-possible-even-desirable）
- **统计学是数据科学中最不重要的部分**。 Andrew Gelman, 哥伦比亚大学（http://andrewgelman.com/2013/11/14/statistics-least-important-part-data-science/）

Clearly, there are many visions of data science and its relation to statistics. In my discussions with others, I have come across certain recurring "memes." I now deal with the main ones in turn.

显然，有许多关于数据科学及其与统计的关系的不同观点。在我与其他人的讨论中，我遇到了某些反复出现的“模因”（memes）。我现在依次回应其中主要的几点。

> 译者注：根据《牛津英语词典》，模因（memes）被定义为：“文化的基本单位，通过非遗传的方式，特别是模仿而得到传递”，源自英国著名科学家理查德·道金斯（Richard Dawkins）所著的《自私的基因》（The Selfish Gene）一书，其含义是指“在诸如语言、观念、信仰、行为方式等的传递过程中与基因在生物进化过程中所起的作用相类似的那个东西。”



> [3] Although, as the next footnote shows, this perception is based on a limited information set.

> [3] 尽管，正如下一个脚注所示，这种看法是基于有限的信息集。


> [4] At the same time, the two largest groups of faculty participating in this initiative are from EECS and statistics. Many of the EECS faculty publish avidly in academic statistics journals-I can mention AL Hero himself, Raj Rao Nadakaduti and others. The underlying design of the initiative is very sound and relies on researchers with strong statistics skills. But that is all hidden under the hood.

> [4] 同时，参与这项倡议的两个最大的教师群体来自EECS（电气工程与计算机科学）和统计学。EECS的许多教员都热衷于在学术统计期刊上发表文章——我可以提到AL Hero本人、Raj Rao Nadakaduti等人。该计划的基础设计非常完善，依赖于具有强大统计技能的研究人员。但这一切都隐藏在引擎盖之下。

> [5] Several faculty at University of Michigan wrote to tell me more about their MIDAS initiative and pointed out that statistics was more important to MIDAS than it might seem. They pointed out that statistics faculty including Vijay Nair were heavily involved in the planning of MIDAS-although not in its current public face-and that the nonstatistics department academics at the inaugural symposium used statistics heavily. This is actually the same point I am making. 

> [5] 密歇根大学的几位教授写信向我详细介绍了他们的密西根数据科学（MIDAS）计划，并指出统计学对MIDAS来说比看起来更重要。他们指出，包括Vijay Nair在内的统计系教师大量参与了MIDAS的规划，尽管目前尚未公开，而且首届研讨会上的非统计系学者大量使用统计学。这实际上与我所说的相同。

## 2.1 The "Big Data" Meme

## 2.1 “大数据”模因

Consider the press release announcing the University of Michigan Data Science Initiative with which this article began. The University of Michigan President, Mark Schlissel, uses the term "big data" repeatedly, touting its importance for all fields and asserting the necessity of data science for handling such data. Examples of this tendency are near-ubiquitous.

回到本文开头密歇根大学发布数据科学计划的新闻稿，密歇根大学校长 Mark Schlisel 反复使用“大数据”一词，宣扬其对所有领域的重要性，并强调数据科学处理此类数据的必要性。这种观点几乎无处不在。

We can immediately reject "big data" as a criterion for meaningful distinction between statistics and data science. $^{12}$

但我们可以立即说明为什么“大数据”不是一个有意义的区分统计学和数据科学的标准 $^{12}$。


- **History**. The very term "statistics" was coined at the beginning of modern efforts to compile census data, that is, comprehensive data about all inhabitants of a country, for example, France or the United States. Census data are roughly the scale of today's big data; but they have been around more than 200 years! A statistician, Hollerith, invented the first major advance in big data: the punched card reader to allow efficient compilation of an exhaustive U.S. census. (http://bulletin.imstat.org/2014/10/ims-presidential-address-let-us-own-datasciencel) This advance led to formation of the IBM corporation which eventually became a force pushing computing and data to ever larger scales. Statisticians have been comfortable with large datasets for a long time, and have been holding conferences gathering together experts in "large datasets" for several decades, even as the definition of large was ever expanding. $^{14}$

- **历史**。“统计”一词是在现代人口普查数据编制工作之时创造的，即一个国家（例如法国或美国）所有居民的综合数据。人口普查数据大致相当于当今大数据的规模；但它们已经存在了200多年！统计学家 Hollerith 发明了大数据领域的第一个重大进步：穿孔卡片阅读器，可以有效地汇编详尽的美国人口普查数据。(http://bulletin.imstat.org/2014/10/ims-presidential-address-let-us-own-datasciencel) 这一进步导致了IBM公司的成立，该公司最终成为一股将计算和数据推向更大规模的力量。长期以来，统计学家处理大型数据集并不觉得多么棘手，而且几十年来一直在召开会议聚集“大型数据集”的专家进行讨论，即使“大”的定义不断扩大 $^{14}$。

- **Science**. Mathematical statistics researchers have pursued the scientific understanding of big datasets for decades. They have focused on what happens when a database has a large number of individuals or a large number of measurements or both. It is simply wrong to imagine that they are not thinking about such things, in force, and obsessively. Among the core discoveries of statistics as a field were sampling and sufficiency, which allow to deal with very large datasets extremely efficiently. These ideas were discovered precisely because statisticians care about big datasets.

- **科学**。几十年来，数理统计研究人员一直在追求对大数据集的科学理解。他们关注的是当数据库中有大量的个体、大量的测量值或两者都有时会发生什么。认为他们并没有疯狂并痴迷于思考这些事情，是完全错误的。统计作为一个领域的核心发现之一是抽样和充分性，它使得我们能够极其有效地处理非常大的数据集。而这些想法的发现正是因为统计学家关心大数据集。


The data-science = “big data” framework is not getting at anything very intrinsic about the respective fields. $^{15}$

数据科学=“大数据”框架并没有触及各个领域的任何本质 $^{15}$。


> [12] One sometimes encounters also the statement that statistics is about "small datasets, while data science is about big datasets." Older statistics textbooks often did use quite small datasets to allow students to make hand calculations.

> [12] 人们有时也会遇到这样的说法，即统计是关于“小数据集，而数据科学是关于大数据集”，旧的统计教科书经常使用相当小的数据集，让学生进行手工计算。


> [14] During the Centennial workshop, one participant pointed out that John Tukey's definition of "big data" was: "anything that won't fit on one device." In John's day the device was a tape drive, but the larger point is true today, where device now means "commodity file server." The data-science $=$ "big data" framework is not getting at anything very intrinsic about the respective fields.

> [14] 在百年研讨会期间，一位与会者指出，John Tukey对“大数据”的定义是：“任何不适合一台设备的东西”。在John的时代，设备指的是一个磁带机，而今天设备意味着“通用文件服务器”（commodity file server），但总体理念依然正确。数据科学 = “大数据”框架没有触及各个领域的任何本质。

> [15] It may be getting at something real about the master's degree programs, or about the research activities of individuals who will be hired under the new spate of DSI's.

> [15] 这可能会得到一些关于硕士学位项目的真实信息，以及将在新一轮数据科学计划下被聘用者的研究活动。

## 2.2 The "Skills" Meme


## 2.2 “技能” 模因

In conversations I have witnessed, computer scientists seem to have settled on the following talking points [^16](For example, at breakouts of the NSF sponsored workshop Theoretical Foundations of Data Science, April 2016.):

在我亲眼目睹的对话中，计算机科学家似乎已经确定了以下谈话要点[^16]（例如，美国国家科学基金会主办的数据科学理论基础研讨会上，2016年4月）：


(a) data science is concerned with really big data, which traditional computing resources could not accommodate.

(a) 数据科学关注的是传统计算资源无法容纳的大数据。


(b) data science trainees have the skills needed to cope with such big datasets.

(b) 数据科学受训人员具备处理此类大数据集所需的技能。


This argument doubles down on the "big data" meme, by layering a "big data skills meme" on top. [^17](which we just dismissed!)

这一论点又加上了“大数据技能模因”，进一步强调“大数据”模因。（我们在前文已经驳斥了这一点！）


What are those skills? In the early 2010s many would cite mastery of Hadoop, a variant of Map/Reduce for use with datasets distributed across a cluster of computers. Consult the standard reference Hadoop: The Definitive Guide. Storage and Analysis at Internet Scale, 4th Edition by Tom White. There we learn at great length how to partition a single abstract dataset across a large number of processors. Then we learn how to compute the maximum of all the numbers in a single column of this massive dataset. This involves computing the maximum over the sub-database located in each processor, followed by combining the individual per-processor-maxima across all the many processors to obtain an overall maximum. Although the functional being computed in this example is dead-simple, quite a few skills are needed to implement the example at scale.


这些技能是什么？在2010年代早期，许多人会说它指的是精通Hadoop。Hadoop是Map/Reduce的一个变体，用于处理分布在计算机集群中的数据集。参考此书（Hadoop: The Definitive Guide. Storage and Analysis at Internet Scale, 4th Edition by Tom White）。在那里，我们详细学习了如何将单个抽象数据集划分到大量处理器之中。然后我们学习了如何计算这个庞大数据集的某一列的最大值。这包括计算位于每个处理器中的子数据集上的最大值，然后组合每个处理器的最大值以获得总体最大值。虽然本例中计算的函数非常简单，但要大规模实现该示例，确实需要一些技巧。


Lost in the hoopla about such skills is the embarrassing fact that once upon a time, one could do such computing tasks, and even much more ambitious ones, much more easily than in this fancy new setting! A dataset could fit on a single processor, and the global maximum of the array "X" could be computed with the six-character code fragment "X" in, say, Matlab or R. More ambitious tasks, like large-scale optimization of a convex function, were easy to set up and use. In those less-hyped times, the skills being touted today were unnecessary. Instead, scientists developed skills to solve the problem they were really interested in, using elegant mathematics and powerful quantitative programming environments modeled on that math. Those environments were the result of 50 or more years of continual refinement, moving ever closer toward the ideal of enabling immediate translation of clear abstract thinking to computational results.


在这种技能的喧嚣中，人们似乎会忘记一个令人尴尬的事实：人们从前就已经可以完成这样的计算任务了，甚至比在这种花哨的设定中更容易完成更宏大的任务！一个数据集可以放在一个处理器上，数组“X”的全局最大值可以用Matlab或R中的六个字符代码片段“X”来计算。更雄心勃勃的任务，如凸函数的大规模优化，都很容易设置使用。过去炒作没那么流行时，这些今天被吹捧的技能是没有必要的。相反，科学家会利用优雅的数学和以数学为模型的强大定量编程环境，发展出解决他们真正感兴趣的问题的技能。这些环境是50多年连续改进的结果，越来越接近于能够立即将清晰的抽象思维转化为计算结果的理想。


The new skills attracting so much media attention are not skills for better solving the real problem of inference from data; they are coping skills for dealing with organizational artifacts of large-scale cluster computing. The new skills cope with severe new constraints on algorithms posed by the multiprocessor/networked world. In this highly constrained world, the range of easily constructible algorithms shrinks dramatically compared to the single-processor model, so one inevitably tends to adopt inferential approaches which would have been considered rudimentary or even inappropriate in olden times. Such coping consumes our time and energy, deforms our judgements about what is appropriate, and holds us back from data analysis strategies that we would otherwise eagerly pursue.

吸引如此多媒体关注的新技能并不是更好地解决真实问题的数据推断；而是处理大规模集群计算的组织工件的应对技能。这些新技能可以应对多处理器/网络问题对算法提出的新的严重限制。而在这个高度受限的环境中，与单处理器模型相比，易于构造的算法的范围急剧缩小，因此人们不可避免地倾向于采用以往被认为是初步的或甚至不适当的处理方法。这样的应对方式消耗了我们的时间和精力，改变了我们对什么是合适的判断，并阻碍了我们采用原本热切追求的数据分析策略。

Nevertheless, the scaling cheerleaders are yelling at the top of their lungs that using more data deserves a big shout.

尽管如此，声势不断壮大的啦啦队员们仍在竭尽全力地大喊：使用更大的数据值得更多关注。

## 2.3 The "Jobs" Meme

## 2.3 “工作岗位”模因

Big data enthusiasm feeds off the notable successes scored in the last decade by brand-name global Information technology (IT) enterprises, such as Google and Amazon, successes currently recognized by investors and CEOs. A hiring "bump" has ensued over the last 5 years, in which engineers with skills in both databases and statistics were in heavy demand. In The Culture of Big Data (Barlow 2013), Mike Barlow summarizes the situation

过去十年，谷歌和亚马逊等全球知名信息技术企业取得了令人瞩目的成功，这些成功目前得到了投资者和首席执行官的认可，而人们对大数据的热情也推动了这些成功。在过去的五年里，相关岗位招聘“激增”，同时具备数据库和统计技能的工程师炙手可热。在《大数据文化》（The Culture of Big Data, Barlow, 2013）中，Mike Barlow 对这一现象进行了总结：

> According to Gartner, 4.4 million big data jobs will be created by 2014 and only a third of them will be filled. Gartner's prediction evokes images of "gold rush" for big data talent, with legions of hardcore quants converting their advanced degrees into lucrative employment deals.


>  根据Gartner的数据，到2014年，会涌现440万个大数据岗位，但其中只有三分之一需求可以得到满足。Gartner 的预测让人联想到大数据人才的“淘金热”，大批核心量化分析师将他们的高级学位转化为收入丰厚的就业协议。


While Barlow suggests that any advanced quantitative degree will be sufficient in this environment, today's Data Science initiatives per se imply that traditional statistics degrees are not enough to land jobs in this area-formal emphasis on computing and database skills must be part of the mix. [^18](Of course statistics degrees require extensive use of computers, but often omit training in formal software development and formal database theory.)

Barlow 认为，在这种环境下，任何高级数理方向的学位都已足够胜任，但今天的数据科学计划本身意味着，传统的统计学位不足以在这一领域找到好工作——因为计算和数据库技能必须是数据科学领域的必要能力。（当然，获得统计学位需要频繁使用计算机，但这一过程中却往往忽略专业软件开发和数据库理论方面的培训。）

We do not really know. The booklet "Analyzing the Analyzers: An Introspective Survey of Data Scientists and Their Work" (Harris, Murphy, and Vaisman 2013) points out that

我们并不真的清楚这一点。小册子《分析师分析：数据科学家及其工作的回顾性调查》（Analyzing the Analyzers: An Introspective Survey of Data Scientists and Their Work, Harris、Murphy和Vaisman 2013）指出


> Despite the excitement around "data science," "big data," and "analytics," the ambiguity of these terms has led to poor communication between data scientists and those who seek their help.

> 尽管人们对“数据科学”、“大数据”和“分析”感到兴奋，但这些术语的模糊性导致了数据科学家和寻求帮助的人之间的沟通不畅。


Yanir Seroussi's blog opines that "there are few true data science positions for people with no work experience." (https://yanirseroussi.com/2014/10/23/what-is-data-science/)

Yanir Serousi在博客中提出，“没有工作经验的人很难获得真正的数据科学职位。”(https://yanirseroussi.com/2014/10/23/what-is-data-science/)

> A successful data scientist needs to be able to become one with the data by exploring it and applying rigorous statistical analysis ...But good data scientists also understand what it takes to deploy production systems, and are ready to get their hands dirty by writing code that cleans up the data or performs core system functionality ...Gaining all these skills takes time [on the job].

> 一个成功的数据科学家需要能够通过探索数据并应用严格的统计分析来与数据融为一体……但是，优秀的数据科学家也得了解部署生产系统需要什么，并准备好“筚路蓝缕”编写代码来清洗数据或执行核心系统功能……但掌握这些技能需要时间。

Barlow implies that would-be data scientists may face years of further skills development post masters degree, before they can add value to their employer's organization. In an existing bigdata organization, the infrastructure of production data processing is already set in stone. The databases, software, and workflow management taught in a given data science masters program are unlikely to be the same as those used by one specific employer. Various compromises and constraints were settled upon by the hiring organizations and for a new hire, contributing to those organizations is about learning how to cope with those constraints and still accomplish something.

Barlow 认为，未来的数据科学家在获得硕士学位后可能会面临多年的进阶技能学习，然后才能为雇主创造价值。在现有的大数据组织中，生产数据处理的基础设施已经一成不变。而数据科学硕士课程中所教授的数据库、软件和管理技能不太可能与某个特定雇主使用的完全一致。招聘单位实际上设置了诸多限制，而对于新员工来说，能够为单位做出的贡献就是学习如何应对这些限制，同时仍然有所成就。


Data science degree programs do not actually know how to satisfy the supposedly voracious demand for graduates. As we show below, the special contribution of a data science degree over a statistics degree is additional information technology training. Yet hiring organizations face difficulties making use of the specific information technology skills being taught in degree programs. In contrast, data analysis and statistics are broadly applicable skills that are portable from organization to organization.

数据科学学位项目实际上并不知道如何满足毕业生的巨大需求。正如我们下面展示的，数据科学学位相对于统计学学位，最大区别是提供了额外的信息技术培训。然而，这些毕业生在学位项目中所学到的特定信息技术技能，与用人单位的实际需求却常常并不匹配。相比之下，数据分析和统计却是更加广泛适用，在任何单位中都能发光发热。


## 2.4 What Here is Real?


## 2.4 真实情况是什么？

We have seen that today's popular media tropes about data science do not withstand even basic scrutiny. This is quite understandable: writers and administrators are shocked out of their wits. Everyone believes we are facing a zeroth order discontinuity in human affairs.


我们已经看到，今天大众媒体关于数据科学的理解甚至经不起基本的推敲。这是完全可以理解的：媒体写手和管理者们都被吓着了。每个人都认为我们即将面临着人类社会的一个沟通断层。

If you studied a tourist guidebook in 2010, you would have been told that life in villages in India (say) had not changed in thousands of years. If you went into those villages in 2015, you would see that many individuals there now have mobile phones and some have smartphones. This is of course the leading edge fundamental change. Soon, eight billion people will be connected to the network, and will therefore be data sources, generating a vast array of data about their activities and preferences.

如果你阅读一本2010年的旅游指南，它会告诉你印度村庄的生活在几千年间没有任何改变。但如果你在2015年走进这些村庄，你会看到那里的许多人现在有手机，有些人还有智能手机。这当然是最前沿的重大变化。很快，80亿人将连接到网络，并成为数据源，不断生产关于他们活动和偏好的大量数据。

The transition to universal connectivity is very striking; it will, indeed, generate vast amounts of commercial data. Exploiting that data is certain to be a major pation of commercial life in coming decades.

迈向广泛连接的转变是非常惊人的；事实上，它将产生海量的商业数据。在未来几十年里，利用这些数据肯定会是商业领域的重头戏。

## 2.5 A Better Framework

## 2.5 更好的框架

However, a science does not just spring into existence simply because a deluge of data will soon be filling telecom servers, and because some administrators think they can sense the resulting trends in hiring and government funding.

然而，一门科学的诞生不仅仅是因为大量数据将很快填满电信服务器，而且因为一些管理人员认为他们能够感知由此产生的招聘浪潮和政府资助趋势。

Fortunately, there is a solid case for some entity called "data science" to be created, which would be a true science: facing essential questions of a lasting nature and using scientifically rigorous techniques to attack those questions.

幸运的是，我们有充分的理由建立一个叫做“数据科学”的实体，这将是一门真正的科学：应对持久性的基本问题，并使用科学严谨的技术来解决这些问题。

Insightful statisticians have for at least 50 years been laying the groundwork for constructing that would-be entity as an enlargement of traditional academic statistics. This would-be notion of data science is not the same as the data science being touted today, although there is significant overlap. The would-be notion responds to a different set of urgent trends-intellectual rather than commercial. Facing the intellectual trends needs many of the same skills as facing the commercial ones and seems just as likely to match future student training demand and future research funding trends.


至少50年来，有洞察力的统计学家一直在为构建这一潜在实体奠定基础，将其作为传统学术统计的扩展。这一潜在的数据科学概念与今天被吹捧的数据科学并不相同，尽管两者有很大的重叠。这一潜在的概念是对一系列不同的紧迫趋势的回应，即才智而非商业。面对才智趋势需要许多与商业趋势相同的技能，并且似乎同样有可能满足未来的学生培训需求和未来的研究资助趋势。

The would-be notion takes data science as the science of learning from data, with all that this entails. It is matched to the most important developments in science which will arise over the coming 50 years. As scientific publication itself becomes a body of data that we can analyze and study, there are staggeringly large opportunities for improving the accuracy and validity of science, through the scientific study of the data analysis that scientists have been doing. [^20] (Farther below, we will use shortened formulations such as "science itself becomes a body of data.)

潜在的概念将数据科学视为从数据中学习的科学，包括所有以上提到的技能。它与未来50年中出现的最重要的科学发展相匹配。随着科学出版物自身成为我们可以分析和研究的数据，通过科学家一直在进行的数据分析的科学研究，提高科学的准确性和有效性的机会多得惊人。（在下文中，我们将使用缩短的公式，例如“科学本身就是一个数据体”。）

Understanding these issues gives Deans and Presidents an opportunity to rechannel the energy and enthusiasm behind today's data science movement toward lasting, excellent programs canonicalizing a new scientific discipline.

对以上事实的了解，有助于帮助各位院校领导重新调动当今数据科学运动背后的能量和热情，致力于将一门新的科学学科打造为一个规范化的、持久卓越的项目。

In this article, I organize insights that have been published over the years about this new would-be field of data science, and put forward a framework for understanding its basic questions and procedures. This framework has implications both for teaching the subject and for doing scientific research about how data science is done and might be improved.

在这篇文章中，我整理了多年来发表的关于这一新的潜在数据科学领域的观点，并提出了一个理解其基本问题和过程的框架。这个框架对教授该学科和进行关于数据科学如何完成和可能改进的科学研究都有影响。

# 3. The Future of Data Analysis, 1962

# 3. 数据分析之未来, 1962

This article was prepared as an aide-memoire for a presentation made at the John Tukey centennial. More than 50 years ago, John prophesied that something like today's data science moment would be coming. In "The Future of Data Analysis" (Tukey 1962), John deeply shocked his readers (academic statisticians) with the following introductory paragraphs: $^{21}$


这篇文章是作为John Tukey百年纪念演讲的备忘录而准备的。50多年前，John预言像今天这样的数据科学时刻即将到来。在《数据分析之未来》（The Future of Data Analysis, Tukey 1962）中，John用以下段落深深震撼了他的读者（学术统计学家） $^{21}$：

> For a long time I have thought I was a statistician, interested in inferences from the particular to the general. But as I have watched mathematical statistics evolve, I have had cause to wonder and to doubt. ..All in all I have come to feel that my central interest is in data analysis, which I take to include, among other things: procedures for analyzing data, techniques for interpreting the results of such procedures, ways of planning the gathering of data to make its analysis easier, more precise or more accurate, and all the machinery and results of (mathematical) statistics which apply to analyzing data

> 长期以来，我一直认为自己是一名统计学家，对从特定到一般的推论感兴趣。但随着我观察数理统计的发展，我有理由好奇并怀疑……总而言之，我开始觉得我的核心兴趣是数据分析，我认为其中包括：分析数据的过程、解释这些过程结果的技术、规划数据收集的方式以使其分析更容易、更精确或更准确，以及适用于分析数据的（数理）统计的所有机制和结果。

John's article was published in 1962 in The Annals of Mathematical Statistics, the central venue for mathematically advanced statistical research of the day. Other articles appearing in that journal at the time were mathematically precise and would present definitions, theorems, and proofs. John's article was instead a kind of public confession, explaining why he thought such research was too narrowly focused, possibly useless or harmful, and the research scope of statistics needed to be dramatically enlarged and redirected.

John的文章于1962年发表在《数理统计年刊》（The Annals of Mathematical Statistics）上，这是当时数理统计研究的核心期刊。当时该杂志上出现的其他文章在数学上是精确的，会给出定义、定理和证明。John 的文章反而是一种公开的坦白，解释了为什么他认为这样的研究过于狭隘，可能是无用或有害的，统计学的研究范围需要大幅扩大和重新定向。

Peter Huber, whose scientific breakthroughs in robust estimation would soon appear in the same journal, recently commented about FoDA:

Peter Huber在稳健估计方面的科学突破很快就出现在同一份杂志上，他最近对FoDA发表了评论：

> Half a century ago, Tukey, in an ultimately enormously influential paper redefined our subject ... [The paper] introduced the term "data analysis" as a name for what applied statisticians do, differentiating this term from formal statistical inference. But actually, as Tukey admitted, he "stretched the term beyond its philology" to such an extent that it comprised all of statistics. *Peter Huber (2010)*

> 半个世纪前，Tukey在一篇震古烁今的论文中重新定义了我们的主题……[论文]引入了术语“数据分析”一词作为应用统计学家工作的名称，该术语与正式的统计推断区分开了。但实际上，正如Tukey 所承认的，他“将该术语扩展到语言学之外”，以至于它包含了所有的统计学。——*Peter Huber（2010）*



So Tukey's vision embedded statistics in a larger entity. Tukey's central claim was that this new entity, which he called "data analysis," was a new science, rather than a branch of mathematics:

因此，Tukey 的愿景将统计嵌入了一个更大的实体中。Tukey 的核心主张是，这个他称之为“数据分析”的新实体是一门新科学，而不是数学的一个分支：


> There are diverse views as to what makes a science, but three constituents will be judged essential by most, viz:
>
> (a1) intellectual content,
>
> (a2) organization in an understandable form,
>
> (a3) reliance upon the test of experience as the ultimate standard of validity.
>
> By these tests mathematics is not a science, since its ultimate standard of validity is an agreed-upon sort of logical consistency and provability. As I see it, data analysis passes all three tests, and I would regard it as a science, one defined by a ubiquitous problem rather than by a concrete subject. Data analysis and the parts of statistics which adhere to it, must then take on the characteristics of a science rather than those of mathematics, ...
>
>　These points are meant to be taken seriously.


> 关于什么是一门科学，有各种各样的观点，但大多数人认为三个要素是必不可少的，即：
> 
>（A1）才智内容， 
> 
>（A2）以可理解的形式组织， 
> 
>（A3）依赖经验测试作为有效性的最终标准。 
> 
> 通过这些测试，数学不是一门科学，因为它的最终有效性标准是一种公认的逻辑一致性和可证明性。在我看来，数据分析通过了所有三项测试，我将其视为一门科学，一门由普遍存在的问题而非具体学科定义的科学。因此，数据分析和遵循它的统计部分必须具有科学的特征，而不是数学的特征……
> 
> 这些要点应该认真对待。


 
Tukey identified four driving forces in the new science:

>　Four major influences act on data analysis today:
>
>　1. The formal theories of statistics
>
>　2. Accelerating developments in computers and display devices
>
>　3. The challenge, in many fields, of more and ever larger bodies of data
>
>　4. The emphasis on quantification in an ever wider variety of disciplines


Tukey确定了新科学的四个驱动力：

 > 今天，数据分析受到四大因素影响：
 > 
 > 1. 统计学的形式理论 
 > 
 > 2. 计算机和显示设备的加速发展 
 > 
 > 3. 在许多领域，越来越大的数据量所带来的挑战
 > 
 > 4. 越来越多的学科开始强调量化

John's 1962 list is surprisingly modern, and encompasses all the factors cited today in press releases touting today's data science initiatives. Shocking at the time was Item 1, implying that statistical theory was only a (fractional!) part of the new science.

John在1962年列出的清单出人意料地现代，涵盖了今天在宣传当今数据科学计划的新闻稿中引用的所有因素。当时令人震惊的是第1项，这意味着统计理论只是新科学的一个（微小的！）部分。

This new science is compared to established sciences and further circumscribed the role of statistics within it :

这门新科学与现有科学相比较，进一步限制了统计学在其中的作用：

> ...data analysis is a very difficult field. It must adapt itself to what people can and need to do with data. In the sense that biology is more complex than physics, and the behavioral sciences are more complex than either, it is likely that the general problems of data analysis are more complex than those of all three. It is too much to ask for close and effective guidance for data analysis from any highly formalized structure, either now or in the near future.


>  ……数据分析是一个非常困难的领域，它必须适应人们使用数据的需求。如果我们说生物学比物理学更复杂，行为科学又比这两者都更复杂，那么数据分析的一般问题可能会比这三者都更复杂。无论是现在还是不久的将来，都很难要求一个高度形式化的结构为数据分析提供密切有效的指导。

Data analysis can gain much from formal statistics, but only if the connection is kept adequately loose.

数据分析可以从传统统计中获得很多，但前提是这种借鉴足够灵活。


So not only is data analysis a scientific field, it is as complex as any major field of science! And theoretical statistics can only play a partial role in its progress.

因此，数据分析不仅是一个科学领域，而且与任何主要科学领域一样复杂！理论统计只能在其发展过程中发挥部分作用。

Mosteller and Tukey’s (1968) title reiterated this point: "Data Analysis, including Statistics” (Mosteller and Tukey 1968).


Mosteller and Tukey (1968) 的标题重申了这一点：“数据分析，包括统计学”。

> [21] (One questions why the journal even allowed this to be published! Partly one must remember that John was a Professor of Mathematics at Princeton, which gave him plenty of authority! Sir Martin Rees, the famous astronomer/cosmologist once quipped that "God invented space just so not everything would happen at Princeton." JL Hodges Jr. of UC Berkeley was incoming editor of Annals of Mathematical Statistics, and deserves credit for publishing such a visionary but deeply controversial article.) 


> [21] 有人质疑为什么该杂志能够允许发表这篇文章！一定程度上可能是因为John是普林斯顿的数学教授，这给了他足够的权威！著名天文学家/宇宙学家 Martin Rees 爵士曾经打趣道：“上帝发明了空间，这样普林斯顿才不会什么都发生。”加州大学伯克利分校的JL Hodges Jr.是《数理统计年鉴》的新任编辑，他同意发表了如此有远见但极具争议的文章，值得称赞。



# 4. The 50 Years Since FoDA

# 4. “数据分析之未来”之后的50年

While Tukey called for a much broader field of statistics, it could not develop overnight-even in one individual's scientific oeuvre.

虽然Tukey呼吁建立一个更广泛的统计领域，但即使是在个人的科学著作中，也不可能一蹴而就。



P. J. Huber wrote that "The influence of Tukey's paper was not immediately recognized ...it took several years until I assimilated its import ..." (Huber 2010). From observing Peter first-hand I would say that 15 years after FoDA he was visibly comfortable with its lessons. At the same time, full evidence of this effect in Huber's case came even much later-see his 2010 book Data Analysis: What can be learned from the last 50 years, which summarizes Peter's writings since the 1980s and appeared 48 years after FoDA! 


P. J. Huber写道：“Tukey的论文的影响力并没有立即得到承认……我花了几年时间才真正理解了它的重要性……”（Huber，2010年）。通过对Peter的近距离观察，我可以说，在FoDA之后15年，他依然坚持自己的观点。与此同时，Huber案例中这种效应的充分证据甚至出现得更晚——参见他2010年的著作《数据分析：过去50年可以学到什么》，该书总结了Peter自20世纪80年代以来的著作，出现在FoDA之后48年！


## 4.1. Exhortations

## 4.1. 劝诫

While Huber obviously made the choice to explore the vistas offered in Tukey's vision, academic statistics as a whole did not. $^{22}$  John Tukey's Bell Labs colleagues, not housed in academic statistics departments, more easily adopted John's vision of a field larger than what academic statistics could deliver.

虽然Huber显然选择了探索Tukey愿景中的前景，但学术统计总体上并没有 $^{22}$。John Tukey的贝尔实验室同事不在学术统计系，他们更容易接受John的视野，即一个比学术统计所能提供的更大的领域。

John Chambers, co-developer of the S language for statistics and data analysis while at Bell Labs, published already in 1993 the essay (Chambers 1993), provocatively titled "Greater or Lesser Statistics, A Choice for Future Research." His abstract pulled no punches:

John Chambers是贝尔实验室统计和数据分析S语言的联合开发者，他于1993年发表了这篇文章（Chambers 1993），标题是“更大或更小的统计，未来研究的选择”。他的摘要毫不留情：

> The statistics profession faces a choice in its future research between continuing concentration on traditional topics-based largely on data analysis supported by mathematical statistics - and a broader viewpoint-based on an inclusive concept of learning from data.

> 统计专业在未来的研究中面临着一种选择，一种是继续专注传统主题——主要基于数理统计支持的数据分析，另一种是更广泛的视野——基于从数据中学习的包容性概念。

The latter course presents severe challenges as well as exciting opportunities. The former risks seeing statistics become increasingly marginal ...


后一条路带来了严峻的挑战，但同时也有令人兴奋的机遇。前者的风险是统计学变得越来越边缘化……

A call to action, from a statistician who feels "the train is leaving the station." Like Tukey's article, it proposes that we could be pursuing research spanning a much larger domain than the Statistical research we do today; such research would focus on opportunities provided by new types of data and new types of presentation. Chambers stated explicitly that the enlarged field would be larger even than data analysis. Specifically, it is larger than Tukey's 1962 vision.


一位统计学家呼吁采取行动，他觉得“火车要离开车站了”。就像Tukey的文章一样，他提出，我们可以在比我们今天所做的统计研究更大的领域进行研究；这类研究将侧重于新型数据和新型展示方法所提供的机会。Chambers明确表示，扩大的领域甚至比数据分析还要大。具体来说，它比Tukey 1962年的愿景更大。

C. F. Jeff Wu, upon his inauguration as Carver Professor of Statistics at University of Michigan, presented an inaugural lecture titled Statistics $=$ Data Science? in which he advocated that statistics be renamed data science and statisticians data scientists. Anticipating modern masters' data science masters courses, he even mentioned the idea of a new masters' degree in which about half of the courses were outside the department of statistics. He characterized statistical work as a trilogy of data collection, data modeling and analysis, and decision making. No formal written article was prepared though the slides he presented are available. (http://www2.isye.gatech.edu/~jeffwu/presentations/datascience.pdf)


吴建福就任密歇根大学Carver统计学教授后，发表了题为《统计=数据科学？》的就职演讲，他在演讲中主张将统计学更名为数据科学，统计学家更名为数据科学家。展望现代数据科学硕士课程，他甚至提到了新硕士学位的想法，其中大约一半的课程在统计学系之外。他将统计工作描述为数据采集、数据建模分析以及决策三部曲。尽管我们能找到他展示的幻灯片，但他并未出版正式的书面文章。（http://www2.isye.gatech.edu/~jeffwu/presentations/datascience.pdf）

William S. Cleveland developed many valuable statistical methods and data displays while at Bell Labs, and served as a co-editor of Tukey's collected works. His 2001 article (Cleveland 2001), titled Data Science: An Action Plan for Expanding the Technical Areas of the field of Statistics addressed academic statistics departments and proposed a plan to reorient their work. His abstract read:

William S.Cleveland在贝尔实验室期间开发了许多有价值的统计方法和数据展示工具，并担任了Tukey作品集的联合编辑。他2001年发表了题为《数据科学：扩大统计技术领域的行动计划》的文章（Cleveland，2001, Data Science: An Action Plan for Expanding the Technical Areas of the field of Statistics ），为学术统计提出了调整研究领域的计划。该文摘要如下：

> An action plan to expand the technical areas of statistics focuses on the data analyst. The plan sets out six technical areas of work for a university department and advocates a specific allocation of resources devoted to research in each area and to courses in each area. The value of technical work is judged by the extent to which it benefits the data analyst, either directly or indirectly. The plan is also applicable to government research labs and corporate research organizations.


> 扩大统计技术领域的行动计划更关注数据分析。该计划部署了大学部门六个技术领域的工作，并主张为每个领域的研究和每个领域的课程专门分配资源。技术工作的价值取决于它对数据分析师的直接或间接收益。该计划也适用于政府研究实验室和企业研究机构。

In the article's introduction, Cleveland writes that $^{24, 25}$

在文章的引言中，Cleveland写道 $^{24, 25}$：


> ... [results in] data science should be judged by the extent to which they enable the analyst to learn from data... Tools that are used by the data analyst are of direct benefit. Theories that serve as a basis for developing tools are of indirect benefit.


>  ……数据科学[的结果]应该根据它们使分析师能够从数据中学习的程度来评判……数据分析师使用的工具提供直接收益，作为开发工具基础的理论则提供间接收益。


Cleveland proposed six foci of activity, even suggesting allocations of effort.


Cleveland提出了六个活动重点，甚至建议了精力分配。

- (*) Multidisciplinary investigations (25%)
- (*) Models and Methods for Data (20%)
- (*) Computing with Data (15%)
- (*) Pedagogy (15%)
- (*) Tool Evaluation (5%)
- (*) Theory (20%)

- (*) 跨学科学习 (25%)
- (*) 数据模型和方法 (20%)
- (*) 数据计算 (15%)
- (*) 教学法 (15%)
- (*) 工具评估 (5%)
- (*) 理论 (20%)

Several academic statistics departments that I know well could, at the time of Cleveland's publication, fit 100% of their activity into the 20% Cleveland allowed for theory. Cleveland's article was republished in 2014. I cannot think of an academic department that devotes today 15% of its effort on pedagogy, or 15 % on computing with data. I can think of several academic statistics departments that continue to fit essentially all their activity into the last category, theory.

在Cleveland出版时，我熟悉的几个学术统计系会将其100%的精力投入Cleveland提及的理论（20%）部分。Cleveland的文章于2014年重新发表。我想不出哪一个学术部如今能将15%的精力投入到教学法上，或者15%的精力用于数据计算，但我能想到几个学术统计系继续将他们的所有活动纳入最后一个类别，即理论。

In short, academic Statisticians were exhorted repeatedly across the years, by John Tukey and by some of his Bell Labs colleagues, and even by some academics like Peter Huber and Jeff Wu, to change paths, towards a much broader definition of their field. Such exhortations had relatively little apparent effect before 2000.

简言之，John Tukey和他在贝尔实验室的一些同事，甚至是Peter Huber和吴建福等学者，多年来在反复劝告学术统计学家要改变道路，对他们的领域进行更广泛的定义。但在2000年之前，这种劝告几乎没有明显的效果。

> [22] If evidence were needed, the reader might consider course offerings in academic statistics departments 1970-2000. In my recollection, the fraction of course offerings recognizably adopting the direction advocated by Tukey was small in those years. There was a bit more about plotting and looking at data.

> [22] 如果需要证据，读者可以参考1970-2000年学术统计系的课程设置。在我的记忆中，那些年，课程中采纳Tukey 建议的方向的比例很小。还有一点点关于绘制和查看数据的内容。


> [24] This echoes statements that John Tukey also made in FoDA, as I am sure Bill Cleveland would be proud to acknowledge.

> [24] 这呼应了John Tukey在FoDA中的发言，我相信Bill Cleveland会很自豪地承认这一点。


> [25] Geophysicists make a distinction between mathematical geophysicists who "care about the earth" and those who "care about math." Probably biologists make the same distinction in quantitative biology. Here Cleveland is introducing it as a litmus test restatistical theorists: do they "care about the data analyst" or do they not?

> [25] 地球物理学家对“关心地球”的数学地球物理学家和“关心数学”的数学地球物理学家进行了区分。可能生物学家在定量生物学中也做了同样的区分。在这里，Cleveland 引入了“试金石”区分理论统计学家：他们是否“关心数据分析”？

## 4.2 Reification

## 4.2 实践落地


One obstacle facing the earliest exhortations was that many of the exhortees could not see what the fuss was all about. Making the activity labeled "data analysis" more concrete and visible was ultimately spurred by code, not words.

最早，这样的劝诫所面临的一个障碍是，许多劝诫者自己都说不清“数据分析”是怎么回事。“数据分析”的活动更加具体和可见，**最终是由代码而不是文字推动的**。

Over the last 50 years, many statisticians and data analysts took part in the invention and development of computational environments for data analysis. Such environments included the early statistical packages BMDP, SPSS, SAS, and Minitab, all of which had roots in the mainframe computing of the late 1960s, and more recently packages such as S, ISP, STATA, and R, with roots in the minicomputer/personal computer era. This was an enormous effort carried out by many talented individuals-too many to credit here properly. $^{26}$

在过去的50年中，许多统计学家和数据分析师参与了数据分析计算环境的开发。这些环境包括早期的统计软件包BMDP、SPSS、SAS和Minitab，它们都起源于20世纪60年代末的大型机计算。而一些更新的软件，如S、ISP、STATA和R，起源于小型计算机/个人计算机时代。这是许多才华横溢的前辈所做的巨大努力，虽然其中部分可能并未得到应有的赞誉 $^{26}$。


To quantify the importance of these packages, try using Google's N-grams viewer (http://preview.tinyurl.com/ycawv9xy) to plot the frequency of the words SPSS, SAS, Minitab, in books in the English language from 1970 to 2000; and for comparison, plot also the frequency of the bigrams "data analysis" and "statistical analysis." It turns out that SAS and SPSS are both more common terms in the English language over this period than either "data analysis" or "statistical analysis"-about twice as common, in fact.

要量化这些软件包的重要性，请尝试使用Google的N-grams查看器 (http://preview.tinyurl.com/ycawv9xy) 绘制1970年至2000年英语书籍中SPSS、SAS、Minitab的单词频率；为了进行比较，还要绘制双字组“数据分析”和“统计分析”的频率。事实证明，在这一时期，SAS和SPSS在英语中都比“数据分析”或“统计分析”更为常见；事实上，是其两倍。

John Chambers and his colleague Rick Becker at Bell Labs developed the quantitative computing environment "S" starting in the mid-1970s; it provided a language for describing computations, and many basic statistical and visualization tools. In the 1990s, Gentleman and Ihaka created the work-alike R system, as an open source project which spread rapidly. R is today the dominant quantitative programming environment used in academic statistics, with a very impressive online following.

John Chambers和贝尔实验室的同事Rick Becker从20世纪70年代中期开始开发了定量计算环境“S”；它提供了一种描述计算的语言，以及许多基本的统计和可视化工具。在20世纪90年代，Gentleman和Ihaka创建了一个类似工作的R系统，作为一个开源项目，被迅速传播开来。如今，R是学术统计中使用的主要数理编程环境，在线用户数量惊人。

Quantitative programming environments run "scripts," which codify precisely the steps of a computation, describing them at a much higher and more abstract level than in traditional computer languages like C++. Such scripts are often today called workflows. When a given QPE becomes dominant in some research community, as R has become in academic statistics, (or Matlab in signal processing) workflows can be widely shared within the community and reexecuted, either on the original data (if it were also shared) or on new data. This is a game changer. What was previously somewhat nebulous-say the prose description of some data analysis in a scientific article-becomes instead tangible and useful, as one can download and execute code immediately. One can also easily tweak scripts, to reflect nuances of one's data, for example, changing a standard covariance matrix estimator in the original script to a robust covariance matrix estimator. One can document performance improvements caused by making changes to a baseline script. It now makes sense to speak of a scientific approach to improving a data analysis, by performance measurement followed by script tweaking. Tukey's claim that the study of data analysis could be a science now becomes self-evident. One might agree or disagree with Chambers and Cleveland's calls to action; but everyone could agree with Cleveland by 2001 that there could be such a field as "data science."


数理编程环境运行“脚本”，精确地编码了计算的步骤，比传统计算机语言（如C++）层级更高、更抽象。这些脚本现在通常被称为工作流。当给定的数理编程环境（QPE）在某些研究社区中占主导地位时，就像学术统计中的 R（或信号处理中的 Matlab）一样，工作流可以在社区中广泛共享并重新执行，无论是在原始数据上（如果也共享的话）还是在新数据上。这彻底改变了游戏规则。以前有些模糊不清的东西——比如一篇科学文章中数据分析的论文描述——变成了具体和有用的，因为人们可以立即下载和执行代码。此外，还可以容易地调整脚本以反映数据的细微差别，例如，将原始脚本中的标准协方差矩阵估计器改变为鲁棒的协方差矩阵估计器。可以记录对原始脚本进行更改所带来的性能改进。现在，通过性能度量和脚本调整，用科学的方法来改进数据分析变得更加有意义。Tukey声称数据分析研究可以成为一门科学，这一说法现在变得不言自明。人们可能对Chambers和Cleveland的行动呼吁各执一词；但到2001年，每个人都会同意Cleveland的观点，认为可能会有“数据科学”这样的领域。


> [26] One can illustrate the intensity of development activity by pointing to several examples strictly relevant to the Tukey Centennial at Princeton. I used three "statistics packages" while a Princeton undergraduate. P-STAT was an SPSS-like mainframe package which I used on Princeton's IBM 360/91 Mainframe; ISP was a UNIX minicomputer package on which I worked as a co-developer for the Princeton Statistics Department; and my teacher Don McNeil had developed software for a book of his own on exploratory data analysis; this ultimately became SPIDA after he moved to Macquarie University.

> [26] 可以通过列举几个与普林斯顿大学Tukey百年纪念活动严格相关的例子来说明发展活动的强度。我在普林斯顿大学本科时使用了三个“统计包”。P-STAT 是一个类似于 SPSS 的主机包，我在普林斯顿的 IBM 360/91 主机上使用过；ISP 是一个 UNIX 小型计算机包，我在普林斯顿统计局担任联合开发人员；我的老师 Don McNeil 为自己的一本关于探索性数据分析的书开发了软件；在他搬到麦格理大学后，这最终成为了 SPIDA。



# 5. Breiman's "Two Cultures," 2001

# 5. Breiman的《两种文化》，2001年

Leo Breiman, a UC Berkeley statistician who reentered academia after years as a statistical consultant to a range of organizations, including the Environmental Protection Agency, brought an important new thread into the discussion with his article in Statistical Science (Breiman 2001). Titled "Statistical Modeling: The Two Cultures," Breiman described two cultural outlooks about extracting value from data.

Leo Breiman是加州大学伯克利分校的统计学家，在担任环境保护局（Environmental Protection Agency）等一系列组织的统计顾问多年后重新进入学术界。他在《统计科学》（Breiman 2001）上发表的文章给统计讨论带来了重要的新思路。在名为“统计建模：两种文化”的文章中，Breiman描述了从数据中提取价值的两种文化观。

> Statistics starts with data. Think of the data as being generated by a black box in which a vector of input variables $x$ (independent variables) go in one side, and on the other side the response variables y come out. Inside the black box, nature functions to associate the predictor variables with the response variables ...
>
> There are two goals in analyzing the data:
>
> - Prediction. To be able to predict what the responses are going to be to future input variables;
>
> - Inference. To [infer] how nature is associating the response variables to the input variables.

> 统计从数据开始。假设数据是由一个黑箱生成的，其中输入变量$x$（自变量）在一侧，而响应变量$y$在另一侧。在黑箱内，大自然将预测变量与响应变量进行关联……
>
> 分析数据有两个目标：
>
> - **预测**。预测未来自变量输入后，响应变量的变化；
>
> - **推断**。推断响应变量如何与输入变量相关联。


[^29] (I changed Breiman's words here slightly; the original has "information" in place of [inference] and "extract some information about" in place of [infer])

（注：我在这里稍微改变了Breiman的话；原文用“信息”（information）代替[推断]（inference），用“提取一些关于”（extract some information about）代替[推断]（[infer]）。

Breiman says that users of data split into two cultures, based on their primary allegiance to one or the other of these goals.

Breiman认为，根据数据使用者更关注哪一个目标，可以大体分为两个文化。


The "generative modeling" $^{30}$  culture seeks to develop stochastic models which fit the data, and then make inferences about the data-generating mechanism based on the structure of those models. Implicit in their viewpoint is the notion that there is a true model generating the data, and often a truly "best" way to analyze the data. Breiman thought that this culture encompassed 98\% of all academic statisticians.

“生成型建模” $^{30}$ 文化试图开发适合数据的随机模型，然后根据这些模型的结构推断数据生成机制。他们的观点隐含着这样一个概念，即有一个真正的模型生成数据，并且通常是分析数据的真正“最佳”方法。Breiman认为这种文化涵盖了98%的学术统计学家。


The "predictive modeling" culture (Breiman used "algorithmic" rather than "predictive") prioritizes prediction and is estimated by Breiman to encompass 2% of academic statisticians-including Breiman-but also many computer scientists and, as the discussion of his article shows, important industrial statisticians. Predictive modeling is effectively silent about the underlying mechanism generating the data, and allows for many different predictive algorithms, preferring to discuss only accuracy of prediction made by different algorithm on various datasets. The relatively recent discipline of machine learning, often sitting within computer science departments, is identified by Breiman as the epicenter of the predictive modeling culture.


“预测型建模”文化（Breiman使用“算法”而不是“预测”）将预测放在首位，据Breiman估计，这一文化包括2%的学术统计人员——包括Breiman——许多计算机科学家，以及很多知名的工业界统计学家。预测型建模实际上对生成数据的潜在机制漠不关心，会尝试各式各样的预测算法，更倾向于讨论不同算法在不同数据集上做出的预测的准确性。Breiman认为，通常隶属于计算机科学系的相对较新的机器学习学科，是预测型建模文化的中心。


Breiman's abstract says, in part

Breiman在摘要中提出：


> The statistical community has been committed to the almost exclusive use of [generative] models. This commitment has led to irrelevant theory, questionable conclusions, and has kept statisticians from working on a large range of interesting current problems. [Predictive] modeling, both in theory and practice, has developed rapidly in fields outside statistics. It can be used both on large complex data sets and as a more accurate and informative alternative to data modeling on smaller datasets. If our goal as a field is to use data to solve problems, then we need to move away from exclusive dependence on [generative] models ...

> 统计界一直致力于尽可能完全使用生成模型。这种理念催生了无关痛痒的理论、似是而非的结论，并使统计学家无法处理当前大量有趣的问题。与之相反的是，预测型建模无论在理论上还是在实践中，都在统计学以外的领域得到了迅速发展。它既可用于大型复杂数据集，也可对较小数据集进行更为准确和信息丰富的建模。如果我们认为目标是使用数据来解决问题，那么我们需要摆脱对生成模型的排他性依赖……


Again, the statistics discipline is called to enlarge its scope.

再一次地，统计学科被要求扩大其涵盖范围。


In the discussion to Breiman's article, esteemed statisticians Sir David Cox of Oxford and Bradley Efron of Stanford both objected in various ways to the emphasis that Breiman was making.

在对Breiman文章的讨论中，牛津大学的著名统计学家 David Cox爵士和斯坦福大学的Bradley Efron曾以多种方式反对Breiman所强调的观点。


- Cox states that in his view, "predictive success ...is not the primary basis for model choice" and that "formal methods of model choice that take no account of the broader objectives are suspect ...".

- Efron stated that "Prediction is certainly an interesting subject but Leo's article overstates both its role and our profession's lack of interest in it."

- Cox 表示，在他看来，“预测成功……不是模型选择的主要基准”，“不考虑更广泛目标的模型选择的方法是不可信的……”。

- Efron 表示，“预测当然是一个有趣的话题，但Breiman的文章夸大了它的作用，也低估了我们对它的兴趣。”

In the same discussion, Bruce Hoadley-a statistician for credit-scoring company Fair, Isaac-engages enthusiastically with Breiman's comments:

在同一次讨论中，信用评分公司Fair Isaac的统计学家 Bruce Hoadley 对 Breiman表达了强烈的支持：


> Professor Breiman's paper is an important one for statisticians to read. He and Statistical Science should be applauded ... His conclusions are consistent with how statistics is often practiced in business. $^{32}$

> Breiman教授的论文是统计学家应该阅读的重要论文。他和《统计科学》杂志都应该受到赞扬……他的结论与统计学在商业中的应用是一致的 $^{32}$。

Fair, Isaac's core business is to support the billions of credit card transactions daily by issuing in real time (what amount to) predictions that a requested transaction will or will not be repaid. Fair, Isaac not only create predictive models but must use them to provide their core business and they must justify their accuracy to banks, credit card companies, and regulatory bodies. The relevance of Breiman's predictive culture to their business is clear and direct.

Fair Isaac的核心业务是实时预测每天数十亿的信用卡交易是否会得到偿还。Fair Isaac不仅创建了预测模型，而且必须使用它们来支撑其核心业务，并且必须向银行、信用卡公司和监管机构证明其准确性。Breiman的预测理念与他们的业务自然息息相关。

> [30] Breiman called this "data modeling," but "generative modeling" brings to the fore the key assumption: that a stochastic model could actually generate such data. So we again change Breiman's terminology slightly.

> [30] Breiman将此称为“数据建模”，但“生成型建模”突出了关键假设：随机模型实际上可以生成此类数据。因此，我们再次稍微改变了Breiman的术语。

> [32] Hoadley worked previously at ATT Bell Labs (Thanks to Ron Kennett for pointing this out).

> [32] Hoadley在ATT贝尔实验室工作（感谢Ron Kennett指出这一点）。
# 6. The Predictive Culture's Secret Sauce

# 6. 预测文化的秘诀

Breiman was right to exhort statisticians to better understand the predictive modeling culture, but his article did not clearly reveal the culture's "secret sauce."

Breiman劝统计学家加深对预测型建模文化的理解是正确的，但他的文章没有明确揭示这种文化的“秘诀”。

## 6.1. The Common Task Framework

## 6.1. 共同任务框架

To my mind, the crucial but unappreciated methodology driving predictive modeling's success is what computational linguist Mark Liberman (Liberman 2010) has called the Common Task Framework (CTF). An instance of the CTF has these ingredients:

在我看来，一个未被认可，但是能推动预测型建模成功的关键方法是计算语言学家Mark Liberman (2010) 所称的——共同任务框架（CTF，The Common Task Framework）。CTF的一个实例包含以下成分：

(A) A publicly available training dataset involving, for each observation, a list of (possibly many) feature measurements, and a class label for that observation.

(A) 一个可公开获得的训练集，其中包括每个观测的（可能是许多）特征测量列表，以及该观测的类别标签。

(B) A set of enrolled competitors whose common task is to infer a class prediction rule from the training data.

(B) 一组参赛者，他们的共同任务是从训练数据中推断出一个分类预测规则。

(C) A scoring referee, to which competitors can submit their prediction rule. The referee runs the prediction rule against a testing dataset, which is sequestered behind a Chinese wall. The referee objectively and automatically reports the score (prediction accuracy) achieved by the submitted rule.

(C) 一个裁判，参赛者可向该裁判员提交其预测规则。裁判对测试数据集执行预测，测试数据集的正确结果参赛者不可见。裁判员客观、自动地报告提交规则所达到的分数（预测准确性）。


All the competitors share the common task of training a prediction rule which will receive a good score; hence the phrase common task framework.

所有参赛者都有一个共同的任务，那就是训练一个预测规则，取得一个高分；这也是“共同任务框架”名字的由来。

A famous recent example is the Netflix Challenge, where the common task was to predict Netflix user movie selections. The winning team (which included AT&T Statistician Bob Bell) won $1M. The dataset used proprietary customer history data from Netflix. However, there are many other examples, often with much greater rewards (implicitly) at stake.

最近一个著名的例子是Netflix挑战赛，其中的共同任务是预测Netflix用户的电影选择偏好。获胜的团队（包括AT&T统计学家Bob Bell）赢得了100万美元。数据集使用了Netflix的客户历史数据。自然，还有很多其他相似的例子，而且往往会伴随着更大的回报。

## 6.2. Experience with CTF

## 6.2. 共同任务框架的经验

The genesis of the CTF paradigm has an interesting connection to our story. In Mark Liberman's telling it starts with J.R. Pierce, a colleague of Tukey's at Bell Labs. Pierce had invented the word "transistor" and supervised the development of the first communication satellite, and served on the Presidential Science Advisory Committee with Tukey in the early/mid 1960s. At the same time that Tukey was evaluating emerging problems caused by over-use of pesticides, Pierce was asked to evaluate the already extensive investment in machine translation research. In the same way that Tukey did not like much of what he saw passing as statistics research in the 1960s, Pierce did not like much of what he saw passing as 1960s machine translation research.

CTF范式的起源与我们的故事有着有趣的联系。在 Mark Liberman的讲述中，这要从贝尔实验室Tukey的同事J.R.Pierce说起。Pierce发明了“晶体管”一词，指导了第一颗通信卫星的开发，并在20世纪60年代初/中期与Tukey一起担任总统科学咨询委员会的成员。在Tukey评估杀虫剂过度使用导致的新问题的同时，Pierce被要求评估已经在机器翻译研究方面的大量投资。正如Tukey不喜欢他在20世纪60年代所看到的统计学研究一样，Pierce也不喜欢他所看到的60年代机器翻译研究。

Now we follow Mark Liberman closely. (https://www.simonsfoundation.org/lecture/reproducible-research-and-thecommon-task-method/) Judging that the field was riddled with susceptibility to "glamor and deceit," Pierce managed to cripple the whole U.S. machine translation research effort-sending it essentially to zero for decades.

现在让我们跟随 Mark Liberman的脚步。Pierce认为这个领域充满了“魅力和欺骗”，他对整个美国机器翻译研究工作的质疑，使得后者几十年间几乎毫无进展。(https://www.simonsfoundation.org/lecture/reproducible-research-and-thecommon-task-method/)

 As examples of glamor and deceit, Pierce referred to theoretical approaches to translation deriving from, for example, Chomsky's so-called theories of language; while many language researchers at the time apparently were in awe of the charisma carried by such theories, Pierce saw those researchers as being deceived by the glamor of (a would-be) theory, rather than actual performance in translation.

作为魅力和欺骗的例子，Pierce提到了翻译的理论方法，例如，乔姆斯基所谓的语言理论；尽管当时许多语言研究人员显然对这些理论所带来的魅力感到敬畏，但Pierce认为这些研究人员被（潜在的）理论的魅力所愚弄，而并未关注翻译模型的实际表现。


Machine Translation research finally reemerged decades later from the Piercian limbo, but only because it found a way to avoid a susceptibility to Pierce's accusations of glamor and deceit. A research team in speech and natural language processing at IBM, which included true geniuses like John Cocke, as well as data scientists avant la lettre Lalit Bahl, Peter Brown, Stephen and Vincent Della Pietra, and Robert Mercer, began to make definite progress toward machine translation based on an early application of the common task framework. A key resource was data: they had obtained a digital copy of the so-called Canadian Hansards, a corpus of government documents which had been translated into both English and French. By the late 1980s, DARPA was convinced to adopt the CTF as a new paradigm for machine translation research. NIST was contracted to produce the sequestered data and conduct the refereeing, and DARPA challenged teams of researchers to produce rules that correctly classified under the CTF.

几十年后，机器翻译研究终于从Pierce的困境中恢复过来，但这主要是因为它找到了一种避免受Pierce魅力和欺骗指控的方法。IBM 语音和自然语言处理研究团队，包括真正的天才 John Cocke，以及数据科学家 avant la lettre Lalit Bahl、Peter Brown、Stephen、Vincent Della Pietra 和 Robert Mercer，基于CTF的早期应用，开始在机器翻译方面取得明确进展。一个关键的资源是数据：他们获得了一份所谓的“加拿大汉萨德”（Canadian Hansards）的数字副本，这是一份翻译成英语和法语的政府文件集。到20世纪80年代末，美国国防高级研究计划局（DARPA）被说服采用CTF作为机器翻译研究的新范式。美国国家标准与技术研究院（NIST）签订了合同，负责生成隔离数据并进行评价，DARPA要求研究人员团队制定在CTF下正确分类的规则。


Variants of CTF have by now been applied by DARPA successfully in many problems: machine translation, speaker identification, fingerprint recognition, information retrieval, OCR, automatic target recognition, and on and on.

目前，DARPA已经成功地将CTF的变体应用于许多问题：机器翻译、语音识别、指纹识别、信息检索、OCR、自动目标识别等等。

The general experience with CTF was summarized by Liberman as follows:

Liberman总结了CFG的一般经验如下：

1. Error rates decline by a fixed percentage each year, to an asymptote depending on task and data quality.

2. Progress usually comes from many small improvements; a change of $1 \%$ can be a reason to break out the champagne.

3. Shared data plays a crucial role-and is reused in unexpected ways.

1. 根据任务和数据质量，错误率每年以固定百分比下降至渐近线。

2. 进步通常来自许多小的改进；一次1%的进步或许就值得开香槟庆祝了。

3. 共享数据起着至关重要的作用，并以意想不到的方式被重用。

The ultimate success of many automatic processes that we now take for granted-Google translate, smartphone touch ID, smartphone voice recognition-derives from the CTF research paradigm, or more specifically its cumulative effect after operating for decades in specific fields. Most importantly for our story: those fields where machine learning has scored successes are essentially those fields where CTF has been applied systematically.

谷歌翻译、智能手机触摸识别、智能手机语音识别等许多自动化过程的最终成功都源自CTF研究范式，或者更具体地说，源自它在特定领域运行了几十年后的累积效应。对于我们的故事来说，最重要的是：机器学习取得成功的领域本质上是CTF被系统应用的领域。

## 6.3. The Secret Sauce

## 6.3. 秘诀

It is no exaggeration to say that the combination of a predictive modeling culture together with CTF is the "secret sauce" of machine learning.

毫不夸张地说，预测型建模文化与CTF的结合是机器学习的“秘诀”。

The synergy of minimizing prediction error with CTF is worth noting. This combination leads directly to a total focus on optimization of empirical performance, which as Mark Liberman has pointed out, allows large numbers of researchers to compete at any given common task challenge, and allows for efficient and unemotional judging of challenge winners. It also leads immediately to applications in a real-world application. In the process of winning a competition, a prediction rule has necessarily been tested, and so is essentially ready for immediate deployment. [^34] (However, in the case of the Netflix Challenge the winning algorithm was never implemented. http://preview.tinyurl.com/ntwlyuu)

最小化预测误差与CTF的协同作用值得注意。这一组合直接导致了对经验绩效的全面优化，正如Mark Liberman 所指出的那样，这使得大量研究人员能够在任何给定的共同任务挑战中进行竞争，并允许对挑战获胜者进行高效、不带情感的评判。它还可以立即引导到现实应用程序中。在赢得比赛的过程中，预测规则必须经过测试，因此基本上可以立即部署。（然而，在Netflix挑战赛中，获胜算法从未被实施。[http://preview.tinyurl.com/ntwlyuu](http://preview.tinyurl.com/ntwlyuu)）


Many "outsiders" are not aware of the CTF's paradigmatic nature and its central role in many of machine learning's successes. Those outsiders may have heard of the Netflix challenge, without appreciating the role of CTF in that challenge. They may notice that "deep learning" has become a white hot topic in the high-tech media, without knowing that the buzz is due to successes of deep learning advocates in multiple CTF-compliant competitions.

许多“局外人”不知道CTF的典范性质及其在许多机器学习成功中的核心作用。这些局外人可能听说过Netflix的挑战，但没有意识到CTF在挑战中的作用。他们可能会注意到，“深度学习”已经成为高科技媒体的热门话题，但他们并不知道，这是因为深度学习倡导者在多个符合CTF的比赛中取得了成功。

Among the outsiders are apparently many mainstream academic statisticians who seem to have little appreciation for the power of CTF in generating progress, in technological field after field. I have no recollection of seeing CTF featured in a major conference presentation at a professional statistics conference or academic seminar at a major research university.

局外人中显然有许多主流的学术统计学家，他们似乎无法理解CTF在诸多技术领域均有所建树的原因。我不记得曾在专业统计会议或大型研究型大学的学术研讨会上看到CTF出现。

The author believes that the Common Task Framework is the single idea from machine learning and data science that is most lacking attention in today's statistical training.

作者认为，CTF是来自机器学习和数据科学的简单概念，但在当今的统计训练中最缺乏关注。

## 6.4. Required Skills

## 6.4. 所需技能

The Common Task Framework imposes numerous demands on workers in a field:

共同任务框架（CTF）对一个领域的工作人员提出了许多要求：

- The workers must deliver predictive models which can be evaluated by the CTF scoring procedure in question. They must therefore personally submit to the information technology discipline imposed by the CTF developers.

- The workers might even need to implement a custommade CTF for their problem; so they must both develop an information technology discipline for evaluation of scoring rules and they must obtain a dataset which can form the basis of the shared data resource at the heart of the CTF.

- 工作人员必须提供可以通过CTF评分程序进行评估的预测模型。因此，他们必须遵守CTF开发人员提出的信息技术准则。

- 工作人员甚至可能需要为他们的问题实施定制的CTF；因此，他们必须开发用于评估评分规则的信息技术学科，并且必须获得一个数据集，该数据集可以构成CTF核心的共享数据资源的基础。



In short, information technology skills are at the heart of the qualifications needed to work in predictive modeling. These skills are analogous to the laboratory skills that a wet-lab scientist needs to carry out experiments. No math required.

简而言之，信息技术技能是预测型建模工作所需资格的核心。这些技能类似于湿实验室科学家进行实验所需的实验室技能，不需要数学。

The use of CTFs really took off at about the same time as the open source software movement began and as the ensuing arrival of quantitative programming environments dominating specific research communities. QPE dominance allowed researchers to conveniently share scripts across their communities, in particular scripts that implement either a baseline prediction model or a baseline scoring workflow. So the skills required to work within a CTF became very specific and very teachable —— can we download and productively tweak a set of scripts?



CTF的应用真正腾飞的同时，开源软件运动开始了，随之而来的是主导特定研究社区的数理编程环境的到来。数理编程环境（QPE）的主导地位允许研究人员在他们的社区中方便地共享脚本，特别是实现基线预测模型或基线评分工作流程的脚本。因此，在CTF中工作所需的技能变得非常具体易学——我们可以下载并高效地调整一组脚本吗？



# 7. Teaching of Today's Consensus Data Science

# 7. 当今共识数据科学的教学

It may be revealing to look at what is taught in today's data science programs at some of the universities that have recently established them. Let us consider the attractive and informative web site for the UC Berkeley Data Science Masters' degree at datascience.berkeley.edu.


看看最近建立数据科学项目的一些大学在今天的数据科学项目中教授的内容，可能会有所启发。让我们看看一下加州大学伯克利分校数据科学硕士学位的网站，它提供了大量颇有吸引力的信息：[datascience.berkeley.edu](datascience.berkeley.edu).

Reviewing the curriculum at https://datascience.berkeley.edu/academics/curriculum/ we find five foundation courses


查看网页 https://datascience.berkeley.edu/academics/curriculum/ 我们找到了五门基础课程


> Research Design and Application for Data and Analysis
> 
> Exploring and Analyzing Data
> 
> Storing and Retrieving Data
> 
> Applied Machine Learning
> 
> Data Visualization and Communication


> 数据与分析的研究设计与应用
> 
> 探索和分析数据
> 
> 存储和检索数据
> 
> 应用机器学习
> 
> 数据可视化和交流

Only "Storing and Retrieving Data" seems manifestly not taught by traditional statistics departments; and careful study of the words reveals that the least traditional topic among the others, "Applied Machine Learning," seems to a statistician thinking about the actual topics covered, very much like what a statistics department might or should offer-however, the use of "machine learning" in the course title is a tip off that the approach may be heavily weighted toward predictive modeling rather than inference.

只有“存储和检索数据”似乎显然不是传统统计系教的。仔细研究这些词可以发现，在所有主题中显得最不传统的“应用机器学习”在统计学家看来似乎是应该实际涵盖的主题，非常像统计系可能或应该提供的内容。然而，在课程标题中使用“机器学习”是一个提示，表明该方法可能会严重偏重于预测型建模而不是推断。


> Machine learning is a rapidly growing field at the intersection of computer science and statistics concerned with finding patterns in data. It is responsible for tremendous advances in technology, from personalized product recommendations to speech recognition in cell phones. This course provides a broad introduction to the key ideas in machine learning. The emphasis will be on intuition and practical examples rather than theoretical results, though some experience with probability, statistics, and linear algebra will be important.


> 机器学习是计算机科学和统计学交叉的一个快速发展的领域，涉及在数据中寻找模式。它促成了技术的巨大进步，从个性化的产品推荐，到手机中的语音识别。本课程广泛介绍了机器学习的关键思想。重点将放在理解和实例，而不是理论结果上，尽管一些概率、统计和线性代数方面的知识将十分重要。

The choice of topics might only give a partial idea of what takes place in the course. Under "Tools," we find an array of core information technology.

只看“主题”可能还无法带我们看到课程内容全貌，在“工具”下，我们找到了一系列核心信息技术。


> Python libraries for linear algebra, plotting, machine learning: numpy, matplotlib, sk-learn / Github for submitting project code

> 用于线性代数、绘图、机器学习的Python库：numpy、matplotlib、sk learn，以及用于提交项目代码的 Github。


In short, course participants are producing and submitting code. Code development is not yet considered utterly de rigueur for statistics teaching, and in many statistics courses would be accomplished using code in R or other quantitative programming environments, which is much "easier" for students to use for data analysis because practically the whole of modern data analysis is already programmed in. However, $R$ has the reputation of being less scalable than Python to large problem sizes. In that sense, a person who does their work in Python might be considered to have worked harder and shown more persistence and focus than one who does the same work in R.

简而言之，课程参与者正在编写和提交代码。代码开发尚未被视为统计教学的绝对必要的工具。在许多统计课程中，代码将使用 R 或其他数理编程环境完成。对于数据分析来说，这些语言比较“容易”让学生上手，因为实际上整个现代数据分析的方法都已经通过这些环境实现了。然而，对于大规模的问题，R 的可扩展性有时被认为不如 Python。从这个意义上讲，使用 Python 进行工作的人可能会被认为比使用 R 进行同样工作的人更加刻苦、更加坚毅、更加专注。（译者注：实际上这是一些刻板印象，交叉使用多种语言是数据分析的常态，且解决问题的方法往往是独立于语言的。）


> Such thoughts continue when we consider the advanced courses.
> 
> Experiments and Causal Inference
> 
> Applied regression and Time Series Analysis
> 
> Legal, Policy, and Ethical Considerations for Data Scientists
> 
> Machine Learning at Scale.
> 
> Scaling up! Really big data.

> 当我们浏览高级课程时，这种印象会继续加深。
> 
> 实验和因果推断（Experiments and Causal Inference）
> 
> 应用回归和时间序列分析（Applied regression and Time Series Analysis）
> 
> 数据科学家的法律、政策和伦理考量（Legal, Policy, and Ethical Considerations for Data Scientists）
> 
> 大规模机器学习（Machine Learning at Scale）
> 
> 扩大！超大规模的数据（Scaling up! Really big data）

The first two courses seem like mainstream statistics courses that could be taught by stat departments at any research university. The third is less familiar but overlaps with "Legal, Policy, and Ethical Considerations for Data Scientists" courses that have existed at research universities for quite a while.

前两门课程看起来像是主流的统计课程，似乎任何研究型大学的统计系都可以教授。第三门不太常见，但同样与研究型大学已经存在了很长一段时间的科研伦理程重叠。（译者注：此处原文有误，已修正。）


The last two courses address the challenge of scaling up processes and procedures to really large data. These are courses that ordinarily would not be offered in a traditional statistics department. Who are the faculty in the UC Berkeley data science program? Apparently not traditionally pedigreed academic statisticians. In the division of the website "About MIDS faculty" on Friday September 11, 2015, I could find mostly short bios for faculty associated with the largely nonstatistical courses (such as "Scaling Up! really Big Data" or "Machine Learning at Scale"). For the approximately 50% of courses covering traditional statistical topics, fewer bios were available, and those seemed to indicate different career paths than traditional statistics Ph.D.'s-sociology Ph.D's or information science Ph.D's. The program itself is run by the information school. $^{35}$

最后两门课程解决了将统计方法扩展到真正大数据的挑战。这些课程通常不会在传统的统计系开设。加州大学伯克利分校数据科学项目的教师是谁？显然不是传统的学术统计学家。在2015年9月11日星期五“关于MIDS教师”网站的子页面，我可以找到大部分与非统计课程相关的教师的简短简历（例如“扩大！超大规模的数据”或“大规模机器学习”）。对于涵盖传统统计主题的大约50%的课程，能找到的简历较少，这些似乎表明它们指向了与传统统计学、社会学或信息科学的博士不同的职业道路。该项目本身由信息学院管理。 $^{35}$

In FoDA, Tukey argued that the teaching of statistics as a branch of mathematics was holding back data analysis. He saw apprenticeship with real data analysts and hence real data as the solution:

在“数据分析之未来（FoDA）”中，Tukey 认为统计学作为数学分支的教学阻碍了数据分析。他认为与数据分析的实际工作者建立学徒制是解决方案，因此真实数据才是解决方案：


> All sciences have much of art in their makeup. As well as teaching facts and well-established structures, all sciences must teach their apprentices how to think about things in the manner of that particular science, and what are its current beliefs and practices. Data analysis must do the same. Inevitably its task will be harder than that of most sciences. Physicists have usually undergone a long and concentrated exposure to those who are already masters of the field. Data analysts even if professional statisticians, will have had far less exposure to professional data analysts during their training. Three reasons for this hold today, and can at best be altered slowly:
>
> - (c1) Statistics tends to be taught as part of mathematics.
> 
> - (c2) In learning statistics per se, there has been limited attention to data analysis.
> 
> - (c3) The number of years of intimate and vigorous contact with professionals is far less for statistics Ph.D.'s than for physics or mathematics Ph.D.'s
>
> Thus data analysis, and adhering statistics, faces an unusually difficult problem of communicating certain of its essentials, one which cannot presumably be met as well as in most fields by indirect discourse and working side by side.


> 所有的科学都有很多艺术成分。除了传授事实和公认的结构之外，所有的科学都必须教他们的学徒如何以特定科学的方式思考问题，以及当前的信仰和实践是什么。数据分析也必须如此。不可避免地，它的任务将比大多数科学更加艰巨。物理学家通常会长期集中地接触那些已经是该领域大师的人。即使是专业的统计学家，通往数据分析师的训练期间，能接触专业数据分析师的机会也会非常之少。今天之所以如此，有三个原因，但最多也只能慢慢改变：
>
> - (c1) 统计学往往被作为数学的一部分。
> 
> - (c2) 在学习统计学本身的过程中，数据分析受到的关注也非常有限。
> 
> - (c3) 统计学博士与专业人士亲密和积极接触的年数远远少于物理学或数学博士。
>
>  因此，数据分析以及基于它的统计学，面临着一个异常困难的问题，即如何传达它的一些核心要点。这个问题不可能通过间接讨论或工作得到解决，即使在其他的很多领域中是可能的。

The Berkeley data science masters program features a capstone course, which involves a data analysis project with a large dataset. The course listing states in part that in the capstone class

伯克利数据科学硕士项目的特色是一个结业课程，它涉及大型数据集的数据分析项目。课程列表部分说明了课程中的内容。


> The final project ... provides experience in formulating and carrying out a sustained, coherent, and significant course of work resulting in a tangible data science analysis project with real-world data ....The capstone is completed as a group/team project (3-4 students), and each project will focus on open, pre-existing secondary data.

> 期末项目将提供制定和实施持续、连贯和重要的工作过程的经验，从而产生带有真实世界数据的有形数据科学分析项目……结业课程将以小组/团队的形式完成（3-4名学生），每个项目都将关注开放的、准备好的数据。


This project seems to offer some of the "apprenticeship" opportunities that John Tukey knew from his college chemistry degree work, and considered important for data analysis.

这个项目似乎提供了一些“学徒”机会，John Tukey 从他的大学化学学位工作中了解到了这些机会，并认为这些机会对数据分析很重要。

Tukey insisted that mathematical rigor was of very limited value in teaching data analysis. This view was already evident in the quotation from FoDA immediately above. Elsewhere in FoDA Tukey said:

Tukey 坚持认为，数学严谨性在数据分析教学中的价值非常有限。这一观点在上面引述的“数据分析之未来（FoDA）”中已经很明显了。在 FoDA 的其他地方，Tukey 说：


> Teaching data analysis is not easy, and the time allowed is always far from sufficient. But these difficulties have been enhanced by the view that "avoidance of cookbookery and growth of understanding come only by mathematical treatment, with emphasis upon proofs." The problem of cookbookery is not peculiar to data analysis. But the solution of concentrating upon mathematics and proof is.

> 教授数据分析并不容易，所投入的时间也总是远远不够。但是，有观点认为“避免教条主义，加深实际理解只能通过数学学习，尤其是数学证明”，因此这样的观点实际上加深了数据分析学习的困难。“教条主义”的问题并不是数据分析所特有的；专注于数学和证明的解决方案才是。

Tukey saw data analysis as like other sciences and not like mathematics, in that there existed knowledge which needed to be related rather than theorems which needed proof. Drawing again on his chemistry background, he remarked that

Tukey 认为数据分析就像其他科学，而不是数学，因为存在需要关联的知识，而不是需要证明的定理。他再次根据自己的化学背景，指出

> The field of biochemistry today contains much more detailed knowledge than does the field of data analysis. The overall teaching problem is more difficult. Yet the textbooks strive to tell the facts in as much detail as they can find room for.

> 今天的生物化学领域比数据分析领域包含了更详细的知识。整体教学问题更难。然而，教科书力求尽可能详细地讲述事实。


He also suggested that experimental labs offered a way for students to learn statistics

他还建议实验室为学生提供学习统计学的试验方法：

> These facts are a little complex, and may not prove infinitely easy to teach, but any class can check almost any one of them by doing its own experimental sampling.

> 这些事实有点复杂，可能不太容易教授，但任何一个班级都可以通过自己的实验抽样来检查其中的任何一个。

One speculates that John Tukey might have viewed the migration of students away from statistics courses and into equivalent data science courses as possibly not a bad thing.

有人因而认为，John Tukey 可能认为学生从统计学课程转换到同类的数据科学课程并不是坏事。

In his article "Statistical Modeling: The Two Cultures," Leo Breiman argued that teaching stochastic model building and inference to the exclusion of predictive modeling was damaging the ability of statistics to attack the most interesting problems he saw on the horizon. The problems he mentioned at the time are among today's hot applications of data science. So Breiman might have welcomed teaching programs which reverse the balance between inference and prediction, that is, programs such as the UC Berkeley data science masters.

在《统计建模：两种文化》一文中，Leo Breiman 认为，教授随机模型构建和推断而拒绝预测型建模，会使得统计学无法处理它所涉及的最有趣的问题。他当时提到的问题是当今数据科学的热门应用之一。因此，Breiman 可能会欢迎打破推断和预测之间平衡的教学项目，也就是说，像加州大学伯克利分校数据科学硕士这样的项目。



Although my heroes Tukey, Chambers, Cleveland, and Breiman would recognize positive features in these programs, it is difficult to say whether they would approve of their long-term direction-or if there is even a long-term direction to comment about. Consider this snarky definition:


尽管我心目中的英雄 Tukey、Chambers、Cleveland 和 Breiman 会认识到这些项目积极的一面，但很难说他们是否会认可它们的长期方向，或者是否有一个长期方向可以评论。考虑一下这个蹩脚的定义：

> Data Scientist (n.): Person who is better at statistics than any software engineer and better at software engineering than any statistician.

> 数据科学家（名词）：比任何软件工程师更擅长统计，比任何统计学家更擅长软件工程的人。


This definition is grounded in fact. Data science masters' curricula are compromises: taking some material out of a statistics master's program to make room for large database training; or, equally, as taking some material out of a database masters in CS and inserting some statistics and machine learning. Such a compromise helps administrators to quickly get a degree program going, without providing any guidance about the longterm direction of the program and about the research which its faculty will pursue. What long-term guidance could my heroes have offered?

这个定义实际上是有根据的。数据科学硕士课程是妥协的产物：从统计硕士课程中拿走一些材料，为大型数据库培训腾出空间；或者，同样地，从计算机数据库硕士课程中删掉一些内容，并加入一些统计学和机器学习。这样的妥协有助于管理人员快速设置学位课程，而无需对课程的长期方向以及教师的研究方向提供任何指导。我心中的英雄们会提供什么样的指导呢？


> [35] I do not wish to imply in the above that there is anything concerning to me about the composition of the faculty. I do wish to demonstrate that this is an opportunity being seized by nonstatisticians. An important event in the history of academic statistics was Hotelling's article "The Teaching of Statistics" (1940) (Hotelling 1940) which decried the teaching of statistics by nonmathematicians, and motivated the formation of academic statistics departments. The new developments may be undoing the many years of postwar professionalization of statistics instruction.

> [35] 我不想暗示学院教师的组成与我有任何关系。我只是想证明，这是一个被非政府组织抓住的机会。学术统计史上的一个重要事件是 Hotelling 的文章《统计教学》（Hotelling, 1940），该文谴责了由非数学家教授统计学的行为，并推动了学术统计系的成立。但这些新的发展可能正在摧毁战后多年的统计教学专业化。


# 8. The Full Scope of Data Science

# 8. 数据科学的范畴


John Chambers and Bill Cleveland each envisioned a wouldbe field that is considerably larger than the consensus data science master's we have been discussing but at the same time more intellectually productive and lasting.

John Chambers 和 Bill Cleveland 各自设想了一个比我们一直在讨论的共识数据科学硕士大得多的领域，但同时在才智上更有成效、更持久。

The larger vision posits a professional on a quest to extract information from data-exactly as in the definitions of data science we saw earlier. The larger field cares about each and every step that the professional must take, from getting acquainted with the data all the way to delivering results based upon it, and extending even to that professional's continual review of the evidence about best practices of the whole field itself.

更大的视野让专业人士寻求从数据中提取信息——就像我们之前看到的数据科学的定义一样。更大的领域关心专业人士必须采取的每一步，从熟悉数据到基于数据交付结果，甚至延伸到专业人士对整个领域本身最佳实践证据的持续审视。


Following Chambers, let us call the collection of activities mentioned until now "lesser data science" (LDS) and the larger would-be field greater data science (GDS). Chambers and Cleveland each parsed out their enlarged subject into specific divisions/topics/subfields of activity. I find it helpful to merge, relabel, and generalize the two parsings they proposed. This section presents and then discusses this classification of GDS.

继 Chambers 之后，让我们将迄今为止提到的活动集合称为“狭义数据科学”（LDS, lesser data science），将更大的潜在领域称为“广义数据科学”（GDS, greater data science）。Chambers 和 Cleveland 各自将他们的主题分解为特定的部门、主题和活动子领域。我发现合并、重新标记和概括他们提出的两个部分很有帮助。本节介绍并讨论 GDS 的这一分类。

## 8.1.  The Six Divisions

## 8.1. 六个部分

The activities of GDS are classified into six divisions:

广义数据科学（GDS）的活动分为六个部分：

1. Data Gathering, Preparation, and Exploration

2. Data Representation and Transformation

3. Computing with Data

4. Data Modeling

5. Data Visualization and Presentation

6. Science about Data Science

 
1. 数据收集、准备和探索
2. 数据表示和转换
3. 基于数据的计算
4. 数据建模
5. 数据可视化和展示
6. 关于数据科学的科学

Let's go into some detail about each division.

让我们详细了解一下每个部分。

**GDS1: Data Gathering, Preparation, and Exploration**. 

**GDS1：数据收集、准备和探索**。


Some say that 80% of the effort devoted to data science is expended by diving into or becoming one with one's messy data to learn the basics of what's in them, so that data can be made ready for further exploitation. We identify three subactivities:

有人说，80%的数据科学精力投入都是通过深入或融入杂乱的数据来学习其中的基本知识，从而为进一步开发数据做好准备。我们确定了三个子活动：

- Gathering. This includes traditional experimental design as practiced by statisticians for well over a century, but also a variety of modern data gathering techniques and data resources. Thus, Google nGrams viewer can quantify the entire corpus of literature 1500-2008, Google Trends can quantify recent web search interests of the whole population and even of localities, humans are taking 1 trillion photos a year, many of which are posted in social media; (https://arxiv.org/abs/1706.01869) billions of utterances are posted on social media.((https://arxiv.org/abs/1704.05579)) We have new data-making technologies like next generation sequencing in computational biology, GPS location fixes, supermarket scanner data. Next gen skills can include web scraping, Pubmed scraping,(http://jamanetwork.com/journals/jama/fullarticle/2503172) image processing, and Twitter, Facebook, and Reddit munging.

- **数据收集**。这包括统计学家在一个多世纪以来实践的传统实验设计，也包括各种现代数据收集技术和数据资源。举例来说，Google nGrams 查看器可以量化1500-2008年的整个文献集，Google Trends 可以量化全部人口甚至细化到地方的网络搜索兴趣，人类每年拍摄1万亿张照片，其中许多照片发布在社交媒体上；(https://arxiv.org/abs/1706.01869) 数十亿的文字内容被发布在社交媒体上。(https://arxiv.org/abs/1704.05579) 我们拥有新的数据提取技术，如计算生物学中的下一代测序、GPS 定位和超市扫描仪数据。下一代技术可以包括网页抓取、Pubmed 抓取、图像处理，以及 Twitter、Facebook 和 Reddit munging。(http://jamanetwork.com/journals/jama/fullarticle/2503172)

- Preparation. Many datasets contain anomalies and artifacts. $^{39}$ Any data-driven project requires mindfully identifying and addressing such issues. Responses range from reformatting and recoding the values themselves, to more ambitious preprocessing, such as grouping, smoothing, and subsetting. Often today, one speaks colorfully of data cleaning and data wrangling.

- **数据准备**。许多数据集包含异常和错误 $^{39}$。任何数据驱动的项目都需要仔细识别和解决这些问题。响应范围从重新格式化和重新编码值本身，到更宏大的预处理，如分组、平滑和取子集。今天，人们经常谈论数据清理和数据合并。

- Exploration. Since John Tukey's coining of the term "exploratory data analysis" (EDA), we all agree that every data scientist devotes serious time and effort to exploring data to sanity-check its most basic properties, and to expose unexpected features. Such detective work adds crucial insights to every data-driven endeavor.  $^{40}$ 

- **数据探索**。自从 John Tukey 发明了“探索性数据分析”（EDA）一词以来，我们都同意，每个数据科学家都花了大量的时间和精力来探索数据，以检查其最基本的属性，并揭示意外的特征。这样的探索工作为每一项数据驱动的努力增添了至关重要的洞察力 $^{40}$。 


> [39] Peter Huber (2010) recalled the classic Coale and Stephan article on teenage widows (Coale and Stephan 1962). In this example, a frequent coding error in a census database resulted in excessively large counts of teenage widows_until the error was rooted out. This example is quaint by modern standards. If we process natural language in the wild, such blogs and tweets, anomalies are the order of the day.

> [39] Peter Huber (2010) 回忆了 Coale 和 Stephan 关于青少年寡妇的经典文章（Coale和Stephen, 1962）。在本例中，人口普查数据库中频繁的编码错误导致青少年丧偶人数过多，直到错误被消除。以现代标准来看，这个例子很奇怪。我们在处理博客和推文等自然语言时，异常现象就是常态。

> [40] At the Tukey Centennial, Rafael Irizarry gave a convincing example of exploratory data analysis of GWAS data, studying how the data row mean varied with the date on which each row was collected, convince the field of gene expression analysis to face up to some data problems that were crippling their studies. 

> [40] 在Tukey 百年纪念上，Rafael Irizarry 给出一个令人信服的例子，对 GWAS 数据进行探索性数据分析。研究了数据行的平均值如何随每一行的收集日期而变化，并说服基因表达分析领域正视一些影响其研究的数据问题。


**GDS2: Data Representation and Transformation.** 

**GDS2：数据展示和转换。**

A data scientist works with many different data sources during a career. These assume a very wide range of formats, often idiosyncratic ones, and the data scientist has to easily adapt to them all. Current hardware and software constraints are part of the variety because access and processing may require careful deployment of distributed resources.

数据科学家在职业生涯中处理许多不同的数据源。这些数据源采用的格式千奇百怪，通常各有不同，数据科学家必须很容易地适应所有这些格式。当前的硬件和软件限制是多样性的一部分，因为访问和处理可能需要仔细部署分布资源。


Data scientists very often find that a central step in their work is to implement an appropriate transformation restructuring the originally given data into a new and more revealing form.

数据科学家经常发现，他们工作中的一个核心步骤是实施适当的转换，将最初给定的数据重组为新的、更具启发性的形式。


Data scientists develop skills in two specific areas:

数据科学家在两个特定领域培养技能：

- Modern Databases. The scope of today's data representation includes everything from homely text files and spreadsheets to SQL and noSQL databases, distributed databases, and live data streams. Data scientists need to know the structures, transformations, and algorithms involved in using all these different representations.

- **现代数据库**。今天的数据表示范围非常广，从简单的文本文件和电子表格到 SQL 和 noSQL 数据库、分布式数据库和实时数据流。数据科学家需要知道使用所有这些不同表示所涉及的结构、转换和算法。

- Mathematical Representations. These are interesting and useful mathematical structures for representing data of special types, including acoustic, image, sensor, and network data. For example, to get features with acoustic data, one often transforms to the cepstrum or the Fourier transform; for image and sensor data the wavelet transform or some other multi scale transform (e.g., pyramids in deep learning). Data scientists develop facility with such tools and mature judgment about deploying them.

- **数学表示**。这些是有趣且有用的数学结构，用于表示特殊类型的数据，包括声学、图像、传感器和网络数据。例如，为了获得声学数据的特征，人们经常转换到倒谱或傅里叶变换；对于图像和传感器数据，小波变换或其他一些多尺度变换（例如深度学习中的金字塔型特征提取）。数据科学家需要利用这些工具进行开发，并对其部署做出成熟判断。


**GDS3: Computing with Data**. 

**GDS3：基于数据的计算**。


Every data scientist should know and use several languages for data analysis and data processing. These can include popular languages like R and Python, but also specific languages for transforming and manipulating text, and for managing complex computational pipelines. It is not surprising to be involved in ambitious projects using a half dozen languages in concert.


每个数据科学家都应该知道并使用多种编程语言进行数据分析和数据处理。这些编程语言可以包括 R 和 Python 等流行语言，也可以包括用于转换、操作文本以及管理复杂计算管道的特定语言。一个大项目同时涉及六种不同语言也并不奇怪。

Beyond basic knowledge of languages, data scientists need to keep current on new idioms for efficiently using those languages and need to understand the deeper issues associated with computational efficiency. Cluster and cloud computing and the ability to run massive numbers of jobs on such clusters has become an overwhelmingly powerful ingredient of the modern computational landscape. To exploit this opportunity, data scientists develop workflows which organize work to be split up across many jobs to be run sequentially or else across many machines.


除了编程语言的基本知识之外，数据科学家还需要了解有效使用这些语言的新习惯用法，并需要了解与计算效率相关的更深层次的问题。集群和云计算以及在这些集群上运行大量任务的能力已经成为现代计算环境中一个极其强大的组成部分。为了利用这一机会，数据科学家需要开发工作流（workflows），这些工作流将工作分为多个任务，依次运行或跨多台机器运行。

Data scientists also develop workflows that document the steps of an individual data analysis or research project.

数据科学家还将搭建工作流，记录单个数据分析或研究项目的步骤。

Finally, data scientists develop packages that abstract commonly used pieces of workflow and make them available for use in future projects.

最后，数据科学家需要开发一些软件包，这些软件包抽象了常用的工作流片段，并将其用于未来的项目。

**GDS4: Data Visualization and Presentation.** 

**GDS4：数据可视化和展示。**


Data visualization at one extreme overlaps with the very simple plots of EDA-histograms, scatterplots, time series plotsbut in modern practice it can be taken to much more elaborate extremes. Data scientists often spend a great deal of time decorating simple plots with additional color or symbols to bring in an important new factor, and they often crystallize their understanding of a dataset by developing a new plot which codifies it. Data scientists also create dashboards for monitoring data processing pipelines that access streaming or widely distributed data. Finally, they develop visualizations to present conclusions from a modeling exercise or CTF challenge.

数据可视化可以通过 EDA 中的直方图、散点图、时间序列图等简单方式呈现，但在实践中，它远不止这些。数据科学家经常花费大量时间用更多的颜色或符号来修饰图像，以引入一个重要的新变量。他们还经常通过开发一个新的图形类型以加深他们对数据集的理解。数据科学家还创建了仪表板，用于监控访问流或广泛分布数据的数据处理管道。最后，他们开发了可视化工具，以展示建模结果或共同任务框架（CTF）挑战的结论。


**GDS5: Data Modeling**. 

**GDS5：数据建模**。


Each data scientist in practice uses tools and viewpoints from both of Leo Breiman's modeling cultures:

在实践中，每位数据科学家都使用来自 Leo Breiman 两种建模文化的工具和观点：


- Generative modeling, in which one proposes a stochastic model that could have generated the data, and derives methods to infer properties of the underlying generative mechanism. This roughly speaking coincides with traditional academic statistics and its offshoots. $^{41}$

- **生成型建模**，提出了一个可以生成数据的随机模型，并推导出推断潜在生成机制属性的方法。这大致上与传统的学术统计及其分支相吻合 $^{41}$。

- Predictive modeling, in which one constructs methods which predict well over some given data universe-that is, some very specific concrete dataset. This roughly coincides with modern Machine Learning, and its industrial offshoots.  $^{42}$

- **预测型建模**，构建预测模型，可以在一些具体给定的数据集上作出很好的预测。这与现代机器学习及其产业分支大致吻合 $^{42}$。


> [41] It is striking how, when I review a presentation on today's data science, in which statistics is superficially given pretty short shrift, I cannot avoid noticing that the underlying tools, examples, and ideas which are being taught as data science were all literally invented by someone trained in Ph.D. statistics, and in many cases the actual software being used was developed by someone with an MA or Ph.D. in statistics. The accumulated efforts of statisticians over centuries are just too overwhelming to be papered over completely, and cannot be hidden in the teaching, research, and exercise of Data Science.)

> [41] 令人惊讶的是，当回顾一篇关于当今数据科学的演讲时，我很自然地注意到，数据科学教授的基本工具、示例和思想都是由受过统计学博士训练的人发明的。大多情况下，实际使用的软件也是由拥有统计学硕士或博士学位的人开发的。几个世纪以来，统计学家们积累的贡献不胜枚举，无法掩盖，也无法隐藏在数据科学的教学、研究和实践中。


> [42] Leo Breiman (2001) was correct in pointing out that academic statistics departments (at that time, and even since) have under-weighted the importance of the predictive culture in courses and hiring. It clearly needs additional emphasis.

> [42] Leo Breiman (2001) 正确地指出，学术统计系（当时，甚至从那时起）低估了预测文化在课程和招聘中的重要性，这显然有待改进。


**GDS6: Science about Data Science**. 

**GDS6：关于数据科学的科学**。


Tukey proposed that a "science of data analysis" exists and should be recognized as among the most complicated of all sciences. He advocated the study of what data analysts "in the wild" are actually doing, and reminded us that the true effectiveness of a tool is related to the probability of deployment times the probability of effective results once deployed.  $^{43}$

Tukey 提出，“数据分析科学”是存在的，而且应该被认为是所有科学中最复杂的科学之一。他提倡研究数据分析师“在野外”实际在做什么，并提醒我们，工具的真正有效性需要同时考虑部署概率以及部署后的有效结果概率 $^{43}$。



Data scientists are doing science about data science when they identify commonly occurring analysis/processing workflows, for example, using data about their frequency of occurrence in some scholarly or business domain; when they measure the effectiveness of standard workflows in terms of the human time, the computing resource, the analysis validity, or other performance metric, and when they uncover emergent phenomena in data analysis, for example, new patterns arising in data analysis workflows, or disturbing artifacts in published analysis results.

当数据科学家识别常见的分析/处理工作流时，他们正在进行数据科学方面的科学研究，例如，使用关于其在某些学术或商业领域中出现频率的数据；当他们在人力时间、计算资源、分析有效性或其他性能度量方面衡量标准工作流的有效性时，当他们发现数据分析中出现的现象时，例如，数据分析工作流中出现的新模式，或公开发表的分析结果中存在的令人不安的【人为因素】。


The scope here also includes foundational work to make future such science possible-such as encoding documentation of individual analyses and conclusions in a standard digital format for future harvesting and meta-analysis.

这里的范畴还包括使未来此类科学成为可能的基础工作——例如以标准数字格式对单个分析和结论进行编码留档，以备将来收获和荟萃分析（meta-analysis）。

As data analysis and predictive modeling becomes an ever more widely distributed global enterprise, "science about data science" will grow dramatically in significance.

随着数据分析和预测型建模成为一个分布越来越广泛的全球行业，“关于数据科学的科学”的重要性将显著增加。

> [43] Data analysis per se is probably too narrow a term, because it misses all the automated data processing that goes on under the label of data science about which we can also make scientific studies of behavior "in the wild."

> [43] 数据分析本身可能是一个过于狭隘的术语，因为它忽略了数据科学标签下的所有自动化数据处理，我们也可以对“野外”行为进行科学研究。

## 8.2 Discussion

## 8.2讨论

These six categories of activity, when fully scoped, cover a field of endeavor much larger than what current academic efforts teach or study.  $^{44,45}$ Indeed, a single category-"GDS5: Data Modeling"-dominates the representation of data science in today's academic departments, either in statistics and mathematics departments through traditional statistics teaching and research, or in computer science departments through machine learning.

这六类活动，如果进行充分概括，涵盖的领域远远大于当前学术统计努力教授或研究的领域 $^{44,45}$。事实上，“GDS5：数据建模”这一单个类别主导了当今学术部门中数据科学的表现，无论是通过统计和数学部门下的传统统计教学和研究，还是通过计算机科学部门下的机器学习。

This parsing-out reflects various points we have been trying to make earlier:

这一分析反映了我们之前一直试图证明的各种观点：


- The wedge issue that computer scientists use to separate "data science" from "statistics" is acknowledged here, by the addition of both "GDS3: Computing with Data" and "GDS2: Data Representation" as major divisions alongside "GDS5: Data Modeling."  $^{47,48}$ 

- 计算机科学家用来将“数据科学”与“统计学”区分开来的关键问题在这里得到明确，“GDS3：基于数据的计算”和“GDS2：数据表示”作为“GDS5：数据建模”的主要部分 $^{47,48}$。


- The tension between machine learning and academic statistics is suppressed in the above classification; much of it is irrelevant to what data scientists do on a daily basis. As I say above, data scientists should use both generative and predictive modeling.

- 上述分类掩盖了机器学习和学术统计之间的紧张关系；其中大部分与数据科学家每天的工作无关。正如我上面所说，数据科学家应该同时使用生成和预测型建模。

 
- The hoopla about distributed databases, Map/Reduce, and Hadoop is not evident in the above classification. Such tools are relevant for "GDS2: Data Representation" and "GDS3: Computing with Data" but although they are heavily cited right now, they are simply today's enablers of certain larger activities. Such activities will be around permanently, while the role for enablers like Hadoop will inevitably be streamlined away.

- 关于分布式数据库、Map/Reduce 和 Hadoop 的喧嚣在上述分类中并不明显。这些工具与“GDS2：数据表示”和“GDS3：基于数据的计算”相关，但尽管它们现在被大量引用，但它们只是当今某些更大活动的推动者。这样的活动将永久存在，而 Hadoop 等推动者的角色将不可避免地被精简。

- Current masters programs in data science cover only a fraction of the territory mapped out here. Graduates of such programs would not have had sufficient exposure to exploring data, data cleaning, data wrangling, data transformation, science about data science, and other topics in GDS.

- 当前的数据科学硕士课程仅涵盖此处所示领域的一小部分。这类课程的毕业生无法充分接触探索数据、数据清理、数据整理、数据转换、关于数据科学的科学以及 GDS 中的其他主题。



Other features of this inventory will emerge below.

本清单的其他特征将在下文中出现。

> [44]: John Chambers' 1993 vision of "greater statistics" proposed three divisions: data preparation, data modeling, and data presentation. We accommodated them here in "GDS1: Data Exploration and Preparation;" "GDS5: Data Modeling," and "GDS4: Data Visualization and Presentation," respectively.

> [44] John Chambers 1993年提出的“大统计”愿景提出了三个部分：数据准备、数据建模和数据展示。我们在此编排为“GDS1：数据探索和准备”分别为“GDS5：数据建模”和“GDS4：数据可视化和展示”。


> [45]: Cleveland's 2001 program for data science included several categories which can be mapped onto (subsets) of those proposed here, for example:
> 
> - Cleveland's categories "Theory" and "Stochastic Models and Statistical Methods" can be mapped into GDS either onto the "Generative Models" subset of "GDS5: Data Modeling" or onto "GDS5 Data Modeling" itself.
> - His category "Computing with Data" maps onto a subset of GDS' category of the same name; the GDS category has expanded to cover developments such as Hadoop and AWS that were not yet visible in 2001.
> - Cleveland's category "Tool Evaluation" can be mapped onto a subset of "GDS6: Science about Data Science"

> [45] Cleveland 2001年的数据科学计划包括几个类别，可以映射到这里提出的类别（或其子集），例如：
> - Cleveland 的分类“理论”和“随机模型与统计方法”可以映射到“GDS5：数据建模”中的“生成式模型”子集，或映射到“GDS5：数据建模”本身。
> - 他的类别“基于数据的计算”映射到 GDS 同名类别的子集；GDS 类别已经扩展到包括 Hadoop 和 AWS 等在内的 2001 年尚未出现的技术。
> - Cleveland 的类别“工具评估”可以映射到“GDS6：关于数据科学的科学”的子集上。


> [46]: Cleveland also allocated resources to multidisciplinary investigations and pedagogy. It seems to me that these can be mapped onto subsets of our categories. For example, pedagogy ought to be part of the science about data science-we can hope for evidence-based teaching. 

> [46] Cleveland 还为多学科调查和教学分配了资源。在我看来，这些可以映射到我们类别的子集上。例如，教学方法应该是数据科学的一部分，我们可以期待循证教学。


> [47] In our opinion, the scaling problems though real are actually transient (because technology will trivialize them over time). The more important activity encompassed under these divisions are the many ambitious and even audacious efforts to reconceptualize the standard software stack of today's data science.

> [47] 在我们看来，数据规模问题虽然是真实的，但实际上是暂时的（因为随着时间的推移，技术会使它们变得微不足道）。这些部门所包含的更重要的活动是许多雄心勃勃甚至大胆的努力，以重新定义当今数据科学的标准软件栈。

> [48] Practically speaking, every statistician has to master database technology in the course of applied projects. 

> [48] 实际上，每个统计学家都必须在应用项目过程中掌握数据库技术。


## 8.3. Teaching of GDS

## 8.3. 广义数据科学（GDS）教学

Full recognition of the scope of GDS would require covering each of its six branches. This demands major shifts in teaching.

全面承认广义数据科学（GDS）的范畴需要涵盖其六个分支中的每一个。这需要教学的重大转变。

"GDS5: Data Modeling" is the easy part of data science to formalize and teach; we have been doing this for generations in statistics courses; for a decade or more in machine learning courses; and this pattern continues in the data science masters programs being introduced all around us, where it consumes most of the coursework time allocation. However, this "easy stuff" covers only a fraction of the effort required in making productive use of data.

“GDS5：数据建模”是数据科学中易于形式化和教授的部分；我们已经长期在统计学课程中这样做了；在机器学习课程中已经做了十年或更长时间；这种模式在我们周围正在引入的数据科学硕士课程中继续存在，它消耗了大部分课程时间分配。然而，这种“简单的东西”只涵盖了有效利用数据所需努力的一小部分。


"GDS1: Data Gathering, Preparation, and Exploration" is more important than "GDS5: Data Modeling," as measured using time spent by practitioners. But there have been few efforts to formalize data exploration and cleaning and such topics still are neglected in teaching. Students who only analyze precooked data are not being given the chance to learn these essential skills.

根据从业人员花费的时间来衡量，“GDS1：数据收集、准备和探索”比“GDS5：数据建模”更重要。但是很少有人努力将数据探索和清理正规化，这些主题在教学中仍然被忽视。只分析预先准备好的数据的学生没有机会学习这些基本技能。


How might teaching even address such a topic? I suggest the reader study carefully two books (together).

教学如何解决这样的问题？我建议读者仔细研读这两本书。

- The Book (Tango, Lichtman, and Dolphin 2007) analyzes a set of databases covering all aspects of the American game of major league baseball, including every game played in recent decades and every player who ever appeared in such games. This amazingly comprehensive work considers a near-exhaustive list of questions one might have about the quantitative performance of different baseball strategies, carefully describes how such questions can be answered using such a database, typically by a statistical two-sample test (or A/B test in internet marketing terminology).

- （Tango, Lichtman, and Dolphin 2007）这本书分析了一套涵盖美国职业棒球大联盟比赛所有方面的数据集，包括近几十年来进行的每一场比赛和曾经出现在比赛中的每一个球员。这项令人惊讶的全面工作考虑了一系列关于不同棒球策略的量化表现的问题，仔细描述了如何使用这样的数据库来回答这些问题，通常通过统计双样本测试（或互联网营销术语中的 A/B 测试）。

- Analyzing Baseball Data with R (Marchi and Albert 2013) showed how to access the impressive wealth of available Baseball data using the internet and how to use R to insightfully analyze that data.

- 使用 R 分析棒球数据（Marchi and Albert 2013）展示了如何使用互联网访问丰富的可用棒球数据，以及如何使用 R 深入分析这些数据。


A student who could show how to systematically use the tools and methods taught in the second book to answer some of the interesting questions in the first book would, by my lights, have developed real expertise in the above division "GDS1: Data Gathering, Preparation, and Exploration." Similar projects can be developed for all the other "new" divisions of data science. In "GDS3: Computing with Data," one could teach students to develop and new R packages, and new data analysis workflows, in a hands-on manner.

如果一个学生能够做到使用第二本书中教授的工具和方法来回答第一本书中的一些有趣问题，在我看来，他就在“GDS1：数据收集、准备和探索”中获得了真实的专业技能。类似的项目也可以用在数据科学的“新”部分中。比如，在“GDS3：基于数据的计算”中，我们可以教学生上手来开发新的 R 包和新的数据分析工作流。

Ben Baumer and co-authors review experiences in Horton, Baumer, and Wickham (2015) and Baumer (2015) teaching first and second courses in data science/statistics that are consistent with this approach.

Ben Baumer 及其合著者回顾了 Horton、Baumer 和 Wickham（2015）以及 Baumer（2015）教授数据科学/统计学入门课程的经验，这些课程与该方法理念一致。


The reader will worry that the large scope of GDS is much larger than what we are used to teaching. Tukey anticipated such objections, by pointing out that biochemistry textbooks seem to cover much more material than statistics textbooks; he thought that once the field commits to teaching more ambitiously, it can simply "pick up the pace." $^{49}$

读者可能会担心广义数据科学（GDS）的范围太大，这要比我们常规的教学要大得多。Tukey 预料到了这样的反对意见，他指出生物化学教科书似乎比统计教科书涵盖了更多的材料；他认为，一旦该领域更加雄心勃勃地致力于教学，它就可以简单地“加快步伐” $^{49}$。

> [49] Tukey also felt that focusing on mathematical proof limited the amount of territory that could be covered in university teaching.

> [49] Tukey还认为，专注于数学证明限制了大学教学所能涵盖的领域。

## 8.4. Research in GDS

## 8.4. GDS 研究

Once we have the GDS template in mind, we can recognize that today there is all sorts of interesting-and highly impactful"GDS research." Much of it does not have a natural "home," yet, but GDS provides a framework to organize it and make it accessible. We mention a few examples to stimulate the reader's thinking.

一旦我们记住了 GDS 的模板，我们就可以认识到今天有各种有趣且极具影响力的“GDS研究”。虽然很多这类研究还没有一个自然的“家”，但 GDS 提供了一个框架来组织它并使其易于访问。我们举几个例子来激发读者的思考。

### 8.4.1. Quantitative Programming Environments: R

### 8.4.1. 数理编程环境：R


The general topic of "computing with data" may sound at first as if it is stretchable to cover lots of mainstream academic computer science; suggesting that perhaps there is no real difference between data science and computer science. To the contrary, "computing with data" has a distinct core, and an identity separate from academic computer science. The litmus test is whether the work centers on the need to analyze data.

“基于数据的计算”这个总的话题乍一听似乎可以延伸到许多主流的学术计算机科学；这表明数据科学和计算机科学之间也许没有真正的区别。但相反，“基于数据的计算”有一个独特的核心，它与学术计算机科学不同。问题的关键在于一项工作是否是以分析数据为中心。


We argued earlier that the R system transformed the practice of data analysis by creating a standard language which different analysts can all use to communicate and share algorithms and workflows. Becker and Chambers (with S) and later Ihaka, Gentleman, and members of the R Core team (with R) conceived of their work as research how to best organize computations with statistical data. I too classify this as research, addressing category "GDS 3: Computing with Data." Please note how essentially ambitious the effort was, and how impactful. In recently reviewing many online presentations about data science initiatives, I was floored to see how heavily R is relied upon, even by data science instructors who claim to be doing no statistics at all.

我们之前谈到，R 系统通过创建一种标准语言彻底改变了数据分析的实践，不同的分析师都可以使用这种语言来交流和共享算法和工作流程。Becker 和 Chambers（S）以及后来的 Ihaka、Gentleman 和 R 核心团队的成员（R）将他们的工作设想为研究如何用统计学最好地组织计算。我也将其归类为研究，涉及类别“GDS 3：基于数据的计算”。请注意这项工作本质上是多么雄心勃勃，多么有影响力。在最近回顾了许多关于数据科学计划的在线演示时，我惊讶地发现，即使是声称根本不做统计的数据科学讲师，对 R 的依赖程度也是如此之高。

### 8.4.2. Data Wrangling: Tidy Data

### 8.4.2. 数据整理：清洗数据


Hadley Wickham is a well-known contributor to the world of statistical computing, as the author of numerous packages becoming popular with R users everywhere; these include ggplot2, reshape2, plyr, tidyr, dplyr; Wickham (2011), Wickham et al. (2007), and Wickham et al. (2011). These packages abstractify and attack certain common issues in data science subfield "GDS 2: Data Representation and Transformation" and also subfield "GDS 4: Data Visualization and Presentation," and Wickham's tools have gained acceptance as indispensable to many.


Hadley Wickham 是统计计算领域的知名贡献者，他开发了众多流行的软件包，包括 ggplot2、reshape2、plyr、tidyr、dplyr 等，这些包在世界各地的 R 用户中广受欢迎；参见 Wickham（2011）、Wickham 等（2007）和 Wickham 等（2011）。这些软件包抽象并解决了数据科学子领域“GDS 2：数据表示和转换”和子领域“GDS 4：数据可视化和展示”中的某些常见问题，Wickham 的工具已被很多人认为是不可或缺的。

In Wickham (2014) Wickham discussed the notion of tidy data. Noting (as I also have, above) the common estimate that 80% of data analysis is spent on the process of cleaning and preparing the data, Wickham develops a systematic way of thinking about "messy" data formats and introduces a set of tools in R that translate them to a universal "tidy" data format. He identifies several messy data formats that are commonly encountered in data analysis and shows how to transform each such format into a tidy format using his tools melt and cast. Once the data are molten, they can be very conveniently operated on using tools from the plyr library, and then the resulting output data can be "cast" into a final form for further use.

Wickham（2014）讨论了数据整理的概念。Wickham 注意到（我在上面也说过）通常的估计是，80% 的数据分析都花在了清理和准备数据上，因此他系统地思考了“凌乱”的数据格式，并在R中引入了一套工具，将它们转换成通用的“整齐”的数据格式。他识别了数据分析中常见的几种混乱的数据格式，并展示了如何使用他的工具 melt 和 cast 将每种格式转换为整齐的格式。一旦数据规整好，就可以非常方便地使用 plyr 库中的工具进行操作，然后将得到的输出数据“cast”为最终形式，以供进一步使用。

The plyr library abstracts certain iteration processes that are very common in data analysis, of the form "apply such-andsuch a function to each element/column/row/slice" of an array. The general idea goes back to Kenneth Iverson's 1962 APL 360 programming language (Iverson 1991), and the reduce operator formalized there; younger readers will have seen the use of derivative ideas in connection with Map/Reduce and Hadoop, which added the ingredient of applying functions on many processors in parallel. Still plyr offers a very fruitful abstraction for users of R, and in particular teaches R users quite a bit about the potential of R's specific way of implementing functions as closures within environments.

plyr 包抽象了数据分析中非常常见的某些操作，形式为“将某函数应用于数组的每个元素/列/行/切片（element/column/row/slice）”。一般的想法可以追溯到 Kenneth Iverson 1962 年的 APL 360 编程语言（Iverson 1991），在那里正式化了 reduce 运算符；年轻的读者会看到与 Map/Reduce 和 Hadoop 相关的衍生思想的使用，这使得能在多处理器上并行跑函数。相应地，plyr 为 R 的用户提供了一个非常有效的抽象，特别是教 R 用户很多关于 R 在环境中实现函数作为闭包的特定方式的潜力。


Wickham has not only developed an R package making tidy data tools available; he has written an article that teaches the R user about the potential of this way of operating. This effort may have more impact on today's practice of data analysis than many highly regarded theoretical statistics articles.

Wickham 不仅开发了一个 R 包，提供了数据整理的工具；他还写了一篇文章，告诉 R 用户这种操作方式的潜力。**与许多备受推崇的理论统计文章相比，这一努力对当今数据分析实践的影响可能更大。**


### 8.4.3. Research Presentation: knitr

### 8.4.3. 研究报告：knitr


As a third vignette, we mention Yihui Xie's work on the knitr package in R. This helps data analysts authoring source documents that blend running R code together with text, and then compiling those documents by running the R code, extracting results from the live computation, and inserting them in a highquality PDF file, HTML web page, or other output product.

作为第三个小插曲，我们提到谢益辉（译者注：统计之都创始人）在 R 中的 knitr 包的工作。这有助于数据分析师将可运行的 R 代码与文本混合在源文档，然后通过运行 R 代码编译这些文档，从实时计算中提取结果，并将其插入高质量的 PDF 文件、HTML 网页或其他输出格式。


In effect, the entire workflow of a data analysis is intertwined with the interpretation of the results, saving a huge amount of error-prone manual cut-and-paste moving computational outputs and their place in the document.

这样的好处是，数据分析的整个工作流与结果的解释交织在一起，从而节省了通过大量容易出错的手动复制、粘贴、移动来处理计算输出及其在文档中的位置。

Since data analysis typically involves presentation of conclusions, there is no doubt that data science activities, in the larger sense of GDS, include preparation of reports and presentations. Research that improves those reports and presentations in some fundamental way is certainly contributing to GDS. In this case, we can view it as part of "GDS3: Computing with Data," because one is capturing the workflow of an analysis. As we show later, it also enables important research in "GDS6: Science about Data Science."

由于数据分析通常涉及结论的展示，毫无疑问，从广义数据科学（GDS）的更宏观视角来说，数据科学活动包括报告和展示。以某种基本方式改进这些报告和展示的研究，毫无疑问是对GDS的贡献。在这种情况下，我们可以将其视为“GDS3：基于数据的计算”的一部分，因为我们正在追踪分析的工作流。正如我们稍后展示的，它还促成了“GDS6：关于数据科学的科学”中的重要研究。



## 8.5. Discussion

## 8.5. 讨论


One can multiply the above examples, making GDS research ever more concrete. Two quick hits:

人们可以列举上述例子，使广义数据科学（GDS）研究更加具体。两个简要例子：


- For subfield "GDS 4: Data Visualization and Presentation," one can mention several exemplary research contributions: Bill Cleveland's work on statistical graphics (Cleveland et al. 1985; Cleveland 2013), along with Leland Wilkinson's (Wilkinson 2006) and Hadley Wickham's Wickham (2011) books on the Grammar of Graphics.

- 对于子领域“GDS 4:数据可视化和展示”，可以提到几个典型的研究贡献：Bill Cleveland 在统计图形方面的工作（Cleveland 等，1985；Cleveland 2013），以及 Leland Wilkinson（2006）和 Hadley Wickham（2011）关于图形语法的著作。


- For subfield "GDS 1: Data Exploration and Presentation," there is of course the original research from long ago of John Tukey on EDA (Tukey 1977); more recently Cook and Swayne's work on Dynamic graphics (Cook and Swayne 2007).

- 对于子领域“GDS 1：数据探索和展示”，当然包括 John Tukey（1977）关于探索性数据分析（EDA）的原始研究；最近还有 Cook 和 Swayne 在动态图形方面的工作（Cook and Swayne 2007）。

Our main points about all the above-mentioned research:

我们对上述所有研究的主要观点是：


(a) it is not traditional research in the sense of mathematical statistics or even machine learning;

(b) it has proven to be very impactful on practicing data scientists;

(c) lots more such research can and should be done.

(a) 它不是数理统计甚至机器学习意义上的传统研究；

(b) 事实证明，它对实践数据科学家非常有影响；

(c) 可以而且应该做更多这样的研究。

Without a classification like GDS, it would be hard to know where to "put it all" or whether a given data science program is adequately furnished for scholar/researchers across the full spectrum of the field.

如果没有像广义数据科学（GDS）这样的分类，就很难知道“把它放在哪里”，也很难知道给定的数据科学项目是否为整个领域的学者/研究人员提供了足够的加持。

# 9. Science About Data Science

# 9. 关于数据科学的科学


A broad collection of technical activities is not a science; it could simply be a trade such as cooking or a technical field such as geotechnical engineering. To be entitled to use the word "science," we must have a continually evolving, evidencebased approach. "GDS6: Science about Data Science" posits such an approach; we briefly review some work showing that we can really have evidence-based data analysis. We also in each instance point to the essential role of information technology skills, the extent to which the work "looks like data science," and the professional background of the researchers involved.

广泛的技术活动不一定是一门科学；它可能只是一个行业，比如烹饪，或者是一个技术领域，比如岩土工程。为了有权使用“科学”一词，我们必须有一个不断发展的、基于证据的方法。“GDS6：关于数据科学的科学”提出了这样一种方法；我们简要回顾了一些工作，表明我们确实可以进行基于证据的数据分析。我们还在每个例子中都指出了信息技术技能的重要作用，这项工作“看起来像数据科学”的程度，以及相关研究人员的专业背景。


## 9.1. Science-Wide Meta-Analysis

## 9.1. 科学范围的荟萃分析（Science-Wide Meta-Analysis）


In FoDA, $^{50}$ Tukey proposed that statisticians should study how people analyze data today.

在“数据科学之未来”（FoDA）中 $^{50}$，Tukey 建议统计学家应该研究当今人们如何分析数据。


By formalizing the notion of multiple comparisons (Tukey 1994), Tukey put in play the idea that a whole body of analysis conclusions can be evaluated statistically.

通过将多重比较的概念正规化（Tukey 1994），Tukey 提出了一个观点，即可以对整个分析结论进行统计评估。


Combining such ideas leads soon enough to meta-analysis, where we study all the data analyses being published on a given topic. $^{51}$ In 1953, the introduction to Tukey's article (Tukey 1994) considered a very small scale example with six different comparisons under study. Today, more than one million scientific articles are published annually, just in clinical medical research, and there are many repeat studies of the same intervention. There's plenty of data analysis out there to meta-study!

结合这些想法很快就可以创造出荟萃分析，即我们研究在给定主题上发布的所有数据分析 $^{51}$。1953年，Tukey 文章（Tukey 1994）的导言考虑了一个很小的例子，其中有六个不同的比较正在研究中。如今，仅在临床医学研究中，每年就有超过100万篇科学文章发表，并且有许多基于相同干预因素的重复研究。有大量数据分析可用于荟萃研究！


In the last 10 years, the scope of such meta-analysis has advanced spectacularly; we now perceive entire scientific literature as a body of text to be harvested, processed, and "scraped" clean of its embedded numerical data. Those data are analyzed for clues about meta-problems in the way all of science is analyzing data. I can cite a few articles by John Ioannidis and coauthors (Ioannidis 2005, 2008; Pan et al. 2005; Button et al. 2013) and for statisticians the article "An estimate of the science-wise false discovery rate ..." Jager and Leek (2014) together with all its ensuing discussion

在过去10年中，这种荟萃分析的范围取得了惊人的发展；现在，我们将整个科学文献视为一个文本体，需要对其进行收集、处理，并“抽取”嵌入其中的数字数据。这些数据被分析以寻找有关元问题（meta-problems）的线索，就像所有科学都在分析数据一样。我可以引用 John Ioannidis 及其合著者的几篇文章（Ioannidis, 2005, 2008；Pan等人, 2005; Button等人, 2013），以及统计学家的文章“科学上错误发现率的估计”（An estimate of the science-wise false discovery rate ...），Jager 和 Leek（2014）及其所有后续讨论。

In particular, meta-analysts have learned that a dismaying fraction of the conclusions in the scientific literature are simply incorrect (i.e., far more than 5%) and that most published effects sizes are overstated, that many results are not reproducible, and so on.

特别地，荟萃分析师已经了解到，科学文献中的一部分结论根本不正确，大多数已发表的效果被夸大，许多结果不可重复，诸如此类。


Our government spends tens of billions of dollars every year to produce more than one million scientific articles. It approaches cosmic importance, to learn whether science as actually practiced is succeeding or even how science as a whole can improve.

我们的政府每年花费数百亿美元生产了100多万篇科学文章。了解实际实践的科学是否成功，甚至整个科学如何改进——这是一个极其重要的问题。


Much of this research occurred in the broader applied statistics community, for example, taking place in schools of education, medicine, public health, and so on. Much of the so far already staggering achievement depends on "text processing," namely, scraping data from abstracts posted in online databases, or stripping it out of PDF files and so on. In the process we build up "big data," for example, Ioannidis and collaborators recently harvested all the $p$-values embedded in all Pubmed abstracts (Chavalarias et al. 2016). Participants in this field are doing data science, and their goal is to answer fundamental questions about the scientific method as practiced today.

这些研究大多发生在更广泛的应用统计界，例如，在教育、医学、公共卫生等学院。到目前为止，已经取得的惊人成就很大程度上取决于“文本处理”，即从发布在在线数据库中的摘要中提取数据，或从PDF文件中提取数据等等。在这个过程中，我们建立了“大数据”，例如，Ioannidis 和合作者最近收获了所有 Pubmed 摘要中包含的所有 $p$-值（Chavalarias 等，2016）。这一领域的参与者正在从事数据科学，他们的目标是回答有关当今实践的科学方法的基本问题。


> [50] "I once suggested, in discussion at a statistical meeting, that it might be well if statisticians looked to see how data was actually analyzed by many sorts of people. A very eminent and senior statistician rose at once to say that this was a novel idea, that it might have merit, but that young statisticians should be careful not to indulge in it too much since it might distort their ideas," Tukey, FoDA

> [50] “在一次统计会议上的讨论中，我曾建议，如果统计学家们看看各行各业的人是如何分析数据的，那可能会很好。一位非常著名的资深统计学家立刻站起来说，这是一个新颖的想法，它可能有价值，但年轻的统计学家应该小心不要沉迷其中。因为这可能会扭曲他们的想法。” Tukey，“数据科学之未来”（FoDA）。

> [51] The practice of meta-analysis goes back at least to Karl Pearson. I am not trying to suggest that Tukey originated meta-analysis; only reminding the reader of John's work for the centennial occasion. 

> [51] 荟萃分析的实践至少可以追溯到 Karl Pearson。我并不是想暗示 Tukey 是荟萃分析的起源；只是在百年纪念中想指出 John 的工作。

## 9.2. Cross-Study Analysis

## 9.2. 交叉研究分析

Because medical research is so extensive, and the stakes are so high, there often are multiple studies of the same basic clinical intervention, each analyzed by some specific team in that specific team's manner. Different teams produce different predictions of patient outcome and different claims of performance of their predictors. Which if any of the predictors actually work?

因为医学研究如此广泛，风险如此之高，通常有多项基于相同临床干预的研究，每项研究都由某个特定团队以其特定的方式进行分析。不同的团队对患者结果产生不同的预测，对其预测者的表现也有不同的说法。究竟有哪些预测能真的起作用？


Giovanni Parmigiani at Harvard School of Public Health explained to me a cross-study validation exercise (Bernau et al. 2014), in which he and co-authors considered an ensemble of studies that develop methods for predicting survival of ovarian cancer from gene expression measurements. From 23 studies of ovarian cancer with publicly available data, they created a combined curated dataset included gene expression data and survival data, involving 10 datasets with 1251 patients in all. From 101 candidate papers in the literature they identified 14 different prognostic models for predicting patient outcome. These were formulas for predicting survival from observed gene expression; the formulas had been fit to individual study datasets by their original analysts, and in some cases validated against fresh datasets collected by other studies.

哈佛大学公共卫生学院的 Giovanni Parmigiani 向我解释了一项交叉研究验证练习（Bernau 等，2014年）。他和共同作者考虑了一系列研究，这些研究开发了通过基因表达测量预测卵巢癌生存率的方法。根据23项卵巢癌研究和公开数据，他们创建了一个包含基因表达数据和生存数据的组合数据集，涉及10个数据集，共有1251名患者。从文献中的101篇候选论文中，他们确定了14种不同的预测患者预后的预测模型。这套模型用于根据观察到的基因表达预测存活率；而且已经被他们的原始分析人员应用于各个研究数据集，并且在某些情况下与其他研究收集的新数据集进行了验证。


Parmigiani and colleagues considered the following crossstudy validation procedure: fit each of the 14 models to one of the 10 datasets, and then validate it on every one of the remaining datasets, measure the concordance of predicted risk with actual death order, producing a 14 by 10 matrix allowing to study the individual models across datasets, and also allowing to study individual datasets across models.

Parmigiani 及其同事考虑了以下交叉研究验证程序：将14个模型中的每一个拟合到10个数据集中的一个，然后在剩余的数据集中对其进行验证，测量预测风险与实际死亡顺序的一致性，生成一个14乘以10的矩阵，以便跨数据集研究各个模型，并且还允许跨模型研究单个数据集。


Surprising cross-study conclusions were reached. First off, one team's model was clearly determined to be better than all the others, even though in the initial publication it reported the middlemost validation performance. Second, one dataset was clearly "harder" to predict well than were the others, in the sense of initially reported misclassification rate, but it is precisely this dataset which yielded the overall best model.

令人惊讶的交叉研究结论出现了。首先，一个团队的模型被明确地确定为优于所有其他团队，尽管在最初的发布中，它报告了比较中间的验证性能。其次，就最初报告的误分类率而言，有一个数据集显然比其他数据集“更难”预测。但正是这个数据集产生了整体最佳模型。


Table 2. OMOP datasets. Numerical figures give the number of persons or objects. Thus, 46.5M in the upper left means 46.5 million persons; while 110M in the lower right means 110 million procedures.

表2. OMOP 数据集。数字表示人或物的数量。因此，左上角的4650万人意味着4650万人；而右下方的110M表示1.1亿个程序（procedures）。


\begin{tabular}{lcccccc}
\hline Acronym & Pop. size & Source & Timerange & Drugs & Cond & Proc \\
\hline CCAE & $46.5 \mathrm{M}$ & Private & $2003-2009$ & $1.03 \mathrm{~B}$ & $1.26 \mathrm{~B}$ & $1.98 \mathrm{~B}$ \\
MDCD & $20.8$ & Medicaid & $2002-2007$ & $360 \mathrm{M}$ & $552 \mathrm{M}$ & $558 \mathrm{M}$ \\
MDCR & $4.6 \mathrm{M}$ & Medicare & $2003-2009$ & $401 \mathrm{M}$ & $405 \mathrm{M}$ & $478 \mathrm{M}$ \\
MSLR & $1.2 \mathrm{M}$ & Lab & $2003-2007$ & $38 \mathrm{M}$ & $50 \mathrm{M}$ & $69 \mathrm{M}$ \\
GE & $11.2 \mathrm{M}$ & EHR & $1996-2008$ & $182 \mathrm{M}$ & $66 \mathrm{M}$ & $110 \mathrm{M}$ \\
\hline
\end{tabular}



This meta study demonstrates that by both accessing all previous data from a group of studies and trying all previous modeling approaches on all datasets, one can obtain both a better result and a fuller understanding of the problems and shortcomings of actual data analyses.

这项荟萃研究表明，通过访问一组研究中的所有先前数据，并在所有数据集上尝试所有先前的建模方法，可以获得更好的结果，并更充分地了解实际数据分析的问题和缺点。

The effort involved in conducting this study is breathtaking. The authors delved deeply into the details of over 100 scientific papers and understood fully how the data cleaning and data fitting was done in each case. All the underlying data were accessed and reprocessed into a new common curated format, and all the steps of the data fitting were reconstructed algorithmically, so they could be applied to other datasets. Again information technology plays a key role; much of the programming for this project was carried out in R. Parmigiani and collaborators are biostatisticians heavily involved in the development of R packages.

进行这项研究所付出的努力是惊人的。作者深入研究了100多篇科学论文的细节，并充分了解了在每种情况下如何进行数据清理和数据拟合。所有基础数据都被访问并重新处理为新的通用规划格式，数据拟合的所有步骤都经过算法重建，因此可以应用于其他数据集。信息技术再次发挥了关键作用；该项目的大部分编程都是在 R 中完成的。Parmigiani 和合作者是生物统计学家，大量参与 R 软件包的开发。


## 9.3. Cross-Workflow Analysis

## 9.3. 跨工作流分析


A crucial hidden component of variability in science is the analysis workflow. Different studies of the same intervention may follow different workflows, which may cause the studies to get different conclusions. Carp (2012) studied analysis workflows in 241 fMRI studies. He found nearly as many unique workflows as studies! In other words researchers are making up a new workflow for pretty much every fMRI study.

科学中可变性的一个关键隐藏部分是分析工作流。同一干预的不同研究可能遵循不同的工作流，这可能导致研究得出不同的结论。Carp（2012）研究了241项 fMRI 研究的分析工作流程。他发现了几乎与研究一样多的工作流模式！换句话说，研究人员正在为几乎每项 fMRI 研究制定一个新的工作流。


David Madigan and collaborators (Ryan et al. 2012; Madigan et al. 2014) studied the effect of analysis flexibility on effect sizes in observational studies; their collaboration will be hereafter called OMOP. As motivation, the OMOP authors point out that in the clinical research literature there are studies of the same dataset, and the same intervention and outcome, but with different analysis workflow, and the published conclusions about the risk of the intervention are reversed. Madigan gives the explicit example of exposure to Pioglitazone and bladder cancer, where published articles in BJMP and BMJ reached opposite conclusions on the very same underlying database!

David Madigan及其合作者（Ryan 等，2012；Madigan 等，2014）研究了观察研究中分析灵活性对效应大小的影响；他们的合作将在下文中称为 OMOP。受此启发，OMOP 作者指出，在临床研究文献中，有对相同数据集、相同干预和结果的研究，但由于分析工作流不同，关于干预风险的结论是完全相反的。Madigan 以吡格列酮与膀胱癌关系为例，这一问题在 BJMP 和 BMJ 上发表的文章在相同的基础数据集上得出了相反的结论！


The OMOP authors obtained five large observational datasets, covering together a total of more than 200 Million Patient-years (see Table 2).

OMOP 作者汇总了五个大型观测数据集，总共涵盖了超过2亿患者-年（参见表2）。

The OMOP group considered four different outcomes, coded "Acute Kidney Injury," "Acute Liver Injury," "Acute Myocardial Infarction," "GI Bleed." They considered a wide range of possible interventions for each outcome measure, for example, whether patients taking drug X later suffered outcome Y. Below, "Acute Liver Injury" stands for the association "Exposure to X and Acute Liver Injury."

OMOP 组考虑了四种不同的结果，编码为“急性肾损伤”、“急性肝损伤”、“急性心肌梗死”和“胃肠道出血”。他们考虑了每种结果的大量可能干预措施，例如，服用药物 X 的患者后来是否会出现结果 Y。下面，“急性肝损伤”代表“暴露于 X 和急性肝损伤”的关联。

For each target outcome, the researchers identified a collection of known positive and negative controls, interventions X for which the ground truth of statements like "Exposure to X is associated with Acute Liver Injury" is considered known. Using such controls, they could quantify an inference procedure's ability to correctly spot associations using the measure of area under the operating curve (AUC).

对于每个目标结果，研究人员确定了一组已知的阳性和阴性对照、干预措施 X，其中“暴露于 X 与急性肝损伤相关”等陈述的基本事实被认为是已知的。使用这样的对照，他们可以使用 AUC（area under the operating curve）来量化一个推断程序正确发现关联关系的能力。

OMOP considered seven different procedures for inference from observational studies, labeled "CC," "CM," "DP," "ICTPD," "LGPS," "OS," and "SCCS." For example, "CC" stands for casecontrol studies, while SCCS stands for self-controlled case series. In each case, the inference procedure can be fully automated.

OMOP 考虑了七种不同的观察性研究推断程序，分别为“CC”、“CM”、“DP”、“ICTPD”、“LGPS”、“OS” 和 “SCCS”。例如，“CC”代表病例对照研究，而“SCCS”代表自我控制病例系列。在每种情况下，推理过程都可以完全自动化。

In their study, OMOP considered, for each database, for each possible outcome, every one of the seven types of observational study method (CC, .., SCCS).

在他们的研究中，OMOP 针对每个数据集、每个可能的结果，考虑了七种观察性研究方法（CC，…，SCCS）中的每一种。


The OMOP report concludes that the three so-called selfcontrolled methods outperform the other methods overall, with SCCS being especially good overall. So their study reveals quite a bit about the effectiveness of various inference procedures, offering an idea what improved inference looks like and how accurate it might be.

OMOP 报告得出结论，三种所谓的自我控制方法总体上优于其他方法，SCCS 整体表现最为优异。因此，他们的研究揭示了各种推断模式的有效性，提供了一个更好的推断模式图景以及它的潜在准确率的估计。


This work represents a massive endeavor by OMOP: to curate data, program inference algorithms in a unified way, and apply them across a series of underlying situations. Dealing with big data was an essential part of the project; but the driving motivation was to understand that the scientific literature contains a source of variation-methodological variation-whose influence on future inference in this field might be understood, capped, or even reduced. The participants were statisticians and biostatisticians.

这项工作呈现了 OMOP 做出的巨大努力：以统一的方式管理数据、程序推断算法，并将其应用于一系列潜在情况。处理大数据是该项目的重要组成部分；但驱动动机是理解科学文献差异的来源，即方法学差异，从此，该领域未来推断的差异可以被理解、限制甚至减少。这项工作的参与者都是统计学家和生物统计学家。


## 9.4. Summary

## 9.4. 总结


There seem to be significant flaws in the validity of the scientific literature (Ioannidis 2007; Sullivan 2007; Prinz, Schlange, and Asadullah 2011; Open Science Collaboration et al. 2015). The last century has seen the development of a large collection of statistical methodology, and a vast enterprise using that methodology to support scientific publication. There is a very large community of expert and not-so-expert users of methodology. We do not know very much about how that body of methodology is being used and we also do not know very much about the quality of results being achieved.

科学文献的有效性似乎存在重大缺陷（Ioannidis 2007；Sullivan 2007；Prinz、Schlange 和 Asadollah 2011；Open Science Collaboration 等，2015）。在过去的一个世纪里，大量统计方法论得到了发展，很多行业利用这些方法论来发表科研成果。专业群体用户数量庞大，但他们不算是方法论专家。我们不太了解这套方法是如何被使用的，我们也不太了解所取得的成果的质量如何。

Data scientists should not blindly churn out methodology without showing concern for results being achieved in practice. Studies we have classed as "GDS6: Science About Data Science" help us understand how data analysis as actually practiced is impacting "all of science."

数据科学家不应该盲目地炮制方法论，而不关心实践中取得的成果。我们归类为“GDS6：关于数据科学的科学”的研究有助于我们理解实际实践中的数据分析是如何影响“所有科学”的。


Information technology skills are certainly at a premium in the research we have just covered. However, scientific understanding and statistical insight are firmly in the driver's seat.

在我们刚刚介绍的研究中，信息技术技能当然非常重要。然而，科学理解和统计洞察力更是应牢牢把控在驾驶席上。

# 10. The Next 50 Years of Data Science

# 10. 未来50年的数据科学


Where will data science be in 2065 ? The evidence presented so far contains significant clues, which we now draw together.

2065年数据科学将往何处去？上述讨论给我们提供了诸多线索，我们现在将这些线索汇总起来。


## 10.1. Open Science Takes Over

## 10.1. 开放科学来主导

In principle, the purpose of scientific publication is to enable reproducibility of research findings. For centuries, computational results and data analyses have been referred to in scientific publication, but typically only have given readers a hint of the full complexity of the data analysis being described. As computations have become more ambitious, the gap between what readers know about what authors did has become immense. Twenty years ago, Jon Buckheit and I summarized lessons we had learned from Stanford's Jon Claerbout as follows:

原则上，科学出版物的目的是使研究结果具有可重复性。几个世纪以来，科学出版物中大量呈现计算结果和数据分析，但通常只会给读者大致描述其数据分析的复杂性。随着计算变得越来越庞大复杂，研究者的工作会愈发难以理解。20年前，Jon Buckheit和我总结了我们从斯坦福大学的Jon Claerbout那里学到的经验：

> An article about computational science in a scientific publication is not the scholarship itself, it is merely advertising of the scholarship. The actual scholarship is the complete software development environment and the complete set of instructions which generated the figures.

> **科学出版物中，关于计算科学的文章并不是学术成果本身，它们只是学术的广告而已。真正的学术成果，是孕育和诞生数值结果的——完整的软件开发环境、代码和操作指南**。


To meet the original goal of scientific publication, one should share the underlying code and data. Moreover there are benefits to authors. Working from the beginning with a plan for sharing code and data leads to higher quality work, and ensures that authors can access their own former work, and those of their coauthors, students and postdocs (Donoho et al. 2009). Over the years, such practices have become better understood (Stodden 2012; Stodden, Guo, and Ma 2013) and have grown (Freire, Bonnet, and Shasha 2012; Stodden, Leisch, and Peng 2014), though they are still far from universal today. In absolute terms the amount of essentially nonreproducible research is far larger than ever before (Stodden, Guo, and Ma 2013).

为了实现科学出版物的最初目标，人们应该共享基础代码和数据。此外，对作者也有好处。从一开始就制定共享代码和数据的计划，这将带来更高质量的工作，并确保作者能够随时追溯自己以前的工作，以及他们的合著者、学生和博士后的工作（Donoho等人，2009）。多年来，这种做法已经得到了更广泛的认同（Stodden 2012；Stodden、Guo和Ma 2013），并有所发展（Freire、Bonnet和Shasha 2012；Storden、Leisch和Peng 2014），尽管它们在今天还远远没有普及。从绝对值来看，基本上不可重复的研究数量远远超过以往（Stodden、Guo和Ma 2013）。


Reproducible computation is finally being recognized today by many scientific leaders as a central requirement for valid scientific publication. The 2015 annual message from Ralph Cicerone, President of the U.S. National Academy of Sciences, stresses this theme; while funding agencies (Collins and Tabak 2014) and several key journals (Peng 2009; McNutt 2014; Heroux 2015), have developed a series of reproducibility initiatives.

今天，可重复计算终于被许多科学领袖视为有效科学出版物的核心要求。美国国家科学院院长Ralph Cicerone 2015年的年度致辞强调了这一主题；而资助机构（Collins和Tabak，2014）和一些关键期刊（Peng，2009；McNutt，2014；Heroux，2015）已经制定了一系列可重复性计划。

To work reproducibly in today's computational environment, one constructs automated workflows that generate all the computations and all the analyses in a project. As a corollary, one can then easily and naturally refine and improve earlier work continuously.

为了在当今的计算环境中实现可重复工作，人们构建了自动化工作流，生成项目中的所有计算和所有分析。相应地，人们可以轻松自然地不断完善和改进早期的工作。


Computational results must be integrated into final publications. Traditional methods-running jobs interactively by hand, reformatting data by hand, looking up computational results, and copying and pasting into documents-are now understood to be irresponsible. Recently, several interesting frameworks combining embedded computational scripting with document authoring have been developed. By working within the discipline such systems impose, it becomes very easy to document the full computation leading to a specific result in a specific article. Yihui Xie's work with the knitr package-mentioned earlier-is one such example. $^{53}$

计算结果必须整合到最终出版物中。传统的手工交互运行作业、手工重新格式化数据、查找计算结果以及复制和粘贴到文档中的方法现在被认为是不负责任的。最近，已经开发了几个有趣的框架，将嵌入式计算脚本与文档创作结合起来 $^{52}$。通过在这样的系统所施加的规则内工作，可以使我们轻易地记录特定文章中特定结果的完整计算过程。谢益辉之前提到的knitr就是一个很好的例子 $^{53}$。

Reproducibility of computational experiments is just as important to industrial data science as it is to scientific publication. It enables a disciplined approach to proposing and evaluating potential system improvements and an easy transition of validated improvements into production use. 

计算实验的再现性对产业数据科学和科学出版物同样重要。它能够提出和评估潜在系统改进的严格方法，并将经过验证的改进轻松过渡到生产使用。

Reproducible computation fits into our classification both at "GDS 4: Presentation of Data" and in "GDS 6: Science about Data Science." In particular, teaching students to work reproducibly enables easier and deeper evaluation of their work; having them reproduce parts of analyses by others allows them to learn skills like exploratory data analysis that are commonly practiced but not yet systematically taught; and training them to work reproducibly will make their post-graduation work more reliable.

可重复计算符合前面提到的“GDS 4：数据展示”和“GDS 6：数据科学”。特别是，教学生可再重复工作可以更容易、更深入地评估他们的工作；让他们复制他人的分析方法及代码，可以让他们学习探索性数据分析等技能，这些技能常常被直接实践，但却并未系统地教授；训练他们复现工作将使他们毕业后的工作更加可靠。


Science funding agencies have for a long time included in their funding policies a notional requirement that investigators make code and data available to others. However, there never has been enforcement, and there was always the excuse that there was no standard way to share code and data. Today there are many ongoing development efforts to develop standard tools enabling reproducibility (Freire, Bonnet, and Shasha 2012; Stodden, Leisch, and Peng 2014; Stodden and Miguez 2014); some are part of high profile projects from the Moore and Simons foundations. We can confidently predict that in coming years reproducibility will become widely practiced.

一直以来，科学资助机构在其资助政策中包含了一个“形式主义”的要求，即研究人员应公开代码和数据。然而，这从来没有强制执行过，而且总能以没有标准的方法共享代码数据为借口。如今，有许多正在进行的开发工作在开发能够实现可重复性的标准工具（Freire、Bonnet和Shasha 2012；Stodden、Leisch和Peng 2014；Stoddeen和Miguez 2014）；其中一些是摩尔和西蒙斯基金会知名项目的一部分。我们可以自信地预测，在未来几年，可重复性将得到广泛应用。

> [52] Such efforts trace back to Donald Knuth's Literate Programming project. While literate programming-mixing code and documentation-does not seem to have become very popular, a close relative-mixing executable code, data, documentation, and execution outputs in a single document-is just what the doctor ordered for reproducible research in computational science.

> [52] 这些工作可以追溯到 Donald Knuth 的文学化编程(Literate Programming)项目。虽然混合代码和文档的文学化编程似乎并不是很流行，但将可执行代码、数据、文档和执行输出紧密结合在一个文档中，这正是计算科学中的可重复研究所要求的。

> [53] Professor Martin Helm reminds me to mention other examples; he points to the SAS system's StatRep package, saying "SAS Institute twice a year produces tens of thousands pages of SAS documentation from LATEX-files with markups that run SAS and include programs as well as output as well as statistical advice (text). When we tested it, it was better and more stable than knitr. This could have changed in the meantime as knitr evolves but SAS is not so eager to open up and publish improvements." 

> [53] Martin Helm 教授提醒我还有其他不错的例子；比如SAS系统的StatRep包，他表示“SAS研究所每年两次从LATEX文件中生成数万页SAS文档，其中包含运行SAS的标记，包括程序、输出以及统计建议（文本）。当我们测试它时，它比knitr更好、更稳定。随着knitr的发展，这一点可能会发生变化，但SAS并不急于开放并发布改进。" 

## 10.2. Science as Data

## 10.2. 作为数据的科学

Conceptually attached to a scientific publication is a great deal of numerical information-for example, the $p$-values reported within it (Chavalarias et al. 2016). Such information ought to be studied as data. Today, obtaining that data is problematic; it might involve reading of individual articles and manual extraction and compilation, or web scraping and data cleaning. Both strategies are error prone and time consuming.

科学出版物包含大量数字信息，例如，其中报告的p值（Chavalarias等人，2016）。此类信息应作为数据进行研究。今天，获取这些数据并不容易；它需要阅读每篇文章、手动提取和编译，或者网络抓取和数据清理。这两种策略都容易出错且耗时。


With the widespread adoption of open science over the next 50 years, a new horizon becomes visible. Individual computational results reported in an article, and the code and the data underlying those results, will be universally citable and programmatically retrievable. Matan Gavish and I wrote some articles (Gavish and Donoho 2011; Gavish 2012), which proposed a way to open that new world and which then explored the future of science in such a world.

随着开放科学在未来50年中的广泛应用，一个新的模式变得清晰可见。一篇文章报告中的单个计算结果，以及这些结果的代码和数据，将是标准的，通用的，可引用和可编程检索的。我和Matan Gavish写了一些文章（Gavish 和 Donoho，2011年；Gavish，2012年），提出了一种打开新世界的方法，然后探讨了这样一个世界中科学的未来。

Those articles defined the notion of verifiable computational result (VCR), a computational result, and metadata about the result, immutably associated with a URL, and hence permanently programmatically citable and retrievable. Combining cloud computing and cloud storage, Gavish developed server frameworks that implemented the VCR notion, recording each key result permanently on the server and returning the citing URL. He also provided client-side libraries (e.g., for Matlab) that allowed creation of VCRs and returned the associated link, and that provided programmatic access to the data referenced by the link. On the document creation side, he provided macro packages that embedded such links into published TEXdocuments. As a result, one could easily write documents in which every numerical result computed for an article was publicly citable and inspectable-not only the numerical value, but the underlying computation script was viewable and could be studied.

这些文章定义了可验证计算结果（VCR）的概念，即计算结果，以及关于结果的元数据，这些元数据与URL直接绑定，因此可以通过编程永久引用和检索。结合云计算和云存储，Gavish开发了实现VCR概念的服务器框架，将每个关键结果永久记录在服务器上并返回引用URL。他还提供了客户端库（例如Matlab），允许创建VCR并返回相关链接，并提供对链接引用的数据的编程访问。在文档创建方面，他提供了宏包，将这些链接嵌入到已发布的TEX文档中。因此，人们可以轻松编写文档，一篇文章中计算的每个数值结果都可以公开引用和检查，不仅是数值，所有基础计算脚本也可以开放浏览。


In a world where each numerical result in a scientific publication is citable and retrievable, along with the underlying algorithm that produced it, current approaches to meta-analysis are much easier to carry out. One can easily extract all the $p$-values from a VCR-compliant article, or extract all the data points in a graph inside it, in a universal and rigorously verifiable way. In this future world, the practice of meta-analysis of the kind we spoke about in Section $9.1$ will of course expand. But many new scientific opportunities arise. We mention two examples:

如果我们科学出版物中的每一个数字结果，每一个基本算法都是可引用和可检索的，当前的荟萃分析方法自然会更容易执行。人们可以轻松地从VCR兼容的文章中提取所有p值，或者以通用且严格可验证的方式提取其中图表中的所有数据点。在这样的世界中，我们在9.1节中提到的那种荟萃分析的实践会得到扩展，而且会出现许多新的科学机会。我们举两个例子：

- Cross-Study Control Sharing. In this new world, one can extract control data from previous studies (Wandell et al. 2015). New opportunities include: (a) having massively larger control sets in future studies; (b) quantifying the impact of specific control groups and their differences on individual study conclusions; and (c) extensive "real world" calibration exercises where both groups are actually control groups.

- **交叉研究控制共享**。在这样的世界中，人们可以从以前的研究中提取控制数据（Wandell等人，2015）。新的机会包括：(a)在未来的研究中拥有更大的对照组；(b) 量化特定对照组及其差异对个体研究结论的影响；(c) 广泛的“真实世界”校准练习，其中两组实际上都是对照组。

- Cross-Study Comparisons. The cross-study comparisons of Sections $9.2$ and 9.3, required massive efforts to manually rebuild analyses in previous studies by other authors, and then manually curate their data. When studies are computationally reproducible and share code and data, it will be natural to apply the algorithm from paper A on the data from paper B, and thereby understand how different workflows and different datasets cause variations in conclusions. One expects that this will become the dominant trend in algorithmic research.

- **交叉研究比较**。第9.2节和第9.3节的交叉研究比较需要研究人员花费大量的精力来手动重建其他作者以前研究中的分析，然后手动整理他们的数据。当研究在计算上可重复并共享代码和数据时，将论文A的算法应用于论文B的数据将是很简单的，从而更高效地理解不同的工作流和不同的数据集是如何导致结论差异的。我们认为这将成为算法研究的主导趋势。


Additional possibilities are discussed in Gavish (2012).

Gavish（2012）讨论了其他可能性。

## 10.3. Scientific Data Analysis, Tested Empirically

## 10.3. 科学数据分析、实证检验


As science itself becomes increasingly mineable for data and algorithms, the approaches of cross-study data sharing and workflow sharing discussed above in Sections $9.2$ and $9.3$ will spread widely. In the next 50 years, ample data will be available to measure the performance of algorithms across a whole ensemble of situations. This is a game changer for statistical methodology. Instead of deriving optimal procedures under idealized assumptions within mathematical models, we will rigorously measure performance by empirical methods, based on the entire scientific literature or relevant subsets of it.


随着科学本身对数据和算法的挖掘变得越来越容易，上文第9.2节和第9.3节讨论的交叉研究数据共享和工作流共享的方法将得到广泛传播。在未来50年，将有足够的数据来衡量算法在所有情况下的性能。统计方法论的游戏规则改变了。我们将基于整个科学文献或其相关子集，通过实证方法严格衡量算法表现，而不是在数学模型中的理想化假设下推导出最佳算法。



Many current judgments about which algorithms are good for which purposes will be overturned. We cite three references about the central topic of classification with a bit of detail.


当前关于哪些算法适合哪些项目的许多判断将被推翻。我们引用了三个关于分类主题的参考文献，并提供了一些细节。


### 10.3.1. Hand et al. (2006)

### 10.3.1. Hand等人（2006）


In Hand et al. (2006), D. J. Hand summarized the state of classifier research in 2006 . He wrote:

在Hand等人（2006）中，D.J.Hand总结了2006年分类方法研究的现状。他写道：


> The situation to date thus appears to be one of very substantial theoretical progress, leading to deep theoretical developments and to increased predictive power in practical applications. While all of these things are true, it is the contention of this paper that the practical impact of the developments has been inflated; that although progress has been made, it may well not be as great as has been suggested. ...

> 因此，迄今为止的情况似乎是一个非常实质性的理论进步，导致了深刻的理论发展和实际应用中预测能力的提高。虽然所有这些都是真的，但本文认为，这些发展的实际影响被夸大了；虽然取得了进展，但很可能没有所暗示的那么大……

>
> The essence of the argument [in this paper] is that the improvements attributed to the more advanced and recent developments are small, and that aspects of real practical problems often render such small differences irrelevant, or even unreal, so that the gains reported on theoretical grounds, or on empirical comparisons from simulated or even real data sets, do not translate into real advantages in practice. That is, progress is far less than it appears. $^{54}$

> [在本文中]论点的本质是，最近的、更先进的发展带来的改进是很小的，而实际问题的各个方面往往使这种小差异变得无关紧要，甚至是不真实的。因此，基于理论基础所获得的结论，或者基于模拟或甚至基于真实数据集的获得的经验，在实践中并不能转化为真正的优势。也就是说，进展远没有看起来的那么快 $^{54}$。


How did Hand support such a bold claim? On the empirical side, he used "a randomly selected sample of 10 datasets" from the literature and considered empirical classification rate. He showed that linear discriminant analysis, which goes back to Fisher (1936), achieved a substantial fraction (90\% or more) of the achievable improvement above a random guessing baseline. The better-performing methods were much more complicated and sophisticated-but the incremental performance above LDA was relatively small.

Hand是如何论证如此大胆的主张的？在实证方面，他使用了文献中“随机选择的10个数据集样本”，并考察了实证分类率。他表明，线性判别分析（LDA，可追溯到Fisher（1936））在随机猜测基线之上取得了很大改进（90%或更多）。性能更好的方法虽然更加复杂和复杂，但在LDA之上的增量提升相对较小。




Hand's theoretical point was precisely isomorphic to a point made by Tukey in FoDA about theoretical optimality: optimization under a narrow theoretical model does not lead to performance improvements in practice.

Hand的理论观点与Tukey在“数据分析之未来”(FoDA)中提出的关于理论最优性的观点完全相同：在狭隘的理论模型下进行优化并不能在实践中提升效果。



> [54] The point made by both Hand and Tukey was that optimality theory, with its great charisma, can fool us. J. R. Pierce made a related point in rejecting the "glamor" of theoretical machine translation.

> [54] Hand和Tukey提出的观点是，最优性理论具有巨大的魅力，同时却可能混淆我们。J. R. Pierce在拒绝理论机器翻译的“魅力”时提出了类似的观点。


### 10.3.2. Donoho and Jin (2008)

### 10.3.2. Donoho和Jin（2008）


To make Hand's point completely concrete, consider work on high-dimensional classification by myself and Jiashun Jin (Donoho and Jin 2008). $^{55}$

为了使Hand的观点具体化，可以看看我和金家顺（Donoho和Jin，2008）在高维分类方面的工作 $^{55}$


Suppose we have data $X_{i, j}$ consisting of $1 \leq i \leq n$ observations on $p$ variables, and binary labels $Y_{i} \in\{+1,-1\}$. We look for a classifier $T(X)$, which presented with an unlabeled feature vector predicts the label $Y$. We suppose there are many features, that is, $p$ is large-ish compared to $n$.

假设我们有数据 $X_{i, j}$，$p$个特征，$n$个观测；二分类变量$Y_{i} \in \{+1,-1\}$。我们寻找一个分类器$T(X)$，它与一个未标记的特征向量一起显示，预测标签$Y$。我们假设有很多特征，即$p$与$n$相比是很大的。


Consider a very unglamorous method: a linear classifier $C(x)=\sum_{j \in J_{+}} x(j)-\sum_{j \in J_{-}} x(j)$, which combines the selected features simply with weights $+1$ or $-1$. This method selects features where the absolute value of the univariate $t$-score exceeds a threshold and uses as the sign of the feature coefficient simply the sign of that feature's $t$-score. The threshold is set by higher criticism. In the published article it was called HC-clip; it is a dead-simple rule, much simpler even than classical Fisher linear discriminant analysis, as it makes no use of the covariance matrix, and does not even allow for coefficients of different sizes. The only subtlety is in the use of higher criticism for choosing the threshold. Otherwise, HC-clip is a throwback to a pre-1936 setting, that is, to before Fisher (1936) showed that one "must" use the covariance matrix in classification. $^{56}$

考虑一个非常简单的方法：一个线性分类器 $C(x)=\sum_{j \in J_{+}} x(j)-\sum_{j \in J_{-}} x(j)$，它将选择的特征简单地与权重$+1$或$-1$组合。该方法选择单变量$t$值的绝对值超过阈值的特征，并仅使用该特征$t$值的正负符号作为特征系数的正负符号。阈值由 **考证(higher criticism)** 统计方法设定。在发表的文章中，它被称为HC-clip；这是一个非常简单的规则，甚至比经典的Fisher线性判别分析要简单得多，因为它不使用协方差矩阵，甚至不考虑不同大小的系数。唯一的微妙之处是在选择阈值时使用了**考证(higher criticism)**。否则，HC-clip是回到1936年之前的设置，即在Fisher(1936)表明“必须”在分类中使用协方差矩阵 $^{56}$。


Dettling (2004) developed a framework for comparing classifiers that were common in Machine Learning based on a standard series of datasets (in the 2-class case, the datasets are called ALL, Leukemia, and Prostate, respectively). He applied these datasets to a range of standard classifier techniques which are popular in the statistical learning community (boosted decision trees, random forests, SVM, KNN, PAM, and DLDA). The machine learning methods that Dettling compared are mostly "glamorous," with high numbers of current citations and vocal adherents.

Detling（2004）开发了一个框架，用于比较机器学习中常见的基于标准数据集系列的分类器（在2类情况下，数据集分别称为全数据、白血病和前列腺）。他将这些数据集应用于统计学习界流行的一系列标准分类器技术（增强决策树、随机森林、SVM、KNN、PAM和DLDA）。Dettling所比较的机器学习方法大多是“迷人的”，当前有大量的引用量和拥护者。

As compared to Hand's work, our work used a preexisting collection of datasets that might seem to be less subject to selection bias, as they were already used in multi-classifier shootouts by machine learners.

与Hand的工作相比，我们的工作使用了一组预先存在的数据集，这些数据集似乎不太受选择偏好的影响，因为机器学习者已经在多分类器射击中使用了这些数据集。

> [55] We did not know about Hand's article at the time, but stumbled to a similar conclusion.

> [55] 我们当时不知道Hand的文章，但得出了类似的结论。


> [56] In the era of desk calculators, a rule that did not require multiplication but only addition and subtraction had some advantages. We extended Dettling's study, by adding our dead-simple clipping rule into the mix. We considered the regret (i.e., the ratio of a method's misclassification error on a given dataset to the best misclassification error among all the methods on that specific dataset). Our simple proposal did just as well on these datasets as any of the other methods; it even has the best worst-case regret. That is, every one of the more glamorous techniques suffers worse maximal regret. Boosting, random forests, and so on are dramatically more complex and have correspondingly higher charisma in the machine learning community. But against a series of preexisting benchmarks developed in the machine learning community, the charismatic methods do not outperform the homeliest of procedures-feature clipping with careful selection of features.

> [56] 在台式计算器时代，不需要乘法，只需要加减运算的规则有一些优势。我们扩展了Dettling的研究，在混合中加入了简单的裁剪规则。我们考虑了后悔率（给定数据集上的方法错误分类错误与该特定数据集上所有方法中最佳错误分类错误的比率）。我们的简单方法在这些数据集上的效果与任何其他方法一样好；它甚至有最低的“最差后悔率”。也就是说，每一种更新潮的技术都会遭受更糟糕的“最差后悔率”。Boosting、随机森林等更加复杂，在机器学习社区中魅力更高。但是，在机器学习社区中开发的一系列预先存在的基准数据上，这些魅力四射的方法并没有胜过最平平无奇的方法——特征选择加上HC-clip。

### 10.3.3. Zhao et al. (2014)

### 10.3.3. Zhao等人（2014）


In a very interesting project (Zhao et al. 2014), Parmigiani and co-authors discussed what they called the Más-o-Menos classifier, a linear classifier where features may only have coefficients that $\pm 1$; this is very much like the just-discussed HC-clip method, and in fact one of their variants included only those features selected by HC-that is, the method of the previous section. We are again back to pre-Fisher-says-use-covariancematrix, pre-1936 setting.

在另一个非常有趣的项目中（Zhao等人，2014），Parmigiani等人讨论了他们所称的Más-o-Menos分类器，这是一种线性分类器，其中特征的系数可能只有±1；这与刚才讨论的HC-clip方法非常相似，事实上，它们的变体之一即包括HC选择的那些特征，也就是上一节的方法。我们再次回到Fisher使用协方差矩阵之前，即1936年之前的设置。

In their study, Zhao et al. compared Más-o-Menos to "sophisticated" classifiers based on penalization (e.g., lasso, ridge).

在他们的研究中，Zhao等人将Más-o-Menos与基于惩罚的“复杂”分类器（如lasso、ridge）进行了比较。


Crucially, the authors took the fundamental step of comparing performance on a universe of datasets used in published clinical medical research. Specifically, they curated a series of datasets from the literature on treatment of bladder, breast, and ovarian cancer, and evaluated prediction performance of each classification method over this universe.

至关重要的是，作者们基于临床医学研究中已发表使用的大量数据集，比较了分类器性能。具体来说，他们从膀胱癌、乳腺癌和卵巢癌治疗的文献中整理了一系列数据集，并评估了每种分类方法在这一领域的预测性能。


> We ... demonstrated in an extensive analysis of real cancer gene expression studies that [Más-o-Menos] can indeed achieve good discrimination performance in realistic settings, even compared to lasso and ridge regression. Our results provide some justification to support its widespread use in practice. We hope our work will help shift the emphasis of ongoing prediction modeling efforts in genomics from the development of complex models to the more important issues of study design, model interpretation, and independent validation.

> 我们……在对真实癌症基因表达研究的广泛分析中证明，[Más-o-Menos]确实可以在现实环境中实现较高的判别准确率，即使与Lasso和岭回归相比也是如此。我们的结果为支持其广泛应用于实践提供了一些理论基础。我们希望我们的工作，将有助于将基因组学中正在进行的预测型建模工作的重点，从复杂模型的开发转移到更重要的研究设计、模型解释和独立验证问题。


The implicit point is again that effort devoted to fancy-seeming methods is misplaced compared to other, more important issues. They continue


隐含的观点是，与其他更重要的问题相比，过度投入于开发看似花哨的方法是错误的。他们同时认为：

> One reason why Más-o-Menos is comparable to more sophisticated methods such as penalized regression may be that we often use a prediction model trained on one set of patients to discriminate between subgroups in an independent sample, usually collected from a slightly different population and processed in a different laboratory. This crossstudy variation is not captured by standard theoretical analyses, so theoretically optimal methods may not perform well in real applications. $^{57}$

> Más-o-Menos与惩罚回归等更复杂的方法更优异的一个原因可能是，我们经常使用在一组患者身上训练的预测模型来判别独立样本分类，但这些样本通常是从有异质性的人群中收集的，并在不同的实验室中处理。这种交叉研究变异没有被标准理论分析捕获，因此理论上的最佳方法在实际应用中可能表现不佳 $^{57}$。


In comparison to the articles (Hand et al. 2006; Donoho and Jin 2008) discussed in previous subsections, this work, by mining the scientific literature, speaks directly to practitioners of classification in a specific field-giving evidence-based guidance about what would have been true for studies to date in that field, had people all known to use the recommended technique.

与前几小节中讨论的文章（Hand等人，2006；Donoho和Jin，2008）相比，这项工作通过挖掘科学文献，直接与特定领域分类问题的从业者对话，用证据告诉他们假如人们知道使用推荐的技术的话，这些领域的研究将会是什么样的。


> [57] Again this vindicates Tukey's point from 1962 that optimization of performance under narrow assumptions is likely a waste of effort, because in practice, the narrow assumptions do not apply to new situations and so the supposed benefits of optimality never appear. 

> [57] 这再次证明了Tukey在1962年提出的观点，即在狭隘的假设条件下优化性能很可能是浪费精力，因为在实践中，狭隘的假设不适用于新的情况，因此最佳化的假设从未带来什么好处。

## 10.4. Data Science in 2065

## 10.4. 2065年的数据科学

In the future, scientific methodology will be validated empirically. Code sharing and data sharing will allow large numbers of datasets and analysis workflows to be derived from studies science-wide. These will be curated into corpora of data and of workflows. Performance of statistical and machine learning methods will thus ultimately rely on the cross-study and crossworkflow approaches we discussed in Sections $9.2$ and $9.3$ Those approaches to quantifying performance will become standards, again because of code and data sharing. Many new common task frameworks will appear; however, the new ones would not always have prediction accuracy for their performance metric. Performance might also involve validity of the conclusions reached, or empirical Type I and II error. Research will move to a meta level, where the question becomes: "if we use such-andsuch a method across all of science, how much will the global science-wide result improve?" measured using an accepted corpus representing science itself.

未来，科学方法论将得到实证验证。代码和数据共享将使所有学科开放大量数据集和分析工作流。这些内容将被整理成数据和工作流的语料库。因此，统计和机器学习方法的性能最终将取决于我们在第9.2和9.3节中讨论的交叉研究和交叉工作流方法。由于代码和数据共享，这些量化性能的方法将成为标准。将出现许多新的共同任务框架；然而，新的任务框架并非总是把预测准确性作为评价指标。效果评估还可能涉及所得出结论的有效性，或经验型一类和二类错误。研究将进入元层次，问题变成：“如果我们在所有科学领域使用这样的方法，全球科学研究的产出将提高多少？”，并使用代表科学本身的公认语料库进行量化。


In 2065 , mathematical derivation and proof will not trump conclusions derived from state-of-the-art empiricism. Echoing Bill Cleveland's point, theory which produces new methodology for use in data analysis or machine learning will be considered valuable, based on its quantifiable benefit in frequently occurring problems, as shown under empirical test. $^{58}$

在2065年，数学推导和证明不会胜过从最先进的经验主义得出的结论。与 Bill Cleveland 的观点相呼应的是，产生用于数据分析或机器学习的新方法论的理论将被认为是有价值的，因为它在经常发生的问题中具有可量化的好处，如实证所示 $^{58}$。


> [58] I am not arguing for a demotion of mathematics. I personally believe that mathematics offers the best way to create true breakthroughs in quantitative work. The empirical method is simply a method to avoid self-deception and appeals to glamor.

> [58] 我并不主张贬低数学。我个人认为，数学是在量化工作中创造真正突破的最佳途径。经验方法只是一种避免自欺欺人和诉诸魅力的方法。

# 11. Conclusion

# 11. 结论

Each proposed notion of data science involves some enlargement of academic statistics and machine learning. The "GDS" variant specifically discussed in this article derives from insights about data analysis and modeling stretching back decades. In this variant, the core motivation for the expansion to data science is intellectual. In the future, there may be great industrial demand for the skills inculcated by GDS; however, the core questions which drive the field are scientific, not industrial.

本文提到的每一个数据科学概念都涉及到学术统计和机器学习的一些扩展。本文中特别讨论的广义数据科学(GDS)变体源自几十年前关于数据分析和建模的见解。在这个变体中，扩展到数据科学的核心动机是才智。未来，行业对GDS灌输的技能可能会有很大的需求；然而，推动这一领域的核心问题是科学问题，而不是工业问题。

GDS proposes that data science is the science of learning from data; it studies the methods involved in the analysis and processing of data and proposes technology to improve methods in an evidence-based manner. The scope and impact of this science will expand enormously in coming decades as scientific data and data about science itself become ubiquitously available.

广义数据科学(GDS)提出数据科学是从数据中学习的科学；它研究数据分析和处理的方法，并提出以循证方式改进方法的技术模式。随着科学数据和关于科学本身的数据变得无处不在，这门科学的范围和影响将在未来几十年中继续深化。



Society already spends tens of billions of dollars yearly on scientific research, and much of that research takes place at universities. GDS inherently works to understand and improve the validity of the conclusions produced by university research, and can play a key role in all campuses where data analysis and modeling are major activities.

社会每年已经在科学研究上花费数百亿美元，其中大部分研究由各个高校负责。广义数据科学(GDS)本质上致力于理解和提高大学研究得出结论的有效性，并且可以在所有以数据分析建模为主的领域中发挥关键作用。



##  Epilogue

## 尾声


The "1.00 version" of this article was dated September 18, 2015. Since its release I received dozens of e-mails from readers with comments. Four sets of comments were particularly valuable, and I'll review them here, together with my response.

本文的“1.00版本”发布日期为2015年9月18日。自它发布以来，我收到了数十封读者的电子邮件评论。其中四组评论尤其有价值，我将在这里引用它们，并给出我的回应。


### Data Science as Branding

### 数据科学的品牌

C. F. Jeff Wu, Professor of Industrial and Systems Engineering at Georgia Tech, wrote to me, pointing out that he had been using the term "data science" in the 1990s. In Section 4.1, we have already mentioned his inaugural Carver lecture at the University of Michigan. Wu proposed in that lecture that statistics rebrand itself.

佐治亚理工大学工业与系统工程教授吴建福写信给我，指出他在20世纪90年代一直使用“数据科学”一词。在第4.1节中，我们已经提到了他在密歇根大学的首次Carver讲座。吴建福在那次演讲中提出，统计学要重塑自己。


We mentioned earlier that the Royal Statistical Society hosted a "debate" in May $2015^{59}$-a video is posted online-asking whether in fact data science is merely such a rebranding, or something larger. Wu's data science proposal was ahead of its time. $^{60}$

我们之前提到，2015年5月，英国皇家统计学会（Royal Statistical Society）举办了一场“辩论”，讨论数据科学实际上只是一种换名，还是革新式的改变，相关视频已公开发布。因此，吴建福的数据科学理念是超前的 $^{60}$。


I have argued here that data science is not a mere rebranding or retitling of statistics. Today's consensus data science includes statistics as a subset.  $^{61}$ I think data science ought to be even larger, for example, to include GDS6: Science about Data Science.

我认为，数据科学不仅仅是统计学的品牌重塑或重新命名。今天的共识是，统计学是数据科学的一个子集。 $^{61}$。我认为数据科学应该更大，例如，包括GDS6：关于数据科学的科学。

> [59] Data Science and Statistics: Different Worlds? Participants: Zoubin Ghahramani (Professor of Machine Learning, University of Cambridge), Chris Wiggins (Chief Data Scientist, New York Times), David Hand (Emeritus Professor of Mathematics, Imperial College), Francine Bennett (Founder, Mastodon-C), Patrick Wolfe (Professor of Statistics, UCL / Executive Director, UCL Big Data Institute). Chair: Martin Goodson (Vice-President Data Science, Skimlinks). Discussant: John Pullinger (UK National Statistician).

> [59] 数据科学与统计：不同的世界？参与者：Zoubin Ghahramani（剑桥大学机器学习教授）、Chris Wiggins（《纽约时报》首席数据科学家）、David Hand（帝国学院数学荣誉教授）、Francine Bennett（Mastodon-C创始人）、Patrick Wolfe（UCL统计教授/UCL大数据研究所执行主任）。主席：Martin Goodson（Skimlinks数据科学副总裁）。讨论者：John Pullinger（英国国家统计学家）。


> [60] Wikipedia credits computer scientist Peter Naur with using the term data science heavily already in the 1960s and 1970s, but not really in the modern sense.


> [60] 维基百科认为计算机科学家 Peter Naur 在20世纪60年代和70年代就已经大量使用了数据科学这一术语，但并不是真正意义上的现代科学。


> [61] Echoing Wu's master's curriculum proposal from the Carver lecture. 

> [61] 呼应了吴建福教授在Carver讲座中提出的硕士课程建议。

### Comments from University of Michigan Readers

### 密歇根大学读者评论


I received e-mails from three readers at the University of Michigan who in various degrees of intensity objected to my portrayal of the MIDAS data science initiative (DSI).

我收到了密歇根大学三位读者的电子邮件，他们在不同程度上强烈反对我对其数据科学计划（DSI）的描述。


For example, Peter Lenk told me good-naturedly that I "bashed his University," while statistician R.J.A. Little offered a friendly warning to avoid "inflammatory language."

例如，Peter Lenk善意地告诉我，我“抨击了他的大学”，而统计学家 R.J.A. Little 则友好地警告我要避免“煽动性语言”。

AL Hero, the director of the MIDAS initiative, wrote to me making several points, some of which are reflected in footnotes to Section 2.1. Hero's points include: (1) that statisticians were involved in the planning effort for MIDAS; (2) that the speakers at the introductory colloquium all used statistical methods in fundamental ways, even though they may not have all been from the Statistics Department; and (3) that the 135 MIDAS affiliated faculty include 30+ statisticians in the Statistics Department and elsewhere. These are all very appropriate points to make.

密歇根数据科学机构(MIDAS)计划的负责人AL Hero写信给我，提出了几点，其中一些内容反映在第2.1节的脚注中。Hero的观点包括：（1）统计学家参与了MIDAS的规划工作；（2） 介绍座谈会上的发言者都以统计方法为基础，尽管他们可能并非都来自统计系；（3）135名MIDAS教员包括统计系和其他系的30多名统计学家。这些观点都十分恰当。


I have nothing to criticize about the MIDAS program; nowhere do I point to some other DSI as doing a better job. I have never organized such a program and doubt that I could. The initiative seems well designed and well run.

我对MIDAS没有什么可批评的；我并不认为其他数据科学计划(DSI)可以做得更好。我从来没有组织过这样的项目，我也同时怀疑我能否做到。这项计划似乎设计完善，运行良好。


Hero and others were concerned that readers of my article might form the incorrect opinion that statisticians were specifically excluded from the MIDAS data science initiative; Hero explained they were involved all along. I never thought otherwise.

Hero和其他人担心我的文章的读者可能会产生错误的印象，即认为统计学家被明确排除在MIDAS数据科学计划之外；Hero解释说他们一直都参与其中。我其实从来没有这么想过。

I am writing here about what the program and its announcement would look like to many statisticians upon inception. Moreover, my specific points about the public face of the initiative were uncontested.

我在这里想要表达的是，该计划及其公告一开始给统计学家留下的印象。此外，我关于该计划宣传的具体观点应该是无可争议的。


To clarify my position: I think that many statisticians would today, on the basis of appearances, conclude that data sciencewhile overlapping heavily with statistics-offers a public face intentionally obscuring this overlap.  $^{62}$ In making a DSI look new and attractive for the media and potential students, DSI administrators downplay continuity with the traditional statistics discipline-suggesting that such discontinuity is a feature and not a bug.

为了澄清我的立场，我需要说明的是：我认为今天许多统计学家会根据表象得出结论，即认为数据科学虽然与统计学有很大的重合，但却同时有意掩饰这种重合 $^{62}$。为了使数据科学计划(DSI)能够显得足够新颖，以吸引媒体和更多有意报考的学生，DSI的管理层淡化了项目与传统统计学科的密切联系，但这种淡化其实是一种策略，而不是一种缺陷。


Moreover, I think it is healthy for statisticians to have this perception. Let them ponder the idea that statistics may become marginalized. The train may well be leaving the station. Statisticians may well get left behind.

此外，我认为统计学家有这种看法并无不妥。这会敦促他们思考统计学是否可能会被边缘化。火车就快要离开车站了，统计学家再无作为，可能便会被甩在后面。


> [62] In fact, Hero's remarks support this interpretation; Hero says in so many words that, if statisticians really knew all the facts behind the scenes, they would agree that statistics is substantially involved in the MIDAS DSI. Fine-but this means my comment that "statistics is the subject that dare not speak its name" (Aside: Is this the inflammatory language that Professor Little worries about?) is roughly on target.

> [62] 事实上，Hero的评论也支持这种解释；Hero说了这么多话来解释：如果统计学家了解了计划幕后完整的运作流程，他们也会认同统计是MIDAS数据科学计划中不可或缺的一部分。没错，但这意味着我的评论“统计学是一门不敢说出名字的学科”（旁白：这是Little教授担心的煽动性语言吗？）倒也并无不妥。


### Chris Wiggins, Columbia University

### Chris Wiggins，哥伦比亚大学

Chris Wiggins is the Chief Data Scientist of the New York Times, and a Professor at Columbia affiliated with several programs, including its Data Science Initiative and its Statistics Department.

Chris Wiggins 是《纽约时报》的首席数据科学家，也是哥伦比亚大学的教授，曾参与多个项目，包括其数据科学计划和统计系建设。


Wiggins and I first interacted after my talk at Princeton in September 2015 when he pointed out to me that he had earlier made a presentation about data science, for example, at ICERM, in which John Tukey's FoDA played a large part. In fact the parallelism in places of the two presentations is striking. $^{63}$

Wiggins和我第一次互动是2015年9月我在普林斯顿的演讲后。当时他提出，他早些时候在ICERM做了一个关于数据科学的演讲，John Tukey的“数据科学之未来”(FoDA)在其中发挥了很大作用。事实上，这两个演讲有诸多惊人的的相似之处 $^{63}$。

Wiggins made numerous points in conversation and in email, the most striking of which I will now attempt to evoke. I stress that Wiggins did not always use these specific words. I hope that he will publish an essay making his points.

Wiggins在谈话和电子邮件中提出了许多观点，我想转述其中最精彩的一部分。请注意Wiggins可能并未使用这些特定的词汇，我希望他也能发表一篇文章阐述他的观点。


- Academic statistics is permanently deformed by the postwar association with mathematics that Tukey first called attention to.

- 战后，Tukey第一次让人们注意到——学术统计和数学的关系变得畸形。

- That deformation will prevent it from having relevance in the new data science field and the new big data world that is rapidly forming.

- 这种畸形将使得它无法在新的数据科学领域和正在迅速形成的新的大数据世界中发挥作用。

- "Data science is not a science, even though Donoho might like it. It is a form of engineering, and the doers in this field will define it, not the would-be scientists." (C. Wiggins, private communication, October 2015.)

- “数据科学不是一门科学，尽管 Donoho 可能喜欢它。它是一种工程形式，该领域的实干家才能定义它，而不是未来的科学家。”（C.Wiggins，私下沟通，2015年10月）


These statements have weight. I obviously cannot object to the first one. The second and third ones are predictions and time will obviously tell.

这些说法很有分量。我显然不能反对第一个。第二个和第三个则是预测，时间会告诉我们答案。


I agree with Wiggins that whether statisticians will respond energetically to the data science challenge is very much an open question.

我同意Wiggins的观点，即统计学家是否会积极应对数据科学挑战，这是一个非常开放的问题。

> [63] James Guzca, Chief Data Scientist at Deloitte, later wrote to me about a data science course that he gave in which Tukey's statements also play a similar role. 

> [63] 德勤（Deloitte）首席数据科学家 James Guzca 后来写信给我，描述了他开设的数据科学课程，Tukey的观点也起到了类似的作用。

### Sean Owen's "What '50 Years of Data Science' Leaves Out"

### Sean Owen的《数据科学50年》


Sean Owen, Director of Data Science at Cloudera, has posted an essay reacting to my manuscript. (https://medium.com/@srowen/what-50-years-of-data-science-leaves-out-2366c9b61d3d)

Cloudera数据科学总监 Sean Owen 发表了一篇文章，对我的手稿做出了回应。(https://medium.com/@srowen/what-50-years-of-data-science-leaves-out-2366c9b61d3d)

Owen makes many interesting points, and readers will wish to consult the text directly.

Owen提出了许多有趣的观点，读者可以直接看原文。

Near the beginning, we read:

在开始时，我们看到：


> ...reading it given my engineering-based take on data science, it looks like an attack on a partial straw-man. Along the way to arguing that data science can't be much more than statistics, it fails to contemplate data engineering, which I'd argue is most of what data science is and statistics is not.

> ……考虑到我对数据科学基于工程学的看法，您的观点在我看来更像是在攻击一个稻草人。在争论统计学是不是数据科学子集的过程中，它没有考虑到数据工程，我认为数据工程才是数据科学的大部分，而统计学不是。

I like Owen's essay and offer a few mild responses.

我喜欢Owen的文章，并给出了一些温和的回应。

- Nowhere did I say that data science cannot be much more than statistics. I quote approvingly others who say the opposite. John Chambers was saying quite literally that there is a larger field than traditional statistics, and Bill Cleveland was saying quite literally that what some academic statistics departments are doing is a small part of data science. I did literally say that even data science as it is currently being instituted is too limited; there is a field I called "greater data science" extending beyond the limits of today's "consensus data science."

- 我没有说过数据科学只能是统计学，恰恰相反，我引用了其他人的对立观点。John Chambers曾直言，有一个比传统统计学更大的领域，Bill Cleveland也曾表示，一些学术统计系正在做的只是数据科学的一小部分。我确实提到过，即使是现在，正在发展的数据科学也依然狭隘；有一个领域我称之为“广义数据科学”，它超越了今天“共识数据科学”的边界。


- Owen's essay focuses on the important term "data engineering," which I under-played in the main text. Data engineers exploit currently available cloud/cluster computing resources to allow the storage of large databases and to implement complex processing pipelines.  $^{65}$

- Owen的文章集中在“数据工程”这一重要术语上，我在正文中没有提到它。数据工程师利用当前可用的云/集群计算资源来存储大型数据库并实现复杂的处理管道 $^{65}$。


- Owen writes that "data engineering ...is most of what data science is and statistics is not." Owen's claim goes beyond my current understanding of the boundaries of both statistics and data science. A block diagram I used in my talk at Princeton showed blocks labeled "Statistics," "Data Science," and "Data Engineering;" there are important differences between these blocks at the present time.

- Owen写道：“数据工程……是数据科学的主要内容，而统计学不是。” Owen的说法超出了我目前对统计学和数据科学界限的理解。我在普林斯顿大学演讲时使用的框图显示了标有“统计学”、“数据科学”和“数据工程”的方框；目前，我认为这些分类之间存在重要差异。


Owen complained that my Version $1.00$ manuscript was "writing data engineering out of the story of data science." I certainly intended no such thing. For the academic statistics audience that I was addressing at the Tukey Centennial, many of whom had not previously heard talks about the data science moment, I judged that I had zero chance of engaging the audience unless I could connect to our (their and my) common academic and historical background.

Owen抱怨说，我的1.00版本手稿是“在数据科学的故事中写数据工程”。”我当然不是有意为之。我在Tukey百年纪念大会上演讲时，台下学术统计听众中的大部分以前从未听到过有关数据科学时刻的消息。我认为，我必须联系到我们（他们和我）共同的学术和历史背景，才能够吸引听众。


Sean Owen is completely correct to say that the full story of the emergence of data science, and the role of industry in shaping and defining it, remains to be written.

Sean Owen 提出，本文还应囊括数据科学出现的完整故事，以及工业在塑造和定义数据科学方面的作用，我十分赞同。


I return to a point I made earlier: many of the struggles associated with scaling up algorithms are transitory. In time, better tools will come along that make the data engineering part of the data science equation much easier in many applications.

回到我之前说过的一点：许多大数据算法带来的困难都是暂时的。随着时间的推移，更优异的工具将会涌现，并使得数据科学分类中的数据工程部分，在许多应用程序中变得更加容易。


Owen's essay supports this point. Owen describes how the example I gave above in Section 2.2, involving Hadoop, is no longer current; the data engineering community has moved away from Hadoop toward Apache Spark, where the example I gave would be much easier to implement. The rapid obsolescence of specific tools in the data engineering stack suggests that today, the academic community can best focus on teaching broad principles-"science" rather than "engineering."

Owen的文章支持了这一观点。Owen讲述了我在第2.2节中给出的涉及Hadoop的示例是如何过时的；数据工程界已经从Hadoop转向Apache Spark，在那里我给出的例子更容易实现。数据工程堆栈中特定工具的迅速过时表明，今天，学术界最好专注于教授广泛的原则——“科学”而不是“工程”。


> [65] Insight Data trains conventionally trained PhD's to become data scientists and data engineers. From their website: Our definition of data engineering includes what some companies might call Data Infrastructure or Data Architecture. The data engineer gathers and collects the data, stores it, does batch processing or real-time processing on it, and serves it via an API to a data scientist who can easily query it. https://blog.insightdatascience.com/about-insight-b535888ecb3a 

> [65] Insight Data致力于培养通过传统培训的博士成为数据科学家和数据工程师。从他们的网站上看：我们对数据工程的定义包括一些公司可能称之为数据基础设施或数据架构。数据工程师收集和收集数据，存储数据，对其进行批处理或实时处理，并通过API将其提供数据科学家。https://blog.insightdatascience.com/about-insight-b535888ecb3a



## Acknowledgments

## 致谢

Thanks to John Storey, Amit Singer, Esther Kim, and all the other organizers of the Tukey Centennial at Princeton, September 18, 2015. This provided an occasion for me to organize my thoughts on this topic, for which I am grateful.

感谢John Storey、Amit Singer、Esther Kim，以及2015年9月18日在普林斯顿举行的Tukey百年纪念的所有其他组织者。这给了我机会组织我对这个主题的思考，我对此表示感谢。


Special thanks to Edgar Dobriban (U. Penn.), Bradley Efron (Stanford), and Victoria Stodden (Univ Illinois) for comments on data science and on pre 1.00 drafts of this article. Thanks to the many readers of the 1.00 draft who wrote to me with valuable suggestions about how it could be improved. In particular, Chris Wiggins (Columbia) corresponded extensively with me on matters large and small concerning many aspects of Version 1.00 and in so doing clarified my thinking notably. This version contains an Epilogue mentioning some important points raised by Wiggins, and also by Jeff Wu (Georgia Tech), AL Hero (University of Michigan), and Sean Owen (Cloudera).

特别感谢Edgar Dobriban（宾夕法尼亚大学），Bradley Efron（斯坦福大学）和Victoria Stodden（伊利诺伊大学）就数据科学和本文1.00前的草稿发表的评论。感谢许多1.00草稿的读者，他们给我写信，就如何改进草稿提出了宝贵的建议。特别是，Chris Wiggins（哥伦比亚）就1.00版诸多方面的各种问题与我进行了广泛沟通，从而明确了我的想法。该版本包含一篇尾声，其中提到了Wiggins、Jeff Wu（佐治亚理工学院）、AL Hero（密歇根大学）和Sean Owen（Cloudera）提出的一些重要观点。


Thanks are also due to Deepak Agarwal (Linked In), Rudy Beran (UC Davis), Peter Brown (Renaissance Technologies), Jiashun Jin (Carnegie Mellon), Rob Kass (Carnegie Mellon), Martin Helm (Deutsche Bank), Ron Kennett (KPA Associates), Peter Lenk (Univ. Michigan), Mark Liberman (Univ. Pennsylvania), R.J. Little (Univ. Michigan), Xiao-Li Meng (Harvard) and Adrian Raftery (University of Washington), and Hadley Wickham (RStudio and Rice) for encouragement and corrections.

感谢Deepak Agarwal（LinkedIn）、Rudy Beran（UC Davis）、Peter Brown（Renaissance Technologies）、金家顺（卡内基梅隆大学）、Rob Kass（卡内基梅隆大学）、Martin Helm（德意志银行）、Ron Kennett（KPA Associates）、Peter Lenk（密歇根大学）、Mark Liberman（宾夕法尼亚大学）、孟晓犁（哈佛大学）、 Adrian Raftery（华盛顿大学）和Hadley Wickham（RStudio和Rice）鼓励和纠正。


Belated thanks to my undergraduate statistics teachers: Peter Bloomfield, Henry Braun, Tom Hettmansperger, Larry Mayer, Don McNeil, Geoff Watson, and John Tukey.

感谢我的本科统计老师：Peter Bloomfield, Henry Braun, Tom Hettmansperger, Larry Mayer, Don McNeil, Geoff Watson和John Tukey。

## Funding

## 基金


Supported in part by NSF DMS-1418362 and DMS-1407813.

部分由NSF DMS-1418362和DMS-1407813支持。


## References

## 参考文献


Barlow, M. (2013), The Culture of Big Data, Sebastopol, CA: O'Reilly Media, Inc. [748]

Baumer, B. (2015), "A Data Science Course for Undergraduates: Thinking With Data," The American Statistician, 69, 334-342. [757]

Bernau, C., Riester, M., Boulesteix, A.-L., Parmigiani, G., Huttenhower, C., Waldron, L., and Trippa, L. (2014), "Cross-Study Validation for the Assessment of Prediction Algorithms," Bioinformatics, 30, i105-i112. [759]

Breiman, L. (2001), "Statistical Modeling: the Two Cultures," Statistical Science, 16, 199-231. [751]

Button, K. S., Ioannidis, J. P. A., Mokrysz, C., Nosek, B. A., Flint, J., Robinson, E. S. J., and Munafò, M. R. (2013), "Power Failure: Why Small Sample Size Undermines the Reliability of Neuroscience," Nature Reviews Neuroscience, 14, 365-376. [759]

Carp, J. (2012), "The Secret Lives of Experiments: Methods Reporting in the fMRI Literature," Neuroimage, 63, 289-300. [759]

Chambers, J. M. (1993), "Greater or Lesser Statistics: A Choice for Future Research," Statistics and Computing, 3, 182-184. [750]

Chavalarias, D., Wallach, J., Li, A., and Ioannidis, J. A. (2016), "Evolution of Reporting $\mathrm{p}$ Values in the Biomedical Literature, 1990-2015," Journal of the American Medical Association, 315, 1141-1148. [759,761]

Cleveland, W. S. (1985), The Elements of Graphing Data, Monterey, CA: Wadsworth Advanced Books and Software. [758]

__(1993), Visualizing Data, Summit, NJ: Hobart Press.

__(2001), "Data Science: An Action Plan for Expanding the Technical Areas of the Field of Statistics," International Statistical Review, 69, 2126. [750] Coale, A. J., and Stephan, F. F. (1962), "The Case of the Indians and the Teen-Age Widows," Journal of the American Statistical Association, 57, 338-347. [755]

Collins, F., and Tabak, L. A. (2014), "Policy: NIH Plans to Enhance Reproducibility," Nature, 505, 612-613. [760]

Cook, D., and Swayne, D. F. (2007), Interactive and Dynamic Graphics for Data Analysis: With R and GGobi, New York: Springer Science \& Business Media. [758]

Dettling, M. (2004), "BagBoosting for Tumor Classification with Gene Expression Data," Bioinformatics, 20, 3583-3593. [762]

Donoho, D., and Jin, J. (2008), "Higher Criticism Thresholding: Optimal Feature Selection When Useful Features Are Rare and Weak," Proceedings of the National Academy of Sciences, 105, 14790-14795. [762]

Donoho, D. L., Maleki, A., Rahman, I. U., Shahram, M., and Stodden, V. (2009), "Reproducible Research in Computational Harmonic Analysis," Computing in Science and Engineering, 11, 8-18. [760]

Fisher, R. A. (1936), "The Use of Multiple Measurements in Taxonomic Problems," Annals of Eugenics, 7, 179-188. [762]

Freire, J., Bonnet, P., and Shasha, D. (2012), "Computational Reproducibility: State-of-the-Art, Challenges, and Database Research Opportunities," in Proceedings of the 2012 ACM SIGMOD International Conference on Management of Data, SIGMOD '12, ACM, pp. 593-596. $[760,761]$

Gavish, M. (2012), "Three Dream Applications of Verifiable Computational Results," Computing in Science \& Engineering, 14, 26-31. [761]

Gavish, M., and Donoho, D. (2011), "A Universal Identifier for Computational Results," Procedia Computer Science, 4, 637–647. [761]

Hand, D. J. (2006), "Classifier Technology and the Illusion of Progress," Statistical Science, 21, 1-14. [761,763]

Harris, H., Murphy, S., and Vaisman, M. (2013), Analyzing the Analyzers: An Introspective Survey of Data Scientists and Their Work, Sebastopol, CA: O’Reilly Media, Inc. [748]

Heroux, M. A. (2015), "Editorial: ACM TOMS Replicated Computational Results Initiative," ACM Transactions on Mathematical Software, 41, 13:1-13. [760]

Horton, N. J., Baumer, B. S., and Wickham, H. (2015), "Taking a Chance in the Classroom: Setting the Stage for Data Science: Integration of Data Management Skills in Introductory and Second Courses in Statistics," CHANCE, 28, 40-50. [757]

Hotelling, H. (1940), "The Teaching of Statistics," The Annals of Mathematical Statistics, 11, 457-470. [754]

Ioannidis, J. P. A. (2005), "Contradicted and Initially Stronger Effects in Highly Cited Clinical Research," Journal of the American Medical Association, 294, 218-228. [759]

__(2007), "Non-Replication and Inconsistency in the Genome-Wide Association Setting," Human Heredity, 64, 203-213. [760]

__(2008), "Why Most Discovered True Associations are Inflated," Epidemiology, 19, 640-648. [759]

Iverson, K. E. (1991), "A Personal View of APL," IBM Systems Journal, 30 , 582-593. [758]

Jager, L. R., and Leek, J. T. (2014), "An Estimate of the Science-Wise False Discovery Rate and Application to The Top Medical Literature," Biostatistics, 15, 1-12. [759]

Liberman, M. (2010), "Fred Jelinek," Computational Linguistics, 36, 595599. [752]

Madigan, D., Stang, P. E., Berlin, J. A., Schuemie, M., Overhage, J. M., Suchard, M. A., Dumouchel, B., Hartzema, A. G., and Ryan, P. B. (2014), "A Systematic Statistical Approach to Evaluating Evidence From Observational Studies," Annual Review of Statistics and Its Application, 1, 11-39. [759]

Marchi, M., and Albert, J. (2013), Analyzing Baseball Data with R, Boca Raton, FL: CRC Press. [757]

McNutt, M. (2014), "Reproducibility," Science, 343, 229. [760]

Mosteller, F., and Tukey, J. W. (1968), "Data Analysis, Including Statistics," in Handbook of Social Psychology (Vol. 2), eds. G. Lindzey, and E. Aronson, Reading, MA: Addison-Wesley, pp. 80-203. [749]

Open Science Collaboration et al. (2015), "Estimating the Reproducibility of Psychological Science,” Science, 349, aac4716. [760]

Pan, Z., Trikalinos, T. A., Kavvoura, F. K., Lau, J., and Ioannidis, J. P. A. (2005), "Local Literature Bias in Genetic Epidemiology: An Empirical Evaluation of the Chinese Literature," PLoS Medicine, 2, 1309. [759]

Peng, R. D. (2009), "Reproducible Research and Biostatistics," Biostatistics, $10,405-408 .[760]$

Prinz, F., Schlange, T., and Asadullah, K. (2011), "Believe It or Not: How Much Can We Rely on Published Data on Potential Drug Targets?" Nature Reviews Drug Discovery, 10, 712-712. [760]

Ryan, P. B., Madigan, D., Stang, P. E., Overhage, J. M., Racoosin, J. A., and Hartzema, A. G. (2012), "Empirical Assessment of Methods for Risk Identification in Healthcare Data: Results From the Experiments of the Observational Medical Outcomes Partnership," Statistics in Medicine, 31, 4401-4415. [759]

Stodden, V. (2012), "Reproducible Research: Tools and Strategies for Scientific Computing," Computing in Science and Engineering, 14, 11-12. [760]

Stodden, V., Guo, P., and Ma, Z. (2013), "Toward Reproducible Computational Research: An Empirical Analysis of Data and Code Policy Adoption by Journals," PLoS ONE, 8, e67111. [760]

Stodden, V., Leisch, F., and Peng, R. D., editors. (2014), Implementing Reproducible Research, Boca Raton, FL: Chapman \& Hall/CRC. [760,761]

Stodden, V., and Miguez, S. (2014), "Best Practices for Computational Science: Software Infrastructure and Environments for Reproducible and Extensible Research," Journal of Open Research Software, 1, e21. [761]

Sullivan, P. F. (2007), "Spurious Genetic Associations," Biological Psychiatry, 61, 1121-1126. [760] Tango, T. M., Lichtman, M. G., and Dolphin, A. E. (2007), The Book: Playing the Percentages in Baseball, Lincoln, NE: Potomac Books, Inc. [757]

Tukey, J. W. (1962), "The Future of Data Analysis," The Annals of Mathematical Statistics, 33, 1-67. [749]

[758] (1977), Exploratory Data Analysis, Reading, MA: Addison-Wesley. [758]

__(1994), The Collected Works of John W. Tukey: Multiple Comparisons (Vol. 1), eds. H. I. Braun, Pacific Grove, CA: Wadsworth \& Brooks/Cole. [758]

Wandell, B. A., Rokem, A., Perry, L. M., Schaefer, G., and Dougherty, R. F. (2015), "Quantitative Biology - Quantitative Methods," Bibliographic Code: 2015arXiv150206900W. [761]

Wickham, H. (2007), "Reshaping Data With the Reshape Package," Journal of Statistical Software, 21, 1-20. [757]

__(2011), "ggplot2," Wiley Interdisciplinary Reviews: Computational Statistics, 3, 180-185. [757]

__(2011), "The Split-Apply-Combine Strategy for Data Analysis," Journal of Statistical Software, 40, 1-29. [757]

Wilkinson, L. (2006), The Grammar of Graphics, New York: Springer Science \& Business Media. [758]

Zhao, S. D., Parmigiani, G., Huttenhower, C., and Waldron, L. (2014), "Más-o-Menos: A Simple Sign Averaging Method for Discrimination in Genomic Data Analysis," Bioinformatics, 30, 3062-3069. [762]
