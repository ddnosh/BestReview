# BestReview
<h1 align="center">争取做到史上最全Android面试题库</h1>

<!--| Ⅰ | Ⅱ | Ⅲ | Ⅳ | Ⅴ | Ⅵ | Ⅶ | Ⅷ | Ⅸ | Ⅹ |
| :--------: | :---------: | :---------: | :---------: | :---------: | :---------:| :---------: | :-------: |
| Android[:bowtie:](#Android) | Java[:blush:](#Java)|Kotlin[:heart_eyes:](#Kotlin) | 计算机系统[:relieved:](#计算机系统) |算法[:stuck_out_tongue_winking_eye:](#算法)| 工具 [:kissing_smiling_eyes:](#工具)| 产品[:frowning:](#产品)| 服务器[:confused:](#服务器)| -->

| &nbsp;Android&nbsp; | Java | &nbsp;Kotlin&nbsp; | &nbsp;计算机系统&nbsp; | 算法 | &nbsp;&nbsp;工具&nbsp;&nbsp; | &nbsp;产品&nbsp; | &nbsp;服务器&nbsp; |
| :--------: | :---------: | :---------: | :---------: | :---------: | :---------:| :---------: | :-------: |
| [:bowtie:](#Android) | [:blush:](#Java)|[:heart_eyes:](#Kotlin) | [:relieved:](#计算机系统) |[:stuck_out_tongue_winking_eye:](#算法)|  [:kissing_smiling_eyes:](#工具)| [:frowning:](#产品)| [:confused:](#服务器)|

<br>

- [Android](#Android)
  - [基础](#Android基础)
  - [进阶](#Android进阶)
  - [优化](#Android优化)
  - [架构](#架构)
  - [测试](#测试)
  - [规范](#规范)
  - [开源框架](#开源框架)
  
- [Java](#Java)
  - [基础](#Java基础)
  - [进阶](#Java进阶)  
  - [优化](#Java优化)  
  
- [Kotlin](#Kotlin)
  
- [计算机系统](#计算机系统)

- [算法](#算法)
  - [查找](#查找)
  - [排序](#排序)
  
- [工具](#工具)  
  
- [产品](#产品)

- [服务器](#服务器)

# Android
## Android基础
- [Android onSaveInstanceState 实时保存数据](https://blog.csdn.net/adminlxb89/article/details/81365082)  
- [Android DecorView浅析](https://www.cnblogs.com/ldq2016/p/6671501.html)  
- [Android中两种序列化方式的比较Serializable和Parcelable](https://blog.csdn.net/wangchunlei123/article/details/51345130)  
- [Jvm、Dalvik和Art的区别](https://www.jianshu.com/p/59d98244fb52)  
- [compileSdkVersion，targetSdkVersion和minSdkVersion三者的关系](https://blog.csdn.net/u012345683/article/details/81286989)  
- [自定义View，有这一篇就够了](https://www.jianshu.com/p/c84693096e41)  
- [Activity-Window-View三者的关系](https://blog.csdn.net/qq_21399461/article/details/79836806)
- [深入理解Message, MessageQueue, Handler和Looper](https://www.cnblogs.com/lao-liang/p/5073257.html)  
- [简析Window、Activity、DecorView以及ViewRoot之间的错综关系](https://www.cnblogs.com/ldq2016/p/9651260.html)  
- [简化Parcelable的使用](https://blog.csdn.net/u013265344/article/details/87979948)  
- [ActivityThread](https://blog.csdn.net/zhangfei2018/article/details/46518615)  
- [Android进程间通信的几种方式](https://www.cnblogs.com/lizhengxian/p/5075635.html)  
- [通用网络请求实现之HttpURLConnection和OkHttp](https://blog.csdn.net/hanmindi/article/details/79449604)  
- [两个 Activity 之间跳转时必然会执行的是哪几个方法？](https://www.cnblogs.com/loaderman/p/6524226.html)  
- [Android系统中的五种进程](https://blog.csdn.net/wolfking0608/article/details/83146268)  
- [Handler、Thread、HandlerThread三者的区别](https://blog.csdn.net/weixin_41101173/article/details/79687313)  
- [Android ListView与RecyclerView对比浅析](https://blog.csdn.net/import_sadaharu/article/details/81323801)  

## Android进阶
- [浅谈移动端 View 的显示过程](https://www.diycode.cc/topics/3183)  
- [ANDROID自定义视图——onMeasure，MeasureSpec源码 流程 思路详解](https://blog.csdn.net/a396901990/article/details/36475213)  
- [Android事件分发机制详解：史上最全面、最易懂](https://blog.csdn.net/zhangjin12312/article/details/78340998)  
- [Android热更新实现原理浅析](https://www.jianshu.com/p/8dcf750acdfe)  
- [Android中图片的三级缓存详解](https://blog.csdn.net/languobeibei/article/details/73176506)  
- [【Android】APT](https://www.jianshu.com/p/7af58e8e3e18)  
- [AOP如何实现及其原理](https://juejin.im/post/5bfcb146e51d451f6e52b3c8)  
- [插件化理解与实现 —— 加载 Activity「类加载篇」](https://fashare2015.github.io/2018/01/24/dynamic-load-learning-load-activity/)  
- [ARouter原理剖析和自己实现EasyRouter](https://blog.csdn.net/jiang19921002/article/details/81777406)  
- [APK安装流程概述](https://www.cnblogs.com/neo-java/p/7117482.html)  
- [一个APP从启动到主页面显示经历了哪些过程？](https://www.jianshu.com/p/a72c5ccbd150)  
- [Android UI刷新机制](https://www.jianshu.com/p/71703df6df40)  
- [android签名机制](https://blog.csdn.net/gangjindianzi/article/details/85492571)  

## Android优化
- [Android界面性能调优手册](https://androidtest.org/android-graphics-performance-pattens)  
- [Android内存优化——常见内存泄露及优化方案](https://www.jianshu.com/p/ab4a7e353076)  
- [Android性能优化之优化layout的层级](https://www.jianshu.com/p/920e1c9551aa)  
- [用ConstraintLayout来优化Android的XML布局的层级](http://tech.dianwoda.com/2017/12/15/yong-constraintlayoutlai-you-hua-androidde-xmlbu-ju-de-ceng-ji/)  
- [设计师必须注意的Android开发者选项之GPU过度绘制](https://www.jianshu.com/p/ab0cf2697236)  
- [Androud 如何有效减少重复代码](https://blog.csdn.net/wangzhongshun/article/details/78738217)  
- [（Android Studio 3.0）Android Profiler内存泄漏检查](https://blog.csdn.net/Double2hao/article/details/78784758)  
- [Android布局优化：include 、merge、ViewStub的详细总结](https://www.cnblogs.com/leipDao/p/8981687.html)  
- [Android图片优化指南](https://segmentfault.com/a/1190000015723665)  
- [Android APP终极瘦身指南](http://jayfeng.com/2016/03/01/Android-APP%E7%BB%88%E6%9E%81%E7%98%A6%E8%BA%AB%E6%8C%87%E5%8D%97/)  
- [Android中的.apk之zipalign优化](https://www.jianshu.com/p/c5eafe6b0b5e)

## 架构
- [App架构经验总结（转载）](https://www.cnblogs.com/ssrstm/p/5709830.html)  
- [REST、RESTful 与 RESTful API](https://blog.csdn.net/xiaojin21cen/article/details/78696943)  

## 规范
- [Android 静态代码分析](https://blog.csdn.net/u010420435/article/details/69605583)  

## 测试 
- [Android 程序员必须掌握的三种自动化测试方法](https://www.cnblogs.com/punkisnotdead/p/5103323.html)  

## 开源框架
- [EventBus原理详解](https://blog.csdn.net/michael_yt/article/details/52014022)  
- [LiveData是如何做到在合适的时机刷新的](https://blog.csdn.net/Kongou/article/details/82798451)  
- [如何绑定页面生命周期（一）－Glide实现](https://www.jianshu.com/p/cdebe33df7a0)  
- [RxJava基本原理解析(一)](https://www.jianshu.com/p/695f780436dd)  
- [网络库Retrofit2原理简析](https://blog.csdn.net/hesong1120/article/details/78775145)  
- [LruCache 实现原理分析](https://blog.csdn.net/u012943767/article/details/51897259)  
- [OkHttp 源码解析](https://www.jianshu.com/p/39a7c97d2004)  

# Java
## Java基础
- [java反射（特别通俗易懂）](https://blog.csdn.net/lwl20140904/article/details/80163880)  
- [Java之动态编译，静态编译简单理解和实例](https://www.jianshu.com/p/781987c1db8a)  
- [浅谈Java中的hashcode方法](https://www.cnblogs.com/dolphin0520/p/3681042.html)  
- [Object类有哪些方法？各有什么作用？](https://blog.csdn.net/qq_30264689/article/details/81903031)  
- [SparseArray与HashMap相比优缺点](https://blog.csdn.net/qwer123qwerz/article/details/79345524)  
- [HashMap实现原理及源码分析](https://www.cnblogs.com/chengxiao/p/6059914.html)  
- [java集合（list,set,map)](https://www.cnblogs.com/yangliguo/p/7476788.html)  
- [java中实现多态的机制是什么？](https://blog.csdn.net/bornlili/article/details/55213563)  
- [final修饰符有什么特点](https://www.cnblogs.com/huiyuantang/p/5422317.html)  
- [成员变量存在堆中，局部变量存在栈中的理解](https://blog.csdn.net/chenzuen113113/article/details/80929617)  
- [String str = new String("abc")究竟创建了几个对象？](https://blog.csdn.net/qq_36470686/article/details/83444483)  
- [JAVA中数组扩容的三种方式](https://blog.csdn.net/wt122694/article/details/81173128)  
- [阻塞队列与非阻塞队列](https://www.cnblogs.com/dolphin0520/p/3932906.html)  
- [String类的equals()与“==”的区别](https://blog.csdn.net/sunshinegirl168660/article/details/81333562)  
- [String类中的equals方法总结](https://blog.csdn.net/qq_25827845/article/details/53868815)  
- [HashMap、Hashtable和ConcurrentHashMap底层实现原理和线程安全问题](https://blog.csdn.net/caisongcheng_good/article/details/79489852)  
- [Java自定义类加载器与双亲委派模型](https://www.cnblogs.com/wxd0108/p/6681618.html)  
- [深入了解双端队列Deque](https://blog.csdn.net/l540675759/article/details/62893335)  
- [ConcurrentHashMap实现原理](https://blog.csdn.net/dingji_ping/article/details/51005799)  
- [图解LinkedHashMap原理](https://www.jianshu.com/p/8f4f58b4b8ab)  
- [new instance和new有什么区别](https://blog.csdn.net/qq_21071965/article/details/55666838)  

## Java进阶
- [IOC,依赖倒置 (理解) Spring依赖注入的实现技术是：动态代理](https://blog.csdn.net/chentao866/article/details/71191005)  
- [老大难的 Java ClassLoader，到了该彻底理解它的时候了](http://blog.itpub.net/31561269/viewspace-2222522/)  
- [Java常见面试题之多线程和高并发详解](https://www.jb51.net/article/160125.htm)  
- [从多线程的三个特性理解多线程开发](https://www.cnblogs.com/dafanjoy/p/10020225.html)  
- [Java中的多线程你只要看这一篇就够了](https://www.cnblogs.com/wxd0108/p/5479442.html)  
- [并发编程之ThreadLocal、Volatile、synchronized、Atomic关键字扫盲](https://blog.csdn.net/u010687392/article/details/50549236)  
- [有了进程为什么还要线程？](https://www.cnblogs.com/Berryxiong/p/6429723.html)  
- [Java多线程----线程的同步，锁和死锁，问题以及解决方法（例子说明）](https://blog.csdn.net/qq_36186690/article/details/82940620)  

## Java优化
- [Android 性能优化 - 彻底解决内存抖动](https://blog.csdn.net/wanghao200906/article/details/79311288)  
- [为什么StringBuilder的效率要比String高?](https://blog.csdn.net/qq_31209193/article/details/81092958)  

## JVM
- [可能是把Java内存区域讲的最清楚的一篇文章](https://mp.weixin.qq.com/s?__biz=Mzg2OTA0Njk0OA==&mid=2247484884&amp;idx=1&amp;sn=0d9b841ce0fc300c78ade2a87ffbfb46&source=41#wechat_redirect)  
- [搞定JVM垃圾回收就是这么简单](https://blog.csdn.net/qq_34337272/article/details/82177383)  
- [Java GC工作原理以及Minor GC、Major GC、Full GC、GC收集相关算法整理](https://blog.csdn.net/lovexiaoqiqi/article/details/81737213)  
- [GC算法](https://blog.csdn.net/luomingkui1109/article/details/72821082)  
- [Javassist动态编程](https://nickid.cn/2017/02/Javassist%E5%8A%A8%E6%80%81%E7%BC%96%E7%A8%8B/)  

# Kotlin
- [Kotlin 的优缺点](https://www.cnblogs.com/bluestorm/p/8965649.html)  
- [写给Android开发者的Kotlin入门](https://www.jianshu.com/p/bb53cba6c8f4)  

# 计算机系统
- [编程范式：命令式编程(Imperative)、声明式编程(Declarative)和函数式编程(Functional)](https://www.cnblogs.com/sirkevin/p/8283110.html)  
- [HTTP与HTTPS的区别](https://www.cnblogs.com/wqhwe/p/5407468.html)  
- [HTTP、TCP、UDP，Socket，HTTPS（史上最强理解，没有之一）](https://blog.csdn.net/WHB20081815/article/details/67640804)

# 算法
## 查找
- [有了这个开源项目，再也不怕去BAT和字节跳动面试考算法了](https://github.com/algorithm-visualizer/algorithm-visualizer)  
- [二分查找](https://www.jianshu.com/p/0f823fbd4d20)  
- [visualgo](https://visualgo.net/en)  

## 排序
- [十大排序算法](https://www.colabug.com/4194710.html)  

# 工具
- [软件开发中会用到的图](https://www.cnblogs.com/Zachary-Fan/p/developdiagram.html)  
- [Android开发规范：Git版本管理规范](https://blog.csdn.net/ddnosh/article/details/78996628)  
