项目为substate-kitty的前端显示项目，可以在前端create kitty，transfer kitty，以及给kitty设定价格。

**步骤如下：**

1. 下载substrate端代码：https://github.com/ChenYunShu-01/substrate-kitty，
2. 进入substrate-kitty目录，cd substate-kitty，
2. 执行编译命令：cargo build --release，
3. 编译完成后运行命令：./target/release/node-kitties --dev --tmp 启动本地实例，
4. 进入本项目目录 cd substrate-kitty-front-end
5. 运行yarn install，
6. 运行yarn start，启动前端页面会连接本地实例，可在页面执行创建，转让kitty以及给kitty设置价格等操作
