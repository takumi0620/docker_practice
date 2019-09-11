#MySQLイメージの取得
FROM mysql

#MySQLのrootアカウントにパスを設定
ENV MYSQL_ROOT_PASSWORD=password

#文字コードにutf8
CMD ["mysqld",\
"--character-set-server=utf8mb4","--collation-server=utf8mb4_unicode_ci"]

