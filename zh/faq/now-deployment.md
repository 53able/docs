---
title: 如何使用 Now.sh 进行部署？
description: 如何使用 Now.sh 进行部署？
---

# 如何使用 Now.sh 进行部署？

使用 [now.sh](https://zeit.co/now) 部署，推荐的 `package.json` 配置如下：

```json
{
  "name": "my-app",
  "dependencies": {
    "nuxt": "latest"
  },
  "scripts": {
    "dev": "nuxt",
    "build": "nuxt build",
    "start": "nuxt start"
  }
}
```

运行 `now` 即可完成部署！

提示: 建议将 `.nuxt` 加入到 `.npmignore` 和 `.gitignore` 中去。
