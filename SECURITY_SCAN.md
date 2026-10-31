# GitHub Pages 公开仓库安全检查

状态：**PASS（仅静态政策包）**；发布状态：**NOT_PUBLISHED**。目标远端：wangxiaowen118-cyber/sijichangqing-privacy（尚未创建/推送）。

## 文件（7）

| 文件 | 字节 | SHA256 |
|---|---:|---|
| .nojekyll | 0 | e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 |
| 404.html | 80 | e338192e84f17f5e8f2d656deb26c470b325719b6547a0e7296e5381d6d0b40c |
| deployment-manifest.json | 692 | b241f622d0bf2f0c147f88490e0a27f944f52396b3806b0e5be0504fc471a3ab |
| index.html | 12483 | 3335c27106fed07702f9d326fc7376298c45103bb15a57fc936320acbdd6d684 |
| README.md | 1401 | 7c406c94229be1577adfdb3de2f23942aafd16ecf47ff11a5d0c3554f663bd5f |
| SECURITY_SCAN.json | 1704 | 99325b205f7543078b717183e02665ba402e830791b9ea71330e98cbaa89b601 |
| SECURITY_SCAN.md | 1500 | 072b6cd79242aed743f8d7d13c97f3ba481498529aa0971d6c32dd9bfde70cb5 |

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
