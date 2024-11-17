# Long Teng 主题配置指南

## 简介

**Lóng Téng**，意为“腾飞的龙”，是一个象征着成长、创新和力量的主题。  
它专为创建引人注目的产品发布页面而设计，能够以优雅和清晰的方式展示您的产品。  
从突出产品特性到讲述产品故事，这个主题为现代且具有前瞻性的创作者量身定制。

## 配置文件示例

```yaml
---
friday-plugin: enabled
site: '1'
theme: github.com/mdfriday/theme-long-teng
content: MDFriday/theme-long-teng/content
---
```

## 配置项说明

### 1. **friday-plugin**
- **描述**：表示 MDFriday 插件的启用状态。
- **默认值**：`enabled`
- **说明**：保持此项为 `enabled` 即可，无需修改。该字段是 MDFriday 插件的标志，确保插件正常工作。

### 2. **site**
- **描述**：站点 ID。
- **默认值**：`'47'`（由插件自动生成）
- **说明**：此字段由 MDFriday 插件自动生成，表示您的站点 ID。建议不要更改。

### 3. **theme**
- **描述**：主题的 GitHub 地址。
- **默认值**：`github.com/mdfriday/theme-long-teng`
- **说明**：此项指定使用的 Hugo 主题的 GitHub 地址。您可以根据需要更换为其他主题的地址。如果您使用的是 Long Teng 主题，保持此值不变。

### 4. **content**
- **描述**：内容文件夹路径。
- **默认值**：`MDFriday/theme-long-teng/content`
- **说明**：此项定义了主题内容文件夹的位置。初始时，`content` 字段值为`empty`，插件会在用户下载样例文件后自动更新为相对路径。


## 使用建议
- 如果您希望使用其他 Hugo 主题，直接在 `theme` 字段中填写新的主题地址即可。
- 内容目录 `content` 在下载样例文件后会自动更新，无需手动更改。但如果您想指向其它的文件位置，记得更新此路径。

---

通过正确配置上述字段，您将能够顺利启用 Long Teng 主题并展示内容。
如果有任何疑问或需要更多帮助，请访问MDFriday官网主题介绍页面：[theme-long-teng](https://themes.mdfriday.com/theme-long-teng)。
