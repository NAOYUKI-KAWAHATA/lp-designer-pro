# Template XX: {{テンプレート名}}（カスタム登録）

## 登録日
{{登録日}}

## 登録者コメント
{{ユーザーが付けたコメント}}

## サンプル画像パス
`/home/ubuntu/skills/lp-designer-pro/custom_templates/template_XX_{{名前}}.png`

## デザイン要素の分析（登録時に自動記録）

| 要素 | 分析内容 |
|---|---|
| 背景 | {{背景の色・グラデーション・テクスチャ}} |
| カラーパレット | {{主要カラー（HEXコード）}} |
| フォントスタイル | {{明朝体 / ゴシック体 / 手書き風 など}} |
| ターゲット | {{男性向け / 女性向け / ユニセックス}} |
| 雰囲気 | {{高級感 / 親しみやすい / プロフェッショナル など}} |
| レイアウト特徴 | {{人物の位置、テキストゾーンの配置など}} |

## 確定プロンプト（generate_image 用）

```text
A professional ultra-high-quality vertical LP banner image, portrait orientation (taller than wide), 1080x1350px, 4:5 aspect ratio. STRICTLY VERTICAL — never landscape.

=== OVERALL STYLE ===
{{登録時に分析したスタイル説明}}

=== BACKGROUND ===
{{背景の詳細説明}}

=== PERSON ===
{{人物の配置・スタイル}}

=== TEXT LAYOUT (top to bottom) ===

[TOP BADGE]
Text: "{{サブタイトル上}}"

[SUB COPY]
Line 1: "{{サブタイトル下行1}}"
Line 2: "{{サブタイトル下行2}}"

[MAIN TITLE]
"{{セミナータイトル行1}}" / "{{セミナータイトル行2}}" / "{{セミナータイトル行3}}"

[SUPPORT COPY]
Line 1: "{{サポートコピー行1}}"
Line 2: "{{サポートコピー行2}}"

[BOTTOM PANEL]
- "{{日時}}"
- "{{特典テキスト}}"

MEDAL: Text: "参加者限定豪華特典" (Fixed. Change only if user requests.)

=== ABSOLUTE RULES ===
- VERTICAL 4:5 only. 1080x1350px. NEVER landscape.
- ALL Japanese text rendered EXACTLY as specified.
- Person MUST be SHARP and PHOTOREALISTIC.
- Main title must NOT overlap the person's face.
```

## ヒアリング変数の差し込み箇所

| 変数 | 差し込み先 |
|---|---|
| `{{セミナータイトル}}` | メインタイトル |
| `{{サブタイトル上}}` | トップバッジ内テキスト |
| `{{サブタイトル下}}` | バッジ下のサブコピー |
| `{{サポートコピー}}` | タイトル下のサポートコピー |
| `{{日時}}` | 下部パネルの大テキスト |
| `{{特典テキスト}}` | 下部パネルの小テキスト |
| メダルテキスト | **固定値「参加者限定豪華特典」**（変更要請があれば差し替え） |
| `{{人物}}`（参照画像） | references パラメータに追加 |
