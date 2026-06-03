# Obsidian 悬浮编辑器 (Hover Editor)

[English](README_en.md) | **中文**

---

> [!NOTE]
> **汉化声明**：
> 本项目为 [NothingIsLost/obsidian-hover-editor](https://github.com/nothingislost/obsidian-hover-editor) 插件的中文汉化版本。
>
> - **原项目地址**：[nothingislost/obsidian-hover-editor](https://github.com/nothingislost/obsidian-hover-editor)
> - **主要修改内容**：
>   - 完整汉化了插件的设置面板、右键上下文菜单、快捷指令面板（Command Palette）及窗口工具栏提示。

---

此插件增强了 Obsidian 核心的“页面预览 (Page Preview)”插件，将悬浮预览窗口转换为了一个功能完备的编辑器实例。

### 免责声明

该插件利用了 Obsidian 目前尚未在官方 API 中公开的功能。因此，未来的 Obsidian 更新可能会引入破坏性的改动。

我会尽力在 Obsidian 更新中保持此插件正常运行，但我的最终目标是：要么让此功能直接合入 Obsidian 核心，要么在官方弹窗 API 可用时，立即切回使用官方 API。

### 核心功能

- **页面预览弹窗现在是一个真正的编辑器实例**
  - 支持绝大部分编辑器功能，包括在不同视图模式之间进行切换。
- **悬浮窗支持拖拽移动和调整大小**
- **支持固定悬浮窗以防止其自动关闭**
  - 当拖拽或调整悬浮窗大小时，它们会自动固定。
  - 固定后，你可以同时打开多个悬浮窗口。
- **打开悬浮窗时，它会成为活动面板并获取焦点**
  - 这意味着你在触发悬浮窗后，可以使用快捷键（如 `Ctrl + E`）来直接切换视图模式。
  - 当悬浮窗关闭时，焦点会自动回到之前的文档上。
- **悬浮窗配有导航条，其中包含文档标题和编辑器控件**
- **双击顶部的拖拽控制条可以折叠/最小化悬浮窗**
- **拥有插件设置，允许设定默认的编辑模式**
  - 选项包括：“阅读模式下打开”、“编辑模式下打开” 或 “与当前文档的模式一致”。
- **悬浮在包含标题（Header）或块引用（Block Ref）的链接上时，编辑器会自动打开并滚动到引用的位置**
- **当有多个悬浮窗处于活动状态且相互重叠时，当前活动的悬浮窗会始终保持在最前端**

### 演示

https://user-images.githubusercontent.com/89109712/160023366-7a1ca044-5725-4d30-a0a7-f7e0664281da.mp4

### 安装方式

可以在 Obsidian 的**社区插件**浏览器中直接搜索并安装 **Hover Editor**。

### 通过 BRAT 插件安装

如果你想参与早期测试，可以使用 BRAT 插件进行安装：

- 在 Obsidian 插件浏览器中安装 BRAT 插件，然后添加测试版仓库 `"nothingislost/obsidian-hover-editor"`。

### 手动安装插件

- 复制 `main.js`、`manifest.json` 和 `styles.css` 文件到你的保险库目录 `VaultFolder/.obsidian/plugins/obsidian-hover-editor/` 下。

### 致谢

- 感谢 **pjeby** 贡献了大量核心功能，使得悬浮编辑器能够与 Obsidian 原生组件完美协同工作。
- 感谢 **boninall** 贡献了“在新悬浮窗中打开”的功能。
- 感谢 **murf**、**liam**、**obadiahcruz** 和 **javalent** 的早期测试与反馈。
