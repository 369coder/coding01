レスポンシブ対応
IE：グレースフルデグラデーション

フォント
基本・・・・・・ゴシック系
数字・欧文・・・Roboto（Regular、Black）

色
ブラック・・・・・#282832
ホワイト・・・・・#ffffff
パープル・・・・・#621f82, #3a0757
ブルー・・・・・・#0b5578, #042230
グレー・・・・・・#d3d3d3

テーブル
tdは等分割
thはチーム名でリンクを設定
チーム名が幅に収まらないときは自動で改行
高さが変わっても良い
ただし、常にth,tdは valign=middleの縦中央配置

画面幅が小さいときは、横スクロールで閲覧
ただし、順位とチーム名の列は固定配置

対戦カードのチーム名
必要に応じて改行
チーム名とロゴは中央揃え
さらに2つ並べたとき、ロゴのてっぺんはそろうこと。
カード全体は、対戦時間がページ中央で、それを中心に左右対称で等距離配置
文字数で崩れないように。

順位表のデータはCSV
直近5試合の情報は、対応するアイコンで表示

///////////////////////////////////////////////////////////////
ヒーローイメージは簡単に実装できるように変更
画像を変えても、背景の色は変わらないように。
ぼかした状態から、じわっとピントが合うフォーカスインのアニメーションにする
ページ読み込みから遅延無しで表示。

ヒーローイメージのデザインレイヤー
上　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　下
コンテンツ---明るさ調整レイヤー---色合い調整レイヤー---ヒーロー画像----ぼかしたヒーロー画像


ヒーローイメ―ジに重ねるタイトル文字は、行の下からスライドインするアニメーション
（タイトル文字はまとめて同じタイミングで動く）

XDのヒーローアニメーションスタートで確認

///////////////////////////////////////////////////////////////////////////////
ナビゲーションは、ハンバーガーメニュ―の形
ボタンクリックでフェード表示


















