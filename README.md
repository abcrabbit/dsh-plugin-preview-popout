# 预览独立窗口

把右侧文档预览的标签页拖出面板（或使用标签页菜单），在独立窗口中打开该文件。

Detaches a right-side document preview tab into its own window by dragging the tab chip out of the panel, or from the tab menu.

## 安装

**方式一（推荐）**：在 DSH 插件的「发现」页添加索引源

```
https://raw.githubusercontent.com/abcrabbit/dsh-plugin-index/main/index.json
```

然后搜索并安装本插件。

**方式二（手动）**：下载本仓库，在 DSH「设置 → 插件 → 添加插件 → 本地目录」中选择本目录。

## 兼容性

- DSH 0.2.2 系列（在 `0.2.2-rc.5` 上验证）
- 许可证：MIT
## 注意事项

安装后需要在本机生成原生窗口壳（壳不随仓库分发，每台机器用硬链接复用本机 DSH 运行时）：`npowershell -ExecutionPolicy Bypass -File setup\build-native.ps1`n