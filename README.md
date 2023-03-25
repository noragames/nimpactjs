# NimpactJS

ゲームエンジンImpactJSの野良ライブラリ。マルチプラットフォーム書き出し対応。axios API通信対応(予定)。

<img src="http://noragames.com/images/github/nimpactjs240x240.png" alt="NimpactJS" />

### What is NimpactJS?

Free plugins for ImpactJS game development by Nora Games

---

## Release Note
- 2023/03/06 <a href="http://nimpactjs.com">nimpactjs.com</a> is ready
- 2023/05/29 Hopefully Ver. 1.0

---

## Documentation

### Sprite
- `Entity`'s wrapper class
- __alpha__: 透過値 (0 to 1)
- __visible__: 表示するかどうか (Boolean)
- __top__: 天面の座標 (Number)
- __bottom__: 底辺の座標 (Number)
- __left__: 左辺の座標 (Number)
- __right__: 右辺の座標 (Number)

### Button
- The subclass of `Sprite`
- タップ検知機。重ね表示、ツイート可。
- You can make tweet button as well
- __onMouseOver__: The event handler executed when the mouse if over (Function)
- __onMouseOUt__: The event handler executed when the mouse if out (Function)
- __onPress__: The event handler executed when the button is pressed (Function)
- __onPressing__: The event handler executed while pressing (Function)
- __onPressingOver__: The event handler executed when the __pressed__ mouse is over (Function)
- __onRelease__: The event handler when the button is released (Function)
- __onReleaseOut__: The event handler when the button is released __outside__ (Function)
- __onDragOver__: The event handler when some dragged object is over (Function)
- __onDragOut__: The event handler when some dragged object is out (Function)
- __onDrop__: The event handler when some dragged object is dropped (Function)

DEMO: http://noragames.com/html5/button/

### Drag
- ドラッグアンドドロップ機能

### Drop
- ドロップ対象が収まる受け皿
DEMO: http://noragames.com/html5/inventory/

### Gauge
- ゲージ機能
DEMO: http://noragames.com/html5/gauge/

### MonospacedFont
- The subclass of `Button`
- 等幅フォントクラス

### ConverterSjis
- ASCIIコードとUTF16をShift_JISに変換するクラス
- ※半角は全角に向き先を統合

### Typewriter
- The subclass of `Button`
- 流れる文字列出力機能

### KeyPad (開発中)
- The subclass of `Group`
- 全角と英数が打てるバーチャルパッド

<img src="http://noragames.com/images/github/keypad.gif" alt="KeyPad" />

### Textarea
- The subclass of `Button`
- KeyPadと連動するテキスト表示領域

### VirtualGri
- The subclass of `Button`
- Spaceless movement control
- トップビュー用バーチャルグリップ
DEMO: http://noragames.com/html5/house/

### Dice
- The subclass of `Button`
- The class returns random number 1 to 6
- 1～6のランダムな数値を返すクラス
- 
### Card
- The subclass of `Button`
- めくったり引いたり出したりできる汎用カードクラス

### Group
- Entity Grouping class
- Entityグループ化機能

### Title
- The subclass of `Button`
- ロゴとタイトル画面の抽象クラス(未着手)

### Hud
- 画面上部の帯、ハド(head up display)の抽象クラス

### Audio
- ロック機能などを完備した`Sound`の管理クラス(未着手)

### Axios
- API管理クラス(未着手)
 
---

## 開発方針
- 追記予定
