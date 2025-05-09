# subweb for Vercel
## Vercel 快速部署

1. 登录 Vercel 创建新的 Project, 选择你的 subweb 仓库.
2. 根据需求设置 Environment Variables, 参考`.env`文件.
3. 点击 deploy 开始部署，立即点击右下角 Cancel Deployment 取消部署。
4. 回到 Vercel 项目 Settings - General - Node.js Version 设置为`16.x` - Save 保存.
5. 回到 Vercel 项目 Deployments - 过滤下拉菜单 Status 中勾选 Cancelled - 将显示的刚才取消的部署记录, 进行 Redeploy 重新部署.
6. 如有更多修改或不想使用环境变量的方式进行设置,请自行修改`public/conf/config.js`文件.

