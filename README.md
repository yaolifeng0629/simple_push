# Simple Push

-   Simple Push 是一个使用 Node.js 编写的命令行工具，它可以简化和自动化你的 git 提交过程。

## 功能

-   自动检测当前目录是否是一个 git 仓库
-   如果是 git 仓库，会提示你输入提交消息
-   自动执行`git add .`，`git commit -m "<message>"`和`git push`命令

## 使用方法

1. 克隆或下载此仓库到本地
2. 在命令行中导航到此仓库的目录
3. 运行`node index.js`
4. 当提示输入提交消息时，输入你的提交消息，然后按回车键

## 注意事项

-   确保你的机器上已经安装了 Node.js 和 git
-   确保你已经在 git 仓库中配置了正确的远程仓库

## 许可证

-   此项目遵循 MIT 许可证。有关详细信息，请参阅[LICENSE](LICENSE)文件。
