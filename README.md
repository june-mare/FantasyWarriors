# FantasyWarriors
## 作成者	
佐生絢弥

## 所属 
バンタンゲームアカデミー大阪校ゲームプログラム総合

|開発の詳細||
----|----
|製作期間|21日間 (147時間)|
|制作時期|一年生9月ごろ|
|制作人数|1人|
|ジャンル|アクションシューティング|
|プレイ人数|1人|
|プレイ時間想定|30分|
|プラットフォーム|PC|
|言語|C言語|

## 開発環境　　　　　　
Microsoft Visual Studio
WindowsAPI

## 製作意図
シューティングゲームを作ろうとしたときに魔法を使いたいと思い、プレイヤーを人にしてアクションシューティングにしました。

## アプリケーションの内容
- Warriorsモード
プレイヤーのHPが０になる、または制限時間が０になるまで敵を倒し、高得点を狙います。
https://github.com/june-mare/FantasyWarriors/blob/master/FantasyWarriors%20Warriors.png
<img src="https://github.com/june-mare/FantasyWarriors/blob/master/FantasyWarriors%20Warriors.png" alt="Warriors" title="Warriors" width="400" height="340">
- Winningモード
七人の敵との勝ち抜き戦です。
全員を倒すまでをタイムアタックできます。
<img src="https://github.com/june-mare/FantasyWarriors/blob/master/FantasyWarriors%20Winning.png" alt="Winning" title="Winning" width="400" height="340">

## 起動方法
実行モジュールより、FantasyWarriors.exeを開いてください。

## 操作方法
同ファイル内の操作方法.txtをご確認ください。

## 終了方法
子Windowの終了ボタンを押してください。

## 工夫した点
- プレイヤーの位置によって背景画像や敵の位置をを移動させて、より違和感なくプレイできるようにしました。　
- スキルカットインを入れて迫力が出るようにしました。
- 一つ一つのキャラクターに基本的な処理の流れと、同じ様なコードの書き方をしたので、キャラクターの追加や変更を出来やすくしました。
- 列挙体を使ったモードの変更を行いコード自体を簡潔にできるようにしました。

## 自分がどのように頑張ったか
自分自身が使いやすいコードを書くためにはどのようにしたらいいかを考えながら作成していました。特に関数内の処理などを出来るだけ同じものはまとめることに力を入れました。
