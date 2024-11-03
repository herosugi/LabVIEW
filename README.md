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

<P>メインVIでパネルを表示するときはshortcut_keysのアイコンを右クリックしてCreate Contorolを選択して接続するとメインパネル上に表示できます。</P>
<p>サブVIで使用の時現状ポップアップは表示しません。サブVIをクリックしてshortcut_keys単体で起動させてください</p>
<p>メインVIでポップアップさせるにはイベントストラクチャを設定してください。</p>

![スクリーンショット 2024-11-03 100144](https://github.com/user-attachments/assets/a184d87e-a602-4f0b-8639-714c3d2d0922)

