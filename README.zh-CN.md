# Swagger Master

<p align="right">
  <a href="README.md">English</a>
</p>

<p align="center">
  <img src="docs/images/swagger-master-logo.svg" alt="Swagger Master Logo" width="200"/>
  <br>
  <i>轻量级的单文件 Swagger UI 管理器，支持多个 OpenAPI 规范切换</i>
  <br>
</p>

<p align="center">
  <a href="#功能特点">功能特点</a> •
  <a href="#界面预览">界面预览</a> •
  <a href="#在线演示">在线演示</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#自定义配置">自定义配置</a> •
  <a href="#参与贡献">参与贡献</a> •
  <a href="#开源协议">开源协议</a> •
  <a href="#致谢">致谢</a>
</p>

<p align="center">
  <a href="https://github.com/tobyqin/swagger-master/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/tobyqin/swagger-master" alt="license">
  </a>
  <a href="https://github.com/tobyqin/swagger-master/stargazers">
    <img src="https://img.shields.io/github/stars/tobyqin/swagger-master" alt="stars">
  </a>
  <a href="https://github.com/tobyqin/swagger-master/network/members">
    <img src="https://img.shields.io/github/forks/tobyqin/swagger-master" alt="forks">
  </a>
</p>

<p align="center">
  ⭐️ 如果这个项目对你有帮助，欢迎点个 Star 支持一下！⭐️
</p>

## 功能特点

- 📦 **单文件部署** - 无需构建过程，无需安装依赖
- 🔄 **多 API 支持** - 无缝切换不同的 OpenAPI 规范
- 🚀 **轻松部署** - 可以部署在任何静态文件服务器
- ⚡ **快速加载** - 使用 CDN 加载所有外部资源
- 🎨 **简洁界面** - 直观的 API 选择器界面
- 🔧 **简单配置** - 易于自定义的 API 列表

## 界面预览

<p align="center">
  <img src="docs/images/swagger-master.png" alt="Swagger Master Screenshot" width="800"/>
  <br>
  <i>Swagger Master 运行界面 - 管理多个 API 规范</i>
</p>

## 在线演示

访问我们的[在线演示](https://tobyqin.github.io/swagger-master)来体验 Swagger Master。

## 快速开始

1. 下载 `index.html` 文件
2. 在 `index.html` 文件中的 `API_LIST` 数组中添加你的 API 列表
3. 在浏览器中打开 `index.html` 文件进行测试
4. 部署到任意静态文件服务器即可使用

## 自定义配置

### 样式定制

可以通过 `index.html` 文件中的 CSS 部分自定义界面样式。主要样式类：

- `#api-selector` - API 选择器容器
- `#swagger-ui` - Swagger UI 主容器
- `.info-icon` - 信息图标样式

### 配置选项

API 列表在 `index.html` 文件中配置。`API_LIST` 数组包含 API 规范配置，每个配置项包含以下属性：

```javascript
const API_LIST = [
  {
    name: "Petstore API",
    url: "https://petstore3.swagger.io/api/v3/openapi.json",
    description:
      "这是 Swagger Petstore API，一个用于演示 OpenAPI 规范特性的示例 API。",
    maintainer: {
      name: "Swagger 团队",
      email: "swagger@example.com",
    },
  },
  // 在这里添加更多 API
];
```

每个 API 配置支持：

- `name`: API 的显示名称
- `url`: OpenAPI 规范的 JSON/YAML 文件地址
- `description`: API 的详细描述，包括用途和特性
- `maintainer`: API 维护者的联系信息
  - `name`: 维护者姓名
  - `email`: 维护者邮箱

点击 API 选择器旁边的信息图标（i）可以查看 API 的描述和维护者信息。

## 参与贡献

欢迎提交 Pull Request 来贡献代码。如果要进行重大更改，请先开 Issue 讨论您想要改变的内容。

1. Fork 本项目
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m '添加一些功能'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 开源协议

本项目基于 MIT 协议开源 - 查看 [LICENSE](LICENSE) 文件了解更多详情。

## 致谢

- [Swagger UI](https://github.com/swagger-api/swagger-ui) - 优秀的 API 文档工具
- [Font Awesome](https://fontawesome.com) - 优秀的图标库

---

<p align="center">
  由 <a href="https://github.com/tobyqin">Toby Qin</a> 用 ❤️ 打造
</p>
