# HP保守事業 デモサイト集

福祉・介護事業所向け「制作費0円・月額保守」営業用のリニューアル提案サイト。

| フォルダ | 対象 | 元サイト |
| --- | --- | --- |
| `liberta-ohfuna/` | リハビリ型デイサービス 大船西口（株式会社Liberta） | https://www.liberta-kanagawa.com/rihabiriday-ohfuna |

各サイトは `index.html` 1ファイル完結（CSS/JS インライン、外部依存は Google Fonts と Google マップ埋め込みのみ）。
ブラウザで直接開けば確認できます。

## 差し替えが必要な箇所
- `.ph` のプレースホルダー → 施設の実写真（`<img>`）に置き換え
- HTML内の「要確認」コメント箇所 → 事業所に確認して文言修正
- お問い合わせフォーム → 送信先（Formspree / Googleフォーム等）を接続
