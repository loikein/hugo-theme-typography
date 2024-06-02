# hugo-theme-typography

Upstream: 

- [sumimakito/hexo-theme-typography: Rediscover the beauty of typography.](https://github.com/sumimakito/hexo-theme-typography)
- [lpgph/hugo-theme-typography: hugo theme](https://github.com/lpgph/hugo-theme-typography) \(Demo: [诗和远方](https://lpgph.github.io/)\)

支持 Valine 和 Gitalk, Disqus

## Fork notes

主要是为了让它长得更像原来的主题。本来想自己重新写一遍，写到一半实在懒得了。

- [x] 移除了 Live2D-Widget，APlayer，以及其余的一些原主题没有的部件。
- [x] 增加了 example site。
- [ ] Valine 已经停止更新，考虑换到 [ Waline](https://waline.js.org/en/migration/valine.html)（但其实我也不用）

## Config

### `hugo.toml`

#### Basis

Ref: [Site methods | Hugo](https://gohugo.io/methods/site/)

- `baseURL`: `https://example.com`
- `theme`: `hugo-theme-typography` \(this theme is not Hugo Module ready\)
- `title`: Title of your website
- `copyright`: Can use Markdown

.

- `languageCode`: Enter the [RFC 5646 tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang) for your contents
- `defaultContentLanguage`: No need to set if the site only has one language version. For multilingual sites, see [Multilingual mode | Hugo](https://gohugo.io/content-management/multilingual/#changes-in-hugo-01120)
- `hasCJKLanguage`: Improves word count for CJK languages

.

- `mainSections`: List of folders under `/content/` to be considered as main sections.
- `paginate`: Number of items per page in paginated lists
- `enableEmoji`: `true` to use [emoji shortcuts](https://gohugo.io/quick-reference/emojis/)
- `enableRobotsTXT`: Generates an [allow-all robots.txt](https://gohugo.io/templates/robots/)
- `enableGitInfo`: Use git commit info to generate lastmod info

#### `[Params]`

Ref: [Params | Hugo](https://gohugo.io/methods/site/params/)

TBE.

- `NoIndex`: `true` to prevent showing up in Google SERP (site-wide)
    - DO NOT set `enableRobotsTXT` if you want to use this option
