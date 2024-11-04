# LabVIEW
LabVIEWを使い始めました基本的なことをここにまとめます

## Sw_test
<p>スイッチは６つのアクションを簡単に比較できるものを作りました。</P>
<p>また、LabVIEWで覚えておくと便利なショートカットキーもポップアップが表示してわかるようにもしています。

![スクリーンショット 2024-11-02 210252](https://github.com/user-attachments/assets/c28d0454-c166-4c07-9507-7f808bf02c67)


<p>そして、構成も基本的な使い方である初期設定、メインループ、終了処理の３部構成にしています。</P>
<P>各ショートカットキーのアクションはイベントストラクチャを使ってダイアログを使ってポップアップしています。</P>

![スクリーンショット 2024-11-02 211624](https://github.com/user-attachments/assets/f830e5ca-b968-4019-bcc7-2210f0e91f3c)

## shortcut_keys
<p>ショートカットキーだけのVIを作りました。</p>

![スクリーンショット 2024-11-03 081345](https://github.com/user-attachments/assets/1ad1e5db-e344-43fc-9ad8-2028eb06b84a)

<p>サブVIで使うことを意識して各スイッチをセレクターにまとめました。
  
![スクリーンショット 2024-11-03 095301](https://github.com/user-attachments/assets/b9ff0bc9-bdcb-4244-8b2a-80a895cb00ce)

<P>メインVIでパネルを表示するときはshortcut_keysのアイコンを右クリックしてCreate Contorolを選択して接続すると</p>
<p>メインパネル上に表示できます。</P>
<p>サブVIで使用の時現状ポップアップは表示しません。サブVIをクリックしてshortcut_keys単体で起動させてください</p>
<p>メインVIでポップアップさせるにはメインのメインのブロックダイヤログでイベントストラクチャを設定してください。</p>

![スクリーンショット 2024-11-03 100144](https://github.com/user-attachments/assets/a184d87e-a602-4f0b-8639-714c3d2d0922)

## time_stamp
<p>タイムスタンプデータを加工し、より使いやすく表示・処理するためのVIです。サブVIとして利用することを想定しており、</p>
<p>複雑なタイムスタンプ情報を年・月・日、時・分・秒などに分解して表示する機能や、曜日表示、午前０時からの合計秒数の計算など、</p>
<p>多彩な出力形式をサポートしています。</p>

![スクリーンショット 2024-11-03 194712](https://github.com/user-attachments/assets/e81187b0-ba59-4ecf-a52c-e709b0214cd2)

ブロック図

![スクリーンショット 2024-11-04 003758](https://github.com/user-attachments/assets/6fab26b7-61d9-4f58-9eec-e492b17d02b2)

アイコンとブロック配線

![スクリーンショット 2024-11-04 004239](https://github.com/user-attachments/assets/2703fb61-50aa-4f25-ac69-51569ab6ad93)

## slide
<p>Express内のNum  Ctrlsのアイコンの動きを知るためのVIです。
DBL（少数を含む）とi32（整数）２種類の型で動きが確認できます。
ループカウンターの中で実行する作りになっています。
プログラム終了したい場合STOPボタンを押してください</p>

![スクリーンショット 2024-11-04 121654](https://github.com/user-attachments/assets/e1467561-2637-44f4-b71a-df85a7395af3)

フロントパネル内に型と数字表示の変更方法も書いています。

![スクリーンショット 2024-11-04 121713](https://github.com/user-attachments/assets/cff856fd-ef07-4785-aab2-f7b8d291d453)



