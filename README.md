# config-apache2-redirect-specific-url
config apache2 redirect specific url
```


<VirtualHost *:80>
    ServerAdmin truongpq@meeyland.com
    DocumentRoot "/var/www/thuylv/public"
    Redirect /old-url https://meeyads.xyz/rcms

    ServerName dev1.meeyads.com
    ServerAlias meeyads.xyz www.meeyads.xyz
</VirtualHost>
```


restart apache2 
```
 service httpd restart

```
