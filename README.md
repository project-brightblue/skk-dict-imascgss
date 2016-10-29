# skk-dict-imascgss

アイドルマスターシンデレラガールズ スターライトステージ SKK辞書

「デレステの話が捗る辞書」を目指しているSKK辞書です。現在はデレステに実装済のアイドルの名前が収録されていますが、将来的に辞書内容の拡張を検討しています(#3)。  
元が作者の個人用辞書のため、

* メンテナンスの都合によりソートしていません。多くのSKK実装はソートされていない辞書を追加しても正常に動作します。
* スターライトステージに実装されていないアイドルの名前は収録されていません。

ので、あらかじめご了承ください。

## ダウンロード

[master.zip](https://github.com/mlny/skk-dict-imascgss/archive/master.zip)

もしくはgitがインストールされている環境で

```
$ git clone https://github.com/mlny/skk-dict-imascgss.git
```

## つかいかた

### [SKK日本語入力FEP](http://coexe.web.fc2.com/programs.html)

```
C:\Windows\IME\SKK0\DICTS
```
の下に辞書をコピーします。

### [AquaSKK](https://github.com/codefirst/aquaskk)

1. 設定画面を開き、辞書タブを開きます。
2. 追加 を押します。
3. 辞書の種類をSKK 辞書(EUC-JP)にします。
4. 場所の選択... を押し、ダウンロードした辞書を選択します。
5. codefirst版AquaSKKを使用していない、もしくはAquaSKK 4.4.0以前のバージョンをお使いの場合、「場所」の先頭にある*file:/*を削除します(この挙動は[AquaSKK 4.4.1で修正されました](https://github.com/codefirst/aquaskk/issues/55))。

### ibus-skk

ibus-skkの設定画面を開き、辞書タブ内でダウンロードした辞書をシステム辞書として追加すると辞書が使用できるようになります。

## ライセンス

[MIT License](https://github.com/mlny/skk-dict-imascgss/blob/master/LICENSE)

## Special Thanks(敬称略)

* mzp( [@mzp](https://twitter.com/mzp) )
* ばんじゅん( [@banjun](https://twitter.com/banjun) )

・・・上の2名には辞書作成時にTwitterで助言を頂きました。