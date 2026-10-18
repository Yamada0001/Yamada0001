<div align="center">

# Tayama

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1400&color=2F81F7&center=true&vCenter=true&width=600&height=45&lines=Minecraft%20%E6%9C%8D%E5%8A%A1%E7%AB%AF%E6%8F%92%E4%BB%B6%E5%BC%80%E5%8F%91;Java%20%C2%B7%20Paper%20%C2%B7%20Folia;%E6%8A%8A%E9%80%89%E6%8B%A9%E6%9D%83%E4%BA%A4%E5%9B%9E%E7%BB%99%E6%9C%8D%E4%B8%BB" alt="Minecraft 服务端插件开发 · Java / Paper / Folia" />

<sub>恋旧是与生俱来的礼物，期待是重逢前的希望</sub>

</div>

---

## 关于

我是 Tayama，GitHub 上是 Yamada0001，代码里署名 FluxCraft。

主要写 Minecraft 服务端插件，Java 为主，跑在 Paper 上，也尽量照顾 Folia。最早只是给自家服务器做个菜单，做到后面慢慢发现，比起替服主改配置，不如让他自己能改——于是热重载、YAML、多语言这些东西就一路留了下来。

现在动手前会先问自己两句：这段调度在 Folia 上会不会炸？这个值真的需要写死吗？

- **平台** — 以 Paper 为主，同时兼容 Folia，不碰 `BukkitScheduler`，走 Region / Entity 调度器
- **形态** — 尽量不改服务端、不进 NMS，用官方 API 配合生态插件拼出想要的效果
- **边界** — 配置能解决的不写死，写死的地方留开关

## 正在做

**MiaoMenu V3.1** —— 把对话框菜单补进菜单系统，让 Java 版背包菜单、基岩版表单和对话框共用同一份配置。三种形态并存，麻烦的地方不在界面，而在条件与变量的语义得保持一致。

## 项目

| 项目 | 说明 | 技术 |
| :-- | :-- | :-- |
| **[MiaoMenu](https://github.com/Yamada0001/MiaoMenu)** | 跨平台菜单解决方案。一套配置同时驱动 Java 版背包菜单与基岩版表单，带条件系统、动作系统、热重载与 BungeeCord / Velocity 跨服 | `Java 25` `Paper 26.2` `Folia` |
| **[VillagerRevolution](https://github.com/Yamada0001/VillagerRevolution)** | 给村民 AI 加上更多样的行为与交互，保持 Folia 兼容 | `Java 25` `Paper 26.2` |
| **[Fxchat](https://github.com/Yamada0001/Fxchat)** | 聊天格式插件。十六进制颜色、PlaceholderAPI 变量、生物群系占位符、玩家头像渲染，配置热更新 | `Java 21+` `Paper` |
| **[Super-EndBox](https://github.com/Yamada0001/Super-EndBox)** | 把末影箱与木桶从 3 行扩展到 6 行 | `Paper 1.21` |
| **[Carefully-Log](https://github.com/Yamada0001/Carefully-Log-MC)** | 更细致的服务端日志 | `Paper 1.21` |

<sub>另外还有几个 Android / TWRP 相关的 fork（Xiaomi SM8850 设备树、system_vold 等），属于折腾设备的痕迹，不在主线。</sub>

## 技术栈

**语言**　Java（主要）；Python、C++（Android 设备树与系统组件）

**服务端**　Paper / Bukkit API、Folia、Floodgate（基岩版互通）

**生态集成**　PlaceholderAPI、CraftEngine、ItemsAdder、Oraxen、MMOItems、HeadDatabase

**工程**　Maven、GitHub Actions、Qodana、bStats

## 在 GitHub 上

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Yamada0001&show_icons=true&hide_border=true&hide_title=true&bg_color=00000000&icon_color=2F81F7&text_color=7D8590&title_color=2F81F7&rank_icon=github" alt="GitHub 统计" />
<img height="165" src="https://streak-stats.demolab.com?user=Yamada0001&hide_border=true&background=00000000&ring=2F81F7&fire=2F81F7&currStreakNum=7D8590&currStreakLabel=2F81F7&sideNums=7D8590&sideLabels=7D8590&dates=7D8590" alt="连续提交" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Yamada0001&bg_color=00000000&color=2F81F7&line=2F81F7&point=FFFFFF&area_color=2F81F7&area=true&hide_border=true&custom_title=Contribution%20Activity" alt="贡献图" />

</div>

<!-- 想要提交热力图的小蛇动画：用 Platane/snk 的 Action 生成 output 分支，再把下面这行取消注释即可
<img src="https://raw.githubusercontent.com/Yamada0001/Yamada0001/output/github-snake.svg" alt="snake" />
-->

## 几句话

> 宁可少一个功能，也不要一个在 Folia 上会炸的调度。

> 宁可多一层配置，也不要让服主为了改一句话去动代码。

---

<div align="center">

邮件最快：**[Avyra@QQ.com](mailto:Avyra@QQ.com)**
插件的问题，也可以直接在对应仓库开 issue。

<sub><a href="https://github.com/Yamada0001">github.com/Yamada0001</a></sub>

</div>
