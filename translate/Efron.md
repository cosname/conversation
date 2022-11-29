# Bradley Efron: A Conversation with Good Friends

# Bradley Efron访谈：与好朋友的对话


Susan Holmes, Carl Morris and Rob Tibshirani


> 译者注：原文标题为*Bradley Efron: A Conversation with Good Friends*，作者Susan Holmes, Carl Morris and Rob Tibshirani。于2013年发表在*Statistical Science*杂志。Bradley Efron是统计学大师，bootstrap方法的提出者。Efron的统计思想对包括生物学、经济学、社会学、计算机科学等众多领域产生了深远的影响。2005年，Efron教授获得了美国国家科学奖章（美国自然科学最高奖）。本文由统计之都访谈栏目组织翻译，由cloud、bored2020等人翻译，潘岚锋审核定稿，丁鹏、李赛、邱怡轩、郭旭曾在翻译过程中给予了非常专业的建议，感谢所有志愿者的付出。


**Abstract:**  Bradley Efron is Professor of Statistics and Biostatistics at Stanford University. He works on a combination of theoretical and applied topics, including empirical Bayes, survival analysis, exponential families, bootstrap and jackknife methods and confidence intervals. Most of his applied work has originated in biomedical consulting projects at the Stanford Medical School, mixed in with a few papers concerning astronomy and physics. Even his theoretical papers usually begin with specific applied problems. All three of the interviewers here have been close scientific collaborators.

**摘要：** Bradley Efron是斯坦福大学统计学和生物统计学教授。他致力于理论和应用主题的结合，包括经验贝叶斯、生存分析、指数族、bootstrap、jackknife方法以及置信区间。他的大部分应用工作都来自斯坦福医学院（Stanford Medical School）的生物医学咨询项目，还有一些关于天文学和物理学的论文。甚至他的理论论文通常都是从具体的应用问题开始的。本文中的三位采访者都是他的紧密科研合作伙伴。

Brad was born in St. Paul, Minnesota, May 1938, to Esther and Miles Efron, Jewish-Russian immigrants. A Merit Scholarship, in the program's inaugural year, brought him to Caltech, graduating in Mathematics in 1960 . He arrived at Stanford that Fall, eventually gaining his Ph.D., under the direction of Rupert Miller and Herb Solomon, in the Statistics Department, whose faculty also included Charles Stein, Herman Chernoff, Manny Parzen, Lincoln Moses and Ingram Olkin. Brad has lived at Stanford since 1960, with sabbaticals at Harvard, Imperial College and Berkeley. He has held several administrative positions in the university: Chair of Statistics, Associate Dean of Science, Chairman of the University Advisory Board and Chair of the Faculty Senate. He is currently Chair of the Undergraduate Program in Applied Mathematics.

1938年5月，Brad出生在明尼苏达州圣保罗，他的父母是俄罗斯犹太移民Esther和迈Miles Efron。在获得一项奖学金之后，他来到了加州理工学院，并于1960年毕业于数学系。同年秋天，他来到斯坦福大学，在统计系Rupert Miller 和 Herb Solomon的指导下，获得了博士学位。统计系的教师还包括Charles Stein、Herman Chernoff、Manny Parzen、Lincoln Moses和Ingram Olkin。Brad自1960年以来一直住在斯坦福大学，并在哈佛大学、帝国理工学院和伯克利大学学术休假。他曾在斯坦福大学担任过多个行政职务：统计系主席、理学院副院长、大学顾问委员会主席和教师委员会主席。他目前是应用数学本科项目的主席。

Honors include doctorates from Chicago, Madrid and Oslo, a MacArthur Prize Fellowship, membership in the National Academy of Sciences and the American Academy of Arts and Sciences, fellowship in the IMS and ASA, the Wilks Medal, Parzen Prize, the newly inaugurated Rao Prize and the outstanding statistician award from the Chicago ASA chapter. He has been the Rietz, Wald, and Fisher lecturers and holds the Max H. Stein endowed chair as Professor of Humanities and Sciences at Stanford. Professional service includes Theory and Methods Editor of $J A S A$ and President of the IMS. Currently he is President-Elect of the American Statistical Association, becoming President in $2004 .$

Efron被授予很多荣誉，包括来自芝加哥、马德里和奥斯陆的博士学位，麦克阿瑟奖、美国科学院和美国艺术与科学院院士、国际数理统计学会(IMS)和美国统计学会(ASA)会士、威尔克斯奖章、帕尔森奖、新成立的Rao奖以及芝加哥ASA分会颁发的杰出统计学家奖。他曾担任Rietz、Wald和Fisher荣誉讲座人，还是斯坦福大学人文与科学学院荣誉教授（由Max H.Stein捐赠）。专业服务包括JASA期刊(Journal of the American Statistical Association)的理论与方法主编和IMS主席。2004年开始，他担任了ASA当选主席。

Part of this interview was taken from an interview videotaped by the American Statistical Association and  sponsored by Pfizer Central Research, November 5 , 2001 ; the rest was done at the Statistics Department at Stanford.

本次访谈的部分内容摘自美国统计学会录制的访谈录像，由辉瑞研究中心赞助，2001年11月5日；其余的工作在斯坦福大学统计系完成。

## EARLY YEARS

## 早年

Tibshirani: Let's start from the beginning. How did you first learn about statistics?

**Tibshirani**：让我们从头开始。你是如何和统计学相识的？

Efron: In St. Paul, Minnesota, my dad was a salesman and truck driver, but he had a great love for math- ematics. He was also the bowling and baseball statistician, which had more effect on me than I thought. I went to Caltech with all these wonderfully smart people, but there was almost no statistics. We had one statistics course out of Cy Derman's book. I asked one of my professors, Morgan Ward, if there was anything else I could study, and he gave me Cramér's book, which I read from beginning to end. I thought it was fitting. Cramér wrote that book in isolation during World War II, and I read it in isolation at Caltech. I decided I wanted to go into statistics because I had no future as a 20 th-century mathematician. I would have been okay in the 19 th century, but I had no mind for the kind of abstractions that dominate modern mathematics, so I wound up going into statistics. I talked to Berkeley and had a very nice interview with two men named Jerzy and Erich, who were very kind to me, but somehow I wound up at Stanford. When I got there I found out I was in the math department because my advisors had told Stanford that I was probably intending to be a mathematician, so I spent my first year in the math department and then went over to statistics.

**Efron**：在明尼苏达州的圣保罗，我父亲是一名推销员和卡车司机，但他对数学有着极大的热爱。他还是保龄球和棒球的统计师，这对我的影响比我想象的要大。我和这些非常聪明的人一起去了加州理工学院，但几乎没有与统计相关的东西。我们除了Cy Derman的书以外没有别的统计的课程。我询问了一位导师Morgan Ward是否还有啥可以让我学习的，他给了我一本Cramér的书，我将这本书从头读到尾。我觉得它挺合我胃口。Cramér在第二次世界大战期间独立地写了这本书，我在加州理工学院独立地读了这本书。我决定从事统计学研究，因为我没有一个作为20世纪数学家的前途。在19世纪，我如果成为一个数学家是还可以的，但是我没有那种抽象的思维，而这种思维主导着现代数学。所以我最终进入了统计学领域。我和伯克利谈了谈，并对两个对我很友善的人——Jerzy和Erich进行了一次非常愉快的采访。但不知何故，我最终来到了斯坦福大学。当我到那里时，我却发现我在数学系，因为我的导师之前告诉斯坦福，我可能打算成为一名数学家，所以我在数学系度过了第一年，然后转到了统计。

That's when Carl and I, who first met as freshmen at Caltech around 1957, were reunited. Nobody in science works by themselves, and I've had more than my share of wonderful colleagues; you just can't work in fields like statistics by yourself. You have to have the kind of stimulation that comes from being around smart people challenging you. One of the great advantages of the Stanford department is that it's full of people quite willing to challenge you in a pleasant way.

就在那时，Carl和我重逢了，他们第一次见面是在1957年左右，当时还是加州理工学院的新生。在科学界，没有人能独立工作，我有很多很棒的同事；你不能一个人在统计这样的领域工作。你必须得受点刺激——那种来自聪明人挑战。**斯坦福系的一大优势是，它从不缺这种非常乐意并以愉快的方式挑战你的人！**
 
Tibshirani: Is it true you were kicked out of Stanford as a student?

**Tibshirani**：你真的被斯坦福大学开除了吗？

Efron: One of the reasons I came to Stanford was because of its humor magazine. I wrote a humor column at Caltech, and I always wanted to write for a humor magazine. Stanford had a great humor magazine, The Chaparral. The first few months I was there, the editor literally went crazy and had to be hospitalized, and so I became editor. For one issue we did a parody of Playboy and it went a little too far. I was expelled from school, and I would have been expelled forever except that people like $\mathrm{Al}$ Bowker, Halsey Royden and Herb Solomon, who were high in the administration, said I was a good student. So I went away for 6 months and then I came back. That was by far the most famous I've ever been. My picture was in the paper everyday because I fought like crazy.

**Efron**：我来斯坦福的原因之一是因为它的幽默杂志。我一直想为一本幽默杂志写稿，我在加州理工学院就写过幽默专栏。斯坦福大学有一本很棒的幽默杂志“The Chaparral”。我在那里的头几个月，编辑疯了，不得不住院，然后我成了编辑。有一期我们模仿了花花公子，有点过火了。我就被学校开除了。如果不是因为在管理层中地位很高的AL Bowker、Halsey Royden和Herb Solomon说我是个好学生，我可能就被永远被开除了。所以我休学了6个月，然后回来了。那是我迄今为止最出名的一次。我的照片每天都在报纸上，因为我像个疯子一样抗争。


<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-02.jpg?height=717&width=508&top_left_y=148&top_left_x=655)

FIG. 1. Stanford faculty photo, $1972 .$

图 1：斯坦福大学教员照片，1972。
</div>


Morris: I remember Brad was a really good writer as an undergrad, but what you did back then was so tame, now people wouldn't think anything about it. It probably just bothered the local clergy.


**Morris**：我记得Brad本科时是一个非常好的作家，但你当时所做的事情太平淡了，现在人们不会去想它。可能只是惹了当地的神职人员。

Efron: I was denounced from the pulpit of the Catholic church.

**Efron**：我曾在天主教堂的讲坛上受到谴责。

Morris: Excommunicated.

**Morris**：被逐出教会？

Efron: Well, they couldn't do that. But they would have if they could have.

**Efron**：不，他们没权限那样做。但如果有的话，他们一定会。

Morris: You've used those writing talents, I think; it's been part of your success in statistics. Your ability to put things in ways that help people understand better.

