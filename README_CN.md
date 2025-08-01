# n8n-cloudflare-ddns-workflow
n8n cloudflare ddns workflow

<img width="1534" height="393" alt="图片" src="https://github.com/user-attachments/assets/90620f71-786d-4135-92ac-adfaa8182e7c" />


## 替换以下占位符：

    YOUR_CLOUDFLARE_API_TOKEN - 你的 Cloudflare API 令牌
    YOUR_ZONE_ID - 你域名的区域 ID
    YOUR_DOMAIN_NAME - 要更新的完整域名（如：ddns.example.com）

## 获取凭据：

    API 令牌：Cloudflare 控制台 → 我的个人资料 → API 令牌 → 创建令牌（需要区域:DNS:编辑权限）
    区域 ID：域名管理页面右侧边栏

## 配置步骤：

    导入 JSON 配置
    替换所有占位符（在"查询DNS记录"和"更新DNS记录"节点中）
    测试工作流
    激活自动运行
