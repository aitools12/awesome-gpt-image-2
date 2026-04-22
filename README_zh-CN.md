# Awesome GPT Image 2 Dev

[![官网](https://img.shields.io/badge/Website-gpt--image--2.dev-111111)](https://www.gpt-image-2.dev/)
[![作品展示](https://img.shields.io/badge/Showcase-Live-c45b2d)](https://www.gpt-image-2.dev/showcase)
[![定价](https://img.shields.io/badge/Pricing-Official-2a7f62)](https://www.gpt-image-2.dev/pricing)
[![English README](https://img.shields.io/badge/README-English-0a66c2)](README.md)

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome GPT Image 2 Dev banner" width="100%" />
</p>

这是一个面向 [gpt-image-2.dev](https://www.gpt-image-2.dev/) 的公开 GitHub 资料仓库，第一版重点放在三件事上：公开展示图、可复用提示词模板、以及适合 SEO 和品牌曝光的 README 结构。

适合人群：

- 想给网站补一个公开 GitHub 入口的人
- 想沉淀 `GPT Image 2` 提示词素材的人
- 想把官网、showcase、pricing 做成统一资料页的人

## 快速入口

- 官网：https://www.gpt-image-2.dev/
- Showcase：https://www.gpt-image-2.dev/showcase
- Pricing：https://www.gpt-image-2.dev/pricing
- Privacy：https://www.gpt-image-2.dev/privacy-policy
- Terms：https://www.gpt-image-2.dev/terms-of-service
- 已发布落地页：https://aitools12.github.io/How-to-use-gpt-image-2/

## 这个仓库里有什么

- `gpt-image-2.dev` 常见场景提示词模板
- 官网公开展示图的引用示例
- 中英文 README
- 结构化提示词库：[`data/gpt-image-2-dev-prompts.json`](data/gpt-image-2-dev-prompts.json)

## 展示图快照

下面这些图片引用的是当前 `gpt-image-2.dev` 公开可访问资源。

| 场景 | 预览 | 说明 |
| --- | --- | --- |
| 文生图 | <img src="https://www.gpt-image-2.dev/_next/image?url=%2Fimgs%2Fcase%2F1.webp&w=1920&q=75" width="220" alt="GPT Image 2 文生图示例" /> | 适合快速出第一版视觉 |
| 图像编辑 | <img src="https://www.gpt-image-2.dev/_next/image?url=%2Fimgs%2Fcase%2F2.webp&w=1920&q=75" width="220" alt="GPT Image 2 编辑示例" /> | 上传原图后二次修改 |
| 参考图重混 | <img src="https://www.gpt-image-2.dev/_next/image?url=%2Fimgs%2Fcase%2F3.webp&w=1920&q=75" width="220" alt="GPT Image 2 参考图重混示例" /> | 保留风格信号重新生成 |
| 电商产品图 | <img src="https://www.gpt-image-2.dev/_next/image?url=%2Fimgs%2Fpopularcases%2F1.png&w=1920&q=75" width="220" alt="GPT Image 2 电商产品图示例" /> | 适合 listing 和 hero banner |
| 概念视觉 | <img src="https://www.gpt-image-2.dev/_next/image?url=%2Fimgs%2Fpopularcases%2F4.webp&w=1920&q=75" width="220" alt="GPT Image 2 概念图示例" /> | 适合风格探索 |
| 系列一致性 | <img src="https://www.gpt-image-2.dev/_next/image?url=%2Fimgs%2Fpopularcases%2F6.png&w=1920&q=75" width="220" alt="GPT Image 2 系列一致性示例" /> | 适合头像组图和变体扩展 |

## 提示词分类

- 产品营销图
- 社媒广告图
- 人像和头像
- 参考图风格迁移
- 修图和清理
- 品牌视觉和排版
- 电商主图和广告素材
- UI 概念和 moodboard

## 精选提示词

### 1. 高级产品主视觉

```text
Premium skincare bottle on a warm travertine pedestal, soft daylight from the left, subtle shadow falloff, realistic glass reflections, clean luxury branding, editorial product photography, shallow depth of field, e-commerce hero shot, 4:5 crop
```

### 2. 背景替换修图

```text
Replace the current background with a bright minimal studio setup, keep the product shape and label readable, preserve realistic shadows under the object, remove clutter, improve contrast, polished commercial retouch style
```

### 3. 社媒活动图

```text
Create a square social media campaign visual for a summer launch, bold central product, clean headline area at the top, supporting decorative elements in brand colors, premium but simple layout, realistic lighting, ad-ready composition
```

### 4. 参考图时尚重混

```text
Using the uploaded reference as the lighting and styling guide, create a new editorial portrait with the same atmosphere, keep the image realistic, preserve a soft cinematic color palette, luxury magazine look, 3:4 vertical
```

### 5. 电商白底主图清理

```text
Convert this product image into a clean marketplace-ready listing image, white background, accurate colors, centered composition, crisp edges, realistic contact shadow, no extra props, no watermark, export-ready
```

## 完整提示词库

完整 starter prompt 集合见：

- [`data/gpt-image-2-dev-prompts.json`](data/gpt-image-2-dev-prompts.json)

当前包含 24 条模板，带分类、使用场景、推荐比例和 prompt 正文，后续可以继续往里加。

## 以后给别的网站复用时怎么做

这个仓库可以直接当模板：

1. 改 repo 名和 banner
2. 改官方链接和 showcase 图
3. 改 `data/*.json` 里的 prompt 集合
4. 同步改中英文 README
5. push 到 `aitools12` 即可

## 说明

- 这个仓库是围绕 `gpt-image-2.dev` 搭建的公开资料层，不是产品后台代码仓库。
- 这里的图片是公开资源引用，如果官网路径变化，需要同步更新。
- 第一版没有加视频素材，因为当前公开站点以图片展示为主。

## License

[MIT](LICENSE)
