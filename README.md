# [班班的小伙伴们](https://blog.dlzhang.com/friends)

所以，要来和班班交换友链吗？

## 基本要求

- 既然是友情链接，自然是优先考虑添加班班眼熟认识的小伙伴们；
- 有 **实质性原创内容** 的网站，对于充斥抄袭、洗稿等内容等网站是不予收录的；
- 网站内容主题不限，但是应当不违背公序良俗和相关法律法规。

## 如何交换友链

如果你认为自己符合上面的要求，那么就欢迎来和班班交换友链啦（参考了[苏卡卡的友链添加方式](https://github.com/SukkaW/Friends)）。

- 将班班的网站添加到自己的友链中：
  - 名称：`醉里挑灯赏猫` 或 `班班碎碎念`，二选一
  - 链接：`https://dlzhang.com` 或 `https://blog.dlzhang.com`，二选一
  - 简介：`班班的碎碎念` 或 `无曰已是 无曰遂真`
    - 你可以自己选择想要展示的文字，也可以不展示
  - Logo 标识
    - https://sdn.geekzu.org/avatar/cc763511474fe24ffcc80257fb7cb970?size=512
    - 你可以自行修改链接中 `size=` 后面的数值来调整 Logo 大小，也可以不展示

- 准备一个自己站点的 Logo（标识）
  - Logo 的要求是中心对称图形，如正方形、圆形、菱形等
  - 长度与宽度应小于 `512px`
  - 使用常见图形文件格式（如 `png`、`jpg`、`svg`、`ico` 等，不包括 `tiff`、`webp`、`icns`）
  - 文件大小应小于 1 MiB
  - **原则上**，应适合在任何网站上展示给任何年龄段的任何人

- 准备需要展示的站点名称，长度应小于 16 个半角字符或 8 个全角字符，否则在展示时可能会被截断

- 在 GitHub 上 Fork 这个仓库
- 在 `src/logo` 文件夹下添加 Logo 图片
  - 文件名格式为 `[domain].[format]`，如 `example.com.png`，`blog.example.com.jpg`
- 按照如下格式将你的网站信息添加到 `src/friendslists.yml` 文件中：
    ```yaml
    - name: 站点名称 # 你的站点名称
      logo: example.com.png # Logo 的文件名
      url: https://example.com # 你的网站链接
    ```

- 完成上述步骤后，请新建一个 Pull Request
- 当 Pull Request 被 Review 并被通过、合并后，你的网站将会尽快显示在 [班班的友链页面](https://blog.dlzhang.com/friends) （这取决于 jsDelivr 更新 CDN 缓存的速度）
- 如果你不会创建 Pull Request，可以在 [GitHub Discussions](https://github.com/lei2rock/Friends/discussions) 或者 [关于更多页面](https://blog.dlzhang.com/more) 留下上述提及的相关网站信息
