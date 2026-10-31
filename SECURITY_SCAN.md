# GitHub Pages 公开仓库安全检查

状态：**PASS（仅静态政策包）**；发布状态：**NOT_PUBLISHED**；内容状态：**PUBLISH_READY**。目标远端：wangxiaowen118-cyber/sijichangqing-privacy（尚未创建/推送）。

## 文件（7）

| 文件 | 字节 | SHA256 |
|---|---:|---|
| .nojekyll | 0 | e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 |
| 404.html | 80 | e338192e84f17f5e8f2d656deb26c470b325719b6547a0e7296e5381d6d0b40c |
| deployment-manifest.json | 691 | 70a45a81363f2c98d3a157ca17047143ff08c5461a078d4603531fc9b6e26fca |
| index.html | 12358 | 7da10cf8f713857d644687145d7ede57f9e89045069b3edc0729db65934f303b |
| README.md | 1401 | 7c406c94229be1577adfdb3de2f23942aafd16ecf47ff11a5d0c3554f663bd5f |
| SECURITY_SCAN.json | 1794 | 2d3e23a6afad8e5a343f570581bcc18853c76983900715a3877ce3e56a655479 |
| SECURITY_SCAN.md | 1528 | 7789de17534b877a187173a1afb508d41ee7651643a0745b870641ffa1fad8a7 |

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
- 页面无 JS/iframe/外部资源；公开仓库尚未创建/推送；正式发布仍须本人确认。
