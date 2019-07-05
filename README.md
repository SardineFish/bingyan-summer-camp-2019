# 2019冰岩夏令营游戏组

## 前言

- 游戏是作品（项目）驱动的，如果你没有一个新的游戏玩法，只是复刻已有的游戏，你会损失很多的成就感。而单单脑子中有崭新的游戏玩法，你还未或者无法实际开发验证它，你是无法确定它是不是真的有趣的。
- 鉴于上一条，每一个游戏开发都应该抱有创作游戏的热情和思考游戏玩法的习惯。每一个游戏策划都应该在开发能力和视野上也该对自己有要求。不要把自己严格归属于开发或者策划，你是游戏创作者。
- 科学上网是技术资料搜索的基本要求，如果你不会，可以勾搭**程序组**的朋友们提供支持。
- 下面的链接多数指向英文资料，如果阅读起来比较吃力，可以尝试自行在`Google`或`Github`上寻找中文翻译版，基本都有。但是在此之前要考虑清楚：**如果你现在走了轻松的路，你只不过是在暂时性地逃避，你总有一天会重新走回这个交叉口，走那条更艰辛的路。**
- 对于一些陌生的概念或设计理念，可以从各种博客和社区（如知乎）中寻找到前辈们积累下的理解和分析。
- 遇到不懂的名词不要跳过，利用维基百科学习。
- 积极找同在夏令营的其他同学聊天、问问题，有一起努力前进的伙伴不是很好吗:)



##  基础知识

### 编程语言


