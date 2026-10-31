# GitHub Pages 公开仓库安全检查

状态：**PASS（仅静态政策包）**；发布状态：**NOT_PUBLISHED**。目标远端：wangxiaowen118-cyber/sijichangqing-privacy（尚未创建/推送）。

## 文件（7）

| 文件 | 字节 | SHA256 |
|---|---:|---|
| .nojekyll | 0 | e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 |
| 404.html | 80 | e338192e84f17f5e8f2d656deb26c470b325719b6547a0e7296e5381d6d0b40c |
| deployment-manifest.json | 692 | 27f8ecc88ca10a4bab9d076d6e23bd8f29b82ae0253445a6bf2bd90e7bdda514 |
| index.html | 12501 | 1ef071d32d3f85e338c59143f9775eec7411b6b1ae81da3ff80b79c8d4b7468e |
| README.md | 1401 | 7c406c94229be1577adfdb3de2f23942aafd16ecf47ff11a5d0c3554f663bd5f |
| SECURITY_SCAN.json | 1794 | ecc77f7543d775762a5f2be1e029968bc0b30e04cfca4725f88342dc980f289c |
| SECURITY_SCAN.md | 1528 | 1c9a8d1ae88964a5300ff4649275772f0ee2689c9562fe723d61d87d3f2ff950 |

## 检查

- PASS onlyAllowedFiles
- PASS noPrivateKeysOrProviderKeys
- PASS noDatabaseUri
- PASS noJwtOrPassword
- PASS noFirebaseCredential
- PASS noActiveContent
- PASS noExternalResources
- PASS onlyAuthorizedPrivacyEmail

## 结论

- 仅包含隐私政策静态文件；允许的隐私联系邮箱为 hhw19830209@hotmail.com，其他邮箱会使扫描失败。
- 未包含 App 源码、构建产物、用户数据、日志、JWT、密码、APNs/.p8、Firebase 凭据、数据库 URI 或密钥。
- 页面无 JS/iframe/外部资源；公开仓库尚未创建/推送；内容与发布授权仍需本人确认。
