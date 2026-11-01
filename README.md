# DSH Market Index: TeamAI & LiteLLM Ecosystem

DeepSeek Harness (DSH) 插件市场索引源，收录面向团队协同与模型治理的核心插件：

- **`dsh-teamai-panel`**：DeepSeek Harness 侧边栏面板，用于团队技能、MCP 和提示词管理与同步。
- **`dsh-resource-center`**：DeepSeek Harness 侧边栏面板，用于 LiteLLM 虚拟钥匙、动态模型注入、MCP 转发与花费统计。

---

## 如何在 DeepSeek Harness 中使用本插件中心

### 方式一：在 DSH 图形界面中订阅（推荐）

1. 打开 **DeepSeek Harness**（Desktop 应用或 Web 界面）。
2. 在左侧菜单点击 **Plugins（插件）**，进入 **Discover（发现）** 标签页。
3. 点击右上角 **索引源**（Index Sources），点击添加以下索引源地址：

```
https://raw.githubusercontent.com/backtomyfuture/dsh-market-index/main/market-index.json
```

4. 添加后即可在发现列表中看到 **TeamAI 资源中心** 和 **LiteLLM 资源中心**，直接点击 **安装** 按钮即可一键完成装载！

---

### 方式二：通过 DSH CLI 命令行安装

如果你更习惯使用终端命令，也可以直接通过 Git Spec 安装到指定 Profile：

#### 1. 安装 TeamAI 插件 (`dsh-teamai-panel`)
```sh
# 桌面客户端 (Desktop profile)
dsh plugin --profile desktop add dsh-teamai-panel

# 浏览器 Web 客户端 (Web profile)
dsh plugin --profile web add dsh-teamai-panel
```

#### 2. 安装 LiteLLM 网关插件 (`dsh-resource-center`)
```sh
# 桌面客户端 (Desktop profile)
dsh plugin --profile desktop add dsh-resource-center

# 浏览器 Web 客户端 (Web profile)
dsh plugin --profile web add dsh-resource-center
```

安装完成后，完全退出 DeepSeek Harness 并重新启动，侧边栏即会出现对应面板。

---

## 插件仓库

- [dsh-teamai-panel](https://github.com/backtomyfuture/dsh-teamai-panel) - DeepSeek Harness sidebar panel for TeamAI.
- [dsh-resource-center](https://github.com/backtomyfuture/dsh-resource-center) - DeepSeek Harness sidebar for LiteLLM models, MCP, and spend.

## 许可协议

MIT License
