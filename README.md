# Town Of Host

[English](https://github.com/tukasa0001/TownOfHost/blob/main/README-EN.md)

[![TownOfHost-Title](./Images/TownOfHost-Title.png)](https://youtu.be/IGguGyq_F-c)

<p align="center"><a href="https://github.com/tukasa0001/TownOfHost/releases/"><img src="https://badgen.net/github/release/tukasa0001/TownOfHost"></a></p>

## この Mod について

この Mod は非公式のものであり、この Mod の開発に関して Among Us の開発元である"Innersloth"は一切関与していません。<br>
この Mod の問題などに関して公式に問い合わせないでください。<br>

[![Discord](./Images/TownOfHost-Discord.png)](https://discord.gg/W5ug6hXB9V)

## リリース

AmongUsバージョン : **2022.12.14**

**最新版は[こちら](https://github.com/tukasa0001/TownOfHost/releases/latest)**

過去バージョンは[こちら](https://github.com/tukasa0001/TownOfHost/releases)

## 特徴

この Mod はホストのクライアントに導入するだけで動作し、他のクライアントの Mod の導入/未導入及び端末の種類に関係なく動作します。<br>
また、カスタムサーバーを利用した Mod と違い、URL やファイル編集などによるサーバー追加も不要なため、ホスト以外のプレイヤーは Town Of Host を導入したホストの部屋に参加するだけで追加役職を楽しむことができます。<br>

しかし、以下の制限が発生することにご注意ください。<br>

- ホストが途中抜けをするなどの要因でホストが変更された場合、追加役職に関する処理が正常に動作しない可能性がある。

なお、ホスト以外のプレイヤーがこの Mod を導入した状態でプレイすると、以下のような変更が行われます。<br>

- 特殊役職独自の開始画面の表示
- 特殊役職の正常な勝利画面の表示
- 設定項目の追加
- その他

## 機能
### ホットキー

#### ホストのみ
| キー                | 機能                         | 使えるシーン     |
| ------------------- | ---------------------------- | ---------------- |
| `Shift`+`L`+`Enter` | 廃村                         | ゲーム内         |
| `Shift`+`M`+`Enter` | ミーティングをスキップで終了 | ゲーム内         |
| `Ctrl`+`N`          | 現在の設定を表示             | ロビー&ゲーム内  |
| `Ctrl`+`Shift`+`N`  | 有効な設定の説明を表示       | ロビー&ゲーム内  |
| `C`                 | ゲーム開始を中断             | カウントダウン中 |
| `Shift`             | ゲームを即開始               | カウントダウン中 |
| `Ctrl`+`右クリック` | クリックしたプレイヤーを処刑 | 会議画面         |

#### MODクライアントのみ
| キー        | 機能                                                                          | 使えるシーン    |
| ----------- | ----------------------------------------------------------------------------- | --------------- |
| `Tab`       | オプション一覧のページ送り                                                    | ロビー          |
| `Ctrl`+`F1` | ログをデスクトップに出力                                                      | どこでも        |
| `F10`       | AmongUsのフォルダを開く                                                       | どこでも        |
| `F11`       | 解像度を変更<br>480x270 → 640x360 → 800x450 → 1280x720 → 1600x900 → 1920x1080 | どこでも        |
| `T`+`F5`    | カスタム翻訳ファイルのリロード                                                | どこでも        |
| `Alt`+`C`   | 現在の設定のテキストをコピー                                                  | ロビー&ゲーム内 |
| `Ctrl`+`C`  | 文章をコピー                                                                  | チャット        |
| `Ctrl`+`V`  | 文章を貼り付け                                                                | チャット        |
| `Ctrl`+`X`  | 文章を切り取り                                                                | チャット        |
| `↑`         | チャット送信履歴を過去に遡る                                                  | チャット        |
| `↓`         | チャット送信履歴を未来に遡る                                                  | チャット        |

### チャットコマンド
チャットコマンドはチャットで入力して使用できるコマンドです。

#### ホストのみ
| コマンド                                 | 機能                                                |
| ---------------------------------------- | --------------------------------------------------- |
| /winner<br>/win                          | 勝者を表示                                          |
| /rename <名前><br>/r <名前>              | 名前を変更                                          |
| /dis <crewmate/impostor>                 | 試合をクルーメイト/インポスターの切断として終了する |
| /messagewait <秒><br>/mw <秒>            | メッセージの表示間隔の秒数を設定                    |
| /help<br>/h                              | コマンドの説明を表示                                |
| /help roles <役職><br>/help r <役職>     | 役職の説明を表示                                    |
| /help addons <属性><br>/help a <属性>    | 属性の説明を表示                                    |
| /help modes <モード><br>/help m <モード> | モードの説明を表示                                  |
| /hidename <文字列><br>/hn <文字列>       | コード隠しの名前を変更                              |
| /say <文字列>                            | ホストとしてアナウンスをする                        |

#### MODクライアントのみ
| コマンド       | 機能                                |
| -------------- | ----------------------------------- |
| /dump          | ログをダンプ                        |
| /version<br>/v | 全MODクライアントのバージョンを表示 |

#### 全クライアント
| コマンド                      | 機能                       |
| ----------------------------- | -------------------------- |
| /lastresult<br>/l             | 試合結果を表示             |
| /now<br>/n                    | 現在の設定を表示           |
| /now roles<br>/n r            | 現在の役職設定を表示       |
| /help now<br>/help n          | 有効な設定の説明を表示     |
| /template <タグ><br>/t <タグ> | タグに対応した定型文を表示 |
| /myrole<br>/m                 | 自分の役割の説明を表示     |

### テンプレート
定型文を送信できる機能です。<br>
`/template <タグ>`もしくは`/t <タグ>`で呼び出すことができます。<br>
定型文を設定するにはAmongUs.exeと同じフォルダの`./TOH_DATA/template.txt`を編集します。<br>
`タグ:内容`のようにコロンで区切って記載します。<br>
また、`タグ:こんなふうに\n改行できます`のように文章中に`\n`を書くと改行できます。<br>

#### ウェルカムメッセージ
テンプレート機能でタグを「welcome」に設定するとプレイヤー参加時に自動で送信されます。<br>
例: `welcome:この部屋はTownOfHostを使用しています。`

#### 変数展開
`{{変数名}}`のように文章中に記載することで、呼び出し時に変数の中身を展開することができます。<br>
例: `roomcode:この部屋はのルームコードは{{RoomCode}}です`

| 変数名               | 内容                       |
| -------------------- | -------------------------- |
| RoomCode             | ルームコード               |
| PlayerName           | ホストのプレイヤー名       |
| AmongUsVersion       | 本体バージョン             |
| ModVersion           | MODバージョン              |
| Map                  | マップ名                   |
| NumEmergencyMeetings | 緊急会議ボタン数           |
| EmergencyCooldown    | 緊急会議ボタンクールダウン |
| DiscussionTime       | 議論時間                   |
| VotingTime           | 投票時間                   |
| PlayerSpeedMod       | プレイヤー速度             |
| CrewLightMod         | クルー視界                 |
| ImpostorLightMod     | インポスター視界           |
| KillCooldown         | キルクールダウン           |
| NumCommonTasks       | コモンタスク数             |
| NumLongTasks         | ロングタスク数             |
| NumShortTasks        | ショートタスク数           |
| Date                 | 日付                       |
| Time                 | 時間                       |

### カスタム翻訳ファイル
ユーザーが自由に独自の翻訳を作成して使用することができます。<br>
- Among Usフォルダの中に『Language』フォルダが作成されているので開きます。
- フォルダ内に`{言語名}.dat`というファイルを作成します。
  - 例: Japanese.dat
  - `template.dat`または`template_English.dat`を名前変更して使用することもできます。
- ファイル内に`翻訳前:翻訳後`のように記載します。
  - 例: Command.rename:ホストの名前を変更
  - `翻訳前`の文字列は`template.dat`を参照してください。

また、`T`+`F5`を押すことで翻訳をリロードできます。

#### 有効言語一覧

| 言語名     |
| ---------- |
| English    |
| Latam      |
| Brazilian  |
| Portuguese |
| Korean     |
| Dutch      |
| Filipino   |
| French     |
| German     |
| Italian    |
| Japanese   |
| Spanish    |
| SChinese   |
| TChinese   |
| Irish      |

### BAN機能
ホストはゲーム中でも他プレイヤーの投票を必要とせずBANを行うことができます。<br>
また、BANを行うとそのプレイヤーは以後あなたのホストする部屋に入室できなくなります。<br>
BANされたプレイヤーは`./TOH_DATA/BanList.txt`に`フレンドコード,プレイヤー名`のように記録されており、該当の行を削除することでBANを解除することができます。<br>
フレンドでブロックした場合も自動的にBANを行います。<br>

### キック機能
ホストはゲーム中でも他プレイヤーの投票を必要とせずキックを行うことができます。<br>

### 名前フィルター
`./TOH_DATA/DenyName.txt`に禁止したい名前を記載することで、一致した名前のプレイヤーは自動的にキックされます。<br>
[正規表現](https://weblabo.oscasierra.net/tools/regex/)で指定することができ、1行ずつ順番に判定されます。<br>

例:
| 指定文字 | 一致する名前                                    | 備考                               |
| -------- | ----------------------------------------------- | ---------------------------------- |
| 部屋主   | `部屋主` `MOD部屋主` `部屋主TOH` `MOD部屋主TOH` | 一部に`部屋主`が含まれていれば一致 |
| ^部屋主  | `部屋主MOD` `部屋主TOH` `部屋主TEST`            | 先頭に`部屋主`とついていれば一致   |
| 部屋主$  | `MOD部屋主` `TOH部屋主` `TEST部屋主`            | 末尾に`部屋主`とついていれば一致   |
| ^部屋主$ | `部屋主`                                        | `部屋主`に完全一致                 |

## 役職

| インポスター陣営                                                     | クルーメイト陣営                                            | 第三陣営                                                    | その他    |
| -------------------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- | --------- |
| [バウンティハンター](#BountyHunterバウンティハンター)                | [ベイト](#Baitベイト)                                       | [アーソニスト](#Arsonistアーソニスト)                       | [GM](#GM) |
| [イビルトラッカー](#EvilTrackerイビルトラッカー)                     | [ディクテーター](#Dictatorディクテーター)                   | [エゴイスト](#Egoistエゴイスト)                             |           |
| [イビルウォッチャー](#Watcherウォッチャー)                           | [ドクター](#Doctorドクター)                                 | [エクスキューショナー](#Executionerエクスキューショナー)    |           |
| [花火職人](#FireWorks花火職人)                                       | [ライター](#Lighterライター)                                | [ジャッカル](#Jackalジャッカル)                             |           |
| [メアー](#Mareメアー)                                                | [メイヤー](#Mayorメイヤー)                                  | [ジェスター](#Jesterジェスター)                             |           |
| [パペッティア](#Puppeteerパペッティア)                               | [ナイスウォッチャー](#Watcherウォッチャー)                  | [恋人](#Lovers恋人)                                         |           |
| [シリアルキラー](#SerialKillerシリアルキラー)                        | [サボタージュマスター](#SabotageMasterサボタージュマスター) | [オポチュニスト](#Opportunistオポチュニスト)                |           |
| [スナイパー](#Sniperスナイパー)                                      | [シーア](#Seerシーア)                                       | [テロリスト](#Terroristテロリスト)                          |           |
| [タイムシーフ](#TimeThiefタイムシーフ)                               | [シェリフ](#Sheriffシェリフ)                                | [シュレディンガーの猫](#SchrodingerCatシュレディンガーの猫) |
| [ヴァンパイア](#Vampireヴァンパイア)                                 | [スニッチ](#Snitchスニッチ)                                 |                                                             |           |  |
| [ウォーロック](#Warlockウォーロック)                                 | [スピードブースター](#SpeedBoosterスピードブースター)       |                                                             |           |
| [魔女](#Witch魔女)                                                   | [トラッパー](#Trapperトラッパー)                            |                                                             |           |
| [マフィア](#Mafiaマフィア)                                           |                                                             |                                                             |           |
| [マッドメイト](#Madmateマッドメイト)                                 |                                                             |                                                             |           |
| [マッドガーディアン](#MadGuardianマッドガーディアン)                 |                                                             |                                                             |           |
| [マッドスニッチ](#MadSnitchマッドスニッチ)                           |                                                             |                                                             |           |
| [サイドキックマッドメイト](#SidekickMadmateサイドキックマッドメイト) |                                                             |                                                             |           |

### GM

GM(ゲームマスター)はオブザーバー役職です。<br>
GMはゲーム自体には何の影響も与えず、すべてのプレイヤーは誰がGMであるかがわかります。<br>
必ずホストに割り当てられ、始めから幽霊状態です。<br>

### BountyHunter/バウンティハンター

陣営 : インポスター<br>
判定 : インポスター<br>

表示されたターゲットをキルした場合、次のキルクールがとても短くなります。<br>
ターゲットではないプレイヤーをキルした場合は、キルクールが伸びてしまいます。<br>
<!--また、設定でキルクールを 2.5 秒に設定する必要があります。<br>-->
ターゲットは一定時間ごとに変更されます。<br>

#### 設定

| 設定名                              |
| ----------------------------------- |
| ターゲット変更時間(s)               |
| ターゲット殺害時のキルクール(s)     |
| ターゲット以外殺害時のキルクール(s) |

### EvilTracker/イビルトラッカー

制作者 : Masami<br>

陣営 : インポスター<br>
判定 : シェイプシフター<br>

追跡能力を持つインポスターです。<br>
インポスターへの矢印が常に表示され、さらにシェイプシフトで選択した一人を追跡することができます。<br>
設定によってはインポスターがキルを行った場合にキルフラッシュを見ることもできます。<br>

- ターゲットは1ターン/1試合に一回設定でき、設定可能時は左向き白三角マーク(◁)が付きます。
- 変身先がインポスター、死亡済みの場合は能力は消費されません。
- 変身クールダウンはターゲット設定可能時は「5秒」、不可時は「255秒」で固定です。
- 変身持続時間は「1秒」で固定されているので、変身能力自体は殆ど使えません。
- オプション次第で[サイドキックマッドメイト](#SidekickMadmate/サイドキックマッドメイト)を指名できます。

#### 設定

| 設定名                                 |
| -------------------------------------- |
| インポスターキル時にフラッシュが見える |
| 会議後に再度ターゲットを設定できる     |
| マッドメイトを指名できる               |

### FireWorks/花火職人

制作・考案者 : こう。<br>

陣営 : インポスター<br>
判定 : シェイプシフター<br>

花火の爆破によって大量キル出来る役職です。<br>
最大3個の花火をシェイプシフトのタイミングで設置出来ます。<br>
すべての花火を設置したら、最後のインポスターとなった時にシェイプシフトのタイミングで一斉起爆します。<br>
花火を設置し始めてから爆破するまでキル出来ません。<br>
自身が爆破に巻き込まれても全滅させることが出来た場合は勝利となります。

#### 設定

| 設定名         |
| -------------- |
| 花火の所持数   |
| 花火の爆発半径 |

### Mare/メアー

制作者 : Kihi,ゆりの,そうくん,しゅー
考案者 : Kihi<br>

陣営 : インポスター<br>
判定 : インポスター<br>

停電時以外にキルをすることができませんが、キルクールが半分になります。<br>
停電中にのみ移動速度も上昇しますが、自分の名前が赤く表示されます。<br>

#### 設定

| 設定名                     |
| -------------------------- |
| 停電時のメアーの加速値     |
| 停電時のメアーのキルクール |

### Puppeteer/パペッティア

陣営 : インポスター<br>
判定 : インポスター<br>

パペッティアのキルはキャンセルされ、キル対象に次に近づいたプレイヤー（インポスターを除く）をキルさせます。<br>
対象がキルした相手がキルされた瞬間に発動するものであった場合、対象にその効果が反映されます。<br>
普通のキルを行うことはできません。<br>

### SerialKiller/シリアルキラー

陣営 : インポスター<br>
判定 : シェイプシフター<br>

自身の命と引き換えにキルクールが短いインポスターです。<br>
一度でもキルをすると自殺タイマーが動き出し、時間までにキルをし続けないと自殺してしまいます。<br>

#### 設定

| 設定名            |
| ----------------- |
| キルクール(s)     |
| 自殺までの秒数(s) |

### ShapeMaster/シェイプマスター

> **Warning**
> 現在使用できません。

制作・考案者 : しゅー<br>

陣営 : インポスター<br>
判定 : シェイプシフター<br>

シェイプマスターは変身後のクールダウンを無視し、再度変身することができます。<br>
通常では 10 秒しか変身できませんが、設定によって変身継続時間を変更することができます。<br>

#### 設定

| 設定名                            |
| --------------------------------- |
| シェイプマスターの変身可能時間(s) |

### Sniper/スナイパー

制作・考案者 : こう。<br>

陣営 : インポスター<br>
判定 : シェイプシフター<br>

遠距離射撃が可能な役職です。<br>
シェイプシフトした地点から解除した地点への延長線上にいる対象をキルします。<br>
射線上のクルーには射撃音が聞こえます。<br>
弾丸を打ち切るまで通常キルは出来ません。<br>

精密射撃モードOFF<BR>
![off](https://user-images.githubusercontent.com/96226646/172194283-5482db76-faab-4185-9898-ac741b132112.png)<br>
精密射撃モードON<BR>
![on](https://user-images.githubusercontent.com/96226646/172194317-6c47b711-a870-4ec0-9062-2abbf953418b.png)<br>

#### 設定

| 設定名         |
| -------------- |
| 所持弾数       |
| 精密射撃モード |

### TimeThief/タイムシーフ

考案者 : みぃー<br>
制作者 : integral, しゅー, そうくん, ゆりの<br>

陣営 : インポスター<br>
判定 : インポスター<br>

プレイヤーをキルすると、会議時間が減少します。<br>
タイムシーフが追放または殺されると、失われた会議時間が戻ってきます。<br>

#### 設定

| 設定名                   |
| ------------------------ |
| 減少する会議時間(s)      |
| 投票時間の下限(s)        |
| 死亡後に盗んだ時間を返す |

### Vampire/ヴァンパイア

陣営 : インポスター<br>
判定 : インポスター<br>

キルボタンを押してから一定時間経って実際にキルが発生する役職です。<br>
キルをしたときのテレポートは発生しません。<br>
また、キルボタンを押してから設定された時間が経つまでに会議が始まるとその瞬間にキルが発生します。<br>
しかし、[ベイト](#Bait/ベイト)をキルした場合のみ通常のキルとなり、強制的に通報させられます。<br>

#### 設定

| 設定名            |
| ----------------- |
| 殺害までの時間(s) |

### Warlock/ウォーロック

陣営 : インポスター<br>
判定 : シェイプシフター<br>

ウォーロックが変身する前にキルすると相手に呪いがかかります。<br>
そして次変身すると、呪った人に一番近い人をキルさせます。<br>
呪いキルの成功または会議を挟むと呪いはリセットされます。<br>

### Witch/魔女

陣営 : インポスター<br>
判定 : インポスター<br>

アクションによりキルモードとスペルモードを切り替え、スペルモードの時にキルボタンを押すとその対象に魔術をかけることができる役職です <br>
ダブルクリックモードではキルボタン1回で魔術、2回連続押しでキルになります。
魔術をかけられたプレイヤーには会議で特殊なマークが付き、その会議中に魔女を追放できなければ死亡してしまいます。<br>

#### 設定

| 設定名               |                                  |
| -------------------- | -------------------------------- |
| モード変更アクション | キル/ベントに入る/ダブルクリック |

### Mafia/マフィア

陣営 : インポスター<br>
判定 : インポスター<br>

初期状態でキルをすることはできません。<br>
マフィアではないインポスターが全員死亡すると、マフィアもキルすることができるようになります。<br>
キルができない状態でもキルボタンはありますが、キルをすることはできません。<br>

### Madmate/マッドメイト

陣営 : インポスター<br>
判定 : エンジニア<br>
カウント : クルー<br>

インポスター陣営に属しますが、マッドメイトからはインポスターが誰なのかはわかりません。<br>
インポスターからもマッドメイトが誰なのかはわかりません。<br>
キルやサボタージュはできませんが、通気口に入ることができます。<br>

### MadGuardian/マッドガーディアン

制作・考案者 : 空き瓶/EmptyBottle<br>

陣営 : インポスター<br>
判定 : クルーメイト<br>
カウント : クルー<br>

インポスター陣営に属しますが、マッドガーディアンからはインポスターが誰なのかはわかりません。<br>
インポスターからもマッドガーディアンが誰なのかはわかりません。<br>
しかし、自身のタスクを全て完了させるとキルされなくなります。<br>
キルやサボタージュはできず、通気口に入ることもできません。<br>

#### 設定

| 設定名                             |
| ---------------------------------- |
| 自身の殺害未遂者を知ることができる |

### MadSnitch/マッドスニッチ

制作・考案者 : そうくん<br>

陣営 : インポスター<br>
判定 : クルーメイトorエンジニア<br>
カウント : クルー<br>

インポスター陣営に属しますが、マッドスニッチからはインポスターが誰なのかはわかりません。<br>
インポスターからもマッドスニッチが誰なのかはわかりません。<br>
タスクを全て完了させるとマッドスニッチからインポスターを認識できるようになります。<br>

#### 設定

| 設定名                       |
| ---------------------------- |
| ベントを使える               |
| インポスターからも視認できる |
| マッドスニッチのタスク数     |

### SidekickMadmate/サイドキックマッドメイト

制作・考案者 : たんぽぽ<br>

陣営 : インポスター<br>
判定 : 変化前の役職<br>
カウント : クルー<br>

この役職はシェイプシフター系の一部役職が変身した際に最も近いプレイヤー（インポスター陣営を除く）が指名されます。<br>
指名できる役職はシェイプシフター、オプション有効時の[イビルトラッカー](#EvilTracker/イビルトラッカー)、[エゴイスト](#Egoist/エゴイスト)です。<br>
インポスター陣営に属しますが、サイドキックマッドメイトからはインポスターが誰なのかはわかりません。<br>
インポスターからもサイドキックマッドメイトが誰なのかはわかりません。<br>


また、マッドメイト系役職共通の設定があります。

| 設定名                                         |
| ---------------------------------------------- |
| マッドメイト系役職が停電を直せる               |
| マッドメイト系役職が通信障害を直せる           |
| マッドメイト系役職がインポスター視界を持つ     |
| マッドメイト系役職にキルフラッシュが見える     |
| マッドメイト系役職に他人の投票先が分かる       |
| マッドメイト系役職に死因が分かる               |
| マッドメイト系役職が追放時クルーを道連れにする |
| マッドメイト系役職のベントクールダウン         |
| マッドメイト系役職のベント内での最大時間       |

### Watcher/ウォッチャー

陣営 : インポスター or クルーメイト<br>
判定 : インポスター or クルーメイト<br>

ウォッチャーは会議中に全員の投票先を見ることができます。<br>

#### 設定

| 設定名                          |
| ------------------------------- |
| イビルウォッチャーになる確率(%) |

### Bait/ベイト

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

キルされたときに、自分をキルしたプレイヤーに強制的に自分の死体を通報させることができる役職です。<br>

### Dictator/ディクテーター

制作・考案者 : そうくん<br>

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

会議中に誰かに投票をすると、会議を強制終了させて投票先を吊る事ができます。<br>
投票したタイミングでディクテーターは死亡します。<br>

### Doctor/ドクター

陣営 : クルーメイト<br>
判定 : 科学者<br>

ドクターはプレイヤーの死因を知ることができ、遠隔でバイタルをみることができます。<br>

#### 設定
| 設定名       |
| ------------ |
| 充電持続時間 |

### Lighter/ライター

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

タスクを完了させると、自分の視界が広がり、停電の視界減少の影響を受けなくなります。<br>

#### 設定

| 設定名                         |
| ------------------------------ |
| タスク完了時の視界             |
| タスク完了時に停電を無効にする |

### Mayor/メイヤー

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

メイヤーは票を複数持っており、まとめて一人のプレイヤーまたはスキップに入れることができます。<br>

#### 設定

| 設定名                           |
| -------------------------------- |
| 追加投票の個数                   |
| ポータブルボタンを持っている     |
| ┗ ポータブルボタンの使用可能回数 |

### SabotageMaster/サボタージュマスター

制作・考案者 : 空き瓶/EmptyBottle<br>

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

サボタージュマスターはサボタージュを早く直すことができます。
原子炉メルトダウンや酸素妨害、MIRA HQ の通信妨害は片方を修理すれば両方が直ります。<br>
停電は 1 箇所のレバーに触れると全て直ります。<br>
Polus や The Airship のドアを開けるとその部屋の全てのドアが開きます。<br>

#### 設定

| 設定名                                   |
| ---------------------------------------- |
| 修理能力を使用できる回数(ドア閉鎖は除く) |
| 1度に複数のドアを開けられる              |
| リアクターに対して能力を使える           |
| 酸素妨害に対して能力を使える             |
| MIRA HQの通信妨害に対して能力を使える    |
| 停電に対して能力を使える                 |

### Seer/シーア

制作者 : Masami<br>

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

プレイヤーの死亡した瞬間が分かります。<br>
視界が一瞬0になり、リアクターサボタージュ中でなければリアクターも一瞬鳴ります（キルフラッシュ）。<br>
ホストの場合は画面が赤くなり、キル音が鳴ります。<br>
キルフラッシュの長さは共通設定で微調整できます（推奨：0.3s~）。<br>

#### 設定

| 共通設定                |
| ----------------------- |
| キルフラッシュの長さ(s) |

### Sheriff/シェリフ

陣営 : クルーメイト<br>
判定 : インポスター(ホストのみクルーメイト)<br>
カウント : クルー<br>

シェリフは人外をキルすることができます。<br>
しかし、クルーメイトをキルした場合、自分が死亡してしまいます。<br>
タスクはありません。<br>

*暗転対策の為、死亡後のシェリフは会議毎に自殺するモーションが本人にだけ見えます。死体は出ません。<br>

#### 設定

| 設定名                                                                                     |
| ------------------------------------------------------------------------------------------ |
| キルクール                                                                                 |
| 誤爆時、ターゲットも死ぬ                                                                   |
| キル可能回数                                                                               |
| 全員生存時にキルできる                                                                     |
| [マッドメイト](#Madmate/マッドメイト)をキルできる                                          |
| 第三陣営をキルできる                                                                       |
| ┣ [アーソニスト](#Arsonist/アーソニスト)をキルできる                                       |
| ┣ [エゴイスト](#Egoist/エゴイスト)をキルできる                                             |
| ┣ [シュレディンガーの猫](#SchrodingerCat/シュレディンガーの猫)(エゴイスト陣営)をキルできる |
| ┣ [ジェスター](#Jester/ジェスター)をキルできる                                             |
| ┣ [オポチュニスト](#Opportunist/オポチュニスト)をキルできる                                |
| ┣ [テロリスト](#Terrorist/テロリスト)をキルできる                                          |
| ┣ [エクスキューショナー](#Executioner/エクスキューショナー)をキルできる                    |
| ┣ [ジャッカル](#Jackal/ジャッカル)をキルできる                                             |
| ┗ [シュレディンガーの猫](#SchrodingerCat/シュレディンガーの猫)(ジャッカル陣営)をキルできる |

### Snitch/スニッチ

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

スニッチはタスクを完了させるとキル可能人外の名前の色が変化し、矢印で方角がわかります。<br>
しかし、スニッチのタスクが少なくなると人外に通知されます。

#### 設定

| 設定名                                       |
| -------------------------------------------- |
| ターゲットを示す矢印が見える                 |
| 矢印の色で陣営がわかる                       |
| 第三陣営のキル可能役職を見つけることが出来る |

### SpeedBooster/スピードブースター

制作・考案者 : よっキング<br>

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

規定のタスク量を完了させると、生存しているランダムなプレイヤーの速度を上げる。<br>

#### 設定

| 設定名                 |
| ---------------------- |
| 加速値                 |
| 効果を発動するタスク数 |

### Trapper/トラッパー

考案者 : 宿主ランニング<br>
制作者 : そうくん<br>

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

キルされると、キルした人を数秒間移動不可にします。<br>
また、拘束中にレポートを行った場合はキャンセルされ、解放後にレポートが行われます。<br>

#### 設定

| 設定名           |
| ---------------- |
| 移動を封じる時間 |

### Arsonist/アーソニスト

陣営 : 第三（単独）<br>
判定 : インポスター<br>
カウント : クルー<br>
勝利条件 : 生存者全員にオイルをかけること

キルボタンを押して、一定時間近くに居ると、相手にオイルが塗れます。<br>
生存者全員にオイルを塗り、ベントに入ると単独勝利します。それ以外では敗北します。<br>

*暗転対策の為、死亡後のアーソニストは会議毎に自殺するモーションが本人にだけ見えます。死体は出ません。<br>

#### 設定

| 設定名       |
| ------------ |
| 塗り時間     |
| クールダウン |

### Egoist/エゴイスト

考案者 : しゅー<br>
制作者 : そうくん<br>

陣営 : 第三（エゴイスト）<br>
判定 : シェイプシフター<br>
カウント : インポスター<br>
勝利条件 : インポスター全滅後、インポスターの勝利条件を達成する<br>

インポスターはエゴイストを認識しています。<br>
エゴイストもインポスターを認識しています。<br>
インポスターとエゴイストは切りあうことができません。<br>
他のインポスターが全滅すると勝利します。<br>
エゴイストが勝利するとインポスターは敗北となります。<br>

敗北条件は以下の通りです。<br>

1.エゴイストが死亡する<br> 2.味方が残っている状態でインポスター勝利をする<br> 3.他の第三陣営が勝利する<br>

#### 設定

| 設定名                   |
| ------------------------ |
| キルクール               |
| マッドメイトを指名できる |

### Executioner/エクスキューショナー

陣営 : 第三（単独）<br>
判定 : クルーメイト<br>
カウント : クルー<br>
勝利条件 : ターゲットが投票で追放されること<br>

ターゲットに対してこちらからのみ視認できるダイヤのマークがついています。<br>
投票でダイヤが付いている人を追放すれば単独勝利します。<br>
対象がキルされた場合は役職が変化します。<br>
ターゲットがジェスターの場合は追加勝利します。<br>

#### 設定

| 設定名                                 |
| -------------------------------------- |
| インポスターもターゲットにできる       |
| キルできる第三陣営もターゲットにできる |
| ターゲットがキルされた後に変化する役職 |

### Jackal/ジャッカル

制作者 :  空き瓶/EmptyBottle<br>

陣営 : 第三（ジャッカル）<br>
判定 : インポスター<br>
カウント : ジャッカル<br>
勝利条件 : インポスターを全滅させ、ジャッカルチームの人数がクルーの人数と同数か上回ること<br>

他のすべてのプレイヤーを排除することで勝利する第三陣営のジャッカルチームの役職です。<br>
タスクがなく、インポスター、クルー、第三陣営をキルすることができます。<br>

注意点<br>
*特定条件になった場合、投票で追放された人がいても「誰も追放されなかった」と表示される(表示のみで追放はされます)<br>
 暗転対策の都合上このような表示になります。<br>
*インポスターを吊りきるとAutoMuteのミュートが解除されます。<br>

#### 設定

| 設定名                   |
| ------------------------ |
| キルクール               |
| ベントを使える           |
| サボタージュを使用できる |
| インポスター視界         |

### Jester/ジェスター

陣営 : 第三（単独）<br>
判定 : クルーメイト<br>
カウント : クルー<br>
勝利条件 : 投票で追放されること。<br>

投票で追放されたときに単独勝利となる第三陣営の役職です。<br>
追放されずにゲームが終了するか、キルされると敗北となります。<br>

### Opportunist/オポチュニスト

陣営 : 第三（その他）<br>
判定 : クルーメイト<br>
カウント : クルー<br>
勝利条件 : いずれかの陣営が勝利したときに生き残っていること。<br>

ゲーム終了時に生き残っていれば追加勝利となる第三陣営の役職です。<br>
タスクはありません。<br>

### SchrodingerCat/シュレディンガーの猫

陣営 : 第三（その他）<br>
判定 : クルーメイト<br>
カウント : クルー<br>
勝利条件 : なし<br>

デフォルトでは勝利条件を持たず、条件を満たすと初めて勝利条件を持ちます。<br>

1.インポスターにキルされるとキルを防いでインポスター陣営となる<br>
2.シェリフにキルされるとキルを防いでクルー陣営となる<br>
3.第三陣営にキルされるとキルを防いで第三陣営となる<br>
4.追放された場合は役職が変化せず、そのまま勝利条件が変わらず死亡する<br>
5.ウォーロックの能力でキルされると、そのまま勝利条件が変わらず死亡する<br>
6.自殺系キル(ヴァンパイア除く)でキルされると、そのまま勝利条件が変わらず死亡する<br>

また、全シュレディンガーの猫共通でタスクがありません。

#### 設定

| 設定名                                     |
| ------------------------------------------ |
| 役職変化前であれば、クルー陣営と勝利できる |
| 吊られた際、陣営が変化する                 |

### Terrorist/テロリスト

制作・考案者 : 空き瓶/EmptyBottle<br>

陣営 : 第三（単独）<br>
判定 : エンジニア<br>
カウント : クルー<br>
勝利条件 : 全てのタスクを完了させた状態で死亡すること。<br>

自身のタスクを全て完了させた状態で死亡したときに単独勝利となる第三陣営の役職です。<br>
タスクを完了させずに死亡したり、死亡しないまま試合が終了すると敗北となります。<br>

## 属性

### LastImpostor/ラストインポスター

制作・考案者 : そうくん<br>

最後のインポスターに付与される属性です。<br>
キルクールが設定した時間まで短くなります。<br>
ヴァンパイア、バウンティハンター、シリアルキラーには付与されません。<br>

| 設定名     |
| ---------- |
| キルクール |

### Lovers/恋人

制作・考案者 : ゆりの<br>

陣営 : 第三（恋人）<br>
判定 : -<br>
カウント : -<br>
勝利条件 : 恋人が2人共生き残っている状態で試合が終了すること。全クルーのタスク終了時は生き残っていても敗北。<br>

全プレイヤーの中から2人配役されます。(他の役職に重複)<br>
クルー陣営のタスクを持つ役職が恋人になった場合、タスクはなくなります。<br>
お互いの名前の後ろにハートマークが付きます。<br>
片方が死んだらもう片方も後追いで死亡します。<br>
投票で恋人が死んだ場合はもう片方も死亡し、通報不可能の死体になります。<br>

役職重複例：<br>
・テロリスト恋人:タスク持ち、タスク完了して死亡すればテロリストとして勝利。<br>
・マッドスニッチ恋人：タスク持ち、タスク完了すればインポスターが分かる。<br>
・スニッチ恋人：タスク無し、インポスターが分からないままになる。<br>
・シェリフ恋人：通常通りインポスター等をキルことが出来る。重複元の役職によってキルできるかどうか決まる。(インポスター恋人 キル可能.クルーメイト恋人 キル不可能)<br>
・オポチュニスト恋人：生き残れば勝利。<br>
・ジェスター恋人：ジェスター恋人が追放されればジェスターとして勝利。恋人が投票で追放された場合はジェスター恋人は敗北。<br>
・ベイト恋人：恋人がキルされてベイト恋人が後追い死亡した時は、通報は行われない。<br>

## DisableDevices/デバイスを無効化

各種機器を無効化することができます。<br>

| 設定名                           |
| -------------------------------- |
| スケルドのデバイス無効化         |
| ┣ アドミン無効化                 |
| ┗ カメラ無効化                   |
| ミラHQのデバイス無効化           |
| ┣ アドミン無効化                 |
| ┗ ドアログ無効化                 |
| ポーラスのデバイス無効化         |
| ┣ アドミン無効化                 |
| ┣ カメラ無効化                   |
| ┗ バイタル無効化                 |
| エアシップのデバイス無効化       |
| ┣ アドミン無効化（コックピット） |
| ┣ アドミン無効化（アーカイブ）   |
| ┣ カメラ無効化                   |
| ┗ バイタル無効化                 |
| 除外条件                         |
| ┣ インポスターを除く             |
| ┣ マッドメイト系を除く           |
| ┣ 第三陣営を除く                 |
| ┣ クルーメイトを除く             |
| ┗ 死人が出た後を除く             |

## SabotageTimeControl/サボタージュの時間制御

一部サボタージュの制限時間を変更することができます。<br>

| 設定名                           |
| -------------------------------- |
| サボタージュの時間制御           |
| ┣ ポーラスのリアクター制限時間   |
| ┗ エアシップのリアクター制限時間 |
## モード

### DisableTasks/タスクを無効化する

特定のタスクを無効化することができます。<br>

| 設定名                     |
| -------------------------- |
| タスクを無効化する         |
| ┣ カードタスク             |
| ┣ 医務室のスキャンタスク   |
| ┣ 金庫タスク               |
| ┣ ダウンロードタスク       |
| ┣ 原子炉起動タスク         |
| ┗ ブレーカーリセットタスク |

### FallFromLadders/転落死

ハシゴから下ると、一定確率で死亡します。<br>

| 設定名         |
| -------------- |
| ハシゴから転落 |
| ┗ 転落する確率 |

### HideAndSeek/かくれんぼモード

制作・考案者 : 空き瓶/EmptyBottle<br>

#### クルーメイト陣営(青色)勝利条件

全てのタスクを完了させること。<br>
※幽霊のタスクはカウントされません。<br>

#### インポスター陣営(赤色)勝利条件

全てのクルーメイトをキルすること。<br>
※クルーメイトとインポスターが同数であってもクルーメイトが全滅していないと試合は終わりません。<br>

#### 狐(紫色)勝利条件

トロールを除くいずれかの陣営が勝利したときに生き残っていること。<br>

#### トロール(緑色)勝利条件

インポスターにキルされること。<br>

#### 禁止事項

・サボタージュ<br>
・アドミン<br>
・カメラ<br>
・幽霊が生存者に位置情報を伝える行為<br>
・待ち伏せ(クルーメイトのタスク勝利が不可能となる可能性があるため。)<br>

#### できないこと

・死体の通報<br>
・緊急会議ボタン<br>
・サボタージュ<br>

#### 設定

| 設定名                     |
| -------------------------- |
| ドア閉鎖を許可する         |
| インポスターの待機時間(秒) |
| ベントの使用を禁止する     |

### NoGameEnd

#### クルーメイト陣営勝利条件

なし<br>

#### インポスター陣営勝利条件

なし<br>

#### 禁止事項

なし<br>

#### できないこと

ホストの SHIFT+L+Enter 以外でのゲーム終了。<br>

勝利判定が存在しないデバッグ用のモードです。<br>

### RandomSpawn/ランダムスポーン

スポーン位置をランダムに変更します。<br>

#### 設定

| 設定名                         |
| ------------------------------ |
| ランダムスポーン               |
| ┗ 追加スポーン位置(エアシップ) |

#### スケルド

![Skeld](Images/The_Skeld_Random_Map.png)

#### ミラHQ

![MiraHQ](Images/Mira_HQ_Random_Map.png)

#### ポーラス

![Polus](Images/Polus_Random_Map.png)

#### エアシップ

![AirShip](Images/The_Airship_Random_Map.png)

`追加スポーン位置(エアシップ) `がOFFの場合は本来のスポーン位置からのみ選出されます。

### RandomMapsMode/ランダムマップモード

制作者 : つがる<br>

ランダムにマップが変わるモードです。<br>

#### 設定

| 設定名               |
| -------------------- |
| ランダムマップモード |
| ┣ The Skeld を追加   |
| ┣ MIRA HQ を追加     |
| ┣ Polus を追加       |
| ┗ The Airship を追加 |

### SyncButtonMode/ボタン回数同期モード

プレイヤー全員のボタン回数が同期されているモードです。<br>

#### 設定

| 設定名                   |
| ------------------------ |
| ボタン回数同期モード     |
| ┗ 合計ボタン使用可能回数 |

### VoteMode/投票モード

| 設定名       | 説明                               |
| ------------ | ---------------------------------- |
| 投票モード   |                                    |
| ┣ スキップ時 | デフォルト/自殺/自投票             |
| ┣ 無投票時   | デフォルト/自殺/自投票/スキップ    |
| ┗ 同数投票時 | デフォルト/全員追放/ランダムに追放 |

## OtherSettings/その他の設定


| 設定名                               |
| ------------------------------------ |
| 全員生存時の会議                     |
| ┗ 全員生存時の会議時間               |
| 追加の緊急ボタンクールダウン         |
| ┣ 適用する生存人数                   |
| ┗ 追加するクールダウン               |
| 役職入りでかくれんぼ                 |
| ┗ 待機時間                           |
| 自動的に試合結果を表示               |
| 名前の二行目                         |
| 色名前モード                         |
| 初期スポーン時のクールダウン修正     |
| 幽霊が他人の役職を見ることができる   |
| 幽霊が他人の投票先を見ることができる |
| 死人のタスクを免除する               |
| タスク勝利を無効化                   |
| ゲーム設定を隠す                     |

#### クライアント設定

## Hide Game Codes/コード隠し

有効化することで、ロビーコードを非表示にすることができます。

コンフィグファイル(BepInEx\config\com.emptybottle.townofhost.cfg)の`Hide Game Code Name`を書き換えることによって、HideCodes を有効にしたときに好きな文字を表示させることができます。
また、`Hide Game Code Color`を書き換えることによって文字の色も好きなように変更できます。

## Force Japanese/強制日本語化

有効化することで言語設定にかかわらず、メニューを強制的に日本語にします。

## Japanese Role Name/役職名日本語化

有効化することで、役職名を日本語で表示させることができます。
クライアントの言語を英語にしている場合、`Force Japanese`を有効にしていないとこの設定は意味のないものとなります。

## クレジット

[バウンティーハンター](#BountyHunter/バンティーハンター)や[マフィア](#Mafia/マフィア)、[ヴァンパイア](#Vampire/ヴァンパイア)、[魔女](#Witch/魔女)、[ベイト](#Bait/ベイト)、[メイヤー](#Mayor/メイヤー)、[シェリフ](#Sheriff/シェリフ)、[スニッチ](#Snitch/スニッチ)、[ライター](#Lighter/ライター)、[シーア](#Seer/シーア)、[ジャッカル](#jackalジャッカル) のアイデア元であり、 Mod の作成方法の参考元 : [The Other Roles](https://github.com/TheOtherRolesAU/TheOtherRoles)<br>
[オポチュニスト](#Opportunist/オポチュニスト)、[ウォッチャー](#Watcher/ウォッチャー) のアイデア元 : [The Other Roles: GM Edition](https://github.com/yukinogatari/TheOtherRoles-GM)<br>
[シュレディンガーの猫](#SchrodingerCat/シュレディンガーの猫)、[イビルトラッカー](#EvilTracker/イビルトラッカー) のアイデア元 : [The Other Roles: GM Haoming Edition](https://github.com/haoming37/TheOtherRoles-GM-Haoming)<br>
[ドクター](#Doctor/ドクター) のアイデア元 : [Nebula on the Ship](https://github.com/Dolly1016/Nebula)<br>
[ジェスター](#Jester/ジェスター)(てるてる)と[マッドメイト](#Madmate/マッドメイト) のアイデア元 : [au.libhalt.net](https://au.libhalt.net)<br>
[テロリスト](#Terrorist/テロリスト)(Trickstar + Joker) : [Foolers Mod](https://github.com/MengTube/Foolers-Mod)<br>
[恋人](#lovers/恋人) : [Town-Of-Us-R](https://github.com/eDonnes124/Town-Of-Us-R)<br>
中国語翻訳 : fivefirex、ZeMingOH233<br>
オプションタブのアイコン製作者 : 花海<br>
Csv: Copyright (c) 2015 Steve Hansen [MIT License](https://raw.githubusercontent.com/stevehansen/csv/master/LICENSE)<br>

## 開発者
<!--
開発者用チャンネルでの一番最初の発言が早い順に記載する。
- [テンプレ](https://github.com/) ([Twitter](https://twitter.com/))
- [Twitter以外のページでも可](https://github.com/) ([Twitter](https://twitter.com/), [TheOtherPages](https://example.com/))
- [何もなくていい場合は消してOK](https://github.com/)
注：README-ENへの追記を忘れないでください。
-->
- [空き瓶/EmptyBottle](https://github.com/tukasa0001) ([Twitter](https://twitter.com/XenonBottle))
- [Tanakarina](https://github.com/tanakanira0118) <!--([Twitter](https://twitter.com/))-->
- [しゅー](https://github.com/shu-TownofHost) ([Twitter](https://twitter.com/Shu_kundayo))
- [kihi](https://github.com/Kihi1120) <!--([Twitter](https://twitter.com/))-->
- [TAKU_GG](https://github.com/TAKUGG) ([Twitter](https://twitter.com/TAKUGGYouTube1), [Youtube](https://www.youtube.com/c/TAKUGG))
- [そうくん](https://github.com/soukunsandesu) ([Twitter](https://twitter.com/Soukun_Dev), [Youtube](https://www.youtube.com/channel/UCsCOqxmXBVT-BD_UKaXpUPw))
- [みぃー](https://github.com/mii-47) <!--([Twitter](https://twitter.com/))-->
- [たんぽぽ](https://github.com/tampopo-dandelion)([Twitter](https://twitter.com/2nomotokaicho),  [Youtube](https://www.youtube.com/channel/UC8EwQ5gu-qyxVxek0jZw1Tg), [ニコニコ](https://www.nicovideo.jp/user/124305243))
- [こう。](https://github.com/kou-hetare) <!--([Twitter](https://twitter.com/))-->
- [よっキング](https://github.com/ykundesu) <!--([Twitter](https://twitter.com/))-->
- [ゆりの](https://github.com/yurinakira) <!--([Twitter](https://twitter.com/))-->
- [Masami](https://github.com/Masami4711) <!--([Twitter](https://twitter.com/))-->
