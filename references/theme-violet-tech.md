# 公众号排版组件库 —— 蓝紫科技

信号标签与圆角模块，蓝紫双色划分概念和提示，浅底保持长文可读性。

适用：AI 观察 · 产品解析 · 技术趋势。预览见 `docs/gallery/violet-tech.html`，完整区块预览见 `assets/theme-previews/theme-violet-tech.html`。

## 设计变量速查表

| 角色 | 值 |
|---|---|
| 主色 | `#6351C7` |
| 全局背景 | `#FCFBFF` |
| 正文 | `#35334B` |
| 辅助文字 | `#7A7692` |
| 卡片底色 | `#F0EDFC` |
| 边框 | `#DCD5F1` |
| 点睛色 | `#3158AD` |
| 字体偏好 | `system` |
| 圆角（px） | `14` |

正文关键词使用 `border-bottom:2px solid #6351C7;font-weight:600;`，不要把整段都标记。正文颜色用于长文，主色用于标题与标记。

## 各组件完整 HTML

以下文案为语义占位。装配时替换为原文，不额外虚构数据、来源、署名、联系渠道或附件。无对应内容的组件省略。每一组件单独使用时，须放在下方全局容器内。

### 01 专题封面

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#7A7692;margin-bottom:14px;"><span leaf="">SIGNAL / IDEAS IN MOTION</span></p><section style="border-radius:18px;background:#F0EDFC;padding:26px 22px;border-top:4px solid #6351C7;margin-bottom:28px;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;color:#6351C7;"><span leaf="">专题观察</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:24px;line-height:1.45;font-weight:700;color:#6351C7;margin-bottom:16px;"><span leaf="">主标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:13px;margin:0;"><span leaf="">专题导语占位</span></p></section>
```

### 02 短刊头

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#7A7692;margin-bottom:14px;"><span leaf="">栏目标签占位</span></p><section style="border-left:4px solid #6351C7;padding:2px 0 2px 14px;margin:34px 0 20px;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#6351C7;margin-bottom:5px;"><span leaf="">01</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:20px;font-weight:700;margin:0;color:#35334B;"><span leaf="">栏目标题占位</span></p></section>
```

### 03 摘要封面

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">摘要标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">摘要正文占位</span></p></section>
```

### 04 导读导航

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">导读要点占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">章节要点占位／阅读路径占位／核心问题占位</span></p></section>
```

### 05 编号章节

```html
<section style="border-left:4px solid #6351C7;padding:2px 0 2px 14px;margin:34px 0 20px;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#6351C7;margin-bottom:5px;"><span leaf="">01</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:20px;font-weight:700;margin:0;color:#35334B;"><span leaf="">章节标题占位</span></p></section>
```

### 06 二级标题

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:17px;font-weight:700;color:#6351C7;margin-top:24px;"><span leaf="">小节标题占位</span></p>
```

### 07 标签标题

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#7A7692;margin-bottom:14px;"><span leaf="">标签占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:17px;font-weight:700;color:#6351C7;margin-top:24px;"><span leaf="">标题占位</span></p>
```

### 08 正文段落

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;"><span leaf="">正文内容占位。用于展示段落行距、字号与阅读节奏。</span></p>
```

### 09 重点段落

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;"><span leaf="">重点信息占位。</span><span style="border-bottom:2px solid #6351C7;font-weight:600;"><span leaf="">核心判断占位</span></span><span leaf="">以细线标记。</span></p>
```

### 10 行内代码

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;"><span leaf="">标识符占位：</span><span style="font-family:monospace;background:#F0EDFC;color:#6351C7;padding:2px 4px;"><span leaf="">sample_identifier</span></span><span leaf="">。</span></p>
```

### 11 引用按语

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">核心信号</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">引用内容占位。补充文章中的关键判断。</span></p></section>
```

### 12 居中引文

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;text-align:center;font-size:19px;color:#6351C7;padding:28px 0;"><span leaf="">金句内容占位</span></p>
```

### 13 旁注说明

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">旁注标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">补充说明占位</span></p></section>
```

### 14 警示提示

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#3158AD;margin-bottom:8px;"><span leaf="">注意事项占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">边界条件占位</span></p></section>
```

### 15 完成提示

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">完成说明占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">检查结果占位</span></p></section>
```

