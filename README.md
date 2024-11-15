# ISUCON11予選 (PISCON2024)
## 問題に関連するリンク
[ISUCON11 予選当日マニュアル](https://github.com/isucon/isucon11-qualify/blob/main/docs/manual.md#isucondition-%E3%81%B8%E3%81%AE%E3%83%AD%E3%82%B0%E3%82%A4%E3%83%B3)
[ISUCONDITION アプリケーションマニュアル](https://github.com/isucon/isucon11-qualify/blob/main/docs/isucondition.md)
[ISUCON11 予選レギュレーション](https://isucon.net/archives/55854734.html)
[PISCON Portal](https://piscon.trap.jp/dashboard)
[ISUCON初心者向け講習会資料](https://isucon-workshop.trap.show/)

## アプリのディレクトリ構造
/home/isucon/webapp/
├── frontend  # フロントエンドのソースコード
├── go        # Go実装
├── public    # jsやcss、画像データ等の静的ファイル
└── sql       # データベースのスキーマおよび初期化に必要なSQL

## その他ISUCONで使いそうなファイルの場所
/home/isucon/env.sh # 環境変数の設定ファイル
/etc/nginx/nginx.conf # Nginxの設定ファイル
/etc/mysql/mariadb.conf.d/50-server.cnf # MySQLの設定ファイル
/etc/systemd/system/isucondition.go.service # アプリケーションのsystemdサービスファイル