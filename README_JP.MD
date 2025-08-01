# n8n-cloudflare-ddns-workflow
n8n cloudflare ddns workflow

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