### 16 概念解释

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">概念标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">定义内容占位</span></p></section>
```

### 17 结尾引导

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">结尾引导占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">互动文案占位</span></p></section>
```

### 18 单步说明

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">01  /  </span></span><span leaf="">流程步骤占位</span></p>
```

### 19 流程总览

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">01  /  </span></span><span leaf="">起点说明占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">02  /  </span></span><span leaf="">处理说明占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">03  /  </span></span><span leaf="">结果说明占位</span></p>
```

### 20 时间线

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">A  /  </span></span><span leaf="">阶段说明占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">B  /  </span></span><span leaf="">下一阶段占位</span></p>
```

### 21 主图占位

```html
<section style="text-align:center;background:#F0EDFC;padding:42px 16px;border:1px solid #DCD5F1;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:24px;color:#7A7692;margin-bottom:8px;"><span leaf="">＋</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;color:#7A7692;font-size:12px;margin:0;"><span leaf="">主图占位</span></p></section>
```

### 22 图说版式

```html
<section style="text-align:center;background:#F0EDFC;padding:42px 16px;border:1px solid #DCD5F1;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:24px;color:#7A7692;margin-bottom:8px;"><span leaf="">＋</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;color:#7A7692;font-size:12px;margin:0;"><span leaf="">图片区域占位</span></p></section><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;color:#7A7692;"><span leaf="">图片说明占位</span></p>
```

### 23 双图对比

```html
<section style="text-align:center;background:#F0EDFC;padding:42px 16px;border:1px solid #DCD5F1;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:24px;color:#7A7692;margin-bottom:8px;"><span leaf="">＋</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;color:#7A7692;font-size:12px;margin:0;"><span leaf="">对照图占位一</span></p></section><section style="text-align:center;background:#F0EDFC;padding:42px 16px;border:1px solid #DCD5F1;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:24px;color:#7A7692;margin-bottom:8px;"><span leaf="">＋</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;color:#7A7692;font-size:12px;margin:0;"><span leaf="">对照图占位二</span></p></section>
```

### 24 视频占位

```html
<section style="text-align:center;background:#F0EDFC;padding:42px 16px;border:1px solid #DCD5F1;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:24px;color:#7A7692;margin-bottom:8px;"><span leaf="">＋</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;color:#7A7692;font-size:12px;margin:0;"><span leaf="">视频素材待补占位</span></p></section>
```

### 25 深色代码

```html
<section style="background:#172128;color:#DBE8ED;padding:18px;border-radius:14px;margin:20px 0;font-family:monospace;overflow-x:auto;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;line-height:1.6;margin:0;font-family:monospace;"><span leaf=""># 代码内容占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;line-height:1.6;margin:0;font-family:monospace;"><span leaf="">example --option value</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;line-height:1.6;margin:0;font-family:monospace;"><span leaf="">　output_placeholder</span></p></section>
```

### 26 浅色代码

```html
<section style="background:#F0EDFC;color:#35334B;padding:18px;border-radius:14px;margin:20px 0;font-family:monospace;overflow-x:auto;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;line-height:1.6;margin:0;font-family:monospace;"><span leaf=""># 代码内容占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;line-height:1.6;margin:0;font-family:monospace;"><span leaf="">example --option value</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;line-height:1.6;margin:0;font-family:monospace;"><span leaf="">　output_placeholder</span></p></section>
```

### 27 数据表格

```html
<table style="width:100%;border-collapse:collapse;margin:20px 0;font-size:12px;"><tr><td style="padding:12px;border-bottom:1px solid #DCD5F1;background:#F0EDFC;"><span leaf="">字段占位</span></td><td style="padding:12px;border-bottom:1px solid #DCD5F1;background:#F0EDFC;"><span leaf="">说明占位</span></td></tr><tr><td style="padding:12px;border-bottom:1px solid #DCD5F1;background:#FCFBFF;"><span leaf="">指标占位</span></td><td style="padding:12px;border-bottom:1px solid #DCD5F1;background:#FCFBFF;"><span leaf="">数值占位</span></td></tr><tr><td style="padding:12px;border-bottom:1px solid #DCD5F1;background:#FCFBFF;"><span leaf="">口径占位</span></td><td style="padding:12px;border-bottom:1px solid #DCD5F1;background:#FCFBFF;"><span leaf="">来源占位</span></td></tr></table>
```

### 28 指标摘要

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">指标标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span style="border-bottom:2px solid #6351C7;font-weight:600;"><span leaf="">数值占位</span></span><span leaf="">　口径说明占位</span></p></section>
```

