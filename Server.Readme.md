## 如何使用这些东西完成后端？

### 材料

- `MySQL` 及 `SQL Editor`
- `Node.js`

### 步骤

1. 将 `server` 文件夹加入到你的构建项目中 ( 简简单单的移入你的项目就好 )
1. 在你的项目中重新检查并安装你的项目依赖文件
    2.1. 如果你尝试了上一步却还是缺少依赖文件，请手动安装 `Express` 及 `MySQL` 组件
1. 将 `SQL` 文件 ( `user.sql` ) 文件里的内容提交到你的某一个合适的数据库中，检查表的数据是否插入正确。或者，显然也可以手动添加自定义的数据用例，前提是符合数据库的语法规则
1. 确定数据方面没有问题后，编辑 `db.js` 文件，将其中的空值：例如用户名密码或是数据库名称全部补全
1. 使用任意命令行工具进入到 `./server/` 文件夹下，使用 `Node.js` 运行 `index.js` 脚本文件 , 即 `$ node index.js`
1. 完成，你的后端将会被部署在 6000 端口
