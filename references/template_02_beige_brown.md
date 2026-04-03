# Template 02: ベージュブラウン（男性向け・コンサル／士業／高単価系）

## 概要
ウォームホワイトクリームからディープベージュブラウンへ変化するグラデーションが特徴。
ゴールドのアクセントと白文字のメインタイトルが高級感と権威性を演出する。
コンサル・士業・ビジネス系セミナーに最適。

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/XRKaWGLjNCZAzDDK.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/output/test_02_beige_brown_v1.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | ウォームホワイトクリーム（#F5F0E8）上部 → ディープベージュブラウン（#3D2B1F）下部へのスムーズグラデーション。斜めの幾何学ライン（光の反射）。上部中央にソフトなウォームスポットライト |
| トップバッジ | 角丸バッジ、ゴールド細枠（#C9A84C）、ウォームクリーム背景。テキストはダークブラウン（#3D2B1F）小ボールドゴシック。**テンプレートごとに装飾を工夫すること** |
| サブコピー | ダークブラウン（#3D2B1F）セミボールドゴシック、細いゴールドアンダーライン付き。2行 |
| メインタイトル | 極太ゴシック体（エクストラブラック）。白（#FFFFFF）。各行の背後にダークブラウンの半透明リボン帯を配置して視認性を確保。左揃え3行。最大要素 |
| サポートコピー | ウォームクリームホワイト、レギュラーゴシック。2行 |
| 情報パネル | ダークブラウン（#3D2B1F、85%不透明）の角丸パネル。日時（大・白・ボールド）＋ゴールド区切り線＋特典テキスト（小・クリームホワイト） |
| 特典メダル | パネル右端から飛び出す円形バッジ。リッチゴールドグラデーション（#C9A84C→#FFD700→#C9A84C）＋3Dメタリックシーン＋十字型レンズフレア。内側クリーム背景。ダークゴールド明朝体テキスト |
| 人物 | 右側（x:50%〜100%, y:5%〜70%）に白シャツの男性（ウエストアップ）。シャープでフォトリアリスティック。ウォームスタジオライティング。下部はグラデーションマスクでフェードアウト |

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Elegant, premium, high-authority design for consulting / business seminars. Warm beige-brown and gold tones. Low-contrast, high-key atmosphere. Sophisticated and trustworthy.

=== BACKGROUND ===
Smooth gradient from warm white-cream (#F5F0E8) at the top to deep rich beige-brown (#3D2B1F) at the bottom. Subtle diagonal geometric lines suggesting light reflection. A soft warm spotlight glow in the upper-center area. No noise, clean and heavy gradient.

=== PERSON ===
A sharp, photorealistic young Japanese man in a white linen shirt, black pants. Placed on the RIGHT side of the canvas (x: 50%–100%, y: 5%–70%), waist-up shot. He faces slightly left toward the text. SHARP and CLEAR — no blur. Warm studio lighting. His lower body fades into the background with a soft gradient mask.

=== TEXT LAYOUT (top to bottom, left-aligned) ===

[TOP BADGE — upper-left]
※ テンプレートの世界観（ベージュブラウン・ゴールド）に合わせた装飾バッジを工夫すること。
例: 角丸バッジ with thin gold border (#C9A84C), warm cream fill.
Text: "{{サブタイトル上}}" — dark brown (#3D2B1F), small bold Gothic.

[SUB COPY — below badge, left-aligned]
Line 1: "{{サブタイトル下行1}}" — dark brown (#3D2B1F), semi-bold Gothic, with thin gold underline.
Line 2: "{{サブタイトル下行2}}" — dark brown (#3D2B1F), semi-bold Gothic, with thin gold underline.

[MAIN TITLE — center-left, 3 lines, left-aligned]
"{{セミナータイトル行1}}" / "{{セミナータイトル行2}}" / "{{セミナータイトル行3}}"
Font: ultra-bold modern Gothic (extra-black weight). LARGEST text on canvas.
Color: pure white (#FFFFFF). A semi-transparent dark brown ribbon band behind each line for readability.

[SUPPORT COPY — below main title, left-aligned]
Line 1: "{{サポートコピー行1}}" — warm cream white, regular Gothic.
Line 2: "{{サポートコピー行2}}" — warm cream white, regular Gothic.

[BOTTOM PANEL — lower portion]
Dark brown rounded rectangle panel (#3D2B1F, ~85% opacity). Inside:
- "{{日時}}" — large bold modern font, pure white (#FFFFFF)
- Thin horizontal gold divider line
- "{{特典テキスト}}" — small regular Gothic, warm cream white

GOLD BADGE: Large circular badge at the right side of the panel, protruding upward.
- Outer ring: rich gold gradient (#C9A84C → #FFD700 → #C9A84C) with 3D metallic sheen
- Strong cross-shaped lens flare effect on the badge
- Inner circle: warm cream background
- Text inside: "参加者限定豪華特典" — elegant Mincho font, dark gold (#8B6914). (Fixed by default. Change only if user requests.)

=== ABSOLUTE RULES ===
- VERTICAL portrait image only. 4:5 ratio. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified — no missing chars, no typos.
- Person MUST be SHARP and PHOTOREALISTIC.
- Main title must NOT overlap the person's face.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Panel Info.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | 3行メインタイトル（必要に応じて行分割） |
| `{{サブタイトル上}}` | トップバッジ内テキスト |
| `{{サブタイトル下}}` | バッジ下の2行サブコピー |
| `{{サポートコピー}}` | タイトル下の2行サポートコピー |
| `{{日時}}` | 下部パネルの大テキスト |
| `{{特典テキスト}}` | 下部パネルの小テキスト |
| メダルテキスト | **固定値「参加者限定豪華特典」**（変更要請があれば差し替え） |
| `{{人物}}`（参照画像） | references パラメータに追加 |

## バッジ装飾の指針（テンプレートごとに工夫）
- Template 02（ベージュブラウン）: ゴールド細枠＋クリーム背景のシンプルな角丸バッジ
- 他テンプレートでは、そのテンプレートのカラー・世界観に合わせた独自の装飾を設計すること
