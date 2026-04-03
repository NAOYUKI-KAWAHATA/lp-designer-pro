# Template 01: Gemini ブルーグラデーション（男性向け・AI/テック系）

## 概要
漆黒を基調にシアン・パープル・ブルーが放射状に広がるGemini風の先進的なグラデーションが特徴。
白いシャツの男性講師が右上に配置され、大きな日本語タイトルが左〜中央に力強く配置される。
下部には半透明のグラスモーフィズムパネルと、ゴールドの月桂樹メダルが視線を誘導する。
AI・IT・テクノロジー系セミナーに最適。

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/UrGytkPRuUqZmuAs.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/templates/template_01_gemini_blue_FINAL.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | 漆黒（#050510）を基調に、右上からシアン・パープル・ブルーの放射状グラデーション。斜めの光の軌跡（レンズフレア）が複数走る。細かいスターダストパーティクル |
| メインタイトル | 極太ゴシック体。各文字の塗りが左端シアン（#00E5FF）→右端ホワイト（#FFFFFF）の水平グラデーション。外側にシアンのソフトグロー（blur ~10px）。左揃えで3行 |
| サブコピー上 | 角丸バッジ（シアン細枠、半透明ダーク背景）。白文字小ゴシック。**テンプレートごとに装飾を工夫すること** |
| サブコピー中 | 白文字・セミボールドゴシック。バッジの下に2行 |
| サポートコピー | 白文字・レギュラーゴシック。タイトルの下に2行 |
| 情報パネル | 下部に半透明グラスモーフィズム（シアン〜ダークブルー）の角丸パネル。日時（大・白・ボールド）＋区切り線＋特典テキスト（小・白） |
| 特典メダル | パネル右端から飛び出す大きな円形メダル。ゴールド月桂樹フレーム＋シアン〜パープル〜ブルーのホログラムグラデーション。金色明朝体テキスト |
| 人物 | 右上（x:48%〜98%, y:3%〜62%）に白シャツの男性（ウエストアップ）。シャープでフォトリアリスティック。左肩にわずかなシアンリムライト。下部はグラデーションマスクでフェードアウト |
| 余白 | 外周52px。テキストブロック間40px。主要セクション間60px |

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Jet black background with Gemini-style cyan/blue/purple gradient from upper-right. Diagonal light streaks. Fine stardust particles. Professional AI/tech seminar banner.

=== BACKGROUND ===
Deep black (#050510) base. Upper-right quadrant: vivid cyan (#00E5FF) → electric blue (#0040FF) → deep purple (#6600CC) radial gradient, fading into black. 3-4 diagonal laser light streaks (thin, ~2px, cyan/blue, ~30% opacity) crossing the canvas. Fine stardust particles scattered at low opacity.

=== PERSON ===
Young Japanese man in white linen shirt, waist-up, slight smile. Positioned UPPER-RIGHT: x: 48%-98%, y: 3%-62%. RAZOR SHARP, photorealistic, natural warm skin tone. White shirt is clean white (NOT cyan-tinted). Subtle cyan rim light on left shoulder edge only. Lower body fades with gradient mask. The person must NOT overlap with the badge or sub copy text on the left side.

=== SPACING & LAYOUT RULES (PROFESSIONAL DESIGNER STANDARDS) ===
Canvas: 1080x1350px. Left margin: 52px. Right margin: 52px. Top margin: 52px. Bottom margin: 52px.
All text blocks are LEFT-ALIGNED in the LEFT HALF of the canvas (x: 52px to ~540px).
Spacing between text blocks must follow a consistent rhythm: 24px between small elements, 40px between major sections.

=== TEXT LAYOUT (TOP TO BOTTOM) ===

[ZONE 1 — y: 52px to 110px]
Badge: "{{サブタイトル上}}"
Style: Rounded rectangle, thin cyan border (#00E5FF, 2px), semi-transparent dark fill (#00000066), white text, small Gothic font (~22px). Left-aligned at x:52px.
※ テンプレートの世界観（Gemini/AI/テック）に合わせた装飾バッジを工夫すること。

[ZONE 2 — y: 142px to 260px] (40px gap after badge)
Sub Copy:
Line 1: "{{サブタイトル下行1}}" — white, semi-bold Gothic, ~34px
Line 2: "{{サブタイトル下行2}}" — white, semi-bold Gothic, ~34px
Line spacing: 28px

[ZONE 3 — y: 300px to 820px] (40px gap after sub copy)
Main Title (3 lines, ultra-bold Gothic, LARGEST):
Line 1: "{{セミナータイトル行1}}" — ~140px font
Line 2: "{{セミナータイトル行2}}" — ~140px font
Line 3: "{{セミナータイトル行3}}" — ~140px font
Line spacing: 20px
Color: Each character fill = horizontal gradient from vivid CYAN (#00E5FF) at left edge to pure WHITE (#FFFFFF) at right edge. Outer soft cyan glow (blur ~10px).

[ZONE 4 — y: 860px to 980px] (40px gap after title)
Support Copy:
Line 1: "{{サポートコピー行1}}" — white, regular Gothic, ~30px
Line 2: "{{サポートコピー行2}}" — white, regular Gothic, ~30px
Line spacing: 24px

[ZONE 5 — y: 1040px to 1298px] (60px gap before panel)
Info Panel: Rounded rectangle (border-radius 16px), glassmorphism (cyan-to-dark-blue gradient, ~35% opacity, thin cyan border #00E5FF 1.5px). Spans full width minus margins (x: 52px to 1028px).
Inside panel:
- Large date/time: "{{日時}}" — white, ultra-bold modern font, ~52px, left-aligned inside panel
- Thin horizontal divider line (white, 40% opacity) below date
- Small text: "{{特典テキスト}}" — white, regular Gothic, ~24px, left-aligned inside panel

MEDAL: Circular badge (diameter ~170px) positioned at RIGHT side of panel, center protruding ~60px ABOVE the panel top edge. Gold laurel wreath frame. Interior: holographic gradient (cyan → purple → blue). Text inside: "参加者限定豪華特典" — gold Mincho font, ~28px. (This text is fixed by default. Change only if user explicitly requests.)

=== ABSOLUTE RULES ===
- VERTICAL 4:5 only. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified.
- Consistent 52px outer margins on all sides.
- 40px breathing room between each major text zone.
- Person positioned upper-right, NOT overlapping left-side text.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Panel Info.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | 3行メインタイトル（シアン→白グラデーション） |
| `{{サブタイトル上}}` | バッジ内テキスト |
| `{{サブタイトル下}}` | バッジ下の2行サブコピー |
| `{{サポートコピー}}` | タイトル下の2行サポートコピー |
| `{{日時}}` | 下部パネルの大テキスト |
| `{{特典テキスト}}` | 下部パネルの小テキスト |
| メダルテキスト | **固定値「参加者限定豪華特典」**（変更要請があれば差し替え） |
| `{{人物}}`（参照画像） | references パラメータに追加 |

## 男性モデル参照パス
`/home/ubuntu/skills/lp-designer-pro/templates/male_instructor.png`
