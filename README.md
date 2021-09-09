## Name
音楽再生アプリ

## Features
firebaseをしようして音楽をアップロードして再生

## Usage 
* login.htmlにてログイン認証
* 曲の情報をデータをアップロード
* リロードして曲がアップロードされていることを確認(曲をfirebase storageにアップロードはできているがstorageから再生できていないため仮で曲データが入っている)

## Author
* 小野寺剣人
* ジーズアカデミーDev21
 
## Reference
*ログイン認証(長友さん)
>https://blog.katsubemakito.net/firebase/firebase-authentication-email-web1

*firestore
>https://firebase.google.com/docs/firestore?hl=ja

*strage
>https://kido0617.github.io/js/2019-12-01-firebase-form-upload/
>https://proengineer.internous.co.jp/content/columnfeature/5845#23

## Postscript
音楽に関わるプロダクトを卒制で作りたいので今回firebaseを使用してspotyfyをイメージした音楽配信アプリを作成。

### 今回の課題で特に勉強になったこと
* firebase Auth
* firebase firestore
* firebase storage
* エラーに対する対処方法

今回の課題で特に勉強になったのはどこでなんの値が取得できているのかをconsole.logで都度確認しながら進めていった。
「この値が取れているってことは？」みたいな考え方ができるようになったことでパズルのように組み合わせて課題がどんどん出来上がっていくのが非常に楽しかった。

