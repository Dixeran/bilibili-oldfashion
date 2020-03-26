# bilibili-oldfashion

在 Bilibili 新版播放器上找回一点旧版播放器的感觉。在我看来新版播放器相比旧版主要有几个问题：

1. 普通状态下控制面也自动隐藏，不方面操作且没有节省多少空间
2. 进度条自动隐藏后跳转不便
3. 半透明背景下进度条操作不便
4. 视觉上，播放控制组件（半透明、自动隐藏）与弹幕组件割裂，但后者实际上与播放行为相关。

为了解决上述问题，使用样式覆盖为以下状态：

- 控制面固定显示
- 进度条保持激活状态
- 改为白底控制面，脱离视频窗口
- 仅影响普通、宽屏模式，不影响全屏下半透明样式
- 兼容无黑边模式

效果展示：

（普通模式）

![普通模式-修改后](https://s1.ax1x.com/2020/03/25/8xCib4.jpg)

（宽屏模式）

![宽屏模式-修改后](https://s1.ax1x.com/2020/03/25/8x9z80.png)

## 使用方法

1. 安装 Stylus 插件

2. 选择 Stylus -> 管理样式 -> 备份 -> Import -> 导入所有样式

3. 下载并导入 Release 中的备份文件（json 格式）到 Stylus

   或者：从 https://userstyles.org/styles/181520/bilibili 安装

导入不会清空已有样式。
