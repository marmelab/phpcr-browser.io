Create a `config/prod.yml` with the connection settings for the repositories you need to browse. For instance, to use the browser with a local instance of jackrabbit:

```yaml
phpcr_repositories:
    'My Jackrabbit Repository':
        factory: jackalope.jackrabbit
        parameters:
            jackalope.jackrabbit_uri: 'http://localhost:8080/server'
            credentials.username: admin
            credentials.password: admin
```

The `factory` setting is the type of PHPCR repository you want to browse. See available factories in [marmelab/phpcr-api/config/factories.yml](https://github.com/marmelab/phpcr-api/blob/master/config/factories.yml).

You can also copy the `config/prod.yml-dist` file as `config/prod.yml` to get this exact configuration.

Copy also the angular app config dist file :

```
cp web/assets/js/browser/config.js-dist web/assets/js/browser/config.js
```
