# web
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://52aomine.github.io/web/index.html$1 [R,L]
