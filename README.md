# MonacaProgrammingEducation
## リンク集

* 第四章　データの取得
  * データのインポート
    * 【実習】検索に使うサンプルデータをインポートしましょう
      * [「4_1_データのインポート_sampleData.csv」をダウンロード](https://natsumo.github.io/MonacaProgrammingEducation/4_1_データのインポート_sampleData.csv)
* 基礎編まとめ　
  * サンプルアプリの準備
    * [「MonacaTapGameApp」をMonacaにインストール](https://monaca.mobi/directimport?pid=5b1105e1e788850674dba6d4)

* 第八章　会員管理機能
  * 参考：パスワードの変更について
     * [会員管理 \(Monaca\) : メールアドレス認証 \| ニフクラ mobile backend](http://mb.cloud.nifty.com/doc/current/user/authorize_email_monaca.html#/Monaca/)
     * [method_requestPasswordReset](http://mb.cloud.nifty.com/assets/sdk_doc/javascript/jsdoc/classes/NCMB.User.html#method_requestPasswordReset)
 
```js
// メールアドレス認証ユーザの登録メールアドレス宛にパスワード再設定のメールを送信
ncmb.User.requestPasswordReset()
         .then(function(){
             /* 再設定メール送信成功時の処理（例） */
             console.log("再設定メール送信成功");
         })
         .catch(function(error){
             /* 再設定メール送信失敗時の処理（例） */
             console.log("再設定メール送信失敗:" + JSON.stringify(error));
         });
```
