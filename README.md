# Interview-Exp

▲联想-C++
C++：
  面向对象特点？
  虚函数相关？
  const int * 与 int * const？

计网
  HTTP 与 HTTPS？
  SSL加密流程？
  三次握手与四次挥手？
  为什么第四次挥手后需要等2MSL？

英文介绍项目

▲得物-iOS
  为什么投iOS开发？
  iOS开发是做什么的？

服务器项目：
  介绍？
  特点？
  QPS？性能？

操作系统：
  进程与线程？

C++：
  堆与栈的区别？
  函数存储在哪里？
  函数指针可以释放掉代码区内容吗？
  数组越界访问会发生什么？（结果跟编译器有关，但是如果访问到的话得到的也是一个未知的值，如果尝试修改的话可能会导致“数组越界访问或堆栈溢出”的异常）

计网：
  网址栏输入谷歌后发生什么？
  为什么进不去？被墙了是什么错误？（403：禁止访问，网站被封锁了；404：未找到；503：错误网关，代理服务器也无法访问对应网址）

数学：
  贝叶斯公式：P(A|B) = P(B|A) * P(B) / P(A)

▲阿里国际-测开
  自我介绍

操作系统：
  *操作系统是什么、作用：（硬件、内存、进程、文件管理，提供用户界面或命令行，介于硬件与用户之间，用户通过操作系统对硬件进行操作）
  用户态和内核态是什么、什么时候切换（权限问题、操作系统内核、系统调用，如文件、进程）
  进程间通信的方式
  死锁的条件、如何避免死锁、解决死锁

计网：
  OSI7层模型
  键入URL发生的事
  TCP与UDP的区别

数据库：
  事务是什么、作用、特性
  索引的分类、索引的作用、什么时候创建索引
  *一条SQL语句执行发生了什么（连接、缓存、词法语法分析、检查字段和表、优化器、执行器、存储引擎）

做题：
  最大子数组和(简单，未知个数输入采用getchar()=='\n'解决)

▲多益-服务器开发
  自我介绍
  项目介绍：如何处理粘包

计网：
  TCP滑动窗口（TCP收发同步）
  TCP哪些方面设计比较好（拥塞控制：慢开始、拥塞避免、超时重传、快速重传）

C++：
  内存分配方式（栈、堆、全局区）
  指针和引用的区别（变量类型、sizeof、）
  智能指针（shared_ptr、unique_ptr、weak_ptr）
  *重载和覆盖（编译期、运行期）
  *迭代器遍历vector并且删除要注意什么、遍历map并且删除需要注意什么
  map底层（红黑树、自平衡二叉树）
  vector与list区别（内存分布、增删效率、查询效率）
  *树与二叉树区别
  归并排序（分治，直至仅有一个元素，排成局部有序，再合成整体有序）
  *面向对象特性（继承、封装、多态）

数据库：
  索引的优点与缺点（查询、增删、内存）
  索引底层（B+树、非叶节点存索引、叶节点存数据，并且有指针相连）
  其他索引（数据结构、存储类型、普通类型）
  其他类型的数据库（Redis-kv存储）
  Redis数据库了解多少（基于内存的数据库、kv存储、分布式、高可用、缓存故障<雪崩、击穿、穿透>、分布式锁机制、哨兵机制）

场景题：
  *地图软件的实时路况如何实现
  *最近学习什么新东西（集群管理？k8s？git？）
  *目标（短期、中期、长期？）
  *主要投递什么公司、什么行业
  *碰到一个概率极低的bug怎么处理
  *空闲时间怎么安排
  *关注的技术热点（chatGPT？-Transformer）
  如何学习一门新的语言
  *设计模式（单例模式、工厂模式、观察者模式）
  *应聘服务器开发的优势
  玩游戏考虑什么
  开源项目里哪个最好
  怎么看待互联网加班（正常、自己经历、不会抗拒、分析加班原因）
  对上司不满意（随和、不介意、更在意上司为人处事，而不是工作安排）

做题：
  全排列（dfs）

▲多益-HR面
  自我介绍
  对多益的认识？
  如何看待互联网公司996？
  预期工资？
  父母工作？家里的厂子不需要回去打理吗？
  如何看待学习新的语言？
  问答题复盘（为什么认为自己是N分之一、军人的天职、是否自己填写）
  能否接受毕业前实习

▲诺瓦星云-软开
  本科项目
  实习内容

计网：
  三次握手与四次挥手？

C++：
  关键字volatile？

▲顺丰-运维开发工程师
  自我介绍
  测试如何保证测试的版本与最终发布的版本一致？(每次迭代开发会给出一个版本号，测试人员在拿到当前版本号的项目后部署测试环境再进行测试，最后测试通过了测试之后也会发布同一个版本号的项目。测试环境与最终投入使用的环境有可能不一致，但是像门锁、视频等嵌入式的测试，通常测试环境就是最终投入使用的环境)
  运维开发工程师的工作
  一个项目从立项到最终发布运维的过程：立项、设计与开发、测试、部署发布、运维、迭代更新

计网：
  TCP三次握手的标志位变化
  TCP与UDP的区别

