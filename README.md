[英语 / English](README.en.md)

> **注意事项**
> 
> 此字体不是普通显示字体，不包括基本区汉字，仅作为后备字体使用。
> 该项目目前处于测试阶段，所以能够支持的字数不多，并有一部分非 G 字符未修改。
  
# PlanKai / 计划楷

An open-source font for Unified Ideographic Extension derived from Fontworks' Klee One.一款开源扩展汉字字体，基于 FONTWORKS 出品字体 Klee One 衍生。
![](https://raw.githubusercontent.com/Des-Magmeta/PlanKai/main/images/PlanKai-1.jpg)  
## Introduction / 项目简介

2020 年 12 月，日本著名字体厂商 FONTWORKS 在 GitHub 上释出了 [7 款开源日文字体](https://github.com/fontworks-fonts)，其中 [Klee One](https://github.com/fontworks-fonts/Klee) 字符数最多，兼有仿宋和楷体的特点，具有优雅的外观及较高的可读性，非常适合正文排版。与一般的教科书体相比，Klee One 保留了传统印刷字体的一些特征。2021 年，[lxgw](https://github.com/lxgw) 在其基础上增补和修改字形，制成[「霞鹜文楷」/ LXGW WenKai](https://github.com/lxgw/LxgwWenKai) 字体，受到广泛欢迎。除此之外，一些字体设计师/爱好者也制作了其他的衍生版本，如[「芫荽」/ Iansui](https://github.com/ButTaiwan/iansui)、[「芫茜雅楷」/ JyunsaiKaai](https://github.com/ItMarki/jyunsaikaai) 等。在字体设计师/爱好者的努力下，一系列基于 Klee One 衍生的字体支持的字符数已足够多，尤其能够支持一些思源黑体不支持的字符。  
然而，还有大量的扩展区汉字无法被直接显示，显示的文本或是回退到宋体，或是显示为不符合在地标准字形，更多的则显示为「豆腐块」。  
计划楷（Plan Kai）是基于 Klee One 进行字符扩展及补充的项目。该项目由本人在 2022 年 12 月份所开启，最终目标是尽可能补全 Unicode 已收录的所有汉字，并制作出一部分原本没有楷体风格的楷体字。

## Coverage / 收录字符范围（计划）

- [ ] 中日韩统一表意文字基本区补充、扩展 A 区  
- [ ] 中日韩统一表意文字扩展 B 区、扩展 C 区、扩展 D 区  
 * 由于扩展 B 区字符数目较大，暂定仅收录思源字体原有字、[「霞鹜文楷」/ LXGW WenKai](https://github.com/lxgw/LxgwWenKai) 收录字符、提交源包含 V0 ～ V2 的字喃（Chữ Nôm），**并不支持完整的扩展 B 区。**  
- [ ] 中日韩统一表意文字扩展 E 区、扩展 F 区  

## Adjustment / 字形调整原则
从 v0.01 版本开始，除更新假想 G 标外，将开始支持假想 J 标，后期根据实际使用情况增加对假想 T/H 标的支持。
* 对提交源不包含对应标准的字，原则上按照各部件之间的地区字形差异进行调整，尽可能接近各地标准字形。  
* 对字喃等提交源仅包含 V 源的字，以宽松标准进行调整、增补，不完全遵循 V 源标准。 

## Authorization / 授权信息

本字体是基于 SIL Open Font License 1.1 改造的 FONTWORKS 开发并发布的 [Klee](https://github.com/fontworks-fonts/Klee) 开源项目。Klee 是 FONTWORKS 的商标。

### License / 许可

- 这款字体无论是个人还是企业都可以自由商用，无需付费，也无需知会或者标明原作者。 *（但如果告知，我会很感激。）*
- 这款字体可以自由传播、分享，或者将字体安装于系统、软件或 APP 中也是允许的，可以与任何软件捆绑再分发以及／或一并销售。
- 这款字体可以自由修改、改造，制作衍生字体。修改或改造后的字体也必须同样以 [SIL OFL 1.1](https://scripts.sil.org/OFL) 公开。

### Limit / 限制

- 在制作衍生字体时，字体名称不可使用原有字体的「保留名称」。本字体保留名称「计划楷」「PlanKai」，基于本字体二次衍生的字体，名称不可出现「计划楷」或「PlanKai」字样；而在没有对字体源代码进行修改的情况下，重新编译出来的字体，可以继续使用本字体的保留名称「计划楷」「PlanKai」。
- 根据 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 许可与条件中第一条的规定， **禁止单独出售字体文件(OTF/TTF文件)的行为。**
- 该字体不可在 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 以外的授权许可下发行。

## Acknowledgement / 鸣谢

- [FONTWORKS 株式会社](http://fontworks.co.jp) 提供原版开源字体（见[开发者 GitHub 主页](https://github.com/fontworks-fonts/)）
- [Fitzgerald](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project) 提供扩展区汉字假想 G 源字形参考。（见[遍黑体 Github 项目](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project)）
- [白易](https://github.com/yi-bai)开发的网站[字统网](https://zi.tools) 提供各地区标准字形参考。
- [lxgw](https://github.com/lxgw)、[ButTaiwan](https://github.com/ButTaiwan)、[ItMarki](https://github.com/ItMarki)提供相关字型。
