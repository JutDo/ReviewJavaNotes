# ReviewJavaNotes
record the Java review info

java集合、异常，lambda表达式，Easy Excel、Hutool
Redis分布式缓存、分布式session、Redisson分布式锁
数据批量导入、缓存预热、定时任务
Nacos和dubbo rpc框架，spring Cloud gateway实现api网关
jsoup爬虫，分词搜索，kibana
Canal、LogStash、定时任务、双写实现Elasticsearch和Mysql同步
能使用CompletableFutrue等juc类，自定义线程池实现并发和操作
熟悉RabbitMq消息队列



## Java常见知识点



### java多线程

#### Thread

#### Runnable

#### CallAble





主要的方法： run（） ，start（）方法





### 线程常用的使用方法

* 礼让yeild()
* 等待方法 ，可以设置等待的时间super.wait()
* notify（）唤醒线程
* notifyAll() 唤醒所有等待的线程
* stop() 已经废弃
* destroy() 销毁（已废弃
* resume()  已废弃
* intercept 线程中断
* 线程的命名和获取 
* 线程优先级，有 0、5 、10 三个int值，默认是5，主线程默认也是5







### 线程的同步和死锁

#### synchronized 一般修饰代码块或者方法

#### 死锁产生的原因

资源抢占------

线程的停止通过设置标志位来停止



* 后台守护线程 Demand()
* volatile 关键字

Volatile和synchronized的区别？？

1. volatle 修饰变量，被此关键字修饰的变量不会创建副本，会直接在内存中修改
2. synchronized 是线程同步的方法，一般修改代码块或者方法





### Java基础类库

* Stringbuffer、String、StringBuilder
* CharSequence 接口
* AutoCloseable 接口
* Runtime类
* System类
* Cleaner类
* 对象克隆

### 其他操作类



#### Math数学计算类

#### Random随机数生成类

#### 大数字处理类

#### Date日期处理类

#### SimpleDateFormat日期处理类







### 正则表达式

#### String类对正则的支持

#### java.util.regex









### 开发支持库

#### UUID

#### Optional

#### ThreadLocal

#### 定时调度

#### Base64 加密和解密

### 比较器

深拷贝和浅拷贝的区别？？？

Comparable

Comparator比较器

二叉树

二叉树基础实现和方法

红黑树





### 类库使用案例分析

StringBuffer 使用

随机数组

Email验证

扔硬币

IP验证

HTML拆分

国家代码

学生信息比较

---- ----







### 文件操作

File基本操作

File类操作深入

获取文件信息



实践：列出目录结构

文件批量改名



### 字节流和字符流

流的基本盖伦

OutputStream 字节输出流

InputStream 字节输入流

Writer 字符输入流

Reader字符输入流

转换流

实践： 文件拷贝

### IO操作

字符编码

内存操作流

管道流

RandomAccessFile





### 输入和输出流

打印流

System对io的支持

BufferedReader缓冲流

Scanner扫描流



### 对象和序列化

序列化和反序列的基本概念



transient关键字

### JavaIO编程案例

数字大小比较

文件保存

字符串逆序显示

数据排序处理

奇偶数统计

用户登录

投票选举





### 反射

反射机制

Class类对象的三种实例化模式

反射实例化对象

反射与工厂设计模式

反射与单例模式

发射获取类结构信息

反射调用普通方法

反射调用成员

Unsafe工具类



### ClassLoader类加载器

classloader的基本概念

自定义classloader处理器

静态代理设计模式

动态代理设计模式

cglib实现代理设计模式



反射获取annotation

自定义annotation

工厂设计模式和annotation整合



### 集合框架LIst、Set、Map

#### List

List

ArrayList

LinkedList

Vector



#### Set

HashSet

Treeset





#### Map

HashMap()

LinkedHashMap()

HashTable()





### 集合工具类

Stack 栈操作

Queue队列

Properties属性操作

Collections工具类

### Statement数据库操作接口

Stream基本操作

MapReduce基础模型
