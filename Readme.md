﻿# PinYinRuby
簡体字に拼音のルビを振る Chrome 拡張機能です。

![キャプチャ](https://raw.githubusercontent.com/syu105/PinYinRuby/master/Capture.jpg)

## ビルド
<http://unicode.org/Public/UNIDATA/Unihan.zip> に含まれる Unihan_Readings.txt が必要です。
Unihan_Readings.txt を ReadingBuilder\Data に展開します。その後、
ReadingBuilder プロジェクトの作業ディレクトリをそのプロジェクトディレクトリに設定し実行します。
reading.json が生成されます。Chrome をデベロッパーモードにし、パッケージ化した .prx を追加します。

## ライセンス
<https://github.com/syu105/PinYinRuby/blob/master/License.md>
