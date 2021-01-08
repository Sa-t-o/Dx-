# Python課題3

## 概要
セラクのサイトにアクセスし、[「セラクのサービス」](https://www.seraku.co.jp/service/)ページよりデータを抽出し、加工してください。\
抽出するデータと加工方法は次の条件に従ってください。

### 条件
- サービス名
- サービス分野（Dx又はSIのどちらか）
- 抽出したデータをCSVファイルとして保存する
- 保存するファイル名は「scraped-seraku-services.csv」とする
- CSVファイルの保存場所は、このPythonプログラムと同じフォルダとする
- 保存先に同じがファイルが存在する場合は、上書き保存すること
- CSVファイルの1行目はヘッダー行とする
- ヘッダーは、「サービス分野, サービス名」とする
- CSVファイルのエンコーディングはUTF-8であること