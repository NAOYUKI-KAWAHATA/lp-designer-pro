# Template 07: ライトブルーパステル（女性向け・清潔感・爽やか系）

## 概要
スカイブルー〜ペールピンクのパステルグラデーションと、幾何学的なダイヤモンドグリッドが特徴。
清潔感・透明感・爽やかさを重視した女性向けデザイン。美容・ウェルネス・ライフスタイル・ビジネス系セミナーに幅広く対応。
人物は右側に配置し、テキストは左側に縦並び（案A レイアウト確定）。

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/rxDALMujuyZerhmJ.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/output/test_07_light_pastel_v2a.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | 純白（#FFFFFF）中央から淡いスカイブルー（#E8F4FD）〜ペールラベンダーピンク（#FDE8F4）への放射状グラデーション。細いシルバーのダイヤモンドグリッド線（~10%不透明）。半透明の幾何学ポリゴン。ドットグリッド（~8%不透明）。ペールブルー＆ピンクのボケ円 |
| トップバッジ | ソフト角丸ピルバッジ。細いスカイブルー枠＋白塗り。小さなスパークルモチーフ。**テンプレートごとに装飾を工夫すること**。テキストはネイビーブルー（#1A3A5C）・ボールドゴシック |
| サブコピー | ネイビーブルー（#1A3A5C）・セミボールドゴシック。左揃え |
| メインタイトル | 左側・3行・左揃え。ダイナミックボールド明朝体。最大要素。スカイブルー（#5BB8F5）→ペールピンク（#F5A0C8）の左→右グラデーション。ソフトドロップシャドウ（ペールブルー） |
| サポートコピー | ミディアムグレーブルー（#4A6A8A）・小さめレギュラーゴシック。左揃え |
| 下部パネル | グラスモーフィズムパネル（白~70%不透明、フロストガラス）。ソフトブルーピンクの枠グロー。日時（大・ネイビーブルー・ボールド）＋スカイブルー区切り線＋特典テキスト（小・グレーブルー） |
| 特典メダル | パネル右端から飛び出す円形バッジ。スカイブルー→ペールピンクグラデーションリング。白内側＋ソフトブルーグロー。テキストはネイビーブルー明朝体 |
| 人物 | 右側（x:45%〜100%, y:0%〜80%）に長い茶髪・クリームニットの女性（胸上）。左方向を向く。シャープでフォトリアリスティック。左上からのソフトナチュラルスタジオ照明。下部グラデーションマスク |

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Soft pastel blue and pink premium design for women. Clean, airy, sophisticated. Like a premium beauty clinic or women's wellness brand. Luminous, fresh, elegant.

=== BACKGROUND ===
Soft gradient from pure white (#FFFFFF) center to very pale sky blue (#E8F4FD) and pale lavender-pink (#FDE8F4) at edges. Subtle thin silver diamond grid lines at ~10% opacity. Translucent geometric polygon shapes floating softly. Small dot grid at ~8% opacity. Soft bokeh circles in pale blue and pink.

=== PERSON ===
Sharp, photorealistic beautiful Japanese woman with long flowing brown hair, wearing a cream knit sweater. RIGHT side (x: 45%–100%, y: 0%–80%), portrait from chest up. Faces slightly LEFT toward the text. RAZOR SHARP, no blur. Soft natural studio lighting from upper-left. Lower body fades with gradient mask.

=== TEXT LAYOUT (LEFT side, top to bottom) ===

[TOP BADGE — upper-left]
※ テンプレートの世界観（パステルブルー・爽やか）に合わせた装飾バッジを工夫すること。
例: Soft rounded pill badge with thin sky-blue border and white fill. Small sparkle motif.
Text: "{{サブタイトル上}}" — navy blue (#1A3A5C), small bold Gothic.

[SUB COPY — left-aligned, below badge]
Line 1: "{{サブタイトル下行1}}" — navy blue (#1A3A5C), semi-bold Gothic.
Line 2: "{{サブタイトル下行2}}" — navy blue (#1A3A5C), semi-bold Gothic.

[MAIN TITLE — left side, 3 lines, left-aligned, LARGE]
Line 1: "{{セミナータイトル行1}}"
Line 2: "{{セミナータイトル行2}}"
Line 3: "{{セミナータイトル行3}}"
Font: dynamic bold Mincho. LARGEST text on canvas.
Color: sky blue (#5BB8F5) to pale pink (#F5A0C8) left-to-right gradient. Soft pale-blue drop shadow.

[SUPPORT COPY — left-aligned, below main title]
Line 1: "{{サポートコピー行1}}" — medium gray-blue (#4A6A8A), small Gothic.
Line 2: "{{サポートコピー行2}}" — medium gray-blue (#4A6A8A), small Gothic.

[BOTTOM GLASSMORPHISM PANEL — full width, lower portion]
Frosted glass panel: white ~70% opacity, soft blue-pink border glow. Inside:
- "{{日時}}" — large bold, navy blue (#1A3A5C)
- Thin sky-blue horizontal divider
- "{{特典テキスト}}" — small, medium gray-blue

PASTEL MEDAL: Circular badge right side of panel, protruding upward. Sky blue to pale pink gradient ring. White interior with soft blue glow. Text: "参加者限定豪華特典" — navy blue, Mincho. (Fixed by default. Change only if user requests.)

=== ABSOLUTE RULES ===
- VERTICAL 4:5 only. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified — no missing chars, no typos.
- Person MUST be SHARP and PHOTOREALISTIC, positioned on the RIGHT side.
- Main title must NOT overlap the person's face.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Panel Info.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | 3行メインタイトル（明朝体・スカイブルー→ピンクグラデーション） |
| `{{サブタイトル上}}` | トップバッジ内テキスト |
| `{{サブタイトル下}}` | バッジ下の2行サブコピー |
| `{{サポートコピー}}` | タイトル下の2行サポートコピー |
| `{{日時}}` | 下部グラスモーフィズムパネルの大テキスト |
| `{{特典テキスト}}` | 下部パネルの小テキスト |
| メダルテキスト | **固定値「参加者限定豪華特典」**（変更要請があれば差し替え） |
| `{{人物}}`（参照画像） | references パラメータに追加（女性モデル） |

## 女性モデル参照パス
`/home/ubuntu/skills/lp-designer-pro/templates/female_instructor.png`
