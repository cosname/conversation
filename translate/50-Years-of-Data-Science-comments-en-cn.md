#  Comment on " 50 Years of Data Science"

# “数据科学50年”述评


\author{
Roger D. Peng \\ Department of Biostatistics, Johns Hopkins Bloomberg School of Public Health, Baltimore, MD
}

Professor Donoho's commentary comes at a perfect time, given that, according to his own chronology, we are just about due for another push to "widen the tent" of statistics to include a broader array of activities. Looking back at the efforts of people like Tukey, Cleveland, and Chambers to broaden the meaning of statistics, I would argue that to some extent their efforts have failed. If you look at a textbook for a course in a typical Ph.D. program in statistics today, I believe it would look much like the textbooks used by Cleveland, Chambers, and Tukey in their own studies. In fact, it might even be the same textbook! Progress has been slow, in my opinion. But why is that? Why cannot statistics grow to more fully embrace the many activities that Professor Donoho describes in his six divisions of "Greater Data Science?"

Donoho教授的评论恰逢其时，因为根据他自己的年表，我们即将再次推动“扩大范围”统计数据，以包括更广泛的活动。回顾Tukey、Cleveland和Chambers等人拓宽统计含义的努力，我认为他们的努力在某种程度上失败了。如果你看一看今天典型的统计学博士课程的教科书，我相信它看起来很像克利夫兰、钱伯斯和图基在自己的研究中使用的教科书。事实上，它甚至可能是同一本教科书！我认为进展缓慢。但为什么呢？为什么统计数据不能更全面地涵盖Donoho教授在其“大数据科学”六个部分中描述的许多活动



One frustration that I think many statisticians have in discussions of data science is that if you look at each of the six divisions that Donoho lays out-data exploration, data transformation, computing, modeling, visualization, and science of data science-statisticians do all those things. But the truth is, we do not teach most of them. Over the years, the teaching of statistics has expanded to include topics like computing and visualization, but typically as optional or ancillary courses. Many of the activities on Donoho's list are things that students are assumed to "figure out on their own" without any formal instruction. Asymptotic theory, on the other hand, requires formal instruction.

我认为许多统计学家在讨论数据科学时遇到的一个挫折是，如果你看看Donoho提出的数据探索、数据转换、计算、建模、可视化和数据科学的六个部门中的每一个，统计学家会做所有这些事情。但事实是，我们没有教他们大多数人。多年来，统计学教学已扩展到包括计算和可视化等主题，但通常作为选修课或辅助课程。Donoho名单上的许多活动都是学生在没有任何正式指导的情况下“自行解决”的。另一方面，渐近理论需要正式的指导。

In my own experience, the biggest challenge to teaching the areas of Greater Data Science is that it is difficult and can be very inefficient. Ultimately, I believe these are the reasons that we as a field choose not to teach this material. Many of the areas in the six divisions, data exploration, and transformation, can be frustratingly difficult to generalize. If I clean up administrative claims data from Medicare and link them to air pollution data from the Environmental Protection Agency, does any of the knowledge I gain from those activities apply to the processing of RNA-seq data and linking it with clinical phenotypes? It is difficult to see any connection. On the other hand, both datasets will likely serve as inputs to a generalized linear model. Rather than teach one course on cleaning administrative claims data and another course on processing RNA-seq data, consider how many birds can be hit with the three stones of an exponential family, a link function, and a linear predictor? Furthermore, the behavior of generalized linear models can be analyzed mathematically to make incredibly useful predictions about the variability of their estimates.

根据我自己的经验，教授大数据科学领域的最大挑战是它很难而且效率很低。最终，我认为这些是我们作为一个领域选择不教授这些材料的原因。六个部门中的许多领域，即数据探索和转换，很难概括，这令人沮丧。如果我清理医疗保险的行政索赔数据，并将其与环境保护局的空气污染数据联系起来，我从这些活动中获得的任何知识是否适用于RNA seq数据的处理，并将它与临床表型联系起来？很难看出任何联系。另一方面，这两个数据集都可能作为广义线性模型的输入。与其教授一门关于清理行政索赔数据的课程，另一门关于处理RNA序列数据的课程不如考虑一下，指数家族、联系函数和线性预测因子的三块石头能击中多少只鸟？此外，可以对广义线性模型的行为进行数学分析，以对其估计的可变性做出非常有用的预测。


The lack of a formal framework for "data cleaning" reduces the teaching of the subject to a parade of special cases. While each case might be of interest to some, it is unlikely that any case would be applicable to all. In any institution of higher learning with finite resources, it is impossible to provide formal instruction on all the special cases to everybody who needs them. It is much more efficient to teach the generalized linear model and the central limit theorem.

由于缺乏“数据清理”的正式框架，这一主题的教学减少了一系列特殊案例。虽然每一种情况都可能引起一些人的兴趣，但不太可能任何情况都适用于所有人。在任何资源有限的高等教育机构中，不可能向所有需要的人提供关于所有特殊情况的正式指导。教授广义线性模型和中心极限定理要有效得多。

Is the lack of a formal framework for some areas of data science attributable to some fundamental aspect of those topics, or does it arise simply from a lack of trying? In my opinion, the evidence to date lays the blame on our field's traditional bias toward to use of mathematics as the principal tool for analysis. Indeed, much of the interesting formal work being done in data cleaning and transformation makes use of a completely different toolbox, one largely drawing from computer science and software engineering. Because of this different toolbox, our field has been blinded to recent developments and has missed an important opportunity to cultivate more academic leaders in this area.

数据科学某些领域缺乏正式框架是因为这些主题的某些基本方面，还是仅仅是因为缺乏尝试？在我看来，迄今为止的证据将责任归咎于我们领域的传统偏见，即使用数学作为分析的主要工具。事实上，在数据清理和转换方面正在进行的许多有趣的正式工作都使用了一个完全不同的工具箱，其中很大一部分来自计算机科学和软件工程。由于这一不同的工具箱，我们的领域对最近的发展视而不见，错过了在这一领域培养更多学术领袖的重要机会。


Professor Donoho rightly highlights the work of Hadley Wickham and Yihui Xie, both statisticians, who have made seminal contributions to the field of statistics in their development of the ggplot2, knitr, dplyr, and many other packages for R. It is notable that Wickham's paper outlining the concept of "tidy data," a concept which has sparked a minor revolution in the field of data analysis, was originally published in the Journal of Statistical Software, a nominally "applied" journal. I would argue that such an article more properly belongs in the Annals of Statistics than in a software journal. The formal framework offered in that article has inspired the creation of numerous "tidy data" approaches to analyzing data that have proven remarkably simple to use and understand. The "grammar" outlined in Wickham's article and implemented in the dplyr package serve as an abstraction whose usefulness has been demonstrated in a variety of situations. The lack of mathematical notation in the presentation of dplyr or any of its "tidyverse" relatives does not make it less useful nor does it make it less broadly applicable.

Donoho教授正确地强调了哈德利·威克姆（Hadley Wickham）和谢一辉（Yihui Xie）的工作，他们都是统计学家，在开发ggplot2、knitter、dplyr、，值得注意的是，Wickham的论文概述了“整洁数据”的概念，这一概念在数据分析领域引发了一场小小的革命，最初发表在《统计软件杂志》（Journal of Statistical Software）上，这是一份名义上的“应用”期刊。我认为，这样的文章更适合发表在《统计年鉴》上，而不是发表在软件期刊上。这篇文章中提供的正式框架启发了许多“整洁的数据”方法的创建，这些方法被证明非常易于使用和理解。Wickham文章中概述的并在dplyr包中实现的“语法”是一种抽象，其实用性在各种情况下都得到了证明。在dplyr或其任何“tidyverse”亲属的表达中缺乏数学符号，这并不会使其变得不那么有用，也不会使其不那么广泛适用。


Finally, it is worth a comment that the people that Professor Donoho cites as driving previous pushes to widen the tent of statistics either did not initially come from academia or at least straddled the boundary. Cleveland, Chambers, and Tukey all spent significant time in industry and government settings and that experience no doubt colored their perspectives. Moving to today, it might just be a coincidence that both Wickham and Xie are employed outside of academia by RStudio, but I doubt it. Perhaps it is always the case that the experts come from somewhere else. However, I fear that academic statistics will miss out on the opportunity to recruit bright people who are making contributions in a manner not familiar to many of us.

最后，值得一提的是，Donoho教授提到的推动扩大统计范围的人，要么最初不是来自学术界，要么至少跨越了界限。克利夫兰、钱伯斯和图基都在工业和政府环境中度过了相当长的时间，这些经历无疑影响了他们的观点。转到今天，这可能只是巧合，韦翰和谢都受雇于RStudio的学术机构之外，但我对此表示怀疑。也许专家总是来自其他地方。然而，我担心学术统计数据会错过招聘聪明人的机会，这些人以我们很多人不熟悉的方式做出了贡献。

#  Teaching Data Science in a Statistical Curriculum: Can We Teach More by Teaching Less?

# 在统计课程中教授数据科学：我们能通过少教多教吗？


\author{
Tian Zheng \\ Department of Statistics, Columbia University, New York, NY
}

In many universities, Statistics departments have seen a surge of majors and concentrators (or minors) over the past decade. No one would argue that this trend has nothing to do with the increasing popularity of data-driven solutions in both private and public sectors. Statistics is considered being equivalent to (by some), a part of, or overlapping with (by most), Data Science. Most data scientists would also agree that Statistics is central to the foundation of these data-driven products. Students of Statistics, on one hand, regard themselves as having one foot inside data science already, while, on the other hand, experiencing confusion and frustration when they find themselves not as competitive in job interviews or hack-a-thons as their peers from computational sciences. One common "complaint" from statistics students is that they have not been equipped with the latest computational skills and knowledge about big data technologies. As educators, shall we cater to the needs of our students and start teaching them data science skills? Given the fact that data science technologies are ever changing, which "data science skills" shall we be teaching them? Which of our faculty can teach them these data science skills? We cannot have a curriculum for just about everything. The main question here is not "shall we teach them Python or Hadoop?" but "how shall we prepare our Statistics students for a career in Data Science as a Statistician?"

在许多大学，统计系在过去十年中出现了专业和专业（或未成年人）激增的现象。没有人会认为，这一趋势与数据驱动解决方案在私营和公共部门的日益普及无关。统计被认为等同于（某些）数据科学，是（大多数）数据科学的一部分或与之重叠。大多数数据科学家也会同意，统计是这些数据驱动产品基础的核心。一方面，统计专业的学生认为自己已经涉足了数据科学，另一方面，当他们发现自己在工作面试或黑客马拉松中不如计算科学专业的同龄人时，他们会感到困惑和沮丧。统计专业学生的一个常见“抱怨”是，他们没有掌握最新的计算技能和有关大数据技术的知识。作为教育工作者，我们是否应该迎合学生的需求，开始教授他们数据科学技能？鉴于数据科学技术在不断变化，我们应该教授哪些“数据科学技能”？我们的哪位教师可以教他们这些数据科学技能？我们不可能有一个几乎所有事情的课程。这里的主要问题不是“我们应该教他们Python还是Hadoop？”但是“我们应该如何让我们的统计学学生做好数据科学统计学家职业生涯的准备？”


Currently, Data Science is a fast-evolving field that represents, in many fields, a new approach of acquiring knowledge, collecting evidence, reasoning decisions, and making predictions, much of which is actually not new to Statistics. The process that produces a data science product can be viewed as a sequence of meticulously engineered decisions (or procedures) for data collection, data processing, data analysis, and result interpretation. While most of current data science efforts have been focused on how to implement these decisions to (or "cope with," as Dr. Donoho described in his article) Big Data, Statistics primarily concerns about evaluating and improving the validity of these decisions.

目前，数据科学是一个快速发展的领域，在许多领域中，它代表了获取知识、收集证据、推理决策和做出预测的新方法，其中很多对统计学来说其实并不陌生。产生数据科学产品的过程可以被视为一系列精心设计的决策（或程序），用于数据收集、数据处理、数据分析和结果解释。虽然当前的大多数数据科学工作都集中在如何实施这些决策以（或“应对”，正如Donoho博士在文章中所描述的）大数据，但统计学主要关注评估和提高这些决策的有效性。