**Morris**：我想你运用了那些写作天赋；这是你在统计学方面取得成功的一部分。你的表达能力能帮助人们更好地理解事务。

Tibshirani: So, tell us more about your family. I know you have three brothers in academia and your son is going into academia.

**Tibshirani**：说说你家庭的情况。我知道你有三个兄弟在学术界，而你的儿子正在进入学术界。

Efron: My father gave us this pretty clear picture that we weren't suited for heavy work. My older brother, Arthur, is a retired professor of English, a noted expert on romantic literature. He publishes his own journal called Paunch, on romantic literature, after Sancho Panza. I get Paunch, and it alternates between very esoteric English theory and smut. My two younger brothers, who are twins, have always been very close. Don was drafted and went to Canada where he's been a happy citizen. They're both psychiatric social workers. Don runs his own journal on family therapy and Ron has become an expert on unpleasant emotions. He's written a book called Angry All the Time. My son, Miles, is one of these cases that we like to hear of, a humanities student who suddenly became interested in statistics in the last few years. He's now working in Chapel Hill on information retrieval. Sometimes he calls me and asks me hard questions about singular value decompositions.


**Efron**：我父亲非常清楚地告诉我们，我们不适合从事繁重的体力工作。我的哥哥Arthur是一位退休的英语教授，著名的浪漫主义文学专家。他创办了自己的期刊《大腹便便》（Paunch），以Sancho Panza的名字命名，是关于浪漫文学的。我看过这个杂志，它交织于深奥的英语理论和淫词艳句之中。我的两个弟弟是双胞胎，他们一直很亲近。Don 被征召入伍，去了加拿大，在那里他是一个快乐的人。同事们都是精神病社会工作者。Don 经营着自己的家庭治疗杂志，而Ron 则成为了情绪低落方面的专家。他写了一本书叫《一直愤怒》(Angry All the Time)。我的儿子 Miles 是那种我们都喜欢的孩子，他是一名人文学科的学生，在过去几年里突然对统计学产生了兴趣。他现在在教堂山从事信息检索工作。有时他打电话给我，问我一些关于奇异值分解的难题。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-03.jpg?height=427&width=483&top_left_y=150&top_left_x=122)

FIG. 2  "Campaign photo" for ASA presidency, 2002

图 2：2002年ASA主席的“竞选照片。
</div>


Morris: In the 1960s a lot of things were happening at once. One thing was that I couldn't make a career choice, and statistics was a way to do mathematics and do everything else in sight. A lot of our students today say that that's one of the great attractions to this field. It's not only an attraction, it's actually a necessity. It was about the 1960 s that most of the departments were being formed. Statistics was suddenly a subject that was just coming on like gangbusters. Statistics, then, at least when we were studying it, was pretty abstract. You were in biostatistics partly, but you took many other courses that were pretty much just pure mathematics.

**Morris**：在20世纪60年代，很多事情同时发生。有一件事是我当时无法做出职业选择，而统计学是一种做数学和其他一切科学的方法。今天我们的许多学生说，这是这个领域最吸引人的地方之一。它不仅是一种吸引力，实际上是一种必需品。大约在20世纪60年代，大多数系都成立了。统计学突然成为一门热门学科。至少在我们学习统计学的时候，统计学是非常抽象的。你有一部分是生物统计学，但你学了许多其他课程，这些课程几乎都是纯粹的数学。

I wound up going to RAND. I thought I'd go to RAND for 1 year and learn all about applied statistics. I wound up staying for 11 years. I had the time of my life. Applications and mathematics and computations are the triangle of ideas in statistics; how they tie together is central to our field. It seems crucial that we keep strong interest in all three fields.

我最终去了兰德咨询。我想我应该去兰德待一年，学习所有关于应用统计学的知识。我最终待了11年，在那里我度过了一生中最美好的时光。应用、数学和计算是统计学中的概念三角形；它们如何联系在一起是我们领域的核心。对这三个领域保持浓厚的兴趣至关重要。

## BEGINNINGS OF BOOTSTRAP

## Bootstrap的起源


Tibshirani: Brad, it looks to me as though your work is becoming more and more applied. That you're more motivated by real problems, is that fair to say?

**Tibshirani**：Brad，在我看来，你的工作越来越应用了。说句公道话，你更有动力去解决真正的问题？

Efron: Another way to say it is I no longer have ideas. Somehow that quit happening about 20 years ago. Now all I have is my colleagues and applied work. We have a wonderful opportunity in statistics, both men and women; we're the last gentlemen scientists, in that we can look in on lots of fields and talk to brilliant people who are confused. It's a wonderful way for me to get into a topic. Some people, more honorably, want to do applications for the application's sake, but I've always been interested in it for statistics' sake. So Rob and I have been working on microarrays together, for example. That's been wonderfully stimulating. But I'm not all that interested in the biology of microarrays. Of course, I'm interested as an amateur. What I'm really interested in is how the inference theory will come out.

**Efron**：换句话说，我不再有好点子了（从理论出发）。不知何故，这种情况发生在大约20年前。现在我只有和同事们做应用工作。在统计学方面，我们有一个极好的机会，无论男女；我们是最后的绅士科学家，因为我们可以研究众多领域，并与困惑的聪明人交谈。这对我来说是进入一个话题的绝佳方式。有些人，更可敬的是，为了应用而做应用，但我一直对统计感兴趣。例如，Rob和我一直在一起研究微阵列(microarrays)。这非常刺激。但是我对微阵列生物学不太感兴趣。当然，作为一个业余爱好者，我很感兴趣。我真正感兴趣的是统计推断理论将如何从中产生。


Tibshirani: One thing I found surprising is that we tend to find statistics relatively easy, but other scientists find it hard. A good scientist colleague of mine says it would be a lot harder for me to teach him statistics than it would be for him to teach me biology. When I look at biology it looks very daunting; it's a huge mass of facts that look mysterious. But statistics is a way of thinking that's very hard for other people to develop if they haven't been trained early on in the field. So, it's good news for us that we have something that's unique.

**Tibshirani**：有一件事让我感到惊讶，那就是我们觉得统计学相对容易，但其他科学家却觉得它很难。我的一位优秀科学家同事说，我教他统计学比他教我生物学要难得多。当我看生物学时，它看起来非常令人生畏；这是一大堆看起来神秘的事实。**但是统计学是一种思维方式**，如果其他人没有在这个领域接受过早期训练，他们很难发展这种思维方式。所以，对我们来说，我们有独特的东西是个好事情。


Morris: Do you think it's hard or do you think we've made it hard?

**Morris**：你认为这很难，还是我们让它变得很难？

Tibshirani: There's some truth to that, but I think the important simple concepts aren't as simple as they appear.

**Tibshirani**：这是事实，但我认为重要的简单概念并不像它们表面上看起来那么简单。

Morris: Like what...?

**Morris**：比如……？

Tibshirani: A permutation test to infer a $p$-value from a set of data

**Tibshirani**：从一组数据推断p值的置换检验。

Morris: I thought you might say $p$-value right off the bat. See, I think $p$-values are hard. I mean they're easy to know as numbers. But they're very confusing, in a sense that people misapply them. $p$-value is, of course, the statement about the data, given the null hypothesis, but people think it's got something to do say about the probability of the null hypothesis given the data.

**Morris**：我就猜到你要说p值。看，我认为p值很难。如果只是把p值当作数字的话是很好理解的。但从某种意义上说，它非常令人困惑，因此人们经常误用它们。当然，p值说的给定原假设，你的数据是否能拒绝；但人们认为它说的是给定数据后接收原假设的概率。


Tibshirani: Another example is confounding. A lot of very good scientists design bad experiments in which important effects are confounded with experimental biases. Confounding is something that is fundamental to our subject, we understand it and know how to address it. 

**Tibshirani**：另一个例子是混淆(confounding)。许多非常优秀的科学家设计了糟糕的实验，在这些实验中，重要的影响与实验偏差混淆在一起。混淆是我们的主题的基础，我们理解它并知道如何解决它。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-04.jpg?height=416&width=323&top_left_y=150&top_left_x=189)

FIG. 3. High school graduation photo, 1956.

图 3：高中毕业照，1956年。
</div> 

Efron: I think that many of my scientific colleagues are pretty good at probability; they naturally can do probability calculations involving elaborate models, but they're very bad at reasoning backwards from data to what the probability model might have been. I remember when going into statistics that first year I thought "this will be pretty easy, I've dealt with math and that's supposed to be hard." But statistics was much harder for me at the beginning than any other field. It took years before I felt really comfortable. It's hard to figure out why people do what we do, why use $p$-values, why stuff like that.

**Efron**：我认为我的许多科学家同事都非常擅长概率论；他们可以轻松的进行涉及复杂模型的概率计算，但是他们非常不擅长从数据来逆向推断概率模型可能是什么。我记得第一年进入统计学专业时，我想“这很容易，我已经学过很难的数学了”。但是对我来说，一开始统计学就比任何领域都难。我花了几年时间才觉得舒服一些。很难弄清楚为什么要学我们做的这些事情，为什么使用$p$值，为什么是这样那样的。


You have to do some applications and get some feeling for it. Statistics is the only place where statistical inference is done. We really perform a service. It's backwards thinking. You think from the specific case, back to the general case rather than vice versa. According to the philosophers, that may even be impossible. But we do it everyday.

你必须做一些应用问题，并对它有一些感觉。统计学是唯一进行统计推断的地方。我们真的提供了服务。这是一种逆向思维。你从具体情况出发思考，回到一般情况，而不是相反。根据哲学家的说法，这甚至可能是不可能的。但我们每天都在这么做。

Tibshirani: I arrived at Stanford in 1981, a couple years after you'd invented the bootstrap. Tell us about the thoughts that led up to the bootstrap and how it happened.

**Tibshirani**：我在1981年来到斯坦福大学，就在你发明bootstrap的几年之后。讲讲它的想法，以及它是如何来的。


Efron: The bootstrap illustrates the value of having good colleagues. Rupert Miller had written a paper called "A Trustworthy Jackknife," which was a good attempt to theoretically justify the jackknife. Then Rupert and I were both on sabbatical the same year at Imperial College in 1972, with David Cox, and Rupert gave a talk about the jackknife. David came up to me afterwards and asked: "Do you really think there's anything to this?"'What I realized many years later was that he was giving me a strong hint to work on this. I was asked to give the Rietz lecture in 1977 and I wrote down one line: What is the jackknife an approximation to? As soon as I wrote that line, I essentially was onto the answer. I started out with something really quite elaborate, I call it the combination distribution because I was taking combinations instead of permutations, and then I started to realize I could get rid of some of the machinery, and then I got rid of more of the machinery, and pretty soon there was no machinery. This seemed pretty dull, but I gave the talk and everyone loved it. Since then, I never thought that I was a good judge of what I was working on.

