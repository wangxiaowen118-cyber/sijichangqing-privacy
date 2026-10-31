# GitHub Pages 公开仓库安全检查

状态：**PASS（仅静态政策包）**；发布状态：**PUBLISHED**。

公开 URL：https://wangxiaowen118-cyber.github.io/sijichangqing-privacy/

## 文件（7）

| 文件 | 字节 | SHA256 |
|---|---:|---|
| .nojekyll | 0 | e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 |
| 404.html | 80 | e338192e84f17f5e8f2d656deb26c470b325719b6547a0e7296e5381d6d0b40c |
| deployment-manifest.json | 691 | ea8e66c54d1fa1f42c8e05024edbfdd3cc7acd691d85c20f30b5d1c72121211f |
| index.html | 13153 | fd716a094d4df1f8e0cd13280e68e527677262ecd1b93bcb4d8eebefe0a8ed73 |
| README.md | 1335 | 791daecb3395bdf9629b5651e91e5ef61143128a50b851e62b262ad99b742937 |
| SECURITY_SCAN.json | 1794 | 867bdc48bf9b19dd6dfac5e57a45da6e763f787bf0946786a6fae0733d6712e7 |
| SECURITY_SCAN.md | 1577 | 4326e8a2042b161ec24cd27bbd6ce0c0da30f0bf7d08ea1373f114ca84610a23 |

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
- 页面无 JS/iframe/外部资源；政策已按实际功能修正。