In his article, "50 Years of Data Science," Dr. Donoho provided in-depth retrospectives and perspectives on data science, especially in relation to Statistics. He reviewed the evolution of data science as a "science of learning from data." This definition of data science focuses on what we hope to accomplish and advance, rather than on what we use or study. It also well explains why data science, as a field, while being supported by a set of fundamental principles, evolves quickly with current data collection and processing technology. Many of these driving principles have deep roots in Statistics (Kass et al. 2016). However, given any of today's data science products, the most visible and arduous part of the implementation is about data management and processing, model computation, and product delivery using advanced technologies, rendering contributions from these principles obscured. As a result, statistical thinking could be initially overlooked in many of today's data science processes (Harvard Business Review on "The Hidden Biases in Big Data" https://hbr.org/2013/04/the-hidden-biases-in-big-data (APRIL 1, 2013).), which unfortunately lead to misuse of data and misinterpretation of results. Statistical thinking, as a data science skill, is essential for any data science team and crucial for the future development and application of Data Science. As statisticians, our contribution to the data science process is not, nor should not be, the same as programmers and engineers, but as decision makers for the data science process, applying Statistical Thinking. Students, who choose Statistics as their field of study and aspire to become a data scientist, should get familiar with the decision-making process in data science and learn how to contribute to a data science team as a Statistician.

在他的文章《数据科学50年》中，Donoho博士对数据科学，特别是与统计学相关的数据科学进行了深入的回顾和展望。他回顾了数据科学作为“从数据中学习的科学”的演变数据科学的这一定义关注的是我们希望实现和进步的东西，而不是我们使用或研究的东西。这也很好地解释了为什么数据科学作为一个领域，在一系列基本原则的支持下，随着当前数据收集和处理技术的发展而迅速发展。许多这些驱动原则都深深植根于统计学（Kass等人，2016）。然而，考虑到当今的任何一种数据科学产品，实施过程中最明显和最艰巨的部分是数据管理和处理、模型计算和使用先进技术的产品交付，这使得这些原则的贡献变得模糊不清。因此，在当今的许多数据科学过程中，统计思维最初可能被忽视（《哈佛商业评论》“大数据中隐藏的偏见”https://hbr.org/2013/04/the-hidden-biases-in-big-data（2013年4月1日）），这不幸地导致数据的误用和结果的误解。统计思维作为一种数据科学技能，对任何数据科学团队都至关重要，对数据科学的未来发展和应用至关重要。作为统计学家，我们对数据科学过程的贡献与程序员和工程师不同，也不应该相同，而是作为数据科学过程中的决策者，应用统计思维。选择统计学作为学习领域并立志成为数据科学家的学生应熟悉数据科学的决策过程，并学习如何作为统计学家为数据科学团队做出贡献。


Arguably, Statistical Thinking is ubiquitous in the curricular discussion of statistical methods, but can often get lost in details in a statistical curriculum. In a conventional statistical curriculum, students learn about theoretical results on the behaviors of various models and methods, and computational tools for evaluating and assessing data analysis results, often under one topic at a time. Most textbooks focus on reputable methods for a certain type of data for which we have more theoretical guarantees under mild assumptions. We also teach how to check these assumptions in practice. While the number of new models and methods grow every year, theoretical assurance about their general applicability to data, big or small, is often not available. Our textbooks are getting bigger to include more possible coping strategies, and our lectures are getting more packed with discussion on recent developments. Unsurprisingly, both professors and students are disappointed in realizing that, after learning more and more statistical models and machine learning algorithms, many of our students are still feeling incompetent to be a "data scientist."

可以说，统计思维在统计方法的课程讨论中无处不在，但在统计课程中经常会迷失在细节中。在传统的统计课程中，学生学习各种模型和方法的行为的理论结果，以及用于评估和评估数据分析结果的计算工具，通常一次只针对一个主题。大多数教科书都侧重于某一类型数据的可靠方法，在温和假设下，我们有更多的理论保证。我们还教导如何在实践中检查这些假设。尽管新模型和方法的数量每年都在增长，但通常无法从理论上保证它们对大小数据的普遍适用性。我们的教科书越来越大，包括了更多可能的应对策略，我们的讲座也越来越多地讨论了最近的事态发展。不出所料，教授和学生都失望地意识到，在学习了越来越多的统计模型和机器学习算法之后，我们的许多学生仍然觉得自己不能胜任“数据科学家”

The key issue here is that our students are not getting enough experience with decision making in data analysis from a conventional statistical curriculum. Most of our traditional classroom teaching, well-defined homework problems, and in-class exams do not expose our students to the "real jungle," where the data are messy, the scientific problems are vague, and the ground truth is not available. In other words, our students have learned how to solve a defined problem and obtain the right answer, but feel powerless doing an open-ended and ill-posed project with no obvious definition of an end product or the ultimate success. Students are often concerned that the statistical knowledge they acquire may turn out to be irrelevant in their future projects, and are either intimidated by the thought that they need to learn a lot of new skills on their own, or confused about which "useful" skills they should be learning now. Data Science, as a "real jungle," is diverse in nature, broad, and complicated, with a fastevolving and growing set of tools. No curriculum, in Statistics or other fields, can teach a student everything they would need to know for any specific project. Therefore, the best "jungle skills" we can provide our students in Statistics are how to think statistically, how to deliver end-to-end data solutions, how to carry out valid, reproducible and transparent data analysis, and how to acquire new tools and skills on the job.

这里的关键问题是，我们的学生没有从传统统计课程中获得足够的数据分析决策经验。我们的大多数传统课堂教学、明确界定的家庭作业问题和课堂考试都没有让我们的学生暴露在“真实的丛林”中，那里的数据很混乱，科学问题很模糊，而且根本无法得到真相。换言之，我们的学生已经学会了如何解决一个确定的问题并获得正确的答案，但在做一个没有明确定义最终产品或最终成功的开放式和病态项目时感到无能为力。学生们常常担心，他们所获得的统计知识可能会在未来的项目中变得无关紧要，他们要么被自己需要学习很多新技能的想法所吓倒，要么对现在应该学习哪些“有用”技能感到困惑。作为一个“真正的丛林”，数据科学具有多样性、广泛性和复杂性，并拥有一套快速发展的工具。统计或其他领域的任何课程都不能教给学生任何特定项目所需的一切知识。因此，我们可以为统计专业的学生提供的最佳“丛林技能”是如何进行统计思考，如何提供端到端数据解决方案，如何进行有效、可复制和透明的数据分析，以及如何在工作中获取新的工具和技能。

How can we teach such skills? First of all, reproducible computational skills, efficient communication, data presentation, and visualization skills can, and should be, taught and encouraged in all Statistical courses, which would further allow better examination of our data analysis workflows. We can certainly encourage our students to carry out end-to-end projects. Concerning the other skills, can statistical thinking be taught? Can learning on the job be taught? These two skills are related. Students cannot exercise statistical thinking without understanding details on models, methods, and algorithms, or knowing how to implement them. There are so many Quora answers, blog posts, online MOOCs, and Youtube tutorials, from which students can learn what they individually need on their own. Why most of them are not doing that? The obscurity preventing our students from taking the first step is actually the vast size of the collection of available resources and the long list of relevant skills. They do not know where to start and how their skills and knowledge can help them survive. If somehow, we can create a simulated jungle and provide some guidance so that they can safely take a first step and manage to emerge from the other end, maybe that is all it takes.

我们如何教这种技能？首先，所有统计课程都可以、也应该教授和鼓励可复制的计算技能、高效沟通、数据展示和可视化技能，这将进一步帮助我们更好地检查数据分析工作流程。我们当然可以鼓励学生进行端到端的项目。关于其他技能，是否可以教授统计思维？在职学习可以教吗？这两种技能是相关的。如果不了解模型、方法和算法的细节，或者不知道如何实施，学生就无法进行统计思维。有这么多Quora答案、博客帖子、在线MOOC和Youtube教程，学生可以从中学习他们自己需要的东西。为什么他们大多数人不这么做？阻碍我们学生迈出第一步的晦涩事实上是大量可用资源和大量相关技能。他们不知道从哪里开始，他们的技能和知识如何帮助他们生存。如果不知怎么的，我们可以创建一个模拟丛林，并提供一些指导，这样他们就可以安全地迈出第一步，并设法从另一端脱颖而出，也许这就是一切。

To prepare our statistics students for a career in Data Science, a limited-term Statistics curriculum could incorporate data science jungle skills by adding one "simulated jungle" course. The other courses in the curriculum can remain focused on basic principles and show how specific solutions to data problems are derivatives of these basic principles. This would probably mean a subset of what we are teaching right now. Then we can add one project-based mock jungle course that uses project/problembased learning (PBL, http://web.stanford.edu/dept/CTL/cgibin/docs/newsletter/problem_based_learning.pdf) and the Common Task Framework (CTF). In such a course, students will carry out self-directed exploration in a sequence of welldesigned "jungle" common-task problems. For PBL to work, the problem needs to be ill-posed and open-ended. Through the Common Task Framework, team collaboration and peer learning also become important parts of this course.

为了让我们的统计学生做好数据科学职业生涯的准备，一门有限期限的统计课程可以通过增加一门“模拟丛林”课程来融入数据科学丛林技能。课程中的其他课程可以继续关注基本原则，并展示数据问题的具体解决方案是如何衍生这些基本原则的。这可能意味着我们现在所教内容的一部分。然后，我们可以添加一个基于项目的模拟丛林课程，http://web.stanford.edu/dept/CTL/cgibin/docs/newsletter/problem_based_learning.pdf)以及共同任务框架（CTF）。在这样的课程中，学生将在一系列精心设计的“丛林”常见任务问题中进行自主探索。为了让PBL发挥作用，这个问题需要是不确定的和开放的。通过共同任务框架，团队协作和同伴学习也成为本课程的重要组成部分。


We have been teaching such a course (http://tzstatsads.github.io/.) since Spring 2016 to master students in Statistics at Columbia. This course has been wellreceived. There are no formal lectures. Class meeting time was used for tutorials, class discussions, and team presentations, similar to the structure of a hack-a-thon. Learning continues outside classroom on GitHub and the class' discussion forum. For each project, we prepare a project release document with a set of "starter codes." Depending on the projects, the starter codes may contain initial data processing scripts that help students get on with complicated datasets (e.g., image analysis and network analysis), or can be a toy end-to-end example to demonstrate what a completed product should look like (e.g., a Shiny app for data visualization). This course was deliberately taught using $\mathrm{R}$ and $\mathrm{R}$ studio. In addition to the benefit of a versatile statistical package that both the instructional team and the students are already familiar with, using $\mathrm{R}$ in a data science course for statistics students provides an important lesson, by itself, that we can always start creating data science products using computational tools that we know. In this course, we adopted new R packages that interface with recent data science technologies, and Python or Matlab routines for data processing. As a class, we code and debug collaboratively as no one can anticipate what each team decides to do for each open-ended project and what new issues we may encounter with each dataset or software package. Gradually, students start to become used to this sense of uncertainty. The class learns together and supports each other. Students came to this course wanting to learn everything about data science. At the end, they finished the course knowing that there were still a lot to learn, accepting the fact that they probably cannot learn everything, and feeling confident that they would be able to learn on the job and solve problems. In this course, we ask the students to present their projects to different hypothetical audiences (investors, managers, peers, etc.) and support the decisions made for their data science products with convincing evidence. For most projects, we do not have one gold standard to rank the projects. Rather, instructor evaluation and peer review on novelty and values of the main idea, reproducibility of the implementation, clarity of the online, and in-class presentations are more central to the grading of projects. This was not easy or natural when the course first started. Through five project cycles, students got better on both self-assessment and peer commenting. In addition to attaining a deeper understanding of the data science process, learning a number of data science methods and algorithms, and developing a stronger drive to carry out self-learning, students reported one originally unintended benefit. They now see that there are really different roles in a data science process, or in other words, there are different kinds of data scientists and the course helps them realize which kind of data scientists they would like to be. (And it is ok if they realize that they prefer coding over model selection, as an informed decision.)

我们一直在教授这样的课程(http://tzstatsads.github.io/.)自2016年春季起，哥伦比亚大学统计硕士学位课程。这门课程受到了广泛的欢迎。没有正式的讲座。课堂会议时间用于指导、课堂讨论和团队演示，类似于黑客马拉松的结构。学习继续在GitHub和课堂讨论论坛上进行。对于每个项目，我们都准备一份带有一组“启动代码”的项目发布文档根据项目的不同，入门代码可能包含帮助学生处理复杂数据集的初始数据处理脚本（例如，图像分析和网络分析），也可能是一个端到端的玩具示例，以演示完成的产品应该是什么样子（例如，用于数据可视化的Shiny应用程序）。本课程特意使用$\mathrm｛R｝$和$\mathrm｛R}$工作室进行教学。除了教学团队和学生都已经熟悉的通用统计软件包的好处之外，在统计学生的数据科学课程中使用$\mathrm｛R｝$本身就提供了一个重要的教训，即我们始终可以使用我们知道的计算工具来创建数据科学产品。在本课程中，我们采用了与最新的数据科学技术相结合的新R包，以及用于数据处理的Python或Matlab例程。作为一个类，我们协作编写代码和调试，因为没有人能够预测每个团队决定为每个开放式项目做什么，以及我们可能会遇到的每个数据集或软件包的新问题。渐渐地，学生们开始习惯这种不确定感。全班同学一起学习，互相支持。参加本课程的学生希望学习有关数据科学的所有知识。最后，他们完成了课程，知道还有很多东西要学习，接受了自己可能无法学习所有东西的事实，并对自己能够在工作中学习和解决问题充满信心。在本课程中，我们要求学生向不同的假设受众（投资者、管理者、同行等）展示他们的项目，并用令人信服的证据支持为他们的数据科学产品做出的决定。对于大多数项目，我们没有一个金标准来对项目进行排名。相反，教师对主要思想的新颖性和价值、实施的可重复性、在线演示和课堂演示的清晰性的评估和同行评审对项目评分更为重要。这在课程刚开始时并不容易或自然。通过五个项目周期，学生在自我评估和同行评论方面都取得了更好的成绩。除了加深对数据科学过程的理解，学习一些数据科学方法和算法，并培养更强的自我学习动力之外，学生们还报告了一个最初意想不到的好处。他们现在发现，在数据科学过程中有着不同的角色，或者换句话说，有着不同类型的数据科学家，这门课程帮助他们认识到自己想要成为哪种数据科学家。（如果他们意识到他们更喜欢编码而不是模型选择，这是一个明智的决定。）


For the ever expanding skill set and application of data science, we can never be able to teach our students enough "coping skills" to handle each situation. We can, however, teach them the fundamental principles, best practice guidelines, and systematic approaches. We further guide them through learning by doing that allows them to gain the confidence to learn on the job. (Here, the idea of "learning by doing" is not new in education. Our homework problems and take-home projects are "doing" exercises for students to practice knowledge acquired in the classroom. For decision-making and problem-solving skills, we need to design the "doing" experience accordingly.) The learning will continue when the actual teaching ends. In other words, we "teach" more by teaching less. Hopefully, by doing so, more statistics students will develop their career in Data Science and contribute statistically in the data science workflow.

由于数据科学的技能范围和应用不断扩大，我们永远无法教给学生足够的“应对技能”来应对每一种情况。然而，我们可以向他们传授基本原则、最佳实践指南和系统方法。我们进一步引导他们通过边做边学，让他们获得在工作中学习的信心。（在这里，“做中学”的理念在教育中并不新鲜。我们的家庭作业和带回家项目是学生练习课堂知识的“做”练习。对于决策和解决问题的技能，我们需要相应地设计“做”的体验。）当实际教学结束时，学习将继续。换句话说，我们通过少教来“教”更多。希望通过这样做，更多的统计学学生将发展他们的数据科学职业生涯，并在数据科学工作流程中做出统计贡献。


## Reference

## 参考


Kass, R. E., Caffe, B. S., Davidian, M., Meng, X.-L., Yu, B., and Reid, N. (2016), "Ten Simple Rules for Effective Statistical Practice," PLOS Computational Biology, 12, e1004961. [772]



#  Data Science: A Three Ring Circus or a Big Tent?

# 数据科学：三环马戏团还是大帐篷？


**Jennifer Bryan  and Hadley Wickham** 

For context, we both trained as statisticians and spent several years as regular professors of Statistics. We still have academic appointments. Yet today we work for RStudio, building tools to improve the workflows for data scientists and statisticians. This gives us an informed and unique perspective on Donoho's piece, which explores aspects of the academic statistical establishment that are deeply connected with this unusual career path.

就背景而言，我们都接受过统计学家的培训，并担任过几年的统计教授。我们还有学术约会。然而，今天我们为RStudio工作，为数据科学家和统计学家构建工具以改进工作流程。这让我们对Donoho的作品有了一个明智而独特的视角，它探索了与这条不同寻常的职业道路有着深刻联系的学术统计体系的各个方面。


Overall, much of the article resonated with us. Our comments deal with three main areas: academic statistics, the skills meme, and coupling of cognitive and computation tools.

总的来说，这篇文章的大部分内容引起了我们的共鸣。我们的评论涉及三个主要领域：学术统计、技能模因以及认知和计算工具的耦合。

## Academic Statistics

## 学术统计


Donoho gives a beautiful synthesis of the (largely unheeded) pleas from four distinguished statisticians, who, over 50 years, argued for an expanded definition of "academic statistics." He rightly points out that statisticians and departments of Statistics generally do not lead the Data Science initiatives at major universities. But Donoho stops short of making the obvious connection: maybe there is a causal relationship between the two facts? Perhaps the reluctance to embrace data preparation, presentation, and prediction is precisely why Statistics often finds itself on the periphery. If Statistics is unwilling to own the full range of activities necessary to learn from data, how is it possible to claim that "Data Science is just statistics"?

Donoho对四位杰出的统计学家提出的（基本上无人理睬的）请求进行了漂亮的综合，他们在50多年的时间里主张扩大“学术统计”的定义他正确地指出，统计学家和统计系通常不会领导主要大学的数据科学计划。但Donoho没有做出明显的联系：也许这两个事实之间存在因果关系？也许，不愿意接受数据准备、展示和预测正是为什么统计局经常处于边缘地位的原因。如果统计学不愿意拥有从数据中学习所需的全部活动，那么怎么可能声称“数据科学只是统计学”？

Anyone who has ever taken wild-caught data through the full process of analysis knows that "statistics," in the strict sense of fitting models and doing inference, is but one small part of the process. Every repetition of the sentiment that "Data Science is just statistics" underscores how many statisticians have yet to appreciate and accept the changes going on around them. It is understandable that Statistics departments want to share in the resources flowing to Data Science Initiatives, but that comes with the responsibility to address a broader set of needs.

任何一个通过整个分析过程获取野生捕获数据的人都知道，严格意义上的“统计”，即拟合模型和进行推断，只是这个过程的一小部分。“数据科学只是统计”这一观点的每一次重复，都突显出许多统计学家还没有意识到并接受他们周围正在发生的变化。统计部门希望分享流向数据科学倡议的资源是可以理解的，但这也有责任满足更广泛的需求。

This unnecessarily narrow definition of our field is often paired with a narrow definition of who is allowed to do statistics. Statisticians have a tendency to advocate statistical abstinence: you should only practice statistics if you are in a long-term relationship with a statistician (Wickham 2015). But abstinencebased education rarely works. People see their friends using statistics and having a great time, and there simply are not enough statisticians to go around. As a field, we need to teach safe-stats, not just statistical abstinence. Donoho correctly confirms that applied statisticians regularly engage in all the activities touted in press releases, like the one he quotes: "the collection, management, processing, analysis, visualization, and interpretation of vast amounts of heterogeneous data associated with a diverse array of $\ldots$ applications." But there is currently a big gap between what statisticians * do* and what is considered worthy of *study.* The incentive structures of academic statistics still signal that mathematical statistics and the creation of new models and inferential procedures are more valuable than work related to data manipulation, visualization, and programming. This is reflected in the content of for-credit courses, qualifying exams, and standards for funding and promotion. Graduate students and junior faculty are caught between a rock and a hard place (Waller 2017). It can be very difficult to present modern data scientific work as impactful scholarly activity, when the system still defines that primarily as theory and methodology papers.

我们领域的这种不必要的狭隘定义往往与允许谁做统计的狭隘定义相结合。统计学家倾向于提倡统计节制：只有当你与统计学家有长期关系时，你才应该练习统计（Wickham 2015）。但基于禁欲的教育很少奏效。人们看到他们的朋友在使用统计数据，玩得很开心，但根本就没有足够的统计学家。作为一个领域，我们需要教授安全的统计数据，而不仅仅是统计上的禁欲。Donoho正确地证实，应用统计学家经常参与新闻稿中所宣传的所有活动，就像他引用的那样：“收集、管理、处理、分析、可视化和解释与各种应用程序相关的大量异构数据。”但目前，统计学家所做的工作与被认为值得研究的工作之间存在很大差距学术统计的激励结构仍然表明，数学统计以及新模型和推理程序的创建比与数据操作、可视化和编程相关的工作更有价值。这反映在学分课程、资格考试以及资助和晋升标准的内容中。研究生和初级教师被夹在岩石和硬地之间（Waller 2017）。当系统仍然主要将其定义为理论和方法论论文时，很难将现代数据科学工作描述为具有影响力的学术活动。


The good news is the above dysfunction is largely selfimposed! The constraints on what Statistics means are coming from inside the house. Donoho's Six Divisions of Greater Data Science make a wonderful basis for evaluating the usefulness of various activities. We hope that academic departments, grant panels, and promotion committees start to use them.

好消息是，上述功能障碍很大程度上是自己造成的！对统计数据含义的限制来自内部。Donoho的大数据科学六分部为评估各种活动的有用性提供了极好的基础。我们希望学术部门、资助小组和推广委员会开始使用它们。


## The Skills Meme and GDS3: Computing with Data

## 技能记忆和GDS3：数据计算


In "The 'Skills' Meme," Donoho sets out to debunk claims about specific skills that allegedly distinguish Data Science. We would like to refine the points made about Hadoop, "a variant of Map/Reduce for use with datasets distributed across a cluster of computers." We think Hadoop is mostly transitional: it is important for * someone* to worry about the issues of data storage and managing computation, in the same way ${ }^{*}$ someone* should worry about measure theory. Unless you are dealing with exceptionally large data (i.e., multiple terabytes), data representation is not something that most data scientists need to think about: worrying about data storage and sharded computation is becoming the responsibility of a cadre of specialized data engineers.

在“技能记忆”一书中，Donoho开始揭穿有关据称区分数据科学的特定技能的说法。我们希望进一步完善Hadoop的观点，“Hadoop是Map/Reduce的一个变体，用于分布在计算机集群中的数据集。”我们认为Hadoop主要是过渡性的：有人担心数据存储和管理计算的问题很重要，就像有人担心度量理论一样。除非您处理的是超大数据（即数TB），否则大多数数据科学家都不需要考虑数据表示：担心数据存储和分片计算正成为专业数据工程师团队的责任。


We want to underscore that there are substantive skills that distinguish Data Science training from that currently offered in Statistics. This relates to what Donoho refers to as GDS3: Computing with Data. Yes, Data Science tends to place a greater emphasis on computing and programming. But statisticians are too quick to discount this as fairly superficial issues of mechanics, like rewriting R code to avoid using for-loops. The skills meme actually runs much deeper when it comes to computation and programming. It is related to important issues of correctness and reusability. There are proven frameworks from software engineering and IT operations that need to become much more common in data analysis (Parker 2017). We must acknowledge the kernel of truth in the cringe-worthy term "professor-ware."

我们想强调的是，数据科学培训与目前在统计学中提供的培训有着实质性的区别。这与Donoho所说的GDS3：数据计算有关。是的，数据科学倾向于更加强调计算和编程。但统计学家很快就将其视为相当肤浅的力学问题，比如重写R代码以避免使用for循环。当涉及到计算和编程时，技能模因实际上运行得更深。它与正确性和可重用性的重要问题有关。软件工程和IT运营部门的成熟框架需要在数据分析中变得更加普遍（Parker 2017）。我们必须承认“教授ware”这一令人畏缩的术语中的真理核心


We do not claim that all statisticians should write code that is ready for others to use. But surely some should! The basic practices of modularity, testing, version control, packaging, and interface design are not mere niceties. They determine whether data scientific products can actually be trusted and built upon, like a proof in mathematics. It is accepted that we should exploit the methodological innovations made in the past 15 years. Likewise, we must acknowledge big changes in the standards for modern scientific computing. If the era of Data Science prompts a long-overdue enlargement of Statistics, we would do well to incorporate these valuable skills into our revamped curriculum.

我们并不主张所有统计学家都应该编写可供他人使用的代码。但肯定有人应该这样做！模块化、测试、版本控制、打包和界面设计的基本实践不仅仅是细节。它们决定了数据科学产品是否真的可以被信任和建立，就像数学证明一样。大家都认为，我们应该利用过去15年中取得的方法创新。同样，我们必须承认现代科学计算标准的巨大变化。如果数据科学时代推动了早就应该扩大的统计学，我们最好将这些宝贵的技能纳入我们修改后的课程。

## Coupling Cognitive and Computational Tools

## 耦合认知和计算工具


Mathematics provides a common language for mathematical statistics. For exactly the same reasons, it is vital to have shared abstractions and notation when solving problems in applied statistics. This is what a programming language provides, that is, it is not just syntax for issuing instructions to a computer. Although a programming language cannot be as timeless as mathematics, $\mathrm{R}$ currently provides a powerful language for applied statistics.

数学为数理统计提供了一种通用语言。出于完全相同的原因，在解决应用统计中的问题时，共享抽象和符号是至关重要的。这就是编程语言所提供的，也就是说，它不仅仅是向计算机发出指令的语法。虽然编程语言不能像数学那样永恒，但$\mathrm｛R｝$目前为应用统计提供了一种强大的语言。


Donoho generously mentions the benefits of the R packages reshape 2 and plyr. These are early milestones in an effort that has more recently matured into the so-called Tidyverse, $<h t t p s: / / w w w$.tidyverse.org $>$, an ecosystem of packages designed for data science. In ggplot2 and dplyr, the Tidyverse provides two illustrations of the idea that programming is a valid medium for intellectual work and human communication. ggplot2 and dplyr are clear intellectual contributions because they provide tools (grammars) for visualization and data manipulation, respectively. The tools make the tasks radically easier by providing clear organizing principles coupled with effective code. Users often remark on the ease of manipulating data with dplyr and it is natural to wonder if perhaps the task itself is trivial. We claim it is not. Many probability challenges become dramatically easier, once you strike upon the "right" notation. In both cases, what feels like a matter of notation or syntax is really a more about exploiting the "right" abstraction.

Donoho慷慨地提到了R套餐重塑2和ply的好处。这些都是最近发展成为所谓Tidyverse，$<h t t p s://w w w$的努力的早期里程碑。蒂迪弗斯。org$$>$，一个为数据科学设计的软件包生态系统。在ggplot2和dplyr中，Tidyverse提供了两个例子，说明编程是智力工作和人类交流的有效媒介。ggplot2和dplyr是明显的智力贡献，因为它们分别为可视化和数据处理提供了工具（语法）。这些工具通过提供清晰的组织原则和有效的代码，使任务更加容易。用户经常评论使用dplyr处理数据的容易性，很自然会怀疑任务本身是否微不足道。我们声称事实并非如此。一旦你找到了“正确”的符号，许多概率挑战就会变得非常容易。在这两种情况下，感觉像是符号或语法的问题实际上更多的是利用“正确”的抽象。

Another part of what makes the Tidyverse effective is harder to see and, indeed, the goal is for it to become invisible: conventions. The Tidyverse philosophy is to rigorously (and ruthlessly) identify and obey common conventions. This applies to the objects passed from one function to another and to the user interface each function presents. Taken in isolation, each instance of this seems small and unimportant. But collectively, it creates a cohesive system: having learned one component you are more likely to be able to guess how another different component works.

使Tidyverse有效的另一部分是很难看到的，事实上，目标是让它变得无形：惯例。Tidyverse哲学是严格（无情地）识别和遵守共同的惯例。这适用于从一个函数传递到另一个函数的对象以及每个函数呈现的用户界面。孤立来看，这类事件的每一个例子都显得微不足道。但总的来说，它创造了一个有凝聚力的系统：学习了一个组件后，你更有可能猜测另一个不同的组件是如何工作的。


The Tidyverse explicitly recognizes that technology, especially programming, is part of the problem domain. It does not matter how good a theoretical solution is, unless there are practical tools that implement it. We must also recognize that humans are an essential part of the data science process and study how they can interact with the computer most effectively. Finding useful abstractions and exposing them through programming languages is an important part of this process.

Tidyverse明确承认技术，尤其是编程，是问题领域的一部分。理论解决方案有多好并不重要，除非有实用的工具来实现它。我们还必须认识到人类是数据科学过程的重要组成部分，并研究他们如何最有效地与计算机交互。找到有用的抽象并通过编程语言公开它们是这个过程的重要部分。

## Conclusion

## 结论


We appreciate this opportunity to comment on the important issues Donoho has raised for the next 50 years of Statistics. Readers can keep exploring these topics in Practical Data Science for Stats $<h t t p s: / /$ peerj.com/collections/50-practicaldatascistats/ $>$, a collection of articles we have co-edited as a PeerJ preprint Collection and a future special issue of The American Statistician.

我们感谢有机会就Donoho为未来50年统计工作提出的重要问题发表意见。读者可以继续在Stats$<h t t p s://$peerj的实用数据科学中探索这些主题。com/collections/50practicaldatascistats/$$>$，这是我们作为PeerJ预印本集和《美国统计学家》未来特刊共同编辑的文章集。


We see a substantial mismatch between what is needed to learn from data and the much smaller subset of activity that is structurally rewarded in academic statistics today. We both still love to teach and to let those experiences inform the design of better tools and workflows for data analysis. But, frankly, this currently feels easier to do outside the academy.

我们看到，从数据中学习所需的内容与当今学术统计中结构上得到回报的活动的小得多的子集之间存在着严重的不匹配。我们仍然喜欢教学，并让这些经验为设计更好的数据分析工具和工作流程提供信息。但是，坦率地说，目前在学院外做这件事感觉比较容易。

Data Science has at least one advantage over Statistics, which partially explains its existence. Redefining an existing field like Statistics is terribly difficult, whereas it is much easier to define something new from scratch. Increasing activity in the areas proposed by Donoho inevitably means reducing the traditional supremacy of statistical theory. It remains to be seen whether the community has the will to finally heed the call of Tukey, Chambers, Cleveland, and Breiman, and rethink our priorities.

数据科学至少比统计学有一个优势，这部分解释了它的存在。重新定义现有的领域（如统计学）非常困难，而从头定义新的领域则容易得多。在Donoho提出的领域增加活动必然意味着减少统计理论的传统霸主地位。社区是否有意愿最终听从Tukey、Chambers、Cleveland和Breiman的号召，重新考虑我们的优先事项，还有待观察。


## References

## 参考文献


Parker, H. (2017), "Opinionated Analysis Development," *PeerI Preprints* 5 (August): e3210v1. Available at https://doi.org/ 10.7287/peerj.preprints.3210v1. doi:[10.7287/peerj.preprints.3210v1]. [785]

Waller, L. A. (2017), "Documenting and Evaluating Data Science Contributions in Academic Promotion in Departments of Statistics and Biostatistics," ${ }^{*}$ PeerJ Preprints* 5 (August): e3204v1. Available at https://doi.org/10.7287/peerj.preprints.3204v1. doi: [10.7287/peerj.preprints.3204v1]. [784]

Wickham, H. (2015), "Teaching Safe-Stats, Not Statistical Abstinence," *Online Supplement Discussion of "Mere Renovation Is Too Little Too Late: We Need to Rethink Our Undergraduate Curriculum from the Ground Up" by G. Cobb, the American Statistician* 69. Available at http://nhorton.people.amherst.edu/mererenovation/17_Wickham.PDF [784]



#  All of This Has Happened Before. All of This Will Happen Again: Data Science

# 所有这些都曾发生过。所有这些都将再次发生：数据科学



\author{
Heike Hofmann (1) a and Susan VanderPlas ${ }^{\mathrm{b}}$

![](https://cdn.mathpix.com/cropped/2022_11_29_b41a14323b731167a6fdg-1.jpg?height=46&width=1230&top_left_y=506&top_left_x=153)

David Donoho's "50 Years of Data Science" provides a valuable perspective on the statistics-vs-data science debate that has been raging in academic statistics departments over the past couple of years. The debate about the relative merits of theoretical and applied statistics flares up occasionally, and even in the infancy of statistics as a discipline distinct from mathematics, there was "something slightly disreputable about mathematical statistics" because of its applied nature (Salsburg 2001, p. 208). It seems, however, that we may be witnessing the birth of the academic discipline of data science as a separate entity from statistics. While data science itself has been, according to Donoho, around for 50 years or more, academic initiatives focusing on the practice of data analysis are becoming ever more popular.

大卫·Donoho（David Donoho）的《数据科学50年》（50 Years of Data Science）为过去几年在学术统计部门掀起的统计学与数据科学之争提供了一个有价值的视角。关于理论统计学和应用统计学的相对优点的争论偶尔会爆发，甚至在统计学作为一门不同于数学的学科的初期，由于其应用性质，“数理统计学有点不光彩”（Salsburg 2001，第208页）。然而，我们似乎正在见证数据科学作为一个独立于统计学的学科的诞生。根据Donoho的说法，尽管数据科学本身已经存在了50年或更长时间，但专注于数据分析实践的学术倡议正变得越来越流行。


## Historical Parallels

## 历史并行数


Statistics became an academic discipline separate from mathematics in part due to the focus on problems of a more applied nature that involved real-world data. In the U.S., the first standalone statistics entity was Iowa State University's Agricultural and Statistical Laboratory, founded by George Snedecor in 1933, and was focused primarily on statistical analyses of agricultural data. A particularly illustrative paragraph from A Lady Tasting Tea (Salsburg 2001, pp. 216) illustrates the development of statistics as separate from mathematics and lays the foundation for the current situation:

统计学成为一门独立于数学的学科，部分原因是它关注的是涉及真实世界数据的更具应用性的问题。在美国，第一个独立的统计实体是爱荷华州州立大学农业和统计实验室，该实验室由乔治·斯奈德科尔（George Snedecor）于1933年创建，主要专注于农业数据的统计分析。《女士品茶》（Salsburg 2001，第216页）中一段特别说明性的段落说明了统计学的发展与数学的分离，并为当前的情况奠定了基础：


The mathematics departments of American and European universities missed the boat when mathematical statistics arrived on the scene. With Wilks leading the way, many universities developed separate statistics departments. The mathematics departments missed the boat again when the digital computer arrived, disdaining it as a mere machine for doing engineering calculations. Separate computer science departments arose, some of them spun off from engineering departments, others spun off from statistics departments. The next big revolution that involved new mathematical ideas was the development of molecular biology in the 1980s. As we shall see in chapter 28 , both the mathematics and the statistics departments missed that particular boat.

当数理统计抵达现场时，美国和欧洲大学的数学系错过了机会。在威尔克斯的领导下，许多大学发展了独立的统计系。当数字计算机到来时，数学系又错过了这条船，他们不屑于把它仅仅当作一台进行工程计算的机器。独立的计算机科学部门应运而生，其中一些是从工程部门分拆出来的，另一些是从统计部门分拆出来。下一次涉及新数学思想的重大革命是20世纪80年代分子生物学的发展。正如我们将在第28章中看到的，数学和统计部门都错过了这条船。


The parallels are obvious; as statistics has matured as a discipline, researchers have specialized, focusing on the practice of data analysis or on the minutiae of theoretical underpinnings of statistical techniques. Those in the first group are beginning to call themselves "Data Scientists," while those in the second group continue to refer to themselves as "Statisticians".

相似之处显而易见；随着统计学作为一门学科的成熟，研究人员开始专注于数据分析的实践或统计技术理论基础的细节。第一组的人开始自称“数据科学家”，而第二组的人继续自称“统计学家”。


Another parallel can be drawn between the beginning of academic statistics and the beginning of academic data science. As statistics developed as an academic discipline distinct from mathematics, there were many new tools and techniques for analyzing data: ANOVA, least-square regression, Box-Cox transformations, etc. These tools were applied to problems of the day, and as the field matured, some of the tools were replaced by more technologically sophisticated techniques. Similarly, there are a flurry of tools for doing data science which are currently in vogue (rmarkdown, the tidyverse, caret by Kuhn (2017), hadoop, Apache Spark), some of which are built on fundamentally new approaches to data analysis and some that will be supplanted as technology changes.

学术统计的开始和学术数据科学的开始可以形成另一种平行。随着统计学发展成为一门不同于数学的学科，出现了许多新的数据分析工具和技术：方差分析、最小二乘回归、Box-Cox变换等，一些工具被技术更先进的技术所取代。同样，目前流行着一系列数据科学工具（rmarkdown、tidyverse、库恩（Kuhn）的caret（2017）、hadoop、Apache Spark），其中一些基于全新的数据分析方法，有些将随着技术变化而被取代。


Some of the popularity of recently developed tools in R, such as rmarkdown (Allaire et al. 2017) or tidyverse (Wickham 2017b), can be explained because these tools are actual implementations of deeper concepts. Both of these tools can be said to make data analysis an application of literate programming. Literate programming is an idea proposed first by Donald Knuth (Knuth 1984) and implemented in his WEB system. Literate programming is the idea of interweaving code and text into a single document while also aiming for highly modular and therefore reusable code pieces. While rmarkdown allows us the first, tidyverse is a collection of highly modular $\mathrm{R}$ packages that all adhere to a similar API, which allows plug and play data manipulation, modeling, and visualization. Identifying these kind of concepts and generalizable frameworks are part of what drives further research in Data Science.

R中最近开发的一些工具（如rmarkdown（Allaire等人，2017）或tidyverse（Wickham 2017b））的流行可以解释，因为这些工具是更深层概念的实际实现。这两种工具都可以说使数据分析成为识字编程的应用。识字率编程是Donald Knuth（Knuth 1984）首先提出的一个想法，并在他的WEB系统中实现。文学化编程是将代码和文本交织成一个文档的想法，同时也旨在实现高度模块化，因此可重用的代码片段。虽然rmarkdown为我们提供了第一个，但tidyverse是一个高度模块化的$\mathrm｛R｝$包的集合，它们都遵循类似的API，允许即插即用数据操作、建模和可视化。识别这些概念和可推广的框架是推动数据科学进一步研究的一部分。


Donoho should give himself more credit-he has been at the fore-front of the concepts which are now fundamental building blocks in the Science of DS, such as the issue of reproducibility of research. Back in 1995, Buckheit and Donoho (1995) phrased the main idea of computational reproducibility (as opposed to experimental reproducibility, which, of course is also important, but cannot be ensured by any computational tools):


Donoho应该给自己更多的荣誉，因为他一直处于概念的前沿，这些概念现在是DS科学的基本组成部分，例如研究的再现性问题。早在1995年，Buckheit和Donoho（1995）就阐述了计算再现性的主要思想（与实验再现性相反，实验再现性当然也很重要，但无法通过任何计算工具来保证）：

When we publish articles containing figures which were generated by computer, we also publish the complete software environment which generates the figures.

当我们发布包含由计算机生成的图形的文章时，我们还发布生成图形的完整软件环境。

Marwick (2016) defined the "Pi-shaped researcher" as a researcher who in addition to the domain knowledge of the field also knows about and implements best practices of reproducibility. One way to view the divergence between statistics and data science is to say that data science encompasses more computational and literate programming style reproducibility, with a focus on practice as well as theory. 

Marwick（2016）将“Pi-shaped研究者”定义为除了领域知识之外，还了解并实施再现性最佳实践的研究者。看待统计学和数据科学之间的分歧的一种方式是，数据科学包含更多的计算和编程风格的再现性，注重实践和理论。


## The Practice of Data Science

## 数据科学实践


The practice of data science cannot be easily separated from research into data science and teaching data science skills. Often, there is a cycle, where an idea develops as a solution to solve a practical problem, then is extended and applied to a wider set of problems through research, and is finally taught to new practitioners of data science, who then develop new tools. This cycle of practice, research, teaching, and practice can be applied to several distinct areas of data science.

数据科学的实践离不开对数据科学的研究和教授数据科学技能。通常有一个循环，一个想法发展成为解决实际问题的解决方案，然后通过研究扩展并应用于更广泛的问题，最后被传授给新的数据科学从业者，然后他们开发新的工具。这种实践、研究、教学和实践的循环可以应用于数据科学的几个不同领域。

Rather than dividing data science into six divisions, we would suggest that there are six steps in any data analysis, and thus six parts of data science:

我们建议任何数据分析都有六个步骤，而不是将数据科学分为六个部分：


1. Data Provenance

2. Data Exploration and Preparation

3. Data Representation and Transformation

4. Computing with Data

5. Data Modeling

6. Communication of Results

1.数据来源

2.数据勘探和准备

3.数据表示和转换

4.数据计算

5.数据建模

6.结果沟通

Five of these steps roughly concur with the divisions of data science in Donoho's article; we have exchanged data provenance for "Science about Data Science." We have also rephrased "Data Visualization and Presentation" as "Communication of Results." Just as data exploration without visualization is unthinkable, presentation of results is much harder without visualizations. Explicitly mentioning visualization in one but not the other part might lead to the (superficial) impression that data visualization does not start until point 6 in the process.

其中五个步骤大致与Donoho文章中的数据科学划分一致；我们将数据来源交换为“关于数据科学的科学”我们还将“数据可视化和演示”改为“结果沟通”正如没有可视化的数据探索是不可想象的一样，没有可视化的结果呈现要困难得多。明确提及其中一部分而不是另一部分的可视化可能会导致（表面的）印象，即数据可视化直到过程中的第6点才开始。


Each of these steps in a data analysis can be practiced, researched, and taught. Tool development for data science often flows from practice to research and then is taught to new individuals; occasionally, tools flow from teaching to practice to research instead. Several of Jenny Bryan's packages appear to have been inspired by differences in workflow between data scientists and collaborators from other areas (googlesheets by Bryan and Zhao 2017, linen by Jenny Bryan and FitzJohn 2017, and jailbreakr by Jennifer Bryan and FitzJohn 2017), while other packages seem to flow from experience teaching data science (githug, Bryan 2017).

数据分析中的每个步骤都可以实践、研究和教学。数据科学的工具开发通常从实践到研究，然后传授给新的个人；偶尔，工具会从教学到实践再到研究。Jenny Bryan的几个软件包似乎受到了数据科学家和其他领域合作者之间工作流程差异的启发（Bryan和Zhao 2017的googlesheets，Jenny Bryan和FitzJohn 2017的亚麻布，Jennifer Bryan和FitzJohn2017的越狱者），而其他包似乎来自数据科学的经验教学（githug，Bryan 2017）。


An academic data scientist or applied statistician should be focused both on education and tool creation to facilitate using new approaches to work with data. The inspiration for new theories and software can flow from both educational contexts and from practical projects; thus, both sources should be respected and encouraged. Importantly, though, tool creation is a parallel path that exists throughout the six steps for the practice of data science: it is integral to the process of data science, and critical for the evolution of the field as a whole. Most people who program develop convenience functions to complete oftrepeated tasks; it is when those functions are expanded and shared with others that they pollinate the community. R packages such as dplyr (Wickham et al. 2017), tidyr (Wickham 2017a), and rmarkdown are iterations of previous packages and software (reshape and reshape2 by Wickham 2007, plyr by Wickham 2011, knitr by Xie 2015, 2017, and Sweave by Leisch 2002), and all were developed to solve practical problems that became obvious through teaching or data analysis.

学术数据科学家或应用统计学家应专注于教育和工具创建，以促进使用新方法处理数据。新理论和软件的灵感来源于教育背景和实践项目；因此，这两种来源都应该得到尊重和鼓励。然而，重要的是，工具创建是贯穿数据科学实践六个步骤的并行路径：它是数据科学过程的组成部分，对整个领域的发展至关重要。大多数编程人员开发方便功能来完成重复的任务；当这些功能被扩展并与其他人共享时，它们才为社区授粉。诸如dplyr（Wickham等人，2017年）、tidyr（Wick ham 2017a）和rmarkdown等R包是先前包和软件的迭代（Wickham2007年的重塑和重塑2，Wickham 2011年的plyer，Xie 2015年、2017年的knifer，Leisch 2002年的Sweave），所有这些都是为了解决通过教学或数据分析变得明显的实际问题而开发的。


## Prediction and Inference

## 预测和推断


In the discussion of Two Cultures of Statistics, Donoho summarizes Breiman's claims that there are two approaches to extracting information from data: Prediction and Inference. It is true that statisticians focus heavily on parametric inference when teaching techniques; predictions are interpreted within the context of the generating parametric model. Harville (2014) discussed this paradigm by splitting prediction even further into model-based approaches to prediction and algorithmic approaches to prediction, favored by statisticians and computer scientists, respectively. Data science does not have the same bias against algorithmic approaches to prediction seen in statistics departments, but what is unclear is whether one approach is superior to the other in applications. We find Harville's distinction between algorithmic and model-based prediction to be more useful in understanding the divide between traditional statistics and data science approaches to modeling.

在《两种统计文化》的讨论中，Donoho总结了布雷曼的观点，即从数据中提取信息有两种方法：预测和推断。的确，统计学家在教授技术时非常注重参数推断；在生成参数模型的上下文中解释预测。Harville（2014）通过将预测进一步分为基于模型的预测方法和算法预测方法来讨论这一范式，这两种方法分别受到统计学家和计算机科学家的青睐。数据科学对统计部门中的算法预测方法没有相同的偏见，但尚不清楚的是，一种方法在应用中是否优于另一种方法。我们发现Harville在算法和基于模型的预测之间的区别对于理解传统统计学和数据科学建模方法之间的区别更为有用。


Donoho suggests that by combining predictive inference with the Common Task Framework, it is simple to obtain iterative improvements in prediction accuracy. Donoho's discussion of the CTF is certainly useful, but it is entirely possible to apply the CTF to model-based predictions as well as to algorithmic predictions. There is no inherent conflict between the CTF and approaches favored by traditional statisticians. Rather, the philosophical approach to the problem produces this underlying conflict: without a model and parameters that can be interpreted, how does one identify the strengths and weaknesses of the predictions? It is much harder to communicate the results to managers and businesspeople who must act on the predictions from an algorithmic model. The algorithmic approach requires a "leap of faith" that depends heavily on the culture of the "customer" seeking help from the data scientist. In many corporate environments, the black box of a neural network or other machine learning approach is less likely to gain management buy-in than an equation, even if the equation is complex and intimidating. In other organizations, it is preferable to use the en-vogue tool, which is often an algorithmic model (neural networks, random forests, support vector machines, etc.), and there is little desire to examine the underlying mechanisms. This dichotomy is company-culture and domain specific: it is often not possible to find underlying causal mechanisms in data collected outside the confines of a designed experiment (for instance, in social media logs), so the disadvantages of algorithmic models are not problematic. In disciplines which deal with more concrete phenomena (engineering, manufacturing, insurance), model-based approaches are preferable because it is important to understand why the model makes certain predictions and what factors are most influential. Students must learn both approaches to be successful in a wide range of applications of data science.

Donoho建议，通过将预测推理与通用任务框架相结合，很容易获得预测准确性的迭代改进。Donoho对CTF的讨论当然是有用的，但将CTF应用于基于模型的预测以及算法预测是完全可能的。CTF与传统统计学家青睐的方法之间没有内在冲突。相反，这个问题的哲学方法产生了这种潜在的冲突：如果没有一个可以解释的模型和参数，人们如何识别预测的优点和缺点？将结果传达给管理者和商业人士要困难得多，他们必须根据算法模型的预测采取行动。算法方法需要“信念的飞跃”，这在很大程度上取决于“客户”向数据科学家寻求帮助的文化。在许多企业环境中，神经网络或其他机器学习方法的黑匣子比方程式更不可能获得管理层的认可，即使方程式很复杂且令人生畏。在其他组织中，最好使用流行工具，它通常是一种算法模型（神经网络、随机森林、支持向量机等），并且很少有人希望检查潜在机制。这种二分法是公司文化和特定领域的：通常不可能在设计实验范围之外收集的数据中找到潜在的因果机制（例如，在社交媒体日志中），因此算法模型的缺点没有问题。在处理更具体的现象（工程、制造、保险）的学科中，基于模型的方法是可取的，因为了解模型为什么做出某些预测以及哪些因素最有影响很重要。学生必须学习这两种方法，才能在数据科学的广泛应用中取得成功。


## Teaching of DS

## DS教学


Donoho suggests that teaching data science should be focused on the six branches of data science: We must teach not just data modeling, but also data exploration, preparation, computing, and visualization. He suggests using two baseball-focused resources to accomplish this task, and while we applaud the use of real-life data, it is important to point out that students who are not interested in baseball might get the impression that baseball is all there is to statistics. This does an incredible disservice to the statistical community. When one of the authors took linear models, all of the material was discussed in the context of agricultural field experiments, and students with no interest in corn and soybean plots had a much harder time relating to the fundamental concepts. In any course, it is important to provide diversity! Courses should use data from a variety of real life sources: baseball, but also social network data, historical data from the US Census, data from experiments conducted at the university (including data from split plot agricultural experiments), and many other sources.

Donoho建议，数据科学教学应侧重于数据科学的六个分支：我们不仅要教授数据建模，还要教授数据探索、准备、计算和可视化。他建议使用两种以棒球为重点的资源来完成这项任务，尽管我们赞扬使用真实数据，但必须指出的是，对棒球不感兴趣的学生可能会得到这样的印象，即棒球就是统计数据的全部。这对统计界造成了难以置信的伤害。当其中一位作者采用线性模型时，所有材料都是在农业田间实验的背景下讨论的，而对玉米和大豆地块不感兴趣的学生则更难理解基本概念。无论如何，提供多样性都很重要！课程应使用各种现实生活来源的数据：棒球，但也包括社交网络数据、美国人口普查的历史数据、大学进行的实验数据（包括分块农业实验数据）以及许多其他来源。


What is important is that data used in statistics and data science courses should be messy, requiring students to grapple not only with the statistical methods and models which are applied to the data but also with data cleaning and tools used to accomplish this task. While this approach requires more of an investment (for instance, students may need to be exposed to packages like stringr along with tools for modeling statistical networks), it promises to produce students who are fully able to handle real-world data and are thus capable of working in academia or in industry right out of school. In addition, exposing students to new software packages in parallel with new statistical concepts allows them to practice the same skills that are necessary to adapt to the ever-changing set of tools needed to do analysis in the business world.

重要的是，统计和数据科学课程中使用的数据应该是混乱的，这要求学生不仅要学习应用于数据的统计方法和模型，还要学习数据清理和用于完成这项任务的工具。虽然这种方法需要更多的投资（例如，学生可能需要接触stringr等软件包以及建模统计网络的工具），但它承诺培养出完全能够处理真实世界数据的学生，从而能够在校外在学术界或工业界工作。此外，让学生接触新的软件包和新的统计概念，使他们能够练习必要的技能，以适应商业世界中不断变化的分析工具集。

The Park City Math Institute (PCMI) undergraduate faculty group released a set of curriculum guidelines for undergraduate data science programs (De Veaux et al. 2017) which concurs with our suggestions as well as Donoho's push for teaching all six parts of data science. The PCMI guidelines emphasize the importance of teaching students to obtain, wrangle, curate, manage, process, explore, define, analyze, and communicate datathat is, they say that data should be at the center of all data science courses, and that raw data should be included in the teaching process. They suggest that the guiding principles of a data science program are:

帕克城数学学院（PCMI）本科教师团队发布了一套本科数据科学课程的课程指南（De Veaux等人，2017），该指南与我们的建议以及Donoho教授数据科学所有六个部分的努力一致。PCMI指南强调了教学生获取、争论、策划、管理、处理、探索、定义、分析和交流数据的重要性，也就是说，数据应该是所有数据科学课程的中心，原始数据应该包含在教学过程中。他们建议数据科学计划的指导原则是：


1. Data Science as a science

2. Data Science as an Interdisciplinary field

3. Data at the core: classes should require students to work with the whole range of data-related tasks

4. Analytical (Computational and Statistical) thinking

5. Mathematical Foundations

6. Flexibility

1.数据科学作为一门科学

2.作为跨学科领域的数据科学

3.以数据为核心：课堂应要求学生完成所有与数据相关的任务

4.分析（计算和统计）思维

5.数学基础

6.灵活性

These foundational principles are entirely in line with the six parts of data science we have proposed above, modified from Donoho's divisions of data science. Students who cannot think scientifically cannot adequately perform data analyses; neither can students who do not have a set of interdisciplinary skills ranging from programming to mathematics to communication. Students must be provided the opportunity to learn not only the algorithms and statistical foundations of data science, but a whole range of practical skills, and data science programs must be flexible enough to allow students and faculty to specialize in one or more areas related to the acquisition, processing, analysis, modeling, and visualization of data. As useful as it is to have foundational principles for data science, we must be careful not to set up barriers to exclude individuals who are computing with data. Any applied statistician is already a data scientist, but there are also data scientists in computer science, psychology, medicine, bioinformatics, and a whole host of other disciplines. Whatever philosophical disagreements may arise in the next 50 years, we should be careful to learn from the past, preserving the "big tent" approach that the discipline developed organically. Data Science is here to stay, and statisticians should welcome the additional energy and opportunities for collaboration that it has brought to the field.

这些基本原则完全符合我们上面提出的数据科学的六个部分，这些部分是从Donoho的数据科学部门修改而来的。不能科学思考的学生无法充分进行数据分析；没有一套跨学科技能（从编程到数学再到沟通）的学生也不能。必须为学生提供机会，不仅学习数据科学的算法和统计基础，还学习一系列实用技能，数据科学课程必须足够灵活，以允许学生和教职员工专攻与数据采集、处理、分析、建模、数据分析、数据分析和数据分析相关的一个或多个领域，以及数据的可视化。尽管有数据科学的基本原则是有用的，但我们必须小心，不要设置障碍，排斥使用数据进行计算的个人。任何一位应用统计学家都已经是数据科学家，但在计算机科学、心理学、医学、生物信息学和其他一系列学科中也有数据科学家。无论在未来50年中可能出现什么哲学分歧，我们都应该谨慎地从过去吸取教训，保留该学科有机发展的“大帐篷”方法。数据科学将继续存在，统计学家应该欢迎它为该领域带来的更多能量和合作机会。


## ORCID

Heike Hofmann (D) http://orcid.org/0000-0001-6216-5183

## References

Allaire, J. J., Cheng, J., Xie, Y., McPherson, J., Chang, W., Allen, J., Wickham, H., Atkins, A., Hyndman, R., and Arslan, R. (2017), "rmarkdown: Dynamic Documents for R," available at https://CRAN.Rproject.org/package $=$ rmarkdown. [775]

Bryan, J. (2017), "Githug: Interface to Local and Remote Git Operations," Available at https://github.com/jennybc/githug. [776]

Bryan, J., and FitzJohn, R. G. (2017), "Jailbreakr: Extract Data From Human-Readable 'Excel' Spreadsheets," available at https://github.com/rsheets/jailbreakr. [776]

- (2017), "Linen: Spreadsheet Data Structures," available at https://github.com/rsheets/linen. [776]

Bryan, J., and Zhao, J. (2017), "Googlesheets: Manage Google Spreadsheets from R," available at https://CRAN.R-project.org/package = googlesheets. [776]

Buckheit, J. B., and Donoho, D. L. (1995), "WaveLab and Reproducible Research," Technical Report \#474, Stanford University. Available at https://statistics.stanford.edu/sites/default/files/EFS\%20NSF\%20474.pdf. [775]

De Veaux, R. D., Agarwal, M., Averett, M., Baumer, B. S., Bray, A., Bressoud, T. C., Bryant, L., et al. (2017), "Curriculum Guidelines for Undergraduate Programs in Data Science," Annual Review of Statistics and Its Application, 4. [777]

Harville, D. A. (2014), "The Need for More Emphasis on Prediction: A 'Nondenominational' Model-Based Approach," The American Statistician, 68, 71-83. doi:10.1080/00031305.2013.836987. [776]

Knuth, D. E. (1984), "Literate Programming," The Computer Journal, 27, 97-111. [775]

Kuhn, M. (2017), "Caret: Classification and Regression Training," Available at https://CRAN.R-project.org/package $=$ caret. [775]

Leisch, F. (2002), "Sweave, Part I: Mixing R and LaTeX: A Short Introduction to the Sweave File Format and Corresponding R Functions," $R$ News, 2, 28-31. [776]

Marwick, B. (2016), "Computational Reproducibility in Archaeological Research: Basic Principles and a Case Study of Their Implementation," Journal of Archaeological Method and Theory, 24, 424-450. [775]

Salsburg, D. (2001), The Lady Tasting Tea: How Statistics Revolutionized Science in the Twentieth Century, New York: Henry Holt and Company. [775]

Wickham, H. (2007), "Reshaping Data With the Reshape Package," Journal of Statistical Software, 21. Available at http://www.jstatsoft.org/v21/i12/paper. [776]

(2011), "The Split-Apply-Combine Strategy for Data Analysis," Journal of Statistical Software, 40, 1-29. Available at http://www.jstatsoft.org/v40/i01/. [776]

(2017a), "Tidyr: Easily Tidy Data With 'Spread()' and 'Gather()' Functions," available at https://CRAN.R-project.org/package $=t i d y r$. [776] (2017b), "tidyverse: Easily Install and Load 'Tidyverse' Packages," Available at https://CRAN.R-project.org/package=tidyverse. [775]

Wickham, H., Francois, R., Henry, L., and Müller, K. (2017), "Dplyr: A Grammar of Data Manipulation," available at https://CRAN.Rproject.org/package $=d p l y r$. [776] Xie, Y. (2015), Dynamic Documents With R and Knitr (2nd ed.), Boca Raton, FL: Chapman Hall/CRC. [776]

- (2017), "knitr: A General-Purpose Package for Dynamic Report Generation in R," available at https://CRAN.Rproject.org/package $=k n i t r$. [776]


#  Focusing on the Needs: Experiences of Developing a Data Science Program

# 关注需求：制定数据科学计划的经验


\author{
Mahbubul Majumder and Xiaoyue Cheng \\ Department of Mathematics, University of Nebraska at Omaha, Omaha, NE
}

\begin{abstract}
Donoho's article "50 Years of Data Science" is a well-thought explanation of a newly developed discipline called "data science." In this article, we examine his explanations and suggestions about data science, follow-up on some of the issues he mentioned, and share our experiences in developing a data science curriculum and the teaching of related courses.
\end{abstract}

Donoho的文章《数据科学的50年》是对一门新发展的学科“数据科学”的一个深思熟虑的解释在这篇文章中，我们考察了他关于数据科学的解释和建议，对他提到的一些问题进行了跟进，并分享了我们在开发数据科学课程和相关课程教学方面的经验。

## KEYWORDS

Common Task Framework (CTF); Data science program; Data product; Data

共同任务框架（CTF）；数据科学计划；数据产品；数据


visualization; Pedagogy

## Introduction

## 引言


The article "50 Years of Data Science" (Donoho 2017) provides a very thoughtful and deep explanation of a field, which is widely misunderstood and has a variety of meanings to different disciplines. It represents an important development that could not be published in a better time. Because of the demand, new developments in computing technologies, and current ambiguity in defining data science, this article serves as an adjuvant article in the development of a new discipline called "data science."

《数据科学的50年》（Donoho 2017）一文对一个被广泛误解并对不同学科具有多种意义的领域进行了非常深入的解释。这是一个重要的发展，在更好的时间内是无法发表的。由于需求、计算技术的新发展以及当前对数据科学定义的模糊性，本文将作为“数据科学”这一新学科发展的辅助文章


The article is concentrated around three eye-opening papers by Tukey (1962), Cleveland (2001), and Breiman (2001) along with two compelling recent developments in data manipulation (Wickham 2009, 2007, 2014) and reproducible research (Xie 2015). Consequently, Donoho proposed a fuller version of data science that has six components. His view of data science is the modern and practical illustration of what Tukey and Cleveland initiated earlier, and he justified them in connection with modern day reality.

本文主要围绕Tukey（1962）、Cleveland（2001）和Breiman（2001）的三篇令人大开眼界的论文，以及数据操纵（Wickham 2009、2007、2014）和可复制研究（Xie 2015）方面的两项引人注目的最新进展。因此，Donoho提出了一个包含六个组成部分的更完整的数据科学版本。他对数据科学的看法是图基和克利夫兰早先提出的观点的现代和实用的例证，他将其与现代现实联系起来加以证明。


Donoho not only suggested six divisions to describe a fuller version of data science, he also provided insights on how to teach them effectively and what should be the optimal point of achievement. He also shows some open areas of research in data science, which may have a profound and lasting influence on the development of the discipline in the next 50 years. In this article, we intend to discuss some follow up on the issue and present our experiences in developing a data science curriculum and teaching-related courses.

Donoho不仅提出了六个部门来描述更完整的数据科学版本，他还提供了如何有效地教授这些部门以及什么应该是最佳的成就点的见解。他还展示了数据科学研究的一些开放领域，这些领域可能会对未来50年的学科发展产生深远而持久的影响。在本文中，我们打算讨论这个问题的一些后续行动，并介绍我们在开发数据科学课程和教学相关课程方面的经验。

## Followups

## 后续行动


The problem of handling massive data has always been an open problem. The computational difficulties of large-scale data are the driving forces of the development of technologies like hadoop. However, the article mentioned these technologies as hoopla, which sounds similar to how others dismiss the expansion idea of statistics. We believe a careful consideration needs to be given in the research directed to that field so that more general methods can be developed to handle the problem of growing data in future. Also, it should be done in a way such that methods are more accessible to general users, which is often not the case as we see with hadoop technology.

处理海量数据的问题一直是一个悬而未决的问题。大规模数据的计算困难是hadoop等技术发展的驱动力。然而，这篇文章将这些技术称为“哗众取宠”，这听起来与其他人对统计数据的扩张想法不屑一顾。我们认为，在针对该领域的研究中需要仔细考虑，以便能够开发出更通用的方法来处理未来数据增长的问题。此外，它应该以这样一种方式进行，即普通用户更容易访问方法，这通常不是我们在hadoop技术中看到的情况。


The focus of data science does not end when learning from data is done. It also involves how effectively that learning be capitalized or communicated. That brings in the idea of data products, something we believe needs more emphasis. The article did mention the creation of dashboards, which is an example of data products. However, data product is such an important and unique component of data science that it deserves more explicit discussion.

当从数据中学习时，数据科学的重点并没有结束。它还涉及如何有效地利用或交流学习。这带来了数据产品的概念，我们认为需要更加强调这一点。文章确实提到了仪表板的创建，这是数据产品的一个例子。然而，数据产品是数据科学的一个重要而独特的组成部分，因此它值得更明确的讨论。


The research on data visualization is an important area of data science research with potentially many challenging issues. This research can be accelerated by the Common Task Framework (CTF), which has achieved great success in many other fields. A visualization task usually satisfies three requirements of the CTF: data, competitors as different visual designs, and the scoring referee. However, how to make the referee "objectively and automatically reports the score" can be an issue, and one possible answer is the recent development of visual inference (Buja et al. 2009; Majumder, Hofmann, and Cook 2013).

数据可视化研究是数据科学研究的一个重要领域，具有潜在的许多挑战性问题。共同任务框架（CTF）可以加速这项研究，它在许多其他领域都取得了巨大成功。可视化任务通常满足CTF的三个要求：数据、作为不同视觉设计的参赛者以及评分裁判。然而，如何让裁判“客观、自动地报告分数”可能是一个问题，一个可能的答案是视觉推断的最新发展（Buja等人，2009年；Majumder、Hofmann和Cook，2013年）。

In the future, teaching courses in a data science program will face higher requirements as the definition of data science is refined. In Cleveland's article, pedagogy was worth $15 \%$ of allocation of effort. Donoho also reviewed the curriculum of Berkeley Data Science master's program. Although he did not mention much about teaching in the coming decades, we see clues from his views of the trend on research and publication. Therefore, in the next section, we will discuss the trend on developing and teaching data science courses.

未来，随着数据科学定义的细化，数据科学课程的教学将面临更高的要求。在克利夫兰的文章中，教育学价值15美元的努力分配。Donoho还回顾了伯克利数据科学硕士课程。尽管他对未来几十年的教学没有太多提及，但我们从他对研究和出版趋势的看法中看到了线索。因此，在下一节中，我们将讨论开发和教学数据科学课程的趋势。


## Our Experience

## 我们的经验


In our mathematics department, we started data science concentration (http://www.unomaha.edu/college-of-arts-and-scienc es/mathematics/academics/undergraduate.php\#data) for both undergraduate and graduate degree programs in 2014. Two new data science core courses were developed. One is Introduction to Data Science (http://mamajumder.github.io/data-science/fall2014/index.html) and the other is exploratory data visualization and quantification. We have seen a $25 \%$ increase in enrollments since the program was launched and majority of our students are choosing data science concentration. In our data science classes, we get students from a variety of disciplines beyond math, statistics, or computer science such as medical schools, engineering colleges, business schools, political sciences, comparative religions, etc. This brings in additional challenges in teaching data science courses since it is hard to find a common background while common need is there. Perhaps, a CTF can be developed to deal with this challenge. We suggest data science be taught at the high school level so that a common background is set for future data science professionals with varieties of disciplines.

在我们的数学系，我们开始了数据科学集中(http://www.unomaha.edu/college-of-arts-and-scienc教育/数学/学术/本科生。php\# 数据）。开发了两个新的数据科学核心课程。一是数据科学导论(http://mamajumder.github.io/data-science/fall2014/index.html)另一个是探索性数据可视化和量化。自该计划启动以来，我们已经看到报名人数增加了25\%$，我们的大多数学生都选择了数据科学专业。在我们的数据科学课程中，我们招收了来自数学、统计学或计算机科学以外的各种学科的学生，如医学院、工程学院、商学院、政治科学、比较宗教、，这给数据科学课程的教学带来了额外的挑战，因为在有共同需求的情况下很难找到共同的背景。也许，可以开发一个CTF来应对这一挑战。我们建议在高中阶段教授数据科学，以便为未来具有不同学科的数据科学专业人员设置共同的背景。


Data scientists must have training on how to work in collaboration. A common language needs to be learned to communicate with such a diverse group of professionals. Also, real world consulting problems can be used to teach students real data science by involving them in those projects. The practical experience of real data analysis is an important part of teaching data science. We achieve that by allowing students work as interns in those projects. This experience is valuable since the toy problems that fit in the conventional modelings are mostly misleading and give the students a wrong impression of real data science problems.

数据科学家必须接受如何协作的培训。需要学习一种共同的语言来与如此多样化的专业人士群体进行交流。此外，通过让学生参与这些项目，真实世界的咨询问题可以用来教授学生真实的数据科学。真实数据分析的实践经验是数据科学教学的重要组成部分。我们通过允许学生在这些项目中实习来实现这一点。这一经验很有价值，因为符合传统模型的玩具问题大多具有误导性，并给学生一个真实数据科学问题的错误印象。

We use CTF in our machine learning classes. It is a good way to trigger enthusiasm in the class to learn and compete, and strongly stimulates students to try different strategies and chase the top teams during the entire competition period. The use of some web services, like Kaggle in Class (https://inclass.kaggle.com/), a management tool for CTF, and Github (https://github.com/), a code hosting platform, makes the competition and collaboration much more effective for students.

我们在机器学习课程中使用CTF。这是激发课堂学习和竞争热情的好方法，并在整个比赛期间强烈激励学生尝试不同的策略并追逐顶尖团队。一些web服务的使用，如类中的Kaggle(https://inclass.kaggle.com/)，CTF和Github的管理工具(https://github.com/)，一个代码托管平台，使竞争和合作对学生更有效。


Data science problems are not just the big data problems, there exists data science problems in small data as well. The problem of organizing data to give it a form so that further anal- ysis can be done or a model can be fit, is fundamental to data science. To develop methodologies so that this process can be done effectively, scientific research is needed. This is the "science" part of data science.

数据科学问题不仅仅是大数据问题，小数据中也存在数据科学问题。组织数据以形成一种形式，以便进行进一步分析或拟合模型的问题是数据科学的基础。为了制定方法以便有效地完成这一过程，需要进行科学研究。这是数据科学的“科学”部分。


## Conclusion

## 结论


Donoho's article includes enough resources to help resolve differences in opinions about data science among different disciplines. It serves as a resourceful guide for young professionals who need direction in research or teaching materials in data science. It provides necessary components that are needed to create a data science program and produce well-trained data scientists who are in high demand.

Donoho的文章包含了足够的资源来帮助解决不同学科之间关于数据科学的意见分歧。它为需要数据科学研究或教学材料指导的年轻专业人士提供了一个足智多谋的指南。它提供了创建数据科学计划所需的必要组件，并培养出需求量很大的训练有素的数据科学家。


## References

## 参考文献


Breiman, L. (2001), "Statistical Modeling: The Two Cultures," Statistical Science, 16, 199-231. [779]

Buja, A., Cook, D., Hofmann, H., Lawrence, M., Lee, E.-K., Swayne, D. F., and Wickham, H. (2009), "Statistical Inference for Exploratory Data Analysis and Model Diagnostics," Royal Society Philosophical Transactions, $A, 367,4361-4383$. [779]

Cleveland, W. S. (2001), "Data Science: An Action Plan for Expanding the Technical Areas of the Field of Statistics," International Statistical Review, 69, 21-26. [779]

Donoho, D. (2017), "50 Years of Data Science," Journal of Computational and Graphical Statistics, 26, 747-768. [779]

Majumder, M., Hofmann, H., and Cook, D. (2013), "Validation of Visual Statistical Inference, Applied to Linear Models," Journal of the American Statistical Association, 108, 942-956. [779]

Tukey, J. W. (1962), "The Future of Data Analysis," The Annals of Mathematical Statistics, 33, 1-67. [779]

Wickham, H. (2007), "Reshaping Data With the Reshape Package," Journal of Statistical Software, 21, 1-20. [779] - (2009), ggplot2: Elegant Graphics for Data Analysis, useR, New York: Springer. [779]

(2014), "Tidy Data," Journal of Statistical Software, 59. [779]

Xie, Y. (2015), Dynamic Documents With R and Knitr (Vol. 29), Boca Raton, FL: CRC Press. [779]

#  Greater Data Science at Baccalaureate Institutions

# 学士学位院校的更大数据科学


\author{
Amelia McNamara $^{a}$, Nicholas J. Horton ${ }^{b}$, and Benjamin S. Baumer ${ }^{a}$

![](https://cdn.mathpix.com/cropped/2022_11_29_21e684d1170dd257839ag-1.jpg?height=46&width=813&top_left_y=509&top_left_x=152)

Donoho's paper is a spirited call to action for statisticians, who he points out are losing ground in the field of data science by refusing to accept that data science is its own domain. (Or, at least, a domain that is becoming distinctly defined.) He calls on writings by John Tukey, Bill Cleveland, and Leo Breiman, among others, to remind us that statisticians have been dealing with data science for years, and encourages acceptance of the direction of the field while also ensuring that statistics is tightly integrated.

Donoho的论文对统计学家来说是一次积极的行动呼吁，他指出，统计学家拒绝接受数据科学是自己的领域，从而在数据科学领域失去了一席之地。（或者，至少是一个正在明确定义的领域。）他呼吁约翰·图基（John Tukey）、比尔·克利夫兰（Bill Cleveland）和利奥·布雷曼（Leo Breiman）等人的著作提醒我们，统计学家多年来一直在研究数据科学，并鼓励人们接受这一领域的方向，同时也确保统计学紧密结合。


As faculty at baccalaureate institutions (where the growth of undergraduate statistics programs has been dramatic (American Statistical Association 2015)), we are keen to ensure statistics has a place in data science and data science education. In his paper, Donoho is primarily focused on graduate education. At our undergraduate institutions, we are considering many of the same questions.

作为学士学位院校的教职员工（在那里，本科统计课程的增长非常迅速（美国统计协会2015）），我们非常希望确保统计在数据科学和数据科学教育中占有一席之地。在他的论文中，Donoho主要关注研究生教育。在我们的本科院校，我们正在考虑许多相同的问题。


We enthusiastically concur with Donoho's description of a "Greater Data Science" comprised of

1. Data Gathering, Preparation, and Exploration

2. Data Representation and Transformation

3. Computing with Data

4. Data Modeling

5. Data Visualization and Presentation

6. Science about Data Science

我们热烈赞同Donoho对“大数据科学”的描述

1.数据收集、准备和勘探

2.数据表示和转换

3.数据计算

4.数据建模

5.数据可视化和展示

6.关于数据科学的科学

and aim to have our students develop all these key capacities in our courses and major programs.


我们的目标是让我们的学生在我们的课程和主要项目中发展所有这些关键能力。


In considering our curriculum development, we have been guided by the 2014 American Statistical Association (ASA)'s Curriculum Guidelines for Undergraduate Programs in Statistical Science (American Statistical Association 2014) and the 2016 Guidelines for Assessment and Instruction in Statistics Education (GAISE) College Report (Carver et al. 2016). Both documents highlight the need for students to work with real problems, messy data, and complex models.

在考虑我们的课程开发时，我们遵循了2014年美国统计协会（ASA）的统计科学本科课程指南（美国统计协会2014）和2016年统计教育评估和指导指南（GAISE）学院报告（Carver等人，2016）。这两份文件都强调了学生处理真实问题、杂乱数据和复杂模型的必要性。


Even more recently, a working group (including Baumer) developed the Curriculum Guidelines for Undergraduate Programs in Data Science, which have now been endorsed by the ASA (De Veaux et al. 2017). This forward-thinking document addresses one of Donoho's primary concerns with data science education-that it may end up being a piecemeal collection of extant courses, with little "long-term direction." While De Veaux et al. (2017) does provide guidance to institutions working with existing courses, it also outlines a model curriculum with a number of new and reformulated courses.

甚至最近，一个工作组（包括Baumer）制定了《数据科学本科课程指南》，该指南现已获得ASA的批准（De Veaux等人，2017）。这份前瞻性的文件解决了Donoho对数据科学教育的一个主要担忧，即它最终可能是现有课程的零敲碎打的集合，几乎没有“长期方向”虽然De Veaux等人（2017）确实为使用现有课程的机构提供了指导，但它也概述了一个具有许多新课程和重新制定课程的模式课程。


## Data Science Developments at Our Institutions

## 我们机构的数据科学发展


Both the Smith College major in statistical and data sciences and the Amherst College major in statistics have been explicitly structured to introduce, extend, and integrate work in all six of the areas of Greater Data Science. Real problems have been interwoven into our courses at multiple levels. This has required extensive revision of existing courses along with the creation of a number of new and courses with complementary learning outcomes.

史密斯学院统计和数据科学专业和阿默斯特学院统计专业的结构明确，旨在引入、扩展和整合大数据科学所有六个领域的工作。真正的问题已经在多个层面交织到我们的课程中。这需要对现有课程进行广泛修订，同时创建一系列具有互补学习成果的新课程。


At both Smith College and Amherst College, the introductory course touches on all six GDS elements, with an increased emphasis on visualization and modeling (Pruim, Kaplan, and Horton 2017; Baumer et al. 2014). In subsequent courses like Multiple Regression or Intermediate Statistics, students explore, prepare, clean, transform, and visualize data. In the Communicating with Data, Visual Analytics, and Multivariate Data Anal$y$ sis courses, students learn principles of data visualization and presentation of data. Modeling is reinforced in Multiple Regression and Machine Learning. Capstone courses help to integrate prior course work with project-based learning while further refining computing and communication skills.

在史密斯学院和阿默斯特学院，入门课程涉及所有六个GDS元素，并更加强调可视化和建模（Pruim、Kaplan和Horton 2017；Baumer等人，2014）。在随后的课程中，如多元回归或中级统计，学生探索、准备、清理、转换和可视化数据。在与数据沟通、可视化分析和多变量数据分析课程中，学生学习数据可视化和数据表示的原理。在多元回归和机器学习中加强了建模。顶层课程有助于将先前的课程工作与基于项目的学习相结合，同时进一步提高计算和沟通技能。


Existing Amherst College theory courses such as Probability and Theoretical Statistics have been restructured to integrate computing as an explicit learning outcome (e.g., how to write a function, how to perform simulations, how to undertake empirical problem solving to complement analytic results, and how to collaborate in groups using GitHub).

现有的阿默斯特学院理论课程，如概率和理论统计，已经进行了重组，以将计算作为一种明确的学习结果（例如，如何编写函数、如何执行模拟、如何进行实证问题解决以补充分析结果，以及如何使用GitHub进行小组协作）。


At Smith College, Introduction to Data Science, Communicating with Data, Visual Analytics, and Machine Learning are all new offerings guided by our understanding of data science as its own discipline.

在史密斯学院，《数据科学导论》、《与数据沟通》、《视觉分析》和《机器学习》都是我们将数据科学理解为自己的学科而推出的新课程。


We would like to draw particular attention to Introduction to Data Science, a successor to the course described in (Baumer 2015) that is offered at both institutions. Donoho makes reference to this course, which teaches data visualization, data wrangling, ethics, SQL, and communication, using a new textbook (Baumer et al. 2017). The course is tied together by liberal arts modules, where professors from other disciplines outline questions relevant to their discipline, and the students seek to address it using their new-found data skills.

我们希望特别注意《数据科学导论》，该课程是（Baumer 2015）中所述课程的后续课程，该课程在两个机构都提供。Donoho参考了本课程，该课程使用新教材教授数据可视化、数据争论、道德、SQL和通信（Baumer等人，2017）。这门课程由文科模块联系在一起，其他学科的教授在其中概述与本学科相关的问题，学生们试图利用他们新发现的数据技能来解决问题。


As Donoho reminds us, some academic statisticians have long been guilty of eschewing data analysis. But even some programs in data science focus more on tools and skills rather than developing the capacity to solve real problems. We believe our positions at liberal arts colleges give us a particular ability to reach across disciplines, connecting to data in the sciences, social sciences, and the humanities. The integration of liberal arts modules in Introduction to Data Science can be used as a model for similar courses.

正如Donoho提醒我们的那样，一些学术统计学家长期以来一直在逃避数据分析。但即使是数据科学中的一些项目，也更注重工具和技能，而不是开发解决实际问题的能力。我们相信，我们在文科学院的职位赋予了我们跨越学科、连接科学、社会科学和人文学科数据的特殊能力。《数据科学导论》中文科模块的整合可以作为类似课程的模式。

Another learning outcome in all of our courses is to produce students who learn how to learn. As with many disciplines, data science is evolving quickly. The tools we teach our students today may not be relevant in five years. In fact, several of the R packages referenced by Donoho (reshape2 and plyr) have now been supplanted by others (tidyr and dplyr) (Wickham and Francois 2016; Wickham 2014). As instructors, we do our best to stay on top of the current computational trends to provide our students with the most contemporary methods, which requires us to continually modify our curriculum. However, the focus is on generalized problem-solving that can be applied using different tools in different settings.

我们所有课程的另一个学习成果是培养学习如何学习的学生。与许多学科一样，数据科学正在快速发展。我们今天教给学生的工具在五年内可能不再适用。事实上，Donoho引用的几个R包（reshape2和plyr）现在已经被其他包（tidyr和dplyr）取代（Wickham和Francois 2016；Wickham 2014）。作为讲师，我们尽最大努力掌握当前的计算趋势，为学生提供最新的方法，这需要我们不断修改课程。然而，重点是可以在不同环境中使用不同工具应用的通用问题解决。


Ethical precepts are an important part of any data science program. Donoho alludes to this with his detailed coverage of the University of California-Berkeley Master's program, which includes a course now titled "Behind the Data: Humans and Values" (formerly "Legal, Policy, and Ethical Considerations for Data Scientists") (UC Berkeley School of Information 2017). At Amherst ethics is now included as a learning outcome in the Intermediate Statistics course with subsequent extension and reinforcement in elective and capstone courses. Ethics is also a component of the Introduction to Data Science courses. Students consider questions like those posed in Boyd and Crawford (2012): what are the ethical implications of data science products? Who has access to data science, and who does not? What are our ethical obligations to our clients, ourselves, and our subjects? These higher-level questions make up a key part of the capstone courses.

道德准则是任何数据科学计划的重要组成部分。Donoho在对加州大学伯克利分校硕士课程的详细报道中提到了这一点，该课程包括一门现在名为“数据背后：人类和价值观”（原“数据科学家的法律、政策和道德考量”）的课程（加州大学伯克利信息学院2017）。在阿默斯特，道德规范现在作为一种学习成果被纳入中级统计课程，随后在选修课和顶层课程中进行扩展和强化。伦理学也是数据科学入门课程的一个组成部分。学生们考虑了Boyd和Crawford（2012）提出的问题：数据科学产品的伦理含义是什么？谁有机会接触数据科学，谁没有？我们对客户、我们自己和受试者的道德义务是什么？这些更高层次的问题构成了顶级课程的关键部分。


At all levels, our courses emphasize best practices of statistical computing and reproducible research. These efforts build upon scholarly work that goes back at least to Don Knuth's literate programming (Knuth 1992) and Donoho's previous work on reproducibility (Buckheit and Donoho 1995). Baumer and McNamara are former faculty fellows of Project TIER: Teaching Integrity in Empirical Research (Ball and Medeiros 2012), which aims to spread good computing and data practices to the social sciences. We are now seeing evidence of adoptions at our institutions, and others, where faculty members in economics, psychology, and environmental science and policy integrate reproducible research into their coursework, further strengthening our pool of data-capable students.

在所有级别，我们的课程都强调统计计算和可复制研究的最佳实践。这些努力建立在学术工作的基础上，至少可以追溯到唐·克努思的识字编程（克努思1992年）和Donoho之前关于再现性的工作（巴克海特和Donoho1995年）。鲍默和麦克纳马拉是TIER项目的前研究员：实证研究中的教学诚信（Ball和Medeiros 2012），该项目旨在将良好的计算和数据实践推广到社会科学中。我们现在看到了我们的机构和其他机构采用的证据，在这些机构中，经济学、心理学、环境科学和政策的教师将可复制的研究融入到他们的课程中，进一步加强了我们的数据能力学生库。


## Data Science Scholarship

## 数据科学奖学金


Beyond our interest in the pedagogy of data science, we are also researchers. However, this is an area that is also undergoing development. Since it is an emerging field, institutions must determine how to judge new types of scholarly production. Like many problems of data science, this is something that applied statisticians have been wrestling with for decades. However, not all data science work is precisely applied statistics (thus, the new degree programs and scholarship). Much like Donoho's notion of Science about Data Science, Jeff Leek has been proposing the idea of Data Science as a Science (Leek 2016). While Donoho's examples focus on meta-analysis, Leek's conception includes hands-on research. Calling on examples like Cleveland's study of graphical perception (Cleveland et al. 1985), Leek advocates for data scientists experimenting to learn how software syntax impacts learning, and how practitioners are actually working (Silberzahn et al. 2017).

除了我们对数据科学教学法的兴趣，我们还是研究人员。然而，这也是一个正在发展的领域。由于它是一个新兴领域，机构必须决定如何判断新类型的学术成果。与许多数据科学问题一样，这是应用统计学家几十年来一直在努力解决的问题。然而，并非所有的数据科学工作都是精确的应用统计学（因此，新的学位课程和奖学金）。就像Donoho关于数据科学的科学概念一样，Jeff Leek一直在提出数据科学是一门科学的概念（Leek 2016）。虽然Donoho的例子侧重于荟萃分析，但Leek的概念包括动手研究。Leek引用了Cleveland的图形感知研究（Cleveland等人，1985）等例子，倡导数据科学家进行实验，以了解软件语法如何影响学习，以及从业者如何实际工作（Silberzahn等人，2017）。


As a case study of scholarly production in data science, consider Hadley Wickham's many contributions. Wickham's work often centers on a profoundly useful R package. However, each piece of software fits into a higher-level framework of intellectually-weighty ideas. The ideas behind ggplot 2 were articulated in a book on implementing Wilkinson's Grammar of Graphics (Wilkinson 2005; Wickham 2009). In addition to tidyr, Wickham wrote an article in the Journal of Statistical Software on the concept of tidy data, which transcends the language it is implemented in Wickham (2014). Although these works are highly-cited, they do not fit cleanly into the traditional fields of statistics (having nothing to do with modeling, estimation, or inference) nor computer science (software engineering?). We submit that these are early, influential works of scholarship in data science.

作为数据科学学术成果的案例研究，请考虑哈德利·威克姆的许多贡献。韦翰的工作通常集中在一个非常有用的R包上。然而，每一个软件都符合一个更高层次的思想框架。ggplot 2背后的想法在一本关于实现威尔金森的图形语法的书中得到了阐述（威尔金森2005年；韦翰2009年）。除了tidyr，Wickham还在《统计软件杂志》上发表了一篇文章，阐述了整洁数据的概念，它超越了Wickham（2014）中实现的语言。尽管这些著作被高度引用，但它们并不完全符合传统的统计学领域（与建模、估计或推理无关），也不符合计算机科学（软件工程？）。我们认为这些都是早期的、有影响力的数据科学学术著作。


Another set of exemplary papers can be found in a recentlypublished collection of articles-curated by Jenny Bryan and Hadley Wickham-entitled Practical Data Science for Stats (to which the authors all contributed) (Bryan and Wickham 2017). These articles discuss meta-data science topics like how to package reproducible analytical work (Marwick, Boettiger, and Mullen 2017), how to organize data in a spreadsheet (Broman and Woo 2017), how to share data for collaboration (Ellis and Leek 2017), and how to implement a version control system (Bryan 2017). Our contributions discussed surviving as an isolated data scientist (Baumer 2017), and wrangling categorical data (McNamara and Horton 2017).

Jenny Bryan和Hadley Wickham最近出版了一系列文章，题为《统计实用数据科学》（Practical Data Science for Stats）（作者均对此做出了贡献）（Bryan和Wickham 2017）。这些文章讨论了元数据科学主题，如如何打包可复制的分析工作（Marwick、Boettiger和Mullen 2017），如何在电子表格中组织数据（Broman和Woo 2017），怎样共享数据进行协作（Ellis和Leek 2017），以及如何实施版本控制系统（Bryan 2017）。我们的贡献讨论了作为一个孤立的数据科学家生存（Baumer 2017），以及争论分类数据（McNamara和Horton 2017）。


The collection also contains an article on evaluating scholarly work in data science, focusing particularly on data science faculty in traditional statistics and biostatistics departments (Waller 2017). Can these exemplary scholarly contributions in data science be neatly categorized into statistics or computer science research? If not, this further strengthens the notion that data science exists as a field of research unto itself.

该集还包含一篇关于评估数据科学学术工作的文章，特别关注传统统计和生物统计部门的数据科学教师（Waller 2017）。这些在数据科学方面的典型学术贡献能被整齐地归类为统计学或计算机科学研究吗？如果没有，这进一步强化了数据科学本身就是一个研究领域的概念。


## Situating Greater Data Science

## 定位更大的数据科学


This brings us to our final question. If Donoho's vision of 'Greater Data Science' takes hold, one wonders whether the current academic departmental alignments will (or should) continue. Of the authors, one is situated within a Department of Mathematics and Statistics (Horton), while the other two are appointed in a Program in Statistical and Data Sciences. Which approach is most fruitful?

这就引出了我们的最后一个问题。如果Donoho的“大数据科学”愿景得以实现，人们会怀疑目前的学术部门联盟是否会（或应该）继续下去。其中一位作者位于数学和统计系（Horton），而另外两位则被任命为统计和数据科学专业的学生。哪种方法最有效？

Clearly, there are many other academic areas that use data and data science methods. As we have discussed, our colleagues across the disciplines are embracing it. However, if data science is its own discipline, it cannot be solely situated within data-generating departments. Its unique teaching and scholarship indicate it may need to become a separate entity. 

显然，还有许多其他学术领域使用数据和数据科学方法。正如我们所讨论的，我们各学科的同事都在接受它。然而，如果数据科学是它自己的学科，它就不能仅仅位于数据生成部门。它独特的教学和学术表明它可能需要成为一个独立的实体。

## References

## 参考文献


American Statistical Association (2014), 2014 Curriculum Guidelines for Undergraduate Programs in Statistical Science. http://www.amstat.org/ asa/education/Curriculum-Guidelines-for-Undergraduate-Programsin-Statistical-Science.aspx. [781]

(2015), "A peek into the largest, fastest-growing undergraduate statistics departments," http://magazine.amstat.org/blog/2015/02/01/ undergraduatedepts_feb2015. [781]

Ball, R., and Medeiros, N. (2012), “Teaching Integrity in Empirical Research: A Protocol for Documenting Data Management and Analysis," The Journal of Economic Education, 43, 182-189. [782]

Baumer, B. (2015), "A Data Science Course for Undergraduates: Thinking with Data," The American Statistician, 69, 334-342. [781]

(2017), "Lessons From Between the White Lines for Isolated Data Scientists," PeerJ Preprints, 5:e3160v2. [782]

Baumer, B., Çetinkaya Rundel, M., Bray, A., Loi, L., and Horton, N. J. (2014), "R Markdown: Integrating a Reproducible Analysis Tool into Introductory Statistics," Technology Innovations in Statistics Education, 8. [781]

Baumer, B., Kaplan, D. T., and Horton, N. J. (2017), Modern Data Science with R, Boca Raton, FL: Chapman \& Hall. [781]

Boyd, D., and Crawford, K. (2012), "Critical Questions for Big Data," Information, Communication \& Society, 15, 662-679. [782]

Broman, K. W., and Woo, K. H. (2017), "Data Organization in Spreadsheets," Peers Preprints, 5:e3183v1. [782]

Bryan, J. (2017), "Excuse Me, Do You Have a Moment to Talk About Version Control?" PeerJ Preprints, 5:e3159v2. [782]

Bryan, J. and Wickham, H. (eds.) (2017), Practical Data Science for Stats. PeerJ. [782]

Buckheit, J. B. and Donoho, D. L. (1995), "Wavelab and Reproducible Research,” Technical Report 474, Stanford University. http://statistics. stanford.edu/ckirby/techreports/NSF/EFS\%20NSF\%20474.pdf. [782]

Carver, R. et al. (2016), Guidelines for Assessment and Instruction in Statistics Education: College Report 2016, American Statistical Association. [781] Cleveland, W. S., McGill, R., et al. (1985), "Graphical Perception and Graphical Methods for Analyzing Scientific Data." Science, 229, 828-833. [782]

De Veaux, R. D. et al. (2017), "Curriculum Guidelines for Undergraduate Programs in Data Science," Annual Review of Statistics and Its Application, 4, 1-16. [781]

Ellis, S. E. and Leek, J. T. (2017), "How to Share Data for Collaboration," PeerJ Preprints, 5:e3139v5. [782]

Knuth, D. (1992), "Literate Programming." CSLI Lecture Notes, Stanford University, 27. [782]

Leek, J. (2016), "Data Science as a Science," in Joint Statistical Meetings, https://www.slideshare.net/jtleek/data-science-as-a-science. [782]

Marwick, B., Boettiger, C., and Mullen, L. (2017), "Packaging Data Analytical Work Reproducibly using R (and friends)," PeerJ Preprints, 5:e3192v1. [782]

McNamara, A. and Horton, N. J. (2017), "Wrangling Categorical Data in R," PeerJ Preprints, 5:e3163v1. [782]

Pruim, R., Kaplan, D. T., and Horton, N. J. (2017), "The Mosaic Package: Helping Students to 'Think with Data' Using R," The R Journal, 9, 77102. [781]

Silberzahn, R. et al. (2017), "Many Analysts, One Dataset: Making Transparent how Variations in Analytical Choices Affect Results." Berkeley Initiative for Transparency in the Social Sciences. [782]

UC Berkeley School of Information (2017), Master of Information and Data Science: Curriculum. https://datascience.berkeley.edu/academics/ curriculum/. [782]

Waller, L. A. (2017), "Documenting and Evaluating Data Science Contributions in Academic Promotion in Departments of Statistics and Biostatistics," PeerJ Preprints, 5:e3204v1. [782]

Wickham, H. (2009), ggplot2: Elegant Graphics for Data Analysis, New York, NY: Springer Verlag. [782]

- (2014), "Tidy data," The Journal of Statistical Software, 59(10). http://vita.had.co.nz/papers/tidy-data.html. [782]

Wickham, H., and Francois, R. (2016), dplyr: a grammar of data manipulation. R package version 0.5.0.9000. [782]

Wilkinson, L. (2005), The Grammar of Graphics, Statistics and Computing, New York: Springer Science + Business Media. [782]


# Discussion of "50 Years of Data Science"

# “数据科学50年”探讨

Susan Holmes $^{a}$ and Julie Josse ${ }^{b}$

![](https://cdn.mathpix.com/cropped/2022_11_29_1867204db031801b11feg-1.jpg?height=46&width=1770&top_left_y=509&top_left_x=103)
INRIA, Palaiseau, France

First of all, we would like to thank the author for writing such a thoughtful article. The article draws attention to so many important aspects at the intersection of data science and applied statistics. Having been raised in the French school of Data Science (Analyse des Données, see Holmes 2008), this article has a particular resonance for us.

首先，我们要感谢作者写了这么一篇深思熟虑的文章。本文提请人们注意数据科学和应用统计学交叉点的许多重要方面。这篇文章在法国数据科学学院（Analyze des Données，见Holmes 2008）长大，对我们来说特别有共鸣。


In the 1970s, a group of French Statisticians under the leadership of Benzécri revolted against the probabilistic emphasis given to the field of statistics and decided to create a new discipline that would put the applications and the data first.

20世纪70年代，一群在Benzécri领导下的法国统计学家反对统计领域的概率论，并决定创建一个将应用程序和数据放在首位的新学科。


Benzécri, having spent time at Bell Labs visiting Roger Shepard, shared the view that the future of applied statistics involves computational and geometric approaches (in particular, the projection of data using a variety of weighted distances). His practical vision of science and data science include the idea of letting the data speak for themselves and of finding a rigorous method which extracts structures, patterns from the data (Benzécri 1973, p. 6, Tome 2). Data encoding, visualization, and writing programs were considered crucial steps in the analysis.

Benzécri曾在贝尔实验室访问Roger Shepard，他认为应用统计学的未来涉及计算和几何方法（特别是使用各种加权距离投影数据）。他对科学和数据科学的实际愿景包括让数据自己说话，并找到从数据中提取结构和模式的严格方法（Benzécri 1973，第6页，Tome 2）。数据编码、可视化和编写程序被认为是分析中的关键步骤。


Correspondence Analysis, the cornerstone method of this current, was developed jointly with Brigitte Escofier-Cordier (1969) and presented by Benzécri during six lectures at Collège de France. Correspondence Analysis was first designed to describe and visualize the associations in a contingency table crossing two categorical variables. A driving application was in linguistics with the analysis of text-word data (Murtagh 2005) from a variety of corpus (Greek and Latin philosophy, Biblical, medieval philosophy, and Russian 20th century literature).

通信分析是这一潮流的基石，是与Brigitte Escofier Cordier（1969年）共同开发的，由Benzécri在法国Collège举办的六场讲座中介绍。对应分析最初设计用于描述和可视化两个类别变量的列联表中的关联。一个推动性的应用是在语言学中，分析来自各种语料库（希腊和拉丁哲学、圣经、中世纪哲学和俄罗斯20世纪文学）的文本单词数据（Murtagh 2005）。


Benzécri attached great importance to the collaboration between disciplines and the explosion of the use of his methods in many fields such as anthropology, sociology, economics, marketing, hydrology, geography, bibliometrics, environmetrics, marked a generation of applied statisticians in France. "L'analyse des données" was especially popular in social sciences where categorical data were prevalent through surveys. Pierre Bourdieu, a pioneer, presented in "La Distinction" (1976/79), graphical maps of social spaces that can uncover complex relations (Lebaron and Le Roux 2015). CA was even discussed in the media "Le nouvel observateur" (you could read sentences as ... "This immense volume, redesigned flat by the computer thanks to savant calculations but which preserve at best the disparities observed between the professions...") (Derosiére in Lebart 2008).

Benzécri非常重视学科之间的合作，并在人类学、社会学、经济学、营销学、水文学、地理学、文献计量学、环境计量学等多个领域大量使用他的方法，这标志着法国一代应用统计学家。“L’analyze des données”在社会科学中特别流行，在那里，分类数据通过调查而流行。先驱皮埃尔·布迪厄（Pierre Bourdieu）在“La Distinction”（1976年/79年）中介绍了可以揭示复杂关系的社会空间图形地图（Lebaron和Le Roux，2015年）。CA甚至在媒体“新生观察者”（Le novel observateur）中被讨论过（你可以把句子读成……“这本巨大的书，由于计算机的计算，它被重新设计成了平面，但最多保留了专业之间观察到的差异……”）（Lebart的Derosiére 2008）。


Dissemination was fostered by the availability of numerical libraries in Fortran and free software. In addition, "l'analyse des données" was taught to many students with Ph.D. and Masters programs covering geometric projection methods ("analyses factorielles"), interpretation tools ("points supplémentaires," "parts d'inertie"), clustering, data encoding, and programming. Internships in companies were also made mandatory after May 1968 (Murtagh 2005).

Fortran数字库和自由软件的可用性促进了传播。此外，还向许多博士和硕士课程的学生教授了“l’analysis des données”，包括几何投影方法（“analysis factorieles”）、解释工具（“points supplyémentaires”、“parts D’inertie”）、聚类、数据编码和编程。1968年5月之后，公司实习也被强制要求（Murtagh 2005）。


Other areas of data science were active and well developed by M. Tenehaus, G. Saporta (1976) among others. E. Diday (1973), I. C. Lermann, M. Roux, and G. Celeux developed and implemented many clustering methods and took the lead in the "Clustering societies."

M.Tenehaus、G.Saporta（1976年）等在数据科学的其他领域也很活跃和发展。E、 Didai（1973）、I.C.Lermann、M.Roux和G.Celeux开发并实施了许多聚类方法，并在“聚类社会”中处于领先地位


Geographically, there were several teaching and research hotbeds outside of Paris: Rennes where I. C. Lermann and G. Le Calve started groups; Montpellier where Y. Escoufier worked, Marseille with B. Fichet. These groups even developed their own software packages for training students and developed new methods; for instance, multiway data fusion-combining multiple matrices of data formed of variables from different domains and of different nature (categorical, quantitative, counts) and multitype clustering methods. Hundreds of articles and books were published, all in French; maybe one reason why much of the work done in the 1980s did not have a large impact.

从地理上看，巴黎以外有几个教学和研究的温床：雷恩，I.C.Lermann和G.LeCalve在那里成立了小组；Y.Escoufier工作的蒙彼利埃，B.Fichet工作的马赛。这些小组甚至开发了自己的培训学生的软件包，并开发了新的方法；例如，多路数据融合结合了由来自不同领域和不同性质（分类、定量、计数）的变量组成的多个数据矩阵和多类型聚类方法。发表了数百篇文章和书籍，都是法语；也许是20世纪80年代所做的大部分工作没有产生重大影响的原因之一。


However, a broader community started to ramify as the French made contacts with the researchers in Britain such as John Gower and Frank Critchley. The Japanese and Dutch schools in multivariate nonparametrics seemed to be following somewhat similar paths and there were successful international meetings that connected these between the different groups. Michael Greenacre, one of Benzécri's best known students has written many books in English making the methods popular in social and ecological sciences.

然而，随着法国人与英国的约翰·高尔（John Gower）和弗兰克·克里切利（Frank Critchley）等研究人员接触，一个更广泛的群体开始分化。日本和荷兰的多元非分型学校似乎在走一些相似的道路，而且成功的国际会议将不同群体之间的联系联系起来。Michael Greenacre是Benzécri最著名的学生之一，他用英语写了很多书，使这种方法在社会和生态科学中很受欢迎。


Today, we can see the influences of the "Euclidean" school epitomized by Cailliez and Pages (1976) in the development of kernel methods. Clustering analyses have certainly remained center stage. Multitable coefficients such as distance correlations are now very popular (Josse and Holmes 2016). Visualization was an important early factor in the success of the methods. In some sense, one can even regard today's stochastic block models as a natural extension of Bertins' early graphical matrix block methods developed in Semiologie Graphique (Bertin 1973).

今天，我们可以看到Cailiez和Pages（1976）所概括的“欧几里德”学派对内核方法发展的影响。聚类分析无疑仍处于中心阶段。距离相关性等多表系数现在非常流行（Josse和Holmes 2016）。可视化是这些方法成功的重要早期因素。在某种意义上，人们甚至可以将今天的随机块模型视为Bertin在Semiologie Graphique（Bertin 1973）中开发的早期图形矩阵块方法的自然扩展。


We note that we were lucky that Donoho's hero, John Chambers liked to come to France. In 1986, he showed up in Montpellier with the tape for a new software programming language called S (Chambers et al. 1988). S became an important tool in developing and teaching French methods. It was very popular in the early 1990s with ecologists, food scientists, and agronomical engineers (Chessel, Dufour, and Thioulouse 2004).

我们注意到，我们很幸运，Donoho的英雄约翰·钱伯斯喜欢来到法国。1986年，他带着一种叫做S的新软件编程语言的磁带出现在蒙彼利埃（Chambers等人，1988）。S成为发展和教授法语方法的重要工具。20世纪90年代初，它在生态学家、食品科学家和农学工程师中非常流行（Chessel、Dufour和Thioulouse 2004）。


Data science in France is now alive and well, most of all because the young French community has become multilingual, speaking and writing in English, R, and python.

法国的数据科学现在蓬勃发展，最重要的是因为年轻的法语社区已经变得多语言，可以用英语、R和python进行口语和写作。

## References

Benzécri, J. P. (1973, 1976), L'analyse des Données (Tome 1 et 2), Paris: Dunod. [768]

— (1982), Histoire et Préhistoire de L'analyse des Données (Dunod), with the texts Published in 1976-77 in "Les Cahiers de L'analyse des Données."

Bertin, J. (1973), Sémiologie Graphique, Paris: Flammarion. [768]

Cailliez, F., and Pages, J. P. (1976), Introduction à L'analyse des Données, Paris: SMASH. [768]

Becker, R., Richard, A., Chambers, J. M., and Wilks, A. R. (1988), The New S language, Pacific Grove, CA: Wadsworth \& Brooks. [768]

Chessel, D., Dufour, A. B., and Thioulouse, J. (2004), "The ade4 Package I: One-Table Methods," R News, 4, 5-10. [769]

Diday, E. (1973), "The Dynamic Clusters Method in Nonhierarchical Clustering," International Journal of Computer and Information Sciences, 2, 62-88. [768] Escofier, B., and Pagès, J. (1998), Analyse Factorielles Simples et Multiples: Objectifs, Méthodes et Interprétation, Paris: Dunod.

Escofier-Cordier, B. (1969), "L'Analyse Factorielle des Correspondances," Cahiers du BURO (Bureau Universitaire de Recherche Opérationnelle), 13, 25-59. [768]

Holmes, S. (2008), "Multivariate Data Analysis: The French Way," in Probability and statistics: Essays in honor of David A. Freedman, eds. Deborah Nolan and Terry Speed, Beachwood, OH: Institute of Mathematical Statistics, pp. 219-233. [768]

Josse, J., and Holmes, S. (2016), "Tests of Independence and Beyond," Statistics Surveys, 10, 132-167. [768]

Lebart, L. (2008). "About History of Multivariate Exploratory Data Analysis," Electronic Journal for History of Probability and Statistics, 32, 159188. [768]

Lebart, L., and Saporta, G. (2014), "Historical Elements of Correspondence Analysis and Multiple Correspondence Analysis," in Visualization and Verbalization of Data (Blasius et Greenacre), eds. G. Blasius and M. Greenacre, Chapman \& Hall.

Le Roux, B., and Rounet, H. (2004), "Historical Sketch," in Geometric Data Analysis, Springer Science \& Business Media.

Lebaron, F., and Le Roux, B. (2015), La méthodologie De Pierre Bourdieu en Action: Espace Culturel, Espace Social et Espace Social, Paris: Dunod. [768]

Murtagh, F. (2005), Correspondence Analysis and Data Coding With Java and R, Boca Raton, FL: Chapman \& Hall. [768]

Saporta, G. (1976, 2006, 2011), Probabilités, Analyse des Données et Statistique, Edition Technip, France.


#  Greater Data Science Ahead!

# 未来更大的数据科学！

## Stephanie Hicks ( 6}

Department of Biostatistics and Computational Biology at Dana-Farber Cancer Institute; Department of Biostatistics at Harvard T.H. Chan School of Public Health, Boston, MA

Dana Farber癌症研究所生物统计学和计算生物学系；马萨诸塞州波士顿哈佛T.H.陈公共卫生学院生物统计学系


David Donoho's "50 Years of Data Science" provides an insightful, historical context and a progressive vision for teaching and performing scientific research in the emerging and evolving field of Data Science and how it relates to Statistics. In my opinion, the main purpose of this article is to encourage faculty in Departments of Statistics and Biostatistics, Deans, and Presidents to embrace a new, "would-be entity as an enlargement of traditional academic statistics," referred to "Greater Data Science (GDS)," which defines Data Science as the "science of learning from data," and "is not the same as the Data Science being touted today," referred to as "Lesser Data Science." I thoroughly agree with Donoho's vision of Data Science and I am optimistic his vision will become a reality in the near future.

大卫·Donoho（David Donoho）的《数据科学50年》（50 Years of Data Science）为在新兴和不断发展的数据科学领域及其与统计学的关系中教授和开展科学研究提供了富有洞察力的历史背景和进步的愿景。在我看来，这篇文章的主要目的是鼓励统计和生物统计学系、院长和校长们接受一种新的，“潜在实体是传统学术统计的扩展”，被称为“大数据科学（GDS）”，它将数据科学定义为“从数据中学习的科学”，“与今天被吹捧的数据科学不同”，被称作“小数据科学”我完全同意Donoho的数据科学愿景，我对他的愿景将在不久的将来成为现实感到乐观。


Here, I would like to offer the following two perspectives on this piece: the first as a co-instructor of an Introduction to Data Science course and the second as an applied statistician in the early stages of my career with a passion for using data science to solve real-world problems.

在这里，我想就这篇文章提出以下两个观点：第一个是作为数据科学入门课程的联合讲师，第二个是作为职业生涯早期的应用统计学家，热衷于使用数据科学解决现实问题。


## What is Wrong With Current Data Science Masters' Programs?

## 当前的数据科学硕士课程有什么问题？


Donoho argues the main problem with current Data Science Masters' programs is that they are based on "compromises," namely, removing material from a traditionally defined masters program, such as statistics, to make room for and combine with material from another traditionally defined masters program, such as computer science. This "helps administrators to quickly get a degree program going, without providing any guidance about the long-term direction of the program and about the research which its faculty will pursue." However, it fails to lead to a consensus of the definition of "Data Science," as observed in a recent roundtable discussion on Data Science education in December 2016 (http://sites. nationalacademies.org/DEPS/BMSA/DEPS_175092).

Donoho认为，当前数据科学硕士课程的主要问题是，它们基于“妥协”，即从传统定义的硕士课程（如统计学）中删除材料，以腾出空间并与另一传统定义的大师课程（如计算机科学）中的材料相结合。这“有助于管理人员快速完成学位课程，而无需对课程的长期方向及其教师将从事的研究提供任何指导。”然而，正如2016年12月最近一次关于数据科学教育的圆桌讨论中所观察到的那样，它未能导致对“数据科学”定义的共识(http://sites.国家学院。org/DEPS/BMSA/DEPS_175092）。


A second problem with current masters programs is that they frequently fail to frame the data analysis around a realworld application. Training typically consists of "mathematically demonstrating that a specific method is an optimal solution to something, and then illustrate the method with an unrealistically clean dataset that fits the assumptions of the method in an equally unrealistic way. When students use this approach to solve problems in the real-world, they are unable to ... identify the most appropriate methodological approach when it is not spoon fed" (Hicks and Irizarry 2017). Donoho suggests incorporating the idea of a Common Task Framework (CTF) from Mark Liberman into the curriculum, where a common task is defined for competitors to "infer a class prediction rule from training data," such as the Netflix Challenge. He argues the CTF "leads immediately to applications in real-world [problems]." Alternative approaches have been previously suggested as solutions such as teaching statistics through in-depth case studies (Nolan and Speed 1999). This is the approach Rafael Irizarry and I used to develop and to teach Introduction to Data Science courses at Harvard (http://datasciencelabs.github.io).

当前主程序的第二个问题是，它们经常无法围绕真实世界应用程序构建数据分析框架。培训通常包括“从数学上证明一种特定的方法是某件事情的最佳解决方案，然后用一个不真实的干净数据集来说明该方法，该数据集以同样不现实的方式符合该方法的假设。当学生使用这种方法来解决现实世界中的问题时，他们无法……确定最合适的方法。”Donoho建议将Mark Liberman提出的共同任务框架（CTF）的理念纳入课程中，在课程中为竞争对手定义共同任务，以“从训练数据中推断班级预测规则”，他认为，CTF“立即导致现实世界中的应用[问题]。”。“以前有人建议采用替代方法作为解决方案，例如通过深入的案例研究教授统计学（Nolan和Speed 1999）。这是Rafael Irizary和我在哈佛大学开发和教授数据科学入门课程时采用的方法(http://datasciencelabs.github.io).


In addition to these problems listed above, Rafael and I recently argued there are three key skills needed to succeed in data science that are currently not prioritized, which can be referred to as creating, connecting, and computing (Hicks and Irizarry in press). For example, a data scientist is often required to be "active; they are expected to create and to formulate questions" as opposed to being "passive: wait for subjectmatter experts to come to you with questions." Furthermore, it is important to learn how to autonomously "connect the subject matter question with the appropriate dataset and analysis tools" as opposed to being "spoon-fed" (Boyer 1987) in the classroom. Finally, the skill of computing is consistent with the ideas described by Donoho. In our article, we note these are "skills that applied statisticians learn informally during their thesis work, in research collaborations with subject matter experts, or on the job in industry." While the skill of computing easily falls into the proposed "GDS3: Computing with Data" division, it is less clear in which division students would learn how to create and connect. It seems these are skills that would need to be woven into multiple divisions of GDS, but I would be interested in a larger discussion from Donoho on how he envisions the mechanics for teaching these skills in a GDS curriculum.

除了上面列出的这些问题之外，Rafael和我最近还认为，在数据科学领域取得成功需要三项关键技能，而这三项技能目前还没有被优先考虑，可以被称为创建、连接和计算（Hicks和Irizarry出版）。例如，数据科学家通常被要求“主动；他们被要求创造并提出问题”，而不是“被动：等待主题专家向你提出问题”此外，重要的是学习如何自主地“将主题问题与适当的数据集和分析工具联系起来”，而不是在课堂上“填鸭式”（Boyer 1987）。最后，计算技能与Donoho所描述的想法是一致的。在我们的文章中，我们注意到这些是“应用统计学家在论文工作、与主题专家的研究合作或在行业工作中非正式学习的技能”虽然计算技能很容易落入拟议的“GDS3：数据计算”部门，但学生将在哪个部门学习如何创建和连接还不太清楚。这些技能似乎需要融入GDS的多个部门，但我很想从Donoho那里得到一个更大的讨论，讨论他如何设想在GDS课程中教授这些技能的机制。


## Greater Data Science in the Classroom

## 课堂上的更大数据科学


Donoho describes Tukey seeing "apprenticeship with real data analysts and hence real data as the solution" to the problem of how to teach students about the science of "Data Analysis" (Tukey 1962). Therefore, it is a natural idea to structure a GDS curriculum in a format that allows an apprentice (a student) to mimic the steps of and understand the logic of choices made by an individual analyzing data (an instructor). Developing GDS courses based on in-depth case studies and structuring course activities to realistically mimic a data scientist's experience provides the most hands-on experience for a student, similar to a one-on-one apprenticeship.

Donoho描述Tukey在如何教授学生“数据分析”（Tukey 1962）这一问题上看到了“与真实数据分析师的学徒关系，从而将真实数据作为解决方案”。因此，以允许学徒（学生）模仿个人分析数据（教师）的步骤并理解其选择逻辑的格式来构建GDS课程是一个自然的想法。基于深入的案例研究开发GDS课程，并组织课程活动，以真实模拟数据科学家的经验，为学生提供最实际的体验，类似于一对一学徒。


Rafael Irizarry and I have recently shared a set of general principles for teaching data science, consistent with the ideas described by Donoho, and offered a detailed guide derived from our successful experience developing and teaching data science courses, centered entirely on case studies (Hicks and Irizarry 2017). Other examples of successful data science courses, consistent with the ideas described by Donoho, include Baumer (2015) and Hardin et al. (2015).

Rafael Irizarry和我最近分享了一套数据科学教学的一般原则，与Donoho所描述的理念一致，并提供了一份详细指南，该指南源自我们开发和教学数据科学课程的成功经验，完全以案例研究为中心（Hicks和Irizarri 2017）。其他成功的数据科学课程的例子与Donoho所描述的理念一致，包括Baumer（2015）和Hardin等人（2015）。


Finally, there are two additional features for teaching GDS proposed by Donoho, which are worth reiterating: (1) demonstrating the importance of skepticism in a data analysis and (2) not using "precooked data" in the classroom. These features are essential for students to successfully process and analyze data to solve real-world problems.

最后，Donoho提出的GDS教学还有两个额外的特点，值得重申：（1）在数据分析中证明怀疑论的重要性；（2）在课堂上不使用“预编码数据”。这些功能对于学生成功处理和分析数据以解决现实问题至关重要。


## Greater Data Science and Academic Departments

## 更大的数据科学和学术部门


As I stated at the beginning, I am optimistic about the future of this field, but as an applied statistician in the early stages of my career, I wonder how academic statistics departments will respond in terms of hiring and promotion of faculty teaching and conducting research in GDS. It is likely that these individuals will become heavily involved some subset or combination of the following: writing and maintaining useable, open-source software, publishing outside of traditional statistics journals, developing and teaching GDS courses based on in-depth case studies, and conducting "interesting-and highly impactful'GDS research.' Each of these bring their own unique challenges as it will require academic departments to evaluate nontraditional contributions, but it also brings exciting opportunities. For example, individuals actively working in and contributing to GDS today may have sought positions in industry because they saw academic statistics departments as "too narrowly focused, possibly useless or harmful" (Tukey 1962) or saw statistics as becoming "increasingly marginal" (Chambers 1993). However, these dynamic and diverse individuals may now be attracted to academic positions, which would lead to better courses for students seeking positions as applied statisticians and data scientists and more impactful and significant research contributions. If academic statistics departments embrace an entirely new science as proposed by Donoho, then it may also be time to reconsider the criteria used to evaluate the faculty involved with these endeavors (Waller 2017). My hope is these individuals will be supported by their departments and rewarded for their scholarly contributions.

正如我在一开始所说的，我对这个领域的未来感到乐观，但作为一名职业生涯初期的应用统计学家，我想知道学术统计部门在招聘和提升教师教学以及在GDS中开展研究方面将如何应对。这些人很可能会大量参与以下内容的子集或组合：编写和维护可用的开源软件，在传统统计期刊之外出版，根据深入的案例研究开发和教授GDS课程，和传导“有趣且极具影响力的‘GDS研究’。每一项研究都带来了各自独特的挑战，因为它需要学术部门评估非传统贡献，但也带来了令人兴奋的机会。例如，今天积极在GDS工作并为其做出贡献的个人可能会在行业中寻求职位，因为他们认为学术统计部门“过于狭隘，可能无用或有害”（Tukey 1962），或认为统计数据“越来越边缘化”（Chambers 1993）。然而，这些充满活力和多样化的个人现在可能会被学术职位所吸引，这将为寻求应用统计学家和数据科学家职位的学生提供更好的课程，并为他们做出更具影响力和重大的研究贡献。如果学术统计部门接受Donoho提出的全新科学，那么也可能是时候重新考虑用于评估参与这些努力的教师的标准了（Waller 2017）。我希望这些人会得到他们部门的支持，并因他们的学术贡献而得到奖励。


## Acknowledgment

"50 Years of Data Science" was presented by David Donoho at the Tukey Centennial Workshop, Princeton, NJ, September 18, 2015.

## ORCID

Stephanie Hicks (D) http://orcid.org/0000-0002-7858-0231

## References

Baumer, B. (2015), "A Data Science Course for Undergraduates: Thinking With Data," The American Statistician, 69, 334-342. [771]

Boyer, E. L. (1987), College, the Undergraduate Experience in America, New York: Harper \& Row. [770]

Chambers, J. M. (1993), "Greater or Lesser Statistics: A Choice for Future Research," Statistics and Computing, 3, 182-184. [771]

Hardin, J., Hoerl, R., Horton, N. J., Baumer, B., Hall-Holt, O., Murrell, P., Peng, R., Roback, P., Temple Lang, D., Ward, M. D. (2015), "Data Science in Statistics Curricula: Preparing Students to 'Think with Data'," The American Statistician, 69, 343-353. [771]

Hicks, S. C., and Irizarry, R. A. (2017), "A Guide to Teaching Data Science," The American Statistician, (in press). doi: http://dx.doi.org/10.1080/00031305.2017.1356747 [770,771]

Nolan, D., and Speed, T. P. (1999), "Teaching Statistics Theory through Applications," The American Statistician, 53, 370-375. [770]

Tukey, J. (1962), "The Future of Data Analysis," The Annals of Mathematical Statistics, 33, 1-67. [770,771]

Waller, L. A. (2017), "Documenting and Evaluating Data Science Contributions in Academic Promotion in Departments of Statistics and Biostatistics," bioRxiv. Available at https://doi.org/10.1101/103093 [771]