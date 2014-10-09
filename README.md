护士大战
============

游戏名称
---------

护士大战

玩法说明
---------

3D第一人称射击游戏，使用wasd控制走动，使用鼠标控制瞄准，点击鼠标左键发射子弹。躲避来自护士的近身攻击。游戏目的在主角被护士攻击死亡前尽可能多的获取分数。

技术细节
--------
基于Unity3d 4.3.4f1，主角使用Character Controller组件，敌人使用Capsule Collier，用Physics.Raycast实现子弹与敌人的射线碰撞。使用另一个摄像头展示小地图效果。敌人的跑动使用Mecanim动画系统实现。并使用场景中创建2D贴图的方式表示UI界面。

游戏展示
--------
- 开始界面：
![image](https://github.com/mingchaoyan/FPS/blob/master/GameShots/begin.png)
- 游戏界面：
![image](https://github.com/mingchaoyan/FPS/blob/master/GameShots/playing.png)
- 结束界面：
![image](https://github.com/mingchaoyan/FPS/blob/master/GameShots/end.png)

