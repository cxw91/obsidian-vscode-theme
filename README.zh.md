# VS Code Theme for Obsidian

把 VS Code 官方默认主题的配色（2026 深色）搬进 Obsidian，支持**暗色 / 亮色双模式**。

---

## 一、安装

### 1.1 社区主题方式（推荐，需经市场审核通过）

1. 设置 → 外观 → 主题 → 管理
2. 搜索 VS Code
3. 安装 

### 1.2 手动方式

把本目录下的 `manifest.json` 与 `theme.css` **两个文件**，复制到你的 Vault：


```

<你的Vault>/.obsidian/themes/VS Code/

├── manifest.json

└── theme.css

```


> **注意**：文件夹名须为 `VS Code`，与 `manifest.json` 的 `name` 字段一致。

> `.obsidian` 是隐藏目录，Windows 可在资源管理器地址栏直接输入 `.obsidian\themes` 进入。


## 二、 启用
  
1. `设置` → `外观`

2. `基础主题` 选 **深色** 或 **浅色**（决定默认用哪套）

3. `主题` 下拉框选 **VS Code**

不重启即生效。若未出现，点主题下拉框旁的刷新按钮。

---
## 三、效果展示

![](附件/1.png)

![](附件/2.png)

![](附件/3.png)

![](附件/4.png)
  

## 四、许可证

- 本主题以 **MIT License** 发布，见 [LICENSE](LICENSE)。可自由使用、修改、再分发。
- 配色数据来源于 [microsoft/vscode](https://github.com/microsoft/vscode)（MIT License），

---

*本主题不修改任何笔记内容，仅影响渲染样式。删除目录即可完全回退。*