**Efron**：bootstrap恰好说明了拥有好同事的作用。Rupert Miller写了一篇论文“值得信赖的刀切法”(A Trustworthy Jackknife)，尝试从理论上证明Jackknife的合理性。1972年，Rupert和我都在帝国理工学院休假，和David Cox在一起，Rupert做了一个关于Jackknife的演讲。David后来走到我跟前问我：“你真的认为这有什么意义吗？” 多年后，我意识到他给了我一个强烈的暗示，让我去做这个研究。1977年，我被要请去做Rietz讲座，我写下了一句话：Jacknife是在近似什么？当我写下这句话的时候，我实质上已经碰触到答案了。我从一个非常复杂的模型开始，我称之为组合分布，因为我用组合代替排列。然后我开始意识到我可以摆脱一些类似Jackknife中的机械操作，进一步地摆脱了更多，最后就没有任何机械操作了。这看起来很无聊，但我做了演讲并且大家都喜欢。打那以后，我从不认为我能很好地判断我在做什么。

Tibshirani: It was sent to the Annals. What kind of reception did it get?

**Tibshirani**：它被统计年刊(Annals of Statistics)刊登了。受到了什么样的待遇？

Efron: Rupert Miller was the editor of the Annals at the time. I submitted what was the Rietz lecture, and it got turned down. The associate editor, who will remain nameless, said it that didn't have any theorems in it. So, I put some theorems in at the end and put a lot of pressure on Rupert, and he finally published it. Earlier I had been editor of $J A S A$, and this reminded me of a rule I had. When a paper made people angry, you should look at it more closely. Anger-arousing papers divide into a bimodal class. There are the worst papers you ever saw, that was a big class, and a few good ones.

**Efron**：Rupert Miller当时是Annals的主编。我提交了Rietz讲座，但被拒绝了。匿名副主编说，这里面没有任何数学定理。所以，我在最后加入了一些定理，给Rupert施加了很大的压力，他才最终发表了这篇文章。早些时候，我是JASA的主编，这让我想起了我的一条规则。当一篇文章让人生气时，你应该更仔细地看看它。让人愤怒的论文有两种。一种是最差的，但另一种是好的。

And since then I've written a lot of papers. If you think that every paper I submit gets accepted right away, you're wrong. I've had many papers turned down. I usually work really hard on revisions. I try hard to rewrite and take referees seriously, but I'm never discouraged by referees not liking something because sometimes it's because you may have a new idea.

之后，我还写了很多论文。如果你认为我提交的每一篇论文都能马上被接受，那你就错了。我有许多文章被拒了。我通常非常努力地修改。我努力重写并认真对待裁判，但我从不因裁判不喜欢某样东西而气馁，因为有时候这是因为你可能有了新的想法。


Tibshirani: I noticed a curious thing about the bootstrap when I started to give talks after I graduated; it was much harder to give talks to people within our field. When I talked to physicists or chemists, they'd say "Oh yea, that's a simulation, we do that all the time." But as a statistical inference tool, it was much harder to embrace, because it involved random number generation, which was unsettling.

**Tibshirani**：当我毕业后作报告时，我注意到bootstrap有一个奇怪的地方。和我们统计领域内的人交谈它非常困难；但当我与物理学家或化学家交谈时，他们会说“哦，是的，这是一个模拟，我们一直都在这样做。”但作为一种统计推断工具，它更难被接受，它涉及随机数生成，这令人不安。

Morris: What I remember was that it was very timely. We'd been paying $300 an hour to use a computer, and $300 was probably $1000 now. Computers were slow, and to do one of these calculations could take minutes to an hour, so that was a real drawback. The bootstrap just happened to coincide with the beginning of personal computing. We all know now that computation is no big deal, at least costwise it's no big deal, but it's still a big deal conceptually. The bootstrap  was an example where you tried to read the literature, deal with something you knew a little about, the jackknife, and thought up a theory related to it. This approach, to read other people's results and do them one step better, can be very successful. But generally I think it's less fruitful than the approach you said to have been using the last 20 years: get involved in a real problem and pretty soon you start to see things that have never been worked out.


**Morris**：我记得那可真是太及时了。我们花了300美元一小时来使用计算机，而之前的300美元现在可能是1000美元。计算机速度很慢，而进行这些计算可能需要几分钟到一个小时，所以这是一个真正的缺点。bootstrap恰好与个人计算时代相遇。我们现在都知道，计算并不是什么大不了的事，至少从成本上来说，它不是什么大不了的事，但从概念上来说，它仍然是一件大事。bootstrap就是一个例子，你试着阅读文献，处理一些你知之甚少的事情，Jackknife，并想出一个与之相关的理论。这种方法，阅读别人的结果并把他们做得更好，可以非常成功。但总的来说，我认为这种方法比你刚说的过去20年来的做法要差：深入一个真正的问题，很快你就会看到一些从未解决过的问题。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-05.jpg?height=535&width=1053&top_left_y=148&top_left_x=111)

</div>

FIG. 4. SIMS conference photo in front of Old Sequoia Hall, 1974; I'm upper left; some of those pictured: John Tukey, Peter Bloomfield, Paul Switzer, Herb Robbins, Betty Scott, Persi Diaconis, Jerzy Neyman, Ingram Olkin, Yash Mittal and Richard Olshen.

图 4：1974年，旧红杉大厅前的SIMS会议照片；Efron在左上角；照片中的一些人：John Tukey, Peter Bloomfield, Paul Switzer, Herb Robbins, Betty Scott, Persi Diaconis, Jerzy Neyman, Ingram Olkin, Yash Mittal和Richard Olshen。




Efron: I'm a bad reader ab initio, but once I've started working on something, I want to read everything in that area. I find it much easier to read once I've got a foothold in an area and can see why people are doing something. That's the hardest thing when you're writing: telling someone why you're doing something, not what you're doing. Once they understand why you're doing it, there's a good chance they'll be sympathetic.

**Efron**：我一贯就不爱阅读文献，但一旦我开始做某件事，我就想阅尽所有该领域的内容。我发现，当我在某个领域站稳脚跟，并且能够了解人们为什么要做某事，阅读起来就会容易得多。这是你写作时最难的事情：告诉别人你为什么要做这个事，而不是你在做什么。一旦他们明白你为什么这么做，他们很有可能会同情你。


Morris: In the bootstrap case why did you start more from theoretical ideas instead of from a data set in trying to solve the problem?

**Morris**：在bootstrap的例子中，为什么你在试图解决问题时更多地从理论观点出发，而不是从数据集出发？

Efron: It was the fact that a colleague had raised an interesting problem that seemed intuitive to me. An awful lot of literature is dull, basically because it's surprise free. You read it, and from the beginning you know perfectly well what the answer is going to be. Every once in a while you see something that's surprising. I remember the Benjamini-Hochberg [1] result on false discovery rates really surprised me. As soon as I am surprised, then I'll read with a great deal more interest.

**Efron**：当我的同事们提出一个有趣问题的时候，这对我来说似乎很直观。很多文献都很枯燥，基本上是因为它没有出人意料的内容。你读它，一看开头你就非常清楚结尾是什么。偶尔你会看到一些令人惊讶的事情。我记得Benjamini Hochberg[1]关于错误发现率(false discovery rates)的结果真的让我吃惊。一旦我感到惊讶，我就会更加感兴趣地阅读。

Tibshirani: Another thing that makes you unique is that you don't have very many co-authors. We are some of the few people who have written papers with you. You tend to be very individualistic in the way you work.

**Tibshirani**：另一件让你与众不同的事情是你合作者寥寥。我们是少数几个和你一起写论文的人。你的工作方式倾向于个人主义。

Efron: Individualistic is a polite term; Rob may be saying I'm a somewhat difficult co-author. First of all, I don't understand anything, and then when I do understand it, I insist on saying it my way. My attention wanders quickly. One of the wonderful things about statistics is you can look in a lot of different fields. For a person with a short attention span, it's an ideal field because if you get tired of doing biopsy data you can go off to astronomy data. Our field is not very filled in. If you made a picture of mathematics, there'd be a very dense central spot with little spots going out a little bit from the center. If you made a picture of statistics, it would be much more diffuse with many more open spaces in the unknown areas.

**Efron**：个人主义是一个礼貌说法；Rob可能想说，我是个不好合作的人。首先，我什么都不懂，但当我懂的时候，我坚持用我的方式。我的注意力穿梭很快。统计学的奇妙之处之一是你可以研究许多不同的领域。对于一个注意力持续时间很短的人来说，这真是一个理想的领域，因为如果你厌倦了做活检数据，你可以转到天文学数据上去。我们这个领域的人不多。如果你画一幅数学图，会有一个非常密集的中心点，有一些小点从中心向外延伸。如果你画一张统计图，它会更加分散，在未知区域有更多的开放空间。


Morris: I know one other thing the bootstrap did and that was give many statisticians an excuse to have someone buy them a computer, and that changed things. The Bayesians got left behind for a while, but of course later they came up with MCMC, the GemanGeman [3] and Gelfand-Smith [2] papers and suddenly everybody in statistics had a computer.

**Morris**：我知道bootstrap还做了一件事，那就是给了许多统计学家一个理由，让他们买一台电脑，这改变了一切。Bayesian人落后了一段时间。当然，后来他们搞出了MCMC（GemanGeman[3]和Gelfand Smith[2]的文章），突然间人手都有了一台电脑。
 

## BAYES AND EMPIRICAL BAYES

## 贝叶斯和经验贝叶斯


Tibshirani: In 1981, you asked the question: why isn't everyone a Bayesian? Twenty-two years later do you think the proportion of Bayesians among us has increased?

**Tibshirani**：1981年，你问了一个问题：为什么并非每个人都是贝叶斯主义者？22年后，你认为贝叶斯主义者在我们中间的比例增加了吗？

Efron: Yes, I think there's been a growth in the interest in Bayesian statistics, particularly in England. The Royal Statistical Society seems to feature Bayes in every issue. It's for good reasons. One of the good reasons is that Bayesian statistics is different now than it was 20 years ago. It's more realistic and aims toward actually solving problems instead of making philosophical points about why frequentism is wrong. For example, José Bernardo just sent an e-mail announcing a conference on the practical applications of Bayesian statistics. Of course, there's been the computing revolution in Bayesian statistics.



