# folium-map-trial

警察庁より公開されている、「交通事故統計情報のオープンデータ」を地図上に表示してみた
- https://www.npa.go.jp/publications/statistics/koutsuu/opendata/index_opendata.html

本件では上記のうち、「２０２２年（令和４年）」のデータを利用している
- https://www.npa.go.jp/publications/statistics/koutsuu/opendata/2022/opendata_2022.html
  - 各種コード表（PDF形式／xlsx形式）
    - https://www.npa.go.jp/publications/statistics/koutsuu/opendata/2022/codebook_2022.pdf
  - 本票_01-12月（csv形式：61.3MB）
    - https://www.npa.go.jp/publications/statistics/koutsuu/opendata/2022/honhyo_2022.csv

ここでは、python folium ライブラリを利用して生成した html ファイルのみを置いている
