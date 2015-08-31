[ ![Image](https://aplazame.com/static/img/banners/banner-728-white-ans.png "Aplazame") ](https://aplazame.com "Aplazame")
[Ansible](http://www.ansible.com/home) playbooks for deploying Prestashop

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

#### Aplazame Module

Start taking online payments through Aplazame's Payment Module!!

[https://github.com/aplazame/prestashop](https://github.com/aplazame/prestashop)

#### Live demo

This is the online demo for uses to test Aplazame and its features. 

[http://prestashop.aplazame.com](http://prestashop.aplazame.com)

#### Help

**Have a question about Aplazame?**

For any support request please drop us an email at [soporte.prestashop@aplazame.com](mailto:soporte.prestashop@aplazame.com?subject=Help me with the ansible).
