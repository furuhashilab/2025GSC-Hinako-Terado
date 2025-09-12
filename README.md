# Pre-thesis project

# 論文再現と応用計画

## 研究テーマ / 目的
- Ye & van Nes (2013) の論文を再現し、その分析手法を習得する  
- 来春までに自分の都市（麻生区）に応用し、卒論に活かす  

## 背景
- 新都市 vs 旧都市の成熟度(発展度合)の違いを定量化した先行研究がある  
- まずは論文を完全に再現することで、自分の研究に必要な分析力を身につける  

## 研究の流れ（ロードマップ）
1. **データ収集**  
   - OSM道路、建物、用途データを取得  
2. **Space Syntax解析(街路統合度)⇒DepthmapX**  
3. **Spacematrix（建物密度）とMXI（土地利用多様性）⇒QGISで計算**  
4. **150mグリッドに統合**  
5. **Match Rate計算と可視化**  
6. **自分の都市（麻生区）に応用**

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
- Ye, Y. & van Nes, A. (2013). *Measuring urban maturation processes in Dutch and Chinese new towns: Combining street network configuration with building density and degree of land use diversification through GIS.* **The Journal of Space Syntax**, 4(1), 18–37.  
  [http://www.journalofspacesyntax.org/](http://www.journalofspacesyntax.org/)  
