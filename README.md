# Mysql role

Installs and configures mysql server.

## Required variables.

* mysql_ssl - weather to configure mysql with ssl connection.

## Optional variables

* mysql_ssl: Boolean - whether you wish to enable encrypotion.
* cert_directory - certificate directory where certificates should be placed. - refer to ssl role readme.
> You can then template key paths as ```{{ cert_directory }}/mysql.key```
* mysql_ssl_ca - path of the ca certificate.
* mysql_ssl_key - path of the ssl key to use
* mysql_ssl_cert - path of the ssl cert to use
