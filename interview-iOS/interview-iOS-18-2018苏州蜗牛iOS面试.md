
# 2018苏州蜗牛iOS开发面试题

> 作者：RocketsChen

> 鏈接：https://www.jianshu.com/p/ffc9b1cec635

> 面试通知邮件：邮件＋电话约当天下午的面试

##面试：（笔试＋面试）

> 虽然对笔试有心里准备但是当拿到5页面试题的时候心还是细微的颤抖了下，除了第一张是一道考宏交换的程序判断题和最后一页三条题<纠错，趣味>以外，中间三页题目密度在平均一页7条。总的来说题量还是很感人的！当然接待的人事特意跟我说笔试题是开卷。

### 笔试

> 附上如下部分面试题目,总的来说蜗牛的面试题题量涉及的范围还是挺广的。

> 我大概做了五十几分钟，然后接待的人事和我说不用写了，可以接下来准备下一轮面试。（笔试过程中有人来看过我，下一轮的面试官）

* 简述itms-services作用；
* POST和GET谁更安全？以及谈谈服务器交互的过程中更安全的保护措施？
* 对于一个xxxx.a的静态库而言，如何使用命令行来查看其支持的CPU架构 ? 苹果在2015年2月之后要求我们必须支持哪一种CPU架构；
* duplicate symbol是什么？谈谈如何避免和产生后解决方案；
* 时间和空间复杂度（剑指Offer-第五章）；
* 交叉编译？简述一下iOS中开发应用场景；
* 两个具体上架过程中苹果审核失败返回的信息请问如何解决：翻译过来第一条是：利用邀请奖励制度来诱惑玩家驳回 第二条是：抽奖类的比赛规则驳回；
* 具体的报错Log分析题；
* 程序输出结果题；
* 趣味思考题。


###  面试：

> 两位面试官：拿着我答题卷和简历开始进行面试：问题整理下大致有如下几个

* 简单分享下你开源作品中的一个技术点
* 对于热跟新技术的理解还有雷区
* 对于项目中的动态性的处理和看法以及组件的运用
* 对于图片加载的方式和图片展示方式的思考
* 项目中使用的框架
* 深入的问了几条我的面试卷上的题目，其中有一条我提出了疑问，面试官简单的给我讲解了下
分析一下趣味题的实现思路

* 问了下职业规划
* 对于技术探究和专研方面
* 最后就是问我有没有什么想问的

> 这样就算面试都结束了。然后过了大概一周人事给我电话说面试已经通过，可以给offer了。面试过程大概用了两个小时。

### 总结
- 总的面试过程还算是比较顺利的，面试官也很友善。对我来说算是来面试的过程中有所学习。开始我在去蜗牛的路上本以为会问一些runtime、Block、MVC、MVP、MVVM、GCD、ARC等等，结果拿到题算是和我想的不太一样，是把技术点运用到实际问题中，比如最后一页的Crash纠错：在一堆报错日志分析下来：简单的来说就是持有的通知对象在生命周期销毁之前没有被释放而或重复使用。是使用KVO常遇到的一种报错。解决：当前持有的被观察对象，在-dealloc中移除观察者。

- 在面试过程中肯定有会被面试官问道你不会的的题目，可以进一步题目来问清楚具体查考的方面。不要说一堆与题目无关或误关的的东西。

### 分享最近看的几本书：
* 《Effective Objective-C 2.0》
* 《剑指Offer》
* 《程序员的自我修养》
* 《Objective-C编程之道》

## 链接

- [面试题系列目录](../README.md)
- **上一份**: [2018 6月底面试经历简单回忆](interview-iOS-17-2018-6月底面试经历简单回忆.md)
- **上一份**: [2019-6-XL公司面试题](interview-iOS-19-6-XL公司面试题.md)