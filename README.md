 # Scraping Books Example


このリポジトリは、Python（requests + BeautifulSoup + pandas）を使った
スクレイピングの練習用プロジェクトです。

## 内容


- ECサイト(https://books.toscrape.com) の書籍データ（カテゴリ、タイトル、価格）を取得
- データを整形してCSVに保存
- pandasでカテゴリごとの平均・中央値を集計
- matplotlibで可視化（棒グラフ作成)

## 実行方法


1. リポジトリをクローン
   1. リポジトリをクローン
```bash
git clone https://github.com/mitaka0927/Scraping.git
cd Scraping



2. 必要なライブラリのインストール 
   pip install -r requirements.txt

3. Jupyter Lab / Notebook を起動してノートブックを開く

成果例

- CSV ファイル（./csv/books_price_data.csv）に書籍の価格情報を出力
- CSV ファイル（./csv/books_price_ave_med_data.csv）に書籍の平均・中央値を出力

- カテゴリごとの平均・中央値棒グラフ

