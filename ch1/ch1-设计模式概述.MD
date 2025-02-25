# 设计模式概述
## 设计模式的定义
**模式**是在特定环境下，人们解决某类重复出现问题的一套成功或有效的解决方案。
**设计模式**是在特定环境下，为解决某一通用软件设计问题提供的一套定制的解决方案，该方案描述了对象和类之间的相互作用。
## 设计模式的基本要素
- 模式名称
- 问题
- 解决方案
- 效果
## 设计模式的分类
### 根据目的分类
- 创建型（Creational）
- 结构型（Structural）
- 行为型（Behavioral）
> **创建型**
> 用于创建对象
- 工厂方法模式
- 抽象工厂模式
- 建造者模式
- 原型模式
- 单例模式
> **结构型**
> 用于处理类或对象的组合
- 适配器模式
- 桥接模式
- 组合模式
- 装饰模式
- 外观模式
- 享元模式
- 代理模式
> **行为型**
> 主要用于描述类或对象怎样交互和分配职责
- 职责链模式
- 命令模式
- 解释器模式
- 迭代器模式
- 中介者模式
- 备忘录模式
- 观察者模式
- 状态模式
- 策略模式
- 模版方法模式
- 访问者模式
### 根据范围分类
- 类模式
  - 处理类和子类之间的关系，这些关系通过继承建立，在编译时就被确定下来，是一种**静态关系**
- 对象模式
  - 对象模式处理对象之间的关系，这些关系在运行时变化，更具**动态性**。
## GOF设计模式
|   范围/目的     |                                      创建型模式                                      |                                                                        结构型模式                                                                        |                                                                                              行为型模式                                                                                              |
|  ---------------   |   --------------------------------------------------------------------   |   -----------------------------------------------------------------------------------------------------------------------   |   ---------------------------------------------------------------------------------------------------------------------------------------------------------  |
|      类模式       |                                    工厂方法模式                                     |                                                                  （类）适配器模式                                                                  |                                                                                解释器模式<br>模版方法模式                                                                                |
|    对象模式     |    抽象工厂模式<br>建造者模式<br>原型模式<br>单例模式     |    （对象）适配器模式<br>桥接模式<br>组合模式<br>装饰模式<br>外观模式<br>享元模式<br>代理模式    |    职责链模式<br>命令模式<br>迭代器模式<br>中介者模式<br>备忘录模式<br>观察者模式<br>状态模式<br>策略模式<br>访问者模式    |

## 设计模式的优点
1. 设计模式**融合了众多专家的经验**，并以一种标准的形式供广大开人员所用。
2. 设计模式使人们可以更加**简单、方便地复用成功的设计和体系结构**。
3. 设计模式使得设计方案**更加灵活，且易于修改**。
4. 设计模式的使用将**提高软件系统的开发效率和软件质量**，并在一定程度上**节约设计成本**。
5. 设计模式有助于初学者更深入地理解面向对象思想。
  - 一方面可以帮助初学者更具**方便的阅读和学习现有类库**与其他系统中的源代码。
  - 一方面可以**提高软件设计水平和代码质量**。

## 课后习题
1. 设计模式具有（   ）的优点<br/>
   A. 提高系统性能<br/>
   B. 减少类的数量，降低系统的规模<br/>
   C. 减少代码开发工作量<br/>
   D. 提升软件设计的质量 <br/>
2. 在面向对象软件开发过程中，采用设计模式（   ）<br/>
   A. 可以减少在设计和实现过程中需要创建的实例和对象的数量<br/>
   B. 可以保证程序的运行速度达到最优值<br/>
   C. 可以复用相似问题的相同解决方案<br/>
   D. 允许在非面向对象程序设计语言中使用面向对象<br/>
3. （   ）都是行为型设计模式<br/>
   A. 组合模式、适配器模式和代理模式<br/>
   B. 观察者模式、职责链模式和策略模式<br/>
   C. 原型模式、建造者模式和单例模式<br/>
   D. 迭代器模式、命令模式和桥接模式<br/>
4. 什么是设计模式?它包含哪些基本要素?
5. 设计模式如何分类?每一类设计模式有何特点?
6. 设计模式具有哪些优点?
7. 除了设计模式以外，目前有不少人在从事“反模式”的研究，请查阅相关资料了解何谓“反模式”以及研究“反模式”的意义。
8. 请查阅相关资料,了解在JDK中使用了哪些设计模式，在何处使用了何种模式，至少列举两个。

## 课后习题答案
1. D
2. C
3. B
4. 设计模式是在特定环境下，为解决某一通用软件设计问题提供的一套定制的解决方案，该方案描述了对象和类之间的相互作用。<br/>基本要素：模式名称、问题、解决方案、效果
5. 分类：类模式/对象模式 OR 创建型/结构性/行为型 <br/> **创建型**:用于创建对象<br/>**结构型**:用于处理类或对象的组合<br/> **行为型**:主要用于描述类或对象怎样交互和分配职责<br/><br/>**类模式**:处理类和子类之间的关系，这些关系通过继承建立，在编译时就被确定下来，是一种静态关系<br/>**对象模式**:对象模式处理对象之间的关系，这些关系在运行时变化，更具动态性。
6. (1).设计模式**融合了众多专家的经验**，并以一种标准的形式供广大开人员所用。<br/>(2). 设计模式使人们可以更加**简单、方便地复用成功的设计和体系结构**。<br/>(3). 设计模式使得设计方案**更加灵活，且易于修改**。<br/>(4). 设计模式的使用将**提高软件系统的开发效率和软件质量**，并在一定程度上**节约设计成本**。<br/>(5). 设计模式有助于初学者更深入地理解面向对象思想。一方面可以帮助初学者更具**方便的阅读和学习现有类库**与其他系统中的源代码。一方面可以**提高软件设计水平和代码质量**。
7. 反模式(AntiPatterns)是指那些导致开发出现障碍的负面模式，即在软件开发中普遍存在、反复出现并会影响到软件成功开发的不良解决方案。反模式是关注于负面解决方案的软件研究方向，揭示出不成功系统中存在的反模式有利于在成功系统中避免出现这些模式，有助于降低软件缺陷和项目失败出现的频率。反模式清晰定义了大部分人在软件开发过程中经常会犯的一些错误，根据视角的不同，可分为开发性反模式、架构性反模式和管理性反模式。
8. 创建模式：<br/>抽象工厂模式：<br/>java.util.Arrays.asList()<br/>java.net.URL.openConnection()<br/>建造者模式：<br/>java.lang.StringBuilder.append()<br/>java.nio.ByteBuffer.put()<br/> 工厂方法模式： <br/> java.lang.Object.toString()<br/>.......