IEEE 802.11 WLAN中使用了扩展频谱通信技术，这种技术的特点是将信号散布到更宽的频带上以减少发生祖泽和干扰的机会。有两种扩频通信方式，一种是频率跳动扩频(FHSS),另外一种是直接序列扩频（DSSS).
下图表示各种扩展频谱系统的共同特点。输入数据首先进入信道编码器，产生一个接近某中央频谱的较窄带宽的模拟信号。再用一个伪随机序列对这个信号进行调制。调制的结果是大大拓宽了信号的带宽，即扩展了频谱。在接收端，使用同样的伪随机序列来恢复原来的信号，最后再进入信道解码器来恢复数据。

伪随机序列由一个使用初值（称为种子seed)的算法产生。算法是确定的，因此产生的数字序列并不是统计随机的。但如果算法设计的好，得到的序列还是能够通过各种随机性测试的，这就是被叫做伪随机序列的原因。

在网络设计阶段进行通信流量分析时可以采用简单的80/20规则，以下关于这种规则的叙述中，正确的是：
这个规则适用于内部交流较多而外部访问较少的网络。

在网络规划过程中，需要根据业务需求和应用需求来计算各个信息流量的大小，并根据通信模式，通信边界的分析，确定不同信息流在网络的不同区域和区域边界上的分布情况。
对于较为简单的网络，不需要进行复杂的痛心流量分析，仅采用一些简单的方法就可以确定痛心流量，例如80/20规则等。但是对于复杂的网络，仍必须进行复杂的通信流量分布分析。
80/20规则是一种设计思路，通过这种方式可以限制用户的不合理需求，是最优化使用网络骨干和使用昂贵的广域网连接的一种行之有效的方法。例如，如果核心交换机容量为100Mb/s,局域网至外部的带宽应限制在20Mb/s以内。80/20规则适用于内部交流较多，外部访问相对较少，网络较为简单，不存在特殊应用的网络或网段。


根据用户需求选择正确的网络技术是保证网络建设成功的关键，在选择网络技术时应考虑多种因素。以下叙述中，不正确的是：
对于大型网络工程，应该选择具有前瞻性的新的网络技术。
根据用户需求选择网络技术时应考虑如下因素：
1.通信带宽。所选择的网络技术必须保证足够的带宽，能够保证用户快速地访问应用系统。在进行选择时，不仅局限于现有的应用需求，还要适当考虑将来的带宽增长需求。
2.技术成熟性。所选择的网络技术必须是成熟稳定的技术，有些新的网络技术在尚没有大规模投入使用时，还存在着较多不确定因素，这将会给网络建设带来很多无法估量的损失。
3.可扩充性。
4.高投资产出。


The analysis phase answers the questions of who will use the system,what the system will do,and where and when it will be used.During this phase,the project team investigates any current system,identifies imporovment opportunities,and develops a concept for the new system.This phase has three steps:first,an analysis strategy is developd to guide the project team's efforts.It usually includes an analysis of the current system and its problems,and the ways to design a new system.The phase has three steps:first,an analysis strategy is developed to guide the project team's efforts.It usually includes an anaysis of the current system and its problems,and the ways to design a new system.The next step is requirements gathering.The analysis of this information- in confunction with input from the project sponsor and many other people - leads to the development of a concept for a new system.The system concept is then used as a basis to develop a set of business analysis models that describes how the business will operate if the new system were developed.The set of models typically includes models that the business will operate if the new system were developed.The set of models typically includes models that represent the data and processes necessary to support the underlying business process.Last,the analyses,system concepts,and models are combined into document called the system proposal,which is presented to the project sponsor and other key decision makers that decide whether the project should continue to move forward.



分析阶段回答谁将使用该系统，系统能做什么及系统在何时何地使用的问题。在该阶段，项目组调研当前系统、识别改进机会并开发出一个新系统的概念。这个阶段分为三个步骤：首先，开发一个分析策略来指导项目组工作。这些分析策略通畅包括了当前系统及其问题的分析和设计新系统的方法。下一步时需求收集。对这些信息（汇同系统发起人和很多其他人员的输入）的分析会导致开发出一个新系统的概念。系统概念作为开发一组业务分析模型的基础，这些模型描述了新系统开发完成后企业如何运作。这组模型通畅包含那些表示数据和过程的模型，这些数据和过程时支持底层业务过程所必需的。最后，这些分析，系统概念和模型合并到一个称为系统建议书的文档中，将被提交给项目组发起人和其他决定项目是否继续执行的主要决策人员。


随着宽带应用快速发展，用户要求系统服务提供商提供基于互联网的多种服务。数字视频监控作为一种区域级的安全监控方式，越来越为更多的用户所使用。数字视频监控告警系统采用与数字视频监控相结合的多媒体技术和基于互联网的信息传递方案，为企业用户以及个人用户提供多媒体的，不同时间，地点的信息通知服务。数字视频监控告警系统可以将用户需要查看的监控视频或告警信息，通过互联网门户系统以多种媒体方式传送给用户，方便用户随时随地了解与自身相关的视频信息。

在设计数字视频监控告警系统时，张工匠该系统划分为5个层次：服务代理层、门户服务层、流程服务总线层、业务流程应用管理层和企业服务层，其中流程服务总线时整个数字视频监控告警系统的核心，实现了服务消息，服务指令与数据的集中传递、

私密性：由于系统涉及的是各个公司或个人的专有的视频监控信息，所以要求系统保证视频信息的私密性，严格限制访问权限。
实时性：当突发事件发生时，必须反应迅速，接警控制器检测到报警信号后，必须及时告警和处理；
扩展性：由于现代技术的快速发展，系统应该具备可扩展性，以适应新技术、新设备；
稳定性：时数字视频




