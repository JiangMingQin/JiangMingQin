<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JiangMingQin/JiangMingQin/main/assets/header-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/JiangMingQin/JiangMingQin/main/assets/header-light.svg" />
    <img src="https://raw.githubusercontent.com/JiangMingQin/JiangMingQin/main/assets/header-light.svg" alt="MingQin J" width="100%" />
  </picture>
</p>

<div align="center">

**写让美术和程序少吵架的工具。**

Python · 智能算法 · Unity · Blender

<img src="https://img.shields.io/badge/%E6%B1%82%E8%81%8C%E4%B8%AD-OPEN%20TO%20WORK-a6e3a1?style=flat-square&labelColor=1e1e2e" alt="Open to work" />
<img src="https://img.shields.io/badge/%E5%9F%BA%E7%A1%80-%E5%85%AD%E5%B9%B4%E7%B4%A0%E6%8F%8F-f9e2af?style=flat-square&labelColor=1e1e2e" alt="Art foundation" />

</div>

---

## 精选项目

<table>
<tr>
<td width="50%" valign="top">

#### HROF 平台 <sub>论文审稿中 · 共同第一作者</sub>

我提出的算法无关拟合框架，可在遗传算法与差分进化之间切换；配套 PySide 软件实现「边拟合边手动修改」的风格化图像工作流。

在有限三角形叠加拟合图像问题上取得优于已公开基线的结果（单核条件，数据以论文为准）。源码暂不公开。

`Python` `NumPy` `PySide` `DE / GA`

</td>
<td width="50%" valign="top">

#### [LazyTkinter](https://github.com/JiangMingQin/LazyTkinter)

基于 CustomTkinter 的声明式封装。链式语法让控件属性直接出现在代码补全里，省掉反复翻文档；纵横容器借鉴 Web 的 flex 布局思路。

先手搓原型，再交给 AI 改。

`Python` `CustomTkinter` `MIT`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [CH3-Orange-Tab](https://github.com/JiangMingQin/CH3-Orange-Tab)

从自己的高频行为出发：打开浏览器后最常做的是点书签，于是把收藏夹做成界面中心，去掉搜索栏。

双栏布局 + 键盘导航 + 模糊搜索；用 **frecency 算法**做快速启动栏，常用站点自然浮现。自己持续用了近一年。

`JavaScript` `Chrome Extension` `UI/UX`

</td>
<td width="50%" valign="top">

#### 节点式工作流引擎 <sub>开发中</sub>

把散落的离散 Python 组件串起来。VueFlow 做节点，NaiveUI 做控件，Python 调度器 + FastAPI 做后端，已能跑通模拟退火。

设计上参考 Rust 的强约束与 Go 的简约核心，能力交给外部自定义节点；交互参考 ComfyUI 与 Blender。

`Vue` `VueFlow` `FastAPI` `NaiveUI`

</td>
</tr>
<tr>
<td colspan="2" width="100%" valign="top">

#### 课表爬虫工具 <sub>已停用</sub>

用 Selenium 抓取网页课表、lxml 解析 DOM，纯手写、未依赖 AI。解决的真实问题是「部门里收集课表难」——手工填的无课表变成可快速汇总的数据。原站点更新后工具已失效。

`Python` `Selenium` `lxml`

</td>
</tr>
</table>

## 算法

- **模拟退火** — 熟悉流程与改进方向：与遗传算法 / 禁忌搜索混合、UCB 算子选择、自适应内循环次数、早停。解过中小规模 TSP、矩形件排样与连续非线性问题
- **遗传算法** — 熟悉流程与调参原理；GA + 贪心解 01 背包
- **其它智能算法** — 粒子群、禁忌搜索、差分进化；能针对问题结构改造算法或搭建框架
- **建模思路** — 因为数学建模入门智能算法，习惯把实际问题改造成可求解的数学问题

## Unity 与 3D

- **Unity**（最熟悉的引擎）— 动画状态机、资产导入、Terrain 地编。做过 FPS（NavMesh 敌人追踪 + 护送目标）、AR 打地鼠（Vuforia）、VR 光剑音游（Pico 头显 + 手柄）三个 demo
- **Blender** — 材质与贴图流程、人物与建筑建模；会写 `bpy` 脚本做程序化生成和插件，正在还原《绝区零》的以太结晶
- **C4D** — 材质、简单动画与渲染

## 现在在做什么

- 重构节点式工作流引擎，收敛 AI 生成带来的冗余
- 迭代 HROF 平台（论文审稿中）
- PS1 复古渲染管线探索：低多边形 + dithering + CRT 后处理

## 技术栈

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,cs,js,vue,unity,blender,git,linux,flask&theme=dark" alt="Tech stack" />
</div>

<div align="center">
<sub>NumPy · PySide · CustomTkinter · DrissionPage · selenium · FastAPI · VueFlow · ComfyUI · C4D · Vim / Helix</sub>
</div>

<div align="center">
<sub>AI 辅助开发：能读懂、能判断、能改，不让生成结果成为黑盒。</sub>
</div>

## 一点数据

<table>
<tr>
<td valign="top"><img src="https://github-readme-stats.vercel.app/api?username=JiangMingQin&show_icons=true&locale=cn&hide_border=true&bg_color=1e1e2e&title_color=a6e3a1&text_color=cdd6f4&icon_color=a6e3a1&rank_icon=github" alt="GitHub 统计" /></td>
<td valign="top"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JiangMingQin&layout=compact&locale=cn&hide_border=true&bg_color=1e1e2e&title_color=a6e3a1&text_color=cdd6f4&langs_count=6" alt="常用语言" /></td>
</tr>
</table>

### 贡献轨迹

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JiangMingQin/JiangMingQin/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/JiangMingQin/JiangMingQin/output/github-snake.svg" alt="Contribution snake" />
</picture>

## 联系

<div align="center">

<a href="mailto:3315536229@qq.com"><img src="https://img.shields.io/badge/3315536229%40qq.com-cba6f7?style=flat-square&labelColor=1e1e2e&logo=maildotru&logoColor=white" alt="Email" /></a>
<a href="https://jiangmingqin.github.io/"><img src="https://img.shields.io/badge/%E4%BD%9C%E5%93%81-jiangmingqin.github.io-a6e3a1?style=flat-square&labelColor=1e1e2e&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="https://github.com/JiangMingQin"><img src="https://img.shields.io/badge/GitHub-JiangMingQin-cdd6f4?style=flat-square&labelColor=1e1e2e&logo=github&logoColor=white" alt="GitHub" /></a>

<sub>欢迎聊技术美术、工具开发、智能算法，或者独立游戏。</sub>

</div>
