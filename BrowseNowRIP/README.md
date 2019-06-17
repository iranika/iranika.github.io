# BrowseNowRIP

## What is this?

これは [BrowseNow](https://github.com/kamaboko123/BrowseNow)のブックマークレットオンリー実装です。  
[Twitter公式のシェア用URL](https://twitter.com/intent/tweet)に依存しています。  
サーバなどは不要です。  

## How to use

1. 下記リンクをブラウザのブックマークバーにドラッグ・アンド・ドロップして、ブックマーク登録します。  
<a href="javascript: (function (e) { window.open('https://twitter.com/intent/tweet?' + 'hashtags=BrowseNowRIP&text=' + e(document.title) + '(' + e(location.href) + ')', null, 'width=520,height=500'); })(encodeURIComponent);">BrowseNowRIP</a>  

1. 共有したいページでブックマークをクリックすると、Twitterの投稿フォームに遷移してつぶやくことができます。  
ブラウザでTwitterにログインしていない場合は、遷移先の右上からログインしてください。  

NOTE: ドラッグ・アンド・ドロップでブックマーク登録できないブラウザの場合以下をブックマークバーに登録してください。

``` js
javascript: (function (e) { window.open('https://twitter.com/intent/tweet?' + 'hashtags=BrowseNowRIP&text=' + e(document.title) + '(' + e(location.href) + ')', null, 'width=520,height=500'); })(encodeURIComponent);
```

## FAQ

* Q. 推奨ブラウザは？  
A .最新版のGoogle Chromeです。その他の環境では動作確認していません。

## Contact

不具合やお問い合わせは以下にお願いします。

* Twitter:いらにか([@happy_packt](https://twitter.com/happy_packet))
* Github Issue：[iranika/BrowseNowRIP](https://github.com/iranika/BrowseNowRIP/issues)
