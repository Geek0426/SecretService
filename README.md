# シークレットサービス？

**日本語** | [English](#english-secret-service)

**画像加工ソフトで、上から黒く塗れば大丈夫？**

**……いつから、本当に消えていると「錯覚」していた？**

**ワレワレニオマカセクダサイ🤖**

見た目が黒くなっただけでは、元の情報が残っていることがあります。

「シークレットサービス？」は、隠したい範囲の**画像そのものを書き換えて保存**。
本名、住所、アカウント情報、偽名、内緒話、うっかり映り込んだ秘密まで。

**見せたい画像だけ見せる。見せたくないものは、きっちり隠す。**

**プライバシーを死守せよ！**

取捨選択は君の手にある。

スクリーンショットを見せたい。でも、名前や住所、アカウント情報などは隠しておきたい。
そんなとき、画像の見せたくない部分を四角く囲んで隠せる Windows 用アプリです。

隠し方は **モザイク・黒塗り・指定色** の3種類。
指定色では好きな色を選べるほか、**スポイトで画像内の色を拾って、背景と同じ色で自然に隠す**こともできます。

必要な部分だけを切り取ったり、画像そのものの大きさを変えたりしてから保存することもできます。

![シークレットサービス？の起動画面](screenshots/main-window.jpg)

## できること

| 操作 | できること |
| --- | --- |
| モザイク | 囲んだ部分を粗くして隠します。 |
| 黒塗り | 囲んだ部分を黒く塗りつぶします。 |
| 指定色 | 好きな色で囲んだ部分を塗りつぶします。スポイトで画像内の色を直接拾えるので、背景と同じ色で自然になじませることもできます。 |
| 切り取り | 四角く囲んだ範囲だけを残します。 |
| リサイズ | 保存する画像そのものの大きさを変えます。 |
| 元に戻す | 直前の加工や切り取り、リサイズを取り消します。 |

隠したい場所は、1枚の画像で続けて何か所でも指定できます。

## はじめての使い方

1. **画像を開く**
   画像ファイルを画面中央にドラッグして離すか、中央をクリックします。上の **FileOpen** から選ぶこともできます。

2. **隠し方を選ぶ**
   画面上部の「モザイク」「黒塗り」「指定色」のどれかを押します。

   「指定色」では好きな色を選べるほか、**スポイトを使って画像から直接色を取ることもできます。**
   背景と同じ色を拾えば、塗りつぶした部分を周囲になじませることができます。

3. **隠す場所を囲む**
   画像の上でマウスの左ボタンを押し、隠したい範囲を四角く囲むように動かして、ボタンを離します。
   別の場所も同じように続けて囲めます。

4. **仕上がりを確認する**
   間違えたら「元に戻す」を押します。
   必要なら「切り取り」で、残したい範囲だけを切り取ることもできます。

5. **保存する**
   はじめて使う場合は、上のフロッピーマークの **「新規」** がおすすめです。
   保存場所と名前を選ぶと、元画像を残したまま別の画像として保存できます。

隠す範囲を囲むと `AREA REDACTED`、保存が完了すると `REDACTION COMPLETE` と表示されます。

## 「新規」と「上書き」の違い

- **新規**
  別の画像として保存します。元画像は残ります。
  最初のファイル名には `-smoke` が付きます。
  例：`photo.png` → `photo-smoke.png`

- **上書き**
  開いた元画像を、加工後の画像に置き換えます。
  保存前に確認画面が表示されます。
  元画像を残しておきたい場合は「新規」を使ってください。

「元に戻す」は、編集中の操作を取り消すためのボタンです。

**一度上書き保存した元画像を復元する機能ではありません。**

## 画像の大きさと画面表示

上段の **「リサイズ」** は、保存する画像そのものの大きさを変更する機能です。

たとえば `80%` と入力して「決定」を押すと、画像そのものが元の大きさの80%になります。

右側の **「画面：＋／－」** は、編集しやすいように画面上の見え方だけを拡大・縮小する機能です。

こちらを操作しても、**保存する画像そのものの大きさは変わりません。**

拡大して画像が画面から見切れたときは「移動」を選び、画像をドラッグして表示位置を動かせます。

## 対応する画像

- **開ける画像**：PNG、JPEG、WebP、BMP
- **「新規」で保存できる画像**：PNG、JPEG
- **「上書き」**：開いた画像と同じ形式で保存

## 大切な情報を隠すときは

保存した画像をもう一度開いて、隠し忘れがないか確認することをおすすめします。

名前や住所、アカウント情報など、**文字を確実に読めない状態にしたい場合は「黒塗り」**が分かりやすいです。

「ここに何かあった」と目立たせたくない場合は、**「指定色」＋スポイト**をどうぞ。
周囲の背景色を拾って塗りつぶせば、黒い四角を置くより自然になじませることができます。

## キーボードでも操作できます

- `Ctrl+O`：画像を開く
- `Ctrl+Z`：元に戻す
- `Ctrl+S`：上書き保存（保存先のない画像では保存先を選択）
- `Ctrl+Shift+S`：別の画像として保存
- `Ctrl++` / `Ctrl+-`：画面表示の拡大／縮小
- `Ctrl+0`：画像全体を画面に合わせる

## ダウンロード

**Windows 64ビット用・インストール不要。**

[最新版をダウンロード](https://github.com/Geek0426/SecretService/releases/latest)

ダウンロードした実行ファイルから、そのまま起動して使えます。

**「何を見せて、何を隠すか。」**

それを決めるのは、あなたです。

**プライバシーを死守せよ！🤖**

---

## English: Secret Service?

**Think painting a black box over an image is enough?**

**...When did you start believing the information was really gone?**

**LEAVE IT TO US, HUMAN. 🤖**

An image can look covered while the original information is still present. Secret Service? replaces the pixels in the areas you select when it saves the edited image.

Hide names, addresses, account details, private conversations, or anything else you did not mean to show. **Share what you want people to see. Cover what you don't.**

**Protect your privacy!** The choice is yours.

Secret Service? is a Windows app for hiding parts of screenshots and other images. Draw a rectangle around each area you want to cover. Choose **Mosaic**, **Black fill**, or **Custom color**. With Custom color, you can use the eyedropper inside the color picker to match a color already in the image.

You can also crop or resize the image before saving it.

![Secret Service? main window](screenshots/main-window.jpg)

The app's interface is in Japanese. The button names below show the Japanese label followed by its English meaning.

### What you can do

| Tool | What it does |
| --- | --- |
| モザイク (Mosaic) | Makes the selected area blocky. |
| 黒塗り (Black fill) | Replaces the selected area with black. |
| 指定色 (Custom color) | Fills the selected area with a color you choose. The color picker's eyedropper can sample a color from the image. |
| 切り取り (Crop) | Keeps only the area inside the rectangle you draw. |
| リサイズ (Resize) | Changes the dimensions of the image you will save. |
| 元に戻す (Undo) | Reverses the most recent edit, crop, or resize. |

You can cover several areas in the same image, one after another.

### Getting started

1. **Open an image.** Drag an image file onto the large area in the middle of the window, click that area to choose a file, or press **FileOpen** at the top.
2. **Choose how to hide an area.** Select **モザイク** (Mosaic), **黒塗り** (Black fill), or **指定色** (Custom color). For Custom color, click the color control to open the color picker. Its eyedropper lets you sample a color directly from the image.
3. **Draw a rectangle.** Hold the left mouse button over the image, drag across the area you want to hide, and release. Repeat for any other areas.
4. **Check the result.** Press **元に戻す** (Undo) if you make a mistake. You can also use **切り取り** (Crop) to keep only part of the image.
5. **Save.** For your first edit, use the floppy disk button labeled **新規** (Save as New). Choose a name and location. This saves a separate image and leaves the original file in place.

The app shows `AREA REDACTED` after you cover an area and `REDACTION COMPLETE` after a successful save.

### Save as New or Overwrite?

- **新規 (Save as New)** saves a separate image and keeps the original. The suggested filename adds `-smoke`: `photo.png` becomes `photo-smoke.png`.
- **上書き (Overwrite)** replaces the image file you opened with the edited version. The app asks you to confirm before doing this. Use Save as New if you want to keep the original.

Undo only reverses edits during the current session. **It cannot restore an original image after you overwrite it.**

### Image size versus screen zoom

The **リサイズ** (Resize) control in the top row changes the image's actual dimensions. Enter `80%` and press **決定** (Apply) to make the image 80% of its original size.

The **画面：＋／－** (Screen zoom) buttons change only how large the image appears while you edit it. They do **not** change the size of the saved image.

If zooming makes part of the image go off screen, select **移動** (Pan) and drag the image into view.

### Supported image formats

- **Open:** PNG, JPEG, WebP, BMP
- **Save as New:** PNG, JPEG
- **Overwrite:** saves in the format of the image you opened

### Before sharing a sensitive image

Open the saved image again and check for anything you forgot to cover. If text such as a name, address, or account detail must be unreadable, **黒塗り** (Black fill) is the clearest choice.

To make a covered area blend into a plain background, use **指定色** (Custom color) and sample the surrounding color with the eyedropper.

### Keyboard shortcuts

- `Ctrl+O`: Open an image
- `Ctrl+Z`: Undo
- `Ctrl+S`: Overwrite (or choose a destination for an image without one)
- `Ctrl+Shift+S`: Save as New
- `Ctrl++` / `Ctrl+-`: Zoom the screen view in or out
- `Ctrl+0`: Fit the whole image to the window

### Download

**For 64-bit Windows. No installation required.**

[Download the latest release](https://github.com/Geek0426/SecretService/releases/latest), then run the downloaded `.exe` file.

**What will you show, and what will you hide? The choice is yours.**

**Protect your privacy! 🤖**
