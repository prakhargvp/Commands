#### hotweb : To Setup Your local-website in a one click using hotweb command.

<b>Examples 1:</b> To create a localhost website only with 1 argument 

Command : `hotweb {webSiteName}`

Default Directory Structure :  /var/www/sites/{WebSiteName}/public_html 

```bash
<b>user@system:~$</b> hotweb devl.local
Direcotry Structure Not exist: /var/www/sites/devl.local/public_html
Create(y/n): y
Directory Structure Created: /var/www/sites/devl.local/public_html
Virtual File Created: /etc/apache2/sites-available/devl.local.conf
[sudo] password for prakhar: 
Enabling site devl.local.
To activate the new configuration, you need to run:
  service apache2 reload
 * Reloading web server apache2    
user@system:~$
```

<b>Examples 2:</b> To create a localhost website with 2 argument 

Command : `hotweb {webSiteName} {DirectoryStructure}`


```bash
<b>user@system:~$</b> hotweb devl.local /var/www/sites/devl.local/public_html
Direcotry Structure Not exist: /var/www/sites/devl.local/public_html
Create(y/n): y
Directory Structure Created: /var/www/sites/devl.local/public_html
Virtual File Created: /etc/apache2/sites-available/devl.local.conf
Site devl.local already enabled
 * Reloading web server apache2                                                                                                 user@system:~$                * 
```

