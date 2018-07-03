# MonacaProgrammingEducation
## サンプル１
* 第四章　データの取得
  * データのインポート
    * 【実習】検索に使うサンプルデータをインポートしましょう
      * [「4_1_データのインポート_sampleData.csv」をダウンロード](https://natsumo.github.io/MonacaProgrammingEducation/4_1_データのインポート_sampleData.csv)
## サンプル２
* 基礎編まとめ　
  * サンプルアプリの準備
    * [「MonacaTapGameApp」をMonacaにインストール](https://monaca.mobi/directimport?pid=5b3a0c3ce788852f56dba6d1)
## サンプル３
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
## サンプル４
* 第八章　会員管理機能
  * ユーザー名・パスワード認証
    * 参考：パスワードの変更について
      * [会員管理 \(Monaca\) : メールアドレス認証 \| ニフクラ mobile backend](http://mb.cloud.nifty.com/doc/current/user/authorize_email_monaca.html#/Monaca/)
      * [method_requestPasswordReset](http://mb.cloud.nifty.com/assets/sdk_doc/javascript/jsdoc/classes/NCMB.User.html#method_requestPasswordReset)
 
## サンプル５
* 第八章　会員管理機能
  * サンプルプロジェクト
     * [「ユーザー名・パスワード認証サンプル」」をMonacaにインストール](https://monaca.mobi/directimport?pid=5b2784d7e78885b569dba6d8)
## サンプル６
* 応用編まとめ
  * サンプルアプリの準備
    * [「MonacaChatApp」をMonacaにインストール](https://monaca.mobi/ja/directimport?pid=5b359d02e78885282fdba6d0)
