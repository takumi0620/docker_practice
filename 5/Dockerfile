# イメージを取得
FROM httpd

# ホストOSにあるindex.htmlをdocument rootに配置
COPY ./httpd/index.html /usr/local/apache2/htdocs/

# 編集したhttpd.confをapatcheのを上書く
COPY ./httpd/httpd.conf /usr/local/apache2/conf/httpd.conf

# Dockerに対して80番ポートを使用することを通知
EXPOSE 80