### 29 进度条

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;"><span leaf="">进度说明占位</span></p><section style="background:#DCD5F1;margin:12px 0;height:5px;"><section style="height:5px;width:60%;background:#6351C7;"></section></section><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;color:#7A7692;"><span leaf="">比例仅为版式示意</span></p>
```

### 30 项目清单

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">•  /  </span></span><span leaf="">条目内容占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">•  /  </span></span><span leaf="">补充条目占位</span></p>
```

### 31 顺序列表

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">01  /  </span></span><span leaf="">第一项说明占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">02  /  </span></span><span leaf="">第二项说明占位</span></p>
```

### 32 检查清单

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">□  /  </span></span><span leaf="">待核对事项占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">✓  /  </span></span><span leaf="">已核对事项占位</span></p>
```

### 33 方案对照

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">方案甲占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">特征说明占位</span></p></section><section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">方案乙占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">差异说明占位</span></p></section>
```

### 34 问答说明

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">问题内容占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">回答内容占位</span></p></section>
```

### 35 作者信息

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">作者署名占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">作者介绍占位</span></p></section>
```

### 36 联系说明

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">联系说明占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">联系渠道占位</span></p></section>
```

### 37 附件指引

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">附件说明占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">获取方式占位</span></p></section>
```

### 38 延伸阅读

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;padding:0 0 12px;border-bottom:1px solid #DCD5F1;"><span style="font-size:11px;font-weight:700;color:#6351C7;"><span leaf="">↗  /  </span></span><span leaf="">延伸阅读标题占位</span></p>
```

### 39 结论摘要

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">结论标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf=""></span><span style="border-bottom:2px solid #6351C7;font-weight:600;"><span leaf="">结论要点占位</span></span><span leaf="">。适用范围占位。</span></p></section>
```

### 40 互动收束

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;text-align:center;color:#6351C7;padding:20px 0;"><span leaf="">互动引导占位</span></p>
```

### 41 数据来源

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;color:#7A7692;border-top:1px solid #DCD5F1;padding-top:12px;"><span leaf="">来源说明占位／统计口径占位</span></p>
```

### 42 术语条目

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">术语标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">术语解释占位</span></p></section>
```

### 43 边界条件

```html
<section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#3158AD;margin-bottom:8px;"><span leaf="">边界条件占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">适用条件与限制说明占位</span></p></section>
```

