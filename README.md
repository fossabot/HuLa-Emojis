---
Author: 目棃
Description: Hula-Emojis说明文档
Date: 2024-12-10
Update: 2024-12-11
---

> 本文档 [`Frontmatter`](https://github.com/BTMuli/MuCli#Frontmatter) 由 [MuCli](https://github.com/BTMuli/Mucli) 自动生成于 `2024-12-10 09:45:22`
>
> 更新于 `2024-12-11 14:28:56`

# HuLa-Emojis
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FHuLaSpark%2FHuLa-Emojis.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FHuLaSpark%2FHuLa-Emojis?ref=badge_shield)


HuLa 表情包的 Monorepo 仓库，负责管理/打包/发布 HuLa 表情包。

Work in progress...

## 参考

- [Vuetify](https://github.com/vuetifyjs/vuetify)：借鉴其Monorepo目录结构
- [Gitmoji](https://github.com/patou/gitmoji-intellij-plugin/)：提交信息类型
- [bangumi-data](https://github.com/bangumi-data/bangumi-data)：打包发布流程

## 使用

```shell
pnpm i hula-emojis
```

```typescript
import HulaEmojis from "hula-emojis";

const emojisBbs = HulaEmojis.MihoyoBbs;
```

## License

项目遵循 [MIT License](./LICENSE.md) 开源协议。


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FHuLaSpark%2FHuLa-Emojis.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FHuLaSpark%2FHuLa-Emojis?ref=badge_large)