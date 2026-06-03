# Obsidian 悬浮编辑器 (Hover Editor)

[🇨🇳 中文说明](#-中文说明) | [🇺🇸 English Description](#-english-description)

---

<details open>
<summary><b>🇨🇳 中文说明 (点击收起/展开)</b></summary>

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

</details>

---

<details>
<summary><b>🇺🇸 English Description (Click to expand/collapse)</b></summary>

This plugin enhances the core "Page Preview" plugin by turning the hover popover into a full featured editor instance.

### Disclaimer

This plugin leverages Obsidian functionality that is not currently exposed in the official API. As a result, future Obsidian updates may introduce breaking changes.

I will attempt to keep this plugin working across Obsidian updates but my goal is to either have this functionality implemented directly into Obsidian core or switch over to using the official API for popovers, once it is made available.

### Features

- **The page preview popover is now an actual editor instance**
  - Most editor functionality is supported including switching between modes.
- **The popover is now draggable and resizable**
- **The popover can now be pinned to prevent it from auto closing**
  - Popovers will auto pin when dragged or resized.
  - With pinning, multiple popovers can be open at the same time.
- **When opening a popover, it will become the active pane and receive focus**
  - This means you can use keyboard shortcuts like `ctrl+e` to switch modes after triggering a popover.
  - When the popover closes, focus will revert back to the previous document.
- **The popover now has a nav bar which includes the document title and editor controls**
- **The top drag handle can be double clicked to minimize the popover**
- **There is a plugin setting that allows for setting the default editor mode**
  - Options are: "Open in Reading mode", "Open in Editing mode", or "Match the mode of the current document".
- **When hovering a link containing header or block ref, the editor will open and auto scroll to the ref location**
- **When multiple popovers are active and on top of each other, the currently active popover will remain on top**

### Demo

https://user-images.githubusercontent.com/89109712/160023366-7a1ca044-5725-4d30-a0a7-f7e0664281da.mp4

### Installing

Hover Editor can be found and installed via the Obsidian Community Plugins browser.

### Installing via BRAT

If you want to participate in early testing you can install the plugin using BRAT:
- Install the BRAT plugin via the Obsidian Plugin Browser and then add the beta repository "nothingislost/obsidian-hover-editor".

### Manually installing the plugin

- Copy over `main.js`, `manifest.json`, and `styles.css` to your vault `VaultFolder/.obsidian/plugins/obsidian-hover-editor/`.

### Acknowledgments

- Thanks to **pjeby** for contributing a ton of core functionality related to making Hover Editors interop properly with native Obsidian components.
- Thanks to **boninall** for contributing the "open in new popover" functionality.
- Thanks to **murf**, **liam**, **obadiahcruz**, and **javalent** for the early testing and feedback.

</details>
