
# 署名ファイル作成
certbot certonly --webroot -w /var/www/html/ -d example.com -m example@example.com

# 署名更新
certbot renew

--dry-run
--force-renewal or --renew-by-default
--keep-until-expiring