**Efron**：是的，我认为人们对贝叶斯统计的兴趣在增长，特别是在英国。英国皇家统计学会（Royal Statistical Society）似乎每一期中都以贝叶斯为特色。这是有充分理由的。其中一个很好的原因是，贝叶斯统计现在与20年前有所不同。它更现实，旨在实际解决问题，而不是抛出哲学观点，批评频率主义为何错了。例如，José Bernardo刚刚发了一封邮件，宣布召开一次关于贝叶斯统计实际应用的会议。当然，贝叶斯统计还发生了计算革命。


The MCMC kind of Gibbs sampling is a really impressive application. I believe that empirical Bayes is the natural meeting ground between frequentism and Bayesian theory, but that's the theory that hasn't boomed as I hoped it would. The MCMC Bayes kind of theory has a drawback, in that it leads to fairly simple priors being used because those are the ones that work nicely for MCMC. As with all mathematical or computational advances, people choose the path of least resistance. In some sense this conceals the main problem of Bayesian statistics, choosing the prior. The nice thing about empirical Bayes, when used correctly, is it finesses the problem of choosing a prior on a high-dimensional parameter space, which is the essence of the division between Bayesian and frequentist statistics.

MCMC的Gibbs采样是一个非常令人印象深刻的应用。我相信经验贝叶斯理论是频率主义和贝叶斯理论之间的天然结合点，但这一理论并没有像我设想的那样蓬勃发展。MCMC贝叶斯理论有一个缺点，因为它会导致使用相当简单的先验，因为这些先验对MCMC很有效。与所有数学或计算的进步一样，人们选择阻力最小的道路。在某种意义上，这掩盖了贝叶斯统计的主要问题，即选择先验。经验贝叶斯的优点是，如果使用得当，它可以很好地解决在高维参数空间中选择先验的问题，这是贝叶斯统计和频率统计的本质区别。


Morris: As regards empirical Bayes, you think it's an underachiever.

**Morris**：关于经验贝叶斯，你认为它是一个后进生。

Efron: Empirical Bayes is an underachiever only in comparison with things like the Wilcoxon test, which are used billions of times. People do use empirical Bayes ideas or hierarchical modeling more generally, but it really hasn't spread into the applications community. Also, I was thinking in terms of the possible gains, and things like the Wilcoxon test aren't really much of a gain over the t test in experienced hands. But empirical Bayes can surprise even statisticians with how much you can gain in practice. You can easily save 75% or 50% of the risk. So why isn't it used more? The reason is that we're not too confident about the theory and when it applies. Analysis of variance is incredibly useful: it fits so many situations. Part of the reason it's so useful is because Fisher taught scientists that statisticians can handle the analysis of variance very well, so researchers designed experiments with us in mind. If we get good at analyzing empirical Bayes situations and confident about it both in the theoretical and applied sense, then I think experimenters will start designing experiments that will make use of the kind of parallel structure you need for empirical Bayes. Microarrays are a good example of useful parallel structure.

**Efron**：经验贝叶斯只有与Wilcoxon检验相比，才是一个后进生，后者被使用了数十亿次。人们确实比以前更普遍地使用经验贝叶斯思想或分层建模，但它实际上还没有扩散到应用社区。此外，我还考虑了这些方法可能带来的收益，在经验丰富的人手中，Wilcoxon检验和t检验相比，并没有多大收益。但是使用经验贝叶斯在实践中获得的收益甚至会统计学家感到惊讶。你可以很容易地节省75%或50%的风险。那为什么不多用呢？原因是我们对这个理论以及它的应用不太自信。方差分析非常有用：它适用于许多情况。它如此有用的部分原因是因为Fisher教导科学家们，统计学家可以很好地处理方差分析，所以研究人员在设计实验时考虑到了我们。如果我们善于分析经验贝叶斯的情况，并对其在理论和应用上都充满信心，那么我认为实验者将开始设计实验，利用经验贝叶斯所需要的那种并行结构。微阵列是有用的并行结构的一个很好的例子。


Holmes: Isn't there a problem of coherence when doing empirical Bayes? What motivates mixing paradigms, taking a Bayesian viewpoint and then using the data like a frequentist?

**Holmes**：在做经验贝叶斯时，不是存在连贯性(coherence)问题吗？是什么促使混合范式，采取贝叶斯观点，然后像频率学家一样使用数据？

Efron: The coherence question is a Bayesian's answer to optimality. Optimality is what frequentists talk about. Bayesians counter with coherence and say that frequentist theory tends to be incoherent in that it doesn't combine information from different situations in a logical way. And that's a perfectly good criticism, especially if you have to combine some information. There are other attractive things about the Bayesian approach. It's far more aggressively optimistic about modeling than frequentism. Frequentism tends to be quite defensive, trying to avoid making a statement that has a high probability of being wrong. There's a lot I like about Bayesian statistics. What I don't like is slapping on a prior and saying you've got an answer. It's very dangerous, especially in high-dimensional problems.

**Efron**：连贯性问题是贝叶斯对最优性的回应。频率主义者通常会谈论最优性。而贝叶斯主义者则反驳说频率主义理论往往是不连贯的，因为它没有以符合逻辑的方式结合来自不同情况的信息。这是一个非常好的批评，尤其是当你必须结合一些信息的时候。贝叶斯方法还有其他吸引人的地方。它在建模时比频率主义更积极乐观。频率主义倾向于保守，试图避免做出错误概率很高的陈述。贝叶斯统计有很多我喜欢的地方。我不喜欢的是迅速地选择一个先验然后分析一下数据就说你有了答案。这是非常危险的，尤其是在高维问题中。

Bayesian theory is quite impressive when you have a pretty good idea that the prior is at least not harmful. You may have some complicated situation that frequentism gets lost in, like multiple comparisons, and the Bayesian approach then starts saying things that are interesting.

贝叶斯理论令人印象深刻，当你有一个很好的想法，先验至少是无害的。你可能有一些复杂的情况，频率主义会迷失，比如多重比较，贝叶斯方法然后开始说有趣的事情。

Tibshirani: I think another important fact is that people tend to use tools that give them answers when they didn't have any answer before. Robust statistics was very big in the 1960 s, but how much do we use it now? Robust statistics gives a higher quality result in a situation where we already had a result. The bootstrap gives an answer where we had no answer before. That's the kind of tool people are going to use, analysis of variance being a good example. It's a basic tool that gives us an answer to questions that are important, scientifically. 

**Tibshirani**：我认为另一个重要的事实是，人们倾向于使用能帮他们解决之前解决不了的问题的工具。稳健统计在20世纪60年代非常庞大，但我们现在用了多少？在我们已经有结果的情况下，稳健的统计学可以提供更高质量的结果。bootstrap给出了一个以前没有答案的答案。这就是人们将要使用的工具，方差分析就是一个很好的例子。这是一个基本工具，能让我们科学地回答重要的问题。


Efron: It helps that the bootstrap is easy to use and flexible. As time goes by it gets easier and easier to apply. The kind of thing that's hard to use is a theory like "uniform minimum variance unbiased," where you have to think of a new trick for each new case in order to apply it. The things that go like gangbusters are ideas like maximum likelihood estimation, where one algorithm fits all. So maybe what I was trying to say was that empirical Bayes needs to be automated.


**Efron**：bootstrap易于使用而且灵活。随着时间的推移，它变得越来越容易用。很难使用的是像“一致最小方差无偏”这样的理论，你必须为每个新的案例想一个新技巧才能应用它。**而像最大似然估计这样的想法，一种算法包打天下**。所以也许我想说的是经验贝叶斯需要自动化。


Tibshirani: I think the point that Brad is making is that a method has to become semiautomatic before it's going to become widespread. If it takes a Ph.D. in statistics to apply it every time, there just aren't enough of us around to make it a widespread tool.

**Tibshirani**：我认为Brad的观点是，**一种方法只有达到半自动化，才能普及。如果每次都需要统计学博士才能应用它，那么我们周围就没有足够的人来使它成为一种流行的工具。**

Morris: So, for instance, lots of different packages now have methods, for better or worse, that incorporate shrinkage of models. Has that gone far enough, in your mind?

**Morris**：比如说，不管好坏，现在很多不同的软件包都包含了压缩模型的方法。在你看来，这已经足够了吗？

Efron: When you use a Bayes or empirical Bayes estimate, you don't have the safety net of each theta being estimated more or less unbiasedly by its own " $x, "$ as you do in the classical theory. With maximum likelihood estimation, each parameter is estimated in a way that's fairly unbiased. If you use an empirical Bayes estimate, everything gets pulled toward the central bulge. You have to grit your teeth and believe the fact that even though any one estimate may be off, overall you're getting a lot of improvement. That's what we have to get people, including ourselves, to believe.

**Efron**：当你使用贝叶斯或经验贝叶斯估计时，你不会像经典理论中那样，对每个θ的都有它或多或少无偏的估计方法。在最大似然估计中，每个参数都是以一种相当无偏的方式估计的。如果你使用经验贝叶斯估计，一切都被拉向中心隆起的地方。你必须咬紧牙关，相信这样一个事实，即使任何一个估计都可能是错误的，但总的来说，你得到了很大的改善。这就是我们必须让人们，包括我们自己相信的。

Morris: I actually believe they're all improved, not in a frequentist sense, but in the sense that on the basis of information available to you every single one of them is more likely than not to be improved. Of course, later if you tell me the true values, I'll find some are better than others.

**Morris**：事实上，我相信他们都在进步，不是在频率学家的意义上，而是在你可以获得的信息的基础上，他们中的每一个都更有可能得到进步。当然，稍后如果你告诉我真正的值，我会发现有些比其他的更好。


Efron: But you may know, for example, that an usually large parameter value has say 80% chance of being underestimated.

**Efron**：但你应该知道，例如，通常一个较大的参数值会有80%的几率被低估。

Morris: I don't think that at all. If you have both levels of the model right, you're better off after you pull things in. The trick is to know about the second level of the model, which involves exchangeability of the parameters or maybe something more complicated.

**Morris**：我一点也不这么认为。如果你把模型的两个层次都设计对了，在你把数据放进去之后，你会做得更好。其诀窍是你需要了解模型的第二个层次，这里面涉及参数的可交换性，或者更复杂的东西。


Efron: So, as we've written, you have to believe in a relationship between all the parameters. You're testing penicillin and ampicillin and 10 other kinds of antibiotics, you have an estimate for each one, and you have to believe that all the data has some implications for penicillin, not just the penicillin data. 

**Efron**：所以，正如我们所写的，你必须相信所有参数之间的关系。你正在测试青霉素、氨苄西林和其他10种抗生素，你对每种抗生素都有一个估计，你必须相信所有的数据都包含一定的关于青霉素的信息和知识，而不仅仅是青霉素数据。

