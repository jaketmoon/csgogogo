是csgogogo小组在cs61a学习的第一个项目：hog。project地址：https://cs61a.org/proj/hog/
rules：两人轮流roll up dice，先达到一百点的胜利，每个人可以choose the number of the dices you roll up。但是一旦里面出现了1，那这人只能获得一点。否则就是你roll 的全部点数加起来。
rules to spice up the game:
  Boar Brawl:当前的roll up 的玩家可以选择扔0个dice，然后获得3*abs（自己点数的个位数-对手点数的十位数），若为0，则获得1点。当只有个位数是十位数默认为0.
  Sus Fuss：每次roll完之后，若玩家的加上roll之后的点数有三个或者四个facters（including 1 and itself），那就直接跳到下一个primary number，比如21跳到23.
