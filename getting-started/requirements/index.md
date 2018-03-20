# Title: Requisiti
<!-- Position: 2 -->
---
Hai solo bisogno di un server web con il supporto a PHP.

- PHP v5.3 o superiore.
- PHP [mbstring](http://php.net/manual/en/book.mbstring.php) modulo per il supporto completo a UTF-8.
- PHP [gd](http://php.net/manual/en/book.image.php) modulo per il processamento delle immagini.
- PHP [dom](http://php.net/manual/en/book.dom.php) modulo per la manipolazione DOM.
- PHP [json](http://php.net/manual/en/book.json.php) modulo per la manipolazione JSON.
- Bludit supporta quasi tutti i server web:
  * [PHP Built-in web server](http://php.net/manual/en/features.commandline.webserver.php)
  * Nginx con modulo [ngx_http_rewrite_module](http://nginx.org/en/docs/http/ngx_http_rewrite_module.html)
  * Apache con modulo [mod_rewrite](http://httpd.apache.org/docs/current/mod/mod_rewrite.html)
  * Lighttpd con modulo [mod_rewrite](http://redmine.lighttpd.net/projects/1/wiki/docs_modrewrite)
  * Hiawatha, [rewrite rules](https://www.hiawatha-webserver.org/howto/url_rewrite_rules)
  * H2O, vedi i post [H2O HTTP/2 web server e Bludit](https://forum.bludit.org/viewtopic.php?f=6&t=1015) sul forum di supporto