# Static Getting Started

在 LeanCloud 云引擎上托管静态网站的示例项目。

## 本地运行

```sh
lean up
```

## 部署到云引擎

部署到预备环境（若无预备环境则直接部署到生产环境）：

```sh
lean deploy
```

## 路由

```
a.html -> /a
```

## 自定义邮件验证、重置密码页面

根据 `verify-template.html` 和 `reset-template.html` 中的注释用你的应用的自定义 API 域名替换 `api.example.com`，
再将这两个文件改名为 `verify.html` 和 `reset.html`，并部署到云引擎上。
然后在「控制台 > 设置 > 邮件模板」中的自定义邮件验证页面、自定义重置密码页面的 url 分别设为 `https://www.example.com/verify` 和 `https://www.example.com/reset` 即可。

## 相关文档

* [云引擎网站托管开发指南](https://leancloud.cn/docs/leanengine_webhosting_guide-node.html)
* [云引擎命令行工具使用指南](https://leancloud.cn/docs/leanengine_cli.html)
* [云引擎常见问题和解答](https://leancloud.cn/docs/leanengine_faq.html)