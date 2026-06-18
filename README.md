# favimg

一键获取任意网站的高清 favicon 图标。

```
https://boluo66.top/favimg/?url=github.com
```

![favimg](https://boluo66.top/favimg/?url=boluo66.top)

## 使用方式

### HTML

```html
<img src="https://boluo66.top/favimg/?url=github.com" alt="GitHub" />
```

### Markdown

```markdown
![GitHub](https://boluo66.top/favimg/?url=github.com)
```

### 浏览器

直接打开 `https://boluo66.top/favimg/?url=任意网站`，返回该网站的 favicon 图片。

## 支持格式

| 输入 | 说明 |
|---|---|
| `?url=github.com` | 纯域名 |
| `?url=blog.csdn.net/cxy_wjq` | 带路径 |
| `?url=https://blog.csdn.net/cxy_wjq?spm=...` | 完整链接 |

不管粘贴什么格式的 URL，自动提取域名获取图标。

## 响应

- `Content-Type` 自动识别（SVG / PNG / ICO / WebP）
- `X-Favicon-Source` 标注图标来源 URL
- `Cache-Control: max-age=3600` 1 小时缓存
- `Access-Control-Allow-Origin: *` 跨域支持

## 更多工具

| 工具 | 说明 |
|---|---|
| [favimg](https://github.com/VeteranBoLuo/favimg) | 网站图标获取 |
| git-heat | Git 年度热力图 · 即将推出 |
| qr | 终端二维码 · 即将推出 |

---

**favimg** — 一行 URL，一张图标。
