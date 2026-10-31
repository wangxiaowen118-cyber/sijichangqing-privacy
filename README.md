# 四季常青公开隐私政策（GitHub Pages 隔离仓库）

本仓库只允许存放：

- 已审批的 `index.html`（静态隐私政策）
- `.nojekyll`
- `404.html`
- 本 README / 部署清单

**禁止**放入 App 源码、构建产物、用户数据、日志、JWT、密码、APNs `.p8`、Firebase 凭据、生产配置或任何密钥。

## 发布前

1. 运营者法定名称、注册地址、隐私联系邮箱、个人信息保护负责人已补齐并经用户确认；
2. `privacy-policy.md` 与 `site/index.html` 已同步；
3. 页面不再包含 “发布前阻断项 / 尚未提供 / [待填写]”；
4. 本地静态校验、移动端 390×844 检查、内容完整性检查通过；
5. 用户单独批准公开发布。

## GitHub Pages

- 新建**独立公开仓库**（例如 `sijichangqing-privacy`），只提交上述静态文件；
- Settings → Pages → Deploy from a branch → `main` / root；
- 开启 Enforce HTTPS；
- 记录真实 URL（形如 `https://<owner>.github.io/<repo>/`）；
- 该 URL 必须实际可访问且返回政策正文，才能填入 App Store Connect。

## 禁止

- 不得把本页面的草案状态直接公开；
- 不得编造 GitHub Pages URL；
- 不得把公开仓库链接到 App 源码仓库或生产域名配置。