Linux：
  知道些什么命令
  vi编辑模式下如何保存并退出

MySQL：
  主从一致性

Redis：
  持久化方式：快照RDB、AOF日志

▲顺丰-二面
  自我介绍
  服务器项目相关（异步与同步的模型的区别、粘包处理）
  科研项目相关

C++：
  内存泄漏相关（new-delete、malloc-free、智能指针）
  是否了解其他语言的内存回收机制（Java的垃圾回收：标记-清除和标记-压缩）

计网：
  TCP四次挥手中为什么要等2个MSS

Linux：
  如何查看系统的CPU使用情况（top-实时、cat \proc\stat、vmstat-虚拟内存以及cpu、mpstat）
  如何查看系统的磁盘使用情况（df -h所有目录的使用情况、du -h当前目录的使用情况）

  对未来的学习规划
  更偏向运维还是更偏向开发
  反问（学习建议：安全、虚拟化、容器化、云计算）

顺丰-HR面
  自我介绍
  本研成绩，为什么并没有很高
  在实习中学习到的东西
  为什么选择运维开发
  应聘运维开发的优势和缺点
  如何看待顺丰这家企业
  有没有offer
  目标薪资
  反问（新员工入职后在运维开发大类下是如何划分工作方向的、大致的作息时间）
  
▲小红书-数据仓库
研究生项目：
  介绍？
  创新点？
  通俗一点？

手撕SQL

▲腾讯-测开
自我介绍：
  要讲到投递该岗位的原因？表示感兴趣？

研究生项目：
  做什么？
  怎么做？
  创新？

C++：
  关键字explicit？
  sizeof 和 strlen区别？

计网：
  HTTP 与 HTTPS？
  TCP 与 UDP？
  TCP的拥塞控制？

力扣中等题-LCR 102 目标和？

未来计划

▲联想-测试开发工程师
  英文自我介绍、英文描述测试开发工作、为什么选择测试开发
  对导师的看法
  对测试工具的认识
  Numpy与Pandas区别
  PyTest了解

做题-在一些版本号中找到最大的版本

▲京东-测试开发工程师
  对测试开发的认识：在规定的条件下对程序进行操作，观察运行过程、结果是否符合程序设计的需求。
  研究生项目
  做过什么测试、单元测试
  测试用例（最简单的就是平常Leetcode、牛客题目当中的测试用例，给定输入，期望输出。在业务测试中，通常测试用例就是针对某个模块的某个功能进行测试的步骤，包括用例编号、模块名称、功能名称、预设条件、测试步骤以及数据还有预期结果等等）

▲腾讯-测开
  自我介绍
  研究生项目放到第一个项目，增加被提问的机会？
  RPC框架，对应公司的产品记一下
  对测试方法的理解（单元测试、集成测试、系统测试、自动化测试...）

C++
  多态、虚函数、纯虚函数
  STL的了解（三大核心：容器、算法、迭代器）
  Vector扩容
  容器了解多少

MySQL
  索引类型（B树：普通索引、唯一索引、主键索引、前缀索引、联合索引；哈希索引；外键索引）
  哈希索引和B树索引性能比较

做题
  荷兰旗（中等）
  MySQL

金证科技-？？
  研究生项目

C++
  智能指针（shared_ptr unique_ptr weak_ptr）
  指针与数组区别（sizeof、访问方式、内存分布、数组名-常量指针、参数传递时数组名退化为指针）
  内存分配
  STL库相关（容器、算法、迭代器）
  Vector扩容
  Vector、map实现原理
  erase

操作系统
  进程线程通信方式（管道、内存映射、共享内存、消息队列、信号、信号量、Socket）
  进程调度（FCFS、SJF、优先级调度、时间片轮转、多级调度）

MySQL
  聚集索引、非聚集索引

口述反转链表

平安-信息科技岗HR
  自我介绍
  实习对技术上有什么提升
  常用工具软件（matlab python hadoop）
  Python 和 MySQL 
  聚合函数（sum average）
  窗口函数
  Having和where区别
  Python主要用于解决什么问题
  画图（散点图如何合到一个图）
  机器学习是否有实操
  有监督算法和无监督算法
  常用无监督算法和有监督算法
  实习中的方法论是什么
  认为自己在银行岗位上的优势
  研究生为什么不实习
  职业规划

平安-数据开发岗HR
  自我介绍
  从什么时候开始决定做数据开发
  对数据开发业务上有什么规划
  互联网大厂offer和银行证券公司的offer
  对公司企业文化有什么追求
  团队工作氛围轻松
  短期职业规划
  是否有了解业务工作

吉比特-游戏测试HR
  自我介绍
  对测试的理解
  做测试的优势
  为什么投递测试
  测试与开发的区别
  对游戏测试的理解
  在项目中运用到的测试理论
  科研项目中最有挑战的事情
  面对困难如何调整自己心态
  为什么不参加实习
  团队工作和独立工作区别
  更喜欢哪种工作模式
  在实习中团队协作出现的困难
  跨部门沟通如何有效沟通
  校招考虑的因素
  薪资
  秋招进度









  
