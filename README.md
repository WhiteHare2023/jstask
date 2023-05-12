Solidity Task Publishing Platform
这是一个基于Solidity编写的任务发布平台。用户可以发布任务，其他用户可以接受并完成这些任务，以获得奖励。该平台使用web3.js和Node.js来实现接口。

项目功能
用户注册和登录：用户可以在平台上注册账户并登录。

任务发布：注册用户可以发布任务，包括任务描述和任务奖励。

接受任务：其他用户可以接受已发布的任务。

提交任务：完成任务的用户可以提交任务以供发布者确认。

确认任务：任务发布者可以确认任务的完成情况，并给出评价。

技术栈
Solidity：用于编写智能合约，实现任务发布、接收、提交和确认等核心功能。
web3.js：用于与以太坊区块链进行交互。
Node.js：用于实现后端服务器和接口。
如何运行
首先，确保你的系统已经安装了Node.js和npm。然后，按照以下步骤操作：

克隆这个仓库到你的本地机器上。
```bash
git clone https://github.com/WhiteHare2023/jstask.git
```
进入项目目录。

```bash
cd jstask
```
安装依赖。
```bash
npm install
```
运行项目。
```bash
npm start
```
现在，你应该可以在浏览器中访问 http://localhost:9090 来查看项目。
