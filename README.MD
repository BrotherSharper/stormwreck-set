# D&D5版用 スターターセット「竜たちの島ストームレック」これだけセット

* **製作者**: Brother Sharp (ディスコード：Brother Sharp#6921)
* **対応dnd5eバージョン**: 3.0.0+

### インストール方法

ワールドタブより「ワールドインストール」を開いて、以下のリンクを入れてください。その後、「依存関係をインストールしますか」と聞かれるので、自動的にインストールを選んでください。環境によってはエラーが多く吐かれるかも知れませんが、正常にインストールされているはずですのでご確認ください。

* 本体v10： https://github.com/BrotherSharper/stormwreck-set/releases/download/1.5/world.json
* 本体v11： https://github.com/BrotherSharper/stormwreck-set/releases/download/2.2/world.json

どれを入れたら良いかわからない人は大きい方のvのものを入れてください。

### バージョン移行
v10からv11へ移行する場合、いくつかのMod構成が違います。v10を残したままアップデートしても動かない可能性が高いです。**v10のワールドをバックアップしてから削除し、v11のものを入れてください。**

V11からは互換性が厳しくチェックされるようになったので、ワールドのバージョンが赤く光って開けない場合は、以下のモッドが全部入っているかをチェックしてください。

### 内容
「竜たちの島ストームレック」を遊ぶためのマップ、無料の範囲のクリーチャーデータとアイテム、作者の好みでNPCたちの画像等をいれたものです。
Modをいくつか依存関係として指定してあるので「とりあえずこれだけありゃ大丈夫っしょ」というModたちを選出しました。

* コマは自分でキャラクター一覧からドラッグ＆ドロップして配置してください。敵のHPなどは自動的にロールされ、個体差が出るようになってます。
* 竜の安らぎのNPCたちはルナラを除きどうせ戦わないのでデータは入れてないです。
* FVTTのサンプルキャラは入れてますので、自分でストームレックのキャラを再現するか、その背景をサンプルキャラに適用してください。
* BGMおよびほぼすべての主要な攻撃の効果音が入ってます。効果音がなるには必ずALT+クリックでターゲットを取った状態で攻撃などを行う必要があります。

### 同封Mod
* Automated Animations：攻撃や特徴を使うとアニメーションを表示するためのモッド。スターターセットのキャラクターとモンスターのいくつかの特徴にはそのまま反応するはずです。反応するにはAltキー＋クリックでターゲットしている必要があります。
* Action HUD Core：キャラが行えるアクションなどをショートカットバー風に表示してくれます。これはベースとなるModであり、続くD&D5版のものがシステム固有の機能を追加します。Theatre Insertsと併用するとエラーが出ますが動作に問題は無いです。
* Action HUD D&D 5e: D&D固有のUIを実装するもの。
* Babele：日本語化に必要なもの。
* (v11のみ)Carousel Combat Tracker：戦闘になると画面上部にイニシアチブ表を出すものです。
* (v11のみ)Custom Compendium Banners：V11から辞典に背景画像が追加され、視認性が悪化しました。これを今のワールドの設定のまま入れると、従来どおりになります。
* Combat Booster：ターンマーカーや前に使った攻撃や特徴をコマを右クリックすると下に表示してくれる便利なやつ。
* Combat-enhancements：戦闘タブでHPを見えやすくしたり、ドラッグ＆ドロップで順番を入れ替えられるようにしてくれます。
* Dice So Nice：3Dダイス。等倍になってるので、テンポを早くしたい場合は設定から3倍速等にしてください。
* Dice Tray：チャットの下にクリックするだけでダイスをロールするためのパネルをおいてくれます。+ - ボタンで修正値も入れることができます。即席のロールでご利用ください。
* Dynamic effects Using Active Effects：自動化に必要なもの。
* Drag Ruler：コマを持ち上げると、どこまで移動できるかを緑（通常）、黄色（早足）、赤（不可能）で教えてくれます。
* FXMaster：雨や霧などの特殊な効果を表示するためのMod。GMツールの左側に魔法のステッキのアイコンからアクセスできます。
* Token Magic FX：テンプレートツール等に特殊効果を付与したり、コマにエフェクトを追加するマクロが使えるようになります。
* JB3A - Free content：アニメーションModが使うアニメーションが入ってる。
* lib - Color Settings：他のModが使う。
* libWrapper：他のModが使う。
* Monks Token Bar: キャラクターのアイテムのショートカットを表示したり、PLがセーヴを行う時、プロンプトを表示してくれます。
* Metron：単位変換Mod。新しい特徴やアイテムを入れた時、ウィンドウの右上の「単位変換」ボタンをクリックするとヤード・ポンド法からメートル法にしてくれます。レベルアップ後にもらった特徴や呪文に使ってあげる必要があります。
* Midi-Qol：自動化Mod。Altキー＋左クリックでターゲットした状態で攻撃を行うと自動的に判定とダメージ適用をしてくれます。セーヴの場合はGMが自動で、PLは30秒以内にキャラシから行う必要があります。集中も自動的にセーヴを求めてきます。
* (v11では不要)Ownership Viewer：権限を可視化してくれます。虹色：全員、単色：その色のPL、ダイヤ：限定的、四角：閲覧者、円形：所有者。例えば虹色＋円形であれば「全員がこのキャラの所有権を持っているよ」を教えてくれます。v11にはまだ対応してないので、対応したらここに追加する。
* Sequencer：他のModが使う。
* Smart Target：Alt＋クリックで別のターゲットを選ぶと、切り替えてくれます。複数選択するにはShift＋Alt＋クリックが必要です。死亡したキャラは自動的にターゲットを外してくれます。
* Splatter：血糊Mod。そのままで動くはずです。
* Tidy5e Sheet：かっちょいいキャラシの見た目になる。アイテム、呪文、特徴などは右クリック→お気に入り登録すると能力値タブに出てきてほしいものだけを使えるようになります。
* (v11では不要)Token Mold：マップに敵のコマを置いた時はランダムな名前をつけてくれる。敵のHPをロールしてくれる。ネームドは除外。V11からはこれをコマ個別で設定できるようになりました。HPの自動ロールだけまだ代用先が未定なので、場に出した後、キャラシを開いて、HPバーのダイスアイコンをクリックしてください。
* Permission Viewer: キャラクターや資料の権限がどうなっているのかを視覚的に表示してくれます。
* Convenient Effects：状態異常などを手軽に設定できるモッドです。日本語のものはいくつかすでに入ってます。
* 日本語化Modも各種入ってます。

#### 注意
この中にはスターターセットを遊ぶために、無料の範囲でかき集められるマップ、データをおいたものです。シナリオは一切貼ってないので、遊ぶには実際の商品を購入する必要があります。

いくつかの敵データはこちらから開示できないので、空のキャラシを自分で記入してみてください。FVTT初心者はここでFVTTに慣れるチャンスです。

#### Modが邪魔な場合
インストールするときにお勧めModを一緒に入れるには「依存関係」として登録する必要があります。この場合、要らないものをオフにできなくなります。worlds/stormwreck-set/world.jsonを開いて、requiresの中身を消してください。

### 不具合？
オンセ工房サーバまたはツイッターのDMでご連絡ください。テストはしたつもりですが、他人の環境ではどう動くかはまだ不明瞭なことが多いです。

### クレジット
マップ：
* https://www.reddit.com/r/battlemaps/comments/wrm4i1/dragons_of_stormwreck_isle_maps/
* https://www.reddit.com/r/DnD/comments/fk8vqv/oc_art_a_beach_battlemap_i_drew_as_my_players/

立ち絵：
niji journey（AI生成）

音声：

不協和世界
https://www.discoseum.com/user-policy

Wingless-seraph
https://wingless-seraph.net/en/material-riyoukiyaku_eng.html

m-art
https://mart.kitunebi.com/info.html

その他：
This world is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC.