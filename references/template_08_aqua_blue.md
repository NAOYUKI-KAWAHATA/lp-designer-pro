# Template 08: 優しいアクアブルー（女性向け・ウェルネス/ライフスタイル系）

## 概要
白を基調に淡いアクアブルーと水の波紋・水滴が広がる、上品で清潔感あふれるデザイン。
女性講師が右上に配置され、手書き風の流れるような書体で大きなタイトルが左〜中央に配置される。
下部には半透明のアクアグラスモーフィズムパネルとシルバーメダルが情報をまとめる。
ピラティス・ヨガ・美容・ウェルネス・ライフスタイル系セミナーに最適。
**講師名は下部パネル内のみに表示。本文エリアには表示しない。**

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/bHxiRszGrUcRLQjX.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/output/test_08_aqua_blue_v3.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | 純白（#FFFFFF）ベースから淡いアクアブルー（#B2EBF2）へのグラデーション。水の波紋（同心円リップル）が複数重なる（~15%不透明）。半透明の水滴が散在。ボケた光の玉（ボケ）が浮かぶ |
| トップバッジ | 細いアクアブルー枠（#00ACC1）の角丸バッジ。透明塗り。水滴モチーフ。**テンプレートごとに装飾を工夫すること**。テキストはダークティール（#006064）・エレガント明朝体 |
| サブコピー | ダークティール（#00838F）・中太エレガント明朝体。左揃え |
| メインタイトル | 左側・3行・左揃え。**手書き風の流れるような書体（筆ペン・カリグラフィー風）**。ティール（#00838F）→ダークアクア（#006064）グラデーション。最大要素 |
| サポートコピー | ダークティール（#006064）・レギュラーエレガント明朝体。左揃え |
| 下部パネル | 半透明グラスモーフィズム（アクアブルーグラデーション、~40%不透明、細いアクア枠#00ACC1）。内部に講師名・日時・メダルを配置 |
| 特典メダル | パネル右端に円形メダル。シルバー/ガラスフレーム＋アクアグラデーション内側。テキストは純白エレガント明朝体 |
| 人物 | 右上（x:50%〜100%, y:0%〜60%）に長い茶髪・クリームニットの女性（胸上）。左方向を向く。シャープでフォトリアリスティック。ソフトナチュラル照明。下部グラデーションマスク |

## フォント方針（確定版）
- **メインタイトル**：手書き風・流れるような書体（筆ペン・カリグラフィー風）
- **それ以外**：エレガント明朝体（サブコピー・サポートコピー・パネル内テキスト）

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Gentle aqua blue design for women. Pure white base with soft aqua blue gradients and water ripple motifs. Clean, elegant, refreshing, feminine. Like a premium spa or Pilates studio. Serene and pure.

=== BACKGROUND ===
Pure white (#FFFFFF) base with soft gradient to pale aqua blue (#B2EBF2) in lower and right areas. Multiple overlapping water ripple (concentric circle) patterns in very light aqua at ~15% opacity. Translucent water droplets of various sizes scattered across the canvas. Soft bokeh light orbs in pale aqua and white. Smooth, airy, luminous texture.

=== PERSON ===
Sharp, photorealistic beautiful Japanese woman with long flowing brown hair, wearing a cream knit sweater. UPPER-RIGHT area (x: 50%–100%, y: 0%–60%), portrait from chest up. Faces slightly left. RAZOR SHARP, no blur. Soft natural lighting. Lower body fades with soft gradient mask.

=== TEXT LAYOUT (LEFT side, top to bottom) ===

[TOP BADGE — upper-left]
※ テンプレートの世界観（アクアブルー・水）に合わせた装飾バッジを工夫すること。
例: Elegant rounded rectangle badge with thin aqua blue border (#00ACC1), transparent fill. Small water drop motif.
Text: "{{サブタイトル上}}" — dark teal (#006064), small elegant Mincho font.

[SUB COPY — left-aligned, below badge]
Line 1: "{{サブタイトル下行1}}" — dark teal (#00838F), medium-weight elegant Mincho.
Line 2: "{{サブタイトル下行2}}" — dark teal (#00838F), medium-weight elegant Mincho.
Line 3 (optional): "{{サブタイトル下行3}}" — dark teal (#00838F), medium-weight elegant Mincho.

[MAIN TITLE — left side, 3 lines, left-aligned, LARGE]
Line 1: "{{セミナータイトル行1}}"
Line 2: "{{セミナータイトル行2}}"
Line 3: "{{セミナータイトル行3}}"
Font: HANDWRITTEN CALLIGRAPHIC STYLE — flowing, feminine brush-pen or calligraphy font with natural stroke variation (thick-thin contrast). Like a Japanese calligraphy brush font. NOT rigid sans-serif.
Color: teal (#00838F) to dark aqua (#006064) gradient. Left-aligned. LARGEST element on canvas.

[SUPPORT COPY — left-aligned, below main title]
Line 1: "{{サポートコピー行1}}" — dark teal (#006064), regular elegant Mincho.
Line 2: "{{サポートコピー行2}}" — dark teal (#006064), regular elegant Mincho.

IMPORTANT: DO NOT add any instructor name between support copy and the bottom panel. Instructor name appears ONLY inside the bottom panel.

[BOTTOM PANEL — lower portion]
Translucent glassmorphism rounded rectangle panel (aqua blue gradient, ~40% opacity, thin aqua border #00ACC1). Inside:
- Left: "{{講師肩書き}} / 講師 / {{講師名}}" — small Mincho, pure white
- Center: "{{日時}}" — bold modern font, pure white
- Right: Medal badge area

SILVER MEDAL: Circular badge on right side of panel, protruding upward. Silver/glass frame with subtle aqua gradient interior. Text: "参加者限定豪華特典" — elegant Mincho, pure white. (Fixed by default. Change only if user requests.)

=== ABSOLUTE RULES ===
- VERTICAL 4:5 only. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified.
- Instructor name appears ONLY in the bottom panel. NOT anywhere else in the image.
- Main title MUST use a flowing, feminine handwritten calligraphic brush font style.
- Person MUST be SHARP and PHOTOREALISTIC, positioned UPPER-RIGHT.
- Main title must NOT overlap the person's face.
- Color palette: aqua/teal/white ONLY. NO warm colors, NO red, NO orange.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Panel Info.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | 3行メインタイトル（手書き風・ティール→ダークアクアグラデーション） |
| `{{サブタイトル上}}` | トップバッジ内テキスト |
| `{{サブタイトル下}}` | バッジ下の2〜3行サブコピー |
| `{{サポートコピー}}` | タイトル下の2行サポートコピー |
| `{{講師肩書き}}` | 下部パネル左列（肩書き部分）— 本文エリアには表示しない |
| `{{講師名}}` | 下部パネル左列（名前部分）— 本文エリアには表示しない |
| `{{日時}}` | 下部パネル中央の大テキスト |
| `{{特典テキスト}}` | 下部パネルの小テキスト |
| メダルテキスト | **固定値「参加者限定豪華特典」**（変更要請があれば差し替え） |
| `{{人物}}`（参照画像） | references パラメータに追加（女性モデル） |

## 女性モデル参照パス
`/home/ubuntu/skills/lp-designer-pro/templates/female_instructor.png`

## サンプル参照画像パス
`/home/ubuntu/skills/lp-designer-pro/templates/sample_08_aqua_blue.jpg`
