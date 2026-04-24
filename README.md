# @mh_hairarrange リール一覧

[@mh_hairarrange](https://www.instagram.com/mh_hairarrange) に投稿されたリール 36 本をカテゴリ別に閲覧できる簡易ビューワです。

## 中身

- `index.html` — ビューワ (カテゴリフィルタ + カードクリックで全文キャプション)
- `reels.json` — リール36件のメタデータ (カテゴリ・名称・URL・サムネパス・キャプション)
- `thumbnails/` — 各リールのサムネ画像 (36枚)

## ローカルで見る

```bash
python3 -m http.server 8765
# → http://127.0.0.1:8765/
```
