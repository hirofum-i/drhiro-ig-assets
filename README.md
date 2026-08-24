# drhiro-ig-assets

@moikumo のストーリーズ／投稿を Instagram Graph API で自動投稿するための**画像の公開置き場**。

Meta の `POST /me/media` はローカルファイルを受け付けず**公開URLしか使えない**ため、投稿予定の画像だけをここに置いて `raw.githubusercontent.com` の URL を渡している。

- 置き場: `img/YYYY-MM-DD/<name>.png`
- 生成元: `C:\workspace\scripts\instagram\publish_asset.py`
- ⚠ここに置いた時点で**誰でも見られる**。投稿予定の画像以外は置かない（下書き・社外秘・顧客情報は禁止）
