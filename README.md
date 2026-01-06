> 💡 本笔记底稿包含[ddy-ddy/cs-408](https://github.com/ddy-ddy/cs-408)（[MIT License](https://opensource.org/license/mit)）的OneNote内容

计算机科学408的[Obsidian](https://obsidian.md/)笔记，**牺牲**OneNote嵌套表格+随处书写，**换取**Obsidian双链无向图+Github版本化工作流

|笔记内容|脚本|其他|
|:-:|:-:|:--|
|[数据结构](1数据结构/数据结构.md)|[Python](https://www.python.org/)|[Obsidian](https://obsidian.md/download)|
|[计算机组成原理](2计算机组成原理/计算机组成原理.md)|[移除行首标签](移除行首标签.cmd)|[Github Desktop](https://github.com/apps/desktop)|
|[操作系统](3操作系统/操作系统.md)|[恢复行首标签](恢复行首标签.cmd)|[笔记仓库页面](https://github.com/XColorful/CS408-Obsidian-Note)|
|[计算机网络](4计算机网络/计算机网络.md)||[笔记仓库Issue](https://github.com/XColorful/CS408-Obsidian-Note/issues)|

## 使用说明

### 下载笔记
1. 下载[Github Desktop](https://desktop.github.com/download/)，到[仓库页面](https://github.com/XColorful/CS408-Obsidian-Note)点击绿色的`<>Code ▼`，点击`Open with Github Desktop`
2. 下载[Obsidian](https://obsidian.md/download)，打开本地仓库（Open folder as vault），选择本地仓库目录（`CS408-Obsidian-Note`）

### 同步笔记更新

1. 打开[Github Desktop](https://github.com/apps/desktop)，点击`Fetch origin`，如有更新则点击`Pull origin`即可
2. （可选）点击`Current branch`，可以查看是否有其他分支（Branch）更新

### 个性化与协作

1. 到[仓库页面](https://github.com/XColorful/CS408-Obsidian-Note)点击`<>Code ▼`右上角的`Fork`，在自己的仓库界面[下载笔记](#下载笔记)，即可得到自己的专属版本
2. 对笔记进行修改后（如添加自己的内容、修改笔记错误等），在[Github Desktop](https://github.com/apps/desktop)里填写`Summary`、`Description`（可选）后，点击`Commit x files to xxx`即可
3. 协作（详细可以请教程序员朋友或AI）：新建分支（Branch） → 提交修改（Commit） → 点击`Create Pull Request`
4. 提出建议/对笔记有疑问/请教使用方式：到[仓库Issue](https://github.com/XColorful/CS408-Obsidian-Note/issues)点击绿色的`New issue`，描述完之后点击`Create`即可

### 脚本

#### 移除行首标签
> 临时移除所有笔记第一行的所有标签，让[关系图谱](https://publish.obsidian.md/help-zh/%E6%A0%B8%E5%BF%83%E6%8F%92%E4%BB%B6/%E5%85%B3%E7%B3%BB%E5%9B%BE%E8%B0%B1)（`Ctrl` + `G`）更纯净
1. 下载[Python](https://www.python.org/)
2. 运行仓库根目录的`移除行首标签.cmd`或`恢复行首标签.cmd`即可（笔记内快捷方式：[移除行首标签](移除行首标签.cmd)、[恢复行首标签](恢复行首标签.cmd)）

> 💡使用建议（避坑指南）：
> - 运行前：若已修改笔记，请务必先完成`Commit x files to xxx`
> - 纯查看：运行脚本查看完图谱，再`恢复行首标签`后如果[Github Desktop](https://github.com/apps/desktop)里修改没清除，则直接全选修改，右键点击`Discard changes`即可还原
> - 有修改：若在移除标签期间修改了笔记，请先运行`恢复行首标签.cmd`，确认无误后再`Commit x files to xxx`

## 笔记展示

## 在开源中相遇，在实践中改变

资源的有限不是束缚，而是我们在既定历史条件下共同出发的起点。

决定发展的从来不是孤立个体的意志，而是人们在协作实践中改变世界的方式。


“躺平”不是否定，而是一种对现实结构的无声反应。

疲惫与停滞并非个人的失败，而是社会关系中矛盾的体现；

真正的否定，来自对这些矛盾的认识与改造。



矛盾推动事物运动。

平衡只是暂时的状态，新的可能往往诞生于集体行动与结构性张力之中。



意志能给我们方向，但唯有实践能让认识扎根。

改造客观世界的过程中，人们的能动性才真正生成。



在当代数字劳动中，开源是一种社会化生产方式：

知识突破私有的围栏，协作让经验积累为共享财富。



笔记的公开不是单向输出，

而是将思想对象化，使其能够在更广阔的合作网络中流动、被扩展、被修正。



感官满足是短暂的，而知识与实践的沉淀会在共同劳动中积累为现实力量。



每一次阅读、整理与分享，都是一次“认识—实践—再认识”的循环；

个人的学习螺旋上升，也只有在知识共同体中才能获得真正的方向与意义。



拒绝原子化的孤立奋斗。

在共同生产、共同分享、共同进步中，学习不只服务于自我，

而是成为人与世界互相改变的过程。

## 授权信息 (Licensing)

### 1. 原创内容授权

本仓库（衍生作品）依据 **知识共享 署名-相同方式共享 4.0 国际协议**（[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)）授权发布。

#### 您的义务

1. **署名 (BY)**：转载或二次创作须注明原作者 `XColorful` 及 [本仓库链接](https://github.com/XColorful/CS408-Obsidian-Note)。
2. **相同方式共享 (SA)**：衍生作品必须继续使用 **CC BY-SA 4.0** 协议发布。

### 2. 原材料授权与致谢

本笔记底稿包含[ddy-ddy/cs-408](https://github.com/ddy-ddy/cs-408)，原项目采用 **[MIT License](https://opensource.org/license/mit)** 授权。
- 原许可证副本已保留于仓库根目录的[LICENSE_ORIGINAL](LICENSE_ORIGINAL)文件中。
- 感谢原作者 **[ddy-ddy](https://github.com/ddy-ddy)** 提供的优质底稿。