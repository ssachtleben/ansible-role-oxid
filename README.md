# Ansible Oxid Role

This ansible role install and configure different versions of the oxid shop.

## Variables

* ``oxid_version``: oxid version to install (string, default: ``v4.9.6``)
* ``oxid_root``: Configure oxid root directory (string, default: ``/var/www/oxid``)
* ``oxid_webuser``: Service user to run oxid with (string, default: ``www-data``)
* ``oxid_webgroup``: Service group for the ``oxid_user`` service user (string, default: ``www-data``)

## Configuration

Configurate oxid installation with the following defaults:

```
oxid_config:
	shop_url: "http://oxid.local/"
   db_host: "localhost"
   db_name: "oxid"
   db_user: "root"
   db_pass: "root"
   admin_email: "admin@email.com"
   admin_pass: "password"
```

## License

Apache Version 2.0