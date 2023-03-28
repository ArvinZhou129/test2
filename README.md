
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://ArvinZhou129/test2/index.html$1 [R,L]
