# Template 04: フォレストグリーン（男性向け・子育て／ウェルネス系）

## 概要
ウォームクリームを基調に、フォレストグリーンの水彩風背景とボタニカルイラストが特徴。
手書き風フォントとメインタイトルの丸ゴシックが温かみを演出。
子育て・ウェルネス・自然育児・教育セミナーに最適。

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/lOuXtSreMoocSptJ.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/output/test_04_forest_green_v2.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | ウォームクリーム（#FDFAF4）ベース。上右・下左にセージグリーン（#A8C5A0）の水彩ウォッシュ。手描きボタニカルイラスト（葉・野草・枝）を全体に散りばめる（#4A7C59、~20%不透明度） |
| トップバッジ | 手描き風の楕円バッジ。スケッチ風のフォレストグリーン枠（#4A7C59）。クリーム塗り。両サイドに手描き葉の装飾。**テンプレートごとに装飾を工夫すること**。テキストは手書き風ブラシフォント |
| サブコピー | 手書き風ブラシフォント。ディープフォレストグリーン（#2E5D3E）。手描き波線アンダーライン（セージグリーン#81A887） |
| メインタイトル | 極太丸ゴシック（エクストラブラック・角丸）。ディープフォレストグリーン（#1B4D2E）→ミディアムグリーン（#4A7C59）上→下グラデーション。白い外側グロー（blur ~6px）。最大要素 |
| 区切り線 | メインタイトルとサポートコピーの間に手描き波線（セージグリーン） |
| サポートコピー | 手書き風ブラシフォント。ダークウォームグレー（#4A4A4A）。レギュラーウェイト |
| 情報パネル | クリーム（#FDFAF4、~85%不透明）のグラスモーフィズムパネル。手描き風フォレストグリーン枠（#4A7C59）。角に葉のモチーフ。日時（大・丸ゴシック・ディープグリーン）＋手描き波線区切り＋特典テキスト（手書き風） |
| 特典メダル | パネル右端から飛び出す円形バッジ。フォレストグリーングラデーション（#1B4D2E→#4A7C59）＋手描き月桂樹の葉の輪。内側クリーム背景。テキストは手書き風ブラシフォント・ディープグリーン |
| 人物 | 右側（x:52%〜100%, y:0%〜65%）に白シャツの男性（ウエストアップ）。シャープでフォトリアリスティック。自然な昼光。下部グラデーションマスクでクリーム背景にフェードアウト |

## フォント方針（確定版）
- **メインタイトルのみ**：極太丸ゴシック（エクストラブラック）
- **それ以外すべて**：手書き風ブラシペンフォント（バッジ・サブコピー・サポートコピー・パネル内テキスト・メダルテキスト）

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Warm, nurturing, natural parenting seminar design. Forest green and warm cream tones. Handwritten-style typography throughout (except the main title). Organic, gentle, trustworthy. Like a premium parenting book cover. Soft watercolor textures, botanical leaf motifs, warm and inviting.

=== BACKGROUND ===
Warm cream white (#FDFAF4) base. Soft watercolor wash of sage green (#A8C5A0) in the upper-right and lower-left corners, fading gently into the cream center. Delicate hand-drawn botanical illustrations: small leaves, tiny wildflowers, and thin branch lines scattered naturally across the background (forest green #4A7C59, very light, ~20% opacity). A gentle warm spotlight in the center. No harsh edges, everything soft and organic.

=== PERSON ===
Sharp, photorealistic [人物の説明] in a white linen shirt, black pants. RIGHT side (x: 52%–100%, y: 0%–65%), waist-up. Faces slightly left with a warm, gentle smile. RAZOR SHARP — no blur. Soft natural daylight from the left. Lower body fades with gradient mask into the cream background.

=== TEXT LAYOUT ===

[TOP BADGE — upper-left]
※ テンプレートの世界観（フォレストグリーン・手書き風）に合わせた装飾バッジを工夫すること。
例: A hand-drawn style oval badge with thin sketchy forest green border (#4A7C59) that looks hand-drawn with slight imperfections. Warm cream fill. Small hand-drawn leaf decorations on both sides of the oval.
Text: "{{サブタイトル上}}" — handwritten brush pen style font, forest green (#4A7C59), small.

[SUB COPY — below badge, left-aligned]
Line 1: "{{サブタイトル下行1}}" — handwritten brush pen style, deep forest green (#2E5D3E). Thin hand-drawn wavy underline in sage green (#81A887).
Line 2: "{{サブタイトル下行2}}" — handwritten brush pen style, deep forest green (#2E5D3E). Thin hand-drawn wavy underline.

[MAIN TITLE — center-left, 2 lines, left-aligned]
Line 1: "{{セミナータイトル行1}}"
Line 2: "{{セミナータイトル行2}}"
Font: ultra-bold modern rounded Gothic (extra-black weight, slightly rounded corners for warmth). LARGEST text on canvas.
Color: deep forest green (#1B4D2E) to medium forest green (#4A7C59) top-to-bottom gradient. Subtle warm white outer glow (blur ~6px) for contrast.

[SUPPORT COPY — below main title, left-aligned]
A thin hand-drawn wavy line in sage green above the support copy.
Line 1: "{{サポートコピー行1}}" — handwritten brush pen style, dark warm gray (#4A4A4A), regular weight.
Line 2: "{{サポートコピー行2}}" — handwritten brush pen style, dark warm gray (#4A4A4A).

[BOTTOM PANEL — lower portion]
Soft glassmorphism panel: warm cream (#FDFAF4) with ~85% opacity, thin hand-drawn style forest green border (#4A7C59) with slight sketch imperfections. Small leaf motifs in the corners. Inside:
- "{{日時}}" — large bold rounded Gothic, deep forest green (#1B4D2E)
- Thin hand-drawn wavy divider line in sage green
- "{{特典テキスト}}" — small handwritten-style font, dark forest green (#2E5D3E)

GREEN MEDAL BADGE: Large circular badge at the right side of the panel, protruding upward.
- Outer ring: forest green gradient (#1B4D2E → #4A7C59 → #1B4D2E) with hand-drawn style laurel wreath of leaves
- Inner circle: warm cream background with soft green radial glow
- Text inside: "参加者限定豪華特典" — handwritten brush font, deep forest green (#1B4D2E). (Fixed by default. Change only if user requests.)

=== ABSOLUTE RULES ===
- VERTICAL portrait image only. 4:5 ratio. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified — no missing chars, no typos.
- Handwritten/brush pen style font for all text EXCEPT the main title (rounded bold Gothic).
- Person MUST be SHARP and PHOTOREALISTIC.
- Main title must NOT overlap the person's face.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Panel Info.
- Warm, nurturing, organic aesthetic throughout.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | 2行メインタイトル（必要に応じて行分割） |
| `{{サブタイトル上}}` | トップバッジ内テキスト |
| `{{サブタイトル下}}` | バッジ下の2行サブコピー |
| `{{サポートコピー}}` | タイトル下の2行サポートコピー |
| `{{日時}}` | 下部パネルの大テキスト |
| `{{特典テキスト}}` | 下部パネルの小テキスト |
| メダルテキスト | **固定値「参加者限定豪華特典」**（変更要請があれば差し替え） |
| `{{人物}}`（参照画像） | references パラメータに追加 |

## バッジ装飾の指針
- Template 04（フォレストグリーン）: 手描き風楕円バッジ＋葉の装飾
- 他テンプレートでは、そのテンプレートのカラー・世界観に合わせた独自の装飾を設計すること
