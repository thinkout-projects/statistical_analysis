# statistical_analysis
統計各処理のJupyter notebookをまとめています。





### 平均の差について

2群ならWelch t検定

3群ならWelch ANOVA→（有意差ありなら）Games-Howell

コードは[average_compare.ipynb](average_compare.ipynb)に



### 比率の差について

2群ならFisher exact検定

3群ならFisher exact + Hochberg法（p値補正方法）

コードは[ratio_compare.ipynb](ratio_compare.ipynb)に

