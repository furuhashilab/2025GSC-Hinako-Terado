# 中間発表

## [11/25発表資料]([https://docs.google.com/presentation/d/14tDjXKVV8x3G4FB8lVPOgMfdCh0nsy45RVLAvrSj3JE/edit?usp=sharing](https://docs.google.com/presentation/d/1UXQNEDKLON1MkX_4vQM7jty1Cu_7F8sw2V-UmEeGDm4/edit?usp=sharing))

## 研究テーマ
**上麻生エリアにおけるSpace Syntax(DepthmapX) を用いた都市構造分析**

## 目的
- 都市空間の“Visibility Graphs Analysis(可視性分析), Axial Map(最長視線), Segment Analysis”を測り、上麻生の空間構造を理解する。
-  **DepthmapX**基礎操作の習得を目指す
- 応用研究テーマ未定 

## 背景
- Ye & van Nes (2013) の論文( 新都市 vs 旧都市の成熟度(発展度合)の違いを定量化した先行研究)を再現し、その分析手法の習得を目指す
- Space Syntaxが成熟度研究の重要な解析であるため、DepthmapXが使用可能かどうか、操作方法の理解を優先する必要があった  

## 研究の流れ（ロードマップ）
1. データの準備とエクスポート(QGIS/Quick OSM)
2. 空間解析の実行(DepthmapX)
   - 建物データを用いた空間解析
   - 道路データを用いた空間解析
3. 解析結果の可視化(QGIS)
4. 解析結果の理解

[Tutorial Manual](https://www.notion.so/Tutorial-2b4ad1d01b29800395c4d8d7ac594856?source=copy_link)


## 成果
- QGISとDepthmapXを連携させる技術の習得
- ３つの主要なSpace Syntax分析の役割の違いをある程度理解
- 都市成熟度論文（Ye & van Nes）とのつながり


## 使用予定ツール
- **DepthmapX**：Space Syntax解析（Visibility Analysis, Axial Map, Segment Analysisの解析）  
- **QGIS**： Visibility Analysis(ヒートマップ),  Segment Analysis(セグメントの色分け)の可視化
-  **GitHub**：進捗管理、成果物共有
-  **Notion**: Tutorialのマニュアル化 

## 参考文献
- [01 | OSM to QGIS: Open Source Data + Vector Export　~07|](https://youtu.be/1TayyUMyE6U?list=TLGGIYF1EyGEUEwyNDExMjAyNQ) 
- [Ye, Y. & van Nes, A. (2013). *Measuring urban maturation processes in Dutch and Chinese new towns: Combining street network configuration with building density and degree of land use diversification through GIS.* **The Journal of Space Syntax**, 4(1), 18–37.](http://www.journalofspacesyntax.org/)  
