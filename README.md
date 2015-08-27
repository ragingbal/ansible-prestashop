[ ![Image](https://aplazame.com/static/img/banners/banner-728-white.png "Aplazame") ](https://aplazame.com "Aplazame")
Ansible role which installs and configures Prestashop

**Latest Prestashop version**

Prestashop 1.6.1.1

#### Dependencies

* MySql
* Nginx

#### Usage

```yaml
prestashop:
  nginx_site:
    server_name: prestashop.aplazame.com

  mysql_db:
    name: prestashop
    user: prestashop
    pass: "pass"
```

#### Default variables

```yaml
prestashop_version: 1.6.1.1
nginx_dir: /etc/nginx
```

## Help

**Have a question about Aplazame?**

Aplazame support team can help you get the answers you need about this plugin by email soporte@aplazame.com.
