# 2018冰岩夏令营游戏组

## 前言

- 游戏是作品（项目）驱动的，如果你没有一个新的游戏玩法，只是复刻已有的游戏，你会损失很多的成就感。而单单脑子中有崭新的游戏玩法，你还未或者无法实际开发验证它，你是无法确定它是不是真的有趣的。
- 鉴于上一条，每一个游戏开发都应该抱有创作游戏的热情和思考游戏玩法的习惯。每一个游戏策划都应该在开发能力和视野上也该对自己有要求。不要把自己严格归属于开发或者策划，你是游戏创作者。
- 科学上网是技术资料搜索的基本要求，如果你不会，可以找我提供支持。
- 下面的链接多数指向英文资料，如果阅读起来比较吃力，可以尝试自行在`Google`或`Github`上寻找中文翻译版，基本都有。但是在此之前要考虑清楚：**如果你现在走了轻松的路，你只不过是在暂时性地逃避，你总有一天会重新走回这个交叉口，走那条更艰辛的路。**
- 遇到不懂的名词不要跳过，利用维基百科学习。
- 积极找同在夏令营的其他同学聊天、问问题，有一起努力前进的伙伴不是很好吗:)

##  基础知识

### 编程语言

- [lua](https://www.lua.org/) —— 常见的游戏脚本语言，极其轻量，很容易嵌入其他语言使用。[Programming in Lua](https://www.lua.org/pil/contents.html)
- ``C#`` —— 支持了`C`系的操作符重载、泛型等，`Unity游戏脚本`。[C# Guide](https://docs.microsoft.com/en-us/dotnet/csharp/index)
- ``C++`` —— 游戏引擎的主要底层语言，兼顾了性能和代码可维护性。[C++ Language](http://www.cplusplus.com/doc/tutorial/)、[C++ Primer](http://www.charleshouserjr.com/Cplus2.pdf)
- ``Javascript/Typescript`` —— 极其轻量的，主要应用于Web平台的解释型或即时编译型脚本语言，具有极良好的跨平台特性。[Javascript - MDN](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)、[Typescript](https://www.typescriptlang.org/)

### 游戏编程模式

- [Game Programming Pattern](http://gameprogrammingpatterns.com/) ，总结了一些**很重要**的游戏开发的设计模式，帮助你对GamePlay开发进行一个总览式的梳理。
- [Entity Component System](https://en.wikipedia.org/wiki/Entity%E2%80%93component%E2%80%93system) , 一种**优雅**、**缓存友好**的游戏架构模式。有效地利用组合代替继承、解决了复杂的依赖关系。

### 代码版本管理

- 用搜索引擎自行了解版本管理的作用。
- [Git](https://git-scm.com/) 是一个出色的版本管理工具。**不推荐图形界面`Git`，请熟悉命令行操作。** 推荐通过官方的[Pro Git](https://git-scm.com/book/en/v2)进行学习。
- [Github](https://github.com/)是一个通过`Git`进行版本管理的代码托管服务。请在夏令营期间全程用`Git`在`Github`上管理你的项目源码、学习日志，我们会进行Code review。
  - 书写`Github`的README文档时会用到`Markdown` 语言。这是一种轻量级标记语言，它的源码有极高的人类可读性，可以轻松地生成HTML文档。你看到的本文档就是用`Markdown`书写的。**请学习`Markdown`语言并用它完成你的所有学习日志。** [Markdown Guide](https://www.markdownguide.org/)
  - 书写规范的、可读的`Commit Message`。理解`Git Commit`的意义，书写`Commit Message`来记录你的工作进度。

### 游戏引擎

- 人见人爱花见花开的[Unity](https://unity3d.com/cn)。 Unity理论性的知识不多，主要靠边做边学API，[Unity Tutorial](https://unity3d.com/cn/learn/tutorials)  。
- [PICO-8](https://www.lexaloffle.com/pico-8.php)， 一个复古、轻量的像素游戏终端（引擎）。
  - 它的一些限制和特点
    - 屏幕分辨率为128x128，仅支持16色
    - 卡带（成品游戏）大小至多为32KB
    - 仅支持上下左右AB控制输入
    - 可以且仅能用自带的精灵、地图、音效、音乐编辑器来完成创作
  - **限制带来了想象力** ，你可以用PICO-8来进行快速游戏原型开发，可仅靠自己的力量完成视觉、听觉效果的游戏润色。
  - [PICO-8 Music Tutorial](https://www.youtube.com/playlist?list=PLur95ujyAigsqZR1aNTrVGAvXD7EqywdS)
  - 它不是免费的——但是很便宜，你要是买不起我给你买。
- [Cocos2d-JS](http://www.cocos2d.org/) 一个基于`Javascript`的2D Web游戏引擎。
    - `Cocos2d-JS` 支持`Javascript`和`Typescript`
    - 可以构建出轻量的Web游戏
    - 可以构建微信小游戏
    - 有中文文档

## 进阶知识

### 渲染

- `OpenGL`是一个用于渲染2D、3D图形的**跨语言、跨平台的应用程序编程接口** 。它是一套API，你可以用任何存在`OpenGL`绑定库的语言来使用它。你可以通过它来了解模型、贴图是怎么一步一步在屏幕上被渲染出来的，即学习**现代渲染管线** 。[Learn OpenGL](https://learnopengl.com/) 
- [Shadertoy](https://www.shadertoy.com/)是一个着色器交流平台，有大量的优异Demo可供围观。这是`Shadertoy`创始人之一Inigo Quilez的个人网站[Inigo Quilez](http://www.iquilezles.org/index.html) 。你可以通过这两个网站学习
  - [光线追踪](https://zh.wikipedia.org/zh-hans/%E5%85%89%E7%B7%9A%E8%BF%BD%E8%B9%A4)
  - 过程式渲染
  - 视觉特效

### AI

- 两种常见的AI模型：[Finite-state machine](https://zh.wikipedia.org/wiki/%E6%9C%89%E9%99%90%E7%8A%B6%E6%80%81%E6%9C%BA) 、 Behaviour Tree。
- 寻路算法：[A*](https://en.wikipedia.org/wiki/A*_search_algorithm), [Theta*](http://www.gameaipro.com/GameAIPro2/GameAIPro2_Chapter16_Theta_Star_for_Any-Angle_Pathfinding.pdf), [JPS](https://zerowidth.com/2013/05/05/jump-point-search-explained.html), [JPS+](http://www.gameaipro.com/GameAIPro2/GameAIPro2_Chapter14_JPS_Plus_An_Extreme_A_Star_Speed_Optimization_for_Static_Uniform_Cost_Grids.pdf)
- 资料
  - [Game AI Pro](http://www.gameaipro.com/)
  - 《游戏人工智能编程案例精粹》

### 游戏物理

- 《游戏开发物理学》
- 《The Nature of Code》
- 开源物理引擎：Bullet 

### 多人游戏编程

- 《网络多人游戏架构与编程》
- [Writing Server and Network Code for Your Online Game](https://www.codeofhonor.com/blog/writing-server-and-network-code-for-your-online-game)

## 任务

- 请自行规划时间，鼓励在任务的推进过程中完成学习，而不是反复学习却不产出。
- 学习日志以“技术博客”的形式给出。
    - 爱因斯坦说过：如果你不能向一个六岁小孩解释清楚一个问题，那么你其实并不真正的理解它。 希望你的文章能让不了解这个领域的人也能看懂。
    - 可实现的——有足够的伪代码或真实代码片段来描述实现，可以让人能依据你的文章重现该技术。
    - 自我加工过的——不要复制书籍和技术资料中的原句，而是用自己的思路整理过。
    - 杜绝流水账式日志，可以用问题->思考->解决之类的流程来描述你是如何学习、理解的。

- 我们会根据你`Github`仓库中的`Commit`记录来观察你的学习进度，请[规范你的Commit message](https://chris.beams.io/posts/git-commit/)，并每日踊跃提交你的学习进度。
- 综上所述，推荐的学习顺序是`Markdown`=>`Git`=>...
- 依据个人兴趣，选择下列任一任务进行：

### Coolest Pixel Game。
1. 设计一个全新的游戏玩法(体量较小）。
2. 通过`PICO-8`来实现你的玩法原型，尽量简化美术。
3. 自我试玩、分享给其他人试玩，询问自己和他人：“这个游戏是否有趣？”
4. 分析不有趣的原因，对玩法进行更新、裁剪、优化，回到3。
5. 玩法基本满意，开始堆积你的游戏内容（关卡、道具、敌人）。
6. 润色，**全部依靠自己**完成美术、音效、音乐。

### Make Game With Your Partners
* 主动勾搭你认识的或同在夏令营的同学，组成你的开发小队，队内包含
    * 开发
    * 策划
    * 美术

* 可以一人身兼多职哦:)
* 做你们想做的游戏去吧。
* 在夏令营结束之前给出你们的游戏原型（包含基本的玩法、美术的设计风格、可玩的关卡原型），我们需要看到你们的创造力、学习成果。
* 在夏令营结束以后请继续你们的开发o(*￣▽￣*)ブ

### Learn Advanced Technology
* 在进阶知识区找到你喜欢的方向
* **深入**学习并写出一个/多个Demo
* 从**底层**开始实现，也就是说，不借助相关领域的轮子，从零开始实现（你可以在学习物理的时候用渲染引擎来渲染你的画面，但是不可以直接使用现成的物理引擎，以此类推）。

* （可选）接触一些这个领域最新的技术。（例如GPU物理等）