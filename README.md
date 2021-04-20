<<<<<<< HEAD
### 1. AI 方法

划分连通块 + 解线性方程组 + 枚举变元 + 随机点

具体见 [扫雷AI](ai\AI.md)

运行结果：

<img src="运行结果\impicture_20210421_030325.png" alt="impicture_20210421_030325" style="zoom: 80%;" />

### 2. 运行方式

自动扫雷：

```shell
python aitest.py ai
```

手动扫雷：

```shell
python aitest.py manual
```

### 3. 文件结构

* game
  * app                  一个CGame 类， 提供游戏接口
  * cmdins      	  各个命令的实现
    * check       点击一个单元格 1 [x] [y]
    * debug      用于调试（偷看） 2：显示所有雷， 3隐藏所有雷
    * flag           用于标记雷 4 [x] [y]
  * command      命令管理器
  * defines           定义常量
  * grids               网格类
  * unit                 单元格类
  * utils                工具函数
* ai
  * ai.py                       实现 AI 的函数集
  * aitest.py                用于测试（人工和AI）
  * gauss.py			    解非齐次线性方程组 + 枚举自由变元 的函数集
  * AI.md                     实现思路说明
* 运行结果                截图和gif
* Enumerate            之前用 C++实现的枚举部分， 问了一下不让用就弃用了

=======
# Boom

#### 介绍
{**以下是 Gitee 平台说明，您可以替换此简介**
Gitee 是 OSCHINA 推出的基于 Git 的代码托管平台（同时支持 SVN）。专为开发者提供稳定、高效、安全的云端软件开发协作平台
无论是个人、团队、或是企业，都能够用 Gitee 实现代码托管、项目管理、协作开发。企业项目请看 [https://gitee.com/enterprises](https://gitee.com/enterprises)}

#### 软件架构
软件架构说明


#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
>>>>>>> 927b4846bba8b306cbb10b45f32a4dd8bbd92eb5
