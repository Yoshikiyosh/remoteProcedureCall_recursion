"# remoteProcedureCall_recursion" 

JSON RPCサーバおよびクライアント
このプロジェクトは、JSON RPC（Remote Procedure Call）のサーバとクライアントの簡単な実装を提供します。サーバは指定されたメソッドを実行し、結果をJSON形式で返します。クライアントはサーバにリクエストを送信し、レスポンスを受信します。

インストール
特別な依存関係は必要ありません。Python 3.xおよびNode.jsが必要です。

使用方法
サーバを起動します。
bash
Copy code
python server.py
クライアントを実行して、サーバにリクエストを送信します。
bash
Copy code
node client.js
サーバ
サーバは指定されたホストとポートで待機し、リクエストを受信して処理します。サポートされているメソッドは現在、subtractのみです。リクエストはJSON形式で送信され、メソッド名とパラメータが含まれます。サーバはリクエストを処理し、結果をJSON形式で返します。

メソッド
subtract(params: List[int]): パラメータのリストから2番目の要素を1番目の要素から減算し、結果を返します。
クライアント
クライアントは指定されたホストとポートに接続し、リクエストをサーバに送信します。クライアントはJSON形式のリクエストを作成し、サーバからのレスポンスを待機します。

ライセンス
このプロジェクトはMITライセンスのもとで公開されています。詳細については、LICENSEファイルを参照してください。


