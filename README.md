# 量化投放系统 - 工作流后台

这是独立后台原型项目，用于管理 ComfyUI 封装节点和节点类型配置。

## 项目位置

```text
/Users/dashan/Documents/dev/
├── sucai-main
└── sucai-backend-main
```

`sucai-backend-main` 与主站 `sucai-main` 并列，后台页面、文档和 mock 数据均独立维护。

## 页面说明

| 文件 | 说明 |
| --- | --- |
| `login.html` | 后台登录页，原型阶段不做真实校验 |
| `index.html` | 后台主框架，包含左侧菜单 |
| `工作流管理.html` | ComfyUI 封装节点管理 |
| `配置管理.html` | 工作流类型管理 |

## 文档说明

| 文件 | 说明 |
| --- | --- |
| `文档/需求文档.md` | 后台完整需求说明 |
| `文档/过程记录.md` | 后台项目过程记录 |
| `文档/设计文档.md` | 后台设计规范 |
| `共享样式/usage.md` | 后台共享样式使用说明 |
| `共享样式/design-system.md` | 后台设计系统规则 |

## 原型范围

- 所有数据均为 mock。
- 上传状态为 mock，不展示进度条。
- JSON 解析结果为 mock。
- 不接真实接口。
- 不做真实 ComfyUI JSON 解析。
- 不做真实跨页面数据持久化。
- 不做真实工作流运行、映射或结果回写。

## 打开方式

直接用浏览器打开：

```text
/Users/dashan/Documents/dev/sucai-backend-main/login.html
```

也可以直接打开：

```text
/Users/dashan/Documents/dev/sucai-backend-main/index.html
```
