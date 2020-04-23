# statistical_analysis
統計各処理のJupyter notebookをまとめています。



# 背景の比較について

### 平均の差について

コードは[average_compare.ipynb](average_compare.ipynb)に

2群ならWelch t検定

3群ならWelch ANOVA→（有意差ありなら）Games-Howell

### 比率の差について

コードは[ratio_compare.ipynb](ratio_compare.ipynb)に

2群ならFisher exact検定

3群ならFisher exact + Hochberg法（p値補正方法）



# 結果のCIの算出方法

コードは[result_analysis.ipynb](result_analysis.ipynb)に

### 2クラス分類

1) AUC <br>
2) ROC曲線 <br>
3) 感度・特異度 (over01 > 0.5と実際の回答で比較) <br>

### 多クラス分類

1) AUC
2) ROC曲線
3) 感度・特異度 (AIの回答と実際の回答で比較)
4) 各クラスの正答率のCI
5) クロス集計表
6) Color map

### 回帰

1) plot
2) 相関係数