<div lang="zh-tw">

> [!IMPORTANT]  
> **注意事項**
> 
> 此字型不是普通顯示字型，不包括統合漢字，僅作為回退字型使用。  
> 該項目目前處於測試階段，所以能夠支持的字數不多，並有一部分不符合在地標準的字符，並未及時修改。  
> 字形調整和修正字形錯誤需求請在 [Issue #1](https://github.com/Des-Magmeta/PlanKai/issues/1) 中反饋，字形增補需求請在 [Issue #2](https://github.com/Des-Magmeta/PlanKai/issues/2) 中反饋，**不要另外新建 Issue 串。**

<div align="center">

<span lang="zh-cn">
 [简体中文](README.md)
</span>
 | [English](README.en.md)

# PlanKai / 計劃楷

[![開源授權](https://img.shields.io/github/license/Des-Magmeta/PlanKai?style=flat-square)](https://github.com/Des-Magmeta/PlanKai) 
 [![最新版](https://img.shields.io/github/release/Des-Magmeta/PlanKai?style=flat-square)](https://github.com/Des-Magmeta/PlanKai/releases/latest)  

</div>

計劃楷是基於 FONTWORKS 的開源字型 Klee One，并以各地字形为標準的對中日韓統合表意文字擴充區進行字形補充的項目。

![](https://raw.githubusercontent.com/Des-Magmeta/PlanKai/main/images/PlanKai-1.jpg)  

## Introduction / 項目簡介

2020 年 12 月，日本著名字型廠商 FONTWORKS 在 GitHub 上釋出了 [7 款開源日文字型](https://github.com/fontworks-fonts)，其中 [Klee One](https://github.com/fontworks-fonts/Klee) 字符數最多，兼有仿宋和楷體的特点，具有優雅的外觀及較高的可讀性，非常適合內文排印。许多字型設計師／爱好者也製作了各個衍生版本，如[霞鶩文楷](https://github.com/lxgw/LxgwWenkai)、[「芫荽」](https://github.com/ButTaiwan/iansui)、[「芫茜雅楷」](https://github.com/ItMarki/jyunsaikaai) 等。在這些人的努力下，一系列基於 Klee One 改作的字形支援的字符數已足夠多，并且能夠支援一些容易顯示為豆腐塊的字符。 
然而，還有大量位於擴充區的漢字無法被直接顯示，顯示的文本或是回退到宋體，或是顯示為不符合在地標準字形，更多的則顯示為「豆腐塊」。  
計劃楷（Plan Kai）是基於 Klee One 进行字符擴展及補充的項目。該項目由本人在 2022 年 12 月所開啟，最終目標是盡可能補全 Unicode 已收錄的所有漢字，並制作出一部分原本沒有楷體風格的楷體字。

## Coverage / 收錄字符範圍（計劃）
- [ ] Adobe-Japan1-6 收录字符  
- [ ] Adobe-CNS1-7 收录字符  
- [ ] [「霞鶩文楷」/ LXGW WenKai](https://github.com/lxgw/LxgwWenKai) 收录字符  
- [ ] V0 ~ V2 字喃（Chữ Nôm） 
- [ ] 中日韓相容漢字及補充

## Adjustment & Descriptions / 字形調整原則與相關說明

從 v0.01 版本開始，除支援假想 G 標外，開始支援假想 J 標，由于字符數量龐大，目前沒有對假想 T/H 標的支援計劃。  
### Simplified Chinese / 簡體（SC）
- 盡可能採用中國大陸標準筆形，對提交源不包含 G 源的字符，原則上按照各部件之間的地區字形差異進行調整，盡可能接近假想中國大陸標準字形。
### Japanese Version / 日本標準（JP）
- 盡可能採用日本標準字形，具體字形參照
  <span lang="ja-jp">[「字雲 / Jigmo」](https://kamichikoichi.github.io/jigmo/)</span>
  。通常情況下，對表外字的處理遵循日文舊字體筆形；  
- 若提交的 J 源字符中部件按照新字体標準，则遵循相應筆形；  
- 為保持風格一致性，對製作的任何字形在此版中的部件採用日本標準筆形；  
- 為與標準性相兼容，對包含中國大陸簡體字部件（如
  <span lang="zh-cn">
  `饣`
  </span>
  、
  <span lang="zh-cn">
  `钅`
  </span>
  、
  <span lang="zh-cn">
  `讠`
  </span>
  、
  <span lang="zh-cn">
  `贝`
  </span>
  、
  <span lang="zh-cn">
  `车`
  </span>
  、
  <span lang="zh-cn">
  `长`
  </span>
等）的字符略微調整接近中國大陸新字形的筆形，相應部件的傳統印刷特徵（如下折的
  <span lang="zh-cn">
  `纟`
  </span>
  、斷筆的
  <span lang="zh-cn">
  `㇜㇙`
  </span>
  、直點的
  <span lang="zh-cn">
  `宀亠`
  </span>
等）也將選擇性保留。

### Additional description / 補充說明
* 在所有版本中，對字喃等提交源僅包含 V 源的字，以寬鬆標準進行調整、增補，不完全遵循 V 源標準。 

## Authorization / 授權信息  

此字型是基於 SIL Open Font License 1.1 改作的 FONTWORKS 開發并釋出的 [Klee](https://github.com/fontworks-fonts/Klee) 開源專案。Klee 是 FONTWORKS 的商標。

### License / 許可  

- 此字型無論是個人還是企業都可以自由商用，無需付費，也無需知會或者標明原作者。*（但如果告知，我會很感激。）*  
- 此字型可以自由傳播、分享，或者將字型安裝於系統、軟體或APP中也是允許的，可以與任何軟件捆綁再分發以及／或一併銷售。  
- 此字型可以自由修改、改造，製作衍生字型。修改或改造後的字體也必須同樣以[SIL OFL 1.1](https://scripts.sil.org/OFL)公開。

### Limit / 限制  

- 在製作衍生字型時，其名稱不可使用原有字型的「保留名稱」。 本字體保留名稱
<span lang="zh-cn">「计划楷」</span>
<span lang="zh-tw">「計劃楷」</span>
<span lang="ja-jp">「プラン楷書」</span>
「PlanKai」，基於本字型二次衍生的專案，名稱不可出現保留名稱
<span lang="zh-cn">「计划楷」</span>
<span lang="zh-tw">「計劃楷」</span>
<span lang="ja-jp">「プラン楷書」</span>
或「PlanKai」； 而在沒有對字體原始程式碼進行修改的情况下，重新編譯出來的字型，可以繼續使用此字型的保留名稱。
- 根據 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 許可與條款第一條的規定，**禁止單獨出售字型檔案（OTF/TTF檔案）的行為。**
- 此字型不可在 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 以外的授權許可下發行。

## Acknowledgement / 鳴謝

- [FONTWORKS 株式會社](http://fontworks.co.jp) 釋出原版开源字型（見[開發者 GitHub 主頁](https://github.com/fontworks-fonts/)）
- [Fitzgerald](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project) 提供擴充區漢字假定 G 源字形參考。（见[遍黑體 Github 項目](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic-Project)）
- [白易](https://github.com/yi-bai)開發的網站[字統网](https://zi.tools) 提供各地區標準字形參考。
- [lxgw](https://github.com/lxgw)、[ButTaiwan](https://github.com/ButTaiwan)、[ItMarki](https://github.com/ItMarki)、[GuiWonder](https://github.com/GuiWonder/MoonStarsKai)提供相關字型。

</div>