Morris: You have to decide a priori whether you're willing to combine estimates; the data is supposed to decide whether you can do much shrinkage. For example, in looking at data on hospitals, I tend to shrink VA hospitals who are doing a bunch of similar procedures. There are about 160 of them. I believe that the information that's in one has some relevance to the others. I don't know how much, but the data helps me decide.

**Morris**：你必须先验地决定是否愿意合并估计；数据应该决定你是否可以做很多收缩 (shrinkage)。例如，在查看有关医院的数据时，我倾向于合并并压缩正在进行一系列类似程序的弗吉尼亚州医院的数据，大约有160个。我相信其中的信息与其他信息有一定的相关性。我不知道有多少，但数据可以帮我决定。



Efron: But if you went to the hospital with the best score and told them you were shrinking their data down because you were pretty sure some of it was luck, they might not agree with you.

**Efron**：但是如果你带着最好的分数去医院，告诉他们你正在缩小他们的数据，因为你非常确定其中只有一些数据是幸运儿，他们可能不会同意你。

Morris: They wouldn't like it. But I'd be right, more often than not. ... It's also very hard to teach these ideas in a first course, and many of the users out there haven't had more than a first course.

**Morris**：他们不会喜欢的。但我是对的，很多时候……在第一门课程中教授这些想法也是非常困难的，很多用户只上过第一门课程。

Efron: Well, I think the serious point is that 20 thcentury statistics mainly taught us to treat each parameter in its own right, essentially try to estimate it without bias, or to test it with an unbiased estimate. Twentyfirst century may have to undo that. You'll have to accept that you're not going to have that safeguard.

**Efron**：嗯，我认为重要的一点是，20世纪的统计学主要教会我们如何正确对待每一个参数，基本上是试图无偏地估计它，或者用无偏的估计来检验它。21世纪可能不得不扭转这种局面。你必须接受你没有那个无偏的保障。


Tibshirani: You also made a point before, that scientists ask us the kind of question that we teach them to ask. For example, they ask us for a t test because that's what they think we can do. Sometimes I think that's all they think we can do. As they learn more about statistical science, if we can treat parallel problems well with empirical Bayes, then we'll get asked that question more often.

**Tibshirani**：你之前也说过，科学家问我们的问题是我们教他们去问的。例如，他们要求我们进行t检验，因为他们认为我们可以这样做。有时候我认为这就是他们认为我们能做的。随着他们学习更多关于统计科学的知识，如果我们能在经验贝叶斯中很好地处理并行问题，那么我们会更经常地被问到这个问题。

Morris: So, we might try teaching our beginning courses a different way. For example, if we teach people who will never be statisticians, we ought to teach them what statistics can do. What kinds of problems come up, and when they should hire a statistician. They might like our courses better, too, because they'll see they have something to do with what they need to know; not just some sort of torture semester.

**Morris**：所以，我们可能会尝试用不同的方式来教授我们的初级课程。例如，如果我们教那些永远不会成为统计学家的人，我们应该教他们统计学能做什么。出现什么问题，他们什么时候应该聘请统计学家。他们可能也更喜欢我们的课程，因为他们会看到他们需要知道的东西，而不仅仅是饱受折磨。


Efron: Right now, we teach pretty much historically. We start out at the beginning of the 20 th century with normal theory methods and work up to more complicated parametric methods. Then maybe into the third quarter, you get to nonparametric methods. If the field had developed in the other direction, if computers had been available before the mathematics, we'd probably start with nonparametrics, which are basically simpler and easier to explain. Then we'd get to that terribly tough stuff, the t tests, and the normal theory near the end. 

**Efron**：现在，我们的教学内容历史悠远。我们从20世纪初开始使用常规的理论方法，然后发展到更复杂的参数方法。也许到了第三季，你才会用到非参数方法。假设时光倒流，计算机在数学出现之前就已经存在，那我们可能会从非参数开始，非参数基本上更简单，更容易解释。然后我们将进入非常困难的东西，t检验，再后来正态理论。


Morris: What we do now is like teaching someone to drive a car by starting with an explanation of how a Model $\mathrm{T}$ engine works. All they want to do is drive.


**Morris**：我们现在所做的就像是从解释T型发动机的工作原理开始教人开车。但大家只想学开车。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-08.jpg?height=351&width=507&top_left_y=150&top_left_x=109)

FIG. 5 Induction into the National Academy of Science; signing the Big Book.

图5：入选美国科学院；在这本大书上签名。

</div>


## FISHER AND OTHER INFLUENCES

## Fisher和其他影响

Tibshirani: You talked a lot about Fisher who is one of your intellectual heroes. Who else in the last 50 years has had an influence on you?

**Tibshirani**：你谈了很多关于Fisher的事，他是你的智慧英雄之一。在过去的50年里，还有谁对你有影响？

Efron: Fisher should be everybody's hero because we were incredibly lucky to get a mentality of that level in our field. It's hard to say hero; there are people in this field that I admire very much for both their mind and their work: Neyman, Hotelling and Rupert Miller. If I look to see who has most influenced my work and judge heroism that way: Charles Stein, who I also admire very much, and Herb Robbins.

**Efron**：Fisher应该是每个人的英雄，因为我们非常幸运，在我们的领域有这样高超的思想力。我非常钦佩Neyman、Hotelling和Rupert Miller的思想和工作，但难以界定是否是英雄。如果说看谁对我的工作影响最大，并以此标准来评判英雄，那就是：Charles Stein，我也非常钦佩他，还有Herb Robbins。



Tibshirani: How about David Cox?

**Tibshirani**： David Cox呢？

Efron: Very much so, and without any close personal contact or anything like that. As an example of clear thinking on inference, I don't think you can do any better than Cox, who embodies the Fisher tradition. It's hard to see how Fisherianism is doing these days; there isn't another Cox in sight at that level. I hope it's not fading, because that's a wonderful tradition that's very well attuned to the community that does practical statistical inference.

**Efron**：非常好，但我和他没有亲密接触。作为一个清晰地思考统计推断的典范，我不认为谁能比Cox做得更好，Cox体现了Fisher的传统。现在很难看出Fisher主义是如何发展的；在这个水平上看不到另一个Cox。我希望它不会消失，因为这是一个非常好的传统，很好地适应了做实际统计推断的社区。


Morris: That's an amazing statement. I haven't heard you say that we don't have another David Cox coming.

**Morris**：这真是一个惊人的声明。我没听你说我们不会再有David Cox了。

Efron: I'm not sure of that; I'm too close to the time to say that for sure. The Fisherian heritage comes mainly out of England. It's just a wonderful way of looking at statistics that really isn't either frequentist or Bayesian. It's got of spirit of compromise and "give" in it, and also a lot of algorithmic wiseness, and l don't see that wisdom as active these days even in its English homeland.

**Efron**：我不确定；我离这个时间太近了，不能特别肯定。Fisher传统主要来自英格兰。这是一种很好的统计方法，它既不是频率学派，也不是贝叶斯学派。它有妥协和“给予”(given)的精神，也有很多算法的智慧，即使在它的英国本土，我也不认为这种智慧还在。


Morris: Well, we've hired them all away to the U.S.

**Morris**：嗯，我们把他们都雇到美国去了。

Efron: The U.S has not been a very friendly ground for Fisherian thinking. It's been a predominantly frequentist preserve, and what might be considered beyond-frequentist thinking, the kind of philosophically atheistic approval that goes under the machinelearning rubric. People forget that Tukey and Mosteller wrote a book together, the famous green book, where there's no probability, let alone, any theory of inference.

**Efron**：对Fisher学派思维，美国并不是一个非常友好的地方。这是频率学派的保护区，在这之外，还有一种哲学上无神论的认可——属于机器学习的范畴。人们忘记了Tukey和Mosteller一起写了一本书，著名的绿皮书，书中没有概率，更不用说任何推断理论了。

Morris: It seems to me that the Fisher couldn't have been Fisher, even as brilliant as he was, without being involved in real problems. He was a great geneticist, but he also worked in agriculture and developed experimental design. I think there are people doing that now, but I' $m$ worried about the loss of the theoretical side.

**Morris**：在我看来，如果不深入到真正的问题，即使强如Fisher复活过来，也决不可能成为Fisher。他是一位伟大的遗传学家，但他也从事农业工作，并开发了实验设计。我认为现在有人这样做，但我担心理论方面的损失。


Tibshirani: I'm worried about the loss of models. What Tukey really did in the 1960 s was say that we don't need models any more. I think he swung the pendulum too far with exploratory data analysis. Now similar things are happening in machine learning, where people act as if all we need are these fast algorithms that are accurate, and we don't need a model. I believe that to understand how an algorithm works, you need to know what model it's fitting. I think that's a very fertile area; I believe the core of our field is modeling.


**Tibshirani**：我担心模型的消减。Tukey在20世纪60年代真正做的是，他说我们不再需要模型了。我认为他用探索性数据分析把钟摆摆得太远了。现在类似的事情正在机器学习中发生，人们表现得好像我们只需要这些准确的快速算法，不再需要模型。我相信要理解一个算法是如何工作的，你需要知道它适合什么模型。我认为这是一个非常肥沃的领域；我相信我们领域的核心是建模。

## MODELS AND COMPUTATION

## 模型与计算

Morris: The deeper science may be in the model itself. Even if it's wrong, somebody also may be able to use it next year to get something better.

**Morris**：更深层次的科学可能在模型本身。即使它是错误的，也有人可能在明年用它来得到更好的东西。

Efron: The concept of models is very closely tied to the concept of optimality. You can't really talk about optimality until you have a model. Though the machine-learning people are not very interested in optimality right now, in the long run there's no science unless you bring it back into that theory. I, too, hope that models come back. They're easy to criticize because people overdo them.

**Efron**：模型的概念与最优性的概念紧密相连。除非你有一个模型，否则你不能真正谈论最优性。虽然机器学习的人现在对最优性不太感兴趣，但从长远来看，除非你找回它的理论，否则就没有科学。我也希望模型回来。它们很容易受到批评，因为人们做得泛滥成灾了。


Morris: Rob, I hear you defending models, but I think you're more nonparametric than I am, yet you're regretting the loss of models?

**Morris**：Rob，我听说你在为模型辩护，但我认为你比我更非参，而你却对失去模型感到遗憾？

Tibshirani: The models can be more adventurous, they don't have to be simple linear models. You should always have a model in mind so that you know what's the best you can do in a given setting. Because to know when a method fails, you have to know what is the ideal method. Then you can move further and say, "here's a case where it won't work." To understand operating characteristics, I believe you need models.

