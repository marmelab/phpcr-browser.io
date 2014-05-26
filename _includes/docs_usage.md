Add a VirtualHost to your Apache config (and add in it 'AllowEncodedSlashes On'), or use PHP 5.4 integrated webserver by calling:

```sh
$ php -S localhost:8000 -t web
```

You can now access the repository by browsing to http://localhost:8000/browser (or equivalent domain as configured in your virtual host).
