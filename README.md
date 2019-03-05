# 日常学习记录(暂不归档，仅按时间序列排序)
- [平均数编码：针对高基数定性特征（类别特征）的数据预处理/特征工程](https://zhuanlan.zhihu.com/p/26308272)
- [Mean Encoding](https://necromuralist.github.io/kaggle-competitions/posts/mean-encoding/)
- [kaggle编码categorical feature总结](https://zhuanlan.zhihu.com/p/40231966)
- [Python target encoding for categorical features](https://www.kaggle.com/ogrellier/python-target-encoding-for-categorical-features)
- [Mean (likelihood) encodings: a comprehensive study](https://www.kaggle.com/vprokopev/mean-likelihood-encodings-a-comprehensive-study)
- [如何在 Kaggle 首战中进入前 10%](http://dnc1994.com/2016/04/rank-10-percent-in-first-kaggle-competition/)
- [kaggle竞赛总结](http://matafight.github.io/2017/08/05/kaggle%E7%AB%9E%E8%B5%9B%E6%80%BB%E7%BB%93/)
- [安全研究者的自我修养](https://mp.weixin.qq.com/s/WrSZpqgq6gvZwEIqghqggg)
- [安全研究者的自我修养（续）](https://mp.weixin.qq.com/s/o7IMaLMuPYuXgr5hatK5Mw)
- [[计算机考研408全网最全!!!!!]王道计算机操作系统](https://www.bilibili.com/video/av33644426)
- [分享一波关于做Kaggle比赛，Jdata，天池的经验，看完我这篇就够了](https://segmentfault.com/a/1190000012084849)
- [中断与异常](https://www.bilibili.com/video/av33644426/?p=5)
- [Java代码审计-层层推进](https://paper.tuisec.win/detail/6c0d0d6d669ee6d)
- [最新统计2005-2017年国内科研单位在国际安全顶级会议中发表文章量统计](https://mp.weixin.qq.com/s/kd4S6hCE_GPpPGbp1aD5Jw)
- [安全人员发展方向杂谈](https://zhuanlan.zhihu.com/p/54936058)<br>
**安全发展-职业规划**：甲方安全发展路线：硬核技术型--->大厂实验室和安全研究岗 非硬核技术型--->互联网企业安全建设之红蓝、技术运营、安全管理
- [我的面经，渗透测试](https://xz.aliyun.com/t/2091)
- [一套实用的渗透测试岗位面试题，你会吗？](http://www.shungg.cn/?post=70)
- [Deep Exploit: Fully automatic penetration test tool using Machine Learning](https://securityonline.info/deep-exploit/)
- [Github:Deep Exploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit)
- [Github:GyoiThon](https://github.com/gyoisamurai/GyoiThon)
- [安全扫描自动化检测平台建设(Web黑盒 中)](https://www.secpulse.com/archives/52464.html)
- [关于风控预警体系的搭建方案](https://mp.weixin.qq.com/s/2r61XB_Po4s3ihkLy46xbA)<br>
**业务安全-风控**：快速发现异常和准确定义风险。通过核心指标的变化发现异常片段及实体、通过聚类手段发现异常簇下全部实体；异常实体抽样--->无感知人工审核--->有针对性制定风险阈值
- [网络安全即将迎来机器对抗时代？](https://zhuanlan.zhihu.com/p/26093848)<br>
**智能安全-智能攻击**：国外已经在研究利用机器学习打造更智能的攻击工具，比如深度强化学习，就是深度学习和强化学习的结合，可以感知环境，做出最优决策，可能被应用到漏洞扫描器里，使扫描器能够自动化地入侵目标。<br>
**个人理解**：国外已有案例Deep Exploit就是利用深度强化学习结合metasploit进行自动化地渗透测试，国内还没有看到过相关公开案例。由于学习门槛高、安全本身攻击场景需要精细化操作、弱智能化机器学习导致的机器学习和安全场景结合深度不够等一系列的问题，已有的机器学习+安全的大多数研究主要集中在安全防护方面，机器学习+攻击方面的研究较少且局限，但是我相信这个场景很有潜力，或许以后就成为蓝方的攻击利器。
- [企业安全建设之HIDS](https://www.freebuf.com/articles/es/194510.html)
- [保障IDC安全：分布式HIDS集群架构设计](https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651750220&idx=2&sn=26e1ae8056e4fd7db5e953e946a00b78&chksm=bd12a6018a652f17643ccf86264ea226a5d881c4dd2911772893e0c5d848f95f1f8de74b786d&mpshare=1&scene=1&srcid=0117j91c1pFiorQDDMN0XQka#rd)
- [点融开源AgentSmith HIDS--- 一套轻量级的HIDS系统](https://mp.weixin.qq.com/s?__biz=MzI5MjE4MDc4OQ==&mid=2247483961&idx=1&sn=2736aad509f08c20d82cfc08b62da27a&chksm=ec040463db738d754cce84506c098caca891b58740e1b38b3621f752f805eb1c02ebf0e2ac73&mpshare=1&scene=1&srcid=1226ZgmHAUTfeYMuLFPWyuHS#rd)
- [企业安全建设—基于Agent的HIDS系统设计的一点思路](https://xz.aliyun.com/t/1732)<br>
**企业安全-入侵检测-主机入侵检测**：美团的系统性实践非常值得学习。从需求描述，产品经理提出需求->分析需求，总结产品架构要符合的特性->技术难点，分析遇到的技术挑战->架构设计与技术选型->分布式HIDS集群架构图->编程语言选择->产品实现。
- [初探机器学习检测 PHP Webshell](https://paper.seebug.org/526/)
- [基于机器学习的 Webshell 发现技术探索](https://mp.weixin.qq.com/s/1V0xcjH-6V5qJoJILP0pJQ)
- [带你读神器之KunPeng源代码分析](https://mp.weixin.qq.com/s/JLMaygM_MioszehGYpY2rw)
- [一组图文，读懂深度学习中的卷积网络到底怎么回事？](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247497838&idx=1&sn=0155aec301bfd63af03fb17727421e1e&chksm=e814dc60df635576971ccd515c440721af1e4d3c256d421953bc4944d2e724c476c5a689f197&mpshare=1&scene=1&srcid=0211JyZWQrYdounFDM2LW3AE&pass_ticket=hAXdmKc6AZ3DdksFdOmip3HL8cWLkL5u880JMyZ2etpYu1WnmEdvgA09xYgh9Im%2B#rd)<br>
**算法-深度学习-卷积神经网络**：卷积层参数：内核大小（卷积视野3*3）、步幅（下采样2）、padding（填充）、输入和输出通道。卷积类型：引入扩张率参数的扩张卷积、转置卷积、可分离卷积。
- [机器学习算法集锦：从贝叶斯到深度学习及各自优缺点](https://mp.weixin.qq.com/s/idxuzwUKG_Q1yUtpipG4Xw)<br>
**算法-机器学习**：主要从算法的定义、过程、代表性算法、优缺点解释回归、正则化算法、人工神经网络、深度学习||决策树算法、集成算法||支持向量机||降维算法、聚类算法||基于实例的算法||贝叶斯算法||关联规则学习算法||图模型。<br>
**个人理解**：回归系列主要基于线性回归和逻辑回归衍生，包括回归、正则化算法、人工神经网络、深度学习；树系列主要基于决策树衍生，包括决策树和基于树的集成学习算法；支持向量机属于老牌算法；降维算法和聚类算法主要基于数据的内在结构描述数据；基于实例的算法实际上并没有训练的过程，代表性算法是KNN，基于记忆的学习；贝叶斯算法利用贝叶斯定理计算输出概率；关联规则学习算法能够提取数据中变量之间的关系的最佳解释；图模型是一种概率模型，可以表示随机变量之间的条件依赖结构。
- [APT detection based on machine learning](https://mp.weixin.qq.com/s?__biz=MzU5MTM5MTQ2MA==&mid=2247484139&idx=1&sn=0da63a49f341eccc0bb48c954d8ebbb4&chksm=fe2efd60c95974767521fe6a6b7257a1d05e5482fc7ddeda281bdf0f0deb20add82d1a82d8ec&mpshare=1&scene=1&srcid=&pass_ticket=bjnNiDKomd79pQvRonW%2BXsTe6JrO%2FFs6oII12dZaLBPuQOtNK6Rzh9WSJ%2B%2F89ZUA#rd)<br>
**安全研究-APT检测模型**：本篇论文提出一种APT检测模型，通过在APT生命周期的多个环节进行检测，并将各个环节告警事件进行关联，并使用机器学习训练检测模型。和我的想法略有相似，之前想过可以用图模型或者规则关联算法进行关联以此重构攻击链，但是本篇文章好像是把关联的事件集作为输入数据输入到一个预测模型中去训练。这么做的目的是要完整地描述一个APT场景下的安全事件集，降低误报率，提高准确率，避免传统APT单环节检测造成的漏报、误报的问题。但是本文也存在一些问题，比如缺少APT数据源问题，缺少安全数据一直是个难题，导致本文提出的模型未能在真实的环境中论证。
- [安全资料：企业实验室、安全社区、安全团队、安全工具等](http://blkstone.github.io/friend/)
- [算法工程师必须要知道的面试技能雷达图](https://zhuanlan.zhihu.com/p/54089811)（学到了）<br>
**算法-技术素质**：算法工程师必备技术素质拆分：知识、工具、逻辑、业务。在满足最小要求的基础上，算法工程师在这四个方面的能力是相对全面的，既包括”算法“，也包括”工程“，而大数据工程师则着重”工具“，研究员则着重”知识“和”逻辑“。<br>
针对安全业务的算法工程师就是安全算法工程师。为了便于理解，举个例子，如果用XGBoost解决某个安全问题，那么可以由浅入深理解，把知识、工具、逻辑、业务四个方面串起来：

        1.GBDT的原理（知识）
    	2.决策树节点分裂时是如何选择特征的？（知识）
    	3.写出Gini Index和Information Gain的公式并举例说明（知识）
    	4.分类树和回归树的区别是什么（知识）
    	5.与Random Forest对比，理解什么是模型的偏差和方差（知识）
    	6.XGBoost的参数调优有哪些经验（工具）
    	7.XGBoost的正则化和并行化分别是如何实现的（工具）
    	8.为什么解决这个安全问题会出现严重的过拟合问题（业务）
    	9.如果选用一种其他模型替代XGBoost或改进XGBoost你会怎么做？为什么？（业务、逻辑、知识）。<br>

	以上，就是以“知识”为切入点，不仅深度理解了“知识”，也深度理解了“工具”、“逻辑”、“业务”。<br>
- [谈谈互联网企业安全的发展方向](白帽子讲Web安全附录)<br>
**企业安全-互联网企业安全-发展方向**：由浅入深分为四个目标：1、消灭漏洞驱使，第一个目标是让工程师写出的每一行代码都是安全的，由此诞生SDL，SDL又衍生技术研究和技术产品，比如代码安全扫描工具的研究和fuzzing。2、有了SDL还无法100%安全，所以第二个目标是让所有已知、未知的攻击，都能在第一时间发现，并迅速报警和追踪。挑战：海量数据和复杂需求 方案：超强计算能力和立体化模型。3、第三个目标是让安全成为公司的核心竞争力，深入到每个产品的特性中，能够更好地引导用户使用互联网的习惯。4、最后一个目标是能够观测到整个互联网安全趋势的变化，对未来一段时间内的风险做出预警。<br>
在互联网公司做安全一定要有想象力，同时紧密关注其他技术领域的发展，这样就不会止步于几种漏洞的研究，而会发现有很多有趣的事情正等着去做，这是一个非常宏伟的蓝图。
- [利用机器学习检测HTTP恶意外连流量](https://www.anquanke.com/post/id/107124)（优秀）<br>
**安全研究-恶意样本-恶意HTTP外连流量检测**：**总体思路**：**1、数据收集**，沙箱运行恶意样本，收集恶意流量，人工区分恶意流量和白流量，再根据威胁情报对恶意流量划分家族。**2、数据分析**（特征工程）：同一家族恶意外连流量的相似性，可以考虑使用聚类算法将同一家族的流量聚为一类，提取它们的共性，形成模板，再用模板检测未知流量。**3、算法：训练阶段**：提取HTTP外连流量--->提取请求头字段--->泛化--->相似度计算（**请求头中字段特异性加权再计算相似性**）--->层次聚类--->生成恶意外连流量模板（聚类中该字段并集作为该字段在模板中的值）。**检测阶段**：未知HTTP外连流量--->提取请求头字段--->泛化--->与恶意模板匹配--->判断相似度是否超过阈值（阈值确定）
- [凝聚式层次聚类算法的初步理解](https://zhuanlan.zhihu.com/p/27659767)<br>
**机器学习-无监督学习-层次聚类**：算法步骤：计算邻近度矩阵--->（合并最接近的两个簇--->更新邻近度矩阵）（repeat），直到达到仅剩一个簇或达到终止条件。
- [推荐算法入门（1）相似度计算方法大全](https://zhuanlan.zhihu.com/p/33164335)<br>
**机器学习-层次聚类-相似性计算**：曼哈顿距离、欧式距离、切比雪夫距离、余弦相似度、皮尔逊相关系数、Jaccard系数
- [一篇文章带你深入理解漏洞之 XXE 漏洞](https://xz.aliyun.com/t/3357)<br>
**安全技术-漏洞分析-XXE漏洞**：XXE的原理：调用外部实体，XXE的利用：利用通用实体、参数实体、外部实体、内部实体进行文件读取，内网主机和端口探测、内网RCE（php下需要expect扩展的支持）
- [浏览器解码与xss](https://blog.csdn.net/he_and/article/details/80588409)(**原文中有一处错误“html实体编码后“应该是`&#x5c;&#x75;&#x37;&#x32;` 产生的原因就是浏览器的html自解码**)<br>
**前端技术-浏览器技术-解码顺序**：浏览器解码主要涉及到两个部分：渲染引擎和js解析器。解码顺序：在什么环境下就进行什么解码，解码顺序为：最外层的环境对应的编码最先解码。举个例子:在`<a href=javascript:alert(1)>click</a>`中alert(1)处在html->url->js环境中。

        1、<a href=javascript:al\u65rt(1)>click</a> 采用unicode编码e，html和url环境下都不能解码，只有在js环境下才能解码为字符e，所以不会弹窗
    	2、<a href=javascript:al%65rt(1)>click</a> 采用url编码，在执行js前，url解码%65，所以到了js引擎启动时，看到了完整的alert(1)
    	3、<a href=javascript:alert(1)>click</a> html实体解码先执行了
    	4、<a href=java%61script:alert(1)>click</a> 在url解码环节，不会认为javascript是伪协议，会出现错误。
		5、<a href=# onclick="alert('&#x27;&#x29;;alert&#x28;&#x27;2');">click</a> htmlparser会优先于JavaScript parser执行，所以解析过程是htmlencode的字符先被解码，然后执行JavaScript事件

  	**浏览器解码顺序是XSS中bypass的基础**。
- [python requests库流程简析](https://www.jianshu.com/p/a5e98489dcb8)<br>
**基础研究-计算机网络-python requests库实现**：socket->httplib->urllib->urllib3->requests。requests.get的内部调用流程：requests.get->requests()->Session.request->Session.send->adapter.send->HTTPConnectionPool(urllib3)->HTTPConnection(httplib)。

		1、socket：是TCP/IP最直接的实现，实现端到端的网络传输
		2、httplib：基于socket库，是最基础最底层的http库，主要将数据按照http协议组织，然后创建socket连接，将封装的数据发往服务端
		3、urllib：基于httplib库，主要对url的解析和编码做进一步处理
		4、urllib3：基于httplib库，相较于urllib更高级的地方在于用PoolManager实现了socket连接复用和线程安全，提高了效率
		5、requests：基于urllib3库，比urllib3更高级的是实现了Session对象，用Session对象保存一些数据状态，进一步提高了效率
- [人工智能反欺诈三部曲之：设备指纹](https://zhuanlan.zhihu.com/p/31712434)<br>
**智能安全-业务安全-设备指纹**：ip、cookie、**设备ID**；**主动式设备指纹**：使用JS或SDK从客户端抓取各种各样的设备属性值，然后组合，通过hash算法得到设备ID；**优点**：Web内或者App内准确率高。**缺点**：主动式设备指纹在Web与App之间、不同的浏览器之间，会生成不同的设备ID，无法实现跨Web和App，不同浏览器之间的设备关联；由于依赖客户端代码，指纹在反欺诈的场景中对抗性较弱。**被动式设备指纹**：从数据报文中提取设备OS、协议栈和网络状态的特征集，并结合机器学习算法识别终端设备。**优点**：弥补了主动式设备指纹的缺点。**缺点**：占用处理资源多；响应时延比主动式长。
- [分类模型评估之ROC-AUC曲线和PRC曲线](https://blog.csdn.net/pipisorry/article/details/51788927)<br>
**机器学习-模型评估-ROC、AUC、PRC**：
- [HTTP DATASET CSIC 2010](http://www.isi.csic.es/dataset/)<br>
**机器学习-安全数据集-CSIC2010**：基于e-Commerce Web应用自动化生成的安全数据集，包含36000个正常请求和25000个异常请求，异常请求包括：SQL注入、缓冲区溢出、信息收集、文件泄露、CRLF注入、XSS等。
- [从内容产出看安全领域变化](https://mp.weixin.qq.com/s/MZp_BOPPrX4hTgP5s5hUPw)<br>
**安全发展-安全格局-技术格局**：企鹅等互联网巨头开始进行流量封锁，对安全从业人员影响很大，爬不到数据，api又有限，只能上升到app hook了；技术上安全分析、数据挖掘、威胁情报的比重越来越重，**AI已经不仅仅是噱头了，智能安全势不可挡**；安全的职业发展方面，越来越多大佬们开始转型业务安全、数据安全。
- [网络安全行业竞争格局浅析](https://mp.weixin.qq.com/s/4odKGqDzyFI1CzWwVvmXEw)<br>
**安全发展-安全格局-市场格局**：基础安全防护（传统安全防护能力），中级安全防护（海量数据建模与分析能力），高级安全防护（云端威胁情报与分析能力），中高级安全防护市场广阔。此外，全文在多处凸显了人工智能技术，智能安全开始迈入开悟之坡了吗？！半数以上的人看好智能安全，也有人不看好智能安全，未来会怎么样，让我们拭目以待！
- [有关安全的面经, 实习, etc](https://github.com/SecYouth/sec-jobs/tree/master/interview-experience)<br>
**安全发展-职业发展-实习面经**：滴滴、百度（2）、360（2）、阿里（6）、腾讯（3）、b站、华为、同花顺、蘑菇街。总的来看，大佬们好强，选择大多是甲方安全部。我的理解：看了大佬们的面经和被问到的问题，真的是五花八门，有bin方向的，有数据安全方向的，也有安全运营方向的等等，有一些参考价值，但是因为方向不同，不能生硬照搬，还是得发挥自己的专长，先做自己小领域的领域专家。
- [全球最全？的安全数据网站](http://www.secrepo.com/)（有时间得好好整理一下）<br>
- [C端安全产品的未来之路](https://mp.weixin.qq.com/s/Sp15EkyNKBZvOZHrJ7zJ2w)<br>
**安全发展-安全产品-C端安全产品**：移动端安全产品是否会像前几天PC端安全产品一样迎来春天？PC时代windows是一家独大的完全开放的平台，这让第三方安全公司能够在平台和用户之间产生价值的空间足够的大，但在移动端，安卓开始封闭，就不好说了。传统安全软件围绕病毒和欺诈，而围绕**个人信息安全的C端安全产品**有一线生机。
- [NO.27 闲扯 关于数据安全](https://zhuanlan.zhihu.com/p/58146084?utm_source=wechat_session&utm_medium=social&utm_oi=663312716719067136)<br>
**安全技术-数据安全**：大数据技术、时代，**数据是很多公司最核心的资产**；传统的安全边界模糊，我们需要假设我们边界已经被渗透的同时，拥有纵深防御能力，保护信息的安全。所以在加强传统安全手段的同时，我们更应该直接把安全的重点放在数据本身上，这就是数据安全所做的工作。在做之前，有一个前提：我们要知道安全依然是为业务服务的（大部分企业安全情况下，业务>安全），所以要权衡安全性和可用性。目前企业常用的措施主要有：数据分级、数据生命周期管理、数据脱敏&数据加密、数据防泄漏。
- [一套实用的渗透测试岗位面试题](https://mp.weixin.qq.com/s/KZn6p5sk1Ae9i3m4e-XCpg)<br>
**安全技术-渗透测试**：代码执行函数：`eval、preg_replace+/e、assert、call_user_func、call_user_func_array、create_function`；命令执行函数：`system、exec、shell_exec、passthru、pcntl_exec、popen、proc_open`；img标签除了onerror属性外，还有其他获取管理员路径的方式吗？src指定一个远程的脚本文件，获取referer。
- [云安全，到底是什么一回事？](https://www.zhihu.com/question/19567976/answer/604675005?utm_source=wechat_session&utm_medium=social&utm_oi=663312716719067136)<br>
**安全技术-云安全**：云安全三大研究方向：云计算安全、安全基础设施的云化、云安全服务。在云安全未来发展趋势中也提到了数据安全协作，说明无论哪种场景，数据都是安全的重点关注对象。云安全服务可以看成厨师做饭（来自cdxy的ppt），云计算（能源）、算法（工具）、数据（原料）、工程师（厨师）、能做成什么样的饭（能提供的安全服务）
- [为什么在实际的kaggle比赛中，GBDT和Random Forest效果非常好？](https://www.zhihu.com/question/51818176/answer/595480045?utm_source=wechat_session&utm_medium=social&utm_oi=663312716719067136)<br>
**算法-树系列算法**：单模型，gradient boosting machine和deep learning是首选。gbm不需要复杂的特征工程，不需要太多时间去调参数，dl则需要比较多的时间去调网络结构。**从overfit角度理解**，两者都有overfit甚至perfect fit的能力，overfit能力越强，可塑性越强，然后我们要解决的问题就是如果把模型训练的“恰好”，比如gbm里有early_stopping功能。线性回归模型就缺乏overfit能力，如果实际数据符合线性模型的关系，那可以得到很好的结果，如果不符合的话，就需要做特征工程，可特征工程又是一个比较主观的过程。树的优势，非参数模型，gbm的overfit能力强。而random forest的perfact fit能力很差，这是因为rf的树是独立训练的，没有相互协作，虽然是非参数型模型，但是浪费了这个先天优势。
- [Data-Knowledge-Action: 企业安全数据分析入门](https://www.cdxy.me/?p=803)（优秀，学到了）<br>
**企业安全建设-数据分析**：**1、让模型理解业务，基于业务历史行为建立异常基线，在异常的基础上检测威胁；将运营结果反馈到模型，将误报视作正常行为回流。2、安全运营可运营，降低事件调查成本，自动化信息收集与聚合。3、随着数据的积累，安全数据分析将向基于图结构的高级知识表达方式发展。（这点深表赞同）4、对场景、攻击模式、数据的认识深度，远比选择工具重要。**
- [从传统安全转行风控领域的心路历程，兼谈黑产和风控行业趋势](https://mp.weixin.qq.com/s/GWOjp1E2B4J0efUjFBnp8Q)<br>
**业务安全-风控**：风控领域斗争日趋激烈，黑产已经从高度专业化、分工明确的团伙进化为产业化运作的公司，现在风控需要有基础安全技术支撑（传统安全），随着司法机关对黑灰产的高压打击，未来大企业会关注风控供应商的产品能力和合规合法性。
- [企业安全建设技能树v1.0发布](https://mp.weixin.qq.com/s/JFWxsdnEPI5NEU1PlR-FjA)<br>
企业安全建设-安全管理：包括六大部分：说明、安全观、安全治理、通用技能、专业技能、优质资源
- [分类模型的性能评估——以 SAS Logistic 回归为例 (3): Lift 和 Gain](https://cosx.org/2009/02/measure-classification-model-performance-lift-gain/)
- [时间序列数据的聚类有什么好方法？](https://www.zhihu.com/question/50656303/answer/584063648?utm_source=wechat_session&utm_medium=social&utm_oi=663312716719067136)<br>
**机器学习-聚类-时间序列**：传统的机器学习数据分析领域：提取特征，使用聚类算法聚集；在自然语言处理领域：为了寻找相似的新闻或是把相似的文本信息聚集到一起，可以使用word2vec把自然语言处理成向量特征，然后使用KMeans等机器学习算法来作聚类；另一种做法是使用Jaccard相似度来计算两个文本内容之间的相似性，然后使用层次聚类的方法来作聚类。常见的聚类算法：基于距离的机器学习聚类算法（KMeans）、基于相似性的机器学习聚类算法（层次聚类）。对时间序列数据进行聚类的方法：时间序列的特征构造、时间序列的相似度方法。如果使用深度学习的话，要么就提供大量的标签数据；要么就只能使用一些无监督的编码器的方法。
- [Categories of algorithms non exhaustive ](https://static.coggle.it/diagram/WHeBqDIrJRk-kDDY)(学到了)<br>
**算法-算法体系**：学到了搭建自己的算法体系。
- [[校招经验] BAT机器学习算法实习面试记录](http://rs.xidian.edu.cn/forum.php?mod=viewthread&tid=929712&extra=page%3D1)(学到了)<br>
**算法-机器学习-面试**：根据面试常遇到的问题再深入理解机器学习，储备自己的算法知识库。
- [浅析白盒审计中的字符编码及SQL注入](https://www.leavesongs.com/PENETRATION/mutibyte-sql-inject.html#1452)(优秀，学到了)<br>
**安全技术-基于字符编码的注入攻击**：一个gbk编码的汉字，占2个字节，一个utf-8编码的汉字，占用3个字节。宽字节注入是利用mysql的特性，mysql在使用gbk编码的时候，会认为两个字符是一个汉字（gbk下，前一个ascii码要大于128，才到汉字的范围；gb2312的编码取值范围：高位`0xA1-0xF7`，低位`0xA1-0xFE`，而`\`是`0x5c`，不在低位范围中，所以`0x5c`不是gb2312中的编码，所以不会被吃掉。把这个思路拓宽到所有的多字节编码，只要低位的范围中含有`0x5c`的编码，就可以进行宽字节注入）。防御方案一：`mysql_set_charset+mysql_real_escape_string`,考虑到连接的当前字符集。防御方案二：将`character_set_client`设置为`binary`（二进制），`SET character_set_connection=gbk, character_set_results=gbk,character_set_client=binary`。当我们的mysql接受到客户端的数据后，会认为他的编码是`character_set_client`，然后会将之将换成`character_set_connection`的编码，然后进入具体表和字段后，再转换成字段对应的编码。然后，当查询结果产生后，会从表和字段的编码，转换成`character_set_results`编码，返回给客户端。所以，我们将`character_set_client`设置成`binary`，就不存在宽字节或多字节的问题了，所有数据以二进制的形式传递，就能有效避免宽字符注入。防御过后调用iconv时也可能出现问题。使用iconv对utf-8转gbk时，利用方式是`錦'`，原因是它的utf-8编码是`0xe98ca6`，它的gbk编码是`0xe55c`，最后变成`%e5%5c%5c%27`，两个`%5c`就是`\`，正好把反斜杠转义了。使用iconv对gbk转utf-8时，利用方式直接用宽字节注入。一个gbk汉字2字节，utf-8汉字3字节，如果我们把gbk转换成utf-8，则php会每两个字节一转换。所以，如果`\'`前面的字符是奇数的话，势必会吞掉`\`，`'`逃出限制。为什么不能用`錦'`这种方式呢，根据utf-8编码规则，`\（0x0000005c）`不会出现在utf-8编码中，所以会报错。
- [风控模型师面试准备--技术篇](https://zhuanlan.zhihu.com/p/56175215)
- [风控模型实战--"魔镜杯"风控算法大赛](https://zhuanlan.zhihu.com/p/56864235)

