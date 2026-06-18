# favimg

一行 URL，一张图标。

```
https://boluo66.top/favimg/?url=xxx
```

## 使用方式

### HTML

```html
<img src="https://boluo66.top/favimg/?url=xxx" alt="icon" />
```

### Markdown

```markdown
![icon](https://boluo66.top/favimg/?url=xxx)
```

### 浏览器

直接打开 `https://boluo66.top/favimg/?url=xxx`，返回该网站的 favicon 图片。

## 支持格式

| 输入 | 说明 |
|---|---|
| `?url=xxx` | 纯域名 |
| `?url=xxx/path` | 带路径 |
| `?url=https://xxx/path?query` | 完整链接 |

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

---

**favimg** — 一行 URL，一张图标。
