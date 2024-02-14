# misskey-note-reaction-viewer-plugin
特定のノートにリアクション・リノートをつけたユーザーの一覧を簡易に表示するMisskeyプラグインです。
[AiScript](https://github.com/syuilo/aiscript/tree/master)によって記述されています。

## 使い方

- 該当のノートの`･･･`メニューからプラグインボタン`リアクション詳細`を選択すると、リアクション・リノートを取得し、ダイアログウインドウで表示します。

![image](images/image_001.jpg)

## 導入

1. [`release`](https://github.com/hatopopvr/misskey-note-reaction-viewer-plugin/releases)から`MisskeyNoteReactionViewer.is`をダウンロードします。
2. ダウンロードした内容を全てコピーします。
3. Misskeyの`設定 > プラグインのインストール`のテキストエリアに貼付けます。
4. `インストール`ボタンを押します。

###  カスタムCSSでのダイアログの表示修正
以下は、ダイアログのテキスト表示を左詰めにしてウインドウサイズを変更するカスタムCSSです。
デフォルトではテキストは中心揃えで、ウインドウ最大サイズが小さいため、作者は変更して利用しています。
数値は自環境に合わせて適切に調整してください。
```css
.xa5A4 {
    min-width: 320px;
    max-width: 2000px;  /* original 480px; */
    box-sizing: border-box;
    text-align: left; /* original center; */
}
```

## 作者
[@hatopop_vr@misskey.io](https://misskey.io/@hatopop_vr)