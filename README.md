迁移到 GitHub Actions 免费运行（完全免服务器部署）
如果您想把 VPS 的资源省下来，用 GitHub 的服务器来跑也是极好的选择！GitHub Actions 内置了完整的 Linux 桌面渲染和 Chrome 环境，跑 seleniumbase 简直是天作之合。

第一步：准备 GitHub 仓库与环境变量 (Secrets)
在 GitHub 创建一个新的私有仓库 (Private Repository)（保护好账号密码）。

把您的 aida_renew.py（以及如有需用到的 requirements.txt）上传到仓库根目录。

点击仓库的 Settings -> Secrets and variables -> Actions -> New repository secret。

把您脚本里用到的变量（如 EMAIL, PASSWORD, TG_BOT_TOKEN, TG_CHAT_ID 等）一个个添加进去。
