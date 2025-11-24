# 中間発表

## [11/25発表資料](https://docs.google.com/presentation/d/14tDjXKVV8x3G4FB8lVPOgMfdCh0nsy45RVLAvrSj3JE/edit?usp=sharing)

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
3. 解析結果の可視化と解釈(QGIS)

[Tutorial Manual](https://www.notion.so/Tutorial-2b4ad1d01b29800395c4d8d7ac594856?source=copy_link)


## スケジュール（目標時期）
- **10月末**：Lelystadで流れを一度通す  （1~4の流れ）
- **12月**：全都市で論文の表・図を再現  
- **3月**：麻生区に応用  

## 期待される成果
- 既存研究の再現性の確認  
- 自分の都市への応用可能性の把握  
- 大学院進学に向けた研究基盤の構築  

## 使用予定ツール
- **DepthmapX**：Space Syntax解析（Angular analysis, Integration計算）  
- **QGIS**：Spacematrix (FSI, GSI, L)、MXI、150mグリッド集計、可視化  
- **Python / R**：Match Rate計算、データ整形、再現性のあるスクリプト化  
- **GitHub**：進捗管理、成果物共有（README, Issues, Project Board）  

## 参考文献
- [Ye, Y. & van Nes, A. (2013). *Measuring urban maturation processes in Dutch and Chinese new towns: Combining street network configuration with building density and degree of land use diversification through GIS.* **The Journal of Space Syntax**, 4(1), 18–37.](http://www.journalofspacesyntax.org/)  