**Tibshirani**：模型可以更具冒险性，它们不必是简单的线性模型。你应该时刻记住一个模型，这样你就知道在给定的环境下你能做的最好的事情是什么。因为要知道一种方法何时失败，你必须知道什么是理想的方法。然后你可以进一步说，“这是一个行不通的情况。” 为了理解原理和性质，我相信你需要模型。


<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-09.jpg?height=624&width=899&top_left_y=148&top_left_x=187)

FIG. $6 .$ Honorary doctorate, University of Chicago Faculty, $1996 .$

图 6：芝加哥大学医学院名誉博士学位，1996。

</div>



Morris: I think a model is usually an oversimplification, hopefully not too much of one.

**Morris**：我认为模型通常是过于简单化的，希望不会太简单。

Efron: Probability itself is a tremendous simplification. You have a lot of things happening that are unexplainable and noisy. The idea of probability simplifies the noise immensely, and then the model for the probability simplifies things further.

**Efron**：概率本身就是一个极大的简化。有很多无法解释、嘈杂的事情发生。概率的概念极大地简化了噪声，然后概率模型进一步简化了事情。

Getting our little brains around a complicated world, let alone being able to manipulate it and predict from it, is a tremendous task, and you need all the help you can get. The fact that now you have a big computer that can do any calculation you want is certainly a big help.

让我们的小脑袋在一个复杂的世界里转来转去，更不用说能够操纵它并从中预测了，这是一项艰巨的任务，你需要所有你能得到的帮助。现在，你有高效的计算机，可以做任何你想要的计算，这无疑是一个很大的帮助。

I once gave a talk to the American Mathematical Society. The first thing I noticed was that everyone was incredibly old (that's when I wasn't old). I started out by asking what would happen in mathematics if somebody invented an infinitely fast computer? So you could bring it home and take it out of the box and by noon you could settle the Riemann hypothesis or Goldbach's conjecture. And I asked, "Would this be the end of math?" And then when they were looking really worried, I answered my own question, "No, it wouldn't be the end of math, people would just start using the machines to answer even harder questions." Something like this has happened in statistics. We can answer the old questions that used to be too hard, almost any of them; does that mean our field is history? No, we've just started asking more realistic questions. In fact, there are more statisticians now, and statistics has become a more important scientific field.

我曾经给美国数学学会做过一次演讲。我注意到的第一件事是每个人都非常之老（那时我还不老）。我一开始问，如果有人发明了速度无限快的计算机，数学会发生什么？然后，你可以把它带回家，从盒子里拿出来，到中午你就可以解决黎曼假设或哥德巴赫猜想。我问，“这会是数学的终结吗？”然后当他们看起来很担心的时候，我回答了我自己的问题，“不，这不会是数学的终结，人们会开始使用机器来回答更难的问题。”类似的事情在统计中发生过。我们可以回答过去的一大堆老大难问题；这是否意味着我们的领域是历史？不，我们刚开始问更现实的问题。事实上，现在有了更多的统计学家，统计学已经成为一个更重要的科学领域。

Tibshirani: Speaking of getting incredibly old, a lot of statisticians, when they hit 60 or 65 , start to do philosophy. They find a grand unified theory of everything, but you haven't done that. You seem to still work on smaller problems, but real applied problems. Is that a conscious decision?

**Tibshirani**：说到变老，很多统计学家，当他们60岁或65岁时，开始研究哲学。他们找到了一个关于一切的大统一理论，但你没有做这一点。你似乎仍然在研究较小问题，但的确是真正的应用问题。这是一个有特意的决定吗？


Efron: I usually don't think about such things, but when I was 60 , a morbid date, I started thinking, "My plan has been no plan so far; I just work on whatever is fun that comes along, whatever colleague seems interesting, whatever paper seems interesting. Maybe I really ought to concentrate on trying to do one big thing." But after I thought about it I found I couldn't possibly follow that advice. There's no way you can just sit down and do a "big thing," or at least I can't. So, I just went back to doing lots of little things, and hoping that some of them will turn out okay. Statistics is a wonderfully forgiving field, you don't have to be the brightest person in the world or work day and night; all you have to do is get an idea and keep at it. Like I said, most of the field is not densely filled. And so I keep working on little problems.

**Efron**：我通常不会考虑这些事情，但当我真到了60花甲之时。我开始想，“我的计划到目前为止，还是没有计划；我做任何有趣的事情，任何看起来有趣的同事，任何看起来有趣的论文 。也许我真的应该集中精力做一件大事。”但是我想了想，我发现我不可能听从这个建议。我们不可能坐下来做一件“大事”，至少我不能。所以，我又回去做了很多小事情，希望其中一些事情会好起来。统计学是一个非常宽容的领域，你不必是世界上最聪明的人，也不必日夜工作；你所要做的就是想出一个主意并坚持下去。就像我说的，这个领域的大部分都不那么卷。所以我一直在解决一些小问题。


## STATISTICS AND SCIENCE

## 统计与科学

Tibshirani: One of the challenges I've found is that we're a funny field in a sense that lots of other people who aren't statisticians do statistics. We don't do chemistry or biology; we don't go into a lab and start filling up test tubes. Statistics is something you can do if you have a personal computer. So, it's a challenge in the sense that a lot of people think they can do it well, but aren't. We not only have to do good statistics, but also spread the word to other sciences about the right way to do things.

**Tibshirani**：我发现的一个挑战是，从某种意义上说，我们是一个有趣的领域，很多其他非统计学家的人都做统计。我们不做化学或生物；我们不会进入实验室，开始填充试管。如果你有一台电脑，就能做统计了。所以，从某种意义上说，这是一个挑战，很多人认为他们能做好，但事实并非如此。我们不仅要做好统计工作，还要向其他科学传播做事的正确方法。

Morris: So, statistics has to be fundamentally interdisciplinary, if it's going to survive.

**Morris**：所以，如果统计要生存下去，就必须从根本上讲是跨学科的。

I want to make sure we save some time to talk about another topic that you have a real perspective on. I understand you've had some administrative positions at Stanford that have let you take a bigger view of the role of statistics. Stanford has just been marvelous; you have a very strong department and very strong university, with interdisciplinary appointments. Why should we try to preserve statistics departments? I'm sure stats will survive; what can we do to keep the departments healthy and the field strong?

我想确保我们节省一些时间来讨论另一个你有真正观点的话题。据我所知，你俩在斯坦福大学担任过一些行政职务，这让你们对统计的作用有了更多的认识。斯坦福大学真是太棒了；你们有一个非常强的系和非常强的大学，有跨学科的任命。我们为何要保留统计系？我相信统计系会继续存在；我们能做些什么来保持统计系各个部门的健康和该领域的强大？


Efron: I was Associate Dean for a while, which is described by one of my colleagues as a mouse training to become a rat. I was the Associate Dean for science. It was really quite an interesting experience. It's not easy doing these things, but statisticians have quite an advantage in the dean's office because we deal with lots of different fields, while most other academics deal only with their own field. Statisticians are very good at comparing things, which is what deans do a lot. Sometimes you can't say whether A or B is good, but you can say whether A is better than B. I spent a lot of time talking to other scientists. They're wonderful, but I wound up feeling that statistics was a very fortunate field. First of all, we're sort of small and not overhyped in the press; we're not under tremendous pressure to raise money. Biologists and chemists are under a lot of pressure to keep big labs going, because that's the only way you can do the science. You can buy a computer pretty cheaply these days, and you don't even have to buy one if you want to work in the classic tradition. Statisticians are nice to each other. Some fields are horribly competitive. Because statistics doesn't have huge prizes or a lot of publicity, people are pretty good to each other. We tend to argue a lot, but basically we like other statisticians, and we praise each other's work, in our hearts at least if not in the pages of our journals. I came happily back to statistics, hoping our little department would continue to do well. As we said before, stat departments are the only place in the world where inference is seriously studied. If statistics departments stop, people will be able to keep doing the stuff we have done, but there wouldn't be any new inferential ideas until another Fisher comes along. You said Fisher wasn't a statistician; it was almost impossible to be a statistician until Fisher.

**Efron**：我做过一段时间的副院长，我的一个同事把这描述为一只老鼠训练成一只耗子。我是理学院副院长。这真的是一段非常有趣的经历。做这些事情并不容易，但是统计学家在院长办公室有相当大的优势，因为我们处理许多不同领域的问题，而大多数其他学者只处理他们自己领域的。统计学家非常擅长比较事物，这是院长经常做的事情。有时候你不能说A或B是好的，但是你可以说A是否比B好。我花了很多时间和其他科学家交谈。它们很棒，但我最终觉得统计学是一个非常幸运的领域。首先，我们比较小，在媒体上没有过度炒作；我们没有筹集资金的巨大压力。生物学家和化学家承受着很大的压力来维持大实验室的运转，因为这是你做此类科学的唯一方法。对我们来说，你可以很便宜地买一台计算机，如果你想按照传统方式工作，你甚至不需要买。统计学家们彼此很友好。有些领域竞争非常激烈。因为统计学没有大奖或大量宣传，人们彼此友善。我们常常争论不休，但基本上我们喜欢其他统计学家，我们会表扬彼此的工作，即使不是在期刊上，至少也会在心里表扬。我很高兴地回到统计系，希望我们的小部门能继续做得很好。正如我们之前所说，统计系是世界上唯一严肃地研究推断的地方。如果统计系没了，人们将能够继续做我们已经做过的一些事情，但在另一个Fisher出现之前，不会有任何新的推断思想。你说过Fisher不是纯统计学家；但在Fisher之前，几乎没人能成为统计学家。

Tibshirani: Are you optimistic about our field?

**Tibshirani**：你对我们统计领域乐观吗？

Efron: Yes, and I'm not one of these cheerfully optimistic people about everything. It seems to me that if you look at statistics over the 20th century, it's a steadily rising curve. It's easy to underestimate how much effect we've had, but no other field has taken over dozens of other fields as the main way of doing science.

**Efron**：是的，我不是那种对一切都乐观的人。如果你看看20世纪的统计学，这是一条稳步上升的曲线。**我们很容易低估我们的影响有多大，但是没有其他领域像统计这样取代了其他几十个领域作为做科学的主要方式**。

Statistics is a 20 th century phenomenon; its modern history starts almost exactly in 1901 with Pearson and Biometrika. At first, there were hardly any statisticians and then gradually more and more fields start using statistics as a means of communication. The way medicine does now: Did you run a clinical trial? Was it randomized? Was it blinded? What was your significance level? That's a tremendous step forward from the case history method, the way they used to run medical experiments: "I saw a patient and I gave him nitroglycerin and he felt a lot better." Field after field has started relying on statistical methodology. Of course, it particularly suits fields where no one bit of data is definitive. You ask one person if he's for the Democrats or Republicans and it doesn't matter. But if you ask a thousand people, then you have a useful poll. The hard sciences were the most resistant to statistics because they didn't need it. Their information came in hard units. You make the measurement and sure enough Einstein's theory will predict the shift of light better than Newtonian theory.

