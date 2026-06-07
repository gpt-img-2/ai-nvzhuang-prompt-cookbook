# AI 女装提示词库常见问题

这里整理“AI 女装提示词库”的常见写法、失败原因和修改方向，方便快速判断该用哪类提示词。

## 更多示例

如果你想直接测试提示词，或继续找更多同类服装案例，可以打开下面入口。

- 浏览完整示例：https://gptimg2.art/zh/prompts/gpt-image-2/category/womens-fashion?utm_source=github&utm_medium=repo&utm_campaign=fashion_prompt_cookbook&utm_content=womenswear
- 查看提示词库：https://gptimg2.art/zh/prompts/ai-nvzhuang-tishici?utm_source=github&utm_medium=repo&utm_campaign=fashion_prompt_cookbook&utm_content=womenswear
- 打开图片生成器：https://gptimg2.art/zh/ai-image?utm_source=github&utm_medium=repo&utm_campaign=fashion_prompt_cookbook&utm_content=womenswear

## AI 女装提示词怎么写？

先不要只写“好看”或“高级感”。更稳的结构是：主体 + 款式 + 颜色 + 面料 + 版型 + 场景 + 画幅 + 失败规避。可以先从 [精选可复制版](../prompts/featured-prompts.md) 选一条，再替换成自己的商品信息。

## AI 女装提示词适合哪些场景？

适合女装店主和电商运营、淘宝、天猫、拼多多女装商家、小红书穿搭博主和内容团队、服装设计师、搭配师和 AI 修图接单者。如果你还不确定从哪里开始，优先看 [女装店对镜自拍提示词](../prompts/womenswear-mirror-selfie.md) 和 [淘宝女装主图提示词](../prompts/womenswear-taobao-main-image.md)。

## 如何让服装细节更清楚？

提示词里要明确写出领口、袖型、腰线、下摆、裤线、面料纹理、自然褶皱和服装完整可见。电商图还要补充“不要被手、包、头发或道具遮挡”。

## 淘宝主图和小红书穿搭提示词有什么区别？

淘宝主图更重视商品完整、背景简洁、卖点清楚和平台尺寸；小红书穿搭更重视生活感、姿势自然、场景真实和封面点击率。不要把同一条提示词无差别用于两个平台。

## 为什么生成的图像像写真，不像卖货图？

通常是因为提示词过度描述人物颜值、氛围和摄影风格，反而没有锁定服装主体。把重点改成服装款式、面料、版型、上身效果和平台用途，出图会更接近商业素材。

## 使用参考图时怎么避免跑偏？

先写“保持人物身份、姿势、背景光线和服装结构”，再写“只替换颜色、面料或款式”。如果是商品图，建议额外写“不要改变服装廓形、领口、袖口、纽扣和图案位置”。

## 可以批量改款式、颜色和面料吗？

可以。把精选提示词中的变量统一成表格字段，例如款式、颜色、面料、版型、场景、画幅，然后批量替换。全量数据可以从 [`data/prompts.zh.json`](../data/prompts.zh.json) 读取。

## 生成图里出现乱码文字或假 logo 怎么办？

在提示词末尾加上“不要随机品牌 logo、水印、乱码文字、不可读小字或未授权品牌标识”。需要真实文字时，尽量减少字数并单独说明文字内容。

## 下一步去哪里？

- 继续看同类提示词：https://gptimg2.art/zh/prompts/ai-nvzhuang-tishici?utm_source=github&utm_medium=repo&utm_campaign=fashion_prompt_cookbook&utm_content=womenswear
- 直接生成图片：https://gptimg2.art/zh/ai-image?utm_source=github&utm_medium=repo&utm_campaign=fashion_prompt_cookbook&utm_content=womenswear
- 返回完整示例页：https://gptimg2.art/zh/prompts/gpt-image-2/category/womens-fashion?utm_source=github&utm_medium=repo&utm_campaign=fashion_prompt_cookbook&utm_content=womenswear
