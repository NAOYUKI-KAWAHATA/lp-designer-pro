# Template 05: ラグジュアリーゴールド（女性向け・高級感・美容／コーチング系）

## 概要
白〜シャンパンゴールドの放射状グラデーションと、液体ゴールドのハイライトが特徴。
圧倒的な透明感と高級感。美容・ウェルネス・高単価コーチング・エリート女性向けセミナーに最適。
人物は左側に配置し、テキストは右側に縦に並べる構成。

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/JymyngbWEbdrxGSb.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/output/test_05_luxury_gold_v1.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | 純白（#FFFFFF）中央から淡いシャンパン（#FDF6E3）への放射状グラデーション。ゴールドの水滴・光粒子が空間全体に散りばめられる。右端に液体ゴールドのハイライト。ゴールドのボケ円が背景に浮かぶ |
| トップバンド | 全幅のシャンパンゴールドバンド（#F5E6C8、~70%不透明）。上下に細いゴールドボーダー。**テンプレートごとに装飾を工夫すること**。テキストはダークブラウン（#5C3D1E）中央揃えゴシック |
| トップバッジ | 右上エリアにダイヤモンド形の3Dゴールドメタリックフレームバッジ。水滴テクスチャ。白内側＋ゴールドシマー |
| メインタイトル | 右側・3行・左揃え。エレガントな細明朝体（高コントラスト）。最大要素。ディープウォームブラウン（#3D1F0A）＋金箔押し風メタリックシーン。ソフトドロップシャドウ |
| サブコピー | メインタイトル下・右側。ダークブラウン（#5C3D1E）・ミディアムゴシック |
| サポートコピー | サブコピー下・右側。ウォームグレーブラウン（#7A5C3E）・小さめレギュラーゴシック |
| ボトムバンド | 全幅のシャンパンゴールドバンド（#F5E6C8、~70%不透明）。上下に細いゴールドボーダー。講師名テキスト（ダークブラウン・左揃え） |
| 日時バッジ | 右下の円形バッジ。3Dゴールドメタリックフレーム＋水滴テクスチャ。白内側＋ゴールドグロー。日時テキスト（ダークブラウン・ボールドゴシック） |
| 特典テキスト | ボトムバンド下・左エリア。小さめゴシック・ダークブラウン |
| 人物 | 左側（x:0%〜55%, y:0%〜80%）に長い茶髪・クリームニットの女性（胸上）。右方向を向く。シャープでフォトリアリスティック。左上からのウォームゴールドリムライト。下部グラデーションマスク |

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Luxury gold and white premium design for women. High-end beauty, wellness, elite coaching. Overwhelming transparency and elegance. Warm white and champagne gold tones. Glossy, radiant, feminine. Like a high-end beauty brand or luxury spa brochure.

=== BACKGROUND ===
Radial gradient from pure white (#FFFFFF) center to very pale champagne (#FDF6E3) edges. Golden water droplets and light particles scattered elegantly throughout the space. Smooth liquid gold highlights on the right edge suggesting moisture and luxury. Subtle golden bokeh circles in the background. Soft and luminous.

=== PERSON ===
Sharp, photorealistic beautiful Japanese woman with long flowing brown hair, wearing a cream knit sweater. LEFT side (x: 0%–55%, y: 0%–80%), portrait from chest up. Faces slightly right toward the text. RAZOR SHARP — no blur. Soft warm studio lighting with golden rim light from upper-left. Lower body fades with gradient mask into the white background.

=== TEXT LAYOUT (right side, top to bottom) ===

[TOP BAND — upper area, spanning full width]
※ テンプレートの世界観（ラグジュアリーゴールド）に合わせた装飾を工夫すること。
例: Translucent champagne-gold band (#F5E6C8, ~70% opacity) with thin gold border lines (top and bottom).
Text: "{{サブタイトル上}}" — dark warm brown (#5C3D1E), medium Gothic, centered.

[TOP BADGE — upper-right area]
Diamond-shaped badge with 3D gold metallic frame and subtle water drop texture. White interior with golden shimmer.
Text: "参加無料" — dark brown (#5C3D1E), bold Gothic. (Fixed by default. Change only if user requests.)

[MAIN TITLE — right side, large, 3 lines, left-aligned]
Line 1: "{{セミナータイトル行1}}"
Line 2: "{{セミナータイトル行2}}"
Line 3: "{{セミナータイトル行3}}"
Font: elegant slender Mincho (thin-stroke, high-contrast). LARGEST text on canvas.
Color: deep warm brown (#3D1F0A) with a glossy gold foil stamping effect — subtle metallic sheen on the strokes. Soft drop shadow.

[SUB COPY — right side, below main title]
Line 1: "{{サブタイトル下行1}}" — dark brown (#5C3D1E), medium Gothic.
Line 2: "{{サブタイトル下行2}}" — dark brown (#5C3D1E), medium Gothic.

[SUPPORT COPY — right side, below sub copy]
Line 1: "{{サポートコピー行1}}" — warm gray-brown (#7A5C3E), small regular Gothic.
Line 2: "{{サポートコピー行2}}" — warm gray-brown (#7A5C3E), small regular Gothic.

[BOTTOM BAND — lower area, spanning full width]
Translucent champagne-gold band (#F5E6C8, ~70% opacity) with thin gold border lines.
Text: "{{講師肩書き}}　{{講師名}}" — dark brown, small Gothic, left-aligned.

[DATE BADGE — bottom-right]
Circular badge with 3D gold metallic frame and water drop texture. White interior with golden glow.
Text: "{{日時}}" — dark brown (#5C3D1E), bold Gothic.

[GIFT TEXT — bottom-left area, below bottom band]
Text: "{{特典テキスト}}" — dark brown, small Gothic.

=== ABSOLUTE RULES ===
- VERTICAL portrait image only. 4:5 ratio. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified — no missing chars, no typos.
- Person MUST be SHARP and PHOTOREALISTIC.
- Main title must NOT overlap the person's face.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Badges.
- Feminine, luxurious, radiant aesthetic throughout.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | 3行メインタイトル（明朝体・金箔風） |
| `{{サブタイトル上}}` | トップバンド内テキスト |
| 右上ダイヤモンドバッジ | **固定値「参加無料」**（変更要請があれば差し替え） |
| `{{サブタイトル下}}` | メインタイトル下の2行サブコピー |
| `{{サポートコピー}}` | サブコピー下の2行サポートコピー |
| `{{講師肩書き}}` | ボトムバンド内（肩書き部分） |
| `{{講師名}}` | ボトムバンド内（名前部分） |
| `{{日時}}` | 右下円形バッジ |
| `{{特典テキスト}}` | ボトムバンド下の特典テキスト |
| `{{人物}}`（参照画像） | references パラメータに追加（女性モデル） |

## 女性モデル参照パス
`/home/ubuntu/skills/lp-designer-pro/templates/female_instructor.png`
