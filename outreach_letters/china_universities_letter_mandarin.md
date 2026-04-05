# China Top 10 Universities Letter — Mandarin Chinese (Simplified)

## Target Universities & Contact Info

| # | University | Chinese Name | CS/AI Contact | Website |
|---|-----------|-------------|---------------|---------|
| 1 | Tsinghua University | 清华大学 | iso@tsinghua.edu.cn, info@cs.tsinghua.edu.cn | cs.tsinghua.edu.cn |
| 2 | Peking University | 北京大学 | studyatpku@pku.edu.cn, webmaster@pku.edu.cn | cs.pku.edu.cn, ai.pku.edu.cn |
| 3 | Zhejiang University | 浙江大学 | iczu@zju.edu.cn, csoffice@zju.edu.cn | cs.zju.edu.cn |
| 4 | Shanghai Jiao Tong University | 上海交通大学 | iso@sjtu.edu.cn, seiee@sjtu.edu.cn | cs.sjtu.edu.cn |
| 5 | USTC | 中国科学技术大学 | isad@ustc.edu.cn, office@ustc.edu.cn | cs.ustc.edu.cn |
| 6 | Nanjing University | 南京大学 | stuadmission@nju.edu.cn | ai.nju.edu.cn |
| 7 | Harbin Institute of Technology | 哈尔滨工业大学 | admission@hit.edu.cn | cs.hit.edu.cn |
| 8 | Beihang University | 北京航空航天大学 | admissions@buaa.edu.cn | scse.buaa.edu.cn |
| 9 | Fudan University | 复旦大学 | iso@fudan.edu.cn | cs.fudan.edu.cn |
| 10 | HUST | 华中科技大学 | admission@hust.edu.cn | cs.hust.edu.cn |

### Why each matters:
1. **Tsinghua** — #1 in China for CS. ChatGLM creators. Turing Award winner Andrew Yao's institute.
2. **Peking** — Top-tier NLP, computer vision, ML. Wangxuan Institute. National key labs.
3. **Zhejiang** — Top 3 CS. First dedicated AI school. Strong in computer vision, industrial AI.
4. **Shanghai Jiao Tong** — John Hopcroft Center (Turing Award). Knowledge graphs, medical AI, speech.
5. **USTC** — Quantum computing, speech (iFlytek born here). Close to Chinese Academy of Sciences.
6. **Nanjing** — LAMDA group (Prof. Zhou Zhihua, most cited AI researcher in China). First standalone AI school.
7. **HIT** — Top NLP group (SCIR). Defense-related AI. LTP platform. Robotics.
8. **Beihang** — Software engineering, knowledge engineering, aerospace AI. State Key Lab.
9. **Fudan** — NLP, data science, medical AI, financial AI. Shanghai tech ecosystem.
10. **HUST** — Computer vision, pattern recognition, medical imaging AI, robotics, smart manufacturing.

## Subject Line

今天你就可以拯救你的国家：一项颠覆性的「人工智能」（artificial intelligence）发明——新「军事工业复合体」（Military-industrial complex）（OpenAI、Google、Anthropic）不希望你知道的隐藏真相——以及你能为此做什么

## Full Letter

尊敬的先生/女士：

首先，我将描述问题，然后介绍一个全新的天才解决方案。

我叫 Nir Strulovitz，是一名来自以色列的**独立发明人，著有17本关于科学和技术突破的书籍**，曾是以色列国防军（IDF）和以色列埃尔比特系统公司（Elbit Systems）的专业软件开发者。我写这封信，是为了通知贵校一项在「人工智能」（artificial intelligence）领域具有革命性意义的发明——一种全新的「分布式计算」（distributed computing）架构，它将从根本上改变「人工智能」的运作方式。

**问题：美国正在通过「人工智能」对全世界实施「大规模监控」（mass surveillance）。**

现在，全世界每一个使用 OpenAI、Google 或 Anthropic 的「云计算」（cloud computing）服务的国家、企业和研究机构，都在做同一件事：把自己最敏感的数据——研究成果、知识产权、国防战略、经济机密——通过美国公司控制的服务器传输。这些公司与美国政府签有合同。这些服务器受美国法律管辖。「爱德华·斯诺登」（Edward Snowden）在2013年已经告诉了全世界——美国情报机构可以获取美国科技公司的数据。什么都没有改变。只是现在，通过「人工智能」，数据流量比以往任何时候都要大上千倍。

**「人工智能」行业一直在向全世界隐瞒一个秘密。**

他们告诉你：要获得强大的「人工智能」能力，你必须使用他们的云端。你必须把数据发送给他们（你进行「匿名化」（anonymization），但他们利用「大数据」（big data）轻易地进行「再识别」（re-identification），还原你的真实数据）。你别无选择。

**这是谎言。**

我独自一人、用一周时间发明并构建了一个完全不同的系统。它的工作原理如下：

一台较强的本地计算机运行一个「大型语言模型」（large language model），充当自动化协调者。它接收用户的请求，将其分解为完全独立的子任务，然后将每个子任务分发到「局域网」（local area network）内的不同计算机上。每台计算机运行自己完整的「大型语言模型」，独立处理自己的子任务。工作计算机之间零通信。这叫做「任务并行」（task parallelism）——不是「流水线」（pipeline）式的把模型切割分层（那种方式很慢，因为每台机器都必须等待上一台），也不是所谓的多智能体系统在同一台计算机上轮流运行（那种方式很弱，因为根本不是并行）。

**这意味着什么？没有任何数据离开你的建筑。一个字节都没有。**