统计学是一个20世纪的现象；它的现代历史几乎完全始于1901年的Pearson和Biometrika。起初，几乎没有任何统计学家，后来越来越多的领域开始使用统计学作为交流手段。现在医学的做法是：你进行过临床试验吗？是随机的吗？它是双盲的吗？你的显著性水平是多少？这与病史方法相比是一个巨大的进步，病史方法是他们过去进行医学实验的方法：“我看到一个病人，我给他硝化甘油，他感觉好多了。”一个又一个领域都已经开始依赖统计方法。当然，它特别适合于数据有随机性的领域。你问一个人他是支持民主党还是共和党，这无关紧要。但是如果你问一千人，你会得到一个有用的民意测验。硬科学是最抵制统计的，因为他们不需要统计。他们的信息以硬单位提供。你进行了测量，并且确信爱因斯坦的理论比牛顿理论更能预测光的移动。


Morris: Well, yes, we handle applications differently than math. Math used to say, "This applies to some field like physics." I hope we continue to value all these different connections and value the people who can make those connections.

**Morris**：嗯，是的，我们搞应用的方式不同于数学。数学过去常说，“这适用于物理等领域。”我希望我们继续重视所有这些不同的联系，并重视能够建立这些联系的人。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-11.jpg?height=336&width=505&top_left_y=150&top_left_x=111)

FIG. 7. Last day in my old Sequoia Hall office, 1998。

图 7：1998年，在我的老红杉厅办公室的最后一天。
</div>

Efron: One thing I've been thinking might happen, from experience around Stanford; we're used to having biostatistics departments as well as statistics departments. Maybe there'll be astrostatistics departments or geostatistics departments springing up. Those fields are starting to use statistics more. In physics they used to have $10^{26}$ particles for any experiment, and no one needed statistics. But when you get down to situations where you're looking at 10 or 100 new particles, suddenly inferential efficiency becomes important. In fact, next fall there'll be a Physics and Statistics conference at the Stanford Linear Accelerator Center.

**Efron**：根据斯坦福大学的经验，我一直认为可能会发生一件事；**我们习惯于有生物统计系和统计系。也许会有天文统计系或地质统计系涌现出来。这些领域开始更多地使用统计学**。在物理学中，之前的任何实验都需要$10^{26}$个粒子，没有人需要统计学。但当你开始观察10或100种新粒子时，推断效率突然变得很重要。事实上，明年秋天将在斯坦福直线加速器中心举行物理和统计学会议。


Tibshirani: Another example is DNA microarrays. In a lot of genetic areas you don't need a statistician to tell you that there's a huge effect. But if you're looking for 6000 possible effects, you need statistical help to sort the signal from the noise.

**Tibshirani**：另一个例子是DNA微阵列。在许多遗传领域，不需要统计学家来告诉你这有巨大的影响。但是如果你在寻找6000种可能的影响，你需要统计帮助来从噪音中找到信号。


Morris: To summarize a couple of points here, I think the world would be set back if we didn't have statistics departments. The statistics department is the way we reach out and communicate and have interdisciplinary connections with other fields. It's also a lot of the fun. I think we'll get people who love to do that, and not everybody has to do it all. But a statistics department can facilitate the infusion of good statistical methods into many fields. We have to take it seriously; we have to get staff and faculty and students who want to do that. If we isolate ourselves trying to show off for each other, and not for anybody else, we'll ruin the interdisciplinary connections.

**Morris**：总结几点，我认为如果没有统计系，世界将会倒退。统计系是我们联系和沟通的方式，与其他领域有着跨学科的联系。这也很有趣。我想我们会找到喜欢这样做的人，而不是每个人都必须这样做。但是，**统计系可以促进将良好的统计方法注入许多领域**。我们必须认真对待它；我们必须让员工、教师和学生都愿意这样做。如果我们孤立自己，试图为彼此炫耀，而不是为其他任何人炫耀，我们将破坏跨学科的联系。

## FUTURE DIRECTIONS

Efron: In academia, and in industry and government, but especially academia, ideas are the coin of the realm. What we really have to do is keep coming up with good ideas. Our record has been pretty good; every few years there's a really useful idea that comes out of statistics. If we keep that up, there won't be any worry about the future of stat departments.

**Efron**：在学术界、工业界和政府界，尤其是学术界，思想是这个领域的硬通货。我们真正要做的是不断想出好主意。我们的历史表现相当好；每隔几年，就会有一个真正有用的想法从统计中产生。如果我们保持这种状态，就不会担心统计系的未来。


Holmes: You've just become president-elect of the ASA. Do you have any particular directions that you would like to see statisticians go as a group?

**Holmes**：你刚刚成为美国统计学会的当选主席。你有没有什么特别的方向，希望看到统计学家作为一个群体去做？

Efron: The people at the ASA asked me that very question. It's a nice tradition for the president to set a theme for the Joint Statistical Meetings. My chosen theme, after some introspection, was "Statistics as a Unified Discipline." Of course, no one would worry about "Physics as a Unified Discipline" or "Astronomy as a Unified Discipline," but they have the advantage of millennium-long traditions and clearly defined subject matter. Statistics is pretty much a one- or two-century field, with a subject matter, "inference," that doesn't even occur in natural science. There are terrific centrifugal forces in stat because we work on so many fronts and there aren't that many of us. It's easy to imagine the field disintegrating into mathstatisticians, drug company statisticians, survival analysts, sample surveyors, etc.

**Efron**：美国统计学会的人问了我这个问题。主席为联合统计会议设定主题是一个很好的传统。经过一番反思，我选择的主题是“统计学作为一门统一的学科”。当然，没有人会担心“物理学作为一门统一的学科”或“天文学作为一门统一的学科”，但它们有着千年悠久的传统和明确定义的主题。统计学几乎是一个一两个世纪的领域，其主题是“推断”，而这在自然科学中根本不存在。**统计中存在着巨大的离心力，因为我们在这么多战线上工作，而我们中的人并不多。很容易想象这个领域会分裂成数理统计学家、制药公司统计学家、生存分析师、抽样调查专家等等**。


In my campaign blurb for the ASA, I spoke, only semi-jokingly, about "inreach." I was flattered and pleased when they asked me to run for president, maybe because West Coast academic statisticians haven't been a big part of the ASA, gravitating toward the IMS instead. I'm glad we have more than one statistics organization, but the ASA is our umbrella. I'd like people in the Berkeley and Stanford and Chicago and Seattle departments to feel that they're in the same field as statisticians at Merck, Pfizer, DOE, Prudential, etc.

在我为美国统计学会所做的竞选宣传中，我半开玩笑地谈到了“另请高明”。当他们要求我竞选主席时，我感到既高兴又受宠若惊，也许是因为西海岸的学术统计学家并不是美国统计学会的重要组成部分，而是被国际数理统计学会(IMS)吸引。我很高兴我们有不止一个统计机构，但美国统计学会是我们的呵护伞。我希望伯克利、斯坦福、芝加哥和西雅图等部门的人能感觉到他们与默克、辉瑞、能源部、保诚等公司的统计学家处于同一个领域。


I'm glad we have lots of different areas statisticians work on. It gives us an extended frontier with other scientists. Statistics has a great record of getting important ideas from people outside the field, maybe even Fisher being an example, Wilcoxon for certain. The trick is to maintain a strong center to the field while remaining open to problems and ideas from the outside. Getting back to the ASA, it has the advantage of bigness and tradition. On the wall of the ASA office are beautiful hand-written minutes from a meeting in 1839 . (They seemed worried about getting more members.) They also have JASA, a wonderful journal that attracts an enormous range of contributions, and the Joint Statistical Meetings, which attract an enormous number of participants.

**我很高兴我们有许多统计学家从事的不同领域。这为我们拓宽了边界，与其他科学家站在一起**。统计有一个伟大的记录，从其他领域的人获得重要的想法。甚至Fisher可能就是一个例子，Wilcoxon肯定是。诀窍是保持一个强大的领域中心，同时对外界的问题和想法保持开放。回到美国统计学会，它有着巨大和传统的优势。在美国统计学会办公室的墙上，是写于1839年的一次会议的漂亮的手写会议记录。（他们似乎担心会有更多的成员。）他们还有JASA，这是一本精彩的杂志，吸引了大量的贡献，还有联合统计会议(JSM)，吸引了大量的参会者。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-12.jpg?height=520&width=766&top_left_y=148&top_left_x=254)

FIG. $8 .$ Academica Sinica, $1997 .$

图 8：中国台湾科学院，1997年。
</div>

## ADVICE AND CONCERNS

## 建议和关切

Holmes: When you're talking about students that come to us, what do you think is the best possible training for a student coming to statistics? 

**Holmes**：当你谈到来到我们这里的学生时，你认为对一个来统计系的学生来说，最好的训练是什么？


Efron: What does it take to do well in statistics? You have to be good at a certain amount of mathematics; you have to really love numbers or else you simply won't put up with the amount of numerical trouble we have to go through. Not very many mathematicians love numbers. They tend to avoid them. If you look at a math journal, numbers are few and far between. A little bit of science certainly helps because scientific inference is our subject matter. People can come from lots of different backgrounds. The traditional math background is by itself not optimal. We spend a lot of our time retraining our students who have a more mathematical background to be less axiomatic and less precise and, instead, view problems more in the spirit that suits statistical inference. You have to find the right degree of accuracy for your problem.

**Efron**：怎样才能在统计学方面取得好成绩？你必须精通一些数学；你必须真正热爱数据，否则你就无法忍受我们要经历的数据麻烦。没有多少数学家喜欢数据。他们倾向于回避它们。如果你看一本数学杂志，数据很少。一些科学知识当然会有帮助，因为科学推断是我们的主题。人们可以来自不同的背景。传统的数学背景本身并不是最佳的。我们花了大量时间重新训练那些数学背景更丰富的学生，使他们变得不那么公理化和不那么追求精确；相反，用更适合统计推断的精神来看待问题。你必须为你的问题找到合适的准确度。


Tibshirani: Today we need students who are better at programming.

**Tibshirani**：今天我们需要编程能力更强的学生。

Efron: That's certainly helpful since it's our main piece of equipment. You wouldn't want a biology student who didn't know how to work a pipette. I like it now that we have some students who are from physics or biology. They have a lot to offer to statistics. Maybe they approach problems in a different way. The one with math training is that it's not great for general science purposes. You have to have some feeling for sciences and scientists. Astronomers have stars, geologists have rocks, we have science-it's the raw material statisticians work from. Just getting started on a data analysis can be very hard. You have a huge set of data sitting there. What do I do first? Sometimes doing even a little statistics can be helpful. I work a lot with bioscientists now, as everyone in this room does. And you know that they have a way of approaching complicated problems, which isn't true pure math. Good statisticians help them think in a logical, clear way.

