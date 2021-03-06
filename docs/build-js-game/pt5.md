# 第五部分：滴答滴答

<!-- ch 24~29 -->

前几章已经向你展示了如何构建几种不同类型的游戏。在这一部分，你用动画角色，物理，和不同的水平建立一个平台游戏。游戏的名字叫*滴答滴答*(见图 [V-1](#Fig1) )，故事围绕一颗稍微有点压力的炸弹展开，这颗炸弹将在 30 秒内爆炸。这意味着游戏中的每一关都应该在 30 秒内完成。如果玩家收集到所有提神的水滴并及时到达终点面板，则一个关卡完成。

![9781430265382_Part05-01.jpg](img/9781430265382_Part05-01.jpg)

[图 V-1](#_Fig1) 。滴答滴答的游戏

这款平台游戏包含许多其他游戏中常见的基本元素:

*   应该可以玩不同的关卡。
*   这些关卡应该从一个单独的文件中加载，这样就可以在不知道游戏代码如何工作的情况下改变它们。
*   游戏应该支持玩家和敌人的动画角色。
*   玩家应该控制可以跑或跳的玩家角色的动作。
*   游戏中应该有一些基本的物理学来管理坠落，与物体碰撞，在平台上跳跃等等。

这是一个很长的列表！幸运的是，您可以重用许多已经开发的类。接下来的章节将介绍清单上的所有项目。如果你想玩完整版的滴答滴答游戏，获取[第 29 章](29.html)的样本代码，并打开`TickTickFinal`文件夹中的`TickTick.html`文件。