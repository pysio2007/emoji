# Pysio 表情包集合

<div align="center">

[![Netlify Status](https://api.netlify.com/api/v1/badges/e243fc1d-1288-434a-ab58-15ff156b6d5b/deploy-status)](https://app.netlify.com/sites/pysio-emoji/deploys)
[![GitHub release](https://img.shields.io/github/v/release/pysio2007/emoji)](https://github.com/pysio2007/emoji/releases)
[![License](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-blue)](LICENSE)
![Waline Compatible](https://img.shields.io/badge/Waline-Compatible-brightgreen)
![Artalk Compatible](https://img.shields.io/badge/Artalk-Compatible-orange)

**可爱的 Pysio 表情包集合，适用于 Waline、Artalk 评论系统和其他场景**

[🌐 在线预览](https://emoji.pysio.online) | [📦 下载](https://github.com/pysio2007/emoji/releases) | [📝 使用文档](#使用方法) | [🔗 CDN](#cdn-访问)

</div>

## ✨ 特性

- 🌈 精美可爱的表情包设计
- 🚀 多种 CDN 加速选项（国际/国内）
- 💻 完美兼容 Waline 和 Artalk 评论系统
- 📱 响应式设计，适配各种设备
- 🔄 持续更新的表情包集合
- 📊 提供多种格式的配置文件

## 📋 仓库信息

- **仓库地址**: [pysio2007/emoji](https://github.com/pysio2007/emoji)
- **当前版本**: v1.4
- **部署状态**: [![Netlify Status](https://api.netlify.com/api/v1/badges/e243fc1d-1288-434a-ab58-15ff156b6d5b/deploy-status)](https://app.netlify.com/sites/pysio-emoji/deploys)

## 🚀 CDN 访问

您可以通过以下 CDN 地址访问表情包:

### 🌍 国际 CDN (jsDelivr)

```
https://cdn.jsdelivr.net/gh/pysio2007/emoji@v1.4/
```

例如，访问 Chibi 系列的 hi 表情:

```
https://cdn.jsdelivr.net/gh/pysio2007/emoji@v1.4/Chibi/pysio_chibi_hi.webp
```

### 🇨🇳 国内 CDN

```
https://emoji.pysio.online/
```

例如，访问 Chibi 系列的 hi 表情:

```
https://emoji.pysio.online/Chibi/pysio_chibi_hi.webp
```

## 💬 使用方法

### 在 Waline 中使用

在 Waline 的配置中添加以下代码：

```js
emoji: [
  '//cdn.jsdelivr.net/gh/pysio2007/emoji@v1.4/Chibi',
  // 或者使用国内CDN
  // '//emoji.pysio.online/Chibi',
],
```

### 在 Artalk 中使用

在 Artalk 的配置中添加以下代码：

#### 🌍 国际版 (jsDelivr CDN)

```js
Artalk.init({
  // ... 其他配置 ...
  emoticons: 'https://cdn.jsdelivr.net/gh/pysio2007/emoji@v1.4/Chibi/artalk.json',
});
```

#### 🇨🇳 中国版

```js
Artalk.init({
  // ... 其他配置 ...
  emoticons: 'https://emoji.pysio.online/Chibi/artalk_cn.json',
});
```

### 配置文件说明

本项目提供了多种格式的配置文件，以适应不同的使用场景：

- **artalk.json** - 使用 jsDelivr CDN 的标准配置
- **artalk_cn.json** - 使用中国 CDN (emoji.pysio.online) 的配置

## 📦 表情包预览

<table>
  <tr>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_hi.webp" width="100" /><br>hi</td>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_love.webp" width="100" /><br>love</td>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_laugh.webp" width="100" /><br>laugh</td>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_crying.webp" width="100" /><br>crying</td>
  </tr>
  <tr>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_cool.webp" width="100" /><br>cool</td>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_angry.webp" width="100" /><br>angry</td>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_question.webp" width="100" /><br>question</td>
    <td align="center"><img src="https://emoji.pysio.online/Chibi/pysio_chibi_wow.webp" width="100" /><br>wow</td>
  </tr>
</table>

更多表情包请访问 [在线预览站点](https://emoji.pysio.online)。

## 📜 许可说明

本仓库中的所有表情包均采用 [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](LICENSE) 进行授权。

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

这意味着您可以：
- ✅ **分享** - 复制和重新分发这些表情包
- ✅ **改编** - 修改、转换和创建基于这些表情包的新作品

但必须遵循以下条件：
- ⚠️ **署名** - 您必须给出适当的署名
- ⚠️ **非商业性使用** - 不得将这些表情包用于商业目的
- ⚠️ **相同方式共享** - 如果您改编这些表情包，您必须以相同的许可条款分发您的作品

## 📝 表情包说明

目前收录的表情包均为 Pysio 的新人设系列，包含多种可爱表情。这些表情包适合在日常社交媒体、即时通讯软件中使用。

## ⚠️ 使用提醒

- 请勿将这些表情包用于商业用途
- 在分享或改编时请保留版权信息
- 建议在使用时注明来源


## 📞 联系方式

如有任何问题或建议，欢迎通过以下方式联系：

- 提交 [Issue](https://github.com/pysio2007/emoji/issues)
- 发送邮件至 [team@pysio.online](team@pysio.online)

---

<div align="center">

© 2025 Pysio 表情包集合

Made with ❤️ by [pysio2007](https://github.com/pysio2007)

</div>
