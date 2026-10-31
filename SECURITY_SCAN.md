# GitHub Pages 公开仓库安全检查

状态：**PASS（仅静态政策包）**；发布状态：**NOT_PUBLISHED**。

## 文件（7）

| 文件 | 字节 | SHA256 |
|---|---:|---|
| `.nojekyll` | 0 | `e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855` |
| `404.html` | 80 | `e338192e84f17f5e8f2d656deb26c470b325719b6547a0e7296e5381d6d0b40c` |
| `deployment-manifest.json` | 542 | `2ce6e62254d7afb49152e6021103bbc6f99bc5325661b23bd29c0806ce1c740e` |
| `index.html` | 11865 | `cc94aef8e6fa0f009a3c446a9febec3bfd4dc8711ba2e29f47eac97b5e299850` |
| `README.md` | 1283 | `591b0d2bc46e01e959f84528132b379a185653f33938858c6891e553468bbda7` |
| `SECURITY_SCAN.json` | 1694 | `5e9b8079a99c2a937964bb900843674d4f10ef97de8948a11034a5c30e2dda83` |
| `SECURITY_SCAN.md` | 1204 | `d15464627e51bf9da5b89a8d54fa590014ff0eebc0915726308aaf8eb4f3e8f3` |

## 检查

- PASS `onlyAllowedFiles`
- PASS `noPrivateKeysOrProviderKeys`
- PASS `noDatabaseUri`
- PASS `noJwtOrPassword`
- PASS `noFirebaseCredential`
- PASS `noActiveContent`
- PASS `noExternalResources`
- PASS `noEmailAddress`

## 结论

- 未包含 App 源码、构建产物、用户数据、日志、JWT、密码、APNs/.p8、Firebase 凭据、数据库 URI 或密钥。
- 页面无 JS/iframe/外部资源/真实邮箱（运营者邮箱仍为待填写）。
- 公开仓库尚未创建/推送；运营者信息补齐并审批后才能发布。
