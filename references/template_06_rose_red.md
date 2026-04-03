# Template 06: ローズレッド（女性向け・情熱・リーダーシップ系）

## 概要
ディープバーガンディ〜ローズレッドのグラデーション背景に、薄く浮かぶバラの花が特徴。
情熱的でパワフルな女性向けデザイン。高単価コーチング・女性リーダーシップ・ビジネス成功セミナーに最適。
メインタイトルは女性らしい明朝体で3行統一カラー。バッジはバラのモチーフ。

## 確定サンプル画像（S3）
https://files.manuscdn.com/user_upload_by_module/session_file/310519663099030020/cuzCnDbwpvLuMeDC.png

## ローカル参照パス
`/home/ubuntu/skills/lp-designer-pro/output/test_06_rose_red_v2.png`

## デザイン要素の詳細（確定版）

| 要素 | 詳細 |
|---|---|
| 背景 | ディープバーガンディ（#4A0018）→ローズレッド（#C0392B）の斜めグラデーション（左下→右上）。大輪のバラ（ボタニカルイラスト風）が~20%不透明度で背景に浮かぶ。ゴールドのシマー粒子。右上にウォームスポットライトグロー |
| トップバッジ | 円形フローラルバッジ。細いゴールドのバラ花びら枠。ディープバーガンディ塗り。上部中央に小さなゴールドバラのモチーフ。**テンプレートごとに装飾を工夫すること**。テキストはウォームホワイト・ボールドゴシック |
| サブコピー | ウォームホワイト（#FFF8F0）・セミボールドゴシック。各行に細いローズゴールドのアンダーライン |
| メインタイトル | 左側・3行・左揃え。エレガントな女性らしい高コントラスト明朝体（細い横画・太い縦画・やや筆記体風）。最大要素。**3行すべて同じ色**：ピュアウォームホワイト（#FFFFFF）＋均一なローズゴールドシマー。強いウォームホワイト外側グロー（blur ~8px）を全行に均等に適用 |
| サポートコピー | ペールピンクホワイト（#FFE8E8）・小さめレギュラーゴシック |
| 情報パネル | ディープバーガンディ角丸パネル（#3D0015、90%不透明）。細いローズゴールド枠（#D4A0A0）。日時（大・ウォームホワイト・ボールド）＋ローズゴールド区切り線＋特典テキスト（小・ペールピンクホワイト） |
| 特典メダル | パネル右端から飛び出す円形バッジ。ローズゴールドグラデーション（#C0392B→#E8A0A0）＋バラの花びら月桂樹。ディープバーガンディ内側＋ソフトローズグロー。テキストはウォームホワイト明朝体 |
| 人物 | 右側（x:50%〜100%, y:0%〜75%）に長い茶髪・クリームニットの女性（胸上）。左方向を向く。シャープでフォトリアリスティック。左上からのウォームドラマティック照明＋ローズゴールドリムライト。下部グラデーションマスク |

## フォント方針（確定版）
- **メインタイトル**：エレガントな女性らしい高コントラスト明朝体（細横・太縦・やや筆記体風）
- **それ以外**：ゴシック体（バッジ・サブコピー・サポートコピー・パネル内テキスト）

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
Rose red and deep burgundy premium design for women. Passionate, elegant, powerful feminine energy. High-end coaching, leadership, business success for women. Rich, warm, bold. Like a luxury fashion magazine editorial.

=== BACKGROUND ===
Deep burgundy (#4A0018) to rich rose red (#C0392B) diagonal gradient from lower-left to upper-right. IMPORTANT: Large semi-transparent rose flowers (full bloom roses, botanical illustration style) floating softly in the background at ~20% opacity, scattered across the canvas like a luxury wallpaper pattern. Soft gold shimmer particles scattered throughout. A warm spotlight glow in the upper-right area.

=== PERSON ===
Sharp, photorealistic beautiful Japanese woman with long flowing brown hair, wearing a cream knit sweater. RIGHT side (x: 50%–100%, y: 0%–75%), portrait from chest up. Faces slightly left. RAZOR SHARP, no blur. Warm dramatic lighting from upper-left with rose-gold rim light. Lower body fades with gradient mask.

=== TEXT LAYOUT ===

[TOP BADGE — upper-left]
※ テンプレートの世界観（ローズレッド・バラ）に合わせた装飾バッジを工夫すること。
例: Elegant circular floral badge with thin gold rose petal border and deep burgundy fill. Small decorative gold rose motif at top center.
Text: "{{サブタイトル上}}" — warm white, small bold Gothic.

[SUB COPY — below badge, left-aligned]
Line 1: "{{サブタイトル下行1}}" — warm white (#FFF8F0), semi-bold Gothic. Thin rose-gold underline.
Line 2: "{{サブタイトル下行2}}" — warm white (#FFF8F0), semi-bold Gothic. Thin rose-gold underline.

[MAIN TITLE — left side, 3 lines, left-aligned]
Line 1: "{{セミナータイトル行1}}"
Line 2: "{{セミナータイトル行2}}"
Line 3: "{{セミナータイトル行3}}"
Font: elegant feminine high-contrast Mincho (thin horizontal strokes, thick vertical strokes, slightly calligraphic). LARGEST text on canvas.
Color: ALL THREE LINES must be EXACTLY THE SAME COLOR — pure warm white (#FFFFFF) with a very subtle uniform rose-gold shimmer applied identically to all three lines. No variation whatsoever between lines. Strong warm white outer glow (blur ~8px) on all lines equally.

[SUPPORT COPY — below main title, left-aligned]
Line 1: "{{サポートコピー行1}}" — pale pink-white (#FFE8E8), small regular Gothic.
Line 2: "{{サポートコピー行2}}" — pale pink-white (#FFE8E8), small regular Gothic.

[BOTTOM PANEL — lower portion]
Deep burgundy rounded rectangle panel (#3D0015, 90% opacity). Thin rose-gold border (#D4A0A0). Inside:
- "{{日時}}" — large bold modern font, warm white (#FFFFFF)
- Thin horizontal rose-gold divider
- "{{特典テキスト}}" — small, pale pink-white

ROSE GOLD MEDAL: Large circular badge right side of panel, protruding upward. Rose-gold gradient ring (#C0392B to #E8A0A0) with elegant rose petal laurel wreath. Deep burgundy interior with soft rose glow. Text: "参加者限定豪華特典" — warm white elegant Mincho font. (Fixed by default. Change only if user requests.)

=== ABSOLUTE RULES ===
- VERTICAL 4:5 only. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified — no missing chars, no typos.
- ALL THREE main title lines must be identical in color treatment.
- Person MUST be SHARP and PHOTOREALISTIC.
- Main title must NOT overlap the person's face.
- Visual hierarchy: Main Title (largest) > Sub Copy > Support Copy > Panel Info.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | 3行メインタイトル（明朝体・白×ローズゴールド統一） |
| `{{サブタイトル上}}` | トップバッジ内テキスト |
| `{{サブタイトル下}}` | バッジ下の2行サブコピー |
| `{{サポートコピー}}` | タイトル下の2行サポートコピー |
| `{{日時}}` | 下部パネルの大テキスト |
| `{{特典テキスト}}` | 下部パネルの小テキスト |
| メダルテキスト | **固定値「参加者限定豪華特典」**（変更要請があれば差し替え） |
| `{{人物}}`（参照画像） | references パラメータに追加（女性モデル） |

## 女性モデル参照パス
`/home/ubuntu/skills/lp-designer-pro/templates/female_instructor.png`
