# Noco

Noco は、タブ管理と外観カスタマイズを備えたデスクトップ向けノートエディタです。  
Markdown とテキストの読み込み・保存に対応し、リッチテキスト編集を行えます。

English README: [README.en.md](README.en.md)

<img width="256" height="256" alt="icon" src="https://github.com/user-attachments/assets/82c87c7b-01f6-4b67-9773-a3da8b970803" />

<details><summary>プレビュー</summary>

<img width="1920" height="1080" src="https://github.com/user-attachments/assets/ca21d710-7dc7-4e40-84e4-e1f709bc3e86" />

<img width="1920" height="1080" src="https://github.com/user-attachments/assets/11044b19-918e-4588-af7e-dc732ef5f1a0" />

<img width="1920" height="1080" src="https://github.com/user-attachments/assets/190fe219-831a-409a-9548-950008fbc68a" />

<img width="1920" height="1080" src="https://github.com/user-attachments/assets/11b193ce-d368-4da3-951b-4b006b48889e" />

<img width="1920" height="1080" src="https://github.com/user-attachments/assets/75ee0f64-e58b-44e6-9159-c2bf3dc50fc4" />

<img width="1920" height="1080" src="https://github.com/user-attachments/assets/0c6dc2ba-a950-45a4-bb59-3e09fa5739ec" />

背景画像：[歳](https://www.pixiv.net/users/107960003)様

</details>

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](buymeacoffee.com/zennqiitagp)

## 対象OS

- Windows

## 主な機能

- 複数タブでのノート管理
  - 新規タブ作成、ドラッグ＆ドロップで並べ替え
  - 1行目から自動タイトル、未保存インジケーターと閉じる前の確認
- リッチテキスト編集
  - 見出し、太字、斜体、取り消し線、インラインコード
  - 引用、コードブロック、箇条書き、番号付きリスト
  - リンク挿入、Undo/Redo
- 表の編集
  - 表の挿入（行/列数の指定）、行/列の追加・削除（右クリックメニュー）
  - 表のコピー（TSV）
  - TSV/CSV/HTML テーブルの貼り付けで表を作成
- ファイル入出力
  - Markdown（.md/.markdown）とテキスト（.txt）の読み込み・保存
  - 保存時に .md / .txt を選択（Save as 対応）
  - Markdown 保存時は Markdown に変換（表は HTML として保持される場合があります）
  - .txt 保存時は Markdown テキストを基本として書き出し（表がある場合は TSV/CSV を選択）
  - .txt 読み込み時は Markdown として解釈しない
- 外観カスタマイズ
  - フォント選択（標準フォント / TTF/OTF）とカスタムフォントの削除
  - コードブロックを含めて本文フォントを適用
  - 背景画像、ぼかし・不透明度の調整
  - カラーオーバーレイと不透明度（HSVカラーピッカー）
  - テーマ色／アクセント色／エディタ文字色
  - 引用・コードブロックの背景色と不透明度
  - 表の罫線の太さ
  - 行の折り返しオン/オフ、ツールバー表示の切り替え
- UI 操作
  - 設定パネルの開閉（右下の歯車ボタン）
  - カスタムタイトルバー/リサイズハンドルを使用
- エディタのズーム（Ctrl + マウスホイール、Ctrl + 0 でリセット）
- 終了時にタブ状態と設定を保存し、次回起動時に復元

## キーボードショートカット

- Ctrl + S: 保存
- Ctrl + O: 開く
- Ctrl + T: 新規タブ
- Ctrl + W: タブを閉じる
- Ctrl + B: 太字
- Ctrl + I: 斜体
- Ctrl + Z: 元に戻す
- Ctrl + Y または Ctrl + Shift + Z: やり直す
- Ctrl + 0: ズームリセット