### 44 分节过渡

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#7A7692;margin-bottom:14px;"><span leaf="">过渡说明占位</span></p><section style="height:1px;background:#DCD5F1;margin:22px 0;"></section>
```

### 45 脚注说明

```html
<p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;color:#7A7692;"><span leaf="">注释占位。补充背景与限定说明占位。</span></p>
```

## 完整文章模板骨架

01 信号封面 → 11 引言 → 04 主题导读 → 05 章节与概念模块 → 39 收束总结 → 35 作者信息 → 40 互动收束。目录为精选导读，不作为完整章节清单。

```html
<section style="max-width:677px;margin:0 auto;padding:28px 24px;background:#FCFBFF;color:#35334B;font-family:-apple-system,BlinkMacSystemFont,'PingFang SC','Microsoft YaHei',sans-serif;box-sizing:border-box;overflow-wrap:break-word;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#7A7692;margin-bottom:14px;"><span leaf="">SIGNAL / IDEAS IN MOTION</span></p><section style="border-radius:18px;background:#F0EDFC;padding:26px 22px;border-top:4px solid #6351C7;margin-bottom:28px;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;color:#6351C7;"><span leaf="">专题观察</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:24px;line-height:1.45;font-weight:700;color:#6351C7;margin-bottom:16px;"><span leaf="">文章标题占位</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:13px;margin:0;"><span leaf="">导语内容占位</span></p></section><!-- 导读槽：有需要时放入组件04 --><section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">核心信号</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">引言内容占位</span></p></section><!-- 下方章节和段落按原文重复 --><section style="border-left:4px solid #6351C7;padding:2px 0 2px 14px;margin:34px 0 20px;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:11px;letter-spacing:2px;color:#6351C7;margin-bottom:5px;"><span leaf="">01</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:20px;font-weight:700;margin:0;color:#35334B;"><span leaf="">章节标题占位</span></p></section><p style="margin:0 0 18px;font-size:15px;line-height:1.95;"><span leaf="">正文内容占位</span></p><!-- 结论与来源槽：仅有对应内容时添加 --><section style="background:#F0EDFC;border-radius:14px;padding:20px;margin:20px 0;"><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:12px;font-weight:700;color:#6351C7;margin-bottom:8px;"><span leaf="">作者信息</span></p><p style="margin:0 0 18px;font-size:15px;line-height:1.95;font-size:14px;margin:0;"><span leaf="">我是 {{作者名}}，{{简介}}</span></p></section><!-- 末尾互动槽：按原文合并一次 --></section>
```

标题最多 24px；装饰空节点无文本时保留空元素即可，不添加虚假内容。章节按 `##` 顺序编号，结语继续数字编号。图片及 GIF 用通用库 2a/2b，背景、文字和说明色替换成本主题色；空 alt 不造图说。待补素材可用本库 21–24，存在真实素材时必须换成真实图片组件。

作者槽使用 35，互动槽使用 40，原文已有署名时合并一次；无署名时保留 `{{作者名}}` 与 `{{简介}}`。17 为另一种结尾样式，与 35+40 二选一，不叠加。

## 文章类型 → 组件组合配方表

所有文章均使用全局容器、标题、正文和按需署名；下表列出主体组合。点缀组件最多 3 类，没有对应内容时省略。

| 文章类型 | 核心组件 | 点缀组件 |
|---|---|---|
| 教程/操作指南 | 04 导读导航 + 18 单步说明 + 26 浅色代码 | 14 警示提示 |
| 盘点/工具清单 | 07 标签标题 + 33 方案对照 + 30 项目清单 | 28 指标摘要 |
| 观点/深度分析 | 01 专题封面 + 16 概念解释 + 11 引用按语 | 39 结论摘要 |
| 访谈/人物特稿 | 01 专题封面 + 12 居中引文 + 35 作者信息 | 13 旁注说明 |
| 数据复盘/报告 | 03 摘要封面 + 28 指标摘要 + 27 数据表格 | 41 数据来源 |
| 生活/情感随笔 | 02 短刊头 + 08 正文段落 + 40 互动收束 | 12 居中引文 |
| 案例实战 | 19 流程总览 + 33 方案对照 + 39 结论摘要 | 15 完成提示 |

## Markdown → 组件映射规则表

| 元素 | 组件与规则 |
|---|---|
| `# 标题` | 01 封面；精简开头可用 02；不改写标题含义 |
| `## 章节` | 05，按顺序编号 |
| `### 小节` | 06；小标签语义用 07 |
| 正文 | 08；关键词采用 09 的下划线写法，每段 1–3 处 |
| `**加粗**` / `==高亮==` / `<u>` / `++文字++` | 09 内的下划线标记；强锚点最多 5 处 |
| `~~文字~~` | 按 Skill 约定作轻量荧光笔标记，使用卡片底色；不改变文字 |
| 行内代码 | 10；保留代码字符和半角标点 |
| `> 引用` | 11；金句可用 12，不虚构归属 |
| 无序 / 有序列表 | 30 / 31；实际项数与原文一致 |
| 任务列表 | 32，保留原文完成状态 |
| 围栏代码 | 25 / 26；每行一个零外边距段落，不使用 white-space:pre |
| 表格 | 27，保留真实列数、行数和数据；不以表格做布局 |
| 图片 / GIF | 通用库 2a / 2b；本库 21–24 只用于素材占位 |
| 指标 / 来源 | 28 / 41；不凭空生成数据、比例或出处 |
| `---` | 44 的细分隔线，无须增加过渡文案 |
| 署名 / 结尾引导 | 35+40 或 17，末尾仅一处 |
