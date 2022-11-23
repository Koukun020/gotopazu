<h1>ios/android向けアプリ 五等分の花嫁 五つ子ちゃんはパズルを五等分できない。</h1>

各URL
apiURL:https://www-cancer.enish-games.com/v{$version}/<br>
AssestBundleURL:https://www-cancer.enish-games.com/v{$version}/resource/list/{Ios or Android}<br>
assestURL:https://assets.enish-games.com/assets-cancer/Resources/{ios or android}/{$name}<br>
assetsAFSurl:https://assets.enish-games.com/assets-cancer/Resources/share/{$name}<br>
<br>
2022-11-17 10:30:59 : $version = "1_31_426"
<br>
<h2>各jsonの説明</h2>
各jsonのkeyは適当にそれらしいものをつけただけです。実際の所は不明です。
<h3>AssestBundle</h3>
　nameがないもの：現段階で不明<br>
　　　　　　　　　suの内容は意味ないです<br>
　sizeがないもの：CRID usm映像ファイル<br>
　idが50からはじまるもの：ACB/AFS 音声ファイル assetsAFSurlの方　hcaの暗号化なし<br>
　その他：UnityFS　画像など<br>
<h3>campain</h3>
　懸賞応募ページ<br>
　su1とsu2は現段階で不明<br>
<h3>challenge</h3>
　チャレンジ一覧<br>
<h3>degree</h3>
　称号<br>
<h3>eventop</h3>
　イベント開始時のらいはのセリフ<br>
　idはイベントID<br>
<h3>gacha</h3>
　ガチャ一覧<br>
  infoidは下のgachainfoと連動<br>
<h3>gachainfo</h3>
　ガチャ説明？<br>
<h3>item</h3>
　アイテム一覧<br>
　末尾が1が名前、2が説明<br>
<h3>login</h3>
　ログインボーナス<br>
<h3>reward</h3>
　プレゼント<br>
<h3>shop</h3>
　課金一覧<br>
<h3>skill</h3>
　スキル説明一覧<br>
<h3>stamp</h3>
　スタンプ一覧<br>
<h3>text</h3>
　各説明テキスト<br>
