# GitHub Pages 公开仓库安全检查

状态：**PASS（仅静态政策包）**；发布状态：**NOT_PUBLISHED**；内容状态：**PUBLISH_READY**。目标远端：wangxiaowen118-cyber/sijichangqing-privacy（当前不存在/未推送）。

## 文件（7）

| 文件 | 字节 | SHA256 |
|---|---:|---|
| .nojekyll | 0 | e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 |
| 404.html | 80 | e338192e84f17f5e8f2d656deb26c470b325719b6547a0e7296e5381d6d0b40c |
| deployment-manifest.json | 691 | b631358e87f932f349c96647f8d4ca23d450c651daf157453c73554b7241fc4a |
| index.html | 12358 | 7da10cf8f713857d644687145d7ede57f9e89045069b3edc0729db65934f303b |
| README.md | 1353 | 99c4f73ce3816bf835188acd0cfa049a72459eb743623630b6d1ed743ef7f38b |
| SECURITY_SCAN.json | 1794 | a9a49d9f00f31265788b856160b2394c133912115416af69dd03f6c803cbdec3 |
| SECURITY_SCAN.md | 1554 | c65baea0d8e1ca9ae00479d3c759cabb557c4cb85ba871a0f107dc9b484c977a |

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