**Efron**：这当然很有帮助，因为这是我们的主要设备。你不会想要一个不知道如何使用移液管的生物系学生。我喜欢现在我们有一些物理或生物专业的学生。他们对统计有很多贡献。也许他们以不同的方式处理问题。数学训练的一个问题是，它不太适合一般科学目的。你必须对科学和科学家有一些感觉。天文学家有恒星，地质学家有岩石，我们有科学，这是统计学家工作的原材料。刚开始数据分析可能非常困难。这里有大量的数据。我先做什么？有时做一点统计也会有帮助。我现在和生物科学家们一起工作，就像这个房间里的每个人一样。你知道他们有一种处理复杂问题的方法，这不是真正的纯数学。优秀的统计学家帮助他们以逻辑清晰的方式思考问题。


Holmes: Sometimes the scientists accuse us of trying to give them the right answer when they want a simple answer. They'd be prepared for a bigger level of approximation.

**Holmes**：有时科学家们指责我们试图给他们一个正确的答案，而他们想要一个简单的答案。他们会为更大程度的近似做好准备。

Efron: What we consider right, they consider confusing. Sometimes they're correct and it is confusing. I remember one of my real failures as a consultant involved a good woman scientist who brought me a big binomial experiment with lots of factors. I explained it all carefully in terms of logistic regressions. She just couldn't think of logits as an answer at all and ended up throwing my stuff away and publishing simple percentages, which for her audience was probably right. For her it was right. I always wished I'd made more of an attempt to communicate. I could have easily restated my results in terms of percentages; I think that would have been enough. Since then I've been careful about trying to write communications to my clients or collaborators in reasonable language, or at least reasonably like what they're used to thinking in. Not that I can always do that. Sometimes it involves knowing more science than I do.


**Efron**：我们认为正确的东西，他们认为令人困惑。有时他们是正确的，这令人困惑。我记得作为一名顾问，我真正的失败之处在于一位优秀的女科学家给我带来了一个包含许多因素的大型二项式实验。我用逻辑回归仔细解释了这一切。她根本不把logits作为答案，最后把我的东西扔掉，公布了简单的百分比，对她的观众来说，这可能是对的。对她来说，这是对的。我一直希望我能多尝试交流。我可以很容易地用百分比来重申我的结果；我想这就足够了。从那以后，我一直小心翼翼地尝试用合理的语言给我的客户或合作者写通信，或者至少合理地喜欢他们习惯的想法。并不是说我总是能做到这一点。有时它涉及到我不了解的科学。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-13.jpg?height=338&width=505&top_left_y=150&top_left_x=111)

FIG. $9 .$ A Stanford party: Jun Liu, Charles Stein, Efron and Persi Diaconis.

图 9：斯坦福大学的聚会: 刘军, Charles Stein, Efron and Persi Diaconis.
</div>


That brings up an interesting question: How much of the science should you know as a collaboratoring statistician? There are different answers to that. The answer that "the more you know the better" isn't necessarily true. Because if you know too much, you get close to it and you start thinking you're the scientist. Some people are really good at educating themselves quickly on the essence of a subject. But if you have to be a biologist to help biologists with statistics, then there is no stat, there are just biologists who are better at numbers. I strongly feel there's an essence to statistical reasoning that cuts across fields. And that's what we train in. But, of course, we also like people to be good at helping with specific fields, maybe very knowledgeable, which leads to a different model of the collaborating statistician. 

这就引出了一个有趣的问题：作为一名与人合作的统计学家，你应该了解多少科学知识？对此有不同的答案。“你知道的越多越好”的答案不一定正确。因为如果你知道的太多，你就会接近它，你会开始认为你是科学家。有些人真的很擅长快速自学了解一门学科。但是，如果你必须成为一名生物学家来帮助生物学家进行统计，那么就没有统计学了，只有擅长数字的生物学家。我强烈地感觉到统计推断的本质是跨领域的。这就是我们训练的内容。但是，我们当然也赞赏统计学家们在特定领域问题上能提供帮助，或许还很有见地，这将会是统计学家去合作的不同模式。


Holmes: Often if you don't know the science's language you can't answer their questions.

**Holmes**：如果你不知道科学的语言，你基本上就无法回答他们的问题。

Efron: The language is certainly important, for example, at least knowing the names for important things. Vahe Petrosian is very good at telling me enough about complicated astronomical ideas that involve tricky relativistic transformations. Well, I can't possibly really understand the physics, but at least he can show me the form of a function and then I can talk to him about it. The stuff in biology these days is very complicated; there's a lifetime of work. But we can know enough so that we can be helpful. Do we train our students correctly? I don't know. We don't tell them to go work for a year in a biology lab or something like that. Maybe we should, but somehow I don't think that would be best. It's more efficient to have them learn the stat here and at least be aware of what it takes to communicate with the scientists in various fields. Then if they go out and get a job where for the next 20 years they're going to be helping microbiologists it would be very wise for them to learn more than I know about microbiology. But I don't think it's our job to teach microbiology.

**Efron**：语言当然很重要，例如，至少知道重要事物的名称。Vahe Petrosian非常擅长告诉我足够多的复杂天文学思想，这些思想涉及复杂的相对论变换。嗯，我不可能真正理解深奥的物理学，但至少他可以给我展示函数的形式，然后我可以和他谈谈。现在生物学的内容非常复杂；这是一辈子的工作。但是我们可以知道的足够多，这样我们就可以提供帮助。我们是否正确地训练学生？我不知道。我们不会告诉他们去生物实验室工作一年或类似的事情。也许我们应该，但不知何故我不认为那是最好的。让他们在这里学习统计学更有效，至少要知道与各个领域的科学家交流需要什么。然后，如果他们出去找一份工作，在未来20年里，他们将帮助微生物学家，对他们来说，学到比我更多的微生物学知识是非常明智的。但我认为我们的工作不是教微生物学。

<div align="center"> 

![](https://cdn.mathpix.com/cropped/c4357fddd050678a597e6abf89644367-13.jpg?height=377&width=767&top_left_y=1111&top_left_x=254)

FiG. $10 . \quad$ Fisher lecture, England $2000 ;$ pictured with some of the Fisher children, daughter far left, son second from right.

图 10：Fisher讲座，英国，2000年；图中是Fisher的几个孩子，女儿在最左边，儿子在右边第二个。
</div>



Tibshirani: Maybe our mathematical standards for admission are too high, so that we're excluding a lot of students who might be good statisticians but who can't do the mathematical statistics.


**Tibshirani**：也许我们的入学数学标准太高了，所以排除了很多可能是优秀统计学家但不会做数理统计的学生。

Efron: Stanford is worried about that. I suspect a lot of the universities are. The truth is that the theory is stated mathematically. I was just working at one of Herb Robbins' papers from 1956 and I was reminded how different the tradition used to be. It starts out with a flurry of definitions of the sigma field, the  loss function, the risk function, the decision rule, etc. Then it goes right to the interesting stuff he was really writing about. That's the way all talks used to start in Sequoia Hall. We are less a mathematical field now than we were back in 1960 .

**Efron**：斯坦福大学对此很担心。我怀疑很多大学都是这样。统计理论是用数学方式表述的，这是事实。我刚刚在研究1956年Herb Robbins的一篇论文，我看到过去的传统是多么的不同。首先是对sigma域、损失函数、风险函数、决策规则等的一系列数学定义，然后才是他真正写的有趣的东西。红杉大厅过去所有的演讲都是这样开始的。与1960年相比，我们现在不再是一个数学领域了。


But that isn't a terrible thing. In the 1960s we were still trying to wring more results out of the beautiful inferential theory built by Fisher, Neyman, Wald and the other giants. Most of the problems involved one or two or a few parameters. It really got too hard for the human mind after that. It's not that we've gotten better at statistics now, and as a matter of fact there has been very little progress on the basics of statistical inference. What's happened is that we've loosened up a lot on what constitutes a solution, and that lets us attack the much bigger problems that scientists want us to solve. Just before this hour I was looking at a genomics problem with 444 main effects, pretty small stuff by current standards. There's not much hope for an axiomatic decision-theoretic solution here, not in my hands at least, but with a good computer and some modern statistical tools like generalized linear models, cross-validation, the bootstrap, Splus, easy graphics, smoothers, and so on and so on, one can really make a dent on it. And as a matter of fact the analysis made me realize an inferential weakness in some previous microarray work I'd done. Maybe all this methodological work we've been doing is the buildup to a new round of progress in inferential theory. It's easy to believe that the 10 -million-fold increase in computational power we've seen will make statistics deeper as well as bigger.

但这不是一件可怕的事情。在20世纪60年代，我们仍然试图从Fisher、Neyman、Wald和其他巨人建立的美丽的推断理论中获得更多的结果。大多数问题涉及一个、两个或几个参数。统计推断非常挑战人类的心智，非常困难。这并不是说我们有了更好的统计学，事实上，在统计推断上进展甚微。发生的事情是，我们在解决方案的构成上放松了很多，这让我们能够解决科学家希望我们解决的更大的问题。就在几个小时之前，我正在研究一个有444个主要影响的基因组学问题，按照目前的标准，这是一个相当小的问题。在这里，公理化决策理论解决方案的希望不大，至少不在我手中，但有了一台好的计算机和一些现代统计工具，如广义线性模型、交叉验证、bootstrap、Splus、统计图表、平滑法等等，我们真的可以在这方面有所作为。事实上，这个分析让我意识到我以前做的一些微阵列工作中的一个推论缺陷。也许我们所做的所有这些方法论工作都是为了推动推断理论的新一轮进展。我们很容易相信，我们所看到的计算能力增加了1000万倍，这将使统计学能更深入、更庞大。


## REFERENCES

## 参考文献

[1] BENJAMINI, Y. and HOCHBERG, Y. (1995). Controlling the false discovery rate: A practical and powerful approach to multiple testing. J. Roy. Statist. Soc. Ser. B 57 289-300.

[2] GELFAND, A. and SMITH, A. F. M. (1990). Sampling-based approaches to calculating marginal densities. J. Amer. Statist. Assoc. 85 398-409 .

[3] GEMAN, S. and GEMAN, D. (1984). Stochastic relaxation, Gibbs distributions, and the Bayesian restoration of images. IEEE Transactions on Pattern Analysis and Machine Intelligence 6 721-741$.
