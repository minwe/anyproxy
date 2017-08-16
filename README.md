dora-openproxy
==========

[![NPM version][npm-image]][npm-url] [![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/dora-openproxy.svg?style=flat-square
[npm-url]: https://npmjs.org/package/dora-openproxy
[download-image]: https://img.shields.io/npm/dm/dora-openproxy.svg?style=flat-square
[download-url]: https://npmjs.org/package/dora-openproxy

为 [dora-plugin-openproxy](https://github.com/minwe/dora-plugin-openproxy) 服务，是在 [anyproxy](https://github.com/alibaba/anyproxy) 基础上做的简化版。

----

调整功能如下：

- 删除 web GUI
- 配合 dora-plugin-openproxy 整理日志信息，[dora-plugin-proxy#3](https://github.com/dora-js/dora-plugin-proxy/issues/3)
- 添加检查是否已经信任证书 API (暂时只限 mac 系统)
- 提示输入 sudo 密码后，自动信任证书 (暂时只限 mac 系统)
- **支持多开（需要指定不同的端口）**（https://github.com/dora-js/dora/issues/101）