**这是一种全新的「并行计算」（parallel computing）范式——学术界尚未充分研究的领域。**

当前学术界对分布式「人工智能」的研究主要集中在两种方法：多智能体系统（共享同一台计算机，顺序执行——本质上不是真正的并行）和「流水线」式模型并行（Petals、Exo等——将模型层分布在多台机器上，但受限于机器间通信瓶颈）。我的方法是第三种——真正的「任务并行」：每台机器运行独立的完整模型，处理独立的子任务，机器之间零通信。这种方法在现有文献中几乎没有被探索过。

**中国在这场革命中拥有巨大的战略优势。**

中国在小型和中型「大型语言模型」方面已经是世界领先者——DeepSeek、Qwen（通义千问）、GLM（智谱）。这些模型之所以如此出色，是因为美国的芯片限制迫使中国的工程师在效率上创新，而不是靠堆砌算力。

我的发明让小型模型成为制胜策略。不再需要一个巨大的模型。你需要的是许多台普通计算机，每台运行一个高效的小型模型，所有计算机同时「并行计算」工作。

中国有什么？14亿人口。数以亿计的个人计算机。世界上最好的小型「人工智能」模型。我的发明将这三者结合成一个任何其他国家都无法匹敌的优势。

**我相信贵校的研究团队将会对以下研究方向感兴趣：**

- 任务分解算法的优化——如何更智能地将复杂请求分解为独立子任务
- 协调者模型的效率提升——如何让协调者更高效地分配和整合工作
- 容错机制——当个别工作机器出现故障时如何保证整体任务完成
- 安全性研究——如何在完全本地化的环境中保证系统安全
- 大规模部署——如何将这种架构扩展到数百甚至数千台机器

**这项技术是完全「开源软件」（open-source software），任何人都可以审查、修改和改进代码：**

开源代码：https://github.com/strulovitz

短片动画视频——私有模式（组织如何在数据零外泄的情况下运行「人工智能」）：
https://www.youtube.com/watch?v=o8R58VuJFx8 （3分08秒）

短片动画视频——公共模式（「分布式计算」如何跨越多台计算机协同工作）：
https://www.youtube.com/watch?v=PTnAqZCAClw （6分23秒）

一本非技术性书籍，讲述这个项目背后的**个人故事，以及这个系统未来的发展方向——我还有更多的发明和想法**：
https://github.com/strulovitz/TheDistributedAIRevolution/blob/main/README.md

我正在积极寻求学术合作——联合研究、论文合作、或作为客座研究员——与任何有兴趣在此架构基础上开展研究的大学或研究机构合作。我可以远程工作，随时可以开始。

联系方式：
- 电子邮件：nir.strulovitz@gmail.com
- 手机：+972-54-475-2626
- GitHub：https://github.com/strulovitz

此致敬礼，
Nir Strulovitz

## Shortened Version for Forms (500 chars each)

### Part 1:

今天你就可以拯救你的国家。新军事工业复合体（OpenAI、Google、Anthropic）不希望你知道的人工智能真相。我叫Nir Strulovitz，来自以色列，独立发明人，著有17本科学技术突破书籍，前以色列国防军（IDF）和埃尔比特系统公司软件开发者。首先描述问题，然后介绍解决方案。美国正通过人工智能对全世界实施大规模监控。使用OpenAI、Google、Anthropic云计算的所有国家和研究机构，都在把研究成果、知识产权、国防数据通过美国服务器传输。斯诺登2013年已揭露此事。他们说必须用云端，必须发送数据（你匿名化，但他们用大数据轻易再识别）。这是谎言。我用一周发明了新系统：本地计算机运行大型语言模型作协调者，将任务分解为独立子任务，分发到局域网内各计算机独立处理，机器间零通信。这叫任务并行——一种学术界尚未充分研究的全新并行计算范式。没有数据离开建筑。

### Part 2:

中国有巨大战略优势：DeepSeek、Qwen、GLM世界领先，14亿人口，数亿台计算机。我的发明让小型模型成为制胜策略——多台普通计算机各运行小模型同时并行工作。研究方向：任务分解优化、协调者效率提升、容错机制、安全性、大规模部署。技术完全开源可审查。代码：github.com/strulovitz 私有模式视频（3分）：youtube.com/watch?v=o8R58VuJFx8 公共模式视频（6分）：youtube.com/watch?v=PTnAqZCAClw 书籍（个人故事·未来发展·更多发明）：github.com/strulovitz/TheDistributedAIRevolution 寻求学术合作——联合研究、论文合作、客座研究员。联系：nir.strulovitz@gmail.com 电话：+972-54-475-2626。此致敬礼，Nir Strulovitz

## Sending Order

1. Tsinghua CS — info@cs.tsinghua.edu.cn (ChatGLM creators, most relevant)
2. Tsinghua International — iso@tsinghua.edu.cn
3. Peking University — studyatpku@pku.edu.cn
4. Zhejiang University — csoffice@zju.edu.cn + iczu@zju.edu.cn
5. Shanghai Jiao Tong — iso@sjtu.edu.cn + seiee@sjtu.edu.cn
6. USTC — isad@ustc.edu.cn + office@ustc.edu.cn
7. Nanjing University — stuadmission@nju.edu.cn (AI school: ai.nju.edu.cn)
8. HIT — admission@hit.edu.cn
9. Beihang — admissions@buaa.edu.cn
10. Fudan — iso@fudan.edu.cn
11. HUST — admission@hust.edu.cn
