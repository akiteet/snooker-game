# Snooker Game

  一个基于 HTML5 Canvas 的双人 2D 斯诺克游戏。

  ## 在线试玩

  [点击开始游戏](https://akiteet.github.io/snooker-game/game_2d.html)

  ## 规则说明

  [查看规则说明](https://akiteet.github.io/snooker-game/game_2d_rules.html)

  ## 项目特点

  - 双人本地对战
  - HTML5 Canvas 球桌渲染
  - 力度与方向控制
  - 引导线辅助
  - 红球、彩球、清彩阶段计分
  - 自动犯规判罚
  - 自由球规则
  - 让杆与空杆还原重打
  - 全场所有球停止后才允许下一次击球
  - 独立规则说明页面

  ## 游戏规则覆盖

  游戏根据斯诺克常见规则实现了核心流程：

  - 红球未清台前遵循“一红一彩”
  - 红球入袋后必须指定目标彩球
  - 彩球在红球阶段入袋后自动复位
  - 红球清台后按黄、绿、棕、蓝、粉、黑顺序清彩
  - 犯规按最低 4 分、活球分值、犯规涉及球最高分值取最高罚分
  - 犯规后支持让杆、自己击球和空杆还原重打
  - 犯规后满足条件时自动判定自由球

  ## 使用方式

  直接打开：

  ```text
  game_2d.html

  或访问 GitHub Pages 在线版本：

  https://akiteet.github.io/snooker-game/game_2d.html

  ## 文件说明

  game_2d.html              游戏主页面
  game_2d_rules.html        规则说明页面
  .gitattributes            Git 文本换行配置

  ## 说明

  这是一个前端练习项目，主要用于实现 2D 球类碰撞、游戏状态机和斯诺克规则判定。
  如果你觉得这个项目有帮助，欢迎点一个 Star。
