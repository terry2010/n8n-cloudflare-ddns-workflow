# n8n-cloudflare-ddns-workflow
n8n cloudflare ddns workflow

## Documentation / 文档 / ドキュメント

- 🇨🇳 [中文说明](README_CN.md)
- 🇺🇸 [English Guide](README_EN.md)
- 🇯🇵 [日本語ガイド](README_JP.md)

<img width="1540" height="455" alt="图片" src="https://github.com/user-attachments/assets/fe62c93f-8401-4189-8802-849f82e7ce80" />


## 以下のプレースホルダーを置き換えてください：

    YOUR_CLOUDFLARE_API_TOKEN - あなたのCloudflare APIトークン
    YOUR_ZONE_ID - あなたのドメインのゾーンID
    YOUR_DOMAIN_NAME - 更新する完全なドメイン名（例：ddns.example.com）

## 認証情報を取得：

    APIトークン：Cloudflareダッシュボード → マイプロフィール → APIトークン → トークンの作成（ゾーン:DNS:編集権限が必要）
    ゾーンID：ドメイン管理ページのサイドバーにあります

## 設定手順：

    JSON設定をインポート
    すべてのプレースホルダーを置き換え（「DNSレコード照会」と「DNSレコード更新」ノード内）
    ワークフローをテスト
    自動実行を有効化
