# 小禾画布 Codex 插件

让 Codex 可以打开并操作[小禾画布](https://www.xiaohe.store/)。

## 安装

### 方式一：Git marketplace（推荐）

```bash
# 添加插件市场
codex plugin marketplace add https://github.com/wild-River2016/xiaohe-canvas-plugin

# 安装插件
codex plugin add xiaohe-canvas
```

### 方式二：MCP 命令

```bash
codex mcp add xiaohe-canvas -- npx -y @xiaohe-store/canvas-agent mcp
```

## 使用

安装后在 Codex 对话中输入：

```text
打开小禾画布
```

或者直接描述你的需求：

```text
我是淘宝店主，卖童装，想做宣传视频
```

## 功能

- 🎨 模板驱动创作：搜索模板库，智能推荐工作流方案
- 🖼️ 画布操作：创建节点、连线、布局、生成图片/视频
- 💬 引导式对话：主动询问需求，提供专业设计建议

## 相关链接

- [小禾画布](https://www.xiaohe.store/)
- [Canvas Agent npm 包](https://www.npmjs.com/package/@xiaohe-store/canvas-agent)
