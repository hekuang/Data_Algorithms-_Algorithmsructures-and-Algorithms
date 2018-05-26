## 基本概念
* 是编译原理，数据库....的基础  
    程序 = 算法+数据结构 ， 算法 = 逻辑 + 控制
* 需要解决的问题
    * 输入
    * 输出
    * 输入如何转换为输出
 ![](https://github.com/hekuang/Data_Algorithms-_Algorithmsructures-and-Algorithms/blob/master/Snipaste_2018-05-08_22-16-47.png)
* **数据结构用途**
    * 存储要处理的数据
    * 实现算法策略
## 相关概念
数据 > 数据对象 > 数据元素 > 数据项
1. 数据
    * 所有能被计算机识别的符号集合
2. 数据元素(Data Elemnet)
    * 是数据(集合)中的一个 "个体"
    * 是数据结构中讨论的**基本单位**
3. 数据项(Data Item)
    * 是数据结构中讨论的**最小单位**
    * 数据元素可以是数据项的合集
4. 数据对象( Data Object) 
    * 数据对象是具有相同性质的数据元素的集合，是数据的一个子集   
5. **数据结构** 
    * 带**结构**的数据元素的集合，  
    **DS = (D, R)**    
    D是数据元素的集合，R是D上关系的集合。数据元素和其相互关系称为数据结构  
    **Data_Structure = (D, L, S, O)**   
    数据元素D, 数据元素之间的逻辑关系L，逻辑关系在计算机中的存储表示S，贵的的操作O     
6. 逻辑结构
* 线性结构,一对一    
* 非线性结构
   * 树形结构，一对多
   * 图形结构（网状结构），多对多
 * 集合结构  
7. 存储结构 (Storage Structure)
  逻辑结构：算法分析与实现
* 存储结构（物理结构）：指导算法实现
    * 顺序存储： 逻辑相邻 ，物理位置也相邻的存储单元中存储 (数组实现)
    * 链式存储：数据元素中添加地址或者辅助结构，用于存放数据元素之间的关系   
8. 数据结构的操作(Operation)     
数据元素的查找、插入、删除、遍历和排序   
9. 数据类型( Data Type)
  也是数据结构的一种
10. 抽象数据类型（Abstract Data Type, ADT）
  不要考虑分配大小，ADT包含数据元素、数据元素之间的操作以及操作三要素（D,R，O）
* 抽象性 
* 扩展性
## 算法
* 输入：零个或者多个外部量作为算法的输入
* 输出：算法产生至少一个量作为输出
* 确定性：组成算法的每条指令清晰、无歧义
* 有限性： 算法每条指令执行次数有限、执行每条指令的时间也有限

> 问题————算法（算法设计过程)————数据结构设计过程————计算机执行
> 问题理解——数据结构设计——算法设计——算法分析——程序实现
### 算法复杂度分析
C = F(N,I,A) N规模I输入A算法本身函数，A隐含在函数复杂度中
#### 空间复杂度
S= S（N，I）
#### 时间复杂度
T=T（N,I）
时间*次数（计算步）
计算步T(n)= O(F(n))



