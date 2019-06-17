# Static Getting Started

在 LeanCloud 云引擎上托管静态网站的示例项目。

## 本地运行

由于该项目是纯静态项目，因此无法通过 `lean up` 本地运行。
不过，你可以使用任何 http 本地服务器查看效果。

例如，假定系统中已预装 Python 3：

```sh
python3 -m http.server
```

如果需要自动重新加载功能，可以试下 [live-server]。

[live-server]: https://github.com/tapio/live-server

很多 IDE 或编辑器也提供类似功能。

## 部署到云引擎

部署到预备环境（若无预备环境则直接部署到生产环境）：

```sh
lean deploy
```

## 相关文档

* [云引擎网站托管开发指南](https://leancloud.cn/docs/leanengine_webhosting_guide-node.html)
* [云引擎命令行工具使用指南](https://leancloud.cn/docs/leanengine_cli.html)
* [云引擎常见问题和解答](https://leancloud.cn/docs/leanengine_faq.html)