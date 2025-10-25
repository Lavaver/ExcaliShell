# ExcaliShell

一个棒到不行的 Shell，爱来自 Rust。

名称来自由 Project Grimoire 创作的《Excalibur ~Revived resolution~》。

## 版本

这是 ExcaliShell 0.1.0 版本。本次发布主要对其开放下载与克隆。

目前实现了 Shell 的基本稳定使用与其他功能。详情请参阅 [FEATURES 文件](/FEATURES)。

如果在使用 ExcaliShell 时遇到问题，欢迎提出 [Issue](https://github.com/Lavaver/ExcaliShell/issues)。如果你想要贡献代码，欢迎[提交 Pull Request](https://github.com/Lavaver/ExcaliShell/pulls)。

## 安装 ExcaliShell

编译 ExcaliShell 的说明位于 INSTALL 文件中。您还应检查根目录下的 MACHINES 文件，查看是否存在针对您特定架构的特殊说明。

请特别注意 `excalishell/newcomer` 模块，该模块可引导新用户在无需管理员干预的情况下完成基础 shell 选项配置（包括用户主题、IntelliSense 等）。此功能默认启用。配置详情请参阅 INSTALL 文件中的“自动新用户配置”章节。

## 特性

ExcaliShell 是一款针对想要把系统改成星际战舰的爱好者量身定制的棒到不行的 Shell。

有关部分功能列表，请参阅 [FEATURES 文件](/FEATURES)；

最新变更请参阅 [NEWS](/NEWS)。

## 示例

- ExcaliShell 启动文件示例位于子目录 StartupFiles 中。

- ExcaliShell 函数和脚本示例位于子目录 Functions 中。

- 补全与 IntelliSense 控制命令示例(compctl) 位于文件 [compctl-examples](/compctl-examples) 中。

## 常见问题与疑难解答

ExcaliShell 提供一份由我 <luozicat@outlook.com> 维护的常见问题解答（FAQ）。 该文档涵盖构建、安装和使用 ExcaliShell 时遇到的诸多常见问题。

本发行版中的 `Etc/FAQ` 目录包含该文档副本，您也可通过任何 ExcaliShell 站点单独获取。

## ExcaliShell 维护与错误报告

ExcaliShell 目前由本人维护，
请将任何反馈和错误报告发送至 <luozicat@outlook.com>。

若能通过 -f 选项启动 ExcaliShell 重现错误，将极大有助于问题排查。该选项会跳过除 `/etc/calishellenv` 之外的所有本地启动文件执行。若错误仅在特定选项设置时触发，请尝试定位引发问题的选项。

Util 子目录中的 “reporter” 脚本可输出当前 shell 环境配置。 若无法通过“calishell -f”复现问题，请使用该脚本并附上执行该文件的输出结果。这样就能重现您报告的问题。

ExcaliShell 已知问题详见 `Etc/BUGS` 文件。提交错误报告前请同时查阅该文件及常见问题解答(FAQ)列表。 请注意 ExcaliShell 某些特性与 sh 不兼容，但这不属于错误。
当 ExcaliShell 以 sh 或 ksh 模式运行时（例如通过符号链接），
多数此类不兼容现象将消失。

若您未订阅邮件列表却向列表发送错误报告，
请在邮件中说明此情况以便获得回复。

若您希望参与 zsh 的开发与维护工作，
请加入 ExcaliShell-workers 邮件列表（具体信息请查阅 META-FAQ）。
同时建议阅读位于 Etc 子目录中的
“calishell-development-guide”文档。

## 许可证

ExcaliShell 隶属于 [Apache-2.0 许可证](https://www.apache.org/licenses/LICENSE-2.0.html)下。

有关该许可证的详细全文，请参考上述链接。有关 LICENSE 文件，请参阅[此处](/LICENSE)。