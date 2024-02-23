> [!IMPORTANT]  
> **注意事项**
> 
> 此字体不是普通显示字体，不包括基本区汉字，仅作为后备字体使用。  
> 该项目目前处于测试阶段，所以能够支持的字数不多，并有一部分不符合在地标准的字符未及时修改。  
> 字形调整和修正字形错误需求请在 [Issue #1](https://github.com/Des-Magmeta/PlanKai/issues/1) 中反馈，字形增补需求请在 [Issue #2](https://github.com/Des-Magmeta/PlanKai/issues/2) 中反馈，**不要另开议题。**

<div align="center">

<span lang="zh-tw">

[繁體中文](README.tc.md)
</span>
 | [English](README.en.md)

# PlanKai / 计划楷

[![开源授权](https://img.shields.io/github/license/Des-Magmeta/PlanKai?style=flat-square)](https://github.com/Des-Magmeta/PlanKai) 
 [![最新版](https://img.shields.io/github/release/Des-Magmeta/PlanKai?style=flat-square)](https://github.com/Des-Magmeta/PlanKai/releases/latest)  

</div>

计划楷是基于 FONTWORKS 的开源字体 Klee One，并以各地字形为标准的对中日韩统一表意文字扩展区进行自行补充的项目。  

![](https://raw.githubusercontent.com/Des-Magmeta/PlanKai/main/images/PlanKai-1.jpg)  

## Introduction / 项目简介

2020 年 12 月，日本著名字体厂商 FONTWORKS 在 GitHub 上释出了 [7 款开源日文字体](https://github.com/fontworks-fonts)，其中 [Klee One](https://github.com/fontworks-fonts/Klee) 字符数最多，兼有仿宋和楷体的特点，具有优雅的外观及较高的可读性，非常适合正文排版。许多字体设计师／爱好者也制作了各个衍生版本，如[霞鹜文楷](https://github.com/lxgw/LxgwWenkai)、[「芫荽」](https://github.com/ButTaiwan/iansui)、[「芫茜雅楷」](https://github.com/ItMarki/jyunsaikaai) 等。在这些人的努力下，一系列基于 Klee One 衍生的字体支持的字符数已足够多，并且能够支持一些容易显示为豆腐块的字符。  
然而，还有大量的扩展区汉字无法被直接显示，显示的文本或是回退到宋体，或是显示为不符合在地标准字形，更多的则显示为「豆腐块」。  
计划楷（Plan Kai）是基于 Klee One 进行字符扩展及补充的项目。该项目由本人在 2022 年 12 月所开启，最终目标是尽可能补全 Unicode 已收录的所有汉字，并制作出一部分原本没有楷体风格的楷体字。

## Coverage / 收录字符范围（计划）
- [ ] Adobe-Japan1-6 收录字符  
- [ ] Adobe-CNS1-7 收录字符  
- [ ] [「霞鹜文楷」/ LXGW WenKai](https://github.com/lxgw/LxgwWenKai) 收录字符  
- [ ] V0 ~ V2 字喃（Chữ Nôm） 
- [ ] 中日韩兼容汉字及补充
## Adjustment & Descriptions / 字形调整原则与相关说明

从 v0.01 版本开始，除支持假想 G 标外，开始支持假想 J 标，由于字符数量庞大，目前没有对假想 T/H 标的支持。  
### Simplified Chinese / 简体（SC）
- 尽可能采用中国大陆标准笔形。对提交源不包含 G 源的字符，原则上按照各部件之间的地区字形差异进行调整，尽可能接近假想中国大陆标准字形。
 
### Japanese Version / 日标（JP）
- 尽可能采用日本标准字形，具体字形参照
  <span lang="ja-jp">[「字雲 / Jigmo」](https://kamichikoichi.github.io/jigmo/)</span>
。通常情况下，对表外字的处理遵循日文旧字体笔形；  
- 若提交的 J 源字符中部件按照新字体标准，则跟从对应写法；  
- 为保持风格一致性，对制作的任何字符在此版中的部件采用日本标准笔形；  
- 为与标准性相兼容，对包含简体字部件（如`饣`、`钅`、`讠`、`贝`、`车`、`长`等）的字符略微调整接近中国大陆新字形的写法，一些简体字部件的传统印刷特征（如下折的`纟`、断笔的`㇜㇙`、直点的`宀亠`等）也将选择性保留。

### Additional description / 补充说明
* 在所有版本中，对字喃等提交源仅包含 V 源的字，以宽松标准进行调整、增补，不完全遵循 V 源标准。 

## Authorization / 授权信息

本字体是基于 SIL Open Font License 1.1 改造的 FONTWORKS 开发并发布的 [Klee](https://github.com/fontworks-fonts/Klee) 开源项目。Klee 是 FONTWORKS 的商标。

### License / 许可  

- 这款字体无论是个人还是企业都可以自由商用，无需付费，也无需知会或者标明原作者。 *（但如果告知，我会很感激。）*
- 这款字体可以自由传播、分享，或者将字体安装于系统、软件或 APP 中也是允许的，可以与任何软件捆绑再分发以及／或一并销售。
- 这款字体可以自由修改、改造，制作衍生字体。修改或改造后的字体也必须同样以 [SIL OFL 1.1](https://scripts.sil.org/OFL) 公开。

### Limit / 限制  

- 在制作衍生字体时，字体名称不可使用原有字体的「保留名称」。本字体保留名称
<span lang="zh-cn">「计划楷」</span>
<span lang="zh-tw">「計劃楷」</span>
<span lang="ja-jp">「プラン楷書」</span>「PlanKai」，基于本字体二次衍生的字体，名称不可出现保留名称
<span lang="zh-cn">「计划楷」</span>
<span lang="zh-tw">「計劃楷」</span>
<span lang="ja-jp">「プラン楷書」</span>
或「PlanKai」；而在没有对字体源代码进行修改的情况下，重新编译出来的字体，可以继续使用本字体的保留名称。
- 根据 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 许可与条件中第一条的规定， **禁止单独出售字体文件(OTF/TTF文件)的行为。**
- 该字体不可在 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 以外的授权许可下发行。

## Acknowledgement / 鸣谢

- [FONTWORKS 株式会社](http://fontworks.co.jp) 提供原版开源字体（见[开发者 GitHub 主页](https://github.com/fontworks-fonts/)）
- [Fitzgerald](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project) 提供扩展区汉字假想 G 源字形参考。（见[遍黑体 Github 项目](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project)）
- [白易](https://github.com/yi-bai)开发的网站[字统网](https://zi.tools) 提供各地区标准字形参考。
- [lxgw](https://github.com/lxgw)、[ButTaiwan](https://github.com/ButTaiwan)、[ItMarki](https://github.com/ItMarki)、[GuiWonder](https://github.com/GuiWonder/MoonStarsKai)提供相关字型。