- C# —— 具有 C 系语言的语法结构的 OOP 语言，支持操作符重载、泛型等。C# 是 Unity 和 XNA 等游戏引擎的主要开发语言。此外，C# 也可以用于开发桌面应用程序、后端服务开发等。Microsoft 为 C# 提供了非常详尽的教学和文档：[C# Guide](https://docs.microsoft.com/en-us/dotnet/csharp/index)
- C++ —— 游戏引擎的主要底层语言，兼顾了性能和代码可维护性。使用 C++ 作为开发语言的游戏引擎有 Unreal Engine、Cocos2D 等。C++ 的学习曲线较为陡峭，推荐借助书籍进行学习。参考资料：[C++ Language](http://www.cplusplus.com/doc/tutorial/)、[C++ Primer](http://www.charleshouserjr.com/Cplus2.pdf)
- Javascript/Typescript —— 非常轻量的，主要应用于 Web 平台的解释型或即时编译型脚本语言，具有极良好的跨平台特性。Cocos2dX JS 等游戏引擎将 JS/TS 作为主要的开发语言。参考资料：[Javascript - MDN](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)、[Typescript](https://www.typescriptlang.org/)
- [Lua](https://www.lua.org/) —— 常见的游戏脚本语言，极其轻量，通常被作为游戏的嵌入式脚本使用。Pico-8 是一款使用Lua作为游戏开发语言的像素风复古游戏引擎。Lua 的语法非常简单，可以通过官方语言文档进行学习。[Programming in Lua](https://www.lua.org/pil/contents.html)

### 游戏编程模式

- [Game Programming Pattern](http://gameprogrammingpatterns.com/) ，总结了一些**很重要**的游戏开发的设计模式，帮助你对 GamePlay 开发进行一个总览式的梳理。
- [Entity Component System](https://en.wikipedia.org/wiki/Entity%E2%80%93component%E2%80%93system) , 一种**优雅**、**缓存友好**的游戏架构模式。有效地利用组合代替继承、解决了复杂的依赖关系。

### 代码版本管理

- 请使用搜索引擎自行了解版本管理的作用。
- [Git](https://git-scm.com/) 是一个出色的版本管理工具。**不推荐图形界面`Git`，请熟悉命令行操作。** 推荐通过官方的 [Git Book](https://git-scm.com/book/en/v2) 进行学习。
- [Github](https://github.com/) 是一个通过`Git`进行版本管理的代码托管服务。请在夏令营期间全程用 `Git` 在 `Github` 上管理你的项目源码、学习日志，我们会进行 Code review。
  - 书写 `Github` 的 README 文档时会用到 `Markdown` 语言。这是一种轻量级标记语言，它的源码有极高的人类可读性，可以轻松地生成 HTML 文档。你看到的本文档就是用 `Markdown` 书写的。**请学习 `Markdown` 语言并用它完成你的所有学习日志。** [Markdown Guide](https://www.markdownguide.org/)
  - 书写规范的、可读的 `Commit Message`。理解 `Git Commit` 的意义，书写 `Commit Message` 来记录你的工作进度。

### 游戏引擎

- 人见人爱花见花开的 [Unity](https://unity3d.com/cn)，一款面向个人免费的跨平台游戏引擎。
    - 主要使用 C# 作为游戏开发语言，
    - 借助强大的跨平台兼容性，可以将游戏轻松的构建到这些平台上：
        - Android
        - iOS
        - PC
        - Web
    - Unity 官方提供了大量的教学案例，详尽的 API 文档和开发手册：
        - [Unity Tutorials](https://unity3d.com/cn/learn/tutorials)
        - [Unity User Manual 2019.1](https://docs.unity3d.com/Manual/index.html)
        - [Unity Scripting API](<https://docs.unity3d.com/ScriptReference/index.html>)
- [PICO-8](https://www.lexaloffle.com/pico-8.php)， 一个复古、轻量的像素游戏终端（引擎）。
  - 它的一些限制和特点
    - 屏幕分辨率为128x128，仅支持16色
    - 卡带（成品游戏）大小至多为32KB
    - 仅支持上下左右AB控制输入
    - 可以且仅能用自带的精灵、地图、音效、音乐编辑器来完成创作
  - **限制带来了想象力** ，你可以用PICO-8来进行快速游戏原型开发，可仅靠自己的力量完成视觉、听觉效果的游戏润色。
  - [PICO-8 Music Tutorial](https://www.youtube.com/playlist?list=PLur95ujyAigsqZR1aNTrVGAvXD7EqywdS)
  - 它不是免费的——但是很便宜，你要是买不起我给你买。
- [Cocos2d-JS](http://www.cocos2d.org/) 一个基于 `Javascript` 的 2D Web 游戏引擎。
    - `Cocos2d-JS` 支持 `Javascript` 和 `Typescript`
    - 可以构建出轻量的 Web 游戏
    - 可以构建微信小游戏
    - 有中文文档

## 进阶知识

### 渲染

- OpenGL 是一个用于渲染 2D、3D 图形的**跨语言、跨平台的应用程序编程接口** 。它是一套 API，你可以用任何存在 OpenGL 绑定库的语言来使用它。你可以通过它来了解模型、贴图是怎么一步一步在屏幕上被渲染出来的，即学习**现代渲染管线** 。[Learn OpenGL](https://learnopengl.com/) 
- [Shadertoy](https://www.shadertoy.com/) 是一个着色器交流平台，有大量的优异Demo可供围观。这是 Shadertoy 创始人之一 Inigo Quilez的个人网站 [Inigo Quilez](http://www.iquilezles.org/index.html) 。你可以通过这两个网站学习
  - [光线追踪](https://zh.wikipedia.org/zh-hans/%E5%85%89%E7%B7%9A%E8%BF%BD%E8%B9%A4)
  - 过程式渲染
  - 视觉特效
- [ShaderLab](https://docs.unity3d.com/Manual/SL-Shader.html) 是 Unity 的渲染系统所使用的着色器语言，用于构造适用于 Unity 渲染系统的材质着色器，你可以通过 Unity 的官方文档和《Unity Shader 入门精要》学习有关 Unity 图形学开发的相关知识。
- [Shader Graph](https://unity.com/cn/shader-graph) 是从 Unity 2018 开始推出的一种可视化的着色器设计器，通过模块化、可视化的图形界面操作减少繁琐的代码编写。（推荐在入门了 Unity 图形学开发之后再考虑学习）
- [Scriptable Render Pipeline](https://unity.com/srp) 是 Unity 新推出的高度可扩展、可编程的渲染管线 API，基于 SRP 可以在 Unity 中构建自定义的渲染管线。（推荐在深入学习了图形学开发和渲染管线架构之后再考虑学习）

### AI

- 两种常见的AI模型：[Finite-state machine](https://zh.wikipedia.org/wiki/%E6%9C%89%E9%99%90%E7%8A%B6%E6%80%81%E6%9C%BA) 、 Behaviour Tree。
- 寻路算法：[A*](https://en.wikipedia.org/wiki/A*_search_algorithm), [Theta*](http://www.gameaipro.com/GameAIPro2/GameAIPro2_Chapter16_Theta_Star_for_Any-Angle_Pathfinding.pdf), [JPS](https://zerowidth.com/2013/05/05/jump-point-search-explained.html), [JPS+](http://www.gameaipro.com/GameAIPro2/GameAIPro2_Chapter14_JPS_Plus_An_Extreme_A_Star_Speed_Optimization_for_Static_Uniform_Cost_Grids.pdf)
- 资料
  - [Game AI Pro](http://www.gameaipro.com/)
  - 《游戏人工智能编程案例精粹》

### 多人游戏编程

- 《网络多人游戏架构与编程》
- [Writing Server and Network Code for Your Online Game](https://www.codeofhonor.com/blog/writing-server-and-network-code-for-your-online-game)

### 游戏物理

- 《游戏开发物理学》
- 《The Nature of Code》
- 开源物理引擎：Bullet、[Box2D](https://box2d.org/about/)...

### 如果这些还不够...

<https://github.com/miloyip/game-programmer>







## 任务

- 请自行规划时间，鼓励在任务的推进过程中完成学习，而不是反复学习却不产出。
- 学习日志以“技术博客”的形式给出。
    - 爱因斯坦说过：如果你不能向一个六岁小孩解释清楚一个问题，那么你其实并不真正的理解它。 希望你的文章能让不了解这个领域的人也能看懂。
    - 可实现的——有足够的伪代码或真实代码片段来描述实现，可以让人能依据你的文章重现该技术。
    - 自我加工过的——不要复制书籍和技术资料中的原句，而是用自己的思路整理过。
    - 杜绝流水账式日志，可以用问题->思考->解决之类的流程来描述你是如何学习、理解的。
- 我们会根据你`Github`仓库中的`Commit`记录来观察你的学习进度，请[规范你的Commit message](https://chris.beams.io/posts/git-commit/)，并每日踊跃提交你的学习进度。
- 综上所述，推荐的学习顺序是`Markdown`=>`Git`=>...

### 基础任务

#### Git 和 Markdown

理解并学会 Git 的使用，如果你还没有 GitHub 账号，请创建一个。

在 GitHub 上创建一个代码仓库用于存放你本次夏令营的学习日志，使用 Markdown 编写你的学习日志，在完成每天工作之后 `commit` 你的学习日志并 `push` 到 GitHub 的远程仓库上，我们会根据你的 Commit 记录来观察你的学习进度。



#### 巩固编程语言基础

可能你在这之前已经学习了 C/C++, C#, JS, TS 之类的编程语言，或许你学习他只是因为学校的课程，或是跟着教程使用一款引擎。工欲善其事必先利其器，希望你能稍微花费1到3天的时间巩固你所选择的编程语言基础，更深入的理解这门语言。你可以选择用项目驱动的方式来激发你的学习热情，比如做一个在控制台上玩的小游戏，或是一个实用的小工具。



### 进阶任务

根据个人兴趣，选择以下任务之一作为参与本次夏令营的终极任务，可以把任务的实现贯穿到整个夏令营的学习过程中。

#### Coolest Pixel Game。
1. 设计一个全新的游戏玩法(体量较小）。
2. 通过`PICO-8`来实现你的玩法原型，尽量简化美术。
3. 自我试玩、分享给其他人试玩，询问自己和他人：“这个游戏是否有趣？”
4. 分析不有趣的原因，对玩法进行更新、裁剪、优化，回到3。
5. 玩法基本满意，开始堆积你的游戏内容（关卡、道具、敌人）。
6. 润色，**全部依靠自己**完成美术、音效、音乐。

#### Make Game With Your Partners
* 主动勾搭你认识的或同在夏令营的同学，组成你的开发小队，队内包含：
    * 开发
    * 策划
    * 美术

* 可以一人身兼多职哦:)
* 做你们想做的游戏去吧。
* 在夏令营结束之前给出你们的游戏原型（包含基本的玩法、美术的设计风格、可玩的关卡原型），我们需要看到你们的创造力、学习成果。
* 在夏令营结束以后请继续你们的开发o(*￣▽￣*)ブ

#### Learn Advanced Technology
* 在进阶知识区找到你喜欢的方向
* **深入**学习并写出一个/多个Demo
* 从**底层**开始实现，也就是说，不借助相关领域的轮子，从零开始实现（你可以在学习物理的时候用渲染引擎来渲染你的画面，但是不可以直接使用现成的物理引擎，以此类推）。

* （可选）接触一些这个领域最新的技术。（例如 PBR 等）