> [!IMPORTANT]  
> **Notes**
> 
> This font isn't used for normal characters. It includes Unified ideograph characters (Extension) only and is just for fallback only.  
> This repository is currently in the testing stage, so there aren't many characters to support. And some glyphs of characters haven't been modified yet.  
> You can leave a comment for glyph addition request(s) in [Issue #2](https://github.com/Des-Magmeta/PlanKai/issues/2). And for glyph adjustment(s) in [Issue #1](https://github.com/Des-Magmeta/PlanKai/issues/1). **Don’t create a new issue.**

<div align="center">

<span lang="zh-cn">

[简体中文](README.md)
</span>
 |
<span lang="zh-tw">
[繁體中文](README.tc.md)
<span>

<span lang="en-us">

# Plan Kai

</span>

An open-source font for Unified Ideographic Extension derived from Fontworks' Klee One.

[![License](https://img.shields.io/github/license/Des-Magmeta/PlanKai?style=flat-square)](https://github.com/Des-Magmeta/PlanKai) 
 [![Latest Version](https://img.shields.io/github/release/Des-Magmeta/PlanKai?style=flat-square)](https://github.com/Des-Magmeta/PlanKai/releases/latest)  

![](https://raw.githubusercontent.com/Des-Magmeta/PlanKai/main/images/PlanKai-EN-Banner.jpg)  
</div>

## Introduction

In December 2020, Japanese type foundry FONTWORKS released [7 Open-source Japanese fonts](https://github.com/fontworks-fonts) on GitHub, with [Klee One](https://github.com/fontworks-fonts/Klee) supporting the most characters. It shares some features with Fangsong and Kaiti, namely elegant composition and high readability. Many font designers also made fonts derived from Klee One, such as [LxgwWenkai](https://github.com/lxgw/LxgwWenkai), [Iansui](https://github.com/ButTaiwan/iansui), [JyunsaiKaai](https://github.com/ItMarki/jyunsaikaai), and so on. With the efforts of font designers, a series of fonts derived from Klee One support many enough characters, especially some characters that are displayed as “tofu”.  
However, there are also a large number of CJK Unified ideographic extensions that can't be displayed directly. These characters either falls back to the Songti, or is displayed as a font that doesn't conform to local standards when they're displayed, and more are displayed as “tofu”.  
Plan Kai(Chinese: <span lang="zh-cn">
计划楷</span> / <span lang="zh-tw">計劃楷</span>; Japanese: <span lang="ja-jp">プラン楷書</span>) is a repository based on Klee One and takes the Chinese Mainland glyphs as the standard to supplement the CJK Unified ideographic extension. This repository was initiated around December 2022. The eventual goal is to complete all the Chinese characters included in Unicode as much as possible, and produce a part of the regular script without the original style of Kaiti(<span lang="zh-cn">楷体</span> / <span lang="zh-tw">楷體</span>).  

## Coverage (Planning) 

- [x] Adobe-Japan1-7  
- [ ] Adobe-CNS1-7  
- [x] Characters from [LxgwWenkai](https://github.com/lxgw/LxgwWenkai)  
- [ ] Chữ Nôm from V0, V1 & V2  
- [ ] CJK compatibility ideographs (including supplement)  
> Since version 1.330, the [character addition issue](https://github.com/lxgw/LxgwWenKai/issues/33) of LxgwWenKai has been closed. Therefore, this repository is currently considered to complete the target range of characters included in LxgwWenKai. If new characters are added in the subsequent versions of it, this repository will follow up.


## Adjustments and Descriptions

Besides (imagination) G standard, (imagination) J standard has been supported since version 0.010, whose specific glyphs will refer to [Jigmo](https://kamichikoichi.github.io/jigmo/).  
Besides, Kangxi radicals, CJK Strokes and CJK Compatibility characters (including supplement) has been added since version 0.020.

## Authorization

Plan Kai is derived from Klee One, which is licensed under the SIL Open Font License 1.1. [Klee](https://github.com/fontworks-fonts/Klee) is the trademark of FONTWORKS.

### License

- Free use, including commercial use, without payment, notification, or identification of the original author.
- Share font files freely and install them on any software or device.
- On this basis, the work shall be modified or re-created. The second modified version shall also be published in [SIL Open Font Licenses 1.1](https://scripts.sil.org/OFL).

### Limit

- When making a derived font, the font name cannot use the “reserved name” of the original font.
- The reserved name “<span lang="zh-cn">计划楷</span>”, “<span lang="zh-tw">計劃楷</span>”, “<span lang="ja-jp">プラン楷書</span>” and “PlanKai” shall not be used for the second modified work. Without modifying the font source code, the recompiled font can continue to use its reserved name.
  
- According to the provisions of Article 1 in the license and terms of [SIL Open Font License 1.1](https://scripts.sil.org/OFL), **Selling this font by itself is banned.**
- This font can't be distributed in a license other than the [SIL Open Font License 1.1](https://scripts.sil.org/OFL).

## Acknowledgement

- Original font developed by [FONTWORKS](http://fontworks.co.jp).
- [Plangothic Project](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project) initiated by  [Fitzgerald](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project).
- [Zitools](https://zi.tools) developed by [Bai Yi](https://github.com/yi-bai).
- Related fonts developed by [lxgw](https://github.com/lxgw),  [ButTaiwan](https://github.com/ButTaiwan), [ItMarki](https://github.com/ItMarki),  [GuiWonder](https://github.com/GuiWonder/MoonStarsKai), and [Steve-Yuu](https://github.com/Steve-Yuu/YshiPen-Shuti).  
- The font is completed with the assistance of [HackerSam](https://github.com/HackerSam) and [Steve-Yuu](https://github.com/Steve-Yuu/YshiPen-Shuti).