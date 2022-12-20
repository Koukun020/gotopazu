<h1>ios/android向けアプリ 五等分の花嫁 五つ子ちゃんはパズルを五等分できない。</h1>

各URL
apiURL:https://www-cancer.enish-games.com/v{$version}/<br>
AssestBundleURL:https://www-cancer.enish-games.com/v{$version}/resource/list/{Ios or Android}<br>
assestURL:https://assets.enish-games.com/assets-cancer/Resources/{ios or android}/{$name}<br>
assetsAFSurl:https://assets.enish-games.com/assets-cancer/Resources/share/{$name}<br>
<br>
2022-12-15 10:33:55 : $version = "1_33_426"
<br>
<h2>各jsonの説明</h2>
各jsonのkeyは適当にそれらしいものをつけただけです。実際の所は不明です。
<h3>AssestBundle</h3>
　nameがないもの：ツールで変換に失敗したもの 実際にはファイルはあると思われます<br>
　sizeがないもの：CRID usm映像ファイル<br>
　idが50からはじまるもの：ACB/AFS 音声ファイル assetsAFSurlの方　hcaの暗号化なし<br>
　　末尾が0:acbファイル 1:awbファイル<br>
　その他：UnityFS　画像など<br>
　<br>
　リストの元はiosの方ですが、一部androidも混ぜてあります。403でアクセスできない場合はandroidの方にアクセスしてください。
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
  titleid,infoidは下のgachainfoと連動<br>
<h3>gachainfo</h3>
　1文字目が1がガチャタイトル<br>
　1文字目が3がガチャ説明文<br>
　idは上のgachaと連動<br>
<h3>homecharatext</h3>
　ホーム画面のセリフ一覧かと思ったけどどうやらちがうっぽい<br>
　現在調査中<br>
<h3>homework</h3>
　宿題<br>
<h3>item</h3>
　アイテム一覧<br>
　末尾が1が名前、2が説明<br>
<h3>login</h3>
　ログインボーナス<br>
<h3>maintenance</h3>
　メンテナンス時にapiから帰ってきたエラー文の一覧です<br>
<h3>notifications</h3>
　お知らせ<br>
　intXはフラグ系だと思われる、現在調査中<br>
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

<h2>event/FromScripts/<イベントID></h2>
イベントのシナリオデータです<br>
　01:プロローグ<br>
　02:エピローグ<br>
　X1:第X話 前編<br>
　X2:第X話 後編<br>
