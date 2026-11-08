# 跨境宝钱包 · PC 端交互原型

V1.4：账户余额、我的费率与可采购额度合并展示，四个资金操作入口为转入、转出、提现、汇兑。支付管理分为「支付顺序与授权」和「1688 账号管理」两个 Tab；支持新增账号授权、详情查看、解除和重新授权。

- 在线原型：https://1737990786-coder.github.io/crossborder-wallet-qingkai/
- 用户动线：https://1737990786-coder.github.io/crossborder-wallet-qingkai/wireflow.html

全部账户、金额、费率与交易均为演示数据，浏览器本地保存模拟状态，未接入真实资金系统。点击“重置”恢复默认数据。

静态部署入口为 index.html，GitHub Pages 从 main 分支根目录发布。

支付顺序与授权采用单栏展示；1688 账号列表通过「详情」统一进入账号信息、解除授权或重新授权。
