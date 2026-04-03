# Template 03: ネイビー＋ゴールド（男性向け・エグゼクティブコンサル系）

## 概要
深みのあるネイビーを基調に、落ち着いたアンティークゴールドを構造的アクセントとして使用。
「静かな高級感」をテーマに、ゴールドは枠線・区切り線・メダルのみに限定し、
テキストはメインタイトルの白→ゴールドグラデーション以外はすべて白に統一。
高級コンサル・プライベートバンキング・エリートビジネスセミナーに最適。

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/RBHcGGOqgEZyBtmV.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/output/test_03_cosmic_navy_v6.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | ディープネイビー（#0D1B3E）→ ダークネイビーブラウン（#1A1208）グラデーション。上右からの斜めゴールド光線（~10%不透明度）。キャンバス外枠に極細ゴールドフレーム |
| トップバッジ | ミニマルな横長ピル型。細いアンティークゴールド枠（#B8962E）。ダークネイビー半透明塗り。**テンプレートごとに装飾を工夫すること**。テキストは白 |
| サブコピー | 白（#FFFFFF）セミボールドゴシック。装飾なし。シンプルで落ち着いた印象 |
| メインタイトル | 極太ゴシック体（エクストラブラック）。左→右グラデーション（白#FFFFFF→アンティークゴールド#D4AF6A）。非常に控えめなゴールド外側グロー（blur ~5px）。リボン帯・アンダーラインなし。**唯一のゴールドテキスト要素** |
| 区切り線 | メインタイトルとサポートコピーの間に細いアンティークゴールド水平線（#B8962E、~1px） |
| サポートコピー | 白（#FFFFFF）レギュラーゴシック。サブコピーより小さめ |
| 情報パネル | ディープネイビー角丸パネル（#0D1B3E、~92%不透明）。細いアンティークゴールド枠（#B8962E）。日時（大・白・ボールド）＋ゴールド区切り線＋特典テキスト（小・白） |
| 特典メダル | パネル右端から飛び出す円形バッジ。アンティークゴールドグラデーション（#8B6914→#D4AF6A→#B8962E）＋月桂樹彫刻。内側ダークネイビー。テキストはアンティークゴールド明朝体 |
| 人物 | 右側（x:52%〜100%, y:0%〜65%）に白シャツの男性（ウエストアップ）。シャープでフォトリアリスティック。上右からの暖かいリムライト。下部グラデーションマスクでフェードアウト |

## デザイン原則（確定版）
- **ゴールドは構造的にのみ使用**（枠線・区切り線・メダル）。テキストには使わない（メインタイトル除く）
- **全テキストは白**。メインタイトルのみ白→ゴールドグラデーション
- **余白を十分に確保**してテキストゾーン間に呼吸感を持たせる
- 全体印象：静かな権威、控えめな格式

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Quiet luxury. Deep navy and muted antique gold. Exclusive private members club, discreet wealth management, elite consulting. Calm, restrained, sophisticated. Gold used ONLY as structural accents (borders, lines, badge frames, medal). ALL text is pure white EXCEPT the main title which has a white-to-gold gradient. Refined, not flashy.

=== BACKGROUND ===
Deep navy (#0D1B3E) to dark navy-brown (#1A1208) gradient top to bottom. Very subtle diagonal gold light rays (#B8962E, ~10% opacity) from upper-right. Soft warm gold spotlight glow in upper-right corner. Thin single gold geometric frame lines along all four canvas edges (very thin, ~2px, like a luxury certificate). Clean, dark, premium.

=== PERSON ===
Sharp, photorealistic [人物の説明] in a white linen shirt, black pants. RIGHT side (x: 52%–100%, y: 0%–65%), waist-up. Faces slightly left. RAZOR SHARP — no blur. Subtle warm rim light from upper-right. Lower body fades with gradient mask.

=== TEXT LAYOUT ===

[TOP BADGE — upper-left]
※ テンプレートの世界観（ネイビー＋ゴールド）に合わせた装飾バッジを工夫すること。
例: Minimal horizontal pill badge. Single thin antique gold border (#B8962E). Dark navy semi-transparent fill. No glow, no shimmer — clean and understated.
Text: "{{サブタイトル上}}" — pure white (#FFFFFF), small regular Gothic. Calm and refined.

[SUB COPY — below badge, left-aligned]
Line 1: "{{サブタイトル下行1}}" — pure white (#FFFFFF), semi-bold Gothic. No decoration.
Line 2: "{{サブタイトル下行2}}" — pure white (#FFFFFF), semi-bold Gothic. No decoration.

[MAIN TITLE — center-left, 3 lines, left-aligned]
"{{セミナータイトル行1}}" / "{{セミナータイトル行2}}" / "{{セミナータイトル行3}}"
Font: ultra-bold modern Gothic (extra-black weight). LARGEST text on canvas.
Color: each character has a LEFT-TO-RIGHT gradient fill — pure white (#FFFFFF) on the left, transitioning to warm antique gold (#D4AF6A) on the right. Very subtle warm gold outer glow (blur ~5px). THIS IS THE ONLY ELEMENT WITH GOLD TEXT.

[THIN GOLD RULE — between main title and support copy]
Single thin horizontal antique gold line (#B8962E, ~1px) spanning the left 60% of the canvas width.

[SUPPORT COPY — below gold rule, left-aligned]
Line 1: "{{サポートコピー行1}}" — pure white (#FFFFFF), regular Gothic, slightly smaller than sub copy.
Line 2: "{{サポートコピー行2}}" — pure white (#FFFFFF), regular Gothic.

[BOTTOM PANEL — lower portion]
Deep navy rounded rectangle panel (#0D1B3E, ~92% opacity). Single thin antique gold border (#B8962E). Minimal, clean. Inside:
- "{{日時}}" — large bold modern font, pure white (#FFFFFF)
- Thin horizontal antique gold divider (#B8962E)
- "{{特典テキスト}}" — small regular Gothic, pure white (#FFFFFF)

GOLD MEDAL BADGE: Circular badge at the right side of the panel, protruding upward.
- Outer ring: antique gold gradient (#8B6914 → #D4AF6A → #B8962E) with subtle engraved laurel wreath. Restrained elegance.
- Inner circle: deep navy background with very soft gold glow
- Text inside: "参加者限定豪華特典" — elegant Mincho font, antique gold (#D4AF6A). (Fixed by default. Change only if user requests.)

=== ABSOLUTE RULES ===
- VERTICAL portrait image only. 4:5 ratio. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified — no missing chars, no typos.
- ONLY the main title uses gold gradient text. ALL other text is pure white.
- NO ribbon bands, NO underlines on any text.
- Person MUST be SHARP and PHOTOREALISTIC.
- Main title must NOT overlap the person's face.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Panel Info.
- Quiet luxury aesthetic — restrained, calm, sophisticated.
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
