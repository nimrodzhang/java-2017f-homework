#Java第三次作业说明
###151220105 王舸帆

**人物**
创建了一个叫做人物的接口
葫芦娃 蛇精 小喽啰等人物都 *implements* 人物

**人物的载体**
所有的人物都放置在一个叫做 *hulu* 的载体中，它可以 *setholder* 和 *getholder* 

**二维空间**
将二维空间抽象为一个tspace
其中包含了一个N*N的 “大棋盘”

**站队**
将所有的站队方法 ***封装*** 到一个类中，便于管理。其中包括雁形，鹤形等队形，以及爷爷和蛇精的站队
（其实应该定义一个站队的父类，各种站队方法都继承该类，不过我觉得这样比较麻烦）

**Director**
在这个类中，相当于有一个导演构造了这些所有的人物和这个二维空间，其中的makebg函数是make background的意思，对这些人物以及二维空间进行初始化。之后导演就可以通过站队等其他各种方法让这些人物在二维空间中动起来

