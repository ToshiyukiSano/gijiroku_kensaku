# gijiroku_kensaku

## search_text/

### search_text.ipynb

テキスト中から、指定したキーワードのある行を抽出し、その前後の行をひとまとめにして出力する。
入力テキストは、hiraya_whisper_medium.txt

### search_text_with_time.ipynb

時間情報入りのテキスト中から、指定したキーワードのある行を抽出し、その前後の行をひとまとめのブロックにして出力する。
そのブロックの開始時刻と終了時刻も併せて出力する。
入力テキストは、largev3_平屋建築.txt

## sort_words/

テキストファイルを読み込み、janomeで形態素解析を行い、出現頻度を求め、出現頻度の高い順に出力する。
